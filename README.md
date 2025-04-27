# elec-3300-solved
**TO GET THIS SOLUTION VISIT:** [ELEC 3300 Solved](https://www.ankitcodinghub.com/product/elec-3300-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123883&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ELEC 3300 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
LAB 2: I/O INTERFACE, INTERRUPT FUNCTION OF ARM

A. OBJECTIVE:

1. To familiarize yourself with the MINI-V3 Development Board.

2. To understand the basic input/output of the microcontroller.

3. To understand the difference of polling and interrupt.

B. PRE-LAB ASSIGNMENT:

1. Study the information about MINI-V3 Development Board from the course website.

2. Study the information about Fire Debugger from the course website.

3. Study the information about STM32CubeMX from the course website.

4. Study the Tutorial for LAB2, and Tutorial for CubeMX.

C. LAB SETUP DETAILS

1. Connect the Fire Debugger according to the information about Fire debugger. Make sure that the Green LED of the Fire Debugger is ON.

2. Follow the Tutorial for CubeMX, generate a Project for Task 1 using CubeMX.

3. Follow the Tutorial for CubeMX, generate another Project for Task 2 and 3 using CubeMX.

D. EXPERIMENT

In this LAB, there are 3 tasks.

Task 1 – Generate a BINKING LED Project using CubeMX.

Task 2 – Implementation of the polling I/O

In the while(1) loop of main.c, implement a polling method that using External Key to toggle the RGB LED in order.

Task 3 – Implementation of the interrupted I/O

In main.c, and modify the stm32f1xx_hal_gpio.c, implement an interrupt driven method that will toggle the external LED when K1 is pressed.

E. PROCEDURE

Task 1 – Generate a BINKING LED Project using CubeMX

Follow the Tutorial of CubeMX, generate a blinking LED on PB.5.

For Task 2 and Task 3, we will be using one RGB LED, K1 button from the MINI-V3 Development Board, one external LED and one external Key. Please refer to Tutorial for LAB2 for information.

Task 2 – Implementation of the polling I/O

In the while(1) loop of main.c, implement a polling method that using External Key to toggle the RGB LED in order.

1

Task 3 – Implementation of the interrupt I/O

In main.c, and modify the stm32f10x_it.c, implement an interrupt driven method that will toggle the external LED when K1 is pressed.

Modify the function so that whenever K1 is pressed, the External LED will toggle.

Rebuild, download the run your program. Verify that when you pressing K1, the External LED will toggle. At the same time, your Task 2 Code should still work. (i.e. pressing the External Key will toggle the RGB LED in order)

2
