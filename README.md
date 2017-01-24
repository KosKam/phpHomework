<?php

$n = 145;
$nStart = 102;

while ($nStart <= $n){
    
    $firstDig = $nStart % 10;
    $removeFirstDig = round($nStart / 10, 0);
    $secondDig = $removeFirstDig % 10;
    $removeSecondDig = round($nStart / 10, 0);
    $thirdDig = $removeSecondDig % 10;
    
   if ($firstDig != ($secondDig != $thirdDig)) {
        echo $nStart.', ';
    }  
 
    
    $nStart++;
 }

 /*   echo $firstDig.'<br>';
   echo $removeFirstDig.'<br>';
   echo $secondDig.'<br>';
  * */
  
