#####Homework 4.1

```javascript
db.products.find({'brand':"GE"}).sort({price:1})
db.products.find({$and:[{price:{$gt:30}},{price:{$lt:50}}]}).sort({brand:1})
```

#####Homework 4.2

```javascript
"This query performs a collection scan."
"The query uses an index to determine the order in which to return result documents."
"The query visits 46462 documents."
```

#####Homework 4.3

```javascript
"dOiP6E1JDOYwDKWP0uN3"
```

#####Homework 4.4

```javascript
15820
```
