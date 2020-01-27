# JSON-task
Creating a table from JSON

●	На основе имеющегося массива данных создать таблицу 
●	Колонки в таблице: 
  ○	Идентификатор (id)
  ○	Имя (name.first), 
  ○	Фамилия (name.last), 
  ○	Пол (gender),
  ○	Ключевые фразы (memo).
  ○	Изображение (img)
●	Необходимо реализоватеь некий управляющий элемент вне таблицы для фильтрации строк таблицы по подстроке с выделением найденных фрагментов текста в таблице
●	Должна присутствовать возможность настройки видимости колонок
●	Показ массива mеmo – с разбиением по строкам
●	При клике на строку во всплывающем div (стилистика модального окна) отобразить форму редактирования данных выбранной строки (изображение – только показ, редактор мемо может быть обычным многострочным текстом с отображением строка-элемент массива). 

Дополнительные цели:
●	Добавить постраничный вывод данных из предоставленного JSON (10 строк на страницу);
●	Добавить возможность фильтрации по конкретной колонке. Общий фильтр и колоночные работают совместно по AND.

