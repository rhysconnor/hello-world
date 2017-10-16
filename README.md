<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Drop Down List Using HTML-CSS</title>
    <style type="text/css">
      nav {
        display: block;
        position: absolute;
        top: 0;
        width: 100%;
        background-color: #E6E6FA;
      }
      li {
        list-style-type: none;
        display: inline;
        margin-right: 20px;
        font-size: 25px;
      }
      a:link {
        text-decoration: none;
      }
      a:hover {
        color: white;
        text-decoration: none;
      }
      li>ul {
        display: none;
      }
      li:hover ul {
        display: block;
        position: absolute;
        left: 200px;
        background-color: #E6E6FA;
        margin: 0;
        padding-top: 30px;
      }
      li:hover ul li a:link {
        display: block;
        margin-left: 0;
        padding-right: 30px;
      }
    </style>
  </head>
  <body>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li>
          <a href="">Products</a>
          <ul>
            <li><a href="#">Engineering</a></li>
            <li><a href="#">Telecome</a></li>
            <li><a href="#">Energy</a></li>
            <li><a href="#">Finance</a></li>
            <li><a href="#">Consultancy</a></li>
          </ul>
        </li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </body>
</html>
