git add README.md
git commit -m "Rewrite README with badges and quickstart cheat sheet"
git push
# AIF360 Starter – Fairness in AI

![Python](https://img.shields.io/badge/python-3.11-blue)
![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange)
![AIF360](https://img.shields.io/badge/IBM-AIF360-success)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

Dit is mijn leer- en oefenrepo waarin ik werk met **[AI Fairness 360 (AIF360)](https://aif360.mybluemix.net/)**, een open-source toolkit van IBM om bias in AI-modellen te meten en te mitigeren.  
Doel: mijn kennis en vaardigheden als **AI Ethiek Consultant in wording** praktisch ontwikkelen en zichtbaar maken.

---

## 🚀 Installatie

Clone de repo en maak een virtual environment:

```bash
git clone git@github.com:BrinkmannB/AIF360.git
cd AIF360

python3 -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\Activate.ps1   # Windows (PowerShell)

pip install --upgrade pip
pip install aif360 numpy pandas scikit-learn jupyter matplotlib

