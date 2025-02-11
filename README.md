# SliceNet: Federated Learning for Network Slicing  

SliceNet is a **Federated Learning (FL) framework** designed to optimize **5G network slicing**.  
It classifies network slices into three categories:  
- **eMBB (Enhanced Mobile Broadband)**  
- **mMTC (Massive Machine-Type Communication)**  
- **URLLC (Ultra-Reliable Low Latency Communication)**  

using **bandwidth and dynamic network parameters** to improve 5G resource allocation.  

---

## 🚀 **Project Overview**  

✔ Implements **Federated Learning (FL)** using the **Flower framework**.  
✔ Uses an **RNN-LSTM** deep learning model for slice classification.  
✔ Trained on a **real-world multi-class network slicing dataset**.  
✔ Achieves **97.78% accuracy**, improving resource efficiency in 5G.  

---

## 📂 **Dataset**  

The dataset contains network parameters affecting slicing decisions.  
📌 **Download Dataset**: [Deep-Slice Dataset](https://www.kaggle.com/datasets/dotslash04/deep-slice)  

**Key Features:**  
- Traffic Load  
- Bandwidth Allocation  
- Network Congestion Level  
- Delay Constraints  
- Reliability Requirements  

### 🔍 **Preprocessing Steps:**  
✔ Encoding categorical variables  
✔ Min-max normalization of features  
✔ Adding **Gaussian noise** for robustness  
✔ Reshaping data for RNN input  

---

## 🛠 **Tech Stack**  

- **Programming:** Python  
- **Frameworks:** PyTorch, Flower (FL)  
- **Machine Learning:** RNN, LSTM, Scikit-Learn  
- **Other Tools:** NumPy, Pandas, Matplotlib  

---

## ⚙️ **Installation & Setup**  

Clone the repository and install dependencies:  
```bash
git clone https://github.com/YourGitHubUsername/SliceNet.git
cd SliceNet
pip install -r requirements.txt
