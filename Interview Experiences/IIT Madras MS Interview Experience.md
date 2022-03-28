# **IIT Madras MS Interview Experience**

No written test. Direct Interview calls.

The cutoff was: 700 gate score. UG marks : 75%

Interviews were conducted from 24th May to 26th May.

Mine was on 25th May 2021

Interview was online via google meet.

I was the last person to be interviewed on that day (5:40 PM to 6:10 PM)

**Programming:**

- I1: I like your tie... (everyone laughs…..me too)
- Me : thank you sir.
- I1: Suraj, we will have 2 rounds in this interview. In first round we want to check your programming skills, just if you can convert logic to code. And in second round we will ask on your chosen subject that is Linear Algebra I think.
- I1: Write a C function that takes two sorted arrays as a parameter and you have to check whether those arrays have something in common or not.

Return 1 if have at least one element as common, else return -1.

(they have given a codeshare link, where both can see the code editor live)

Me: written this code:

![](RackMultipart20220328-4-o70w8v_html_78ed6cb7f873462c.png)

(due to nervousness I Forgot to pass array b in binary\_search() function, but they didn&#39;t mock that mistake.)

I1: What is the time complexity of your code.

Me: O(nlogm) n is the size of a, m is the size of n.

I1: correct. Try to optimize it.

Me: Sir, we will check whether n\&gt;m or n\&lt;m, whichever is greater, we will do log of that (i.e apply binary\_search() on that array)

I1: just assume both n &amp; m are nearly equal…..(after few seconds) you have used the sortedness of array a, but try to use the sortedness of b also.

Me: (after 1 minute) Sir, Can I get some hint.

I1: try to compare 1st element of both matrices and then proceed !!

Me: Sir, I got it. I will use the Merge() procedure of Merge-sort and compare elements of both arrays parallelly, then if I found anything equal then return 1.

Its time complexity would be O(n+m)

I1: ok it&#39;s better than nlogm, now code it. We want to check your coding ability.

Me: written this code. ![](RackMultipart20220328-4-o70w8v_html_68cfa45de51db9c3.png)

I1: ok fine, now move to the next part.

**Subject of Choice (Linear Algebra)**

I2: what have you studied? ( he is looking tired by then, due to taking a lot of interviews I think).

Me: Column space, Nullspace, Rowspace..

I2: OK, I ask from Nullspace. write a matrix. The dictated a 2x2 matrix……...find its Nullspace.

Me: its rank is 2. So only zero vector will be the solution.

I2: How you can say this after seeing rank 2?

Me: If we see matrix A as a transformation then only zero vector will land on the origin after the transformation because rank = n means it is a transformation from n-D space n-D space. So every one vector on exactly one vector, So null space is vector zero only.

I2: write a 3x3 matrix now. (He gave a similar kind of matrix(there is same pattern (3x3 matrix is: 123, 234, 234) ).

Now, What are the basis vectors for the nullspace of this matrix?

Me : (took some more time to do Gaussian elimination, due to nervousness)

I2: Is it an invertible matrix?

Me: (after doing Gaussian elimination) No sir this matrix is not invertible. Because it has rank=2. We can take first two columns of this matrix as the basis vectors. ( this was a mistake, first two columns would be the basis vectors for the column space, not nullspace, I realised it later after interview)

I2: hm… ( he gave confused look…..)WHAT is the dimension of that nullspace?

Me: sir, since the rank=2, dimension(N(A)) = n-r = 3-2 = 1.

I2: Now tell what are the basis vectors. Just look the column of the matrix, and say? How will you find Nullspace by looking at the columns of the matrix ?

Me: ( now I got the hint..) Sir, the linear combination of the columns of the matrix should be equal to zero. (after sometime…….)So, here col1+col3-2col2 = 0.

So the solution is [1 -2 1].

I2: ok, now what can you infer from this, if I give you another matrix following this pattern of size 4x4, what can you say about the dimension of its nullspace.

Me: sir it should be n-r =\&gt; (n-2)....as 2x2 have r=2……...3x3 have r=2…..so every matrix would have r=2.

I2: (he didn&#39;t look convinced.) yes it has rank= 2, but how can you say this ?

Me: sir it would give no. of pivots = 2.

I2: No, you have not done this, don&#39;t say directly as I have told you the rank. ( I was not able to understand, what he is asking at this moment).

(meanwhile, he asked other prof that how much time do I have, he replied 4,5 minutes)

I2: ok we don&#39;t have much time that you can now do gaussian Elim of 4x4 matrix. Just tell the two independent vectors in the nullspace, by looking at the column of the matrix? and yes the rank is 2 for 4x4 also.

Me: (after seeing analogy from 3x3, I got it) sir 1st soln is [0 -1 2 -1] and 2nd is [-1 2 -1 0]

I2: what is for 5x5….and now generalise it. What is the rank of nxn matrix of this pattern, and what is the dimension of its nullspace ?

Me: rank = 2, and nullspace dimension = n-r =\&gt; n-2. For 5x5 it is 5-2 = 3 independent vectors in the nullspace.

I2: ok I am done.

……………………………………………………………………………………………………….

Duration : 30 min ( they were keep checking the time left by asking to other prof.)

Suggestion:

- For IITM, just prepare 1 subject properly, they will not ask anything else as I have seen everywhere.( subject can be: Discrete maths, Linear Algebra, Probability, CN, CO, DSA,etc) and 1 programming ques is for sure and they will ask you for some optimisation.
- I will suggest maths topics to choose, becoz they will not go in too deep into it (as they go in OS, COA)
- Most of the IITM Profs especially are very encouraging.