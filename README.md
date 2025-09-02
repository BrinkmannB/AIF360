# 🔎 AIF360 Fairness Check Project

[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![IBM AIF360](https://img.shields.io/badge/AI%20Fairness-360-green.svg)](https://aif360.mybluemix.net/)
[![GitHub last commit](https://img.shields.io/github/last-commit/BrinkmannB/AIF360)](https://github.com/BrinkmannB/AIF360)
[![GitHub repo size](https://img.shields.io/github/repo-size/BrinkmannB/AIF360)](https://github.com/BrinkmannB/AIF360)

---

## 📌 Over dit project
Dit project onderzoekt **bias in AI** met behulp van IBM’s **AI Fairness 360 (AIF360)**.  
We gebruiken de bekende *Adult dataset* (inkomensdata) en analyseren de fairness tussen mannen en vrouwen.  

---

## ⚙️ Functionaliteit
- ✅ Dataset laden via OpenML  
- ✅ Bias detecteren met *Disparate Impact*  
- ✅ Bias mitigeren met *Reweighing*  
- ✅ Interpretatie in gewone taal  

---

## 📊 Voorbeeld-output
```
✅ Dataset geladen: 48842 samples
Disparate Impact vóór mitigatie: 0.63
Disparate Impact ná mitigatie: 0.98
```

👉 Interpretatie: de dataset discrimineerde duidelijk tegen vrouwen (0.63 < 0.8).  
Na *Reweighing* is de bias sterk verminderd: de waarde schuift naar ~1.0 → veel eerlijker verdeeld.  

---

## 📂 Projectstructuur
```
AIF360/
├── notebooks/
│   └── AIF360_Fairness_Check_With_Reweighing_And_Interpretation.ipynb
├── docs/
│   ├── Python_Gegevenstypen_CheatSheet.pdf
│   └── AIF360_Cheat_Sheet_Mac.pdf
├── requirements.txt
├── README.md
└── .venv/
```

---

## 🚀 Installatie & gebruik

### 1. Repo clonen
```bash
git clone https://github.com/BrinkmannB/AIF360.git
cd AIF360
```

### 2. Virtuele omgeving maken
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Dependencies installeren
```bash
pip install -r requirements.txt
```

### 4. Start Jupyter
```bash
jupyter notebook
```

Open het notebook in `notebooks/` en klik op **Run All**.  

---

## 📖 Meer weten?
- [AI Fairness 360 (IBM)](https://aif360.mybluemix.net/)  
- [Adult Dataset (OpenML)](https://www.openml.org/d/1590)  

---

👨‍💻 **Auteur:** Bas Brinkmann  
*AI Ethiek Consultant in opleiding | Extern Vertrouwenspersoon*  
