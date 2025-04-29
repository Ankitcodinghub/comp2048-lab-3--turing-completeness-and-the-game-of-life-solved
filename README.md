# comp2048-lab-3--turing-completeness-and-the-game-of-life-solved
**TO GET THIS SOLUTION VISIT:** [COMP2048 Lab 3- Turing Completeness and the Game of Life Solved](https://www.ankitcodinghub.com/product/comp2048-turing-completeness-and-the-game-of-life-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116146&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2048 Lab 3- Turing Completeness and the Game of Life Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

The Game of Life (GoL) simulation can be thought of as a form of cellular automation originally developed by John Conway. The game involves a set of cells within an 𝑁𝑁×𝑁𝑁 grid whose state is either alive or dead (i.e. 1 or 0 respectively). The grid effectively represents the ‘universe’ that will be simulated and the alive cells the life within it. The game is governed by a set of simple rules that dictate the next state of each cell in this universe depending on its current state and the states of its neighbours. The rules of GoL depend on the 8-connected neighbours of a cell as follows:

1. Underpopulation: A live cell that has &lt; 2 live neighbouring cells will die

2. Survival: A live cell that has 2-3 live neighbouring cells will remain alive

3. Overpopulation: A live cell with more than 3 live neighbours will die

4. Reproduction: A dead cell with exactly 3 live neighbours will become alive

The game begins with an initial state of the universe with a pattern of live cells. The universe is evolved by applying the above rules to each cell of the universe to determine the next iteration of the simulation. The evolution of the universe is observed by continual computing the next iteration of the universe. See chapter 7, section 7.6.4 of (Moore and Mertens, 2011) for more theoretical details.

In this laboratory, you will create a simulation of the GoL using Python based on an initial class provided. In the following parts of the lab, you will be required to code up the algorithms related to the computation, importation and evaluation of the GoL.

Important Notes

For this practical you will need to install/already have numpy, scipy and matplotlib on your machine. Use either Anaconda Python or WinPython to have these setup for you quickly and hassle free. See my video series on setting up Python environments on Windows for help.

For this practical, we will only accept solutions in Python and all animations must be in matplotlib (not tkinter or turtle, etc).

An initial class called “conway.py” is provided with the necessary hooks required for this part of the lab. An example test script is provided that enables the animation of the simulation. Another script is also provided without animation for debugging purposes, especially for implementing the GoL rules.

——————————-

[See scripts conway.py, test_gameoflife_glider_simple.py and test_gameoflife_glider.py]

(1 Mark) c) Change the initial pattern to the glider gun (already implemented in conway.py) and run the animation. What should you get and what is wrong? Fix the glider gun pattern so that its runs correctly. Hint: One of the lines for the glider gun member is incorrectly alive.

An initial class called “rle.py” is provided with the necessary hooks required for this part of the lab. An example test script is provided that enables the running of the relevant patterns.

——————————-

[See scripts conway.py, rle.py and test_gameoflife_turing.py]

e) Implement a fast method for computing the weights for the rules based on convolution and run a large simulation (𝑁𝑁&gt;1024) with an appropriately large pattern (at least of the order of 𝑁𝑁⁄4 or one that is acceptable to your demonstrator).

g) Demonstrate a running GoL Turing Machine pattern by using your RLE reader from the previous section to load and run the pattern.

(1 Mark) h) Given the Turing machine pattern runs within GoL, comment on whether GoL is Turing complete. Justify your answer by referencing the theory of Turing machines and the different components of the Turing machine pattern provided using this link.

Interesting Links

Shakes’ Windows Deep Learning Python Setup Series

<iframe title="Windows Deep Learning Python Setup" width="980" height="551" data-src="https://www.youtube.com/embed/videoseries?list=PLC0kkV5axv-X4OpBHlIPlIz15XNNGd3OE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" data-load-mode="1"></iframe>

Video of an 8-bit Programmable computer in GoL! https://www.youtube.com/watch?v=8unMqSp0bFY

Various GoL and Langton’s Ant videos on the course Computation YouTube Playlist https://www.youtube.com/playlist?list=PLC0kkV5axv-X3JOXeHGoedTMCXGakoYmt

References
