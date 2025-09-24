## Rust语言安装方法：
### 1.下载Rustup，Microsoft C++生成工具，RustRover或Trae
### 2.运行Microsoft C++生成工具，选择“使用C++的桌面开发”，设置安装路径（这步不要落下，否则默认安装在C盘），Visual Studio生成工具2022点击启动，把VS安装软件固定到任务栏!!!
### 3.右键以管理员身份运行Rustup，选1（直接回车），安装好后，回车下载，完成后回车关闭CMD窗口
### 4.设置环境变量PATH： %USERPROFILE%\.cargo\bin 即：C:\Users\zgslz\.cargo\bin
### 5.验证 WIN+R打开CMD窗口
### CMD>cargo --version
### CMD>rustup update     //更新Rust  
### CMD>rustup override set nightly    //Rust最新版
### CMD>rustup target add wasm32-unknown-unknown
### bash>curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh
### 6.安装RustRover,安装rust插件如：中文简体，CodeGeeX
### 7.安装Trae，安装rust-analyzer插件，
### CMD>cargo install trunk

### 更新wasm-bindgen
### CMD>rustup update
### 或项目根目录下：
### CMD>cargo update -p wasm-bindgen
### 检验：
### CMD>wasm-bindgen --version

### 清空缓存，检查依赖
### CMD>cargo clean
### CMD>cargo update


### 例子安装运行：
### 1.下载github源码zip格式，解压
### 2.进入examples
### 3.右键打开终端（翻墙）设置构建
### CMD>cargo install cargo-make
### CMD>cargo install trunk
### 安装perl：在https://strawberryperl.com/下载zip文件，解压后，设置环境变量（/bin目录）
### CMD>cargo install cargo-leptos    //有错误
### 4.进入具体目录  以下按README.md提示！！！
### CMD>cargo make start
### 或CMD>trunk serve --open
### 或CMD>cargo leptos watch
### 5.yarn构建
### CMD>pnpm add yarn -g
### CMD>yarn install
### CMD>yarn watch
### CMD>yarn build


### 备用：
### VS code插件：
### rust-analyzer
### better-toml
### CodeLLDB

### Rust客户端库：Reqwest
### 轻量级Rust异步运行时：smol

### Rust IDE:Lapce IDE









