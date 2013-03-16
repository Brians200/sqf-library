sqf-library
===========

Library with helpful reusable SQF code written by me.  
Each component can be used independently from other components, if not stated otherwise.  
The code is licensed under the MIT license (see LICENSE file).

Structure
-----------

Each folder is a simple mission that contains the code for the component.

- functions: contains all functions of the component.
- Description.ext: contains the declarations that will add the component to the missions function library.
- tests.sqf: tests for the component
- mission.sqm: simple test mission for the component.

How to use a component in your mission
-----------

Copy the functions folder of the component into your mission. Also copy the content of the Description.ext into your missions Description.ext.
To get information about the usage of the component, open your (or the component's) mission in the in-game editor. Now open the functions viewer (CTRL + F).
Select the missionConfigFile and you will see the component and all its functions each with a description and example usage.

Components
-----------

- Dictionary: A [dictionary (aka associative array, aka map)](http://en.wikipedia.org/wiki/Associative_array) type.
