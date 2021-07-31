# Introduction
HTE(Html Template Exporter) a tool used for exporting an html file by
taking a static html with an unstatic section wich contains variables
and the program arguments which will be replaced with varibles in their
specific places.
# Running HTE
```
hte -i <TEXT-FILE> -t <TEMPLATE>
```
## Syntax of Text-file
```
#some-variable
content ...
....
some-variable#
....
```
## Syntax of Template
```
#define 
var-name type attributes
....
define#
#static 
....
....
....
#dynamic 
var-name
....
dynamic#
...
static#

