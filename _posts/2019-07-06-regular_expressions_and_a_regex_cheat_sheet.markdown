---
layout: post
title:      "Regular Expressions and a Regex Cheat Sheet"
date:       2019-07-06 17:14:58 +0000
permalink:  regular_expressions_and_a_regex_cheat_sheet
---




Regex stands for regular expression.  A regular expression is a sequence of text that define a search pattern, which allow you to create patterns that match, locate, and manage text.  Reguar expressions are based on mathematical theory.  Using regular expressions can save time in locating large amounts of text.  The following information used for the Regex Cheat Sheet was found on www.computerhope.com/jargon/r/regex.htm, where this website takes a nice in depth look at regular expressions.   


**Regex Cheat Sheet:**
              
Character:                              What it does:                                                      Examples:                                           

^                                     Matches beginning of line                                            ^abc

$	                                    Matches end of line	                                                         abc$
 
.                                      	Match any character                                                        	a.c

|	                                      OR operator	                                                                      abc|xyz

(...)	                                 Capture anything matched	                                           (a)b(c)

(?:...)	                              Non-capturing group                                               	     (a)b(?:c)
   
[...]                                  Matches anything contained in brackets	                 [abc]

[^...]	                             Matches anything not contained in brackets	        [^abc]

[a-z]                              Matches any characters between 'a' and 'z'	              [b-z]

{x}                                  The exact 'x' amount of times to match	                   (abc){2}

{x,}	                               Match 'x' amount of times or more                       	      (abc){2,}

{x,y}	                              Match between 'x' and 'y' times.	                                  (a){2,4}

*                                     Greedy matches everything in place of the *             ab*c

+	                                   Matches character before + one or more times	       a+c

?	                                    Matches the character before the ? zero or          	   ab?c
                                       one times.  Also, used as a non-greedy match
                                       
																			 
																			** Escape Characters /	**																		 


\	                                    Escape the character after the backslash or 	            a\sc 
                                       create an escape sequence.

\0	                                Null character	

\a	                                Match a bell or alarm.																			 
 
\b	                                Word boundary in most or backspace

\B	                                Non word boundary

\d	                                Match any decimal digit (0-9)

\D	                               Match any non digit

\e	                               Match an escape

\f	                                Match a form feed

\n	                               Match a new line

\Q...\E                       	Ignores any special meaning in what is being matched.

\r	                                Match a carriage return

\s	                                Matches a space character (space, \t, \r, \n)

\S	                               Matches any non-white space character

\t	                                Match a tab

\v	                               Match a vertical tab

\w	                              Matches any one word character

\W	                             Matches any one non word character

                                         Regular Expression Flags -Outside the regular expression (at the end) flags can 
																				 be used to help with the pattern matching.
																					
i	                                   Ignore the case (upper and lower case allowed)		

m	                                Multi-line matchs

s                                   Match new lines

x	                                  Allow spaces and comments

J                                 	Duplicate group names allowed

U	                                  Ungreedy match



