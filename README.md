# Работа со рифтами
- в браузере шрифтов нет
- самые быстрые - системные
- ffss (font-family) -системныйф шрифт без засечек (arial, roboto)
- fsz (font-size) - 16px - базовый размер (100%, medium )
- fw (font-weight) - жирность (normal, bolt, 100-900)
- text-decoration: none;/* зачеркивание и т.д.*/
- конверторы шрифтов (https://transfonter.org/)
- иконочный шрифт (текстовый, т.е. inline)
  <head> ....
<script src="https://kit.fontawesome.com/02902f4142.js" crossorigin="anonymous"></script>
<link rel="stylesheet" href="css/main.css">
.....
</head>

 в нужном месте рисуем крестик в кружочке....
 <i class="fa-regular fa-circle-xmark my_icon_red"></i>

 в css
 .my_icon_red{
    font-size: 25px;
    color:red;
}
