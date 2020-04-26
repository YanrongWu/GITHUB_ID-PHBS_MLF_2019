```
CASE_1#Dataframe:

             DATE  10M1  1Q_LAG
0       1967/10/2  0.06     0.0
1       1967/10/3  0.06     0.0
2       1967/10/4  0.06     0.0
3       1967/10/5  0.06     0.0
4       1967/10/6  0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.37     0.0
12776  2018/11/27  0.36     0.0
12777  2018/11/28  0.37     0.0
12778  2018/11/29  0.34     0.0
12779  2018/11/30  0.31     0.0

[12780 rows x 3 columns]
CASE_1#scores_LR: CV accuracy: 0.687 +/- 0.003
CASE_1#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_1#scores_DT: CV accuracy: 0.714 +/- 0.004
CASE_1#LR Best Score: 0.685222445785826
CASE_1#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_1#SVM Best Score: 0.6787391012743126
CASE_1#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_1#DT Best Score: 0.7107086966241896
CASE_1#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_1
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.685222445785826
CV Accuracy: 0.6867867721495257+-0.003090525584376196
SVM painting... ...
Data: DATASET_1
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_1
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7107086966241896
CV Accuracy: 0.7137271443390449+/-0.004375898022446026
CASE_1_FINISHED ########################################################################
CASE_2#Dataframe:

             DATE  10M1  3Q_LAG
0       1967/10/2  0.06     0.0
1       1967/10/3  0.06     0.0
2       1967/10/4  0.06     0.0
3       1967/10/5  0.06     0.0
4       1967/10/6  0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.37     0.0
12776  2018/11/27  0.36     0.0
12777  2018/11/28  0.37     0.0
12778  2018/11/29  0.34     0.0
12779  2018/11/30  0.31     0.0

[12780 rows x 3 columns]
CASE_2#scores_LR: CV accuracy: 0.708 +/- 0.005
CASE_2#scores_SVM: CV accuracy: 0.679 +/- 0.004
CASE_2#scores_DT: CV accuracy: 0.723 +/- 0.011
CASE_2#LR Best Score: 0.7074670243684329
CASE_2#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_2#SVM Best Score: 0.681757209926224
CASE_2#SVM Best Params: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_2#DT Best Score: 0.7217750950145316
CASE_2#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_2
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.7074670243684329
CV Accuracy: 0.7080269456213365+-0.0054375806811989376
SVM painting... ...
Data: DATASET_2
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.681757209926224
CV Accuracy: 0.6794098459000412+/-0.004258218177421811
DT painting... ...
Data: DATASET_2
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7217750950145316
CV Accuracy: 0.723454313674028+/-0.01102801680851481
CASE_2_FINISHED ########################################################################
CASE_3#Dataframe:

             DATE  10M1  5Q_LAG
0       1967/10/2  0.06     0.0
1       1967/10/3  0.06     0.0
2       1967/10/4  0.06     0.0
3       1967/10/5  0.06     0.0
4       1967/10/6  0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.37     0.0
12776  2018/11/27  0.36     0.0
12777  2018/11/28  0.37     0.0
12778  2018/11/29  0.34     0.0
12779  2018/11/30  0.31     0.0

[12780 rows x 3 columns]
CASE_3#scores_LR: CV accuracy: 0.696 +/- 0.009
CASE_3#scores_SVM: CV accuracy: 0.672 +/- 0.006
CASE_3#scores_DT: CV accuracy: 0.718 +/- 0.008
CASE_3#LR Best Score: 0.6962888441761681
CASE_3#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_3#SVM Best Score: 0.6699083389224234
CASE_3#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_3#DT Best Score: 0.7211044042029957
CASE_3#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_3
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6962888441761681
CV Accuracy: 0.696286603426943+-0.009058353584985773
SVM painting... ...
Data: DATASET_3
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6699083389224234
CV Accuracy: 0.6715863672153276+/-0.005881266296795179
DT painting... ...
Data: DATASET_3
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7211044042029957
CV Accuracy: 0.7175256520815367+/-0.007511724065453241
CASE_3_FINISHED ########################################################################
CASE_4#Dataframe:

             DATE  10M3  1Q_LAG
0       1967/10/2 -0.09     0.0
1       1967/10/3 -0.08     0.0
2       1967/10/4 -0.09     0.0
3       1967/10/5 -0.07     0.0
4       1967/10/6 -0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.21     0.0
12776  2018/11/27  0.20     0.0
12777  2018/11/28  0.22     0.0
12778  2018/11/29  0.20     0.0
12779  2018/11/30  0.18     0.0

[12780 rows x 3 columns]
CASE_4#scores_LR: CV accuracy: 0.681 +/- 0.002
CASE_4#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_4#scores_DT: CV accuracy: 0.705 +/- 0.005
CASE_4#LR Best Score: 0.6816454281243014
CASE_4#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_4#SVM Best Score: 0.6787391012743126
CASE_4#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_4#DT Best Score: 0.7033310976972948
CASE_4#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 1}
LR painting... ...
Data: DATASET_4
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6816454281243014
CV Accuracy: 0.6814217689625435+-0.0017400368985502285
SVM painting... ...
Data: DATASET_4
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_4
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 1}
Best Scores: 0.7033310976972948
CV Accuracy: 0.7050085611088199+/-0.004758038554937969
CASE_4_FINISHED ########################################################################
CASE_5#Dataframe:

             DATE  10M3  3Q_LAG
0       1967/10/2 -0.09     0.0
1       1967/10/3 -0.08     0.0
2       1967/10/4 -0.09     0.0
3       1967/10/5 -0.07     0.0
4       1967/10/6 -0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.21     0.0
12776  2018/11/27  0.20     0.0
12777  2018/11/28  0.22     0.0
12778  2018/11/29  0.20     0.0
12779  2018/11/30  0.18     0.0

[12780 rows x 3 columns]
CASE_5#scores_LR: CV accuracy: 0.697 +/- 0.006
CASE_5#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_5#scores_DT: CV accuracy: 0.715 +/- 0.011
CASE_5#LR Best Score: 0.6968477531857813
CASE_5#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_5#SVM Best Score: 0.6787391012743126
CASE_5#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_5#DT Best Score: 0.7173038229376257
CASE_5#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 3}
LR painting... ...
Data: DATASET_5
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.6968477531857813
CV Accuracy: 0.6969597440415932+-0.00569557038287197
SVM painting... ...
Data: DATASET_5
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_5
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 3}
Best Scores: 0.7173038229376257
CV Accuracy: 0.7147353555047304+/-0.011497198648345934
CASE_5_FINISHED ########################################################################
CASE_6#Dataframe:

             DATE  10M3  5Q_LAG
0       1967/10/2 -0.09     0.0
1       1967/10/3 -0.08     0.0
2       1967/10/4 -0.09     0.0
3       1967/10/5 -0.07     0.0
4       1967/10/6 -0.07     0.0
...           ...   ...     ...
12775  2018/11/26  0.21     0.0
12776  2018/11/27  0.20     0.0
12777  2018/11/28  0.22     0.0
12778  2018/11/29  0.20     0.0
12779  2018/11/30  0.18     0.0

[12780 rows x 3 columns]
CASE_6#scores_LR: CV accuracy: 0.684 +/- 0.008
CASE_6#scores_SVM: CV accuracy: 0.680 +/- 0.001
CASE_6#scores_DT: CV accuracy: 0.699 +/- 0.008
CASE_6#LR Best Score: 0.6835457187569863
CASE_6#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_6#SVM Best Score: 0.6794097920858484
CASE_6#SVM Best Params: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_6#DT Best Score: 0.6965124077800133
CASE_6#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_6
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6835457187569863
CV Accuracy: 0.6841022083911364+-0.008000313263959632
SVM painting... ...
Data: DATASET_6
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6794097920858484
CV Accuracy: 0.679633309587192+/-0.001340634138225243
DT painting... ...
Data: DATASET_6
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.6965124077800133
CV Accuracy: 0.6989712921650232+/-0.0077231435387789754
CASE_6_FINISHED ########################################################################
CASE_7#Dataframe:

             DATE   5M1  1Q_LAG
0       1967/10/2  0.14     0.0
1       1967/10/3  0.15     0.0
2       1967/10/4  0.16     0.0
3       1967/10/5  0.16     0.0
4       1967/10/6  0.18     0.0
...           ...   ...     ...
12775  2018/11/26  0.20     0.0
12776  2018/11/27  0.19     0.0
12777  2018/11/28  0.18     0.0
12778  2018/11/29  0.16     0.0
12779  2018/11/30  0.14     0.0

[12780 rows x 3 columns]
CASE_7#scores_LR: CV accuracy: 0.686 +/- 0.004
CASE_7#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_7#scores_DT: CV accuracy: 0.716 +/- 0.010
CASE_7#LR Best Score: 0.6853342275877488
CASE_7#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_7#SVM Best Score: 0.6787391012743126
CASE_7#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_7#DT Best Score: 0.7158506595126314
CASE_7#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_7
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6853342275877488
CV Accuracy: 0.6858927924212316+-0.0037648079828194307
SVM painting... ...
Data: DATASET_7
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_7
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7158506595126314
CV Accuracy: 0.715625960781373+/-0.010245805915243355
CASE_7_FINISHED ########################################################################
CASE_8#Dataframe:

             DATE   5M1  3Q_LAG
0       1967/10/2  0.14     0.0
1       1967/10/3  0.15     0.0
2       1967/10/4  0.16     0.0
3       1967/10/5  0.16     0.0
4       1967/10/6  0.18     0.0
...           ...   ...     ...
12775  2018/11/26  0.20     0.0
12776  2018/11/27  0.19     0.0
12777  2018/11/28  0.18     0.0
12778  2018/11/29  0.16     0.0
12779  2018/11/30  0.14     0.0

[12780 rows x 3 columns]
CASE_8#scores_LR: CV accuracy: 0.707 +/- 0.004
CASE_8#scores_SVM: CV accuracy: 0.680 +/- 0.003
CASE_8#scores_DT: CV accuracy: 0.716 +/- 0.008
CASE_8#LR Best Score: 0.7070198971607422
CASE_8#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_8#SVM Best Score: 0.6801922646993069
CASE_8#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_8#DT Best Score: 0.7155153141068634
CASE_8#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 2}
LR painting... ...
Data: DATASET_8
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.7070198971607422
CV Accuracy: 0.7065719320610401+-0.00403350506289349
SVM painting... ...
Data: DATASET_8
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6801922646993069
CV Accuracy: 0.6797449164510766+/-0.0033794792206945762
DT painting... ...
Data: DATASET_8
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 2}
Best Scores: 0.7155153141068634
CV Accuracy: 0.7159627810480796+/-0.007607929813260727
CASE_8_FINISHED ########################################################################
CASE_9#Dataframe:

             DATE   5M1  5Q_LAG
0       1967/10/2  0.14     0.0
1       1967/10/3  0.15     0.0
2       1967/10/4  0.16     0.0
3       1967/10/5  0.16     0.0
4       1967/10/6  0.18     0.0
...           ...   ...     ...
12775  2018/11/26  0.20     0.0
12776  2018/11/27  0.19     0.0
12777  2018/11/28  0.18     0.0
12778  2018/11/29  0.16     0.0
12779  2018/11/30  0.14     0.0

[12780 rows x 3 columns]
CASE_9#scores_LR: CV accuracy: 0.700 +/- 0.008
CASE_9#scores_SVM: CV accuracy: 0.672 +/- 0.003
CASE_9#scores_DT: CV accuracy: 0.716 +/- 0.012
CASE_9#LR Best Score: 0.7002012072434608
CASE_9#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_9#SVM Best Score: 0.6808629555108429
CASE_9#SVM Best Params: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_9#DT Best Score: 0.7146210596914822
CASE_9#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_9
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.7002012072434608
CV Accuracy: 0.7001990926474448+-0.00775744315809904
SVM painting... ...
Data: DATASET_9
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6808629555108429
CV Accuracy: 0.6724792221264045+/-0.0033570022250715512
DT painting... ...
Data: DATASET_9
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7146210596914822
CV Accuracy: 0.7159604064339545+/-0.011563873105127253
CASE_9_FINISHED ########################################################################
CASE_10#Dataframe:

             DATE  10M1*2  1Q_LAG
0       1967/10/2   -5.23     0.0
1       1967/10/3   -5.23     0.0
2       1967/10/4   -5.25     0.0
3       1967/10/5   -5.25     0.0
4       1967/10/6   -5.23     0.0
...           ...     ...     ...
12775  2018/11/26   -2.33     0.0
12776  2018/11/27   -2.34     0.0
12777  2018/11/28   -2.32     0.0
12778  2018/11/29   -2.35     0.0
12779  2018/11/30   -2.39     0.0

[12780 rows x 3 columns]
CASE_10#scores_LR: CV accuracy: 0.696 +/- 0.005
CASE_10#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_10#scores_DT: CV accuracy: 0.705 +/- 0.007
CASE_10#LR Best Score: 0.6958417169684775
CASE_10#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_10#SVM Best Score: 0.6787391012743126
CASE_10#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_10#DT Best Score: 0.7062374245472837
CASE_10#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_10
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.6958417169684775
CV Accuracy: 0.6957308187419544+-0.005012427428436953
SVM painting... ...
Data: DATASET_10
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_10
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7062374245472837
CV Accuracy: 0.7053436316598553+/-0.006856145013656197
CASE_10_FINISHED ########################################################################
CASE_11#Dataframe:

             DATE  10M1*2  3Q_LAG
0       1967/10/2   -5.23     0.0
1       1967/10/3   -5.23     0.0
2       1967/10/4   -5.25     0.0
3       1967/10/5   -5.25     0.0
4       1967/10/6   -5.23     0.0
...           ...     ...     ...
12775  2018/11/26   -2.33     0.0
12776  2018/11/27   -2.34     0.0
12777  2018/11/28   -2.32     0.0
12778  2018/11/29   -2.35     0.0
12779  2018/11/30   -2.39     0.0

[12780 rows x 3 columns]
CASE_11#scores_LR: CV accuracy: 0.693 +/- 0.005
CASE_11#scores_SVM: CV accuracy: 0.679 +/- 0.003
CASE_11#scores_DT: CV accuracy: 0.704 +/- 0.008
CASE_11#LR Best Score: 0.6920411357031075
CASE_11#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_11#SVM Best Score: 0.6797451374916164
CASE_11#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_11#DT Best Score: 0.7085848423876593
CASE_11#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_11
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6920411357031075
CV Accuracy: 0.6925993276092635+-0.005162471242180255
SVM painting... ...
Data: DATASET_11
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6797451374916164
CV Accuracy: 0.678850061864947+/-0.00291581942002238
DT painting... ...
Data: DATASET_11
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7085848423876593
CV Accuracy: 0.7040039743541675+/-0.008463440659986532
CASE_11_FINISHED ########################################################################
CASE_12#Dataframe:

             DATE  10M1*2  5Q_LAG
0       1967/10/2   -5.23     0.0
1       1967/10/3   -5.23     0.0
2       1967/10/4   -5.25     0.0
3       1967/10/5   -5.25     0.0
4       1967/10/6   -5.23     0.0
...           ...     ...     ...
12775  2018/11/26   -2.33     0.0
12776  2018/11/27   -2.34     0.0
12777  2018/11/28   -2.32     0.0
12778  2018/11/29   -2.35     0.0
12779  2018/11/30   -2.39     0.0

[12780 rows x 3 columns]
CASE_12#scores_LR: CV accuracy: 0.683 +/- 0.007
CASE_12#scores_SVM: CV accuracy: 0.680 +/- 0.001
CASE_12#scores_DT: CV accuracy: 0.696 +/- 0.008
CASE_12#LR Best Score: 0.6830985915492958
CASE_12#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_12#SVM Best Score: 0.6787391012743126
CASE_12#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_12#DT Best Score: 0.6956181533646323
CASE_12#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 6}
LR painting... ...
Data: DATASET_12
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6830985915492958
CV Accuracy: 0.6829867646507443+-0.006764467195305227
SVM painting... ...
Data: DATASET_12
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6796334345668829+/-0.0011035846042767683
DT painting... ...
Data: DATASET_12
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 6}
Best Scores: 0.6956181533646323
CV Accuracy: 0.6959535325509604+/-0.007802390349255551
CASE_12_FINISHED ########################################################################
CASE_13#Dataframe:

             DATE  10M3*2  1Q_LAG
0       1967/10/2   -5.53     0.0
1       1967/10/3   -5.51     0.0
2       1967/10/4   -5.55     0.0
3       1967/10/5   -5.51     0.0
4       1967/10/6   -5.51     0.0
...           ...     ...     ...
12775  2018/11/26   -2.65     0.0
12776  2018/11/27   -2.66     0.0
12777  2018/11/28   -2.62     0.0
12778  2018/11/29   -2.63     0.0
12779  2018/11/30   -2.65     0.0

[12780 rows x 3 columns]
CASE_13#scores_LR: CV accuracy: 0.692 +/- 0.003
CASE_13#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_13#scores_DT: CV accuracy: 0.692 +/- 0.006
CASE_13#LR Best Score: 0.6924882629107981
CASE_13#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_13#SVM Best Score: 0.6787391012743126
CASE_13#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_13#DT Best Score: 0.6941649899396378
CASE_13#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 5}
LR painting... ...
Data: DATASET_13
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6924882629107981
CV Accuracy: 0.6923761138814942+-0.0031048288537133995
SVM painting... ...
Data: DATASET_13
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_13
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 5}
Best Scores: 0.6941649899396378
CV Accuracy: 0.6923777386174746+/-0.005624530046341719
CASE_13_FINISHED ########################################################################
CASE_14#Dataframe:

             DATE  10M3*2  3Q_LAG
0       1967/10/2   -5.53     0.0
1       1967/10/3   -5.51     0.0
2       1967/10/4   -5.55     0.0
3       1967/10/5   -5.51     0.0
4       1967/10/6   -5.51     0.0
...           ...     ...     ...
12775  2018/11/26   -2.65     0.0
12776  2018/11/27   -2.66     0.0
12777  2018/11/28   -2.62     0.0
12778  2018/11/29   -2.63     0.0
12779  2018/11/30   -2.65     0.0

[12780 rows x 3 columns]
CASE_14#scores_LR: CV accuracy: 0.691 +/- 0.004
CASE_14#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_14#scores_DT: CV accuracy: 0.701 +/- 0.008
CASE_14#LR Best Score: 0.691594008495417
CASE_14#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_14#SVM Best Score: 0.6787391012743126
CASE_14#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_14#DT Best Score: 0.6993069528280796
CASE_14#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_14
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.691594008495417
CV Accuracy: 0.6912580455675953+-0.0037479017140052964
SVM painting... ...
Data: DATASET_14
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_14
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.6993069528280796
CV Accuracy: 0.700986714658868+/-0.008365465376422618
CASE_14_FINISHED ########################################################################
CASE_15#Dataframe:

             DATE  10M3*2  5Q_LAG
0       1967/10/2   -5.53     0.0
1       1967/10/3   -5.51     0.0
2       1967/10/4   -5.55     0.0
3       1967/10/5   -5.51     0.0
4       1967/10/6   -5.51     0.0
...           ...     ...     ...
12775  2018/11/26   -2.65     0.0
12776  2018/11/27   -2.66     0.0
12777  2018/11/28   -2.62     0.0
12778  2018/11/29   -2.63     0.0
12779  2018/11/30   -2.65     0.0

[12780 rows x 3 columns]
CASE_15#scores_LR: CV accuracy: 0.679 +/- 0.004
CASE_15#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_15#scores_DT: CV accuracy: 0.684 +/- 0.003
CASE_15#LR Best Score: 0.6794097920858484
CASE_15#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_15#SVM Best Score: 0.6787391012743126
CASE_15#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_15#DT Best Score: 0.6851106639839034
CASE_15#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_15
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6794097920858484
CV Accuracy: 0.6792978640970841+-0.004144179222057162
SVM painting... ...
Data: DATASET_15
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_15
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.6851106639839034
CV Accuracy: 0.6841044580255707+/-0.002979791004578981
CASE_15_FINISHED ########################################################################
CASE_16#Dataframe:

             DATE  5M1*2  1Q_LAG
0       1967/10/2  -5.15     0.0
1       1967/10/3  -5.14     0.0
2       1967/10/4  -5.15     0.0
3       1967/10/5  -5.15     0.0
4       1967/10/6  -5.12     0.0
...           ...    ...     ...
12775  2018/11/26  -2.50     0.0
12776  2018/11/27  -2.51     0.0
12777  2018/11/28  -2.51     0.0
12778  2018/11/29  -2.53     0.0
12779  2018/11/30  -2.56     0.0

[12780 rows x 3 columns]
CASE_16#scores_LR: CV accuracy: 0.696 +/- 0.005
CASE_16#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_16#scores_DT: CV accuracy: 0.702 +/- 0.007
CASE_16#LR Best Score: 0.6959534987704001
CASE_16#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_16#SVM Best Score: 0.6787391012743126
CASE_16#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_16#DT Best Score: 0.7018779342723005
CASE_16#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 5}
LR painting... ...
Data: DATASET_16
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.6959534987704001
CV Accuracy: 0.6958425505855299+-0.005390928758017434
SVM painting... ...
Data: DATASET_16
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_16
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 5}
Best Scores: 0.7018779342723005
CV Accuracy: 0.7022143901615988+/-0.007286229962252029
CASE_16_FINISHED ########################################################################
CASE_17#Dataframe:

             DATE  5M1*2  3Q_LAG
0       1967/10/2  -5.15     0.0
1       1967/10/3  -5.14     0.0
2       1967/10/4  -5.15     0.0
3       1967/10/5  -5.15     0.0
4       1967/10/6  -5.12     0.0
...           ...    ...     ...
12775  2018/11/26  -2.50     0.0
12776  2018/11/27  -2.51     0.0
12777  2018/11/28  -2.51     0.0
12778  2018/11/29  -2.53     0.0
12779  2018/11/30  -2.56     0.0

[12780 rows x 3 columns]
CASE_17#scores_LR: CV accuracy: 0.692 +/- 0.005
CASE_17#scores_SVM: CV accuracy: 0.678 +/- 0.004
CASE_17#scores_DT: CV accuracy: 0.708 +/- 0.010
CASE_17#LR Best Score: 0.6924882629107981
CASE_17#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_17#SVM Best Score: 0.6762799016320143
CASE_17#SVM Best Params: {'onevsrestclassifier__estimator__C': 1.0, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_17#DT Best Score: 0.7076905879722781
CASE_17#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_17
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6924882629107981
CV Accuracy: 0.692487595765688+-0.005359728720483418
SVM painting... ...
Data: DATASET_17
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6762799016320143
CV Accuracy: 0.6778451001712221+/-0.003970246611340616
DT painting... ...
Data: DATASET_17
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.7076905879722781
CV Accuracy: 0.7081415519978004+/-0.009942146956894085
CASE_17_FINISHED ########################################################################
CASE_18#Dataframe:

             DATE  5M1*2  5Q_LAG
0       1967/10/2  -5.15     0.0
1       1967/10/3  -5.14     0.0
2       1967/10/4  -5.15     0.0
3       1967/10/5  -5.15     0.0
4       1967/10/6  -5.12     0.0
...           ...    ...     ...
12775  2018/11/26  -2.50     0.0
12776  2018/11/27  -2.51     0.0
12777  2018/11/28  -2.51     0.0
12778  2018/11/29  -2.53     0.0
12779  2018/11/30  -2.56     0.0

[12780 rows x 3 columns]
CASE_18#scores_LR: CV accuracy: 0.684 +/- 0.007
CASE_18#scores_SVM: CV accuracy: 0.679 +/- 0.001
CASE_18#scores_DT: CV accuracy: 0.701 +/- 0.011
CASE_18#LR Best Score: 0.6832103733512185
CASE_18#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_18#SVM Best Score: 0.6805276101050749
CASE_18#SVM Best Params: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_18#DT Best Score: 0.7021014978761457
CASE_18#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 5}
LR painting... ...
Data: DATASET_18
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.6832103733512185
CV Accuracy: 0.6837691375151538+-0.007044831854899836
SVM painting... ...
Data: DATASET_18
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6805276101050749
CV Accuracy: 0.6789626685663579+/-0.0006451192571006593
DT painting... ...
Data: DATASET_18
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 5}
Best Scores: 0.7021014978761457
CV Accuracy: 0.7014301426018272+/-0.01117518020630007
CASE_18_FINISHED ########################################################################
CASE_19#Dataframe:

             DATE  10*2M1  1Q_LAG
0       1967/10/2    5.41     0.0
1       1967/10/3    5.41     0.0
2       1967/10/4    5.43     0.0
3       1967/10/5    5.43     0.0
4       1967/10/6    5.44     0.0
...           ...     ...     ...
12775  2018/11/26    3.44     0.0
12776  2018/11/27    3.42     0.0
12777  2018/11/28    3.43     0.0
12778  2018/11/29    3.37     0.0
12779  2018/11/30    3.32     0.0

[12780 rows x 3 columns]
CASE_19#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_19#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_19#scores_DT: CV accuracy: 0.684 +/- 0.003
CASE_19#LR Best Score: 0.6787391012743126
CASE_19#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_19#SVM Best Score: 0.6787391012743126
CASE_19#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_19#DT Best Score: 0.6841046277665996
CASE_19#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 2}
LR painting... ...
Data: DATASET_19
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_19
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_19
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 2}
Best Scores: 0.6841046277665996
CV Accuracy: 0.6843281716721032+/-0.003243946633897342
CASE_19_FINISHED ########################################################################
CASE_20#Dataframe:

             DATE  10*2M1  3Q_LAG
0       1967/10/2    5.41     0.0
1       1967/10/3    5.41     0.0
2       1967/10/4    5.43     0.0
3       1967/10/5    5.43     0.0
4       1967/10/6    5.44     0.0
...           ...     ...     ...
12775  2018/11/26    3.44     0.0
12776  2018/11/27    3.42     0.0
12777  2018/11/28    3.43     0.0
12778  2018/11/29    3.37     0.0
12779  2018/11/30    3.32     0.0

[12780 rows x 3 columns]
CASE_20#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_20#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_20#scores_DT: CV accuracy: 0.681 +/- 0.002
CASE_20#LR Best Score: 0.6787391012743126
CASE_20#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_20#SVM Best Score: 0.6787391012743126
CASE_20#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_20#DT Best Score: 0.6808629555108429
CASE_20#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 2}
LR painting... ...
Data: DATASET_20
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_20
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_20
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 2}
Best Scores: 0.6808629555108429
CV Accuracy: 0.681421519003162+/-0.0017863200610324682
CASE_20_FINISHED ########################################################################
CASE_21#Dataframe:

             DATE  10*2M1  5Q_LAG
0       1967/10/2    5.41     0.0
1       1967/10/3    5.41     0.0
2       1967/10/4    5.43     0.0
3       1967/10/5    5.43     0.0
4       1967/10/6    5.44     0.0
...           ...     ...     ...
12775  2018/11/26    3.44     0.0
12776  2018/11/27    3.42     0.0
12777  2018/11/28    3.43     0.0
12778  2018/11/29    3.37     0.0
12779  2018/11/30    3.32     0.0

[12780 rows x 3 columns]
CASE_21#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_21#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_21#scores_DT: CV accuracy: 0.679 +/- 0.000
CASE_21#LR Best Score: 0.6787391012743126
CASE_21#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_21#SVM Best Score: 0.6787391012743126
CASE_21#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_21#DT Best Score: 0.6787391012743126
CASE_21#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 1}
LR painting... ...
Data: DATASET_21
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_21
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_21
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
CASE_21_FINISHED ########################################################################
CASE_22#Dataframe:

             DATE  10*2M3  1Q_LAG
0       1967/10/2    5.26     0.0
1       1967/10/3    5.27     0.0
2       1967/10/4    5.28     0.0
3       1967/10/5    5.30     0.0
4       1967/10/6    5.30     0.0
...           ...     ...     ...
12775  2018/11/26    3.28     0.0
12776  2018/11/27    3.26     0.0
12777  2018/11/28    3.28     0.0
12778  2018/11/29    3.23     0.0
12779  2018/11/30    3.19     0.0

[12780 rows x 3 columns]
CASE_22#scores_LR: CV accuracy: 0.680 +/- 0.001
CASE_22#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_22#scores_DT: CV accuracy: 0.689 +/- 0.004
CASE_22#LR Best Score: 0.6803040465012296
CASE_22#LR Best Params: {'onevsrestclassifier__estimator__C': 10}
CASE_22#SVM Best Score: 0.6787391012743126
CASE_22#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_22#DT Best Score: 0.6896937178627319
CASE_22#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 3}
LR painting... ...
Data: DATASET_22
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 10}
Best Scores: 0.6803040465012296
CV Accuracy: 0.6798575231524877+-0.001460139626436393
SVM painting... ...
Data: DATASET_22
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_22
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 3}
Best Scores: 0.6896937178627319
CV Accuracy: 0.6894708359891517+/-0.0041511800658854195
CASE_22_FINISHED ########################################################################
CASE_23#Dataframe:

             DATE  10*2M3  3Q_LAG
0       1967/10/2    5.26     0.0
1       1967/10/3    5.27     0.0
2       1967/10/4    5.28     0.0
3       1967/10/5    5.30     0.0
4       1967/10/6    5.30     0.0
...           ...     ...     ...
12775  2018/11/26    3.28     0.0
12776  2018/11/27    3.26     0.0
12777  2018/11/28    3.28     0.0
12778  2018/11/29    3.23     0.0
12779  2018/11/30    3.19     0.0

[12780 rows x 3 columns]
CASE_23#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_23#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_23#scores_DT: CV accuracy: 0.686 +/- 0.004
CASE_23#LR Best Score: 0.6787391012743126
CASE_23#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_23#SVM Best Score: 0.6787391012743126
CASE_23#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_23#DT Best Score: 0.6879052090319696
CASE_23#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 3}
LR painting... ...
Data: DATASET_23
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_23
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_23
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 3}
Best Scores: 0.6879052090319696
CV Accuracy: 0.686228487870721+/-0.00402684746068884
CASE_23_FINISHED ########################################################################
CASE_24#Dataframe:

             DATE  10*2M3  5Q_LAG
0       1967/10/2    5.26     0.0
1       1967/10/3    5.27     0.0
2       1967/10/4    5.28     0.0
3       1967/10/5    5.30     0.0
4       1967/10/6    5.30     0.0
...           ...     ...     ...
12775  2018/11/26    3.28     0.0
12776  2018/11/27    3.26     0.0
12777  2018/11/28    3.28     0.0
12778  2018/11/29    3.23     0.0
12779  2018/11/30    3.19     0.0

[12780 rows x 3 columns]
CASE_24#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_24#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_24#scores_DT: CV accuracy: 0.679 +/- 0.000
CASE_24#LR Best Score: 0.6787391012743126
CASE_24#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_24#SVM Best Score: 0.6787391012743126
CASE_24#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_24#DT Best Score: 0.6789626648781579
CASE_24#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 2}
LR painting... ...
Data: DATASET_24
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_24
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_24
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 2}
Best Scores: 0.6789626648781579
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
CASE_24_FINISHED ########################################################################
CASE_25#Dataframe:

             DATE  5*2M1  1Q_LAG
0       1967/10/2   5.57     0.0
1       1967/10/3   5.59     0.0
2       1967/10/4   5.63     0.0
3       1967/10/5   5.63     0.0
4       1967/10/6   5.66     0.0
...           ...    ...     ...
12775  2018/11/26   3.10     0.0
12776  2018/11/27   3.08     0.0
12777  2018/11/28   3.05     0.0
12778  2018/11/29   3.01     0.0
12779  2018/11/30   2.98     0.0

[12780 rows x 3 columns]
CASE_25#scores_LR: CV accuracy: 0.680 +/- 0.001
CASE_25#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_25#scores_DT: CV accuracy: 0.690 +/- 0.005
CASE_25#LR Best Score: 0.6799687010954616
CASE_25#LR Best Params: {'onevsrestclassifier__estimator__C': 1.0}
CASE_25#SVM Best Score: 0.6787391012743126
CASE_25#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_25#DT Best Score: 0.6901408450704225
CASE_25#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 3}
LR painting... ...
Data: DATASET_25
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 1.0}
Best Scores: 0.6799687010954616
CV Accuracy: 0.6798570232337245+-0.0009757450291400669
SVM painting... ...
Data: DATASET_25
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_25
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 3}
Best Scores: 0.6901408450704225
CV Accuracy: 0.6900291202679564+/-0.005042681642353354
CASE_25_FINISHED ########################################################################
CASE_26#Dataframe:

             DATE  5*2M1  3Q_LAG
0       1967/10/2   5.57     0.0
1       1967/10/3   5.59     0.0
2       1967/10/4   5.63     0.0
3       1967/10/5   5.63     0.0
4       1967/10/6   5.66     0.0
...           ...    ...     ...
12775  2018/11/26   3.10     0.0
12776  2018/11/27   3.08     0.0
12777  2018/11/28   3.05     0.0
12778  2018/11/29   3.01     0.0
12779  2018/11/30   2.98     0.0

[12780 rows x 3 columns]
CASE_26#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_26#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_26#scores_DT: CV accuracy: 0.684 +/- 0.003
CASE_26#LR Best Score: 0.6787391012743126
CASE_26#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_26#SVM Best Score: 0.6787391012743126
CASE_26#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_26#DT Best Score: 0.6841046277665996
CASE_26#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 2}
LR painting... ...
Data: DATASET_26
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_26
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_26
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 2}
Best Scores: 0.6841046277665996
CV Accuracy: 0.6839934760601402+/-0.0025170206039476215
CASE_26_FINISHED ########################################################################
CASE_27#Dataframe:

             DATE  5*2M1  5Q_LAG
0       1967/10/2   5.57     0.0
1       1967/10/3   5.59     0.0
2       1967/10/4   5.63     0.0
3       1967/10/5   5.63     0.0
4       1967/10/6   5.66     0.0
...           ...    ...     ...
12775  2018/11/26   3.10     0.0
12776  2018/11/27   3.08     0.0
12777  2018/11/28   3.05     0.0
12778  2018/11/29   3.01     0.0
12779  2018/11/30   2.98     0.0

[12780 rows x 3 columns]
CASE_27#scores_LR: CV accuracy: 0.679 +/- 0.000
CASE_27#scores_SVM: CV accuracy: 0.679 +/- 0.000
CASE_27#scores_DT: CV accuracy: 0.679 +/- 0.000
CASE_27#LR Best Score: 0.6787391012743126
CASE_27#LR Best Params: {'onevsrestclassifier__estimator__C': 0.1}
CASE_27#SVM Best Score: 0.6787391012743126
CASE_27#SVM Best Params: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
CASE_27#DT Best Score: 0.6788508830762352
CASE_27#DT Best Params: {'onevsrestclassifier__estimator__max_depth': 4}
LR painting... ...
Data: DATASET_27
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+-0.0004497189559481774
SVM painting... ...
Data: DATASET_27
Model:LR
Best Paras: {'onevsrestclassifier__estimator__C': 0.1, 'onevsrestclassifier__estimator__kernel': 'linear'}
Best Scores: 0.6787391012743126
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
DT painting... ...
Data: DATASET_27
Model:LR
Best Paras: {'onevsrestclassifier__estimator__max_depth': 4}
Best Scores: 0.6788508830762352
CV Accuracy: 0.6787392048792071+/-0.0004497189559481774
CASE_27_FINISHED ########################################################################
```

