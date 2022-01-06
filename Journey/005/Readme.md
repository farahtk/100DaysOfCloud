# Adding another API Method and LAmbda function

## Introduction
Today was more about adding Dynamo DB and adding lambda function connection, but ended up spending all time figuring out how to add another method in the API. 

## Use Case
Any RESTful API supports multiple http methods, including Get, Put, Post, Delete etc. I never thought adding another method is going to be so challenging in Lambda. I was not able to find any documentation about how to connect two methods to the same function and the differentiator of the methods inside the function. MAy be there is a documentation but it was not easier to find at the moment. 

## Cloud Research

Issues I faced today,
- Not able to figure out how to access the http method information inside the lambda function from the same API Resource but different methods. It involes the same lambda function. 
- One lambda fuunction connected to one API Resource and was able to authenticate correctly. Created another function and connected with another resource inside the same API but a different resource. It is failing on Authentication issue. 

## Try yourself
Nothing much to share today other than the repeat of the steps from yesterday. I am planning to enable the logas from Cloudwatch and see if Ia m able to find out the root cause. 

## ☁️ Cloud Outcome

Sometimes things are frustrating :D

## Next Steps

Hopefully Ic an find out the issue form logs OR by reaching out to the AWS cloud community :)

## Social Proof

[Twitch link](https://www.twitch.tv/videos/1254471569)
