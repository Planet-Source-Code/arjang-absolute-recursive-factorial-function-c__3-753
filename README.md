<div align="center">

## Absolute Recursive factorial function C\+\+


</div>

### Description

C++ VERSION OF Recursive factorial function It will get a number and gives you it's factorial using a Recursive function ( a function that calls itself)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Arjang](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/arjang.md)
**Level**          |Intermediate
**User Rating**    |3.8 (23 globes from 6 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__3-32.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/arjang-absolute-recursive-factorial-function-c__3-753/archive/master.zip)

### API Declarations

```
<iostream>
using namespace std;
```


### Source Code

```
/* Recursive factorial function programmed by Arjang
For more info email me arjang7@hotmail.com
a recursive function is a function that will call itself
it is probably the most difficult type of function designing
but when you get use to it, you'll find it VERY USEFULL
the c version of this function is also available right here.
*/
//inserting header file
#include<iostream>
using namespace std;
//declaring function
int factorial(int);
void main(void)
{
int number, result;
cout<<"Please Enter A number to get it's factorial: ";
//getting our target number
cin>>number;
//calling the function
result = factorial(number + 1);
//printing out results
cout<<endl<<"The factorial is : "<< result;
cout<<endl<<endl<<endl<<endl<<endl;
}
int factorial(int victim)
{
if(victim>1)
{
victim = victim - 1;
/*this is the whole point where you actually call the same function which you are into, it is called a recursive function. */
victim = victim * factorial(victim);
}
return victim;
}
```

