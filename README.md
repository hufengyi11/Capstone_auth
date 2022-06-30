1. create database on Postgres called registration => app_user table and confirmation_token

2. use Lombok to auto generate getters, setters and constructors using annotation

3. changed port to 3500 in application.yml

4. create model for user

5. security config (override http; configure)

6. Predicate

    1. Represents a predicate (boolean-valued function) of one argument.

       This is a [functional interface](https://docs.oracle.com/javase/8/docs/api/java/util/function/package-summary.html) whose functional method is [`test(Object)`](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html#test-T-).

7. token

8. create model for confirm token and join column with user_id

9. Email service using javamail

10. https://github.com/maildev/maildev

11. launch maildev: http://0.0.0.0:1080
