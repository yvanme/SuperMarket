<html>
<body>
<h1>网上商城</h1>
<h2>截图展示</h2>
<img src="./img/index.png" alt="首页" /><br />
<img src="./img/regist.png" alt="注册页面" /><br />
<img src="./img/login.png" alt="登录页面" /><br />
<img src="./img/logout.PNG" alt="注销页面" /><br />
<h2>声明</h2>
<ul>
    <li>泵项目静态资源由网络收集得来，并加以大范围修改</li>
    <li>未经许可不得将本项目商用，如需商用请联系作者<a href="mailto:zxr@tju.edu.cn">zxr@tju.edu.cn</a></li>
</ul>
<h2>关键技术</h2>
<ul>
    <li>JDBC连接MySQL</li>
    <li>可自定义使用的连接池：在JDBC.properties中全局配置，在web.xml中局部配置</li>
    <li>Servlet完成后端注册有效性校验</li>
    <li>Servlet完成后端登录校验</li>
    <li>jQuery完成前端注册有效性校验</li>
    <li>完成前端登录非空校验</li>
    <li>使用Ajax技术完成前端用户名可用性校验、退出登录功能</li>
</ul>
<h2>版本迭代</h2>
<table>
    <tr>
        <th>版本号</th>
        <th>更新内容</th>
        <th>上传时间</th>
    </tr>
    <tr>
        <td>0.1</td>
        <td>
            <ul>
                <li>初步完成项目方案确定</li>
                <li>完成主页及注册页面的静态资源编写(包括js,css)</li>
                <li>完成主页及注册页面的动态资源编写(包括jsp,servlet)</li>
                <li>通过jdbc链接MySQL数据库</li>
                <li>使用c3p0连接池</li>
            </ul>
        </td>
        <td>2020年8月3日</td>
    </tr>
    <tr>
        <td>0.1.1</td>
        <td>
            <ul>
                <li>可以选择使用哪个连接池，并且在web.xml中指定，现在可以使用DBCP连接池</li>
                <li>通过反射机制设置如果指定连接池调用失败，再调用哪个连接池</li>
                <li>使用Ajax技术完成前端用户名校验</li>
                <li>更改img标签的src属性，使浏览器异步发送GET请求，刷新验证码</li>
            </ul>
        </td>
        <td>2020年8月7日</td>
    </tr>
    <tr>
        <td>0.1.2</td>
        <td>
            <ul>
                <li>使用JDBC.properties进行全局JDBC配置</li>
                <li>去掉JDBC的反射调用</li>
                <li>使用cookie完成记住用户名功能</li>
                <li>新增登录功能：使用session完成会话级别的数据传递</li>
                <li>新增注销功能：通过ajax请求销毁session</li>
                <li>修改静态页面，使其实现对logo.png的单独依赖</li>
            </ul>
        </td>
        <td>2020年8月9日</td>
    </tr>
    <tr>
        <td>0.2</td>
        <td>
            <ul>
                <li>使用EL表达式、JSTL标签替换jsp页面中的脚本表达式</li>
                <li>修改静态资源，主页增加右下角浮动项以及向上返回功能</li>
                <li>重构为JavaEE三层经典模型</li>
            </ul>
        </td>
        <td>待定</td>
    </tr>
</table>
<h2>配置情况</h2>
<ul>
<li>本地修改hosts文件,自定义一个域名</li>
<li>虚拟主机使用tomcat7.0.62托管,将上述域名新增为虚拟主机,appBase参数填写绝对路径</li>
<li>本项目基于IntelliJ Idea 2020.01编写</li>
<li>JAVA_HOME环境变量配置为<code>set JAVA_HOME=C:\PROGRA~1\JetBrains\INTELL~1\jbr</code></li>
</ul>
</body>
</html>
