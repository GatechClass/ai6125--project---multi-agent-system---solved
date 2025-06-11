# ai6125--project---multi-agent-system---solved
**TO GET THIS SOLUTION VISIT:** [AI6125 -PROJECT – Multi-agent System – Solved](https://mantutor.com/product/ai6125-project-multi-agent-system-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86272&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AI6125 -PROJECT - Multi-agent System  - Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The purpose of this project is to:

<ul>
<li>Make students familiar with a popular toolkit for the modelling and simulation of agent-based systems.</li>
<li>Provide students the opportunity to experiment with different agent designs for a popular agent- based testbed.</li>
</ul>
&nbsp;

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; SPECIFICATION</h1>
The aim of this exercise is to use the MASON agent toolkit (Java-based tool) to implement an agent which can inhabit and perform in the provided Tileworld system. You are free to implement any type of agent you desire using any algorithms you would like. This will be conducted in teams of 3-4 students, with each team member designing and implementing one agent. Your agent team (3-4 agents) will then perform together in the same Tileworld.

&nbsp;

<h2>2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; MASON</h2>
MASON is a widely used, open-source, cross-platform, agent-based modelling and simulation toolkit that was originally developed at George Mason University. It is written in Java and has extensive online tutorials and examples. Before the implementation, it is recommended that you spend some time going through the manual of MASON (Section 1.1 and Section 2.1-2.12) yourself. The manual and other related materials can be obtained from the following link: https://cs.gmu.edu/~eclab/projects/mason/. By reading the recommended sections of the manual, you should have a basic understanding of the architecture of MASON and its working flow.

&nbsp;

<h2>2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Tileworld</h2>
In this project, you will use Tileworld as a canonical reference for an agent-based model to implement. Tileworld is a chessboard-like grid on which there are agents, tiles, obstacles, holes, and a fuel station. See Figure 1 for an example.

<ul>
<li>An <strong>agent </strong>is able to move up, down, left or right, one cell at a time.</li>
<li>A <strong>tile </strong>is a unit square which can be carried by the agent.</li>
<li>An <strong>obstacle </strong>occupies a grid cell and is immovable, agents cannot occupy the same cell as an obstacle.</li>
<li>A <strong>hole </strong>is a grid cell which can be filled in by a tile.</li>
<li>The <strong>fuel station</strong> is a grid cell where agents can refuel.</li>
<li>The <strong>reward </strong>is obtained by: when the tile is moved on top of the hole cell, the tile and hole cell disappear, which leaves a blank cell. This means a hole is filled and the agent gets a reward.</li>
</ul>
In this project, you have to develop an agent for the Tileworld domain. We have uploaded two papers about the Tileworld domain to NTULearn, i.e. “A history of the Tileworld agent testbed” and

“Introducing the Tileworld: Experimentally evaluating agent architectures”. You may study them to gain a better understanding about the domain.

&nbsp;

&nbsp;

<h2>2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Implementing the Agent</h2>
The source file of the Tileworld implementation can be downloaded from NTULearn. To compile and run the Java program, you need to meet the following conditions:

<ul>
<li>Install Java JDK and the JDK version should be 1.8.</li>
<li>Install the Java3D library (version 1.5). You can download the library file here:</li>
</ul>
<a href="https://www.oracle.com/java/technologies/javase/java-3d.html">https://www.oracle.com/java/technologies/javase/java</a><a href="https://www.oracle.com/java/technologies/javase/java-3d.html">–</a><a href="https://www.oracle.com/java/technologies/javase/java-3d.html">3d.html</a> and install the library following: <a href="https://download.java.net/media/java3d/builds/release/1.5.1/README-download.html">https://download.java.net/media/java3d/builds/release/1.5.1/README</a><a href="https://download.java.net/media/java3d/builds/release/1.5.1/README-download.html">–</a><a href="https://download.java.net/media/java3d/builds/release/1.5.1/README-download.html">download.html</a><a href="https://download.java.net/media/java3d/builds/release/1.5.1/README-download.html">.</a>

<ul>
<li>Download the MASON_14.jar file from NTULearn and use this jar file as the external library for compiling and running. Note that the latest MASON.20.jar file from MASON website is not compatible with the given Tileworld implementation, and thus should not be used.</li>
</ul>
&nbsp;

<strong>2.3.1</strong><strong> Agent Specifications</strong>

Each student in a team needs to design one agent. The designed agent must adhere to the following specifications:

<ul>
<li>The agent can perceive only limited neighbouring cells. Mathematically, given the agent’s position (<em>x, y</em>) and an object’s position (<em>X, Y </em>), the object can be sensed only when <em>max</em>(<em>abs</em>(<em>x </em><em>− </em><em>X</em>)<em>, abs</em>(<em>y </em><em>− </em><em>Y </em>)) <em>≤ </em>3. See Figure 2 for an example.</li>
<li>The agent has a limited set of actions that it can take. That is, {WAIT, MOVE_UP, MOVE_DOWN, MOVE_LEFT, MOVE_RIGHT, PICK_UP, DROP, REFUEL}.</li>
<li>The agent can carry up to 3 tiles at a time.</li>
<li>Every movement consumes one fuel from the agent. Once there is zero fuel, the agent can no longer move and will become stuck.</li>
<li>The agent performs a Sense-Communicate (optional)-Plan-Act cycle once per time step.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

Figure 2: The visibility of an agent

&nbsp;

<ul>
<li>Your agent should inherit from the TWAgent class provided.</li>
<li>Your agents may communicate via message passing. As all agents belong to the same team, all messages are broadcasted to every agent. However, an agent can still specify the intended recipient(s) in the messages. Also, there is no communication range limit.</li>
</ul>
&nbsp;

&nbsp;

<strong>2.3.2</strong><strong> Modules Needed to be Implemented</strong>

To meet the above agent specifications and obtain a high reward in the game, you are expected to implement the following functions:

<ul>
<li>Planning module: in every step, the agent senses the objects around it and updates its memory. Based on the updated memory, the agent plans its action of current step. You can refer to the existing codes in “tileworld.planners” package and implement your own planner. A good planner is critical for obtaining a high reward.</li>
<li>Memory module (optional): the agent stores the previously sensed information in its memory and does planning based on its memory. Therefore, the memory module can affect the performance of the agent. The “TWAgentWorkingMemory.java” file implements a basic memory module. You may create your own memory module by extending the “TWAgentWorkingMemory” class.</li>
<li>Communication module (optional): in every time step, each agent can broadcast a message after it senses the environment. Currently, the “Message” class encodes each message. You can create your own message class by extending the “Message” class and use your own design to encode information. In the planning phase, your agent may use the messages from other agents for better planning. To retrieve all messages broadcasted in the current time step, just call the “getMessages()” method of the “TWEnvironment” class.</li>
</ul>
Note that to implement your own agent, you should create a new agent class by extending the “TWA- gent” class. In your own agent class, you can override the “communicate()”<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, “think()” and “act()” methods. You should <strong>NOT </strong>override the other methods of “TWAgent”, e.g. “sense()” (and related “TWAgentSensor” class), “putTileInHole()” etc. Also, you should <strong>NOT </strong>modify the “environment” package of the simulator and the “increaseReward()” method of “TWEnvironment” class can only be called in the “putTileInHole()” method of “TWAgent” class. Any violations will lead to the downgrade of your final score.

&nbsp;

&nbsp;

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ASSESSMENT</h1>
The assessment has two components:

<ul>
<li>A report for each team member (maximum 2000 words and 8 pages including images/plots) outlining the agent you designed and its implementation. The report is 40% of the whole course assessment. The report should include:
<ul>
<li>A background section on Tileworld.</li>
<li>Analysis of different designs of the agents your team have tried and developed (this part can be the same for different reports from the same group).</li>
<li>A detailed description of the agent you have developed and tested. In this part, you should specify the connections between your agent and the whole team, e.g. the role your agent plays.</li>
<li>The results you have achieved for different agent designs.</li>
</ul>
</li>
<li>A team based 20-minute presentation and demonstration of your agents. This will form part of a competition. The presentation and demonstration are 20% of the whole course assessment.</li>
</ul>
&nbsp;

<h2>3.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Experiments</h2>
Tileworld is characterized by a configurable environment. The number of tiles, holes and obstacles created in every time step can be specified. Each object also has a lifetime, i.e. the number of time steps that the object will persist for. The configurations are specified in the “Parameters.java” file. The competition will use 3 different environment configurations, two of which will be known to you and one of which will be unknown to you.

&nbsp;

<ul>
<li><strong>Configuration One:</strong>
<ul>
<li>Environment Size: 50 <em>× </em>50 cells</li>
<li>Average Object Creation Rate: NormalDistribution(<em>µ</em>=0.2, <em>σ</em>=0.05) <strong>–</strong> Lifetime: 100</li>
</ul>
</li>
<li><strong>Configuration Two:</strong>
<ul>
<li>Environment Size: 80 <em>× </em>80 cells</li>
<li>Average Object Creation Rate: NormalDistribution(<em>µ</em>=2, <em>σ</em>=0.5) <strong>–</strong> Lifetime: 30</li>
</ul>
</li>
<li><strong>Configuration Three:</strong>
<ul>
<li>Environment Size: ?<em>×</em>? cells</li>
<li>Average Object Creation Rate: ?(<em>µ</em>=?, <em>σ</em>=?)</li>
<li>Lifetime: ?</li>
</ul>
</li>
</ul>
&nbsp;

The following parameters are fixed in all cases:

<ul>
<li>Total Time Steps : 5000</li>
<li>Amount of fuel at beginning: 500</li>
</ul>
We will run 10 experiments for each configuration. For each experiment, we will use a different random seed.
