# 命令行工具
mdBook 既可以用作命令行工具，也可以用作 Rust crate。 让我们首先关注命令行工具功能。

# 二进制文件安装
我们尽最大努力为主要平台提供了预编译的二进制文件。 访问发布页面以下载适合您平台的版本。

# 源码安装
mdBook 也可以通过在本地机器上编译源代码来安装。

# 先决条件
mdBook 是用 Rust 编写的，因此需要用 Cargo 编译。 如果您还没有安装 Rust，请立即安装。

# 安装 Crates.io 版本
如果您已经安装了 Rust 和 Cargo，则安装 mdBook 相对容易。 你只需要在你的终端中输入这段代码：


# cargo install mdbook
这将从 Crates.io 获取最新版本的源代码并编译它。 您必须将 Cargo 的 bin 目录添加到您的 PATH 环境变量中。

在终端中运行 mdbook help 以验证它是否有效。 恭喜，您已经安装了 mdBook！