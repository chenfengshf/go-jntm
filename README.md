# 功能
- go开发的win10-gui程序, 使用lxn/walk, 打包体积7MB
- 点击按钮，播放几你太美.

# 下载依赖
- go mod tidy
- go get github.com/akavel/rsrc // 编译依赖

# 打包 : go generate
细节如下：
- rsrc -manifest test.exe.manifest -o rsrc.syso
- go build -ldflags="-H windowsgui"、
- .\项目名.exe
