-- QUESTION 1
DROP INDEX idxPhone ON customers;

-- QUESTION 2
CREATE USER 'bob'@'localhost' IDENTIFIED BY 'S$cu3r3!';

-- QUESTION 3
INSERT GRANT ALL ON salesDB.* TO 'bob'@'localhost';

-- QUESTION 4
ALTER USER 'bob'@'localhost' IDENTIFIED BY 'P$55!23';
