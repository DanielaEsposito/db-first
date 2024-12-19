# Used Cars Table

| NAME                | Type           | Key     | ATTRIBUTE                         | NOTE                                             |
| ------------------- | -------------- | ------- | --------------------------------- | ------------------------------------------------ |
| id                  | BIGINT(20)     | PRIMARY | NOT NULL - AUTOINCREMENT UNSIGNED |
| model               | VARCHAR(50)    |         | NOT NULL                          |
| make                | VARCHAR(50)    |         | NOT NULL                          |
| year                | YEAR           |         | NOT NULL                          |
| mileage             | INT            |         | NOT NULL                          |
| price               | DECIMAL(10, 2) |         | NOT NULL                          |
| fuel_type           | VARCHAR(20)    |         | NOT NULL                          |
| color               | VARCHAR(20)    |         | NULL                              |
| registration_number | VARCHAR(15)    |         | NULL                              |
| condition           | CHAR(1)        |         | NULL                              | "A" for excellent, "B" for good, "C" for average |
