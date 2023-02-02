## 单引号
   MySQL里引用字符串时需要用一对英文单引号或英文双引号将字符串常量括起来。例如：
``
'an apple'
"a book"
``
需要字符串内包含单引号：  

1,使用转义  
2,双引号将字符串括起来，这样字符串内的单引号被视作普通字符。  
``
select "Johnson's mother", 'Johnson''s mother', 'Johnson\'s mother';
``

## 双引号

   需要字符串包含双引号：  
1,单引号将字符串括起来，这样字符串内的双引号被视作普通字符。  
``
select 'He said: "Go away"' ,"He said: ""Go away""" ,"He said: \"Go away\"" ;
``