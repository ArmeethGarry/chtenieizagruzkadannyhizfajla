# Внешняя обработка для работы с файлами
С помощью данной обработки можно загрузить данные из файла, в формате TXT, CSV, XLS(XLSX), DBF и XML

Реалезованны следующие возможности.
1. С помощью процедур (ПутьКФайлуНачалоВыбора и ПослеВыбораФайла) и тумблера ФорматФайла пользователь имеет возможность отфильтровать
   файлы по типу (TXT, CSV. XLS, DBF и XML). После чего в реквизите ПутьКФайлу подставляется полный путь до нужного файла.
2. Для чтения различных типов файлов создано 6 Процедур: ПрочитатьФайлTXT, ПрочитатьФайлCSV, ПрочитатьФайлXLS, ПрочитатьФайлXLSНаСрвере,
   ПрочитатьФайлDBF, ПрочитатьФайлXML.
3. Процедура ПрочитатьФайлTXT: реализована с помощью последовательного чтения файла (Объект <ТекстовыйДокумент>). Данный способ больше
   подходит для чтения небольших текстовых файлов.