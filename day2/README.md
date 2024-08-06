# fine tuning GPT foundation model 

### high level methods for fine tuning 

<img src="m1.png">

###  to fine tune any model we have to supply 2 things at bare minimum 

- data
- parameters

<img src="data1.png">

### parameters 

<img src="para1.png">


### model parameters

<img src="model1.png">

### overall understanding 

<img src="ud.png">

## GPT things 

### model release understanding 

<img src="mud.png">



### model to fine tune

<img src="m123.png">

### data message format 

```
# data model format for GPT 
# ROle specific 
# we have to prepara training data with few examples  
# single sample data 1 data of example 
{
    "messages": [
        { "role": "system" , "content": "my hotel bot which is helping customer untill they are not satified" },
        { "role": "user" , "content": "i can't find wifi password" },
        { "role": "assistant" , "content": "hey sorry for inconvience but wifi passsword you have to just ask at reception" }
    ],
    "messages": [
        { "role": "system" , "content": "my hotel bot which is helping customer untill they are not satified" },
        { "role": "user" , "content": "i need to order food where is the menu " },
        { "role": "assistant" , "content": "there must be a table in you room check there else please call 9 extension" }
    ]
}
```

