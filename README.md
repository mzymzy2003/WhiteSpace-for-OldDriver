# WhiteSpace-for-OldDriver
Simple enough, but also awesome enough. A new luxury car for old drivers.

Inspired from an awesome programming language *WhiteSpace*, which only contains Tabs, Spaces and Enters, the WhiteSpace here is an encrypt mechanism which only has Spaces and Tabs.

It it better than some Morse Code Car, for all the encrypted text will be *invisible* for the above reasons, so it is impossible for a HUMAN to decrypt as it cannot be seen at all, but the former cannot.

It can not only decrypt a single message, but a entire file as well. But mind that the encrypted file will be larger than the original one. So only try to encrypt a text file or some torrents, never try to encrypt a video please...

# Usage
```
python whitespace.py -e|-d (-i input -o output)
-h, --help: View the manual
-e, --encrypt: Run encrypt mode
-d, --decrypt: Run decrypt mode
-a, --advanced: use '+' as a spliter in order to prevent some idiot escape methods, also needs to decrypt with this mode
-i, --input=: Read a file instead of typing it
-o, --output=: Write to a file instead of printing it
```
Notice that when you running decrypt mode, everything besides spaces and tabs will be ignored, but at least contain one space or tab or the program will throw an error.

# How it works?
Well, as I said before, simple enough, we all know that everything in the computer is a combination of binary 0/1 code, so a space represents a 0 status, a tab represents an 1 status...

That's all!

# Demo
All the code part down below must be viewed as [raw](https://raw.githubusercontent.com/hanbang-wang/WhiteSpace-for-OldDriver/master/README.md)!
The following is an encrypted `Hello, World!` message:
```
 	  	    		  	 	 		 		   		 		   		 				  	 		    	      	 	 			 		 				 			  	  		 		   		  	    	    	
```
![demo1.jpg](http://i2.wp.com/www.superfashi.com/wp-content/uploads/2016/01/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7-2016-01-15-%E4%B8%8B%E5%8D%8811.06.48.jpg)

Wow, nice!

It also supports all the Unicode characters, say Hello as `你好` in Chinese:
```
			  	  	 				 		 	     			  	 		 	  	 		 				 	
```
![demo2.jpg](http://i2.wp.com/www.superfashi.com/wp-content/uploads/2016/01/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7-2016-01-15-%E4%B8%8B%E5%8D%8811.07.10.jpg)

And as some social apps will escape spaces and tabs, we can use `-a` mode:
```
+ + + ++ ++++ +++ + ++ + + ++ +++ +++ + + ++ ++++ +++ + ++ + + ++ +++ +++
```
![demo2.jpg](http://i0.wp.com/www.superfashi.com/wp-content/uploads/2016/01/%E5%B1%8F%E5%B9%95%E5%BF%AB%E7%85%A7-2016-01-16-%E4%B8%8B%E5%8D%8810.18.53.jpg)

Maybe not that fun anymore...

But, using file is always a best option since even Github will escape those innocent letters.
# To-Do
- Try inserting random letters or a specific infomation between char in order to make more confusing text (since the program only recongnize blank :P)
- Try to make some messages passcode-needed.

# License
What, license? Fuck the license, do whatever you want.
