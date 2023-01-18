#### A-1)
```Create Table employee(
	id SERIAL Primary KEY,
	name VARCHAR(50) NOT NULL,
	email VARCHAR(100),
	birthday DATE
);```

#### A-2)
`insert into employee (name, email, birthday) values ('Millie Januszkiewicz', 'mjanuszkiewicz29@ehow.com', '1951-08-12');`

#### A-3)
```Update employee
Set name = 'Name Surname',
email = 'name@hotmail.com',
birthday = '2000-05-15'
Where id IN(1,2,3,4,5);```

#### A-4)
```Delete From employee
Where id IN(1,2,3,4,5);```
