# Halley's method
This can solve any equation of the form ax^z+bx+c=0 where z is positive using [Halley's method](https://en.wikipedia.org/wiki/Halley%27s_method)  
See also: https://github.com/qwertpi/newtons-method  
PRs to make the input to python function process are more robust are very welcome, autograd can then be used for automatic differentation of the python function
## Example valid equation inputs
5x^2+2x-3  
5x^2-2x-3  
5x^2-2x+3  
-5x^2+2x-3  
0x^2+5x-100  
1x^2+0x-20  
## Example invalid euqation inputs
x^2+5x+2 - there must be an a term (at the moment!)  
1x^-1+5x+2 - no negative powers (at the moment!)  
1x^3+1x^2+2 - too many terms (at the moment!)  

