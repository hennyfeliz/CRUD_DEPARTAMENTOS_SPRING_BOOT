create database department_db;

use department_db;

CREATE TABLE `department` (
    `department_id` int(11) NOT NULL AUTO_INCREMENT,
    `department_address` varchar(200) NOT NULL,
    `department_code` varchar(45) NOT NULL,
    `department_name` varchar(45) NOT NULL,
    PRIMARY KEY (`department_id`)
);

DROP DATABASE department_db;

SELECT * FROM department;

INSERT INTO department (department_id, department_address, department_code, department_name)
VALUES (1, '91428931', '293 westhood st', 'Ritch department');

INSERT INTO department (department_id, department_address, department_code, department_name)
VALUES (2, '4812392', '923 clowford av', 'Roberts department');

INSERT INTO department (department_id, department_address, department_code, department_name)
VALUES (3, '5471232', '8512 jhonsons st', 'Enriques department');