# cs2110-homework-3-sequential-logic-state-machines-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 3-Sequential Logic & State Machines Solved](https://www.ankitcodinghub.com/product/cs2110-homework-3-sequential-logic-state-machines-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92764&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 3-Sequential Logic \u0026amp; State Machines Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1 Overview 1.1 Purpose

The purpose of this assignment is to practice implementing sequential logic circuits – from an RS Latch up to a Finite State Machine, using Circuitsim. You will build a register from the ground up. Then you will build a One Hot State Machine circuit, based on a provided state machine diagram (see Part 2 below). Then you will build a reduced state machine, using a K-Map to simplify your logic.

Objectives:

1. Understand how a register circuit works

2. To learn how to make a state machine

3. To become familiar with different state machine styles 4. To understand K-maps and simplification

1.2 Task

There are three parts to this assignment.

<ol>
<li>First, you will build a register in CircuitSim from the ground up.</li>
<li>Second, you will implement a one hot state machine Circuit in CircuitSim, based on the state transition diagram found below.</li>
<li>Third, you will complete a K-Map to simplify your state machine circuit, and implement the reduced state machine.</li>
</ol>
Please read the rest of this document for more detailed instructions and hints.

1.3 Criteria

Your grade is based on: 1) the correct outputs from your circuits; and 2) not using any banned components. For part 3 (reduced state machine), you will lose points if your circuit does not correspond to your K-Map or if your circuit is not minimal. The grade you see on Gradescope may not be the final grade you receive, as we may run additional tests on your submission.

You will submit three files to Gradescope: latches.sim; fsm.sim; and kmap.xlsx.

You may submit your code to Gradescope as many times as you like until the deadline. We will grade your last submission. We have also provided a local checker that you can test your code with. Please submit your code to Gradescope at least once prior to the deadline, to ensure you are not encountering any issues submitting at the last minute.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
2 Instructions

Part 1: For this part of the assignment you will build your own register from the ground up. • Implement your circuits in the “latches.sim” file

Part 2: Given a simple state diagram, you will build a state machine in CircuitSim using the “one-hot” style of building state machines.

• The circuit will be implemented in the “One Hot FSM” subcircuit of the “fsm.sim” file

Part 3: Given the same state diagram from part 1, you will be minimizing the logic by using K-Maps.

• Fill out the K-Maps located in the spreadsheet named “kmap.xlsx”

• The reduced circuit will be implemented in the “Reduced FSM” subcircuit of the “fsm.sim” file

Do not change/delete any of the input/output pins.

For parts 2 and 3 of this homework, you must use exactly 1 register. These are found under the Memory tab in CircuitSim. Failure to do so may result in large point deductions.

2.1 Part 1

For this part of the assignment you will build your own register from the ground up. For more information about each subcircuit refer to your textbook.

2.1.1 RS Latch

You will start by building a RS latch using NAND gates, as described in your textbook. The RS Latch is the basic circuit for sequential logic. It stores one bit of information, and it has 3 important states:

<ol>
<li>R=1 S=1 : This is called the Quiescent State. In this state the latch is storing a value, and nothing is trying to change that value.</li>
<li>R=1 S=0 : By changing momentarily from the Quiescent State to this state, the value of the latch is changed so that it now stores a 1.</li>
<li>R=0 S=1 : By changing momentarily from the Quiescent State to this state, the value of the latch is changed so that it now stores a 0.</li>
</ol>
Once you set the bit you wish to store, change back to the quiescent state to keep that value stored.

Notice that the circuit has two output pins; one is the bit the latch is currently storing, and the other is the opposite of that bit.

Note: In order for the RS Latch to work properly, you must not set both R and S to 0 at the same time.

• Build your circuit in the “RS Latch” subcircuit in the “latches.sim” file 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2.1.2 Gated D Latch

Using your RS latch subcircuit, implement a Gated D Latch as described on the textbook.

The Gated D Latch is made up of an RS Latch as well as two additional gates that serve as a control. With that addition not only can we control what value is stored by the latch, but also when that value will be saved.

The value of the output can only be changed when Write Enable is set to 1. Notice that the Gated D Latch subcircuit only has one output pin, so you should disregard the inverse output of your RS Latch.

• Implement this circuit in the “Gated D Latch” subcircuit in the “latches.sim” file

• You are not allowed to use the built-in SR Flip-Flop in CircuitSim to build this circuit

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2.1.3 D Flip-Flop

Using the Gated D Latch circuit you built, create a D flip-flop.

A leader-follower D flip-flop is composed of two Gated D latches back to back, and it implements edge triggered logic.

Your D flip-flop output should be able to change on the rising edge, which means that the state of the D Flip-Flop should only be able to change at the exact instant the clock goes from 0 to 1.

• Implement this circuit in the “D Flip-Flop” subcircuit in the “latches.sim” file. 2.1.4 Register

Using the D Flip-Flop you just created, build a 4-bit Register. Your register should also use edge-triggered logic. The value of the register should change on the rising edge.

• This circuit will be implemented in the “Register” subcircuit in the “latches.sim” file

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
2.2 Part 2

For this part of the assignment you are given the state machine transition diagram of a new video game that is currently in the early stages of production. The game has a start state, game state, victory state, and defeat state. Our game manager has one input button which is either pressed (G) or not pressed (G!). This computer has six outputs (A, B, C, D, E, F) that affect the screen, music, and animations the game plays for the user.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>You will be implementing this state transition diagram as a circuit using the one-hot style. Remember for one-hot you will have a register with the number of bits being the number of states of the FSM. Each bit corresponds to a state, and you are in that state if the corresponding bit is a 1. Since you can only be in one state at a time, exactly one of the bits can be 1 at each time (except when the machine starts up, when all the bits will be 0).</li>
<li>You must implement this using one-hot. A template file fsm.sim has been given to you. Implement the state machine in the provided “one-hot state machine” subcircuit.</li>
<li>Note that there are 3 inputs to the “One Hot FSM” subcircuit: CLK, G, and RST. The CLK input turning off and on repeatedly will be used to represent clock ticks in your circuit. The G input corresponds to whether or not G is on, as in the diagram above. RST resets the circuit (clears all the bits of your state register).</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
2.3 Part 3

Take a look at this state machine transition diagram:

</div>
</div>
<div class="layoutArea">
<div class="column">
• First, produce the K-maps for the state diagram above on the provided spreadsheet named “kmap.xlsx”. Use the K-maps to produce the reduced Boolean expressions for the state machine.

The inputs for each K-map are:

– S0 = Current state least significant bit – S1 = Current state most significant bit – G = Input button

The outputs make K-maps for are:

– N0 = Next State least significant bit – N1 = Next State most significant bit – A,B,C,D,E,F

Please Note: This State Machine is a Moore State Machine, meaning that the output values are determined solely by the current state (you should not use the N1 and N0 outputs or the G input for determining the values for A, B, C, D, E, F .

<ul>
<li>– &nbsp;You will fill out one K-map per output and one per next state bit for a total of 8 K-maps (A, B, C, D, E, F, N0, N1). The respective K-maps are located in the kmap.xlsx file.</li>
<li>– &nbsp;Your K-map must give the best solution groupings possible to receive full credit. This means you must select the optimal values for any don’t cares (if applicable) in your K-maps to do this.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
– It may be helpful to check with others on Piazza to see if your circuit is optimal. In order to do this without giving away your answer you may share the number of AND and OR gates used.

– IMPORTANT: The K-maps will be autograded. Because of this, there are a set of restrictions to how you must fill your K-maps to ensure you get full credit:

<ul>
<li>∗ &nbsp;When you fill the row and column headers for your K-maps, you may only use the following variable names: S0, S1, and G. To negate a variable, you must use an apostrophe. Two adjacent variables with nothing in between are interpreted as an AND.

Example label: S0′G</li>
<li>∗ &nbsp;When writing the Boolean expressions resulted from your K-map groupings, you must use the same rules as the previous bullet point, but also use ”+” for OR.

Example grouping: For the Boolean expression (NOT S0) OR (S1 AND G), write S0′+S1G</li>
<li>∗ &nbsp;When filling in the cells of your K-map table, you must use 0, 1, and x.</li>
</ul>
<ul>
<li>Implement this circuit in the “Reduced FSM” subcircuit of the provided fsm.sim file. You will lose points if your circuit does not correspond to your K-map or if your circuit is not minimal. You should use only the minimal components possible to implement the state machine.</li>
<li>HINT: We recommend you make a truth table for the state machine to help organize the logic, and then transfer your answers to the K-maps. We’ve provided truthtable.xlsx to help with this.
Note: You are not required to complete truthtable.xlsx or submit it anywhere; it is only provided for convenience when making your K-maps.

3 Testing

To test your circuits locally, navigate to the directory with the latches.sim and fsm.sim files and run the tester JAR file with

<pre>    java -jar hw03-tester.jar
</pre>
Make sure to run the local autograder in a terminal in Docker.

To test your K-maps, please submit your kmap.xlsx to the “Homework 3: K-maps” assignment on Grade- scope.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
