# SQL_Event_Scheduler
MySQL 事件觸發器


    CREATE EVENT < event_name >
        ON SCHEDULE < EVERY 1 DAY STARTS CURRENT_TIMESTAMP >
        DO 
           DELETE FROM `mytable` WHERE `publish_date` /*Event Body*/
