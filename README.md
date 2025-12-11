# data_engineer_
![SQLite Version](https://img.shields.io/badge/sqlite-3.32.3-blue)
![Python Version](https://img.shields.io/badge/python-3.8-blue)
## 📚 Описание проекта
Это проект по обучению профессия Data Engineer с нуля до junior на сайте stepik: https://stepik.org/lesson/893138/step/6?unit=898079
Тут будет информация как работать с БД, что такое CI/CD, olap, что такое DWH, озера данных hadoop, python.
В проект будут использоваться docker, postgresql, python, dbear.

## 🛠 Предварительные требования
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="20" height="20" /> **Docker Desktop** - [Скачать с официального сайта](https://www.docker.com/products/docker-desktop/)

## 📖 Установка/Документация.
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
1. Установите Docker
2. В docker разверните postgresql.
3. Создате базу данных и таблицы для работы.

## 💻 Использование
После проделанных действий, вы можете приступать к обучению, а также самостоятельно тренировать запросы, проекты связанные с dwh.
Работая с таблицами, создавая процедуру и вьюшки.

##Цели
Укрепить знания в области DS
Приобрести новые полезные навыки
Применять их в работе

### Примеры запросов к бд
#### 1.1 Создание таблицы
CREATE TABLE client
(
PRIMARY KEY id,
firs_name VARCHAR(30)
last_name VARCHAR (30)
);
#### 1.2 Запрос к таблицам(вывод иформации)
SELECT * FROM client; - вывод все информации по таблице

#### 1.3. Вставка данных в таблицу
INSERT INTO client (id, firs_name, last_name)
VALUES 
	(1, Alexei, Alexei),
	(2, Igor, Igor),
	(3, Misha, Misha);



