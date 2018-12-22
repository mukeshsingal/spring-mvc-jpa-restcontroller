### Introduction

This Spring MVC project exposes below Rest APIs.

|Type|Root|Description|
|---|---|---|
|GET|/topics|get all the topics avaiable|
|GET|/topics/{id}|get topic with metioned `id` the topics avaiable|
|POST|/topics/|create new topic(mention content in POST body in json)|
|PUT|/topics/{id}|update exisitng topic(mention content in POST body in json)|
|DELETE|/topics/{id}|delete topic with metioned id|
|GET|/topics/{id}/courses|get all the courses avaiable under topic with metioned id|
|GET|/topics/{id}/courses/{courseId}|get specific course under methioned topic|
|POST|/topics/{id}/courses|create new course under metioned topic|
|PUT|/topics/{id}/courses/{courseId}|update course under metioned topic|
|DELETE|/topics/{id}/courses/{courseId}|delete course from metioned topic|

### Package 
Run `mvn clean install`
This command create a jar file in taget folder.

### Run 
Use `java -jar $jarName` 
It will start application at http://localhost:8081/

