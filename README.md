
# 📘 MDK-11.02 — Учебная практика УП.11 «Конфигурирование и программирование в 1С»
## 🏫 Информационная система «Школьное управление»

MDK 11.02 (междисциплинарный курс) является частью профессионального модуля PM.11 в рамках специальности среднего профессионального образования **09.02.07 «Информационные системы и программирование»**.

---

# 🇷🇺 RU — Информационная система «Школьное управление»

## 📑 Оглавление
- [Описание проекта](#-описание-проекта)
- [Функциональные роли](#-функциональные-роли)
- [Подсистемы](#-подсистемы)
- [Справочники](#-справочники)
- [Документы](#-документы)
- [Отчеты](#-отчеты)
- [Регистры](#-регистры)
- [Календарь и расписание](#-календарь-и-расписание)
- [Импорт данных](#-импорт-данных)
- [ERD-диаграмма](#-erd-диаграмма)
- [Используемые технологии](#-используемые-технологии)
- [Цели учебной практики](#-цели-учебной-практики)
- [Запуск проекта](#-запуск-проекта)
- [Контакты](#-контакты)

---

## 📖 Описание проекта
Данный репозиторий содержит реализацию учебной информационной системы для автоматизации процессов в общеобразовательной школе.  
Система разработана в среде **1С:Предприятие**, включает основные объекты конфигурации и демонстрирует навыки конфигурирования, работы с данными, построения отчетов и организации ролевого доступа.

---

## 👥 Функциональные роли
- **Директор** — административный контроль, доступ к подсистеме «Администрирование».  
- **Завуч** — работа с расписанием, успеваемостью, образовательным процессом.  
- **Учитель** — ведение успеваемости, просмотр расписания, работа с учениками.  

Каждая роль имеет собственный рабочий стол.

---

## 🧭 Подсистемы
- **Образование** — расписание, учебные дни, успеваемость, ученики.  
- **Администрирование** — сотрудники, должности, пользователи, настройки.  

---

## 🗂️ Справочники
- 👦 Ученики  
- 🏫 Классы  
- 📚 Предметы  
- 👨‍🏫 Сотрудники  
- 🗂️ Должности *(импорт из файла)*  
- 🔐 Пользователи  

Один из справочников содержит изображение.

---

## 📄 Документы
- **Учебный день (расписание)**  
- **Успеваемость по предметам**  

Один документ имеет печатную форму (xlsx / txt / doc).

---

## 📊 Отчеты
- **Отчет по успеваемости** — формируется на основе регистра накопления.

---

## 📦 Регистры
### Регистр накопления
- **Успеваемость** — хранит данные по ученикам, предметам, расписанию и оценкам.

---

## 🗓️ Календарь и расписание
Реализовано отображение:

- расписания занятий,  
- учебных дней,  
- календаря.  

---

## 📥 Импорт данных
Справочники (например, «Должности») заполняются через импорт Excel/CSV.

---

## 🧱 ERD-диаграмма
Диаграмма включает:

- сущности,  
- связи,  
- атрибуты.  

Файл расположен в `/docs`.

---

## 🛠️ Используемые технологии
- **1C:Enterprise 8.3**  
- **MS Visio** (ERD)  
- **1C Query Language**  
- **Excel/CSV Import**  
- **GitHub Documentation**  

---

## 🎯 Цели учебной практики
1. Разработка ERD-диаграммы.  
2. Создание сущностей ИС.  
3. Импорт данных.  
4. Авторизация и роли.  
5. Планировщик расписания.  
6. Изображения в справочниках.  
7. Автоматический расчет итогов.  
8. Печатные формы.  
9. Регистр накопления и отчеты.  
10. Презентация проекта.  

---

## 🚀 Запуск проекта
1. Открыть конфигурацию в **1С:Предприятие**.  
2. Запустить в режиме предприятия.  
3. Войти под ролью: директор / завуч / учитель.

---

## 📞 Контакты
**Автор:** 1angelina-bez4  
**Email:** angelina_bezzrukovvva@bk.ru  

---

# 🇬🇧 EN — Information System “School Management”

## 📑 Table of Contents
- [Project Description](#-project-description)
- [User Roles](#-user-roles)
- [Subsystems](#-subsystems)
- [Directories](#-directories-reference-catalogs)
- [Documents](#-documents)
- [Reports](#-reports)
- [Registers](#-registers)
- [Calendar and Schedule](#-calendar-and-schedule)
- [Data Import](#-data-import)
- [ERD Diagram](#-erd-diagram)
- [Technologies Used](#-technologies-used)
- [Practice Goals](#-practice-goals)
- [Project Launch](#-project-launch)
- [Contacts](#-contacts-1)

---

## 📖 Project Description
This repository contains an educational information system designed to automate processes in a general education school.  
Developed in **1C:Enterprise**, it includes key configuration objects and demonstrates skills in configuration, data processing, reporting, and role-based access.

---

## 👥 User Roles
- **Director** — administrative control, access to “Administration”.  
- **Deputy Director (Head Teacher)** — schedules, performance, educational processes.  
- **Teacher** — grading, schedule viewing, student management.  

---

## 🧭 Subsystems
- **Education** — schedules, school days, performance, students.  
- **Administration** — employees, positions, users, settings.  

---

## 🗂️ Directories (Reference Catalogs)
- 👦 Students  
- 🏫 Classes  
- 📚 Subjects  
- 👨‍🏫 Employees  
- 🗂️ Positions *(file import)*  
- 🔐 Users  

One directory contains an image.

---

## 📄 Documents
- **School Day (Schedule)**  
- **Subject Performance**  

One document includes a printable form.

---

## 📊 Reports
- **Performance Report** — based on the accumulation register.

---

## 📦 Registers
### Accumulation Register
- **Performance** — stores students, subjects, schedules, grades.

---

## 🗓️ Calendar and Schedule
Includes:

- class schedule,  
- school days,  
- calendar view.  

---

## 📥 Data Import
Directories can be filled via Excel/CSV import.

---

## 🧱 ERD Diagram
Includes entities, relations, attributes.  
Located in `/docs`.

---

## 🛠️ Technologies Used
- **1C:Enterprise 8.3**  
- **MS Visio**  
- **1C Query Language**  
- **Excel/CSV Import**  
- **GitHub Documentation**  

---

## 🎯 Practice Goals
1. ERD diagram creation.  
2. IS entities development.  
3. Data import.  
4. Authorization and roles.  
5. Schedule planner.  
6. Images in directories.  
7. Automatic totals calculation.  
8. Printable forms.  
9. Accumulation register and reports.  
10. Project presentation.  

---

## 🚀 Project Launch
1. Open in **1C:Enterprise**.  
2. Run in enterprise mode.  
3. Log in as director / deputy director / teacher.

---

## 📞 Contacts
**Author:** 1angelina-bez4  
**Email:** angelina_bezzrukovvva@bk.ru  
