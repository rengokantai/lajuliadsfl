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








###7 Macros
ex:
```
ex=quote x=2 end
```
eval it:
```
eval(ex)
```
return 2.  
then we can call the constructor explicitly
```
ex = Expr(:call, print, :hello:)
eval(ex)
```

modify args
```
ex.args[2]="world"
eval(ex)
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
