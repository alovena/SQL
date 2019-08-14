데이터베이스 생성
CREATE DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
데이터베이스 수정
ALTER DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
테이블 생성
create table Stock_Register(id bigint(20) unsigned not null AUTO_INCREMENT,
                            store_name varchar(255) not null,
                            user_name varchar(255) not null,
                            user_id varchar(255) not null,
                            user_pwd varchar(255) not null,
                            PRIMARY key(id)          
                           )DEFAULT CHARSET=utf8 COLLATE=utf8_general_ci;
                           
테이블 정보 삽입 insert into Stock_Register values("명동점","이한울","a","a")

내부조인 select * bcl.idx,bcl.userID,bcl.comment,bl.id
from buycommentList as bcl
join buylist as bl
on(where) bl.id=bcl.idx and bcl.idx='$idx';
