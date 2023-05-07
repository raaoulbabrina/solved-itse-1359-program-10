Download Link: https://assignmentchef.com/product/solved-itse-1359-program-10
<br>



<ul>

 <li>Create a file using PyCharm.</li>

 <li>Name the source file program_10.py.</li>

 <li><u>Format code like the examples</u>.</li>

 <li><u>Include comments in your code like the examples</u>.</li>

 <li>Code the requirements in the numbered list below.</li>

 <li>Output a header in the console: “This is Program 10”</li>

</ul>

This program requires the use of pyperclip, a module to work with the clipboard.

<strong>Command Line</strong> – Navigate to your working directory and run the commands:

C:python -m pip install –upgrade pip   –   upgrade pip installer

C:pip install pyperclip   –   install pyperclip

C:set PYTHONPATH=.   –  may need if your PYTHONPATH is not set correctly

In <strong>PyCharm</strong> | Settings, add the pyperclip package using the following steps:

Find the pyperclip package in the list on the left and select Install Package.

PyCharm should report that the pyperclip package was installed successfully. Select OK.

<strong>Requirements</strong> to be numbered in program_10.py:

<ol>

 <li>Print “This program manipulates text from files and the clipboard and performs other string, file, and directory manipulation tasks.”</li>

 <li>Output the current working directory of the program.</li>

 <li>Ask the user to enter the directory where they would like files to be stored, make that directory, and store files in the program in that directory.</li>

 <li>Write the following three lines to file_one.txt (without bullet points):

  <ul>

   <li>Line 1 from file_one wrong_text</li>

   <li>Line 2 from file_ one wrong_ text</li>

   <li>Line 3 from file_ one wrong_ text</li>

  </ul></li>

 <li>Display the contents of file_one.txt.</li>

 <li>Programmatically replace the substring ‘file_one wrong_text’ in data read from file_one.txt with ‘file_two correct_text’ and write the corrected lines to file_two.txt.</li>

 <li>Ask the user to type the following lines (without bullet points) into Notepad++ and copy the lines to the clipboard (using Ctrl-c):

  <ul>

   <li>Line 1 from the clipboard</li>

   <li>Line 2 from the clipboard Line 3 from the clipboard</li>

  </ul></li>

 <li>Programmatically display the contents of the clipboard which should contain the three lines from Requirement 5.</li>

 <li>Read the contents of file_two.txt and read the contents of the clipboard.</li>

 <li>Append the contents of the clipboard onto the contents of file_two.txt line-by-line to produce the following:

  <ul>

   <li>Line 1 from file_two followed by Line 1 from the clipboard</li>

   <li>Line 2 from file_two followed by Line 2 from the clipboard Line 3 from file_two followed by Line 2 from the clipboard 11. While performing Requirement 8, write the lines out to file_three.txt.</li>

  </ul></li>

 <li>Display the contents of the file_three.txt.</li>

 <li>Ask the user for a new directory name. Programmatically create that directory and programmatically copy the files created earlier in the program to the new directory. Programmatically compress the files in the new directory.</li>

 <li>Print a statement explaining your experiences with Program 10.</li>

</ol>

TEST – TEST – TEST your application to ensure the specific program requirements are met.

<ul>

 <li>Use the list above and the common requirements as a confirmation checklist.</li>

 <li>Not meeting all requirements = 0 points for the assignment.</li>

</ul>


