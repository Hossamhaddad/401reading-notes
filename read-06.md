# Inheritance and Interfaces

## Inheritance: is the mechanism in java by which one class is allowed to inherit the features of another class.

## The keyword used for inheritance is extends.

## Types of Inheritance :

1. ### Single Inheritance
2. ### Multilevel Inheritance
3. ### Hierarchical Inheritance
4. ### Multiple Inheritance
5. ### Hybrid Inheritance

## Inheritance Example :

### class Employee{

### float salary=40000;

### }

### class Programmer extends Employee{

### int bonus=10000;

### public static void main(String args[]){

### Programmer p=new Programmer();

### System.out.println("Programmer salary is:"+p.salary);

### System.out.println("Bonus of Programmer is:"+p.bonus);

### }

### }

## Interface: is a reference type in Java. It is similar to class. It is a collection of abstract methods.

## The interface body can contain :

1. ### abstract methods
2. ### default methods
3. ### static methods.

## Like abstract classes, interfaces cannot be used to create objects.

## Method Overriding is used to provide specific implementation of a method that is already provided by its super class.
