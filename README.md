Article ：Contextual cueing effect under rapid presentation（Author：Siyi Chen, Xiaowei Xie, Xuelian Zang）

The meaning of parameters in the program：
RT   (reaction time)
Crr  (correct response) 
NB   (number of block)
NE   (number of epochs, every 5 blocks were combined into one epoch)
nSub (number of subjects)
New  (is new display? 1=new; 0=old)
TLoc (target location)
TDir (target direction)
NT   (number of trials)
RP   (ResPonse)
nExp (number of experiments)

"dataProcessAll.m" is the main function of experimental data analysis. 
If you want to get the analysis result of error rates, you can enter sub function "ErrorProcess,m"; 
If you want to get the analysis result of reaction time, you can enter sub function "dataProcessValid.m"; 
If you want to get the result of recognition stage, you can run sub function "dataProcessRec.m".
The result includes the data format that can be used for SPSS analysis and the corresponding result pictures. The specific information is also explained in each function.

Programmer: Xuelian Zang, Xiaowei Xie
Updata data: 07/28/2020
If you have any questions, please contact: zangxuelian@gmail.com or lianlian81821@126.com
If you need to use the data and results in this paper, please indicate the source
