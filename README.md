# Описание курса "Интеллектуальные базы данных" для магистров направлений 09.04.01 МТУСИ.

## Структура курса:
1. Реляционные БД

    1.1. OLTP, PostgreSQL
    - [Документация PostgreSQL](https://www.postgresql.org/docs/)
    - [PostGIS](https://postgis.net/)
   
    1.2. OLAP, Clickhouse
    - [Документация Clickhouse](https://clickhouse.tech/docs/ru/)
2. NoSQL подходы

    2.1. In-Memory DB. Memcached, Redis
    - [Документация Memcached](https://github.com/memcached/memcached/wiki)
    - [Документация Redis](https://redis.io/documentation)
    - Сравнения Memcached vs Redis: [Amazom](https://aws.amazon.com/elasticache/redis-vs-memcached/), 
      [Oracle](https://oracle-patches.com/common/3143-redis-%D0%B8%D0%BB%D0%B8-memcached,-%D1%87%D1%82%D0%BE-%D0%BB%D1%83%D1%87%D1%88%D0%B5-%D0%B4%D0%BB%D1%8F-%D0%BA%D1%8D%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F),
      [Классный комментарий на SO](https://stackoverflow.com/a/11257333),
      [Статья на imaginarycloud.com](https://www.imaginarycloud.com/blog/redis-vs-memcached/)
      
    2.2. Документоориентированные БД. MongoDB
    - [Драйверы к разным языкам](https://docs.mongodb.com/drivers/)
    - [Полезные гайды](https://docs.mongodb.com/guides/)
    
    2.3. Объектные хранилища. S3
    - Поставщики S3 и S3-совместимых хранилищ: [Amazon](https://aws.amazon.com/ru/s3/),
      [Mail](https://mcs.mail.ru/storage/?utm_source=google_dial-cloudstorage-rf&utm_medium=cpc&utm_campaign=storage.adap.114117079392.g.11688684425&utm_content=adap.481799632045&utm_term=amazon%20s3&placement=&adposition=&matchtype=b&device=c&gclid=Cj0KCQiAx9mABhD0ARIsAEfpavQLW33C4pH05Ym88J6m7tyE_ymERzOkKU-hmtBVb6jHHnDJXW65FdMaAmP_EALw_wcB),
      [MTC](https://cloud.mts.ru/services/s3object/), [Yandex](https://cloud.yandex.ru/docs/storage/)
    - [Общий FAQ по S3](https://aws.amazon.com/ru/s3/faqs/)
    
    2.4. Распределенные системы. Cassandra
    - [Документация Cassandra](https://cassandra.apache.org/doc/latest/)
    
    2.5. Брокеры сообщений. RabbitMQ, SQS, Kafka
    - [Документация RabbitMQ](https://www.rabbitmq.com/documentation.html)
    - [Документация SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
    - [Документация Kafka](https://kafka.apache.org/documentation/)

3. Масштабирование

    3.1. Мониторинг нагрузки. Grafana
    - [Документация Grafana](https://grafana.com/docs/)
    
    3.2. Репликация
    
    3.3. Шардирование