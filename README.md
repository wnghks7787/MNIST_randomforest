# 개요
> [!note] 참고사항
>이 프로젝트는 Obsidian 개인 노트와 github에 모두 올라갈 내용입니다.
>기본적인 노트의 작성은 Obsidian의 포맷을 따르지만, github에서 100% 호환되지 않을 수 있기에, 해당 분을 최대한 고려하여 github에는 수정된 내용이 들어갈 수 있습니다.
>하지만, 완벽하게 모든 내용을 체크하지 못할 수 있으니, 이 점 양해 부탁드립니다.

## 기술 스택

![Google Colab|146](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white) ![Weights & Biases](https://img.shields.io/badge/weightsandbiases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=white) ![Keras](https://img.shields.io/badge/keras-D00000?style=for-the-badge&logo=keras&logoColor=white)


# Colab과 Github 연결
가장 먼저 할 일은 Colab과 Github를 연결하는 일입니다.


### .gitignore 파일
gitignore 파일은 Google Gemini의 도움을 받아 제작하였습니다.
옵시디언 부분은 개인적으로 관리하는 옵시디언과의 혹시 모를 충돌 때문에 추가되었습니다.

```.gitignore
# --- Python & Jupyter ---
__pycache__/
*.py[cod]
*$py.class
.ipynb_checkpoints
.virtualenvs/
venv/
ENV/

# --- Colab & OS ---
.config/
sample_data/
.DS_Store

# --- Weights & Biases (WandB) ---
wandb/

# --- Data & Models ---
# 데이터셋과 모델 가중치는 용량이 크므로 관리하지 않음
data/
*.pth
*.pt
*.pkl
*.joblib

# --- Obsidian & Docs ---
# 옵시디언 사용에 의해 혹시 모를 충돌 방지
.obsidain/
```
