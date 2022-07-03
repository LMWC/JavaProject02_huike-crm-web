## 运行

```bash
# 获取huike-crm-web文件
解压huike-crm-web.zip获取完整文件，仓库文件缺少node_modules

# 打开控制台窗口
在huike-crm-web文件夹窗口路径栏中输入cmd并回车打开huike-crm-web控制台窗口

# 运行前端程序
在控制台窗口中输入npm run dev并回车启动前端程序
```
## 开发

```bash
# 克隆项目
git clone http://git.itcast.cn/wangshengli/course-huike-java

# 进入项目目录
cd huike-ui

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:80

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```
