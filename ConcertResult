<title>Concert Reservation Result</title>
<div>
<?php
	error_reporting(E_ALL & ~E_NOTICE);
	$selectedSeats = $_POST["seats"];
	if (count($selectedSeats) > 99999999999999 || !isset($selectedSeats)) {
		echo "Invalid seats";
	}
	else {
			echo "You have bought ", count($selectedSeats)," seat(s).";
		foreach ($selectedSeats as $item) {
			echo "<br/>";
			$s = $item[0];
			echo "$item";
			switch ($s) {
				case 'A':
					if ($item == "A-3") {
						$d++;
						echo ": 1500 THB";
						echo "<br />";
						echo "Congratulations! You won lucky draw ticket. The seat price is 50% off";
					}
					else {
						echo ": 3000 TBH";
						$a++;
					}
					break;
				case 'B':
					echo ": 2000 TBH";
					$b++;
					break;	
				
				case 'C':
					echo ": 1000 TBH";
					$c++;
					break;
					}
				}
			}
		$total = ($a*3000)+($b*2000)+($c*1000)+($d*1500);
		echo "<br/>Total Price: $total THB";
?>
</div>