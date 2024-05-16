# HW
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <title>Document</title>
    <style>
        .bg_color{
            background: linear-gradient(to top, blanchedalmond, rgb(106, 230, 143));
        }
        .smal{
            font-size: xx-small;
        }
        .normal{
            font-size: medium;
        }
        .large{
            font-size: x-large;
        }
    </style>
    <script language = "javascript">
        arrColor = ["0", "1", "2", "3", "4", "5", "6", "7", "8", "9", "a", "b", "c", "d", "e", "f"];
        function mouseOut() {
          for (i = 0; i < 13; i++)
            setTimeout ('document.blinkbutton.button.style.background = "#'+arrColor[15-i]+'0'+arrColor[15-i]+'FFF";', i * 50);
        }
        function mouseOver() {
          for (i = 0; i < 15; i++)
            setTimeout ('document.blinkbutton.button.style.background = "#'+arrColor[i]+'0'+arrColor[i]+'F31";', i * 50);
        }
        </script>
</head>
<body class="bg_color">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Панель навигации</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Переключатель навигации">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="Практика.html">Главная</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="Практика copy.html">Помощь</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Поиск" aria-label="Поиск">
              <button class="btn btn-outline-success" type="submit">Поиск</button>
            </form>
          </div>
        </div>
      </nav>
    <div>
        <h1 align="center">Заголовок</h1>
    </div>
    <div>
        <img src="C:\Users\Анастасия\Desktop\HTML\Без названия.jpg">
        <form name = "blinkbutton">
            <input type="button" name="button" value=" Наведи мышку " onMouseOver='mouseOver()' onMouseOut='mouseOut()' style="background-color: #1400FF">
          </form>
    </div>
    <div align="center">
        <i>Подвал</i>
    </div>
</body>
</html>
