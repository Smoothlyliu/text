<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>常见的表单属性</title>
</head>
<body>
    <form action="" autocomplete="on">

        用户名<input type="text" name="username" placeholder="请输入用户名" required>

        邮箱<input type="email" name="email" autocomplete="off" autofocus multiple>
        
        <input type="image" src="../语义化标签/img/1.jfif" width="150px" height="150px">

        <input type="submit" value="提交">
    </form>

    <!-- 
        autocomplete="on" 提示之前的输入内容选项      autocomplete="off" 不提示之前的输入内容选项
        
        autofocus 该属性规定在页面加载时，该input框自动获得焦点
        
        multiple input元素可选多个值

        required 提示输入框必须填写；
        
        
    -->
</body>
</html>


