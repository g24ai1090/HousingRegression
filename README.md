# HousingRegression

---

## 📁 Project Structure

HousingRegression/
│
├── .github/
│ └── workflows/
│ └── ci.yml
│
├── utils.py
├── regression.py
├── requirements.txt
├── README.md


## ⚙️ How to Run

### 1️⃣ Create & Activate Environment
```bash
conda create -n housing_reg python=3.10 -y
conda activate housing_reg

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Script
python regression.py

Git Branch Workflow
reg_branch (Basic Models)

git checkout -b reg_branch
git add --all
git commit -m "Add regression models"
git push origin reg_branch

git checkout main
git merge reg_branch
git push origin main

hyper_branch (Hyperparameter Tuning)

git checkout -b hyper_branch
git add --all
git commit -m "Add hyperparameter tuning"
git push origin hyper_branch

git checkout main
git merge hyper_branch
git push origin main