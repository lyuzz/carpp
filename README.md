# Consultant Assignment and Routing Problem with Priority (CARPP) 

The CARPP problem aims to simultaneously assign consultants to clients and determine the traveling routes. The features of the problem are listed as follows. The consulting activities must be performed face-to-face at the client site. Therefore, consultants travel to almost all client assignments to fulfill their jobs. The objective is to minimize the incurred airfares and the consultants’ wages. Consultants are proficient in different skills and they can only fill demands requiring the relevant skill. The skills cannot be easily replicated or cross-trained. In addition, priority requirement has to be matched before assigning consultants to clients. To avoid dissatisfaction from consultants, the maximum number of flying trips should not exceed four for each consultant per week. The CARPP problem does not consider time window because the specific working time is determined by consultants and clients.

## data
In the "data" folder, there are 100 sythetic instances. The sythetic instances are randomly generated based on the real-life data. How the synthetic data are generated can be found in our paper named consultant assignment and routing problem with priority. The 100 instances are divided into three categraies, i.e. "S", "M", and "L" based on the number of clusters. The real-life data is hold to protect the firm's privacy. 

## solution
MILP formulation, RMIP algorithm and MNSA algorithm have been used to solve the CARPP problem. The results can be found in the "solutions" folder.

## formulation scale
The number of binary variables, integer variables, and constraints for each instance is listed in the WORD file "countVars.docx".  

## paper URL
(https://www.sciencedirect.com/science/article/pii/S0360835220306069)
