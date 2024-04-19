# college

GRANT ALL PRIVILEGES ON your_database.* TO 'new_username'@'localhost';
CREATE TABLE user (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL,
    mobile_no VARCHAR(15) NOT NULL,
    address VARCHAR(255) NOT NULL
);



SELECT user, host FROM mysql.user;




GRANT ALL PRIVILEGES ON your_database.* TO 'new_username'@'localhost';


USE your_database;

CREATE TABLE your_table (
    id INT AUTO_INCREMENT PRIMARY KEY,
    column1 VARCHAR(255),
    column2 INT,
    column3 TEXT
);
