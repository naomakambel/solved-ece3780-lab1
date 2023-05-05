Download Link: https://assignmentchef.com/product/solved-ece3780-lab1
<br>
<h1>1.0 Matlab tutorials</h1>

Check out the web site www.mathworks.com. At this site check out the features available for this software package, and the available shareware files that can also be downloaded.

The following videos found in <a href="https://www.mathworks.com/products/matlab/demos.html">http://www.mathworks.com/products/matlab/demos.html</a>  will be of great help:

<a href="https://www.mathworks.com/videos/matlab/getting-started-with-matlab.html">Getting Started with MATLAB </a><a href="https://www.mathworks.com/videos/matlab/getting-started-with-matlab.html"> </a>

Get started with MATLAB and learn how to get more information.

<a href="https://www.mathworks.com/videos/matlab/working-in-the-development-environment.html">Working in The Development Environment </a><a href="https://www.mathworks.com/videos/matlab/working-in-the-development-environment.html"> </a>

Access tools such as the command history workspace browser, and variable editor; save and load your workspace data; and manage windows and desktop layout.

<a href="https://www.mathworks.com/videos/matlab/writing-a-matlab-program.html">Writing a MATLAB Program </a><a href="https://www.mathworks.com/videos/matlab/writing-a-matlab-program.html"> </a>

Write a MATLAB program, including creating a script and a function.

<a href="https://www.mathworks.com/videos/matlab/importing-data-from-files.html">Importing Data from Files </a><a href="https://www.mathworks.com/videos/matlab/importing-data-from-files.html"> </a>

Import data from spreadsheets, text files, and other formats into MATLAB.

<a href="https://www.mathworks.com/videos/matlab/creating-a-basic-plot-interactively.html">Creating a Basic Plot Interactively </a><a href="https://www.mathworks.com/videos/matlab/creating-a-basic-plot-interactively.html"> </a>

Create plots interactively from within the MATLAB desktop environment.

<a href="https://www.mathworks.com/videos/matlab/using-basic-plotting-functions.html">Using Basic Plotting Functions </a><a href="https://www.mathworks.com/videos/matlab/using-basic-plotting-functions.html"> </a>

Create plots programmatically using basic plotting functions.




<a href="https://www.mathworks.com/videos/matlab/working-with-arrays.html">Working with Arrays </a><a href="https://www.mathworks.com/videos/matlab/working-with-arrays.html"> </a>

Create and manipulate MATLAB arrays, including accessing elements using indexing.

<h1>2.1 Basic Matlab commands</h1>

Type the given statements into the command window or create an *.m file through the <em>File</em>, <em>New</em>, <em>M-file</em> on the menu bar and then run the m-file through <em>Debug</em>, <em>Run</em>. You can also type the filename in Matlab Command Window.

%  Loops in Matlab

% The percent sign leading indicates a comment line

%  Type the following command

for i=0:7,  x(i+1)= sin(i*pi/4), end

% Plot the function using

plot(x)

% Type in the command prompt  whos




% How many variables are there in memory, which one is the vector

% and which one is the integer? Record the  Size. Do you really have integers?




% Type and check the size again i = int8(i)




% Type

help int8 % Type

help lookfor




% You will find the above two commands very useful at the beginning, so keep them  % in mind.







% run the following

tic, for i=0:7,  x(i+1)= sin(i*pi/4); end,  toc,  plot(x)

% use the <em>up arrow</em> key in the keyboard and run the commands several times

% Explain what is happening




% run the following

tic,  i=0:7;,  x = sin(i*pi/4);  toc, plot(x)

% use the <em>up arrow</em> key in the keyboard and run the commands several times

% Explain the similar and different things that are happening between the above

% and this new set of commands (this must encourage you to become familiar with % array manipulation in Matlab)




% try  and explain what is happening. i=0:0.1:7;,  x = sin(i*pi/4); plot(x)




% Can you do the following?  Explain for i=0:5;, x(i)=i^2, end

for i=1:6;, x(i)=(i-1)^2, end




% Run the following and explain the difference




x = [1 2 3; 4 5 6; 7 8 9];, x.*x

x = [1 2 3; 4 5 6; 7 8 9];, x*x




x = [1+j*1 2+2*j; 3+3*j 4+ 4*j]’

x = [1+j*1 2+2*j; 3+3*j 4+ 4*j].’




<h1>2.2 Input data, plotting and function calls</h1>




You are given a text file A.txt.

It contains data stored by ultrasound equipment and the first column corresponds to the real value of a complex signal, the second column corresponds to the imaginary part. By using the command load in Matlab, read the data and plot it as follows:







Look for help within the Matlab software regarding <em>complex</em> numbers.

Implement your solution as a function in Matlab. Thus a main program will call your function (you will be writing two different .m files) and you will send the data contained in the file and your function will read it, turn it into a complex value vector and plot it as shown above.

<strong> </strong>

<h1>3.0 Part II Experiments</h1>




Provide the complete code of your M-Files along with required plots and answers to the questions in each section. Do not forget the command <em>subplot</em> when plotting several signals (please see the Figure above, it is only one Figure –subplot(311) is the real part).




3.1 Consider the following signal




For T = 4, 8 and 16 plot the signal on the interval 0 ≤ <em>t</em> ≤ 5. What is the period of <em>x</em>(<em>t</em>) in terms of <em>T</em>?




3.2 Plot the following signals for -1≤ <em>t</em>  ≤−5 sec. Label your axes appropriately.


