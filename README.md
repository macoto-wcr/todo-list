# 我的待办清单

  一个纯前端的待办清单应用，数据保存在浏览器本地，无后端、断网可用。

  🔗 **在线预览**：https://macoto-wcr.github.io/todo-list/

  ## 功能

  - 添加、编辑、删除待办事项
  - 勾选完成，自动加删除线
  - 回车快速添加，Esc 取消编辑
  - 数据保存在 localStorage，刷新页面不丢失
  - 首次打开从 jsonplaceholder API 拉取示例数据

  ## 技术栈

  - 原生 HTML / CSS / JavaScript（无框架）
  - `localStorage` 做本地持久化
  - `fetch` API 获取初始数据

  ## 本地运行

  ```bash
  git clone https://github.com/macoto-wcr/todo-list.git
  cd todo-list
  ```

  然后用浏览器打开 `index.html`，或用 VS Code 的 Live Server 插件。

  ## 说明

  纯静态页面，无后端服务。待办数据仅保存在访问者自己的浏览器中，不同设备之间不共享。
