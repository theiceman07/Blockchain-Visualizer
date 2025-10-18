# 🧱 Blockchain Visualizer (Google Colab)

An interactive **blockchain simulation** built entirely in **Google Colab**.  
It visually explains how blockchains work — mining, validation, hashing, Merkle trees, and more.

---

## 🚀 Features

✅ Proof-of-Work mining  
✅ Adjustable difficulty  
✅ Chain validation & tamper detection  
✅ Balances + mining rewards  
✅ Transaction fees  
✅ ECDSA digital signatures  
✅ Merkle tree generation & inclusion proofs  
✅ Interactive widgets for transactions & mining  
✅ Graph visualization using NetworkX  

---

## ▶️ Run it instantly on Google Colab
Click the badge below to open and run this notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theiceman07/Blockchain-Visualizer/blob/main/Blockchain_Visualizer_clean.ipynb)

---

## 🧠 Overview
This project is **for learning purposes** — it shows how a blockchain functions **internally** (no external network, no crypto).  
It covers:
- Block structure and linkage  
- Proof of Work (PoW)  
- Merkle root calculation  
- Transaction management  
- Validation and tamper detection  

All using **pure Python** and **free Google Colab** tools.

---

## 🧩 How to Use
1. Open the notebook in Colab.  
2. Run each cell (Shift + Enter).  
3. Use the on-screen buttons to:
   - Add transactions  
   - Mine blocks  
   - Validate the chain  
4. Try tampering a block to see the validation fail!  

---

## ⚙️ Technologies Used
| Purpose | Library |
|----------|----------|
| Notebook & UI | Google Colab, ipywidgets |
| Visualization | NetworkX, Matplotlib |
| Crypto | hashlib, ecdsa |
| Logic | Python dataclasses, JSON |

---

## 🧰 Installation (Optional, for local Jupyter)
If you want to run it locally:
```bash
pip install -r requirements.txt
jupyter notebook
📜 License

Licensed under the MIT License — you can use or modify freely.

👨‍💻 Author

Arjun (theiceman07)
Information Technology student
Interested in cybersecurity, blockchain, and AI.

⚠️ Educational Only — This is a blockchain simulation, not a real cryptocurrency network.


---

### ✅ What this does
This makes your GitHub page show:
- A **title**, **description**, and **Colab launch badge**  
- All your **features and tech stack**  
- Clear instructions for others  
- Your **author info**

---

### 🧾 STEP 2: Add 3 small files

#### 1️⃣ requirements.txt
Click **Add file → Create new file**  
File name: `requirements.txt`

Paste:


ipywidgets
networkx
ecdsa
matplotlib


Then **Commit changes**.

---

#### 2️⃣ LICENSE
Click **Add file → Create new file**  
File name: `LICENSE`

Paste:


MIT License

Copyright (c) 2025 Arjun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.


Commit.

---

#### 3️⃣ .gitignore
Click **Add file → Create new file**  
File name: `.gitignore`

Paste:


.ipynb_checkpoints/
pycache/
*.pyc
*.DS_Store


Commit.

---

### 🖼️ (Optional STEP 3) Add screenshots

If you took screenshots or graphs:
1. Click **Add file → Upload files**
2. Upload your images (e.g., `graph.png`, `demo.gif`)  
3. Create a folder called `assets` if you want it organized.
4. In your README, add:
   ```markdown
   ![Demo](assets/graph.png)
