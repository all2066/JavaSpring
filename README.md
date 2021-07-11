# Java Spring Course
### Table of contents
* [Introduction](#introduction) 
* [Technologies](#technologies)
* [Commands](#commands)
* [Syntax](#syntax)
* [Illustrations](#illustrations)


## Introduction
In this course we practice with Spring, 

#### Main topics of this project:
* Classes 
* Objects
* Properties
* Methods
* Abstraction
* Polymorphism
* Inheritance 
* Encapsulation

## Technologies
* Java 11
* Spring
* MySQL 
* Postman

## Commands


## Syntax
#### To Define a Class
##### Java
```
class Person{
String name=””;
void walk(){}
}
```
##### Python
```
class Person:
name=””;
def walk():
```
##### JavaScript
```
Person.prototype.walk ) function(){
}
```
##### PHP
```
class Person{
$name=””;
function walk(){}
}
```
************************************
#### Constructor Method
##### Java
```
public Person(String name){
this.name=name;
}
```
##### JavaScript
```
function Person(name){
this.name=name
}
```

##### PHP
```
public function __construct($name){
$this->name=name;
}
```
##### Python
```
def __int__(self,name):
self.name=name
```

************************************
#### Getters & Setters example in java
```
public Integer getPassenger()
    {
        return passenger;
    }
    public void setPassenger(Integer passenger)
    {
        if(passenger==4){
            this.passenger = passenger;
        }else{
            System.out.println("Necesitas asignar 4 pasajeros");
        }
    }

```


## Illustrations

Creating app with Spring Initializr
![](images/1.jpg)
**************************************
Project structure
![](images/2.jpg)
**************************************
Postman practice
![](images/3.jpg)
**************************************
How JWT(JSON Web Tokens) works
![](images/4.jpg)

