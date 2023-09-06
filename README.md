# httpserver
python3 http server｜本地远程服务器互传文件

## Usage

[Remote server] Download script to home:
```bash
cd ~/
curl -O https://raw.githubusercontent.com/winterant/httpserver/master/httpserver.py
```

[Remote server] Go to directory you want to transfer files and start http server:
```bash
cd /data/myfiles/
python3 ~/httpserver.py 8888
```

[Local computer] Accessing remote server `http://[remote_server_ip]:8888` which lists files existed you remote server, and you can upload and download files.
