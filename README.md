# hello-word

<?php
  $z = 12;
  function test(){
	  global $y;
	  $y = 3;
	  $x = 2;
	  echo $y;
	  echo $x;
	  // echo $z;
  }
  test();
  echo "<br />";
  echo $y;
  function test1(){
	  static $h = 1;
	  echo $h;
	  $h++;
  }
  test1();
  test1();
  test1();
  test1();
  
  
  print "nihao";
?>			
