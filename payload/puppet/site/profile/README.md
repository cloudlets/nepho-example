profile
=======

Using the [Puppet Roles and Profiles](http://www.craigdunn.org/2012/05/239/) design pattern, this module defines profiles that can be combined into roles for application to nodes.

Profiles:
* Define logical technology stacks
* Provide an area to add cross-module functionality such as resource chaining
* Allow modules to remain granular and secular

We achieve maximal separation by using Hiera and Puppet 3's parameter binding to define almost all parameter configuration.
