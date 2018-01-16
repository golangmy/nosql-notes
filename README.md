# https://docs.mongodb.com/v3.4/reference/method/
```>mongod```<br/>
Start mongo server.<br/>
```>mongo```<br/>
Cmd for mongo<br/>
```>show dbs```<br/>
To show all database<br/>
```>use [dbname](user)```<br/>
Swich to dbname<br/>
```>show collections```<br/>
Show collection(table)<br/>
```>db.[table].find()```<br/>
Show all data in collection<br/>
```
>db.[table].find().pretty()
        "_id" : ObjectId("5a5e0ad89c9d5e65f2864cd9"),
        "name" : "Nyein Chan Aung",
        "age" : "12"
}
```   
Show all data in collection with json format<br/>
```>db.createCollection('[collectionName]')```<br/>
Create Collection<br/>
```>db.[table].insert({json})```   
```
db.[table].insert({
        "name": "Mg Mg Gyi",
        "age" : "23"
})
```
Insert data to collection   

```
db.[table].update({
        name : "Mg Mg Gyi"
        },
        { $set : {
                name: 'ford'
                }
         })
 ```   
Update name = 'ford' where name = "Mg Mg Gyi"   






