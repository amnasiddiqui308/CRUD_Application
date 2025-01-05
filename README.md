# CRUD_Application
A CPP CRUD Application that uses it's own syntax for queries and parses each query using tokenization. Data is stored in a CSV File.

Syntax:

Create Query Syntax:
C-rollno='NNiNNNN',name='amna',age=21,maths=32,science=90,computer=90,english=90;

Retrieve Query Syntax:
R-rollno='NNiNNNN';

Update Query Suntax:
U-rollno='NNiNNNN',rollno='NNiNNNN';

Delete Query Syntax:
D-rollno='NNiNNNN';

In these queries, N can be any number from 0-9 and you can use any field from maths, science, computer and english in place of rollno accordingly.
