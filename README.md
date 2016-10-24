# lajuliadsfl
##1. The Central Content
###3 Types
####01:14
add gadfly plotting lib, in juliabox
```
Pkg.add('Gadfly')
```
import:
```
using Gadfly
```

###8 Calling C, Python, and R
```
Pkg.add('PyCall')
```
then
```
@pyimport urllib
```
```
page=urllib.urlopen("http://")
```
methods are accessed using a symbol instead of the usual dot.
```
content = page[:readlines]()
page
```
