# PHP Web Service Part III - Coding the web service

[Overview](#overview)

[I. Get Started](#get-started)

[II. Add some content](#add-some-content)

[III. Get random joke](#get-random-joke)

<hr><hr>

<a id="overview" />

## Overview
- Now that you know about PHP, we can finally get coding our web service!

<hr>

<a id="get-started" />

## I. Get Started

- Here is your start file - go ahead and get this posted to banjo
- Open it up in your web browser, and be sure that you get similar outpout as the screenshot below before you continue

**get-random-joke.php**

```php
<?php
	/*
		Name: get-random-joke.php
		Description: Returns a single random joke in JSON format
		Author: 
		Last Modified: 
	*/
	
	// $jokes contains our data
	// this is an indexed array of associative arrays
	// the associative arrays are jokes -  they have an 'q' key and an 'a' key
	$jokes = [
		["q"=>"What do you call a very small valentine?","a"=>"A valen-tiny!"],
		["q"=>"What did the dog say when he rubbed his tail on the sandpaper?","a"=>"Ruff, Ruff!"],
		["q"=>"Why don't sharks like to eat clowns?","a"=>"Because they taste funny!"],
		["q"=>"What did the fish say when be bumped his head?","a"=>"Dam!"]
	];


	// Debugging - comment all these `echo()` statements out after you verify that everything works
	// print the first joke
	echo $jokes[0]["q"] . " " . $jokes[0]["a"]; 
	// print a blank line
	echo "\n\n"; 
	// print the entire array to the window
	print_r($jokes); 

?>
```


<hr>

![screenshot](./_images/HW-php-web-service-6.jpg)

<hr>

<a id="add-some-content" />

## II. Add some content

- Go ahead and add 4 (or more) jokes to the array
- Please keep them SFW - ***Safe For Work!***
- Preview your web service in Chrome to be sure that you didn't break anything

<hr>

<a id="get-random-joke" />

## III. Get random joke

- Go ahead and add 4 (or more) jokes to the array
- Please keep them SFW - ***Safe For Work!***
- Preview your web service in Chrome to be sure that you didn't break anything

<hr>




<hr><hr>

**[Previous Chapter <- PHP Web Service - Part II](HW-php-web-service-2.md)**

**[Next Chapter -> PHP Web Service - Part IV](HW-php-web-service-4.md)**