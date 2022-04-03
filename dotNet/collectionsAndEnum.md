# Collections  & enumeration
I’ll summarise what I read in a Quiz form.

## There are two ways to manage groups of related objects, mention them.
1.	We can create arrays of objects
2.	We can Also create collections of objects.



## What are the differences between Arrays and collections? When do we use each one of them?
We use arrays when we want to work with fixed number of strongly typed objects.

As for collections they are suitable if you want a flexible way to work with groups of objects, because collections allow the groups of objects to grow and shrink dynamically.

## what is the usage of a key?
In some collections we can assign keys to objects so that we can retrieve them quickly.



## Can we instantiate Collections? 
Yes, since Collections are classes so we must declare instances of them before adding elements to them.



## give some kinds of collections.
-	System.Collections.Generic classes
-	System.Collections.Concurrent classes
-	System.Collections classes



## When do we use System.Collections.Generic classes?
If all the elements in a collection are from the same type and we don’ t want other types to be added to this collection.



## when do we use System.Collections.Concurrent classes?
We use the classes of System.Collections.Concurrent instead of the other collections whenever there are multiple threads accessing the collection concurrently.



## how do System.Collections classes store objects?
They don’t store specifically typed objects. Instead, they store objects as type Object.



## which classes are more preferred to use?
We should the collections in of System.Collections.Concurrent and System.Collections.Generic whenever possible because the types in System.Collections are legacy.


## what can we use LINQ for?
It can be used for accessing collections.


## what are other uses for LINQ?
Its queries provide grouping, filtering and ordering capabilities.



## What is an enumeration type?
It is a value type that’s defined by a group of constants of the integral numeric type.

## how do we define an enumeration type?
By using the keyword enum then specifying the enum members’ names.

## what is the default type of enum members?
They are of type int.

## can we define a method inside an enumeration type? If no then how can we add functionality to it?
No we cannot but if we want to add functionality to an enumeration type we can create an extension method.

## what is System.Enum type?
It is the abstract base class for all enumeration types.
 
         



