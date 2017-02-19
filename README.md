<h1>SQLAlchemy-Python</h1>
Python tool project 

<h2>Motivation:</h2>

Building a strong database backend has become a very common task for programmers. It has not been an easy task to write raw SQL statements, run them and store the results as an array of records. This method has not only been tedious but prone to various errors. However, programmers today can write Object-Relational Mapping (ORM) programs to avoid this outdated method of using data from databases when using any object-oriented programming language. ORM is a programming technique that converts data between incompatible systems in object-oriented programming languages. The SQLAlchemy library takes part in solving this problem many programmers have faced in the past while using Python. SQLAlchemy’s ORM includes a method of relating user-defined Python classes with database tables as well as instances of those classes with rows in their corresponding tables. This library is similar to sqlite3 in some things; however, SQLAlchemy’s code is distinguishable as it is more object-oriented and easier to read and keep. Besides, one can easily create, read, update and delete SQLAlchemy objects as if they were normal Python objects. We believe this library would bring upon our classmates and us an additional set of skills to simplify our tasks when working with databases, which is why it is important for all of us to know about it so that we can use our time more efficiently.

SQLAlchemy is used by organizations such as:
 
-Yelp!
-The OpenStack Project
-Reddit
-Mozilla
-Survey Monkey
-FreshBooks
-Fedora Project

<h2> Context: </h2>

Various other libraries are similar to SQLAlchemy. Python has various other ORM libraries which are alternatives to SQLAlchemy. Some other libraries include SQLObject, Storm, Django ORM, peewee and PonyORM. 

<b>SQLObject</b> presents some advantages like how it has adopted the ActiveRecord pattern and it has a relatively small codebase. However, this library also follows Java’s ‘camelCase’ style to name objects and it does not support database sessions to isolate units of work.

On the other hand, the <b>Storm</b> library presents a clean and lightweight API, which leads to short learning curve and long-term maintainability. In addition, it does not require special class constructors or imperative base classes. However, it also has some disadvantages like forcing the programmer to write manual table-creation DDL statements instead of deriving them automatically from the model class. Besides, the library’s contributors have to give their contributions’ copyrights to Canonical Ltd. 

<b>Django’s ORM</b> is easy to use and has a short learning curve. It is also closely integrated with Django, which makes it easier to revert the code to its prior state when dealing with databases using Django. On the other hand, this library does not handle complex queries too well, which sometimes means the developer has to go back to using raw SQL. In addition, due to its tightness with Django, it is hard to use is outside of a Django context. 

The library <b>peewee</b> is similar to Django, which makes it easy to use. It also has a lightweight implementation, which makes it easy to integrate with web frameworks. However, it does not support automatic schema migrations or many-to-many queries, as this are not intuitive to write. 

<b>PonyORM</b> contains a very convenient syntax to write queries; it has automatic query automation and has simplified setup and usage. However, it is not designed to process thousands or millions of records simultaneously, which is unappealing when dealing with big data.

As mentioned before, <b>SQLAlchemy</b> has a flexible design, which makes it easy to write complex queries. It also has enterprise-levels APIs, which makes the code adaptable and strong. However, this library has a heavyweight API, this leads to a long learning curve. In addition, the unit-of-work concept the library uses is not common. 

Therefore, compared to what other libraries have to offer, SQLAlchemy stands out because of its focus on the unit-of-work concept. This is prevalent when writing SQLAlchemy code. The DBSession concept is hard to initially understand and use; however, the complexity comes out helpful at the end because it reduces accidental database committing related bugs to almost zero. 
