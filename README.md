# Roboadvisor - A Portfolio Selection Recommendation System
A portfolio selection recommendation system based on Markowitz Mean-Variance Model and Black-Litterman Model implemented on the App "Navigator".
This is my first practical project during my internship at Asset Pro in Beijing. And the project is already implemented on the "Navigator" financial APP with thousands of users.


## About

Here are the presentation slides for the whole project.

[RoboAdvisor - Presentation Slides](https://github.com/PeterQiu0516/RoboAdvisor/raw/master/01_13/%E5%9F%BA%E4%BA%8EMarkowitz%20Mean-Variance%E4%B8%8EBlack-Litterman%E7%90%86%E8%AE%BA%E7%9A%84%E8%B5%84%E4%BA%A7%E9%85%8D%E7%BD%AE%E6%A8%A1%E5%9E%8B%E2%80%94%E2%80%94%E6%9C%AA%E6%9D%A5%E8%88%AA%E6%B5%B7%E5%AE%B6RoboAdvisor%E6%96%B0%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D.pdf)

You may also take a glance at the sample portfolio report generated by the Roboadvisor.

[Sample Portfolio Report - Risk Level 5 (most aggressive strategy, for risk-loving customers)](https://github.com/PeterQiu0516/RoboAdvisor/raw/master/Sample%20Portfolio%20Report%20-%20Risk%20Level%205.pdf)

[Sample Portfolio Report - Risk Level 3 (neutral strategy, for risk-neutral customers)](https://github.com/PeterQiu0516/RoboAdvisor/raw/master/Sample%20Portfolio%20Report%20-%20Risk%20Level%203.pdf)

[Sample Portfolio Report - Risk Level 1 (most convervative strategy, for risk-averse customers)](https://github.com/PeterQiu0516/RoboAdvisor/raw/master/Sample%20Portfolio%20Report%20-%20Risk%20Level%201.pdf)

### Programming Languages

+ **Python 3**: For model implementation `(PyPortOpt)` online data crawling `(selenium)`, project integrating `(rpy2)` and data processing `(pandas)`.
+ **R**: For model implementation `(PortfolioAnalytics)` and online data crawling `(rvest)`.
+ **Javascript**: For plotting related intuitive financial figures `(ECharts)` and online survey designing.
+ **Html**: For online survey designing.

### Building

On Win 10, run

```
pip install RoboAdvisor
```

### Running
Access the '01_15' directory and make sure that the three input files `bloomberg.csv`、`filter.csv` and `newfund.csv` are present in the '01_15' directory.

Then run

```
python final.py
```

And access the following [survey page](localhost:9000)




## Milestones

### Data
+  Obtained the historical NAV(Net Asset Value) data for about 800 selected funds from [iFund](https://www.ifund.com.hk/en/companies/) and Bloomberg based on Python, Excel and R.

+  Then I designed a questionaire for investigating the customers' specific needs (like risks and return rates requirements).

+  Then I designed the specific funding recommendation system to satisfy each customer's specific needs based on Python and R. I utilized the famous Markowitz and Black-Litterman model in the main body of the project.

+ ... To be completed.
