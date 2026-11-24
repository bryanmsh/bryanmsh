# 👨‍💻 @bryanmsh

CS at **UMass Amherst**

💼 [LinkedIn](https://linkedin.com/in/bmhuang) • 📧 [Email](mailto:bryanmsh@gmail.com) • 📍 Amherst, MA

---

## Featured Projects

### [Miraai](https://github.com/bryanmsh/miraai)

Adapts picture books for children with cortical visual impairment. Teachers review subjects extracted from the original artwork and approve each child's personalized pages.

I co-trained a 7.8M-parameter PyTorch U-Net that reached **0.897 mean IoU** versus SAM 2.1's 0.906 at **about 5× the GPU speed**. In a cascade benchmark, it handled **67% of cut-outs** at **0.919 mean IoU agreement with SAM 2.1** on accepted masks. I also set up Docker and Caddy deployment on Vultr, auto-deploy, and branch protection.

**Built with:** Python, PyTorch, FastAPI, React, TypeScript, Docker

**[Watch the demo](https://www.youtube.com/watch?v=5-VnosZ5yUA)**

### [neural-net-from-scratch](https://github.com/bryanmsh/neural-net-from-scratch)

A modular feedforward neural network and analytical backpropagation engine built from scratch with pure NumPy, without ML frameworks. Achieved **~94.2% test accuracy on MNIST**.

At the same learning rate, SGD reached **90.95% average test accuracy** after five epochs versus **9.92%** for full-batch gradient descent.

**Built with:** Python, NumPy, Matplotlib

### [CareLeap](https://github.com/bryanmsh/CareLeap)

A Hackachusetts 2026 project that helps patients plan round-trip clinic visits and helps clinics assess whether changing appointment times improves transit access.

I extended RAPTOR routing across **PVTA and FRTA**, implemented Census-based **90% confidence intervals** for access estimates, and mapped **86 rural block groups** where an estimated **3,270 adults without cars** had modeled access only through assisted rides. I also integrated clinic and ride data through MCP and FastAPI, added Hypothesis tests, and ran the official GTFS validator.

**Built with:** Python, NumPy, FastAPI, React, TypeScript, MapLibre, MCP

**[Live demo](https://careleap-production.up.railway.app/)** · **[API demo](https://careleap-production.up.railway.app/docs)**

### [titanic-survival-classifier](https://github.com/bryanmsh/titanic-survival-classifier)

An end-to-end machine learning pipeline with custom transformers, preprocessing within stratified 5-fold cross-validation, gradient boosting optimization, and permutation importance diagnostics.

Achieved **~89.4% cross-validation ROC-AUC** and **~83.4% held-out ROC-AUC**.

**Built with:** Python, scikit-learn, pandas, NumPy

---

## 🛠 Tech Stack

**Languages**  
[![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)](https://en.cppreference.com/w/c)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)](https://java.com)
[![AutoHotkey](https://img.shields.io/badge/AutoHotkey-334455?style=flat-square&logo=autohotkey&logoColor=white)](https://autohotkey.com)

**Machine Learning & Applications**  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io)

**Developer Tools & Deployment**  
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://kernel.org)
[![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)](https://microsoft.com)
[![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)](https://railway.com)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com)

**Engineering & Simulation**  
[![SOLIDWORKS](https://img.shields.io/badge/SOLIDWORKS-FEA_%26_CAD-red?style=flat-square)](https://solidworks.com)
[![AutoCAD](https://img.shields.io/badge/AutoCAD-2D_Drafting-E51027?style=flat-square&logo=autodesk)](https://autodesk.com)
[![Autodesk Revit](https://img.shields.io/badge/Revit-BIM_Modeling-0696D7?style=flat-square&logo=autodesk)](https://autodesk.com)
[![Fusion 360](https://img.shields.io/badge/Fusion_360-CAD%2FCAM-orange?style=flat-square&logo=autodesk)](https://autodesk.com)
