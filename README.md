# Список поддерживаемых функций:
<ul>
  <li>загрузка файла в хранилище с перезаписью помощью метода PUT;</li>  
  <li>получение файла из хранилища с помощью метода GET;</li>
<li>получение списка файлов каталога с помощью метода GET (в качестве формата данных для ответа рекомендуется использовать JSON);</li>
<li>получение информации о файле в виде HTTP-заголовков без получения содержимого файла с помощью метода HEAD;</li>
  <li>удаление файла/каталога из хранилища с помощью метода DELETE.</li>
  
  <li>Реализована функция копирования файлов в новое расположение.
Пример API :
PUT http://storage.com/path/to/file.txt с установленным заголовком COPYFROM: /path/toanother/file2.txt для копирования файла  </li>
  
</ul>
<h2> При реализации использовался веб-фреймворк, реализующий HTTP-роутинг и работу с HTTP-вызовами.</h2>
