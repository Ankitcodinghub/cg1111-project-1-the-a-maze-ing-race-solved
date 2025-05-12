# cg1111-project-1-the-a-maze-ing-race-solved
**TO GET THIS SOLUTION VISIT:** [CG1111 Project 1-The A-maze-ing Race Solved](https://www.ankitcodinghub.com/product/cg1111-project-1-the-a-maze-ing-race-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91296&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CG1111 Project 1-The A-maze-ing Race Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column">
&nbsp;

Welcome to the grand project of CG1111: The A-maze-ing Race!

In this race, your mBot needs to find its way through a maze in the shortest time. Similar to its namesake TV program, your mBot will be facing a number of challenges at intermediate waypoints while attempting to complete the race. To successfully meet all the requirements, you need to have a good grasp of many of the principles you have learnt in CG1111 and apply them into good practice!

The following are the key requirements:

<ol>
<li>The mBot must not bump into any wall. Your mBot shall rely on a front ultrasonic sensor, and two side IR proximity sensors to accomplish this. You also need to come up with your own algorithms to meet this requirement. Note that there will be penalty points for bumping into walls, even if your mBot doesn’t get stuck.</li>
<li>All turns in the maze are dictated by the waypoint challenges. Your mBot must not make any automatic turn without decoding a challenge.</li>
<li>At each waypoint challenge, there will be a black strip (about 4 cm by 21 cm) on the maze floor. Your mBot needs to detect the black strip, stop, solve the challenge above it, and act according to the turn instruction decoded from the challenge.</li>
<li>There are two types of challenges that dictate the turns at the waypoints:</li>
</ol>
(i) Colour-sensing Challenge:

Your mBot already has two RGB LEDs and one LDR built on its mCore. You need to use them to implement colour-sensing. (Note that you need to remove the top cover of your mCore to accomplish this.) Depending on the colour of the paper that your mBot senses above it, it needs to execute one of the following five types of turns:

Table I summarizes how the colours are to be interpreted. Setups with colour samples for each type of turn will be provided in the lab. Note that the colour paper will be suspended at a height of about 14 cm from the maze floor. Hence, your mBot’s maximum height (including all the wires and other components) must not be taller than 14 cm.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Table I: Colour interpretation for the Colour-sensing Challenge

</div>
</div>
<div class="layoutArea">
<div class="column">
Colour

</div>
</div>
<div class="layoutArea">
<div class="column">
Interpretation

</div>
</div>
<div class="layoutArea">
<div class="column">
Left-turn

Right turn

White 180° turn within the same grid

Two successive left-turns in two grids Two successive right-turns in two grids

(ii) Sound-based Challenge:

At this challenge waypoint, there will be a speaker suspended above the mBot that plays two frequency tones (fA = 300 Hz, and fB = 3000 Hz) that are superimposed together. Depending on the relative loudness of fA with respect to fB, the mBot needs to execute one of the following three types of turns.

Table II: Interpretation of Relative Loudness for the Sound-based Challenge

</div>
</div>
<div class="layoutArea">
<div class="column">
Red

</div>
</div>
<div class="layoutArea">
<div class="column">
Green

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Orange

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Blue/cyan

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Case

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Relative Loudness

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Interpretation

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 fA louder than fB

2 fB louder than fA

3 fA and fB have about the same loudness

</div>
<div class="column">
Left-turn

Right turn

180° turn within the same grid

</div>
</div>
<div class="layoutArea">
<div class="column">
Table II summarizes how the relative loudness of the two frequency tones are to be interpreted. Note that for cases 1 and 2, when one frequency tone is louder than the other, we will ensure in our sound sample that the louder frequency tone is at least 9 dB louder than the softer frequency tone. Setups with the sound samples for each type of turn will also be provided in the lab.

5. End of Maze:

At the end of the maze, there will also be a black line. The colour of the paper above the mBot at this point will be black. Upon decoding that no turn action needs to be taken for both colour-sensing challenge and sound-based challenge, the mBot shall interpret this as the end of the conquest and play a celebratory tune of your choice (Yay!).

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
Final Project Evaluation:

The race will be conducted during your Week 13 Studio 2 timeslot:

Group 1: 14 Nov, 9am-12pm Group 2: 14 Nov, 2pm-5pm Group 3: 15 Nov, 9am-12pm

Rules:

<ol>
<li>At each challenge, if your mBot turns in the wrong direction, it will be teleported to one grid before the challenge to make a second attempt while the clock continues to run. If it fails in its second attempt, it will be manually turned to the correct direction, and an additional penalty time of 30 seconds will be added.</li>
<li>You are not allowed to add any commercial-off-the-shelf sensors that are not issued by the DSA Lab.</li>
<li>The actual maze layout for the A-maze-ing race will not be revealed until the race. The figure below shows a sample maze layout.</li>
<li>The group that completes the maze in the shortest time wins a delicious prize (through the courtesy of your instructors)!</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Grading Criteria:

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Criterion

</div>
</div>
</td>
<td></td>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
Marks

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Meeting the required features 15 Algorithms and coding (e.g., elegance of 5 algorithms, well commented codes, etc.)

Short group report 5 Total 25

Deliverables (Report and Source Codes):

Deadline: 19 Nov 2018 (Monday), 2359 hrs

(10% will be deducted for every day it is late)

Zip all files into a single file, and name it according to your Section and Group numbers (You can find your Section and Group numbers from IVLE), e.g., Section A – Group 01.zip, and upload it into IVLE Workbin under the “Project Submission” folder before the deadline. You must include the following:

<ol>
<li>Program source codes. The codes must be well documented by providing appropriate comments.</li>
<li>A concise written report, in PDF format. You may use your own discretion for the number of pages. Your report must describe your design in detail, especially about how the required features are met.</li>
</ol>
Peer Evaluation:

You will submit a confidential peer evaluation form about your groupmates’ contribution in the project. More details will be announced at a later date. If there is any groupmate who is not contributing to the project, please inform us as early as possible.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Resources and Tips:

<ol>
<li>You can download the latest Makeblock libraries from the following link:
https://github.com/Makeblock-official/Makeblock-Libraries.

Copy the “makeblock” folder to your Arduino IDE’s default library location. Your Arduino IDE’s library folder should now look like this:

<ul>
<li>(on Windows): [arduino installation directory]\libraries\makeblock\src</li>
<li>(on MACOS): [arduino Package Contents]\contents\Java\libraries\makeblock\src
There are many code examples inside the subfolder “examples”, which will give you a head start on how to work with the different components on your mBot (e.g., RGB LEDs, LDR, line sensor, DC motors, speaker, etc.).
</li>
</ul>
</li>
<li>The schematic for your mCore can be downloaded from this link:
https://github.com/Makeblock-official/mBot_Firmata/blob/master/hardware/mCore.pdf
</li>
<li>The datasheet for your electret microphone can be downloaded from this link:
http://www.farnell.com/datasheets/50039.pdf?_ga=2.170247846.786460716.1540354873- 1082133259.1539236531
</li>
<li>When mounting your breadboard with the audio processing circuits on top of your mBot, ensure that it does not cover the RGB LEDs and the LDR on your mCore. Otherwise it may affect your mBot’s performance in the colour-sensing challenge.</li>
<li>You need to ensure that your batteries are properly charged. If their voltage gets too low, your mCore’s 5V line may be less than 5 V. This could affect your calibrations.</li>
<li>To tackle the sound-based challenge, you need to build two active bandpass filters with peak detectors. Since your mBot only has 0 V and 5V, you will power your op-amp using just the positive power rail. Include a variable resistor in each of the two bandpass filter circuits, so that you can tune its gain.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
