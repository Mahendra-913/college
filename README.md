# college

GRANT ALL PRIVILEGES ON your_database.* TO 'new_username'@'localhost';
CREATE TABLE user (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(255) NOT NULL,
    mobile_no VARCHAR(15) NOT NULL,
    address VARCHAR(255) NOT NULL
);
