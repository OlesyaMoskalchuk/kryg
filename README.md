# kryg
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>РиоДеЖанейро.</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<!--
Подключаем API карт 2.x
       Параметры:
        - load=package.full - полная сборка;
        - lang=ru-RU - язык русский.
        -->
<script src="http://api-maps.yandex.ru/2.0/?load=package.full&lang=ru-RU"
type="text/javascript"></script>
<script type="text/javascript">
        ymaps.ready(init);
        function init() {
var myMap = new ymaps.Map('map', {
        center: [-22.912154, -43.175009],
        zoom: 8
     }),
      myCircle = new ymaps.Circle([
        [-22.91, -43.17],
         15000
          ]);
         myMap.geoObjects.add(myCircle);
         }
</script>
</head>
<body>

<h2>РиоДеЖанейро</h2>
<div id="map" style="width:600px;height:400px"></div>
</body>
</html>
