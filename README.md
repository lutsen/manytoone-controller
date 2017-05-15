[<img src="https://cdn.rawgit.com/lutsen/lagan/master/lagan-logo.svg" width="100" alt="Lagan">](https://github.com/lutsen/lagan)

Lagan Many-to-one Property Controller
=====================================

 Controller for the Lagan many-to-one property.  
 Lets the user define a may-to-one relation between two content objects.
 
 The Manytoone property type controller enables a many-to-one relation between 2 Lagan models, as described here: http://redbeanphp.com/index.php?p=/many_to_one. The name of the property should be the name of the Lagan model this model can have a many-to-one relation with. For this to work properly the other model should have a one-to-many relation with this model. So in our example in the Lagan project the Lagan Crew model has a many-to-one relation with the Lagan Hoverkraft model, and the Lagan Hoverkraft model has a one-to-many relation with the Lagan Crew model.

A property type controller can contain a set, read, delete and options method. All methods are optional.

To be used with [Lagan](https://github.com/lutsen/lagan). Lagan lets you create flexible content objects with a simple class, and manage them with a web interface.

Lagan is a project of [Lútsen Stellingwerff](http://lutsen.land/) from [HoverKraft](http://www.hoverkraft.nl/).