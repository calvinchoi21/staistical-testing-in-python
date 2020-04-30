# Application of Statistical Testing in Python

While Python is a powerful, general purpose, language that is widely used in data science, R is a domain-specific language designed for statistical analysis. Its libraries are often released by researchers and the documentation and code is accompanied by citations from scientific papers. The application of statistical formulas are much simplier with R language and the outputs tend to be more informative than their counterparts in Python (although there are packages in Python that can provide a similar framework to R, i.e. statsmodels). 

The purpose of this project is to demonstrate through examples how one can apply statistical testing in Python using only SciPy.stats to achieve the similar functionality as R. 

### Contents

<ul>
  <li>1. Parametric (Normal Distribution) Testing:   
    <ul>
      <li>1.1 Comparing Two Groups:
        <ul>
          <li>1.1.1 Unpaired: sample t-tests</li>
          <li>1.1.2 Paired: paired t-test</li>
          <li>1.1.3 Chi-square test for variance</li>
        </ul>
      </li>
      <li>1.2 Comparing More than Two Groups:
        <ul>
          <li>1.2.1 Sample design: one way ANOVA</li>
          <li>1.2.2 Block design: two way ANOVA</li>
        </ul>
      </li>
     </ul>
    </li>
    <li>2. Non-Parametric (Non-Normal Distribution) Testing:   
      <ul>
        <li>2.1 Comparing Two Groups:
           <ul>
             <li>2.1.1 Unpaired: Wilcoxon rank-sum test</li>
             <li>2.1.2 Paired: Wilcoxon signed-rank test </li>
           </ul>
        </li>
        <li>2.2 Comparing More than Two Groups:
           <ul>
             <li>2.2.1 Sample design: Kruskal-Wallis test</li>
             <li>2.2.2 Block design: Friedman test</li>
           </ul>
        </li>
      </ul>
    </li>
</ul>
