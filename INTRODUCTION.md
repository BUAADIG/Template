
# 📦 项目代码与数据上传说明

## 📘 1. 代码及数据集上传步骤

### 🧰 步骤 1：准备项目代码

请在本地整理好代码结构，可参考模板仓库：[BUAADIG/Template](https://github.com/BUAADIG/Template)

建议至少包含以下内容：

- ✅ 完整、可运行的项目代码文件  
  包括 `model.py`、`train.py`、`data_loader.py`、`configs.py`、`main.py` 等模块
- ✅ 环境依赖文件：`requirements.txt` 或 `environment.yml`
- ✅ 待输入的数据集或数据集的下载方式说明  
  需额外包括 `data/README.md` 文件，说明数据结构和使用方式
- ✅ 完整的 `README.md` 文件  
  内容可参考模板仓库中的 `README.md`，应包含 Installation、Download Dataset、Quick Start 等部分，确保他人可顺利运行并复现实验结果

> 💡 **Note:** 完成代码打包后，请将压缩包发送至 **许嘉璐 (xujialu405@gmail.com)** 并说明项目名称，由管理员测试后统一上传至 GitHub 仓库。

---

### 📂 步骤 2：上传数据集

#### 情况 1：小型数据集（< 50MB）

- 将数据集压缩（如 `.zip`），放入项目代码的 `data/` 文件夹中
- 随代码一起上传至 GitHub
- 在 `data/README.md` 中补充说明数据内容和使用方式

#### 情况 2：大型数据集（≥ 50MB）

我们统一通过 Google Drive 平台进行托管。上传步骤如下：

1. 打开 Google Drive 链接：  
   [📁 Research Datasets Folder](https://drive.google.com/drive/folders/15aAt-6GX53iMOR4TmAeLY80osrsGf4yo?usp=sharing)
2. 点击左上角 “➕” 按钮，**新建文件夹**，命名为项目名（如 `ProjectX_data`）
3. 上传数据集（建议打包为 `.zip` 或 `.tar.gz`）

> 💡 **Note:**  
> 如使用 Google Drive 托管数据集，请在代码中的 `README.md` 和 `data/README.md` 文件中参考模板位置预留下载链接位置，管理员完成上传后将统一更新链接。

---

## 🧑‍💼 2. 管理员操作步骤

### 🔧 步骤 1：上传代码到 GitHub 组织仓库

1. 登录 GitHub，进入组织页面：[BUAADIG](https://github.com/BUAADIG)
2. 创建新的仓库，并填写项目信息
3. 在本地终端操作：

```bash
cd path/to/MyResearchProject         # 进入项目目录
git init                             # 初始化 Git
git remote add origin https://github.com/BUAADIG/repo-name.git
git add .
git commit -m "Initial commit"
git branch -M main
git push -u origin main
```

---

### ☁️ 步骤 2：上传数据集到 Google Drive

1. 打开 Google Drive：[https://drive.google.com/](https://drive.google.com/)
2. 登录实验室 Google 账号
3. 在 `我的云端硬盘 > ResearchDatasets` 中，新建一个文件夹（如 `ProjectX_data`）
4. 上传数据集压缩包
5. 右键设置为“**任何拥有链接的人可查看**”
6. 获取分享链接，例如：

```
https://drive.google.com/file/d/1AbcDeFgHijKlmNopQrSTuvwxYZ/view?usp=sharing
```

提取的 `file_id` 是：`1AbcDeFgHijKlmNopQrSTuvwxYZ`

7. 替换项目中两处 `README.md` 文件中的数据集下载链接：

```markdown
[Click here to download the dataset](https://drive.google.com/uc?id=1AbcDeFgHijKlmNopQrSTuvwxYZ)
```
