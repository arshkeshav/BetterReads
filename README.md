# BetterReads
Scope: Building a book tracker app

#### System Design

-Performant, Handle large data, Reliability, Backend focus

#### Technologies

-Html5(UI), Springboot(mvc and security), Apache Cassandra(database), OpenLib Search API(for search)


##### Cassandra Schema design

Book: date,id,name,desc,cover---read by(n-n)---User:id,name
|
written by(n-n)
|
Author: id,name,img.



