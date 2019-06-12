	f,p,s	Input 	Output	RF	Jump
Conv	7,3,2	224	112	7	1
MaxPool	3,1,2	112	56	11	2
Conv	3,1,1	56	56	19	4
MaxPool	3,1,2	56	28	27	4
MaxPool	3,1,2	28	14	43	8
MaxPool	3,1,2	14	7	75	16
AvgPool	7,0,1	7	1	267	32
