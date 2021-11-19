# webscrapping_ilincs
This code will take in list of drugs aimed at targetting Prostate Cancer disease and output the rank ordered list of them based on LINCS(http://www.ilincs.org/ilincs/) gene signature reversal. It does so by automatically extracting drug gene signatures from the iLINCS website and computing the discordance wrt to the disease gene signature. The disease gene signature was obtained through Differential Gene Expression.
Inputs:
1. Drug list
2. Differential Gene expression of Prostate Cancer disease
Outputs:
1. Rank ordered list of drugs based on gene signature reversal
