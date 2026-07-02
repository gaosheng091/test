# GitHub Pages 绑定自定义域名教程

本文记录如何使用 GitHub Pages 网站(默认地址 `用户名.github.io`)让其他人也可以访问。

---

## 一、前提条件

在开始之前,你需要准备好:

1. **一个 Git 的账号**
   - 例如 `https://github.com/gaosheng091`

---

## 二、创建仓库

1. **点右上角的「+」号**

   看你截图右上角,有个 `+ ▾` 的按钮(在放大镜 🔍 图标右边)。点它,会弹出一个菜单,选 `New repository`(新建仓库)。

   > 也可以直接访问:<https://github.com/new>

2. **填写仓库信息**

   进入创建页面后,重点填这几项:

   | 项目 | 你要填的内容 |
   |------|------|
   | Repository name(仓库名) | 填 `test` |
   | Description(描述) | 可填可不填,随便写比如 `我的个人网站` |
   | Public / Private | 选 **Public(公开)** ← 免费账号做网站必须选这个 |
   | Add a README file | 勾上 ☑️(这样仓库不为空,方便后面操作) |

   其他选项(`.gitignore`、`license`)先不用管,留空。

3. **点绿色的「Create repository」按钮**

   页面最下面有个绿色按钮 `Create repository`,点它,仓库就建好了。

---

## 三、放一个 index.html(网页内容)

1. **进入你的 test 仓库**

   打开 <https://github.com/gaosheng091/test>

2. **找到上传入口**

   在仓库页面找 `Add file ▾` 按钮(在文件列表右上方,绿色 `Code` 按钮附近),点它 → 选 `Upload files`(上传文件)。

   > 也可以直接访问:<https://github.com/gaosheng091/test/upload/main>

3. **把 index.html 拖进去**

   - 把你电脑里的 `index.html` 直接拖到网页的上传框里
   - 或者点 `choose your files` 选择文件

   > ⚠️ 注意文件名:必须叫 `index.html`(全小写),这是首页的固定名字,不能叫 `Index.html` 或 `index.HTML`。

4. **提交**

   拉到页面下方,有个 `Commit changes`(提交)绿色按钮,直接点它。

---

## 四、开启 Pages

1. **点 Settings**

   在这个仓库页面最上方一排标签里(`Code` / `Issues` / `Pull requests` … 那一排,你截图往上滚一点能看到),找到最右边的 `Settings`(⚙️ 设置),点它。

   > 也可直接访问:<https://github.com/gaosheng091/test/settings/pages>

2. **左侧找 Pages**

   进 Settings 后,看左侧菜单,往下找到 `Pages`,点一下。

3. **设置分支**

   在 `Build and deployment` → `Branch` 区域:

   - 左边下拉框:把 `None` 改成 `main`
   - 右边文件夹:保持 `/ (root)` 不变
   - 点旁边的 `Save` 按钮

   保存后,页面上方会出现一句话,类似:

   > Your site is live at <https://gaosheng091.github.io/test/>
