# Git & Github
## 关于 GitHub
可以使用 GitHub 和 Git 来协作处理工作。

GitHub 是一种基于云的平台，可在其中存储、共享并与他人一起编写代码。

- 通过将代码存储在 GitHub 上的“存储库”中，你可以：

  - “展示或共享”你的工作。
  - 持续“跟踪和管理”对代码的更改。
  - 让其他人“审查”你的代码，并提出改进建议。
  - 在共享的项目中开展“协作”，无需担心这些更改会在准备好集成更改之前影响协作者的工作。
  - 协作式工作是 GitHub 最基本的功能之一，该功能由开源软件 Git 实现，而 GitHub 是以该软件为基础进行构建的。

## 关于 Git
Git 是一种可以智能追踪文件中的更改的版本控制系统。 在你和一组人员同时对同一文件进行更改时，Git 的价值就体现出来了。

- 通常，要在基于 Git 的工作流中执行此操作，需要：

  - 为你（和协作者）正在处理的文件的主副本“创建分支”。
  - 在自己的个人分支上独立安全地对文件“进行编辑”。
  - 让 Git 智能地将特定更改“合并”回文件的主副本，从而确保更改不会影响其他人的更新。
  - 让 Git “跟踪”你和其他人的更改，这样就可以一直使用项目的最新版本。
  - 若要自行尝试使用 Git，请参阅 开始使用 Git。
 
# Git
## 身份认证
从 Git 连接到 GitHub 仓库时，需要使用 HTTPS 或 SSH 向 GitHub 进行身份验证。

注意

可以使用 GitHub CLI 向 GitHub 进行身份验证，无论是通过 HTTP 还是 SSH 均可。 有关详细信息，请参阅 gh auth login。

通过 HTTPS 连接（推荐）
如果使用 HTTPS 克隆，则可以使用凭据帮助程序在 Git 中缓存 GitHub 凭据。 有关详细信息，请参阅 关于远程仓库 和 在 Git 中缓存 GitHub 凭据。

通过 SSH 连接
如果使用 SSH 克隆，则必须在每台计算机上生成用于从 GitHub 进行推送或拉取的 SSH 密钥。 有关详细信息，请参阅 关于远程仓库 和 生成新的 SSH 密钥并将其添加到 ssh-agent。

关于 Git 用户名
可使用 git config 命令更改与 Git 提交关联的名称。 你设置的新名称将在从命令行推送到 GitHub 的任何未来提交中显示。 如果您想要将真实姓名保密，则可以使用任意文本作为您的 Git 用户名。

使用 git config 更改与 Git 提交关联的名称仅影响未来的提交，而不会更改用于过去提交的名称。

为计算机上的每个存储库设置 Git 用户名
打开Git Bash。

设置 Git 用户名：

git config --global user.name "Mona Lisa"
确认您正确设置了 Git 用户名：

$ git config --global user.name
> Mona Lisa
为一个仓库设置 Git 用户名
打开Git Bash。

将当前工作目录更改为您想要在其中配置与 Git 提交关联的名称的本地仓库。

设置 Git 用户名：

git config user.name "Mona Lisa"
确认您正确设置了 Git 用户名：

$ git config user.name
> Mona Lisa







