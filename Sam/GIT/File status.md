## File status
- Зафиксированное (committed) состояние означает, что данные надежно сохранены в локальной базе.
- Модифицированное (modified) состояние означает, что изменения уже внесены в файл, но пока не зафиксированы в базе данных. 
- Индексированное (staged) состояние означает, что вы пометили текущую версию модифицированного файла как предназначенную для следующей фиксации.

Папка Git — это место, где Git хранит метаданные и объектную базу данных проекта. Это наиболее важная часть Git, которая копируется при дублировании репозитория (хранилища) с другого компьютера.

Область индексирования — это файл, обычно находящийся в папке Git и хранящий информацию о том, что именно войдет в следующую операцию фиксации. Иногда её еще называют промежуточной областью.

Рабочая папка — это место, куда выполняется выгрузка одной из версий проекта. Эти файлы извлекаются из сжатой базы данных в папке Git и помещаются на жесткий диск вашего компьютера, готовые к использованию или редактированию.