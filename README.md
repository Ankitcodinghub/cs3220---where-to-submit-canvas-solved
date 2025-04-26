# cs3220---where-to-submit-canvas-solved
**TO GET THIS SOLUTION VISIT:** [CS3220 – Where to submit: Canvas Solved](https://www.ankitcodinghub.com/product/cs3220-where-to-submit-canvas-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126091&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3220 - Where to submit: Canvas Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
CS 3220 Homework#2: Synchronous FIFO

(3 points)

In this assignment, you will implement a synchronous FIFO in Verilog.

$ git clone https://github.com/gt-cs3220/gt-cs3220.github.io.git $ cd gt-cs3220.github.io/Spring_2023/

A FIFO is a structure that stores data and handles the input-output in first-in first-out fashion. Important points to note: 1. All actions synchronized to positive edge of “clk” signal. 2. “rst_n” is active high 3. “o_data” always points to the head of the FIFO

Parameters: 1. FIFO_DEPTH: Depth of the FIFO buffer 2. DATA_WIDTH: width of the data packets

Input signals: 1. “push”: Read the data from “i_data” and add it to FIFO 2. “pop” : Remove the data from the head of the FIFO. NOTE: o_data must point to the head at all times. After the “pop” action, it will point to head+1.

Output signals: 1. “empty”: Asserted if the FIFO is empty 2. “full” : Asserted if the FIFO is full

Critical functionality: 1. When the FIFO is “full,” and another packet is pushed into the FIFO, then FIFO should ignore the packet. 2. When the FIFO is “empty” and a “pop” signal is sent, ensure that the FIFO signal still says it is empty.

HINT: Use pointers to track the head and tail of the FIFO.

We have provided the skeleton code for the module (fifo.v).

NOTE: DO NOT CHANGE THE PORT OR MODULE DEFINITIONS. Implement functionality for the main buffer structure in the FIFO and functionality for handling all status signals.

We have provided the testbench code (fifo.cpp).

1. Follow instructions from hw1part2 to compile the verilog code, run the testbench and view the waveforms. e.g.) verilator -Wall –trace –exe –build -cc fifo.v fifo.cpp

OR 2. Use the makefile provide to build and run the code. make (will compile, build and execute the testbench) What to submit: 1. fifo.v

How to test the correctness: Testbench runs on the verilog module without errors.

Grading Policy:

(3 points) If you pass the provided test code.

Partial grading Policy: Partial grade points are very limited.

FAQ [Q] When I compile the files, it generates errors. What should I do? [A] You need to complete the code. The provided code is incomplete, so it will generate errors

[Q] Can I modify fifo.cpp file? [A] Yes, you can modify it to add more prints or other test cases

[Q] How can I debug the internal wires? [A] Please look at the trace to see all wire values in the module.

[Q] Do I need to test other test cases? [A] We will use the same test case as the provided code.
