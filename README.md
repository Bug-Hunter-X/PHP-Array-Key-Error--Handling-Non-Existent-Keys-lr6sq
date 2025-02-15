# PHP Array Key Error: Handling Non-Existent Keys

This repository demonstrates a common error in PHP: attempting to access array elements using keys that may not exist.  The code shows how this can lead to errors and provides a solution using `array_key_exists()` to check for the key's existence before accessing it.

## Bug Description

The `bug.php` file contains a simple example where a non-existent array key is accessed, resulting in an error. 

## Solution

The `bugSolution.php` file demonstrates a robust approach by checking if the key exists using `array_key_exists()` before attempting to access the array element. This prevents the error and handles the case where the key is missing gracefully.