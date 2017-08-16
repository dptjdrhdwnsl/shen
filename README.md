# shen
[Spring]shoppingmall category, 쇼핑몰 분류관리
Hi, this is categorization program. Here's SQL for oracle creating a table

create table category_table(
    category_no number not null,
    subclass_no number not null,
    category_name varchar2(30),
    primary key(category_no, subclass_no)
    );
    
    
    
    
