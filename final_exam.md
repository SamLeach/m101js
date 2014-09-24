######Class started: Aug 12, 2014

######Note: MongoDB University change the answers slightly so please don't copy these answers

#####Question 1

###### Same question and answer as M101J

```javascript
"3"
```

#####Question 2

###### Same question and answer as M101J

```javascript
"susan.mara@enron.com to jeff.dasovich@enron.com"
```

#####Question 3

```javascript

###### Same question and answer as M101J except mrpotatohead@10gen.com is changed to mrpotatohead@mongodb.com

"vOnRg05kwcqyEFSve96R"

db.messages.update({"headers.Message-ID":"<8147308.1075851042335.JavaMail.evans@thyme>"},{$addToSet:{"headers.To":"mrpotatohead@mongodb.com"}})
```

#####Question 4

Add

```javascript
"VQ3jedFjG5VmElLTYKqS"
```

#####Question 5

###### Same question and answer as M101J

```javascript
"a_1_b_1"
"a_1_c_1"
"c_1"
"a_1_b_1_c_-1"
```

#####Question 6

###### Same question and answer as M101J

```javascript
"Remove all indexes from the collection, leaving only the index on _id in place"
"Set w=0, j=0 on writes"
```

#####Question 7

###### Same question but difference answer as M101J as MongoDB University changed the data

```javascript
44,822
```

#####Question 8

```javascript
"Maybe, it depends on whether Node 2 has processed the write"
```

#####Question 9

###### Same question and answer as M101J

```javascript
"patient_id"
```

#####Question 10

###### Same question and answer as M101J

```javascript
"The query did not utilize an index to figure out which documents match the find criteria."
"The query used an index for the sorting phase."
"The query performed a full collection scan."
```
