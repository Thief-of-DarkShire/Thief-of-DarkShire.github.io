# thief_of_darkshire
our blog

https://thief-of-darkshire.github.io/

## 安装
```bash
git clone https://github.com/Thief-of-DarkShire/source.git
```

> 其实直接在线编辑 ``source/_posts/`` 下的文件即可，增删改查啥的。

### 标准安装
1. 本地安装 npm
2. 全局安装 hexo-cli
    ```powershell
    npm i hexo-cli -g
    ```
3. 进入在上一步的 [安装](#安装) 拉下来的代码库中，
    ```powershell 
    npm i 
    ```

    ```powershell
    hexo server
    ```

4. 在浏览器中访问 `localhost:4000`

## 部署

```powershell
# 生成
hexo g
```
```powershell
# 推送
hexo d
```

## 语法

主要使用 markdown 的语法。

详见 [文档](https://hexo.io/zh-cn/docs/writing.html)

## 新增文章
```powershell
hexo new "文章名"
```

保存后即可刷新页面访问
