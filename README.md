# Company2
My implementation of Google Analytics data with Python and BigQuery: Multichannel Path/Grouping, Attribution Model (heuristic+markov), Time-lag calculation, Keyword Focus, Uplift/PtB modelling


# 0. Working with Google Analytics API v3 (ga:report, mcf:report)


# 1. Multichannel Path/Grouping:
* With the mcf report from GA API v3 mcf:report, I have to group the channel according defined rules
https://colab.research.google.com/drive/1jltvVV7Q7ToFD0Vr-E23T8RsiuHZgz6I?usp=sharing
https://colab.research.google.com/drive/1WUPXZUWWA9RKQTIyA8aQwQtRH5O3p-uQ?usp=sharing
https://colab.research.google.com/drive/1z9JojmRo6xgk7MqaHJ-qxgg4v_R5EZFn?usp=sharing

# 2. Attribution Model (heuristic+markov)
* Attribution modeling with DP6 package: https://github.com/DP6/Marketing-Attribution-Models
https://colab.research.google.com/drive/1J5b0yY1JKWWeXAYOzftE2NFpAiEww0mI?usp=sharing
https://colab.research.google.com/drive/1ZUrTQledut4Xll-jDLVI1kcDy24J2usv?usp=sharing

# 3. Time-lag calculation
* Calculate number of days between touchpoint end the final conversion day
https://colab.research.google.com/drive/1GoQMK0C1PTfBOl_s8l8KtSwtdyHOT1w7?usp=sharing
https://colab.research.google.com/drive/1vuPJdgeUPuGg_GTOa2FufOUtIwhSut6U?usp=sharing

## Life-time Values with BQ
* LTV=Cumulative sum of revenue to certain date
https://colab.research.google.com/drive/1P_KtocdkLQ-qCF5pRIAa3J9Ty4cEKQAP?usp=sharing

# 4. Keyword Focus
* Focus on keyword analysis
https://colab.research.google.com/drive/1xycJLkzlxEiWBiPETsEetZo5yRFdZ2Sh?usp=sharing
https://colab.research.google.com/drive/1--VW2Sd2e69QsiXYarEY_UuUZ8BrnXLJ?usp=sharing

# 5. Uplift/PtB modelling
* Logistics Modeling, Uplift Modeling for customer conversion prediction and campaign effectiveness respectively
https://colab.research.google.com/drive/1W6c_F52iv-EWFLAEPjwq5d_nHRjgEnQw?usp=sharing
https://colab.research.google.com/drive/1o7hmpuzTkd4FC78ahGDp2jgrEfJDCJBs?usp=sharing
https://colab.research.google.com/drive/1rtUM5ibjUt_1GbQ3KIAoO56Xy-8mz6Hy?usp=sharing
