# gr5206-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [GR5206 Homework 2 Solved](https://www.ankitcodinghub.com/product/gr5206-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94736&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GR5206 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Goals: data cleaning, EDA, R graphics, more practice with filtering and vectorized com- mands.

The data set NYChousing.csv contains property-level data on privately-owned, subsidized rental properties in New York City collected by the Furman Center. The data can be down- loaded from Canvas. The dataset contains financial and physical information on the prop- erties including geographic, subsidy, ownership, physical, and financial information.

Perform the following tasks:

Part 1: Loading and Cleaning the Data in R

<ol>
<li>Load the data into a dataframe called housing.</li>
<li>How many rows and columns does the dataframe have?</li>
<li>Run this command, and explain, in words, what this does:
apply(is.na(housing), 2, sum).
</li>
<li>Remove the rows of the dataset for which the variable Value is NA.</li>
<li>How many rows did you remove with the previous call? Does this agree with your result from (iii)?</li>
<li>Create a new variable in the dataset called logValue that is equal to the logarithm of the property’s Value. What are the minimum, median, mean, and maximum values of logValue?</li>
<li>Create a new variable in the dataset called logUnits that is equal to the logarithm of the number of units in the property. The number of units in each piece of property is stored in the variable UnitCount.</li>
<li>Finally create a new variable in the dataset called after1950 which equals TRUE if the property was built in or after 1950 and FALSE otherwise. You’ll want to use the YearBuilt variable here. This can be done in a single line of code.
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 2: EDA

</div>
</div>
<div class="layoutArea">
<div class="column">
The column Borough contains the Borough of each property and is one of either Bronx, Manhattan, Staten Island, Brooklyn, or Queens.

<ol>
<li>Plot property logValue against property logUnits. Name the x and y labels of the plot appropriately. logValue should be on the y-axis.</li>
<li>Makethesameplotasabove,butnowincludetheargumentcol = factor(housing$after1950). Describe this plot and the covariation between the two variables. What does the coloring

in the plot tell us?

Hint: legend(“bottomright”, legend = levels(factor(housing$after1950)), fill = unique(factor(housing$after1950))).
</li>
<li>The cor() function calculates the correlation coefficient between two variables. What is the correlation between property logValue and property logUnits in (i) the whole data, (ii) just Manhattan (iii) just Brooklyn (iv) for properties built after 1950 (v) for properties built before 1950?</li>
<li>Make a single plot showing property logValue against property logUnits for Manhat- tan and Brooklyn. When creating this plot, clearly distinguish the two boroughs.</li>
<li>Consider the following block of code. Give a single line of R code which gives the same final answer as the block of code. There are a few ways to do this.
<pre>    manhat.props &lt;- c()
</pre>
<pre>    for (props in 1:nrow(housing)) {
      if (housing$Borough[props] == "Manhattan") {
</pre>
<pre>        manhat.props &lt;- c(manhat.props, props)
      }
</pre>
}

<pre>    med.value &lt;- c()
    for (props in manhat.props) {
</pre>
<pre>      med.value &lt;- c(med.value, housing$Value[props])
    }
</pre>
<pre>    med.value &lt;- median(med.value, na.rm = TRUE)
</pre>
</li>
<li>Make side-by-side box plots comparing property logValue across the five boroughs.
2
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
vii. For five boroughs, what are the median property values? (Use Value here, not logValue.)

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
