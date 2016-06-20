# User-Defined-Graphics-UDG-Utilities
A set of procedures to manage and create UDGs (user defined graphics) for PSION Organiser II


**Note:** all this tools work on an array named **UDGBUF%(*256*)** holding 32 UDGs declared **GLOBAL** in a scope above first usage.

* 2016-06-13: Added **UDGZOOM:(N%)** procedure (**Used by EDITUDG:**)<br> ... and by anyone who wants to **zoom 2-fold into an UDG**

* 2016-06-20: Added **EDITUDG:** procedure (**Used by UDGMAN:**).<br>Allows to edit the 32 UDGs loaded into UDGBUF%() by UDGMAN:


