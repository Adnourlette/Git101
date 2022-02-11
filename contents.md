# **เนื้อหาสรุป** :sweat_smile:
## Terminal Run Code
> Compile : gcc <File>.c -o <File>
> Run : ./<File>

## Variable(VA)

- Char(VC) : ASCII character -128 to 127
- Int(VI)	: Number -32768 to 32767
- Long(VL) : Number -2147483648 to 2147483649
- Float(VF) : 6 decimal places
- Double(VD) : 12 decimal places
* (in) : Declared Variable 


## Operator
> Ralational : > >= < <= == !=
> Logical : && || !

## Type
```
%c : Single character (char)
%s : String of characters (char)
%d : Decimal integer (int)
%o : Octal Integer (int)
%x/X : Hexadecimal Integer (int)
%e/E/f/g/G : Floating point (float)
```

## Library
### stdio.h 
> Input
```
scanf("[Type]", <VA>)
fgets(<VC>, (maximum number of characters to input), stdin)
gets(<VC>) : Keep text
<VC> = getchar() : Keep first character
```

> Output
```
printf("<text>" or "[Type]",<VA>)
puts(<VC>) Show text
putchar(<VC>) : Show one character(ASCII)
```

### stdlib.h
> Transfer Variable
```
int <VI> = atoi(<Array>) : array Transfer to int
float <VI> = atof(<Array>) : array Transfer to float
long <VI> = atol(<Array>) : array Transfer to long
```

### math.h
```
acos(x) : arc cosine of x in radians.
asin(x) : arc sine of x in radians.
atan(x) : arc tangent of x in radians.
cos(x) : cosine of a radian angle x.
cosh(x) : hyperbolic cosine of x.
sin(x) : sine of a radian angle x.
sinh(x) : hyperbolic sine of x.
tanh(x) : hyperbolic tangent of x.
exp(x) : value of e raised to the xth power.
log(x) : natural logarithm (base-e logarithm) of x.
log10(x) : common logarithm (base-0 logarithm) of x.
pow(x, y) : x raised to the power of y.
sqrt(x) : square root of x.
ceil(x) : smallest integer value greater than or equal to x.
floor(x) : largest integer value less than or equal to x.
fabs(x) : absolute value of x.
fmod(x, y) : remainder of x divided by y.
M_PI : Def PI 3.14 or 22/7
```