<h1 align="center">Тестовое задание для стажера на позицию
«Разработчик JS» в компании Infotecs </h1>
<p> <a href='https://elenalenivtseva.github.io/tableApp/'>Сайт<a/> на github pages указан в информации о проекте. Дополнительно проект выложен на Netify <a href='https://tabletasttest.netlify.app/'>тут</a> </p>

<h3>Общее задание</h3>
<p>Необходимо разработать приложение, которое отображает таблицу с информацией о
пользователях, с возможностью поиска по всей таблице. В таблице должны быть следующие
колонки: ФИО, возраст, пол, номер телефона и адрес (город и название улицы).</p>

<h3>Что удалось реализовать</h3>
<ul>
  <li>Выполнены основные цели:
    <ul>
      <li>Реализована таблица (использован запрос на <a href='https://dummyjson.com/users'>https://dummyjson.com/users</a>).</li>
      <li>Таблица имеет ограничение по ширине (100% от ширины экрана, но не более 1200px)</li>
      <li>Реализован поиск по таблице (использован запрос на <a href='https://dummyjson.com/users/filter'>https://dummyjson.com/users</a>)</li>
      <li>Для запросов использовался fetch</li>
    </ul>
  </li>
  <li>Выполнены дополнительные цели:
    <ul>
      <li>Добавлена возможность регулирования ширины колонок (минимальный размер столбца 50px, но его также можно регулировать. К значениям, не поместившимся по ширине, добавляется "...")</li>
      <li>Реализовано модальное окно при ДВОЙНОМ клике на пользователя. В модальном окне отображается дополнительня информация о пользователе</li>
      <li>Сделана обработка ошибок при работе с запросами на dummyjson. Если возникает ошибка, сообщение о ней и информация отображается на экране</li>
      <li>Реализована сортировка при ДВОЙНОМ клике на столбцы: name, age, gender, address. Как было сказано в ТЗ, для phone сортировка не нужна. Сортировка происходит по убыванию и по возрастанию. Отмену сортировки реализовать не получилось. Т.е. сделано 2 из 3.</li>
    </ul>
  </li>
</ul>
<h6>Примечания</h6>
<ul>
  <li>Все на английском, т.к. данные с dummyjson на английском. Также в ТЗ было сказано, что первый столбец - ФИО. Однако в объектах, предлагаемых dummyjson, свойства, отвечающего за отчество, обнаружено не было. </li>
<li>Мне не нравится архитектура приложения. Я вижу свои ошибки (пусть не все, но все же), но пока не знаю, что с ними делать. Я работала с Redux, мне немного знаком FLUX. Но попытка создать свой Redux в приложении (useContext+useReducer), ухудшило приложение. К сожалению, я пока не имею опыта в построении архитектуры. Я сделала вывод, что пора изучать и пробывать различные архитектурные паттерны. Уже начала. </li>
</ul>
