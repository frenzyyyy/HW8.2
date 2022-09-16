Group vars

 - Версия clickhouse 22.3.3.44
 - Паветы , которые будем устанавливать : 
  
        - clickhouse-client
        - clickhouse-server
        - clickhouse-common-static

Описание Play

 - Get clickhouse distrib : 

        Скачивание дистрибутивов clickhouse
 - Install clickhouse packages :
 
        Установка дистрибутивов Clickhouse
 - Start clickhouse service : 

        Запуск Handler Start clickhouse service
 - Get vector distrib :

        Скачивание дистрибутива vector
 - Get libs1 distrib :

        Скачивание пакета gcc10-libstdc++-10.2.1-7.gf.el7.x86_64.rpm для работы vector
 - Install lib1 package :

        Установка пакета gcc10-libstdc++-10.2.1-7.gf.el7.x86_64.rpm
 - Get libs2 distrib :

        Скачивание пакета  glibc-2.17-317.el7.x86_64.rpm для vector
 - Install lib2 package :

        Установка пакета glibc-2.17-317.el7.x86_64.rpm
 - Install vector package :
 
        Установка пакета vector
 - Create database :

        Подключение к серверу vector и создание бд