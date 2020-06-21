I was inspired to create this one-stop Top 100  PHP functions because a lot of people might choose PHP as their first programming language due to the popularity of it. Huge thanks to exakat.com who shared them here https://www.exakat.io/top-100-php-functions/. 

Note: I haven't finished the rest.. so if you would care to help, just PR away!

1. [count](https://www.php.net/count) - Count all elements in an array, or something in an object

```
count ( mixed $array_or_countable [, int $mode = COUNT_NORMAL ] ) : int
```

2. [is_array](https://www.php.net/is_array) - Finds whether a variable is an array

```
is_array ( mixed $var ) : bool
```

3. [substr](https://www.php.net/substr) - Return part of a string

```
substr ( string $string , int $start [, int $length ] ) : string

```
4. https://www.php.net/in_array -  Checks if a value exists in an array

```
in_array ( mixed $needle , array $haystack [, bool $strict = FALSE ] ) : bool
```

5. https://www.php.net/explode - Split a string by a string

```
explode ( string $delimiter , string $string [, int $limit = PHP_INT_MAX ] ) : array
```

6. https://www.php.net/str_replace - Replace all occurrences of the search string with the replacement string 

```
str_replace ( mixed $search , mixed $replace , mixed $subject [, int &$count ] ) : mixed
```
7. https://www.php.net/implode - Join array elements with a string

```
implode ( string $glue , array $pieces ) : string
```

8. https://www.php.net/strlen -  Get string length

```
strlen ( string $string ) : int
```

9. https://www.php.net/array_merge - Merge one or more arrays


10. https://www.php.net/strpos - Find the position of the first occurrence of a substring in a string

```
strpos ( string $haystack , mixed $needle [, int $offset = 0 ] ) : int
```

11. https://www.php.net/preg_match - Perform a regular expression match
```
preg_match ( string $pattern , string $subject [, array &$matches [, int $flags = 0 [, int $offset = 0 ]]] ) : int
```

12. [sprintf](https://www.php.net/sprintf) - Return a formatted string
13.	[trim](https://www.php.net/trim) - Strip whitespace (or other characters) from the beginning and end of a string
14.	[strtolower](https://www.php.net/strtolower) -  Make a string lowercase
15.	[file_exists](https://www.php.net/file_exists) - Checks whether a file or directory exists
16.	[is_string])(https://www.php.net/is_string) - Find whether the type of a variable is string
17.	[preg_replace](https://www.php.net/manual/en/function.preg-replace.php) - Perform a regular expression search and replace
18.	[file_get_contents](https://www.php.net/file_get_contents) - Reads entire file into a string
19.	[array_key_exists](https://www.php.net/array_key_exists)	- Checks if the given key or index exists in the array
20.	[array_keys](https://www.php.net/array_keys) - Return all the keys or a subset of the keys of an array
21.	[dirname](https://www.php.net/dirname) - Returns a parent directory's path
22.	[function_exists](https://www.php.net/function_exists)	-
23.	[array_map](https://www.php.net/array_map) - Applies the callback to the elements of the given arrays
24.	[get_class](https://www.php.net/get_class)	- Returns the name of the class of an object
25.	[class_exists](https://www.php.net/class_exists)	- Checks if the class has been defined
26.	[is_object](https://www.php.net/is_object)	 - Finds whether a variable is an object
27.	[time](https://www.php.net/time)	- Return current Unix timestamp	
28.	[json_encode](https://www.php.net/json_encode)	
29.	[date](https://www.php.net/date)	- Format a local time/date
30.	[is_null](https://www.php.net/is_null)	- Finds whether a variable is NULL
31.	[is_numeric](https://www.php.net/is_numeric)	- Finds whether a variable is a number or a numeric string
32.	[array_shift] (https://www.php.net/array_shift) - Shift an element off the beginning of array
33.	[defined](https://www.php.net/defined)	- Checks whether a given named constant exists
34.	[is_dir](https://www.php.net/is_dir) - Tells whether the filename is a directory
35.	[json_decode](https://www.php.net/json_decode)	- Returns the JSON representation of a value
36.	[header](https://www.php.net/header) - Send a raw HTTP header
37.	[strtoupper](https://www.php.net/)strtoupper -  Make a string uppercase	
38.	[array_values](https://www.php.net/array_values)	
39.	[md5](https://www.php.net/md5)	
40.	[method_exists](https://www.php.net/method_exists)	
41.	[file_put_contents](https://www.php.net/file_put_contents)
42.	[rtrim](https://www.php.net/rtrim)
43.	[array_pop]	(https://www.php.net/array_pop)
44.	[unlink](https://www.php.net/unlink)	
45.	[basename](https://www.php.net/basename) - Returns trailing name component of path
46.	[realpath](https://www.php.net/realpath)	
47.	[call_user_func](https://www.php.net/call_user_func)	
48.	[call_user_func_array](https://www.php.net/call_user_func_array)	
49.	[fopen](https://www.php.net/fopen)
50.	[microtime]	(https://www.php.net/microtime)
51.	[fclose](https://www.php.net/fclose) -
52.	[is_int](https://www.php.net/is_int) - Find whether the type of a variable is integer
53.	[is_file](https://www.php.net/is_file) - Tells whether the filename is a regular file
54.	[array_slice](https://www.php.net/array_slice) - Extract a slice of the array
55.	[preg_match_all](https://www.php.net/) - Perform a global regular expression match
56.	[ucfirst](https://www.php.net/ucfirst) - Make a string's first character uppercase
57.	[intval](https://www.php.net/intval) - Get the integer value of a variable
58.	[str_repeat](https://www.php.net/str_repeat) - Repeat a string
59.	[serialize](https://www.php.net/serialize) - Generates a storable representation of a value
60.	[array_filter](https://www.php.net/array_filter) - Filters elements of an array using a callback function
61.	[mkdir](https://www.php.net/mkdir) -
62.	[is_callable](https://www.php.net/is_callable) - Verify that the contents of a variable can be called as a function
63.	[ltrim](https://www.php.net/ltrim) - Strip whitespace (or other characters) from the beginning of a string 
64.	[ob_start](https://www.php.net/ob_start) - Turn on output buffering
65.	[round](https://www.php.net/round) -  Rounds a float
66.	[fwrite](https://www.php.net/fwrite) - Binary-safe file write
67.	[array_unique](https://www.php.net/array_unique) - Removes duplicate values from an array
68.	[array_search](https://www.php.net/array_search) - Searches the array for a given value and returns the first corresponding key if successful
69.	[reset](https://www.php.net/reset) - Set the internal pointer of an array to its first element
70.	[array_unshift](https://www.php.net/array_unshift) -
71.	[parse_url](https://www.php.net/parse_url)
72.	[func_get_args](https://www.php.net/func_get_args) -
73.	[end](https://www.php.net/end) -
74.	[base64_encode](https://www.php.net/base64_encode) - encode to base64 format
75.	[unserialize](https://www.php.net/unserialize) - 
76.	[max](https://www.php.net/max) - Find highest value
77.	[preg_split]((https://www.php.net/preg_split)-
78.	[gettype](https://www.php.net/gettype) -
79.	[strrpos](https://www.php.net/strrpos) -
80.	[version_compare](https://www.php.net/version_compare)
81.	[array_push](https://www.php.net/array_push) -
82.	[floor](https://www.php.net/floor) -
83.	[strtotime](https://www.php.net/strtotime) -
84.	[htmlspecialchars](https://www.php.net/htmlspecialchars) -
85.	[ini_get](https://www.php.net/ini_get) -
86.	[ini_set](https://www.php.net/ini_set) -
87.	[chr](https://www.php.net/chr) -
88.	[extension_loaded](https://www.php.net/extension_loaded) -
89.	[is_bool](https://www.php.net/is_bool) - Finds out whether a variable is a boolean
90.	[ksort](https://www.php.net/ksort) - Sort array by key 
91.	[array_reverse](https://www.php.net/array_reverse) - Reverse an array
92.	[ord](https://www.php.net/ord) - Convert the first byte of a string to a value between 0 and 255
93.	[uniqid](https://www.php.net/uniqid) -
94.	[strtr](https://www.php.net/strtr) - Translate characters or replace substrings
95.	[array_diff](https://www.php.net/array_diff) -
96.	[error_reporting](https://www.php.net/manual/en/errorfunc.configuration.php#ini.error-reporting) - Turn off all error reporting `error_reporting(0);` 
97.	[ceil](https://www.php.net/) - Round fractions up
98.	[urlencode](https://www.php.net/) -  URL-encodes string
99.	[min](https://www.php.net/) - Find lowest value
100. [print_r](https://www.php.net/print_r) -	Prints human-readable information about a variable,  alternative is [var_dump](Dumps information about a variable)
