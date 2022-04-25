# Data Transfer Objects 
## what is a data transfer object?
A Data Transfer Object (DTO) is an object of a POCO (plain old CLR object) class that specifies how data will be delivered across the network.

## why do we need data transfer objects?
we need it to change the shape of the data that we send to client.

## give some examples on how can we use DTO?

-	Hide specific properties from clients who aren't supposed to see them.

-	Get rid of any circular references.

-	Reduce the size of the payload by omitting some attributes.

-	To abstract the domain objects of an application from the user interface or the presentation layer.
