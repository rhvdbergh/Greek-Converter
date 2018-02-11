Greek Converter 1.0 Readme

Introduction
------------
This program converts the "Egreek" font to Unicode characters. It will work well for all the basic letters, accents, etc. Specialized characters (e.g. the koppa or digamma) are not included. Characters and symbols that are not associated with a specific Greek symbol in Egreek (e.g. numbers) will simply be copied into the resulting Unicode file. 

The program is unfortunately not GUI driven at this stage - perhaps some other time. 

How to use Greek Converter 1.0
------------------------------
The program ALWAYS uses a file called "input.txt" in which should be copied the text that should be converted and ALWAYS produces a file with the converted Unicode text called "output.txt". The "input.txt" file should be in the same directory as the executable file "Greek_Converter.jar".

One can either save the text to be converted as a "Plain Text" file from one's word processer (e.g. Microsoft Word) or copy the text to be converted into a plain text word editor like Wordpad. Remember to save the file as "input.txt" in the same directory as the file "Greek_Converter.jar.

Now run Greek_converter.jar. A file called "output.txt" should be in the same directory. The text can now be copied from this file to wherever it is needed.

Known issues
------------
*Any spaces at the end of a line will be removed.

*Needless to say, if any language except Greek (e.g. English) is included in the input file, it will be converted to "Greek" - resulting in Gibberish.
