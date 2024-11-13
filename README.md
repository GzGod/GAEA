## GAEA脚本 [https://app.aigaea.net/](https://app.aigaea.net/register?ref=gajY8tu3rkd5vg)

## 环境要求

- python3.11
- Aigaea 账号

## 安装

1. **克隆仓库或下载脚本**：

    ```bash
    git clone https://github.com/Gzgod/GAEA.git
    cd GAEA

    ```

2. **安装依赖**：

    ```bash
    pip install -r requirements.txt
    ```


3. **把代理填入 `proxy.txt` 文件**：

    支持socks5和http

## 获取访问令牌放入id.txt

请按照以下步骤操作：

1. 登录到您的 [Aigaea 控制面板](https://app.aigaea.net/dashboard)。
2. 打开浏览器的开发者工具（按 `F12` 键，或右键点击页面选择“检查”）。
3. 选择 **Console**（控制台）选项卡，然后输入以下命令并按回车：

    ```javascript
    localStorage.getItem('gaea_token');
    ```

4. 控制台中会显示一个类似 `"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVC..."` 的字符串，这就是您的 `accessToken`。将此令牌复制下来，放入id.txt中



## 运行脚本

1. **运行脚本**：

    在安装好依赖并配置 `proxy.txt` 文件后，可以运行脚本：

    ```bash
    pytho main.py
    ```
