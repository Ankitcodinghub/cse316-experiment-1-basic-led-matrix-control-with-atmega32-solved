# cse316-experiment-1-basic-led-matrix-control-with-atmega32-solved
**TO GET THIS SOLUTION VISIT:** [CSE316 Experiment 1-Basic LED matrix control with ATmega32 Solved](https://www.ankitcodinghub.com/product/cse316-experiment-1-basic-led-matrix-control-with-atmega32-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96794&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE316 Experiment 1-Basic LED matrix control with ATmega32 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Basic LED matrix control with ATmega32: static and rotating display.

Goal:

To understand basic LED matrix control in order to generate different characters/symbols.

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig. 1: 8×8 LED Matrix

Experimental Tools And Materials:

ATmega32, Red LED matrix, Push Buttons.

Experiment:

The experiment has the following parts.

● First, you have to show a symbol in the LED matrix. The symbol will be

assigned by the lab teachers. This is the static mode.

<ul>
<li>● &nbsp;Second, you will left/right/up/down rotate the symbol. The direction will be
assigned by the lab teachers. This is the rotating mode.
</li>
<li>● &nbsp;If the button is pushed, you have to toggle between static mode and rotate mode.
You have to use Interrupt for that. The interrupt specs will be assigned by the lab teachers.

Your Specification: MC Experiment 2 – Individual Spec

You can connect the LED matrix to any of the ports of your choice.
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
LED Matrix Basics:

There are 8 pins in total to select which LED(s) we want to light up. 8 of the pins are used to select the row(s), while the remaining 8 pins are used to select the column(s) (The notion of row and columns are only artificial and depends on the way we consider the orientation of the LED matrix. Rotating the matrix by 90 degrees will alter the orientation. We will be using the default orientation of the Proteus).

Fig. 2: 8×8 LED matrix display and its internal structure

Let’s say, columns pins are C1-C8 and row pins are R1-R8. Let’s name 64 LEDs as LED(row,column), e.g. LED(1,1)-LED(8,8).

If you want to light up LED(1,1), you have to connect C1 to HIGH and R1 to LOW.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Let’s connect all pins to LOGICSTATEs and see some examples.

If you want to light up the first column, set C1 to HIGH and all of R1-R8 to LOW.

</div>
</div>
<div class="layoutArea">
<div class="column">
Similarly, if you want to light up column 7, set C7 to HIGH and R1-R8 to LOW.

</div>
</div>
<div class="layoutArea">
<div class="column">
If you set C7 to HIGH, R1-R2 to LOW, R3-R6 to HIGH and R7-R8 to LOW, you will get this. Only LED(1,7), LED(2,7), LED(7,7) and LED (8,7) is on.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Showing a symbol in dot matrix:

Typically multiplexing is used to display arbitrary patterns with led matrices. Multiplexing is sometimes also called scanning. In column multiplexing, it scans columns (usually from left to right) and turns on the selected LEDs only in one row at a time following these steps:

<ul>
<li>● &nbsp;Turn on only the leftmost column (i.e., set HIGH)</li>
<li>● &nbsp;Turn on the necessary rows of the leftmost column by setting the corresponding
row pins to LOW. This lights up the selected LEDs in the leftmost column.
</li>
<li>● &nbsp;Do steps 1 and 2 one by one for all columns and keep repeating.
If you do this slowly, you would see the LED rows turning on one after another. However, if it is done fast enough, the human eye will see the whole pattern together. This phenomenon is called persistence of vision.

The amount of time you light up one row, before lighting up the next one is very crucial for the symbol to be displayed properly. Usually you will light up one row and then create a delay. After the delay is over you will light up the next row. If this delay is too long, one will see the rows being lit up one after another and the illusion of displaying the whole symbol at once will not work. On the other hand, if the delay is very small, the LEDs will not get enough time to glow fully. Hence, the symbol will look less bright. In the experiment you will have to find a near optimal delay on trial and error basis, so that the symbol is displayed bright and clear.

Why multiplexing:
</li>
</ul>
<ul>
<li>● &nbsp;There are 64 bicolor LEDs in a dot matrix, without multiplexing we would have needed 64 different pins to operate a single dot matrix! Using multiplexing technique we can still operate it with only 16 pins.</li>
<li>● &nbsp;Also, without multiplexing, we would have to turn on all the necessary LEDs together. That would have consumed a lot more energy. In multiplexing, we are only turning on at most 8 LEDs at a time.
Example:

Say, you want to show the following pattern,
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
You have to start from the leftmost column. Then for each column turn on the necessary LEDs by setting corresponding row pins to LOW.

Rotate a Symbol:

Show a symbol for some time (say, 100 ms). Then according to the direction assigned to you, rotate the symbol. After each button press you have to toggle between static mode and rotating mode. Here’s a demo of what we expect. MC Experiment 2 – LED Matrix Demo.mkv . This one displays ‘A’ and rotates to the right.

Procedure:

1. In Proteus, connect the LED matrix to the ATmega32.

2. Write a C program to implement, static display, rotating display and mode change

by button press.

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Submission:

Open a folder with your 7 digit student ID. Copy these 2 files

<ol>
<li>Proteus Project file (.pdsprj)</li>
<li>C Code (.c)</li>
</ol>
Zip the folder. Submit the 1705xxx.zip.

Special Notes (11-04-2021):

You have to keep the matrix in the default orientation. In the real world, you are absolutely allowed to orient the matrix to your preferences to make your code easier. However, we are imposing the default orientation just to test your understanding.

Miscellaneous:

<ul>
<li>● &nbsp;Further details on working with LED matrices: How Does Led Matrix Work?</li>
<li>● &nbsp;Some pins of PORTC can not be used for I/O directly. First the JTAG has to be turned off.
One way is to uncheck the JTAG box while writing the fuse bits, the second is to write a 1 to the JTD bit twice consecutively. MCUCSR = (1&lt;&lt;JTD); MCUCSR = (1&lt;&lt;JTD);

For more details refer to: JTAG enabling/disabling in ATmega32 and fuse settings-SOLVED
</li>
</ul>
</div>
</div>
</div>
</div>
