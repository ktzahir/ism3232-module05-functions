# Debug Log
# Author: kazi Zahir

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 11
What the error means: Python is trying to find key called 'amount' the record has it spelled as 'amout' so it gives key error 
What I told the duck:that the first record has a spelling mistake, which prevents the function from finding the correct key.
What I tried: I ran the Python script and got a KeyError. I checked line 11 and compared it to the records list. I noticed that the first record had a spelling mistake.
How I fixed it: I fixed the spelling mistake in the first record by changing ‘amout’ to ‘amount’. Then I removed the DEBUG print statement and ran the code again to check if the error was gone.

## Bug 2
Error type: typeError
File + line: week8_buggy.py, line 16
What the error means: Python was trying to compare an integer with a string using >, which caused a TypeError.
How I fixed it: I removed the quotation marks around 1000 so Python would compare two integers instead of an integer and a string.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records
True
Did pytest pass? Yes, all 13 tests passed.

## AI Literacy Reflection
Did I use AI? yes 
If yes -- exact prompt I used:  “Is it the +=” and “Would it be line 4 instead of 11 because they spelled it wrong". "what is the error for bug 2"
What AI explained: AI explained what a KeyError and TypeError mean, how to read the traceback, and why comparing an integer with a string causes an error. It also guided me through using a DEBUG print statement.
What I changed myself:I corrected the misspelled dictionary key, changed the comparison to use an integer, and removed the temporary DEBUG print statement.
Can I explain every fixed line? yes

## What I learned: I learned how to read Python error messages and figure out what is causing the problem. I also learned how to use DEBUG print statements to find mistakes in my code. This lab helped me understand why spelling and data types are important when writing Python code.