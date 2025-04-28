# csc4005-assignment-2--mandelbrot-set-computation-solved
**TO GET THIS SOLUTION VISIT:** [CSC4005 Assignment 2- Mandelbrot Set Computation Solved](https://www.ankitcodinghub.com/product/csc4005-assignment2-mandelbrot-set-computation-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118019&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC4005 Assignment 2- Mandelbrot Set Computation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Description

Set of points in a complex plane that are quasi-stable (will increase and decrease, but not exceed some limt) when computed by iterating the function:

When is the iteration of the complex number and is a

complex number giving the position of the point in the complex plan. (For example, in a

image of height and width , . You can also scale the to obtain a different output).

The initial value for is zero. The iterations continued until the magnitude of is greater than a threshold or the maximum number of iterations have been achieved. For . The magnitude of is defined below:

Computing the complex function is simplfied by recognizing that:

Therefore, real part is the real part is . The next iteration values can be produced by computing:

You need to design your own method to partition the image and assign pixels to different threads or processes. For visualizing the Mandelbrot Set on an image, compute for each pixels. If is quasi-stable, draw this pixel on the display using asg2 (where template is uploaded to bb) or Xlib (where template is uploaded to http://www.cs.nthu.ed u.tw/~ychung/homework/para_programming/seq_mandelbrot_c.htm.)

Requirement

Requirement

You need to implement two versions of the tasks, which are MPI version and a Pthread version. And hand in the codes for these two versions in two seperate code files.

In your submit code, it should display an image with size of 800 × 800.

Include the results in your report.

You need to specify the command line about how to compile and run your program.

You need to compare the performance of different implementation and configurations in your report.

a. The number of processes or threads used in the program

b. MPI vs Sequential vs Pthread

c. Size of the output images (three different sizes ranging from small, medium to large)

d. More if you have

You need to include two figures describing the structure of your MPI program and Pthread program.

The report should be in appropriate format, with a title page, introduction session to introduce the basic problem and task, method session to describe your parallel implementation, result session to compare performance under different configurations, and a conclusion session which concludes your experiment results.

Tips

When measuring the running time of the program, make sure only measure the computation time. (Because asg2 or xlib’s drawing are time consuming.)

Debug your program on the VM that is built on the image centos. Make sure the program is OK

Make sure use ‘sbatchʼ command to submit your jobs onto the master machine, do not directly run your program on the master machine.

Try to limit your program running time within 60 seconds. If your program is running slow, try to improve your code or reduce the imageʼs size.

If you are using xlib to draw the image. Remember to add a -lX11 flag when compiling your code.

Where and What to Turn in Your Homework

Please turn in a zip file includes

report code

zip your source codes and paper in a zip file, and name it studentID.zip, then submit it on Black board.
