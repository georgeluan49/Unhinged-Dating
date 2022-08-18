Note: The executable right now only supports Mac OS. If you are using another machine, please contact me for the source code!

This piece of software is a class project of CS 32 at UCLA.
This is a command-line based dating software. Here is how one may use it:
	Please enter the path of your member database: /home/unhinged-dating/members.txt
	Please enter the path of your translator file: /home/unhinged-dating/translator.txt
	Enter the member's email for whom you want to find matches: sm0lbirg@hotmail.com
	The member has the following attributes:
	hobby --> coding
	job --> professor
	gender --> male
	hobby --> baking
	favorite food --> b'stilla
	How many shared attributes must matches have? 5
	The following members were good matches:
	Jamie Lai at jamie_lai24143@hotmail.com with 13 matches! Stephen Li at slee1724@gmail.com with 11 matches!
	Emile Gin at egin9389@xfinity.com with 10 matches!
	Jame Buoy at jamebuoy2008@gmail.com with 6 matches! Karrie Wong at kw4224@aol.com with 6 matches!
*You can quit by hitting enter.

The members database file is a text file with the following format:
	Person 1’s name
  Person 1’s email address
	Count of number of attribute-value pairs for person 1 attr1,value1
	attr2,value2
	...
  attrN,valueN
	
	Person 2’s name
	Person 2’s email address
	Count of number of attribute-value pairs for person 2 attr1,value1
	attr2,value2
	...
	attrN,valueP
Each member record separated by a single blank line, and there is a blank line after the last record.

The attribute translator file consists of one or more lines with the following comma-separated format:
	source_attribute,source_value,compatible_attribute,compatible_value
