# 데이터베이스 생성  
CREATE DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;  
# 데이터베이스 수정  

ALTER DATABASE 데이타베이스_이름 DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;
# 테이블 생성 
create table Stock_Register(id bigint(20) unsigned not null AUTO_INCREMENT,
                            store_name varchar(255) not null,
                            user_name varchar(255) not null,
                            user_id varchar(255) not null,
                            user_pwd varchar(255) not null,
                            PRIMARY key(id)          
                           )DEFAULT CHARSET=utf8 COLLATE=utf8_general_ci;
                           
# 테이블 정보 삽입 
insert into Stock_Register values("명동점","이한울","a","a")

# 내부조인 

select * bcl.idx,bcl.userID,bcl.comment,bl.id
from buycommentList as bcl
join buylist as bl
on(where) bl.id=bcl.idx and bcl.idx='$idx';
# Android-Network
Android <-> Network communication code

# 2019-04-08
- ( + Insert.java ) 
- ( + Update.java ) 
- ( + Delete.java ) 
<blockquote>
Simple Client and Server communication In Android Using Asyntask<br>
first time,<br>
I tried to connect my hosting Server<br>
</blockquote>

<h3>Insert</h3>
Post data transfer to serverl<br>
*Query : Insert mTable to values(name1,name2..)

<h3>Update</h3>
Post data transfer to server<br>
*Query : Delete mTable where if...

<h3>Select</h3>
Post data transfer to server<br>
*Query : Select * from mTable 

# 2019-07-13
- ( + XmlTask.java ) 
<blockquote>
Simple Client Server communication In Android Using Asyntask<br>

I added it to the Xmlparsing code to find the API
</blockquote>

