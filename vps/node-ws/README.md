# node-ws

index.js和package.json 上传到/domains/域名目录/public_html

执行node index.js

如探针没扎进去，在终端使用

> ```bash
> curl -L https://raw.githubusercontent.com/mqiancheng/public/refs/heads/main/vps/node-ws/agent.sh -o agent.sh && chmod +x agent.sh && env NZ_SERVER=[agentg:port] NZ_TLS=false NZ_UUID=[UUID] NZ_CLIENT_SECRET=[CLIENT SECRET] ./agent.sh
> ```

卸载探针
> ```
> ./agent.sh uninstall
> ```
