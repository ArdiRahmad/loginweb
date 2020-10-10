//Database query
CREATE TABLE 'users' (
  'userName' varchar(100) NOT NULL,
  'userPassword' varchar(100) NOT NULL,
  'admintoken' varchar(100) NOT NULL,
  PRIMARY KEY ('userName')  
)

INSERT INTO `buku` (`userName`, `userPassword`, `admintoken`) VALUES
('oda', '1234', '111111');
