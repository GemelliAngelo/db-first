# USED CARS

| name              | type        | attributes                          | key     |
| ----------------- | ----------- | ----------------------------------- | ------- |
| id                | SMALLINT    | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |
| plate             | CHAR(7)     | NOT NULL - UNIQUE                   |         |
| brand             | VARCHAR(30) | NOT NULL                            |         |
| model             | VARCHAR(30) | NOT NULL                            |         |
| power             | TINYINT     | NOT NULL - UNSIGNED                 |         |
| fuel              | CHAR(1)     | NOT NULL                            |         |
| mileage           | INT         | NOT NULL - DEFAULT(0) - UNSIGNED    |         |
| conditions_code   | CHAR(1)     | NOT NULL                            |         |
| owners_number     | TINYINT     | NOT NULL - DEFAULT(1) - UNSIGNED    |         |
| registration_date | YEAR        | NULL                                |         |
