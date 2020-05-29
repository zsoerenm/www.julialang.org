
# 下载 Julia

如果你喜欢 Julia 语言，请考虑在 GitHub 上给我们一个 star，并向他人传播这个词语。

我们提供了几种方式供大家运行 Julia：
* 在命令行中使用 Julia REPL。
* 在浏览器中通过 JuliaBox.com 在 Jupyter notebook 上运行。不需要任何下载或安装——只要点开浏览器、注册，就可以开始计算啦。
* 使用 Docker Hub 上由 Docker 社区维护的镜像。
* 下载由 Julia Computing 提供的 JuliaPro。 JuliaPro 是一个集成了常用外置库的 Julia 发行版。 它包括了 Juno IDE、 Gallium debugger 和其它一系列用于画图、优化、机器学习、数据库的外部库。（需要注册才能下载）

此外，你可以安装 Plots.jl， 一个集成了大部分Julia绘图后端的绘图前端库。 其绘图能力由不同的后端提供，例如 PyPlot.jl 和 Gadfly.jl。 如果你在使用 JuliaBox，那么所有以上提到的绘图包都是预先安装的。

国内用户可以从 BFSU镜像源、USTC镜像源 或者 ZJU镜像源下载各个稳定版本， 若以上镜像未及时更新，还可前往 Julia 英文下载页面 下载最新的“当前的稳定版本”。习惯命令行的用户也可以通过社区维护的 jill.py -- Julia一键安装脚本来简化 Julia 的安装过程。

如果您安装 Julia 出现了问题，请查看特定平台的安装指南。如果您无法使用上面提供的安装方式，请提交一个 issue。

在安装 Julia 外置包时可以通过 切换上游Pkg服务器 来加速下载过程。
