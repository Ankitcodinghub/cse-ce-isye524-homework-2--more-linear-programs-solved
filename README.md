# cse-ce-isye524-homework-2--more-linear-programs-solved
**TO GET THIS SOLUTION VISIT:** [CSE-CE-ISyE524 Homework 2- More Linear Programs Solved](https://www.ankitcodinghub.com/product/cse-ce-isye524-homework-2-more-linear-programs-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120320&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE-CE-ISyE524  Homework 2- More Linear Programs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
(Submit a pdf image of your Jupyter notebook via Canvas.)

(Please denote the start of each question in your Julia workbook using a LARGEFONT.)

2. [4 points]

Stigler’s diet. In 1945, American economist (and future Nobel Memorial Prizewinner in Economics) George Stigler published a paper investigating the composition of an optimal diet; minimizing total cost while meeting the recommended daily allowance (RDA) of several nutrients. To answer this question, Stigler tabulated a list of 77 foods and their nutrient content for 9 nutrients: calories, protein, calcium, iron, vitamin A, thiamine, riboflavin, niacin, and ascorbic acid. Here is what the first few rows and columns of his table looked like:

Calories (1000) Protein (g) Calcium (g) Iron (mg) …

Wheat Flour (Enriched) 44.7 1411 2 365 …

Macaroni 11.6 418 0.7 54 …

Wheat Cereal (Enriched) 11.8 377 14.4 175 …

… … … … … …

To make calculations easier, Stigler normalized his data so each row shows the nutrients contained in $1’s worth of the given food item. Back then, $1 could buy you quite a lot!

When Stigler posed his diet problem, the simplex method had not yet been invented. In his paper, he wrote: “…the procedure is experimental because there does not appear to be any direct method of finding the minimum of a linear function subject to linear conditions.” Nevertheless, through a combination of what he called “trial and error, mathematical insight, and agility”, he eventually arrived at a solution: a diet costing only $39.93 per year. Though he confessed: “There is no reason to believe that the cheapest combination was found, for only a handful of the [many] possible combinations of commodities were examined.”

(a) Formulate Stigler’s diet problem as an LP and solve it. To get you started, Stigler’s original data is provided in stigler.csv, and the IJulia notebook stigler.ipynb imports the data and puts it into a convenient array format. How does your cheapest diet compare in annual cost to Stigler’s? What foods make up your optimal diet? Write out a list of foods and the optimal daily number of units, for just those foods where the optimal diet has more than 0 units.

Note: Remember that the lower bounds are for daily quantities, so you can solve the LP to find the optimal daily cost of the diet, but remember to multiply by 365 to obtain the optimal annual cost.

(b) For the model above, print out the lower bounds for each nutrient alongside the amount of nutrient in the optimal diet and the dual variable corresponding to that constraint. Which of these bounds are active, that is, satisfied by the solution with equality? Verify that complementarity is satisfied for this solution.

1 of 2

(Remember that the solutions of LPs often contain some roundoff error, so the reported nutrient amounts for the optimal solution might be very slightly infeasible, but in such cases we would report them as “active.”

(c) Suppose we wanted to find the cheapest diet that contains no “Liver (Beef)” and at least .01 units of “Milk.” Again, write out the foods that consitute the optimal diet, the amount of each, and the annual cost.

3. [3 points]

Museum site planning. A site is being investigated as a potential location for a new museum. An aerial plan of the site is shown in the figure below (in units of feet). The museum will have a circular footprint and law mandates that there be at least 75 feet of clearance between the building and any edge of the site. If we want the largest possible museum, where should it be located? What is its optimal radius?

(a) In a markdown cell in your jupyter notebook, write down the mathematical model of this optimization problem, including the decision variables, constraints and objective function. Make sure to describe all problem parameters.

(b) Solve the problem in Julia/JuMP, finding the optimal location for the museum and the optimal radius. Re-plot the figure below, indicating the footprint of the museum as a red circle. Hint:

Use the Julia code in Chebyshev plot figure.ipynb to plot the figure below.

2 of 2
