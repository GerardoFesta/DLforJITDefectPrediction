# DLforJITDefectPrediction
Using deep learning to approach the Fine Grained Just in Time defect prediction in software engineering.
## Just In Time Defect Prediction
Fine Grained Just In Time defect prediction is a branch of software engineering involving the identification of likely defective files within new commits pushed by developers onto a shared repository, based on SE metrics such as Commit Count, various Lines counts, and much more that you can check out in this [paper](https://www.sciencedirect.com/science/article/pii/S0164121218302656) Table 2.

## Data
Dataset and PaperResults come from this [article](https://www.researchgate.net/publication/359109059_Regularity_or_Anomaly_On_The_Use_of_Anomaly_Detection_for_Fine-Grained_Just-in-Time_Defect_Prediction).

The context involves the commits of 32 open-source projects for a total of 193'000 files involved (which are the lines of the dataset), 37% of which is defective, exploited from the [Technical Debt Dataset](https://arxiv.org/ftp/arxiv/papers/1908/1908.00827.pdf).

## Model
I realized a MLP to compete with the machine learning approach and anomaly detection approach used in the first two papers I cited.
The results are average, the MLP does better than others regarding certain metrics, but worse regarding others. For the full discussion, please check the full [report](https://github.com/GerardoFesta/DLforJITDefectPrediction/blob/main/Deep%20Learning%20per%20la%20JIT%20Defect%20Prediction.pdf)
