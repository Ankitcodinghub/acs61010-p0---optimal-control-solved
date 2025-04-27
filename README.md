# acs61010-p0---optimal-control-solved
**TO GET THIS SOLUTION VISIT:** [ACS61010 P0 – Optimal Control Solved](https://www.ankitcodinghub.com/product/acs61010-p0-acs61010-optimal-control-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124326&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ACS61010 P0 - Optimal Control Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
Assignment weighting 15%

How to submit

• Use the “Coursework (written solution)” link on Blackboard to submit your written solution.

• Use the “Coursework (MATLAB)” link on Blackboard to submit your Matlab files in a single ZIP archive.

Feedback Assignment Project Exam Help

Unfair means

See https://www.sheffield.ac.uk/ssid/unfair-means/index for guidance.

Extenuating circumstances

MATLAB help

• Matlab Onramp

• Solving Ordinary Differential Equations with Matlab

• Solving Boundary Value Problems with Matlab

• Tutorial on solving BVPs with BVP4C

Assignment briefing

r˙ = −V

where

• r is the radial distance from the Earth’s centre;

• V is the speed;

• m is the rocket mass;

• T ∈ [0,TM] is the thrust magnitude (control);

• D(r,V ) is the drag force (a function of r and V );

• g(r) is the gravitational acceleration atAssignment Project Exam Helpr;

• g0 is the gravitational acceleration at R⊕ (Earth radius);

c. The last two equations describing the booster dynamics imply

.

Assuming that D(r,V ) &lt; mg(r) (the gravity is stronger than the drag), show that the consumed fuel is a monotone increasing function of the final time. (Hint: You need to integrate both sides from 0 to tf and use V (tf) = 0.) What does this observation allow us to conclude about the relation between the solutions of the minimum-time and minimum-fuel problems?

d. The calculations above suggest that the optimal minimum-time control has the form

.

Write a Matlab program that solves the state equations for given ts and tf. Use this program to find the optimal values of ts and tf. Plot the optimal state.

When solving the state equations, assume that the drag force is given by

,

where

• CD = 0.3 is the drag coefficient;

• ρ(r) ≡ 1.225 kg/m3 is the air density (for simplicity we take it constant);

• S = 10.75 m2 is the reference area.

The gravitational acceleration is given by

,

where

• g0 = 9.8 m/s2 is the acceleration on Earth; • R⊕ = 6,371 km is the Earth radius. Assignment Project Exam Help

For the selected type of thruster, TM = 1,375.6 kN and.

x˙1 = x1 + x2, x1(0) = 2,

and the cost

a. Let α = 0 and x1(2) = 4. Express the optimal control in terms of the optimal costate. Write down the corresponding two-point boundary value problem. By solving this problem in Matlab (use bvp4c or bvp5c), find the optimal states and costates for β = 0,0.1,1,10,100. Plot your results in four subplots each showing one state/costate component for all β. For example, subplot(2,2,1) must show x1 for different β.

On the same axes but using dashed lines, plot the optimal states and costates for the case when α = 0 = β, x1(2) = 4, and x2(2) = 6. Add a legend, a title, and labels to each subplot.

(x1(2) − 1)2 + (x2(2) − 1)2 = 1.
