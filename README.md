# java-chameleon
Автоматизация тест-кейсов с помощью Chameleon
- [AddProductWeb](https://github.com/Salimgareev/java-chameleon/blob/efdd7cd2214f32f57b14a07f90fe6a8ed233649f/src/test/resources/features/AddProductWeb.feature) сценарий с параметрами успешного добавления товара в таблицу через веб-интерфейс
- [AddProductToDatabase](https://github.com/Salimgareev/java-chameleon/blob/efdd7cd2214f32f57b14a07f90fe6a8ed233649f/src/test/resources/features/AddProductToDatabase.feature) сценарий успешного добавления товара в таблицу через БД
- `mvn clean test` - удалить файлы предыдущего билда и запустить тесты
- `mvn allure:report` - отчет будет сгенерирован во временную папку
- `mvn clean test allure:report` - чистка, запуск тестов и генерация отчета
- Открыть сгенерированный отчет можно через плагин Chameleon, нажав "Показать отчет" на вкладке плагина