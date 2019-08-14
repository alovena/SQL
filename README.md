# 2018-12-15
- ( + Create Database )
*Query : CREATE DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;  
- ( + Update Database )  
*Query : ALTER DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
- ( + Create Table ) 
*Query : create table Stock_Register(id bigint(20) unsigned not null AUTO_INCREMENT,</br>
                            store_name varchar(255) not null,</br>
                            user_name varchar(255) not null,</br>
                            user_id varchar(255) not null,</br>
                            user_pwd varchar(255) not null,</br>
                            PRIMARY key(id)</br>
                            )DEFAULT CHARSET=utf8 COLLATE=utf8_general_ci;</br>
                           
- ( + Insert data in Table )
*Query : insert into Stock_Register values("명동점","이한울","a","a")

# 2019-08-13
- ( + Inner Join)

<blockquote>
  I tried to use Inner join first time,</br>
  It extracts data with the same column values</br>
  <h5>(In my case buycomment.idx == buylist.id)</h5>
</blockquote>
*Query : select * bcl.idx,bcl.userID,bcl.comment,bl.id</br>
from buycommentList as bcl</br>
join buylist as bl</br>
on(where) bl.id=bcl.idx and bcl.idx='$idx';

