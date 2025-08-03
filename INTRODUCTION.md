1、 代码及数据集上传步骤
	步骤 1：准备项目代码
		在本地整理好代码结构，可参考模版中的格式(https://github.com/BUAADIG/Template)：
		· 完整、可正确运行的项目代码文件，包括model.py、train.py、data_loader.py, configs.py, main.py等必需的模块
		· 环境依赖文件：requirements.txt
		· 运行代码所需输入的数据集/数据集下载说明(数据集上传要求请看步骤2), 数据集对应的data/README.md说明文件
		· 完整的项目README.md文件，具体内容可参考模板(https://github.com/BUAADIG/Template)中README.md，需要确保通过Installation、Download dataset、Quick start步骤之后能够跑通代码，得到正确结果

		note: 完成代码打包后，请先把压缩包发送给许嘉璐(xujialu405@gmail.com)并告知，由其检验并测试后统一上传到Github仓库

	步骤2: 上传数据集
		1、如果使用的数据集较小(<50MB)可以将数据集压缩后放在代码的data文件夹中随代码上传至github仓库中，添加对应的数据集说明
		2、如数据集较大，我们依托于Google Drive平台共享我们的数据集，使用步骤如下：
		· 使用谷歌浏览器打开链接 https://drive.google.com/drive/folders/15aAt-6GX53iMOR4TmAeLY80osrsGf4yo?usp=sharing
		· 点击左上角“+”号新建文件夹，例如ProjectX_data
		· 上传数据集（推荐打包为 .zip 或 .tar.gz）

		note: 如为第二种需要下载数据集的情况，README.md和data/README.md文件中需要填写下载链接的地方可先为空，待管理员整理上传后统一填写下载链接


2、管理员操作步骤
步骤 1：创建组织中的新仓库，上传代码到 GitHub 仓库中
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

步骤 2：上传数据集到 Google Drive
	· 使用谷歌浏览器打开 Google Drive(https://drive.google.com/)
	· 登录实验室Google Drive账号
	· 在“我的云端硬盘-ResearchDatasets”文件夹中新建一个对应的文件夹，例如ProjectX_data
	· 复制指定的数据集到对应的位置
	· 设置文件或文件夹为「任何拥有链接的人都可以查看」
	· 复制分享链接，获取 file_id（用于 gdown 下载）
		https://drive.google.com/file/d/1AbcDeFgHijKlmNopQrSTuvwxYZ/view?usp=sharing
		提取的file_id为 1AbcDeFgHijKlmNopQrSTuvwxYZ
	替换提交者代码文件中两处README.md文件中的数据集下载链接
