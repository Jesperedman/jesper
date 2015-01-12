# jesper

<?php
date_default_timezone_set("Europe/Stockholm");
echo "The time is " . date("h:i:sa") . "<br>";
$d=mktime(11, 14, 54, 8, 12, 2014);
echo "Todays date is " . date("Y-m-d ", $d);
?>
