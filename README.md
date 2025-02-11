# SliceNet: Federated Learning for Network Slicing  

SliceNet is a Federated Learning (FL) framework designed to optimize network slicing in 5G environments.  
It classifies network slices into categories like **eMBB (Enhanced Mobile Broadband), mMTC (Massive Machine-Type Communication), and URLLC (Ultra-Reliable Low Latency Communication)** based on bandwidth and dynamic network parameters.  

## 🚀 **Project Overview**  
- Implements **Federated Learning (FL)** using the Flower framework.  
- Uses an **RNN-based model with LSTM layers** for efficient classification.  
- Trained on a real-world **multi-class network slicing dataset**.  
- Achieves **97.78% accuracy** in slice classification.  

## 📂 **Dataset**  
The dataset contains various network parameters that influence the slicing mechanism. These parameters are preprocessed and normalized before training.

## 🛠 **Tech Stack**  
- **Programming:** Python  
- **Frameworks:** PyTorch, Flower (FL)  
- **Machine Learning:** RNN, LSTM, Scikit-Learn  
- **Other Tools:** NumPy, Pandas, Matplotlib  

## ⚙️ **Installation & Setup**  
Clone the repository:  
```bash
git clone https://github.com/YourGitHubUsername/SliceNet.git
cd SliceNet
