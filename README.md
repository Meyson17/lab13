
<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №12 <br>
по курсу «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"PHP"</b><p>
<p align="right"><b>Выполнил: </b> студент 231 группы Рыжков Владимир</p>
<p  align="right"><b>Принял: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p align="justify">PHP — язык программирования, который наиболее распространён в сфере веб-разработки.
В настоящее время PHP является одним из лидеров среди серверных языков программирования, применяющихся для создания динамических веб-сайтов и веб-приложений. Большая часть коробочных систем управления сайтами написана именно на PHP, язык поддерживается подавляющим большинством хостинг-провайдеров, Язык получил широкое распространение благодаря своей простоте, скорости, мультипарадигмальности, богатой функциональности и кроссплатформенности.
</p>

<h2>Задачи:</h2>
Спросите город пользователя с помощью формы. Результат запишите в переменную $city. Выведите на экран фразу 'Ваш город: %Город%'. 

Решите предыдущую задачу так, чтобы пользователь не мог вводить теги и сломать сайт. 

Сделайте так, чтобы форма после отправки скрывалась. 

Спросите имя пользователя с помощью формы. Результат запишите в переменную $name. Выведите на экран фразу 'Привет, %Имя%'. 

Спросите у пользователя имя, возраст, а также попросите его ввести сообщение (его сделайте в textarea). Выведите эти данные на экран в формате, приведенном под данной задачей. Позаботьтесь о том, чтобы пользователь не мог вводить теги (просто удаляйте их) и таким образом сломать сайт. 

Спросите возраст пользователя. Если форма была отправлена и введен возраст, то выведите его на экран, а форму уберите. Если же форма не была отправлена (это будет при первом заходе на страницу) - просто покажите ее. 

Спросите у пользователя логин и пароль (в браузере должен быть звездочками). Сравните их с логином $login и паролем $pass, хранящихся в файле. Если все верно - выведите 'Доступ разрешен!', в противном случае - 'Доступ запрещен!'. Сделайте так, чтобы скрипт обрезал концевые пробелы в строках, которые ввел пользователь. 

Спросите имя пользователя с помощью формы. Результат запишите в переменную $name. Сделайте так, чтобы после отправки формы значения ее полей не пропадали. 

Спросите у пользователя имя, а также попросите его ввести сообщение (textarea). Сделайте так, чтобы после отправки формы значения его полей не пропадали. 

Дана строка 'ahb acb aeb aeeb adcb axeb'. Напишите регулярку, которая найдет строки ahb, acb, aeb по шаблону: буква 'a', любой символ, буква 'b'. 

Дана строка 'aba aca aea abba adca abea'. Напишите регулярку, которая найдет строки abba adca abea по шаблону: буква 'a', 2 любых символа, буква 'a'. 

Дана строка 'aba aca aea abba adca abea'. Напишите регулярку, которая найдет строки abba и abea, не захватив adca. Дана строка 'aa aba abba abbba abca abea'. Напишите регулярку, которая найдет строки aba, abba, abbba по шаблону: буква 'a', буква 'b' любое количество раз, буква 'a'.  

 Дана строка 'aa aba abba abbba abca abea'. Напишите регулярку, которая найдет строки aa, aba, abba, abbba по шаблону: буква 'a', буква 'b' любое количество раз (в том числе ниодного раза), буква 'a'.  

 Дана строка 'aa aba abba abbba abca abea'. Напишите регулярку, которая найдет строки aa, aba по шаблону: буква 'a', буква 'b' один раз или ниодного, буква 'a'.  

Дана строка 'ab abab abab abababab abea'. Напишите регулярку, которая найдет строки по шаблону: строка 'ab' повторяется 1 или более раз.  

Дана строка 'a.a aba aea'. Напишите регулярку, которая найдет строку a.a, не захватив остальные.  

 Дана строка '2+3 223 2223'. Напишите регулярку, которая найдет строку 2+3, не захватив остальные.  

 Дана строка '23 2+3 2++3 2+++3 345 567'. Напишите регулярку, которая найдет строки 2+3, 2++3, 2+++3, не захватив остальные (+ может быть любое количество).  

 Дана строка '23 2+3 2++3 2+++3 445 677'. Напишите регулярку, которая найдет строки 23, 2+3, 2++3, 2+++3, не захватив остальные.  

 Дана строка '*+ *q+ *qq+ *qqq+ *qqq qqq+'. Напишите регулярку, которая найдет строки *q+, *qq+, *qqq+, не захватив остальные.  

 Дана строка '*+ *q+ *qq+ *qqq+ *qqq qqq+'. Напишите регулярку, которая найдет строки *+, *q+, *qq+, *qqq+, не захватив остальные.  

Дана строка 'aba accca azzza wwwwa'. Напишите регулярку, которая найдет все строки по краям которых стоят буквы 'a', и заменит каждую из них на '!'. Между буквами a может быть любой символ (кроме a).  

<h2>Решение задач:</h2>

<h3>Задания 1-3</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №1-3</title>
<meta charset="utf-8">
</head>
<body>
<?php
if (empty($_POST['city'])){
?>
<form action="" method="POST">
 <p>Ваш город: <input type="text" name="city" /></p>
 <p><input type="submit" /></p>
</form>
<?php
}
?>
<?php
if (!empty($_POST['city'])){
$city = strip_tags($_POST["city"]);
echo "Ваш город: " . $city;
}
?>
</body>
</html>
```
<h3>Задания 4-5</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №4,5</title>
<meta charset="utf-8">
</head>
<body>
<form action="" method="POST">
 <p>Ваше имя: <input type="text" name="name" /></p>
 <p>Ваш возраст: <input type="text" name="age" /></p>
 <p>Ваше сообщение: <textarea name="message" /></textarea></p>
 <p><input type="submit" /></p>
</form>
<?php
if (!empty($_POST['name'])){
$name = strip_tags($_POST["name"]);
$age = strip_tags($_POST["age"]);
$message = strip_tags($_POST["message"]);
echo "Привет, $name, тебе $age лет <br>";
echo "Твоё сообщение: $message";
}
?>
</body>
</html>
```

<h3>Задание6 </h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №6</title>
<meta charset="utf-8">
</head>
<body>
<?php
if (empty($_POST['age'])){
?>
<form action="" method="POST"> 
 <p>Ваш возраст: <input type="text" name="age" /></p>
 <p><input type="submit" /></p>
</form>
<?php
}
?>
<?php
if (!empty($_POST['age'])){
$age = strip_tags($_POST["age"]);
echo "Привет, тебе $age лет";
}
?>
</body>
</html>
```

<h3>Задание7</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №7</title>
<meta charset="utf-8">
</head>
<body>
<form action="" method="POST">
 <p>Логин: <input type="text" name="login" /></p>
 <p>Пароль: <input type="password" name="passwd" /></p>
 <p><input type="submit" /></p>
</form>
<?php
$login = "student";
$password = "qwerty";
if (!empty($_POST['login'])){
$userLogin = strip_tags($_POST["login"]);
$userPassword = strip_tags($_POST["passwd"]);
$userLogin = trim($userLogin);
$userPassword = trim($userPassword);
if($login==$userLogin & $password==$userPassword)
echo "Доступ разрешен!";
else echo "Доступ запрещён!";
}
?>
</body>
</html>
```

<h3>Задание8</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №8</title>
<meta charset="utf-8">
</head>
<body>
<form action="" method="POST">
 <p>Ваше имя: <input type="text" name="name" value = "<?php 
 if (!empty($_POST['name'])) echo $_POST['name']; ?>"></p> 
 <p><input type="submit" ></p>
</form>
<?php
if (!empty($_POST['name'])){
$name = strip_tags($_POST["name"]);
echo "Привет, $name";
}
?>
</body>
</html>
```

<h3>Задание9</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №9</title>
<meta charset="utf-8">
</head>
<body>
<form action="" method="POST">
 <p>Ваше имя: <input type="text" name="name" value = "<?php 
 if (!empty($_POST['name'])) echo $_POST['name']; ?>"/></p>
 <p>Ваше сообщение: <textarea name="message" /><?php 
 if (!empty($_POST['message'])) echo $_POST['message']; ?></textarea></p>
 <p><input type="submit" /></p>
</form>

<?php
if (!empty($_POST['name'])){
$name = strip_tags($_POST["name"]);
$message = strip_tags($_POST["message"]);
echo "Привет, $name!<br>";
echo "Твоё сообщение: $message";
}
?>
</body>
</html>
```

<h3>Задание 10</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №10</title>
<meta charset="utf-8">
</head>
<body>
<?php
$str = 'ahb acb aeb aeeb adcb axeb';
$regexp = '/a[a-z]b/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 11</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №11</title>
<meta charset="utf-8">
</head>
<body>
<?php
$str = 'aba aca aea abba adca abea';
$regexp = '/a..a/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 12</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №12</title>
<meta charset="utf-8">
</head>
<?php
$str = 'aba aca aea abba adca abea';
$regexp = '/ab[^d]a/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 13</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №13</title>
<meta charset="utf-8">
</head>
<?php
$str = 'aa aba abba abbba abca abea';
$regexp = '/ab+a/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 14</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №14</title>
<meta charset="utf-8">
</head>
<?php
$str = 'aa aba abba abbba abca abea';
$regexp = '/ab*a/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 15</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №15</title>
<meta charset="utf-8">
</head>
<?php
$str = 'aa aba abba abbba abca abea';
$regexp = '/ab?a/';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 16</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №16</title>
<meta charset="utf-8">
</head>
<?php
$str = 'ab abab abab abababab abea';
$regexp = '#(ab)+#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 17</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №17</title>
<meta charset="utf-8">
</head>
<?php
$str = 'a.a aba aea';
$regexp = '#a[.]a#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 18</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №18/title>
<meta charset="utf-8">
</head>
<?php
$str = '2+3 223 2223';
$regexp = '#2\\+3#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 19</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №119</title>
<meta charset="utf-8">
</head>
<?php
$str = '23 2+3 2++3 2+++3 345 567';
$regexp = '#2[+]+3#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 20</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №20</title>
<meta charset="utf-8">
</head>
<?php
$str = '23 2+3 2++3 2+++3 445 677';
$regexp = '#2[+]*3#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 21</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №21</title>
<meta charset="utf-8">
</head>
<?php
$str = '*+ *q+ *qq+ *qqq+ *qqq qqq+';
$regexp = '#[*]q+[+]#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 22</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №22</title>
<meta charset="utf-8">
</head>
<?php
$str = '*+ *q+ *qq+ *qqq+ *qqq qqq+';
$regexp = '#[*]q*[+]#';
preg_match_all($regexp,$str,$res);
print_r($res);
?>
</body>
</html>
```

<h3>Задание 23</h3>

```php
<!DOCTYPE html>
<html>
<head>
<title>Лабораторная работа №13 №23</title>
<meta charset="utf-8">
</head>
<?php
$str = 'aba accca azzza wwwwa';
$regexp = '/a[^a]+a/';
$delimiter='!';
echo preg_replace($regexp,$delimiter,$str);
?>
</body>
</html>
```

<h2>Вывод</h2>
<p>В результате выполнения лабораторной работы были изучены элементы языка PHP, выполнены все цели и задачи.</p>  
