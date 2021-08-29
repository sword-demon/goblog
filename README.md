# goblog

## 自动重载

### 安装air
设置Go Proxy
```bash
go env -w GOPROXY=https://goproxy.cn
```
设置成功后安装air
```bash
go get -u github.com/cosmtrek/air
```

需要在Go Module开启时下载。

安装完成后使用以下命令检查：
```bash
➜  goblog git:(main) ✗ air -v

  __    _   ___  
 / /\  | | | |_) 
/_/--\ |_| |_| \_ , built with Go 

```

### 使用air
在goblog项目根目录运行以下命令即可
```bash
air


  __    _   ___  
 / /\  | | | |_) 
/_/--\ |_| |_| \_ , built with Go 

watching .
!exclude tmp
building...
running...


```
