# transitiontojulia
## Purpose
Get familiar with Julia by translating commonly used programming languages to Julia.
### Programming languages supported:

* Matlab
* Java
* Numpy

####Matlab
| Action     | Matlab           | Julia  |
| :------------- |:-------------| :-----|
|Save file|`save 'file.mat'`|  |
|Load file|`save 'file.mat'`| |
|Quick help|`save 'file.mat'`|  |
|Define or change variable|| |
||`x = 3`| `x = 3`|
||`x = [1 2 3]`| `x = [1,2,3]`|
||`x = [1 2 3];`| |
||`x = [1;2;3]`| |
||`A = [1 2 3 4;5 6 7 8;9 10 11 12];`| |
||`x(2) = 7`|`x[2] = 7` |
||`A(2,1) = 0`| `A[2,1] = 0`|
|Arithmetic and functions of numbers:|| |
||`3*4, 7+4, 2-6, 8/3`| `3*4, 7+4, 2-6, 8/3`|
||`3^7, 3^(8+2i)`|`3^7, 3^(8+2im)` |
||`sqrt(-5)`| `sqrt(-5+0im)`|
||`exp(12)`| `exp(12)`|
||`log(3), log10(100)`|`log(3), log10(100)` |
||`abs(-5)`|`abs(-5)` |
||`sin(5*pi/3)`|`sin(5pi/3)` |
|||`besselj(2,6)` |


####Python
| Action     | Numpy          | Julia  |
| ------------- |:-------------| :-----|
|Arithmetic|| |
||`a=1`| |
||`a + b` or `add(a,b)`| |
||`a - b` or `subtract(a,b)`| |
||`a * b` or `multiply(a,b)`| |
||`a / b` or `divide(a,b)`| |
||`a ** b`| |
||`a % b`||


####Java
<table>
  <tbody>
    <tr>
      <th>Action</th>
      <th align="left">Java</th>
      <th align="left">Julia</th>
    </tr>
  </tbody>
</table>



Useful links:
* [ipython.org/notebook.html] (ipython.org/notebook.html)
* [juliabox.org] (juliabox.org)





