**University**: [ITMO University](https://itmo.ru/ru/)

**Faculty**: [FICT](https://fict.itmo.ru)

**Course**: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)

**Year**: 2026

**Group**: U4125
**Author**: Vasilev Anton
**Lab**: Lab3
**Date of create**: 16.03.2026
**Date of finished**: ?


- Создал папку prometheus и yml файл к ней с нужным содержимым
<img width="804" height="189" alt="Снимок экрана 2026-03-16 в 20 42 23" src="https://github.com/user-attachments/assets/a343c8ee-c415-4a3d-b595-c7135d20d93c" />

Запустил node explorer для трекинга метрик и проверил что он работает
<img width="1712" height="735" alt="Снимок экрана 2026-03-16 в 20 51 02" src="https://github.com/user-attachments/assets/15aac19c-6a9d-4186-99d6-02d227db0bd1" />

Создал нетворк мониторинг и том для хранения данных прометус
<img width="1780" height="252" alt="image" src="https://github.com/user-attachments/assets/369048d6-47cd-4941-9575-826327c3a4f6" />

Запустил контейнер прометус и открыл его в браузере 
<img width="1428" height="896" alt="image" src="https://github.com/user-attachments/assets/f0d6207c-4570-4123-b9a4-130e48f01aba" />
<img width="1722" height="941" alt="Снимок экрана 2026-03-16 в 20 57 17" src="https://github.com/user-attachments/assets/a547b0a0-a8b9-42e8-9da6-38b7c61ea896" />

- Сделал том для графаны и заранил ее 

<img width="1610" height="682" alt="image" src="https://github.com/user-attachments/assets/e99c0b0c-1107-4006-aa4f-6d85e3c7bc3f" />

Залогинился админ админ в дэшборд
<img width="1727" height="1043" alt="Снимок экрана 2026-03-16 в 20 59 03" src="https://github.com/user-attachments/assets/c7168414-dc89-4860-bbf7-d7a9a9f32211" />

Проверил что все контейнеры ранятся
<img width="2088" height="134" alt="image" src="https://github.com/user-attachments/assets/d70e5933-d75e-418b-85bc-2510e51d2e32" />

Добавил коннекшн для прометуса чтобы шли данные 

<img width="3440" height="1894" alt="image" src="https://github.com/user-attachments/assets/cb320be6-9456-46e2-b5db-ab8adbfd7201" />

Сделал run query и подтянул графики на cup мониторинг , проверил health в prometheus + добавил трекинг memory 

<img width="2394" height="1782" alt="image" src="https://github.com/user-attachments/assets/679bfa43-0ce5-48d8-a6d9-585526748467" />


