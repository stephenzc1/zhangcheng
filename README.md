html基础语法
<!DOCTYPE html>
<!-- 注释 ctrl+/ -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> 章程的网页</title>
    <style>
        /* css注释 */
        /* 这里写的都是css */
        /* 选择器{css属性}*/
        /* 选择器：查找标签 */
        p {
            color: skyblue;
        }
        /* 标签 */
        #aa{
            color: yellowgreen;
        }
        /* id */
        .one{
            color: blue;
        }
        /* 类 */
        div{
            width: 100px;
            height: 100px;
            background-color: pink;
            padding: 10px;
            border: 1px solid black;
            margin: 10px;
        }
    </style>
    <link rel="stylesheet" href="./样式.css">
</head>
<body>
    <h1 style="color: red; font-size: 60px;"> <strong>章程的网页</strong></h1><hr>
    <h2 id="aa">章程爱万佳怡，万佳怡也爱章程</h2>
    <h3 class="one">一起跳个舞先</h3>
    <img src="./person.gif" alt="" title="章程和万佳怡" width="400" height="200" >
    <br>
    <a href="./队长 _ 黄礼格 - 11.mp3">点击此处听音乐</a>  
    <br>
    <a href="./一分钟短视频校园大赛三等奖.mp4" autoplay controls loop>点击此处看视频</a>
    <br>
    <p>这是内嵌式标签</p>
    <div>这是一个盒子，这个盒子类似于生活中的盒子，可以装很多东西</div>
    <div>这是一个盒子，这个盒子类似于生活中的盒子，可以装很多东西</div>
    <dl>
    <!-- 自定义标签 -->
        <dt>帮助</dt>
        <dd>转人工</dd>
        <dd>智能语音助手</dd>
    </dl>
    <ul>
    <!-- 无序列表 -->
        <li>a</li>
        <li>b</li>
        <li>c</li>
    </ul>
    <ol>
    <!-- 有序列表 -->
        <li>a</li>
        <li>b</li>
        <li>c</li>
    </ol>
    <table border="1" width="500" height="100">
    <!-- 表格 -->
        <caption><strong>学生成绩单</strong></caption>
        <tr>
            <th>姓名</th>
            <th>成绩</th>
            <th>评语</th>
        </tr>
        <tr>
            <td>章程</td>
            <td rowspan="2">150</td>
            <td>纯爱战神</td>
        </tr>
        <tr>
            <td>万佳怡</td>
            <td>纯爱战神的老婆</td>
        </tr>
    </table>
        <br>
        <form action="">
        <!-- 一组input标签 -->
            文本框：<input type="text" placeholder="请输入用户名">
            <br>
            <br>
            密码框：<input type="password" placeholder="请输入密码">
            <br>
            <br>
            单选框：<label><input type="radio" name="x">男</label>
                    <label><input type="radio" name="x">女</label>
            <br>
            <br>
            上传文件框：<input type="file" multiple>
            <br>
            <br>
            提交与重置按钮：<input type="submit" value="免费注册"> 
            <input type="reset">
            <br>
            <br>
            <input type="button" value="普通按钮">
            <br>
            <br>
            <input type="checkbox">我同意以上协议
        </form>
        <select>
            <!-- 下拉菜单 -->
            <option selected>重庆</option>
            <option>北京</option>
            <option>天津</option>
            <option>上海</option>
        </select>
        <br>
        <br>
        <textarea name="" id="" cols="30" rows="10"></textarea>
        <!-- 文本域 -->
        <div>这是div标签</div>
        <div>这是div标签</div>
        <span>这是span标签</span>
        <span>这是span标签</span>
        <!-- 无语义的布局标签 -->
        <br>
        我爱&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;学习
        <!-- 空格 -->
        <br>


</body>
</html>