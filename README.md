# Fetal Cardiotocography Analysis

Website Link: 
- [Report Part 1](https://express.adobe.com/page/OCn3NTYaM8SHb/)
- [Report Part 2: Neural Network and Random Forest]()

## Dataset Description

Abstract: <br>
The dataset consists of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocograms classified by expert obstetricians.

Data Set Information: <br>
- 2126 fetal cardiotocograms (CTGs) were automatically processed and the respective diagnostic features measured. 
- The CTGs were also classified by three expert obstetricians and a consensus classification label assigned to each of them. 
- Classification was both with respect to a morphologic pattern (A, B, C. ...) and to a fetal state (N, S, P). 
- Therefore the dataset can be used either for 10-class or 3-class experiments.

Attribute Information: <br>
LB - FHR baseline (beats per minute) <br>
AC - # of accelerations per second <br>
FM - # of fetal movements per second <br>
UC - # of uterine contractions per second <br>
DL - # of light decelerations per second <br>
DS - # of severe decelerations per second <br>
DP - # of prolongued decelerations per second <br>
ASTV - percentage of time with abnormal short term variability <br>
MSTV - mean value of short term variability <br>
ALTV - percentage of time with abnormal long term variability <br>
MLTV - mean value of long term variability <br>
Width - width of FHR histogram <br>
Min - minimum of FHR histogram <br>
Max - Maximum of FHR histogram <br>
Nmax - # of histogram peaks <br>
Nzeros - # of histogram zeros <br>
Mode - histogram mode <br>
Mean - histogram mean <br>
Median - histogram median <br>
Variance - histogram variance <br>
Tendency - histogram tendency <br>
CLASS - FHR pattern class code (1 to 10) <br>
NSP - fetal state class code (N=normal; S=suspect; P=pathologic) <br>
