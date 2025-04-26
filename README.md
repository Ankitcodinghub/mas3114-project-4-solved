# mas3114-project-4-solved
**TO GET THIS SOLUTION VISIT:** [MAS3114 Project 4 Solved](https://www.ankitcodinghub.com/product/mas3114-project-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;64838&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAS3114 Project 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Each exercise has to begin with the line

<strong>Exercise#</strong>

You should also mark down the parts such as (a), (b), (c), and etc. This makes grading easier. <strong><u>Important</u>: we use the default </strong>format short<strong> for the numbers in all exercises unless it is specified otherwise</strong>. <strong>If </strong><strong>format </strong><strong>long or </strong>format rat <strong>has been used, please make sure to return to the default </strong><strong>format in the next exercise.</strong>

<strong>&nbsp;</strong>Part I. Eigenvalues, Eigenvectors &amp; Diagonalization

<strong>&nbsp;</strong>In this exercise, you will work with the eigenvalues of a given <em>n n</em><sub>×</sub> matrix A. First, you will find all eigenvalues and, then, you will take distinct eigenvalues and find orthonormal bases for the corresponding eigenspaces and the dimensions of the eigenspaces. Next, you will check if A is diagonalizable by applying the general theory. If a matrix A is diagonalizable, the output has to contain an invertible matrix P and the diagonal matrix D, such that, <em>A</em><sub>= </sub><em>PDP</em><sup>−</sup><sup>1</sup>, or, equivalently, <em>AP PD</em><sub>=&nbsp;&nbsp;&nbsp;&nbsp; </sub> and P is invertible. Next, for diagonalizable matrices, you will run a built-in MATLAB function, which also performs diagonalization, and you will compare its outputs with the outputs P and D of your function.

&nbsp;

**Create a function in MATLAB that begins with function [P,D]=eigen(A) format compact [~,n]=size(A);

&nbsp;

Your function [P,D]=eigen(A)will have a set of commands which generates the following outputs for an <em>n n</em><sub>×</sub> matrix A. Each output has to be supplied with a corresponding message – you could use the commands disp and fprintf.

&nbsp;

<strong>Part 1</strong>. <u>Output the vector <strong>L</strong> of eigenvalues of the matrix</u>.

To do that, you will go through several steps. Please suppress all intermediate outputs and display only the final output vector <strong>L</strong>.

**Find a <u>row</u> vector <strong>L</strong> of all eigenvalues, where each eigenvalue repeats as many times as its multiplicity. A basic MATLAB command for this part L=eig(A) returns a <u>column</u> vector of all eigenvalues of A, and we use the function transpose() to get a <u>row</u> vector.

**You will also need to <strong>sort</strong> the entries of <strong>L – </strong>use the MATLAB command sort() to output the entries of <strong>L</strong> in ascending order.

To output vector L correctly, you will go through <u>two more steps</u>:

**In your code, you have to ensure that the multiple eigenvalues show as the same number. You will use closetozeroroundoff function with the parameter p = 7 to compare the eigenvalues and assign the same value to the ones that are within 10^(-7) tolerance of each other. To perform this task, you can go through the sequence of the sorted eigenvalues and, if there is a set of eigenvalues that are within 10^(-7) from each other, you will assign the <u>first</u> eigenvalue that comes across to all of them in that set.

<u>Note</u>: please work with the eigenvalues that are stored in MATLAB – we do not round off any eigenvalues on this step.

**A singular matrix A has a zero eigenvalue; however, when running your code, a zero eigenvalue may not show as a zero due to round-off errors in MATLAB. <u>If a matrix A is not</u> <u>invertible</u>, you will run the function closetozeroroundoff&nbsp; with p = 7 on the vector of the eigenvalues to ensure that the zero eigenvalues show as a zero. To check whether a matrix is not invertible, please use a MATLAB command rank().

&nbsp;

After performing all the tasks outlined above, you will <u>display</u> your final output <strong>L</strong> – a <u>row</u> vector of the <u>sorted</u> eigenvalues of A where all multiple eigenvalues equal to each other and the zero eigenvalues (for singular matrices) show as a zero.

&nbsp;

<strong>Part 2</strong>. <u>Construct an orthonormal basis W for each eigenspace</u>.

**Output a <u>row</u> vector <strong>M</strong> of all distinct eigenvalues (no repetitions are allowed). The MATLAB command unique() can be used here.

&nbsp;

For each distinct eigenvalue M(i), your function has to do the following:&nbsp; **Find the multiplicity, m(i), of the eigenvalue M(i). Output it with the message:

fprintf(‘Eigenvalue %d has multiplicity %i\n’,M(i),m(i))

**Output an orthonormal basis <strong>W</strong> for the eigenspace for the eigenvalue M(i). Display it with the message:

fprintf(‘A basis for eigenvalue lambda = %d is:\n’,M(i))

W

<u>Hint</u>: An appropriate command in MATLAB that creates an orthonormal basis for the null space of a matrix is null().

**Calculate the dimension d(i) of <strong>W</strong>. Output it with the message:

fprintf(‘Dimension of eigenspace for lambda = %d is %i\n’,M(i),d(i))

<strong>Part 3</strong>. <u>Construct a Diagonalization when possible</u>.

(For help with this part, please review the material of Lecture 14)

**First, we determine if A is diagonalizable. You will work with the multiplicity of the eigenvalue M(i), m(i), and the dimension of the corresponding eigenspace, d(i), for every i. If A is not diagonalizable, output a corresponding message, assign the empty outputs P=[];D=[];&nbsp; and <u>terminate</u> the program.

If A is diagonalizable, output a corresponding message, and your function will continue with constructing a diagonalization:

**Output and <u>display</u> a matrix P constructed from the combined bases W for the eigenspaces.&nbsp; **Output and <u>display</u> a diagonal matrix D with the <u>corresponding</u> eigenvalues on its main diagonal.

**Verify that both conditions hold: AP=PD and P is invertible. To verify the first condition, you will need to use the function closetozeroroundoff with the parameter p = 7. To verify the second condition, please use the command rank(). If both conditions hold, output a message: ‘Great! I got a diagonalization!’ Otherwise, output a message: ‘Oops! I got a bug in my code!’ and <u>terminate</u> the program.

&nbsp;

<strong>Part 4</strong>. <u>Compare your outputs with the corresponding ones of a MATLAB built-in function</u>.

If the diagonalization is confirmed, your code will continue with the following task.

**There is a MATLAB built-in function that runs as

[U,V]=eig(A)

which, for a <u>diagonalizable</u> matrix A, generates a diagonal matrix V, with the eigenvalues of A on its main diagonal, and an <em>n n</em><sub>×</sub> invertible matrix U of the corresponding eigenvectors, such that AU=UV. Place this function in your code and <u>display</u> the outputs U and V.

&nbsp;

**Compare the output matrix U with the matrix P: write a set of commands that would check on the following case:

The sets of columns of P and U are the same or match up to a scalar (-1), where the order of the columns does not matter.

If it is the case, output a message ‘Sets of columns of P and U are the same or match up to scalar (-1)’.

If it is not the case (which is possible), the output message could be ‘There is no specific match among the columns of P and U’

<u>Note</u>:&nbsp; You will need to use the function closetozeroroundoff with p = 7 when comparing the sets of columns of the matrices P and U.

&nbsp;

**Verify that the matrices D and V have the same set of diagonal elements (the order does not count either). If it is the case, output a message ‘The diagonal elements of D and V match’. If it is not the case, output something like: ‘That cannot be true!’

<u>Hint</u>: To perform this task, you can “sort” the diagonal elements of V and compare them with the vector L using the function&nbsp; closetozeroroundoff with p = 7.

<strong>&nbsp;</strong>

<strong>This is the end of the function </strong><strong>eigen. </strong>

&nbsp;

**Print the functions eigen<strong>,&nbsp; </strong>closetozeroroundoff,jord in the Live Script. <strong>&nbsp;&nbsp;</strong>

(The function jord was created in Exercise 1 of Project 1.)

**Type in the Live Script format

**Run the function [P,D]=eigen(A); on the following matrices:

%(a)

A=[3 3; 0 3]

%(b)

A=[4 0 0 0; 1 3 0 0; 0 -1 3 0; 0 -1 5 4]

%(c)

A=jord(5,5)

%(d)

A=diag([3, 3, 3, 2, 2, 1])

%(e)

A=magic(4)

%(f)

A=ones(4) %(g)

A=magic(5) %(h)

A=hilb(7)

%(k)

A=[5 8 -4;8 5 -4;-4 -4 -1]

In this exercise, we will construct an orthogonal diagonalization of an <em>n n</em><sub>×</sub> symmetric matrix.

<u>Theory</u>: A square matrix A is called symmetric if <em>A</em><em><sup>T </sup></em><sub>= </sub><em>A</em>.

A matrix A is said to be orthogonally diagonalizable if there exists an orthogonal matrix <em>P</em>

( <em>P</em><sup>−</sup><sup>1 </sup><sub>= </sub><em>P</em><em><sup>T </sup></em>) and a diagonal matrix <em>D</em>, such that <em>A</em><sub>= </sub><em>PDP</em><sup>−</sup><sup>1</sup>, or equivalently, <em>A</em><sub>= </sub><em>PDP</em><em><sup>T </sup></em>.&nbsp; An <em>n n</em><sub>×</sub> matrix A is orthogonally diagonalizable if and only if A is symmetric.

&nbsp;

**Create a function in MATLAB function []=symmetric(A)

&nbsp;

**First, your function has to check whether A is symmetric. If not, output a message that the matrix is not symmetric and <u>terminate</u> the program.

&nbsp;

**If a matrix is symmetric, you will construct an orthogonal diagonalization using a built-in MATLAB function

[P,D]=eig(A)

in your code. The outputs have to be an orthogonal matrix P of the eigenvectors of A and a diagonal matrix D with the corresponding eigenvalues on its main diagonal. Place this function in your code and <u>display</u> the outputs P and D.

**Next, you should verify in your code that you have got an orthogonal diagonalization, that is, both conditions hold: AP=PD and P is an orthogonal matrix. If it is the case, output a corresponding message. Otherwise, a message could be ‘What is wrong?!’

&nbsp;

<u>Note</u>: you will need to use the function closetozeroroundoff with p = 7 in your code for verification of each of the two conditions above.

(For the help with this exercise, please refer to Lecture 29.)&nbsp; <strong>This is the end of the function </strong><strong>symmetric. </strong>

&nbsp;

**Print the functions symmetric&nbsp; and closetozeroroundoff&nbsp; in your Live Script.&nbsp; **Run the function on the given matrices as indicated below:

%(a)

A=[2 -1 1;-1 2 -1;1 -1 2] symmetric(A)

%(b)

A=[2 -1 1;-1 2 -2;1 -1 2] symmetric(A)

<table width="616">
<tbody>
<tr>
<td width="616">%(d)

A=[3 1 1;1 3 1;1 1 3] symmetric(A)

%(e)

A=[5 8 -4;8 5 -4;-4 -4 -1] symmetric(A)

%(f)

A=[4 3 1 1; 3 4 1 1 ; 1 1 4 3; 1 1 3 4]
</td>
</tr>
</tbody>
</table>
%(c) B=A*A’ symmetric(B) symmetric(A)

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>Part II. Orthogonal Projections &amp; Least-Squares Solutions

<strong>&nbsp;</strong><strong>Difficulty: Moderate </strong>

In this exercise, you will create a function proj(A,b)which will work with the projection of a vector <strong>b</strong> onto the Column Space of an <em>m n</em><sub>×</sub>&nbsp; matrix A.

For a help with this exercise, please refer to Lectures 28, 30, and 31.

<strong>&nbsp;</strong>

<strong><u>Theory</u></strong>: When the columns of A are linearly independent, a vector <strong>p </strong>is the orthogonal projection of a vector <strong>b</strong>∉ Col A onto the Col A if and only if <strong>p</strong>=<em>A</em><strong>x</strong>ˆ , where <strong>x</strong>ˆ is the unique least-squares solution of <em>A</em><strong>x b</strong>= , or equivalently, the unique solution of the <strong><em>normal equations</em></strong>

<em>A A A</em><em><sup>T </sup></em><strong>x</strong>= <em><sup>T</sup></em><strong>b</strong>.

Also, if <strong>p </strong>is the orthogonal projection of a vector <strong>b</strong> onto Col A, then there exists a unique vector <strong>z</strong>, such that, <strong>z b p</strong>= − and <strong>z</strong> is orthogonal to Col A.

&nbsp;

**Your program should allow a possibility that the columns of A are not linearly independent. In order for the algorithm to work, we will use the function shrink() to create a new matrix, also denoted A, whose columns form a basis for Col A. Thus, we assign in our code:

A=shrink(A);

The function shrink() was created in Exercise 2 of Project 3 and you should have it in your Current Folder in MATLAB. If not, please see the code below:

function B=shrink(A) format compact [~,pivot]=rref(A); B=A(:,pivot); end

&nbsp;

You will create a function proj&nbsp; as defined below. The inputs are an <em>m n</em>× matrix A and a column vector <strong>b</strong>. The outputs will be the projection <strong>p</strong> of the vector <strong>b</strong> onto the Col A and the vector <strong>z</strong> which is the component of <strong>b</strong> orthogonal to the Col A.

&nbsp;

**Your function will begin with: function [p,z]=proj(A,b) format compact A=shrink(A); m=size(A,1);

&nbsp;

**First, the program checks whether the input vector <strong>b</strong> has exactly <em>m</em> entries, where <em>m</em> is the number of rows in A. If it doesn’t, the <u>program breaks</u> with a message ‘No solution: dimensions of A and b disagree’, outputs and <u>displays</u> the empty vectors <strong>p</strong> and <strong>z</strong>.

&nbsp;

<u>If <strong>b</strong> has exactly <em>m</em> entries</u>, we proceed to the next step:

**Determine whether it is the case that <strong>b</strong>∈ Col A. You should use a MATLAB function rank(). If <strong>b</strong>∈ Col A, you will just assign the values to the vectors <strong>p</strong> and <strong>z </strong>based on the general theory (no computations are needed!) and output a message ‘b is in Col A’. After that, the program <u>terminates</u>.

&nbsp;

If <strong>b</strong>∉ Col A, proceed to the next step:

**Determine whether it is the case that <strong><u>b</u></strong><u> is orthogonal to Col A</u>. Due to&nbsp; round-off errors in MATLAB computations, you will need to use closetozeroroundoff with p = 7 to check orthogonality. If <strong>b</strong> is orthogonal to Col A, you should just assign the values to the vectors <strong>p</strong> and <strong>z </strong>(no computations are needed!) and output a message ‘b is orthogonal to Col A’. After that, the program <u>terminates</u>.

&nbsp;

**If <strong><u>b</u></strong><u> is not orthogonal to Col A</u>, proceed to the next steps:

Find the solution of the <strong><em>normal equations</em></strong> (see the <strong>Theory</strong> above), a vector <strong>x</strong> (use the inverse matrix or the <strong><em>backslash operator</em></strong>, \ ). Output the least squares solution, <strong>x</strong>, with a message:

‘the least squares solution of the system is’&nbsp; (display <strong>x)</strong>.

**Then, calculate and output a vector&nbsp; x1=A\b

and check, by using the function closetozeroroundoff with p=12, whether the vectors <strong>x</strong> and

<strong>x1</strong> match within the given precision. If yes, output a message: ‘A\b returns the leastsquares solution of an inconsistent system Ax=b’

**Next, calculate the vectors <strong>p </strong>and<strong> z</strong> (see the <strong>Theory</strong> above).

**Check whether the vector <strong>z</strong> is, indeed, orthogonal to the Col A – the function closetozeroroundoff with p=7 should be used here. If your code confirms that, display a message: ‘z is orthogonal to Col A. Great job!’ &nbsp;Otherwise, output a message like:

‘Oops! Is there a bug in my code?’ and <u>terminate</u> the program.

**Finally, use the vector <strong>z</strong> to compute the distance d from <strong>b</strong> to Col A. Output d with the message:

fprintf(‘the distance from b to Col A is %i’,d) <u>Hint</u>: use a MATLAB built in function <strong>norm().</strong>

<strong>&nbsp;</strong>

<strong>This is the end of the function </strong><strong>proj. </strong>

&nbsp;

**Print the functions closetozeroroundoff, shrink, proj in your Live Script.

**Run the function [p,z]=proj(A,b)on the following choices of matrices A and vectors <strong>b</strong>. Notice that some of the matrices are created in several steps and some intermediate outputs have been suppressed.

%(a)

A=magic(4), b=sum(A,2)

%(b)

A=magic(4); A=A(:,1:3),b=(1:4)’

%(c)

A=magic(6), E=eye(6); b=E(:,6)

%(d)

A=magic(6), b=(1:5)’

%(e)

A=magic(5), b = rand(5,1)

%(f)

A=ones(4); A(:)=1:16, b=[1;0;1;0]

%(g)

B=ones(4); B(:)=1:16, A=null(B,’r’), b=ones(4,1)

<strong>&nbsp;</strong>

%Analyze the outputs in parts (e) and write a comment that would explain a reason why a random vector <strong>b </strong>belongs to the Col A.

<strong>&nbsp;</strong>

<strong>BONUS! </strong>(1 point)

%For part (g), based on the input matrix A and the outputs, state to which vector space the vector <strong>b</strong> has to belong.

&nbsp;

**You will need to present some additional computation in your Live Script to support your responses. Supply them with the corresponding output messages and/or comments.

<h1>The Exact and Least-Squares Solutions</h1>
<strong>&nbsp;</strong>

Please review the section Theory below very carefully – you will be using these facts when working on Exercise 4. <strong>&nbsp;</strong>

<strong><u>Theory</u></strong>: An <em>m n</em>× matrix <em>U</em> has orthonormal columns if and only if <em>U U</em><em><sup>T </sup></em><sub>= </sub><em>I</em><em><sub>n</sub></em>, where <em>I</em><em><sub>n</sub></em> is an <em>n n</em><sub>×</sub> identity matrix. If <em>U</em> is a <u>square</u> matrix with orthonormal columns, it is called orthogonal.

&nbsp;

We will work with the system A<strong>x=b</strong>, where the columns of A are linearly independent.

&nbsp;

When solving a <u>consistent</u> system A<strong>x</strong>=<strong>b (</strong>that is, <strong>b</strong>∈Col A), the unique “exact” solution can be found by using the backslash operator: <strong>x </strong>=A\<strong>b</strong>.

&nbsp;

When solving a <u>consistent</u> system A<strong>x</strong>=<strong>b</strong>, where A is a <u>matrix with orthonormal columns</u>, we can find the unique solution <strong>x</strong> in two ways as indicated below:&nbsp; (1) using the backslash operator, \ , that is, <strong>x </strong>=A\<strong>b</strong>;<strong>&nbsp; </strong>

(2) using the Orthogonal Decomposition theorem (see Lecture 28).

&nbsp;

When solving an <u>inconsistent</u> system A<strong>x</strong>=<strong>b</strong> (that is, <strong>b</strong>∉ColA), we will be looking for the least-squares solution, which can be found either by solving the normal equations,

<em>A A A</em><em><sup>T </sup></em><strong>x</strong>= <em><sup>T</sup></em><strong>b</strong>, or by using the backslash operator, A\<strong>b </strong>(see Exercise 3 of this Project).

&nbsp;

Another way of calculating the least squares solution of an <u>inconsistent</u> system A<strong>x</strong>=<strong>b</strong> is to employ an orthonormal basis U for the Col A. If the columns of an <em>m n</em><sub>×</sub> matrix U form an orthonormal basis for Col A, then, for any vector <strong>b</strong>∈¡<em><sup>m</sup></em>, we can find its projection <strong>b</strong><sup>ˆ</sup> onto the Col A by the formula <strong>b</strong>ˆ <sub>=</sub><em>UU</em><em><sup>T</sup></em><strong>b </strong>, and, then, calculate the least-squares solution <strong>x</strong><sup>)</sup> as the “exact” solution of a consistent system <em>A</em><strong>x b</strong>= <sup>) </sup>.

Using the projection of <strong>b</strong> onto the Col A, which could be represented either as <em>A</em><strong>x</strong>) or as <strong>b</strong>ˆ , we can calculate the least-squares error of approximation of the vector <strong>b</strong> by the elements of the Col A as <em>norm</em>(<strong>b</strong>−<em>A</em><strong>x</strong>)) or as <em>norm</em>(<strong>b b</strong>−<sup>)</sup>) (either of them is also the distance from <strong>b</strong> to Col A

– see Exercise 3 of this Project).

&nbsp;

In this exercise, you will work with the matrix equation <em>A</em><strong>x b</strong>= , where the columns of A are linearly independent. You will look for the unique “exact” solution, for a consistent equation (<strong>b</strong>∈Col A); and you will look for the unique least-squares solution, for an inconsistent equation (<strong>b</strong>∉Col A).

&nbsp;

**Create a function in MATLAB that begins with function X=solvemore(A,b) format compact format long [m,n]=size(A);

&nbsp;

The inputs are an <em>m n</em><sub>×</sub> matrix A, whose columns form a basis for Col A, and a vector <strong>b</strong>∈¡<em><sup>m</sup></em>.&nbsp; Some of the input matrices A will be created by running the function shrink() – it will leave only linearly independent columns. You should have already had the function shrink() created in a file in MATLAB, if not, please see the code in Exercise 3 of this Project.

&nbsp;

**Next step is to determine if <strong>b</strong>∈Col A or <strong>b</strong>∉Col A – please use a MATLAB function rank() – and you will employ a logical “if … else” statement to work with the two possible outcomes as indicated below.

&nbsp;

<strong>This is the beginning of “if … else” statement: </strong>

<strong>&nbsp;</strong>

<h1>“If” b is in Col A</h1>
first, we output a message: ‘The system is consistent – look for the exact solution’ and go through the following steps:

**Determine whether the matrix A has orthonormal columns and, if it is the case, determine if A is also orthogonal.

<u>Hint</u>: To conduct this test in MATLAB, you will need to use the function closetozeroroundoff() with p = 7.

&nbsp;

**If A does not have orthonormal columns, output a corresponding message and find the unique solution x1 of <em>A</em><strong>x b</strong>= using the backslash operator, \ . In this case, we assign X=x1 and <u>terminate</u> the program.

&nbsp;

**If A does have orthonormal columns, output a corresponding message, and your code will continue with the following tasks:

First, it will check whether A is orthogonal. If yes, it outputs a message ‘A is orthogonal’.

If not, the output message should be ‘A has orthonormal columns but is not orthogonal’.

Next, output the solution of <em>A</em><strong>x b</strong>= in two ways (<u>do not display</u> the outputs x1 and x2 here):

<ul>
<li>using the backslash operator, \ , denote this solution x1,</li>
<li>using the Orthogonal Decomposition theorem (Lecture 28), denote this solution</li>
</ul>
<u>Hint</u>: for part (2), you can either use a “for loop” to calculate the entries of the vector x2, one by one, or you can employ the transpose of A and output x2 by using a MATLAB operation.

&nbsp;

<h1>else (b is not in Col A)</h1>
we display a message ‘The system is inconsistent: look for the least-squares solution’ and, then, we will find the least-squares solution in both ways as indicated below: **<u>First way</u>: we will find the unique least-squares solution directly by <u>either</u> solving the normal equations <u>or</u> using the backslash operator. We denote the solution x1 and <u>display</u> it with a message that it is the least-squares solution of the system.

**<u>Second way</u>: we will use an orthonormal basis for Col A to find the least-squares solution. It might be possible that the matrix A has orthonormal columns and, if not, we will create an orthonormal basis for Col A.

Check if the matrix <em>A</em> has orthonormal columns. If yes, your outputs will be: disp(‘A has orthonormal columns: orthonormal basis for Col A is U=A’) U=A

If the matrix <em>A</em> does not have orthonormal columns, find an orthonormal basis U for Col A using a MATLAB function orth(). Output and display U with a message&nbsp; disp(‘A does not have orthonormal columns: orthonormal basis for Col A is’) U=orth(A)

Next, using the orthonormal basis U for Col A, calculate the projection of <strong>b</strong> onto Col A, denote it b1. Output and display vector b1 with the corresponding message.

Next, find the least-squares solution x2 as the “exact” solution of the equation A<strong>x </strong>= b1 (you can use the backslash operator here). Output x2 with the message: ‘The least-squares solution using the projection b1 is’ (output and display x2).

&nbsp;

**Use the least-squares solution x1 to find a least-squares error of approximation of <strong>b</strong> by the elements of Col A, denote it n1.

Display n1 with a message:&nbsp; fprintf(‘Error of approximation of b by vector A*x1 of Col A is\n’) n1

**Now, we use the projection b1 to find the least-squares error of approximation of <strong>b</strong> by the elements of Col A, denote it n2.

Display n2 with a message:&nbsp; fprintf(‘Error of approximation of b by vector b1 of Col A is\n’) n2

**Next, input a vector x=rand(n,1). Compute an error n3=norm(b-A*x) of approximation of the vector <strong>b</strong> by a vector Ax of the Col A for a random vector x. &nbsp;Output it with a message:

fprintf(‘error of approximation of b by A*x of Col A for random x is\n’) n3

<strong>This is the end of your “if … else” statement </strong>

<strong>&nbsp;</strong>

<h1>After completing all of the above</h1>
your code will proceed with composing the output X for the cases when we have two solutions x1 and x2 for <u>both consistent and inconsistent systems</u>, but, first, we will check if the corresponding entries of the two solutions x1 and x2 are sufficiently close to each other. We will run the function closetozeroroundoff() with p = 12 on the vector of the difference between x1 and x2, and compare the output with the zero vector. If your code confirms that the corresponding entries of the solutions are in the range of 10^(-12) from each other, output a message ‘solutions x1 and x2 are sufficiently close to each other’, and assign (and <u>display</u>)&nbsp; X=[x1,x2]. Otherwise, the output message should be ‘Check the code!’ and the empty matrix should be assigned to the output X.

&nbsp;

<strong>**</strong>Print<strong> t</strong>he functions closetozeroroundoff, shrink, solvemore in your Live Script.

&nbsp;

**Run the function X=solvemore(A,b) on the following matrices. Please type (or copy and paste) the matrices and the vectors exactly as they appear below.

%(a)

A=magic(4); b=A(:,4), A=orth(A)

%(b)

A=magic(5); A=orth(A), b=rand(5,1)

%(c)

A=magic(6); A=shrink(A), b=ones(6,1)

%(d)

A=magic(6); A=shrink(A), b=rand(6,1)

%(e)

A=magic(4); A=orth(A), b=rand(4,1)

&nbsp;

% Compare the outputs n1 and n2 and write a comment whether they are close to each other.

% Next, compare n1 with n3. Write a comment whether the least-squares solution, x1 (or x2) may, indeed, minimize the distance between a vector <strong>b </strong>and the vectors A<strong>x</strong> of the Col A<strong> (</strong>which has to be true according to the general theory).

<h2>Part III. Application to Polynomials</h2>
&nbsp;

<strong>Applications to Linear Models – Regression Lines&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

&nbsp;

In this part of the project, you will write codes that output the least-squares fit equation for the given data. The equation is determined by the <strong>parameter vector</strong> <strong>c </strong>(that has to be calculated), the <strong>design matrix</strong> X, and the <strong>observation vector</strong> <strong>y, </strong>such that, the 2-norm of the residual vector <strong>e</strong> = <strong>y – </strong><em>X</em><strong>c&nbsp; </strong>is the minimum.

Assume that we are given the data points (<em>x y</em><em><sub>i </sub></em>, <em><sub>i </sub></em>), where <em>i </em><sub>=</sub>1:<em>m </em>. A choice of the equation of a curve which gives the least-squares fit to the data is, in general, arbitrary. First, we will take a look at the equation of a straight line <em>y </em><sub>=</sub><em>c x c</em><sub>1 </sub>+ <sub>0</sub> that minimizes the sum of squares of the residuals – it is called the least-squares regression line. The parameter vector <strong>c</strong> can be determined by computing the least-squares solution of <em>X</em><strong>c y</strong>= , where

<em>x</em><sub>1 </sub>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>y</em><sub>1 </sub>

<em>X </em>=<em>x</em>M2 M1 ,&nbsp; <strong>c</strong>=  <sub> </sub><em>cc</em>10 , <strong>y</strong>=M<em>y</em>2  . <strong>&nbsp;</strong>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; 

<em>x</em><em><sub>m </sub></em>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>y</em><em><sub>m</sub></em>

&nbsp;

**First, create the following function in MATLAB that will be used in the function below:

function []=polyplot(a,b,p) x=(a:(b-a)/50:b)’; y=polyval(p,x); plot(x,y); end

&nbsp;

**Create another function in MATLAB that begins with the following lines:

function c=lstsqline(x,y) hold off format format compact x=x’; y=y’; a=x(1); m=length(x); b=x(m); disp(‘the design matrix is’) X=[x,ones(m,1)]

disp(‘the parameter vector is’) c=lscov(X,y) disp(‘the norm of the residual vector is’) N=norm(y-X*c) &nbsp;plot(x,y,’*’),hold on polyplot(a,b,c’); fprintf(‘the least-squares regression line is\n’)

P=poly2sym(c)

&nbsp;

<u>Note</u>: The data vectors <strong>x</strong> and <strong>y </strong>(inputs) are the row vectors – we use the transpose function in the code above to convert them into the column vectors. The parameter vector p in the function polyplot(a,b,p) has to be a <u>row</u> vector – in the code above it appears as c’.

&nbsp;

**The MATLAB command c=lscov(X,y)calculates the parameter vector c&nbsp; which is, in fact, the least-squares solution of the inconsistent system <em>X</em><strong>c y</strong>= . You will continue the function lstsqline with a verification of this fact: output (<u>do not display</u>) the least-squares solution c1 of the system <em>X</em><strong>c y</strong>= , calculated by any of the method from Exercise 4 of this Project, and, then, employ closetozeroroundoff() with p=7, to verify that c and c1&nbsp; match. If it is the case, output the message ‘c is the least-squares solution’

(Please make sure that you will receive this message after running the function)

&nbsp;

**Complete your function<strong> lstsqline</strong>&nbsp; with the commands: hold off end

**Print the functions polyplot and lstsqline in your Live Script.

**Input the vectors:

x = [0,2,3,5,6], y = [1,4,3,4,5]

**Run the function&nbsp; c=lstsqline(x,y);

&nbsp;

Your outputs have to be: the design matrix X, the parameter vector c, the 2-norm of the residual vector N, the equation of the least-squares regression line P, the <u>plot</u> that contains <u>both</u> the data points and the line of the best fit, and the message confirming that c is, indeed, the leastsquares solution.

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong><u>Exercise 6</u></strong> (4 points)&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Difficulty: Moderate </strong>

In this Exercise you will find a polynomial of degree n of the best fit for the given data points.

&nbsp;

**Create a new function in a file

function c=lstsqpoly(x,y,n) which takes as inputs the data vectors x and x and a positive integer number n.

&nbsp;

The function lstsqpoly(x,y,n) is a <u>modification</u> of the function lstsqline(x,y) from Exercise 5 in the way that it has to output the least-squares <u>polynomial of degree <em>n</em></u>.

&nbsp;

You will take the function c=lstsqline(x,y)and make the <u>three </u>changes in it as indicated below (everything else will stay the same):

**Add one more input variable n and re-name the function as lstsqpoly.

**Replace the matrix X with the new matrix, also named X, whose form depends on the degree <em>n</em> of the polynomial that we use to fit the data. For example, when n=3, the least-squares polynomial will be of degree 3, and the design matrix X will have a form:

<em>x</em>13&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>x</em>12&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>x</em>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1

<em>X </em>=<em>x</em>M23&nbsp; <em>x</em>M22&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>x</em>M2 1M .



<em>x</em><em>m</em>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>x</em><em>m</em>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>x</em><em>m&nbsp;&nbsp;&nbsp; </em>1

**Replace the output message for the polynomial P with a message fprintf(‘the polynomial of degree %i of the best least-squares fit is\n’,n)

&nbsp;

Please make sure that you have the function polyplot in your Current Folder in MATLAB – it was used in the function lstsqline and it will be used in the function lstsqpoly as well.

&nbsp;

**Print the functions polyplot and lstsqpoly in the Live Script. **Run the function c=lstsqpoly(x,y,n) on the vectors from Exercise 5:

x = [0,2,3,5,6], y = [1,4,3,4,5] for each n = 1, 2, 3, 4.

&nbsp;

<u>For each </u><u>n</u>, the outputs have to be: the design matrix X, the parameter vectors c, the 2-norm of the residual vector N, the equation of the least-squares polynomial P, the plot containing <u>both</u> the data points and the graph of the polynomial P, and the message confirming that c is, indeed, the least-squares solution.

.

% Verify that your code in Exercise 6 for n = 1 is consistent with the code in Exercise 5, that is, the outputs of the functions c=lstsqline(x,y) and c=lstsqpoly(x,y,1) match. Write a comment about it.

<strong>BONUS!</strong>

% Analyze the outputs for n = 4. <u>Justify</u> the fact that the least-squares polynomial of degree 4 is, actually interpolates the 5 data points.

Part III. Application to Dynamical Systems

&nbsp;

In this part of the Project, you will be working with application of eigenvalues and eigenvectors to the description of evolution of a discrete dynamical system.

: We will work with a 2×2 matrix A, whose entries are real numbers, and the related linear difference equation&nbsp;&nbsp; <strong>x</strong><em><sub>k</sub></em><sub>+</sub><sub>1 </sub>= <em>A</em><strong>x</strong><em><sub>k </sub></em>(<em>k </em>= 0,1,2,…)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1)

that describes evolution of a discrete dynamical system with an initial vector <strong>x</strong><sub>0</sub> in ¡<sup>2 </sup>.&nbsp; If A <u>is diagonalizable</u>, there exists an eigenvector basis {<strong>v v</strong><sub>1</sub>, <sub>2</sub>} for ¡<sup>2 </sup>, and, for any initial vector <strong>x</strong><sub>0</sub> in ¡<sup>2 </sup>, there is a unique vector of weights <em>C</em>=(<em>c c</em><sub>1</sub>, <sub>2. </sub>), such that,

<strong>x</strong><sub>0 </sub>=<em>c</em><sub>1 1</sub><strong>v </strong>+<em>c</em><sub>2 2</sub><strong>v </strong>.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (2)

Moreover, the solution of the difference equation (1) is represented in an explicit form as <strong>x</strong><em><sub>k </sub></em>=<em>c</em><sub>1</sub>(λ<sub>1</sub>)<em><sup>k </sup></em><strong>v</strong><sub>1 </sub>+<em>c</em><sub>2</sub>(λ<sub>2</sub>)<em><sup>k </sup></em><strong>v</strong><sub>2 </sub>(<em>k</em>= 0,1,2,…)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (3)

where <sub>λ</sub><sub>1</sub> and <sub>λ</sub><sub>2</sub> are the eigenvalues of A corresponding to the eignevectors <strong>v</strong><sub>1</sub> and <strong>v</strong><sub>2</sub>, respectively.

&nbsp;

<u>To represent the solution geometrically</u>:

we will use equation (3) to calculate<strong>x x</strong><sub>1</sub>, <sub>2</sub>,<strong>x</strong><sub>3</sub>,…, when working with the matrices whose eigenvalues are <u>positive</u> numbers;

and we will use the recurrence relation (1) to find the consecutive <strong>x x</strong><sub>1</sub>, <sub>2</sub>,<strong>x</strong><sub>3</sub>,…, when working with the matrices whose eigenvalues are <u>complex</u> (non-real) numbers.&nbsp; The graph of <strong>x</strong><sub>0</sub>,<strong>x x</strong><sub>1</sub>, <sub>2</sub>,… is called the <u>trajectory</u> of the dynamical system.

&nbsp;

We will accept the following description of <u>the origin</u> in relation to the patterns of the trajectories of a dynamical system:

<ol>
<li><u>All trajectories tend towards the origin</u>. In this case, the origin is called an <u>attractor</u>, and it happens when both eigenvalues are less than 1 in magnitude. The direction of the greatest attraction is through the origin and the eigenvector corresponding to the eigenvalue of the smaller magnitude.</li>
<li>All solutions, except for the constant (zero) solution, are unbounded, and their <u>trajectories tend away from the origin</u>. In this case, the origin is called a <u>repeller</u>, and it happens when both eigenvalues are greater than 1 in magnitude. The direction of the greatest repulsion is through the origin and the eigenvector corresponding to the eigenvalue of the larger magnitude.</li>
</ol>
<ul>
<li><u>Some trajectories tend towards the origin and the others tend away from the origin</u>. In this case, the origin is called a <u>saddle point</u>, and it happens when one of the eigenvalues is less than 1 in magnitude and the other one is greater than 1 in magnitude. The direction of the (greatest) attraction is through the origin and the eigenvector corresponding to the eigenvalue of the smaller magnitude; and the direction of the greatest repulsion is through the origin and the eigenvector corresponding to the eigenvalue of the larger magnitude.</li>
</ul>
For more details, please refer to Lecture 26 and Section 5.6 of the Textbook.

&nbsp;

**Create a function in MATLAB that begins with the lines: function []=trajectory(A,X0,N) format format compact

L=eig(A);

&nbsp;

<u>The inputs are</u>: a 2×2 real-valued matrix A, a matrix X0 <u>whose columns are the initial vectors</u> in ¡<sup>2 </sup>, and the number N of the vectors <strong>x x</strong><sub>1</sub>, <sub>2</sub>,<strong>x</strong><sub>3</sub>,…,<strong>x</strong><em><sub>N</sub></em> which we will calculate.

<strong>We will use a logical ‘if … else” statement to break up the whole code into <u>two parts</u>: </strong>

&nbsp;

Part 1

<strong>&nbsp;“if” matrix A has real eigenvalues</strong>

first, we display a message ‘the eigenvalues of A are real’ and proceed with the following tasks:

**Check if A has a zero eigenvalue. If it is the case, output a message ‘A has a zero eigenvalue’ and <u>terminate</u> the program – we will not graph the solutions in this case.&nbsp;&nbsp; **You will continue your code for trajectory by modifying the function eigen, which was created in Exercise 1 of this Project. The details how the function eigen should be modified to be included into the function trajectory are listed below – please remove/suppress all the tasks/outputs of the function eigen that are not on the list.

<u>Important</u>: Please notice that you have n=2 in your code and you also need to replace the command null( ), used in the function eigen, with null( ,’r’) to output a “rational” basis for an eigenspace.

After adjusting the function eigen for your code, you will add some more commands that are listed below in these instructions.

&nbsp;

The function trajectory has to contain the following parts coming from the function eigen: &nbsp;**Output a <u>row</u> vector <strong>L</strong> of the <u>sorted</u> eigenvalues of A, where the multiple eigenvalues are all equal to each other: the entries of <strong>L</strong> have to be written in the ascending order and each eigenvalue repeats as many times as its multiplicity. <u>Display</u> L with a message: fprintf(‘all sorted eigenvalues of A are\n’) L

**Output (<u>do not display</u>) the matrix P whose columns are bases for the eigenspaces corresponding to the sorted eigenvalues in L.&nbsp;&nbsp; **Check if A is diagonalizable. <u>If A is not diagonalizable</u>, output a message: ‘A is not diagonalizable: there is no eigenvector basis for R^2’ and <u>terminate</u> the code.

<u>If A is diagonalizable</u>, output the following:

fprintf(‘A is diagonalizable: there exists an eigenvector basis for R^2\n’) fprintf(‘it is formed by V1,V2 corresponding to sorted eigenvalues in L\n’)

(assign to V1 and V2 the columns 1 and 2 of P, respectively, and <u>display</u> V1 and V2 here.)

<strong>&nbsp;</strong>

<strong>This is the end of the part of your code which relates to the function </strong><strong>eigen</strong>.

&nbsp;

Continue your function&nbsp; trajectory with the following:

**Check if all eigenvalues of A are positive numbers. If at least one of the eigenvalues of A is negative, we <u>terminate</u> the code with a message ‘A has a negative eigenvalue’ **Next (for the matrices whose eigenvalues are positive numbers), we will determine whether the origin is an attractor, a repeller, or a saddle point. (See the <strong>Theory</strong> above.) Program an output message for each of the three cases and also output a message that will state the direction of the greatest attraction/repulsion.

An example of the output messages when the origin as an attractor, is below: disp(‘the origin is an attractor’)

fprintf(‘a direction of greatest attraction is through 0 and\n’)

V1<sup> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>2

(Remember, V1 and V2 are the vectors in an eigenvector basis for ¡ corresponding to the positive eigenvalues of A <u>sorted</u> in the ascending order.)

**Then, we will check if at least one of the eigenvalues of A is the integer number 1. If it is the case, we display a message ‘A has an eigenvalue 1’ and go to the next step (<u>do not</u> <u>terminate</u> the code here).

&nbsp;

Next, we will create plots of the trajectories of a dynamical system.

**First, you will introduce a new matrix of the initial vectors, which is a horizontal concatenation of the vectors V1,V2,-V1,-V2 with the input matrix X0.Type in your code: X0 = [V1,V2,-V1,-V2,X0];

&nbsp;

**Next, type the following lines in your code:

n=size(X0,2); X=zeros(2,N+1);

The first line counts the total number of the initial vectors, and the second line stores a matrix X, whose entries will be re-calculated by using a <u>double “for loop</u>” as indicated below:

&nbsp;

**For each initial vector X0(:,i), where i=1:n, calculate the coefficient vector C according to the formula (2). Use the vector C to calculate by formula (3) the N+1 vectors <strong>x</strong><sub>0</sub>,<strong>x x</strong><sub>1</sub>, <sub>2</sub>,…,<strong>x</strong><em><sub>N</sub></em> and output them as N+1 columns of the matrix X. Proceed with graphing the trajectories.&nbsp; Type (see also Exercise 5 of Project 2):

x=X(1,:);y=X(2,:); plot(x,y,’*’), hold on plot(x,y)

and program the viewing window as&nbsp; v=[-1 1 -1 1];

for the two cases: when the origin is an attractor and when A has an eigenvalue 1; and program the viewing window as&nbsp; v=[-5 5 -5 5]; for all other cases.

&nbsp;

After that, type: axis(v)

<strong>This is the end of the double “for loop”.&nbsp; </strong>

<strong>&nbsp;</strong>

<strong>This is the end of the “IF” part of your code – proceed to the “ELSE” part.&nbsp; </strong>

&nbsp;

Part 2

<strong>else</strong> (<strong>matrix A has complex conjugate (non-real) eigenvalues</strong>) first, we output a message

disp(‘the eigenvalues of A are complex conjugate (non-real) numbers’)

**Next, we will graph the trajectories by calculating consecutive iterations <strong>x x</strong><sub>1</sub>, <sub>2</sub>,<strong>x</strong><sub>3</sub>,…,<strong>x</strong><em><sub>N </sub></em>, for each initial vector <strong>x</strong><sub>0</sub> (a column of the input X0) by using the recurrence equation (1) (see the

<strong>Theory</strong>).

Begin this part with the commands: L=eig(A) magn=abs(L) n=size(X0,2);

X=zeros(2,N+1);

Entries of the vector magn are the magnitudes (moduli) of the complex eigenvalues in L.

&nbsp;

**Then, use a double “for loop” to graph the trajectory:&nbsp; for each initial vector X0(:,i), where i=1:n, calculate the consecutive iterations <strong>x</strong><sub>0</sub>,<strong>x x</strong><sub>1</sub>, <sub>2</sub>,…,<strong>x</strong><em><sub>N</sub></em> by formula (1), and output them as the N+1 columns of X.&nbsp; Plot the trajectory by the following lines:

x=X(1,:);y=X(2,:); plot(x,y,’*’), hold on plot(x,y)

<strong>This is the end of a double “for loop”. </strong>

<strong>&nbsp;</strong>

<strong>This is the end of the “ELSE” part of your “if … else” statement. </strong>

&nbsp;

**The <u>last commands</u> in your function trajectory are:

hold off end

&nbsp;

**Print the function trajectory in your Live Script.

**Run the function trajectory(A,X0,N) on&nbsp; the following sets of variables.

%(a)

A=[2 0;0 .5]

X0=[[.1;5],[-.1;5],[-.1;-5],[.1;-5]]; N=10;

&nbsp;

%(b)

A=[2 0; 0 3]

X0=[[0;0],[1;1],[1;-1],[-1;-1],[-1;1],[1;.1],[-1;.1],[-1;-.1],[1;-.1]];

N=10;

A=[.80 0;0 .64]

X0=[[1;1],[-1;1],[-1;-1],[1;-1],[.5;1],[-.5;1],[-.5;-1],[.5;-1]];

N=10;

%(c)

A=[.80 0;0 .64]

X0=[[1;1],[-1;1],[-1;-1],[1;-1],[.5;1],[-.5;1],[-.5;-1],[.5;-1]];

N=10;

%(d)

A=[.64 0;0 .64]

X0=[[1;1],[-1;1],[-1;-1],[1;-1],[.5;1],[-.5;1],[-.5;-1],[.5;-1]];

N=10;

%(e)

A=[5 0; 1 5]

X0=[[1;1],[-1;1],[-1;-1],[1;-1]];

N=10;

%(f)

A=[1 0;0 .64]

X0=[[.5;1],[-.5;1],[-.5;-1],[.5;-1]];

N=10;

%(g)

A=[.90 .04;.10 .96]

X0=[[.2;.8],[.1;.9],[.9;.1],[.6;.4],[.5;.5]];

N=10;

%(h)

A=[0 -1;1 0]

X0=[[.1;.1],[.5;.5],[.8;0],[1;-1]];

N=10;

%(i)

A=[.5 -.6;.75 1.1]

X0=[[.1;.1],[.5;.5],[-1;-1],[1;-1]];

N=10;

%(j)

A=[.8 .5; -.1 1.0]

X0=[[1;0],[0;-1]];

N=100;

%(k)

A=[1.01 -1.02;1.02 1.01]

X0=[[1;0],[0;-1]];

N=10;

%(l)

A=[.3 .4;-.3 1.1]

X0=[[0;.5],[1;1],[-1;-1],[0;-.5],[-1;-.8],[1;.8],[-.5;.5],[.5;-.5]];

N=10;

%(m)

A=[.5 .6; -.3 1.4]

X0=[[.1;2],[4;0],[-4;0],[-.1;-2]];

N=30;

&nbsp;

<table width="616">
<tbody>
<tr>
<td width="616">%(n)

A=[.8 .3; -.4 1.5]

X0=[[0;1],[-1;0],[0;-1],[1;0],[0;0],[3;0],[-3;0]];

N=50;

%(p)

A=[[1 2;2 4]]

X0=[]; N=10;

%(q)

A=[-.64 0;0 1.36]

X0=[]; N=10;
</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>BONUS! </strong>(1 point)

%Analyze the outputs for the choice (d) and use equation (3) to explain why all trajectories are <u>straight</u> lines.

%Explain the pattern of behavior of the solutions for part (f).

&nbsp;

<strong>BONUS! </strong>(1 point)

In part (g), we have a regular stochastic matrix A. Slightly modify your function trajectory&nbsp; and the vector X0 to output additionally the unique steady-state vector q that describes the evolution of the given Markov Chain. Save your new function in MATLAB as trajectory_1&nbsp; **Print the function trajectory_1

**Run trajectory_1(A,X0,N) with N=100 on the stochastic matrix A given in (g) and your own input X0. Output and <u>display</u> the steady-state vector q.

&nbsp;

<strong>BONUS! </strong>(1 point)

%Analyze the outputs for choices (h),(i),(j), and (k), where the eigenvalues are complex conjugates. Use the equation (3) and the output for magn to explain the pattern of the trajectories for each system.

&nbsp;
