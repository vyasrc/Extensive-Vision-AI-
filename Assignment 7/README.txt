		f,p,s	Input 	Output	RF	Jump
Conv		7,3,2	224	112	7	1
MaxPool		3,1,2	112	56	11	2
Conv		3,1,1	56	56	19	4
MaxPool		3,1,2	56	28	27	4
Inception Conv	3,1,1	28	28	43	8
Inception Conv	3,1,1	28	28	59	8
MaxPool		3,1,2	28	14	75	8
Inception Conv	3,1,1	14	14	107	16
Inception Conv	3,1,1	14	14	139	16
Inception Conv	3,1,1	14	14	171	16
Inception Conv	3,1,1	14	14	203	16
Inception Conv	3,1,1	14	14	235	16
MaxPool		3,1,2	14	7	267	16
Inception Conv	3,1,1	7	7	331	32
Inception Conv	3,1,1	7	7	395	32
AvgPool		7,0,1	7	1	587	32
