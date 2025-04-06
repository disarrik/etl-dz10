1. Создать кластер PG (бакет возьмем из предыдущей пратики)
![pg-create](create_pg.png)
2. Выполнить скрипт инициализации данных (скрипт init.sql в корне проекта)
![init](init.png)
3. Создать эндпоинт источник из ПГ 
![src-endoint](pg_endpoint.png)
4. Создать эндпоинт назначения в Object Storage
![dst-endoint](s3_endpoint.png)
5. Создать трансфер
![dt](datatransfer.png)
6. Скачать результат трансфера из Objecct Storage (положил csv тут в корень проекта)
![dt](result.png)
