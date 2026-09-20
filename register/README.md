 # 第二次作业：用户注册页面
## 作业内容
本项目实现用户注册HTML页面，综合使用表单、表格、列表。页面使用语义标签header、main、footer。
表单包含用户名、密码、确认密码、单选性别、日期、邮箱、手机号、复选爱好、文件上传、下拉城市、文本域，提交、重置按钮。
表格用于展示注册须知，使用colspan合并单元格；使用ul无序列表、ol有序列表、dl定义列表。
JS监听表单提交事件，在控制台打印表单数据。

## 使用到的标签
header,main,footer,h1,form,input,label,select,option,textarea,button,table,thead,tbody,th,tr,td,ul,ol,li,dl,dt,dd,script

## 遇到的困难及解决方法
1. 一开始手机号正则校验写法出错，查阅教材，使用pattern="[0-9]{11}"完成11位数字校验。
2. 表单提交页面会自动刷新，使用JS e.preventDefault()阻止默认提交，实现控制台打印数据。
3. 表格单元格合并，学习colspan属性完成跨列合并。