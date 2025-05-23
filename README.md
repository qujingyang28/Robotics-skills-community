# RobotQu-
这将是全球机器人工程师的聚集地
# 机器人学习笔记

这是一个机器人学习笔记仓库，按品牌分类，包含技术手册、图片和学习资源。欢迎使用和贡献！

## 目录结构
- [Brands](robotbrands)：按品牌分类的笔记
- [Resources](#resources)：通用学习资源
- [如何贡献](#contributing)

## Brands
- [OMRON](robotbrands/omron)：OMRON机器人学习笔记
- [ABB](robotbrands/ABB)：ABB机器人学习笔记
- [EFORT](robotbrands/EFORT)：EFORT机器人学习笔记
- [ESPON](robotbrands/ESPON)：ESPON机器人学习笔记
- [ESTUN](robotbrands/ESTUN)：ESTUN机器人学习笔记
- [FANUC](robotbrands/FANUC)：FANUC机器人学习笔记
- [HCFA](robotbrands/HCFA)：HCFA机器人学习笔记
- [INOVANCE](Brands/INOVANCErobot)：INOVANCErobot机器人学习笔记
- [JAKA](robotbrands/JAKA)：JAKA机器人学习笔记
- [KUKA](robotbrands/KUKA)：KUKA机器人学习笔记
- [Mitsubishi](robotbrands/Mitsubishi)：Mitsubishi机器人学习笔记
- [SINSUN DUCO](robotbrands/SINSUNSUCO)：新松多可机器人学习笔记
- [TMrobot](robotbrands/TMrobot)：达明机器人学习笔记
- [YAMAHA](robotbrands/UR)：YAMAHA机器人学习笔记

  

## Resources
- [ROS教程](Resources/ROS-Tutorials)
- [AI工具](Resources/AI-Tools)

## 如何贡献

在机器人领域探索的道路上，深知个人的力量是有限的，因此我打造了这个开源网站的分支内容，旨在构建一个最优质的开源机器人技能平台。我真诚地希望有更多同行业的专家、爱好者能加入进来，共同为机器人行业的发展添砖加瓦。

这是一个纯粹的开源共享平台，汇聚了我多年来在机器人领域调试的宝贵经验与积累，非官方内容，仅供参考学习使用。在这里，你可以上传自己的研究发现、项目成果、实践心得等一切与机器人相关的有价值内容，也能与众多志同道合的纯粹大佬相识相交，碰撞出思维的火花。让我们携手共进，共同创造属于我们的机器人世界！

以下是关于如何上传内容到 GitHub 的教程：

**一、前期准备**

  1. 注册并登录 GitHub 账号
在浏览器中访问 [GitHub 官方网站](https://github.com/)，点击 “Sign up” 按钮，按照页面提示填写相关信息完成账号注册，之后点击右上角 “Sign in” 输入账号密码登录。

  2. 创建仓库（Repository）

登录后，点击右上角的 “+” 号，选择 “New repository”，在弹出的页面中填写仓库名称（Repository name）、可选的描述信息（Description），选择仓库的隐私级别（公开 “Public” 或私密 “Private”，建议选择 “Public” 以便大家共享交流），然后点击 “Create repository” 按钮创建新的仓库。

**二、上传内容**

  1. 克隆仓库到本地（如果已在本地有要上传的项目文件可跳过此步骤直接添加到本地文件等夹操作）

点击仓库页面中的 “Code” 按钮，选择 “HTTPS” 选项，复制下方显示的链接（即仓库的克隆地址）。在本地打开命令提示符（Windows）或终端（Mac/Linux），切换到你希望放置仓库的目录，输入命令 `git clone [复制的克隆地址]`（将 “[复制的克隆地址]” 替换为实际复制的链接），按下回车键，即可将仓库克隆到本地，此时在对应目录下会生成一个与仓库同名的文件夹。

  2. 添加文件到本地仓库

将你想要上传的文件或文件夹放入刚刚克隆的本地仓库文件夹中（如果是新创建的仓库，也可直接在对应的本地目录下创建文件等）。

  3. 提交更改

在命令提示符或终端中，切换到本地仓库目录（使用 `cd` 命令），输入 `git add .` 命令（注意是英文句号），这个命令会将所有新增、修改的文件添加到暂存区。接着输入 `git commit -m "[提交说明]"`（将 “[提交说明]” 替换为你对此次提交内容的简要描述，比如 “添加机器人运动控制算法代码”），完成本地提交，此时更改的内容已保存在本地仓库的历史记录中。

  4. 推送到 GitHub 远程仓库

输入命令 `git push origin main`（假设远程仓库的默认分支为 “main”，如果不是，可将 “main” 替换为实际分支名称，如 “master”），按下回车键，按照提示输入 GitHub 账号密码（如果是首次操作，可能会进行身份验证等步骤），等待命令执行完成，即可将本地仓库中的内容推送到 GitHub 远程仓库，这样其他用户就能在该仓库页面看到你上传的内容了。

加入我们，一起丰富开源机器人技能平台的内容，推动机器人行业迈向更辉煌的未来！
