# Fetal Health Classification
This study uses machine learning algorithms such as <strong>K-Nearest Neighbors (KNN)</strong>, <strong>Random Forest</strong>, and <strong>Support Vector Classification (SVC)</strong> to easily analyze cardiotocogram (CTG) data and evaluate their fetal and maternal health outcomes as normal, suspicious, and pathological.

<h2>What is Fetal Death?</h2>
Fetal death refers to the spontaneous intrauterine death of the fetus during pregnancy. Fetal mortality is generally divided into three periods: less than 20 weeks of pregnancy, 20-28 weeks of pregnancy, and 28 or more weeks of pregnancy [1]. Fetal and maternal death due to various reasons is one of the tragic events observed all over the world. According to research, the number of maternal and fetal deaths is quite high. In 2020, approximately 287,000 women died during and after pregnancy and childbirth. Approximately 95% of maternal deaths this year occurred in low- and middle-income countries [2]. The healthy growth and development of the fetus is directly related to the health status of the mother. If the pregnancy process could be monitored reliably and the necessary interventions could be detected and implemented at an early stage, the rate of deaths occurring could be significantly reduced. Therefore, it is of great importance to effectively monitor maternal and fetal health.

<h2>What is Cardiotocogram?</h2>
Cardiotocography (CTG) is the process of recording the fetal heartbeat and uterine contractions during pregnancy. In this process, the machine used to perform monitoring of the required parameters is called cardiotocograph [3]. CTGs are used to detect and prevent potential complications in the fetus.

<h2>Dataset</h2>
The data set of fetal health assessments obtained from CTG examinations was taken from Kaggle. You can access the dataset <a href="https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification/data">here.</a> The dataset considered in this study includes 2126 fetal cardiotocogram (CTG) exams and the relevant 21 measured diagnostic features.

<h3>Features</h3>
<ul>
  <li><strong>baseline value:</strong> FHR baseline (beats per minute)</li>
  <li><strong>accelerations:</strong> Number of accelerations per second</li>
  <li><strong>fetal_movement:</strong> Number of fetal movements per second</li>
  <li><strong>uterine_contractions:</strong> Number of uterine contractions per second</li>
  <li><strong>light_decelerations:</strong> Number of light decelerations per second</li>
  <li><strong>severe_decelerations:</strong> Number of severe decelerations per second</li>
  <li><strong>prolongued_decelerations:</strong> Number of prolonged decelerations per second</li>
  <li><strong>abnormal_short_term_variability:</strong> Percentage of time with abnormal short term variability</li>
  <li><strong>mean_value_of_short_term_variability:</strong> Mean value of short term variability</li>
  <li><strong>percentage_of_time_with_abnormal_long_term_variability:</strong> Percentage of time with abnormal long term variability</li>
  <li><strong>mean_value_of_long_term_variability:</strong> Mean value of long term variability</li>
  <li><strong>histogram_width:</strong> Width of FHR histogram</li>
  <li><strong>histogram_min:</strong> Minimum (low frequency) of FHR histogram</li>
  <li><strong>histogram_max:</strong> Maximum (high frequency) of FHR histogram</li>
  <li><strong>histogram_number_of_peaks:</strong> Number of histogram peaks</li>
  <li><strong>histogram_number_of_zeroes:</strong> Number of histogram zeros</li>
  <li><strong>histogram_mode:</strong> Histogram mode</li>
  <li><strong>histogram_mean:</strong> Histogram mean</li>
  <li><strong>histogram_median:</strong> Histogram median</li>
  <li><strong>histogram_variance:</strong> Histogram variance</li>
  <li><strong>histogram_tendency:</strong> Histogram tendency</li>
  <li><strong>fetal_health:</strong> Fetal health status as 1 (Normal), 2 (Suspect) and 3 (Pathological)</li>
</ul>

<h2>Model Evaluation</h2>
You can explore the solutions and model methodologies for the given problem on platforms such as <a href="https://github.com/berkayuzer/Fetal-Health-Classification/blob/main/fetal-health-classification.ipynb">GitHub</a> or <a href="https://www.kaggle.com/code/berkayuzer/fetal-health-classification-96-45-accuracy">Kaggle.</a>
    
<h2>Contributions</h2>
This study was conducted as a group project.
<ul>
  <li><a href="https://github.com/berkayuzer">Berkay ÜZER</a></li>
  <li>İrem Gül ER</li>
</ul>

<h2>References</h2>
<ul>
<li>[1] <a href="https://www.cdc.gov/nchs/nvss/fetal_death.htm">Centers for Disease Control and Prevention. (2022, October 18). NVSS - Fetal Deaths. Centers for Disease Control and Prevention.</a></li>
<li>[2] <a href="https://www.who.int/news-room/fact-sheets/detail/maternal-mortality">World Health Organization. (n.d.). Maternal Mortality. World Health Organization.</a></li>
<li>[3] <a href="https://www.dremeilkamel.com.au/patient-resources/obstetrics/cardiotocography/">Kamel, E. (2017, July 13). Cardiotocography (CTG). Dr Emeil Kamel.</a></li>
</ul>


