# ITproject
ПО необходимое для запуска скриптов, импорта БД:Python версии 3+, PostgreSQL, Jupyter Notebook.

Ссылка на скачивание Python:https://www.python.org/downloads/

Установка Jupyter Notebook осуществляется из cmd: 
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
Запуск Jupyter: jupyter notebook

Необходимые библиотеки (устанавливаются также запросами из cmd):
pip install WeasyPrint
pip install pyodbc
pip install psycopg2
pip install cairocffi
pip install sqlalchemy
pip install jinja2
pip install matplotlib
pip install pandas

Ссылка на установку PostgreSQL:https://www.postgresql.org/download/windows/
Прим: При установке PostgreSQL могут возникать ошибки вида - отказ в доступе, несовместимость ОС и installer, "error occured executing MS Visual installer". Для решения этих проблем нужно: 1) создать аккаунт с правами администратора, установить пароль, запустить .exe с этого аккаунта 2) убедиться в одинаковой разрядности PostgreSQL и MS Visual
После установки нужно настроить SQL сервер и сохранить данные для дальнейшего использования в коде при соединении БД с Python.

В случае, если вышеуказанные меры не помогают, можно настроить сервер альтернативным способом через установку MS SQL Server. Здесь все дефолтно. В этой ситуации следует самостоятельно развернуть готовую базу данных и продолжать работать с ней.

До запуска кода важно поместить данные (файлы base_prices.xlsx и bond_description.xlsx) в одну папку с файлом c расширением .ipynb.
Дальнейшие инструкции содержатся непосредственно в скриптах.
