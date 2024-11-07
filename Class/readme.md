30 Sept 2024
-------------------------------------------------------------
-------------------------------------------------------------

AP and GP - focus on a when Ap, and r when GP
1,3,5,7    ascending order
5,4,3,2,1  descending order

common difference = 5 10 15 20 25 = 5;

# Formulas:-
# An = a + (n-1)d
# Sn = n/2[2a + (n-1)d]
# Sn = n/2(a+l)

where,
    a = first term
    d = common difference
    l = last term
    n = total no of terms
    An = last term

# Questions
Q1. The First and the last terms of an AP are 17 and 350, if common difference is 9, how many terms are there and what is the sum of them.
Soln =>
        a = 17
        l = 350
        d = 9

        sum of all terms = n/2(a+l)
        n = ?

        An = a + (n-1)d
        350 = 17 + (n -1)9
        n = 38

        Sn = 38/2(17 + 350)
        Sn = 6973 ans.

Q2. 200 logs are stacked in the following manner,
        20 logs are in the bottom row,
        19 in the next row,
        18 in the row next to it,
        and so on.
    in how many rows are the 200 logs placed and how many logs in the top row.
Soln =>
        a = 20
        d = -1
        Sn = 200
        An = l = ?

        Sn = n/2[2a + (n-1)d]
        200 = n/2(2*20+ (n-1)*-1)  -- eq1
        
        {
            n2 - 41n + 400 = 0
            n2 - 16n - 25n + 400 = 0
            n(n-16) -25(n + 16) = 0
            (n - 16)(n - 25) = 0
            n = 16
            n = 25

            chech n in eq1
            n = 16 true
        }
  
        n = 16

        Sn = n/2(a+l)
        Sn = n/2(20 + l)
        l = 5

        Hence, no of rows will be n = 16, and log in the top row is l = 5.

Q3. The sum of first 7 terms of an AP is 49, and the sum of first 17 terms is 289. Find the sum of first n terms.
Soln =>
        Sn = n/2[a + (n-1)d], put the values of both the conditions in this formula

        firstly,
               put n = 7, Sn = 49 as given in question
               49 = 7/2[2a + (7-1)d]
               7 =  a + 3d --eq1

        Now,
                put n = 17, Sn = 289 given in the question
                289 = 17/2[2a + (17-1)d]
                17 = a + 8d --eq2

        Now Subtract eq2 form eq2:-
                                    17 = a + 8d
                                    -7 = -a - 3d
                                    d = 2

        Now, put the value of d=5 in eq1:-

                                    7 = a + 3*2
                                    a = 1

        Now, we have:-
                        d = 5
                        a = 1

        Sn = n/2[2a + (n-1)d]
        Sn = n/2[2*1 + (n-1)2]
        Sn = n2 ans.


Geometric Progression (GP):-
---------------------------------------------------------------
---------------------------------------------------------------

4,8,16,32,64,128,....
Ratio of next term and inital term is always the same
    4:8 = 1:2 common ratio
    8:16 = 1:2, and so on

In, a1,a2,a3,a4,a5,a6,a7,a8,.................
    a1/a2 = a3/a4 = a5/6, aka common ratio

Here, 
    a = first terms
    r = common ratio

# Formulas:-
    nth term = Tn = a*r.pow(n-1)
    Sn = [a(r.pow(n) - 1)]/r -1, in case of r > 1
    Sn = [a(1-r.pow(n))]/(1 - r), in case of r < 1


# Questions

Q1. Find the 5th term in the GP. 1/7,1/14,1/28,....
Soln =>
        tn = a*r.pow(n-1)
        tn = (1/7)*[1/2].pow(5-1)
        tn = 1/112 ans,

Q2. Find sum, 10 +100 + 1000 + 10000 + .... + 40th term
Soln =>
        a = 10
        r = 10
        n = 40

        Sn = [a(r>pow(n) - 1)]/(r - 1)
        Sn = [10(10.pow(40)-1)]/9
        Sn = 10/9*10.pow(40) ans.

Q3. Find the sum. 9,99,999,9999,9999,.....,100th term
Soln =>
        It doesn't even look like a GP at a first glance but:-

        10-1,100-1,1000-1,10000-1,100000-1, ....., 100th term
        (10+100+1000+10000+......) - 100 --eq1

        Sn = [a(rn-1)] / (r-1)
        Sn = 10(10.pow(100)-1) / (10 - 1) - 100

        Sn = [10.pow(101) - 910] / 9 ans.


Q4. Find the sum. 5,55,555,5555,55555......100th term
Soln => 
        It doesn't look a GP at a glance:-

        5/9[9,99,999,9999,99999.....100th term]
        5/9[(10-1), (100-1), ....., 100th term]

        !---------Cloud be wrong------
        Sn = [a(r.pow(n)-1)] / (r-1)
        Sn = 5/9[10(10.pow(100)-1) / (10 - 1) - 100]

        Sn = 5/9{[10.pow(101) - 910] / 9} ans.
        

Testᵃᵇᶜᵈᵉᶠᵍʰⁱʲᵏˡᵐⁿᵒᵖʳˢᵗᵘᵛʷˣʸᶻ
so hello form the o

ṣṣṣṣṣṣ
ṢṆṀṀL̥ḤṄŚĀÆĒR̥ṬŪŪŌ

To convert a portion of text to a superscript or subscript just type '\_123' or '\^123' + [tab]. This will display ₁₂₃ or ¹²³. For a full list of supported subscript and superscript characters see here.

Xʰᵉˡˡᴼ


Q6. A = 1/4+1/16+1/64.....nthterm and b= 1+1/2++1/4...... 2n term
        fint a/b
Soln =>
        Sₙ = a(rⁿ - 1)/(r - 1)

        a/b = [(1/4(1/4)ⁿ - 1)/ (1/4 - 1)] / [(1(1/2)ⁿ - 1)/ (1/2 - 1)]
        a/b = 





\frac{a}{b}

<!-- box      -->


Q7. A Ball is thrown from a height of 5k meters. on a ground the ball bounced 4/5 times of its every last bounce, calculate the total distance covered by the ball till it stopped.
Soln =>
        Gp = 5000, 5000x4/5, 5000x4/5x4/5,..... etc
        so,
        5000+4000, 4000+3200,... and so on

        a = 9000
        r = 7200/9000 = 4/5

        For Descending, the formula of infinity is = Sₙ = a/(1 - r)

        Sₙ = 9000/(4/5 - 1)
        Sₙ = 45000 ans.


Q8. A ball is thrown from a height of 540 meters on a ground, the ball bounced back 2/3 times of its previous bounce. calculate the total distance covered by the ball till it stopped
Soln =>
        GP = 540, 540x2/3, 540x2/3x2/3....... and so on
        540*2/3 = 360
        360*2/3= 240
        240*2/3 =160
        and so on

        so, 
                900, 600......etc
                a = 900
                r = 2/3

                Sₙ = a/(1 - r)
                Sₙ = 900/((2/3) - 1)
                Sₙ = 2700 meter ans.

Q9. The side of the square is 16 cm, infinite number of squares are made by joining mid points of each side of the square. Calculate the total area of all the infinite number of Squares
Soln =>
        Pythagoras theoram will be used here
        Square inside a square

        h² = p² + b²

        GP = 16², 8root2²,....... and so on

        here,
                a = 16²
                r = 1/2

                For Descending, the formula of infinity is = Sₙ = a/(1 - r)
                Sₙ = 256/ [1 - 1/2]
                Sₙ = 512 cm² ans.



Q10. The side of a square is 20 cm and inifinite number of squares are made by joining the mid points of the square, calulate the total area of the Squares
Soln =>
        Pythagoras theoram will be used here
        Square inside a square

        h² = p² + b²

        GP = 20², 5root8²,....... and so on

        here,
                a = 20²
                <!-- r = 1/2 -->

                For Descending, the formula of infinity is = Sₙ = a/(1 - r)
                <!-- Sₙ = 256/ [1 - 1/2] -->
                Sₙ = 800 cm² ans.


Q11. The side of a right angled triangle are 6, 8, and 10. a new right angled triangle is formed by joining the mids of the triangle, calculate the total area of all the triangles.
Soln =>
        Pythagoras theoram will be used here
        Square inside a square

        h² = p² + b²

        GP = 1/2*b*h
        GP = 

        For Descending, the formula of infinity is = Sₙ = a/(1 - r)
        Sₙ = 30 cm² ans.











# How to use linked for fresher
# for fresher job (job profile)
# or any hiring platforms

# Internshala
# How to build professional resume for (profile)



                
        








        







          













