## This is an add-in for [Fody](https://github.com/Fody/Fody/) 

![Icon](https://raw.github.com/Fody/Unsealed/master/Icons/package_icon.png)

An addin for Fody to unseal sealed types. The most obvious usage of this is when working with F# records and an ORM like Entity Framework or NHibernate. Or if you want to create a dynamic proxy. 
    All of the previously listed scenarios require you in some cases to have an object can be proxied, requiring virtual properties which aren't possible when a type is sealed.

## Nuget 

Nuget package http://nuget.org/packages/Unsealed.Fody 

To Install from the Nuget Package Manager Console 
    
    PM> Install-Package Unsealed.Fody
	

## Icon

Icon designed by Simon Keating, courtesy of [The Noun Project](http://thenounproject.com)

