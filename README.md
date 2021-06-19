# analytics_skillbox

`courses.csv` содержит следующие значения:
`id` – идентификатор курса
`title` – название курса
`field` – сфера, к которой относится курс

`students.csv` содержит следующие значения:
`id` – идентификатор студента
`city` – город студента
`birthday` – день рождения студента

`course_contents.csv` содержит следующие значения:
`course_id` – идентификатор курса
`module_number` – номер модуля
`module_title` – название модуля
`lesson_number` – номер урока
`lesson_title` – название урока
`lesson_token` – токен урока
`is_video` – наличие видео *(true/false)*
`is_homework` – наличие домашней работы *(true/false)*

`progresses.csv` содержит следующие значения: 
`id` – идентификатор прогресса
`student_id` – идентификатор студента
 `course_id` – идентификатор курса
 
`progress_phases.csv` содержит следующие значения:
`progress_id` – идентификатор прогресса
`module_number` – номер модуля
`lesson_number` – номер урока
`status` – статус прохождения урока
`start_date` – дата начала
`finish_date` – дата окончания
