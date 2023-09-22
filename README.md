# test_task_sql

В таблице sql_test_personell содержится список сотрудников компании.
Таблица содержит следующие поля:

pers_id                    - уникальный номер сотрудника\
department_id              - уникальный номер подразделения, в котором работает сотрудник\
chief_id                   - id руководителя для данного сотрудника\
pers_name                  - ФИО сотрудника\
pers_salary number         - оклад сотрудика в месяц, тыс. руб.\
pers_bd date               - дата рождения сотрудника\
gender                     - пол сотрудника

В таблице sql_test_department содержится список отделов компании:

department_id                 - идентификатор подразделения\
department_name               - наименование подразделения\
department_head               - идентификатор сотрудника - главы отдела

В таблице sql_test_address содержится юридический адрес компании, разбитый по столбцам.
