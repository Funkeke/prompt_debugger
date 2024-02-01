
### 安装依赖
`pip install -r requirements.txt`

### 打包
```bash
pyinstaller -w -F main.py -n="prompt debugger" -i logo.png --clean
```