```
var a = "outer";
{
    fun f() {
        print a;
     }
  f();
  var a = 1;
  f();
}
```
why output is "outer", "outer" ?

is output need to be "outer", "outer" ?



