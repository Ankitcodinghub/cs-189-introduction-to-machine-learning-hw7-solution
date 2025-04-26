# cs-189-introduction-to-machine-learning-hw7-solution
**TO GET THIS SOLUTION VISIT:** [CS 189  Introduction to Machine Learning HW7 Solution](https://www.ankitcodinghub.com/product/cs-189-introduction-to-machine-learning-hw7-solution/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;32240&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS 189&nbsp; Introduction to Machine Learning HW7 Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<ol>
<li>Submit a PDF of your homework, with an appendix listing all your code, to the Gradescope assignment entitled “Homework 7 Write-Up”. In addition, please include, as your solutions to each coding problem, the specific subset of code relevant to that part of the problem. You may typeset your homework in LaTeX or Word (submit PDF format, not .doc/.docx format) or submit neatly handwritten and scanned solutions. Please start each question on a new page. If there are graphs, include those graphs in the correct sections. Do not put them in an appendix. We need each solution to be self-contained on pages of its own.
<ul>
<li>In your write-up, please state with whom you worked on the homework.</li>
<li>In your write-up, please copy the following statement and sign your signature next to it. (Mac Preview and FoxIt PDF Reader, among others, have tools to let you sign a PDF file.) We want to make it <em>extra </em>clear so that no one inadvertently cheats.</li>
</ul>
</li>
</ol>
<em>“I certify that all solutions are entirely in my own words and that I have not looked at another student’s solutions. I have given credit to all external sources I consulted.”</em>

<ol start="2">
<li>Submit all the code needed to reproduce your results to the Gradescope assignment entitled “Homework 7 Code”. Yes, you must submit your code twice: in your PDF write-up following the directions as described above so the readers can easily read it, and once in compilable/interpretable form so the readers can easily run it. Do NOT include any data files we provided. Please include a short file named README listing your name, student ID, and instructions on how to reproduce your results. Please take care that your code doesn’t take up inordinate amounts of time or memory. If your code cannot be executed, your solution cannot be verified.</li>
</ol>
<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Regularized and Kernel k-Means</h1>
Recall that in <em>k</em>-means clustering we attempt to minimize the objective

<em>k</em>

X X

min&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; k<em>x</em><em>j </em>− µ<em>i</em>k2, where

<em>C</em><sub>1</sub>,<em>C</em>2,…,<em>C</em><em>k&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>2

<em>i</em>=1 <em>x<sub>j</sub></em>∈<em>C<sub>i</sub></em>

µ<em>i </em>= argminµ<em>i</em>∈R<em>d </em><em>x</em>X<em>j</em>∈<em>C</em><em>i </em>k<em>x</em><em>j </em>− µ<em>i</em>k22 = |<em>C</em>1<em>i</em>| <em>x</em>X<em>j</em>∈<em>C</em><em>i x</em><em>j</em>, <em>i </em>= 1,2,…,<em>k</em>.

The samples are {<em>x</em><sub>1</sub>,…, <em>x<sub>n</sub></em>}, where <em>x<sub>j </sub></em>∈ R<em><sup>d</sup></em>. <em>C<sub>i </sub></em>is the set of sample points assigned to cluster <em>i </em>and |<em>C<sub>i</sub></em>| is its cardinality. Each sample point is assigned to exactly one cluster.

<ul>
<li>What is the minimum value of the objective when <em>k </em>= <em>n </em>(the number of clusters equals the number of sample points)?</li>
<li>(Regularized <em>k</em>-means) Suppose we add a regularization term to the above objective. The objective is now</li>
</ul>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <em>k </em>

Xλkµ<em>i</em>k X k<em>x</em><em>j </em>− µ<em>i</em>k22.



<table width="382">
<tbody>
<tr>
<td width="183">Show that the optimum of</td>
<td width="109"><em>i</em>=1 </td>
<td width="55"><em>x</em><em>j</em>∈<em>C</em><em>i</em></td>
<td width="35"></td>
</tr>
</tbody>
</table>
X

µmin<em>i</em>∈R<em>d </em>λkµ<em><sub>i</sub></em>k <em>x<sub>j</sub></em>∈<em>C</em><em>i </em>k<em>x<sub>j </sub></em>− µ<em><sub>i</sub></em>k<sup>2</sup><sub>2</sub>

is obtained at µ<em>i </em>= |<em>C</em><em>i</em>1|+λ P<em>x</em><em>j</em>∈<em>C</em><em>i x</em><em>j</em>.

<ul>
<li>Here is an example where we would want to regularize clusters. Suppose there are <em>n </em>students who live in a R<sup>2 </sup>Euclidean world and who wish to share rides efficiently to Berkeley for their final exam in CS189. The university permits <em>k </em>vehicles which may be used for shuttling students to the exam location. The students need to figure out <em>k </em>good locations to meet up. The students will then walk to the closest meet up point and then the shuttles will deliver them to the exam location. Let <em>x<sub>j </sub></em>be the location of student <em>j</em>, and let the exam location be at (0,0). Assume that we can drive as the crow flies, i.e., by taking the shortest path between two points. Write down an appropriate objective function to minimize the total distance that the students and vehicles need to travel. Hint: your result should be similar to the regularized <em>k</em>-means objective.</li>
<li>(Kernel <em>k</em>-means) Suppose we have a dataset {<em>x<sub>i</sub></em>}<em><sup>n</sup><sub>i</sub></em><sub>=1</sub>, <em>x<sub>i </sub></em>∈ R<sup>` </sup>that we want to split into <em>k </em>clusters, i.e., finding the best <em>k</em>-means clustering <em>without the regularization</em>. Furthermore, suppose we know <em>a priori </em>that this data is best clustered in an impractically high-dimensional feature space R<em><sup>m </sup></em>with an appropriate metric. Fortunately, instead of having to deal with the (implicit) feature map Φ : R<sup>` </sup>→ R<em><sup>m </sup></em>and (implicit) distance metric<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, we have a kernel function κ(<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>) = Φ(<em>x</em><sub>1</sub>) · Φ(<em>x</em><sub>2</sub>) that we can compute easily on the raw samples. How should we perform the kernelized counterpart of <em>k</em>-means clustering?</li>
</ul>
Derive the underlined portion of this algorithm, and show your work in deriving it. The main issue is that although we define the means µ<em><sub>i </sub></em>in the usual way, we can’t ever compute Φ explicitly because it’s way too big. Therefore, in the step where we determine which cluster each sample point is assigned to, we must use the kernel function κ to obtain the right result. (Review the lecture on kernels if you don’t remember how that’s done.)

Algorithm 1: Kernel <em>k</em>-means

Require: Data matrix <em>X </em>∈ R<em><sup>n</sup></em><sup>×<em>d</em></sup>; Number of clusters <em>K</em>; kernel function κ(<em>x</em><sub>1</sub>, <em>x</em><sub>2</sub>) Ensure: Cluster class class(<em>j</em>) for each sample <em>x<sub>j</sub></em>. function Kernel-k-means(<em>X</em>,<em>c</em>)

Randomly initialize class(<em>j</em>) to be an integer in 1,2,…, <em>K </em>for each <em>x<sub>j</sub></em>. while <em>not converged </em>do

(e) The expression you derived may have unnecessary terms or redundant kernel computations. Explain how to eliminate them; that is, how to perform the computation quickly without doing irrelevant computations or redoing computations already done.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Low-Rank Approximation</h1>
Low-rank approximation tries to find an approximation to a given matrix, where the approximation matrix has a lower rank compared to the original matrix. This is useful for mathematical modeling and data compression. Mathematically, given a matrix <em>M</em>, we try to find <em>M</em>ˆ in the following optimization problem,

argmin k<em>M </em>− <em>M</em>ˆ k<em><sub>F&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub></em>subject to&nbsp;&nbsp;&nbsp;&nbsp; rank(<em>M</em>ˆ ) ≤ <em>k&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>(1)

<em>M</em>ˆ

q where k<em>A</em>k<em><sub>F </sub></em>= <sup>P</sup><em><sub>i </sub></em><sup>P</sup><em><sub>j </sub>a</em><sup>2</sup><em><sub>ij </sub></em>is the Frobenius norm, i.e., the sum of squares of all entries in the matrix, followed by a square root.

This problem can be solved using Singular Value Decomposition (SVD). Specifically, let <em>M </em>= <em>U</em>Σ<em>V</em><sup>&gt;</sup>, where Σ = diag(σ<sub>1</sub>,…,σ<em><sub>n</sub></em>). Then a rank-<em>k </em>approximation of <em>M </em>can be written as <em>M</em>ˆ = <em>U</em>Σˆ<em>V</em><sup>&gt;</sup>, where Σ =ˆ diag(σ<sub>1</sub>,…,σ<em><sub>k</sub></em>,0,…,0). In this problem, we aim to perform this approximation method on gray-scale images, which can be thought of as a 2D matrix.

<ul>
<li>Using the image low-rankdata/face.jpg, perform a rank-5, rank-20, and rank-100 approximation on the image. Show both the original image as well as the low-rank images you obtain in your report.</li>
<li>Now perform the same rank-5, rank-20, and rank-100 approximation on low-rankdata/sky.jpg. Show both the original image as well as the low-rank images you obtain in your report.</li>
<li>In one plot, plot the Mean Squared Error (MSE) between the rank-<em>k </em>approximation and the original image for both low-rankdata/face.jpg and low-rankdata/sky.jpg, for <em>k </em>ranging from 1 to 100. Be sure to label each curve in the plot. The MSE between two images <em>I</em>, <em>J </em>∈ <em>R<sup>w</sup></em><sup>×<em>h </em></sup>is</li>
</ul>
MSE(<em>I</em>, <em>J</em>) = <sup>X</sup>(<em>I<sub>i</sub></em>,<em><sub>j </sub></em>− <em>J<sub>i</sub></em>,<em><sub>j</sub></em>)<sup>2</sup>.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (2)

<em>i</em>,<em>j</em>

<ul>
<li>Find the lowest-rank approximation for which you begin to have a hard time differentiating the original and the approximated images. Compare your results for the face and the sky image. What are the possible reasons for the difference?</li>
</ul>
<a href="#_ftnref1" name="_ftn1">[1]</a> Just as how the interpretation of kernels in kernelized ridge regression involves an implicit prior/regularizer as well as an implicit feature space, we can think of kernels as generally inducing an implicit distance metric as well. Think of how you would represent the squared distance between two points in terms of pairwise inner products and operations on them.
