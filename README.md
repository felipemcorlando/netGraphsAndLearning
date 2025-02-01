# 📊 Network Science and Graph Learning – Facebook100 Analysis

## 📌 Overview
This project explores network science and graph learning techniques using the **Facebook100 dataset**. The dataset contains friendship networks from U.S. universities in 2005, enabling the study of **social structures, link prediction, assortativity, and community detection**.

We implement various **graph-based algorithms**, including:
- **Social Network Analysis (SNA)**
- **Link Prediction Algorithms** (Common Neighbors, Jaccard Index, Adamic/Adar)
- **Label Propagation for Missing Attribute Recovery**
- **Community Detection (Louvain Method)**
- **Modularity and Stability Analysis**

## 📂 Repository Structure
```
📦 Network-Analysis-FB100
 ┣ 📜 README.md
 ┣ 📜 Homework_Network_Analysis.pdf
 ┣ 📜 requirements.txt
 ┣ 📜 homework.ipynb
 ┗ 📜 fb100/data/*.gml  # Facebook100 dataset (download from pdf)
```

## 🚀 Installation
1️⃣ Clone the repository:
```bash
git clone https://github.com/felipemcorlando/netGraphsAndLearning.git
cd Network-Analysis-FB100
```

2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

3️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook homework.ipynb
```

## 📈 Results & Findings
### **1️⃣ Link Prediction**
We tested **Common Neighbors, Jaccard Index, and Adamic/Adar** to predict missing edges. The results showed that **Common Neighbors** performed best in most cases.

### **2️⃣ Label Propagation**
We evaluated the ability to recover missing labels (**dorm, major, and gender**). The algorithm performed well for **dorm affiliation**, but struggled with **major assignment**.

### **3️⃣ Community Detection**
Using **Louvain Modularity**, we identified student groups based on dorm and major. Results showed that **dorm-based clustering** was more structured than **major-based clustering**.

### **4️⃣ Stability Analysis**
We performed multiple runs of the Louvain method and measured the variability in **modularity scores and Adjusted Rand Index (ARI)** across different universities.

## 📚 References
- Facebook100 Dataset: [Traud et al., 2011](https://arxiv.org/abs/0809.0690)
- Community Detection: [Blondel et al., 2008](https://arxiv.org/abs/0803.0476)
- Label Propagation: [Bhagat et al., 2011](https://arxiv.org/abs/1101.3291)
- Link Prediction: [Liben-Nowell & Kleinberg, 2003](https://www.cs.cornell.edu/home/kleinber/link-pred.pdf)

## 🤝 Contributing
Feel free to open issues and submit pull requests!

---
📌 **Author:** Felipe Orlando
📅 **Date:** January 2025  
🔗 **GitHub:** [felipemcorlando](https://github.com/felipemcorlando)  

