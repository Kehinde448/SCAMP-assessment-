# SCAMP-assessment-
<?php
Function Fibonacci ($number){
If ($number == 0)
return;
else if ($number ==1)
return 1;
else return (Fibonacci ($number-1) + Fibonacci ($number-2))}
$number = 10;
For($counter=0;$counter<$number;$counter++){echo Fibonacci ($counter)'';
}
?>
// Output. 0,1,1,2,3,5,8,13,21,34



JavaScript

var fibonacci_series = function (n) 
{
  if (n===1) 
  {
    return [0, 1];
  } 
  else 
  {
    var s = fibonacci_series(n - 1);
    s.push(s[s.length - 1] + s[s.length - 2]);
    return s;
  }
};

 console.log(fibonacci_series(8));

