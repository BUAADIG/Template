步骤 1：准备项目代码
	在本地整理好代码结构，确保有：
	· 完整、可正确运行的项目代码文件，包括model.py、train.py、main.py等
	· 环境依赖文件：requirements.txt
	· 数据集(数据集上传要求请看步骤3、4)
	· 完整README.md文件，具体内容可参考模板(https://github.com/BUAADIG/Template)中README.md，需要确保通过Installation、Download dataset、Quick start步骤之后能够跑通代码，得到正确结果

	note: 完成代码打包后，请先把压缩包发送给许嘉璐(xujialu405@gmail.com)并告知，由其核验测试后统一上传到github组织中，因此可先跳过步骤2

步骤 2：创建组织中的新仓库，上传代码到 GitHub 仓库中
	· 登录 GitHub 并创建新的仓库并设置仓库信息
	· 打开终端 / Git Bash，进入你的本地项目目录
		cd path/to/MyResearchProject
	· 初始化 Git
		git init
	· 添加 GitHub 组织仓库为远程地址
		git remote add origin https://github.com/BUAADIG/repo-name.git
	· 提交修改、推送
		git add .
		git commit -m "Initial commit"
		git branch -M main
		git push -u origin main

步骤 3：上传数据集到 Google Drive
	· 使用谷歌浏览器打开 Google Drive(https://drive.google.com/)
	· 登录实验室Google Drive账号 账号：buaadig@gmail.com 密码：BuaaDIG717
	· 在“我的云端硬盘-ResearchDatasets”文件夹中新建一个文件夹，例如ProjectX_data
	· 上传数据集（推荐打包为 .zip 或 .tar.gz）
	· 设置文件或文件夹为「任何拥有链接的人都可以查看」
	· 复制分享链接，获取 file_id（用于 gdown 下载）
		https://drive.google.com/file/d/1AbcDeFgHijKlmNopQrSTuvwxYZ/view?usp=sharing
		提取的file_id为 1AbcDeFgHijKlmNopQrSTuvwxYZ

步骤 4：在项目中添加数据下载说明
	· 编辑data/README.md, 具体内容格式可参考模板(https://github.com/BUAADIG/Template)中的对应文件
