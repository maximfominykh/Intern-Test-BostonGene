# Intern-Test-BostonGene
Test task for internship in BostonGene
# Часть 1. Многопоточность
Вам нужно реализовать многопоточное приложение на языке Java 8.
Условия:
 в приложение должно быть реализовано два потока:
первый поток считывает введённые с клавиатуры числительные на английском языке
(от one до nine thousand nine hundred ninety nine) и помещает их в память,
второй поток обращается к памяти один раз в пять секунд, извлекает (удаляет его из
памяти) самое маленькое из записанных чисел и выводит его на экран;
 задачу запрещается решать с помощью потокобезопасных коллекций как из стандартного пакета,
так и от сторонних разработчиков.
# Часть 2. Spring user service
В компании «А» возникла потребность в хранении и управлении учетными записями
пользователей (добавление, удаление и поиск по email). Задача по реализации данных
потребностей выпала Вам. Необходимо реализовать REST сервис, отвечающий следующим
требованиям:
 данные пользователя, которые будут храниться: Фамилия, Имя, Дата рождения, email и
пароль;
 пароль пользователя должен храниться в безопасной форме;
 использовать InMemory реализацию базы данных (т.е. хранить данные в памяти);
 приложение необходимо реализовать на одном из языков: Java 8, Groovy или Kotlin с
использованием Spring Boot;
 наличие примеров запросов к сервису (например, curl).
# Часть 3. Yandex translate API
У Яндекс переводчика (translate.yandex.ru) имеется REST API. Необходимо реализовать консольное
приложение на одном из языков Java8, Groovy или Kotlin, которое переводит введенную
английскую фразу на русский язык, пользуясь предложенным API.
