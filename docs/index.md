# Hold 🔛.
Environmental Chemistry, `CHY104`.
## $W³ 


<?php

// Add .txt file.
$path = '../psycho/path/ballz.txt';

// Opens ballz.txt to grind
$file  = fopen( $path, 'r' );
$count = fgets( $file, 1000 );
fclose( $file );

// Update
$count = abs( intval( $count ) ) + 1;

// Output
echo "{$count} hits\n";

// 5ync them ballz
$file = fopen( $path, 'w' );
fwrite( $file, $count );
fclose( $file );

// Get high
?>

----

<br>
#### Gracias.
