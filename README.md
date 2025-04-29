# cs161-fundamentals-of-artificial-intelligence-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS161: Fundamentals of Artificial Intelligence Assignment 2  Solved](https://www.ankitcodinghub.com/product/cs161-fundamentals-of-artificial-intelligence-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;54827&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS161: Fundamentals of Artificial Intelligence  Assignment 2&nbsp; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Questions</h1>
<ol>
<li>A search tree can be represented in LISP as follows:</li>
</ol>
<ul>
<li>if the search tree contains a single leaf node <em>L</em>, it can be represented by atom L</li>
<li>if the search tree has more than one node and is rooted at <em>N</em>, then it can be represented by a list (S1 S2 … Sk) where Si represents the <em>i</em>th subtree of <em>N</em>.</li>
</ul>
Consider for example the following search trees, whose LISP representations are shown later.

o&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o

C&nbsp;&nbsp;&nbsp;&nbsp; T &nbsp;E&nbsp;&nbsp;&nbsp;&nbsp; A

A&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; H&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; R&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; EB

C

D

E

Write a single LISP function, called BFS. It takes a single argument FRINGE that represents a list of search trees, and returns a top-level list of leaf nodes, in the order they are visited by left-to-right breadth-first search. The inital call to BFS passes a FRINGE list with a single element: the root of the search tree.

Test your program on at least these inputs:

&gt; (BFS ’(ROOT))

(ROOT)

&gt; (BFS ’((((L E) F) T)))

(T F L E)

&gt; (BFS ’((R (I (G (H T))))))

(R I G H T)

&gt; (BFS ’(((A (B)) C (D))))

(C A D B)

&gt; (BFS ’((T (H R E) E)))

(T E H R E)

&gt; (BFS ’((A ((C ((E) D)) B))))

(A B C D E)

<ol start="2">
<li>This question aims to solve a problem stated by Homer Simpson in <em>“Gone Maggie Gone”</em>, The Simpsons, Season 20, Episode 13. Watch the clip at <a href="http://www.simpsonsworld.com/video/313361987548">http://www.simpsonsworld.com/video/313361987548</a><a href="http://www.simpsonsworld.com/video/313361987548">. </a>Homer wants to cross a river with his baby (Maggie), his dog (Santa’s Little Helper), and a jar of poison. Homer is the only one who can operate the boat, and he can take at most one thing with him. The dog cannot be left alone with the baby, because he tries to bite her. The baby cannot be left alone with the poison, because she tries to eat it. The goal is to get everybody on the other side of the river.</li>
</ol>
The file <strong>hw2-skeleton.lsp </strong>contains a framework for solving this puzzle using depth-first search. Implement the functions in it as described in the comments. <strong>DO NOT CHANGE THE FUNCTION</strong>

<strong>NAMES OR PARAMETERS. DO NOT WRITE ANY ADDITIONAL FUNCTIONS</strong>.

<u>Extra: </u>watch the clip at <a href="http://www.simpsonsworld.com/video/313359939855">http://www.simpsonsworld.com/video/313359939855</a><a href="http://www.simpsonsworld.com/video/313359939855">.</a> It illustrates what happens when the search problem formulation ignores important details of the ill-defined real-world problem, and how the problem formulation is only an abstraction.

&nbsp;
