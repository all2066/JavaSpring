# Java Spring Course
### Table of contents
* [Introduction](#introduction) 
* [Technologies](#technologies)
* [Commands](#commands)
* [Syntax](#syntax)
* [Illustrations](#illustrations)


## Introduction
The Spring Framework is an open-source application framework that provides infrastructure support for developing Java applications. One of the most popular Java Enterprise Edition frameworks, Spring helps developers create high performing applications using plain old Java objects (POJOs).

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
* IntelliJ IDEA 2021
* Spring
* MySQL 
* Postman

## Commands
##### JPA
| Annotation | Description                    |
| ------------- | ------------------------------ |
| `@Entity`      | Declares the class as an entity or a table.       |
| `@Table`   | Declares table name.    | 
| `@Basic`   | Specifies non-constraint fields explicitly.     | 
| `@Embedded`   | Specifies the properties of class or an entity whose value is an instance of an embeddable class.     | 
| `@Id`   | Specifies the property, use for identity (primary key of a table) of the class.     | 
| `@Column`   | Specifies the column attribute for the persistence property.     | 
| `@ManyToMany`   | Defines a many-to-many relationship between the join Tables.     | 
| `@ManyToOne`   | Defines a many-to-one relationship between the join Tables.     | 
| `@OneToMany `   | Defines a one-to-many relationship between the join Tables.     | 

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

