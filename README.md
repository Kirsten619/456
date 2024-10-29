HTML 结构
index.html 文件包含以下主要部分：

输入框: 用于输入姓名、手机号、归属地和备注。
按钮: “添加”和“保存”按钮用于提交表单。
联系人列表: 使用表格展示所有联系人信息。
样式
cs.css 是可选的，用于改善网页呈现。你可以根据需求自定义样式，让通讯录的外观更符合用户需求。

接口说明
本前端系统将通过 AJAX 与后端进行交互，主要接口包括：

添加联系人: POST 请求发送到 api.php?action=add
编辑联系人: POST 请求发送到 api.php?action=edit
删除联系人: POST 请求发送到 api.php?action=delete
获取联系人: GET 请求向 api.php?action=get