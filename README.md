# telegramBot
Рабочая версия TelegramLongPollingBot (на Spring Boot) с минимальным количеством кода.

Если в ходе компиляции проекта возникают ошибки, то в первую очередь проверьте:
1. Что в качестве профиля запуска проекта (в IDEA) выбран "Spring Boot", а не "Application";
2. Также проверьте, что нигде над названием класса не проставлена спринг-аннотация @Component;
3. Работоспособность проекта проверял на Java 11, пробовал указывать версию 8 (в Project Structure), но начало падать кучу ошибок;
3.1 Получилось запустить на Java 8, только на JDK8 скаченной с Oracle.
