<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />
    <title>每秒23兆字节</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial;
            padding: 10px;
            background: #f1f1f1;
        }

        /* 头部标题 */
        .header {
            padding: 30px;
            text-align: center;
            background: white;
        }

        .header h1 {
            font-size: 50px;
        }

        /* 导航条 */
        .topnav {
            overflow: hidden;
            background-color: #333;
        }

        /* 导航条链接 */
        .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        /* 链接颜色修改 */
        .topnav a:hover {
            background-color: #ddd;
            color: black;
        }

        /* 创建两列 */
        /* Left column */
        .leftcolumn {
            float: left;
            width: 75%;
        }

        /* 右侧栏 */
        .rightcolumn {
            float: left;
            width: 25%;
            background-color: #f1f1f1;
            padding-left: 20px;
        }

        /* 图像部分 */
        .fakeimg {
            background-color: #ffffff;
            width: 100%;
            padding: 4px;
        }

        /* 文章卡片效果 */
        .card {
            background-color: white;
            padding: 30px;
            margin-top: 40px;
        }

        /* 列后面清除浮动 */
        .row:after {
            content: "";
            display: table;
            clear: both;
        }

        /* 底部 */
        .footer {
            padding: 20px;
            text-align: center;
            background: #ddd;
            margin-top: 20px;
        }

        /* 响应式布局 - 屏幕尺寸小于 800px 时，两列布局改为上下布局 */
        @media screen and (max-width: 800px) {

            .leftcolumn,
            .rightcolumn {
                width: 100%;
                padding: 0;
            }
        }

        /* 响应式布局 -屏幕尺寸小于 400px 时，导航等布局改为上下布局 */
        @media screen and (max-width: 400px) {
            .topnav a {
                float: none;
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="header">
        <h1>欢迎来到我的网站</h1>
        <p>该网站目前处于起步阶段，后续更新可能比较慢，更多功能请敬请期待</p>
    </div>

    <div class="topnav">
        <a href="#">测试</a>
        <a href="#">测试</a>
        <a href="#">测试</a>
        <a href="#" style="float: right">测试</a>
    </div>

    <div class="row">
        <div class="leftcolumn">
            <div class="card">
                <h2>M4A1卡宾枪：现代战场的中坚力量</h2>
                <h5>2025 年 4 月 26日</h5>
                <div class="fakeimg" style="height: 220px">
                    <img src="https://i.imgs.ovh/2025/04/26/fvgsC.jpeg" alt="fvgsC.jpeg" border="5" width="400"
                        height="230" />
                </div>
                <p></p>

                M4A1卡宾枪是美国陆军广泛装备的突击步枪，由M16系列改进而来，
                它采用5.56×45毫米北约标准弹药，
                具有射速高、后坐力小、精度优良等特点，
                其模块化设计支持加装战术配件，如瞄准镜、激光指示器和榴弹发射器，
                适应多种作战需求，M4A1凭借轻便灵活和可靠性能，
                成为特种部队和常规部队的首选武器， 在现代战争中发挥着关键作用
                </p>
            </div>
            <div class="card">
                <h1>男子甘某肇事逃逸,警方迅速抓获归案</h1>
                <h5>2025 年 4 月 26日</h5>
                <div class="fakeimg" style="height: 240px"><img src="https://i.imgs.ovh/2025/04/26/fFZiH.jpeg"
                        alt="fFZiH.jpeg" border="5" width="274" height="222">
                </div>
                <div class="fakeimg" style="height: 210px"><img src="https://i.imgs.ovh/2025/04/26/fFcnX.jpeg"
                        alt="fFcnX.jpeg" border="5" width="366 height=" 200"></div>
                <p>2025年4月25日晚，甘某驾驶一辆鬼火在南宁市科园大道与一辆电动车相撞
                    ，致骑车人死亡，事故发生后，甘某未停车救助，反而加速逃离现场。
                    警方接报后迅速展开调查，通过监控锁定嫌疑车辆，并于次日早晨将甘某抓获，
                    目前，案件正在进一步处理中，
                    甘某将面临法律严惩
                </p>
            </div>
        </div>
        <div class="rightcolumn">
            <div class="card">
                <h2>关于我</h2>
                <p>一个只会每天坐在电脑前写代码的废物</p>
            </div>
            <div class="card">
                <h3>热门文章</h3>
                <div class="fakeimg">
                    <p>未开发</p>
                </div>
                <div class="fakeimg">
                    <p>未开发</p>
                </div>
                <div class="fakeimg">
                    <p>未开发</p>
                </div>
            </div>
            <div class="card">
                <h3>关注网站</h3>
                <p>该网站目前处于起步阶段，又是一个人制作
                    后续更新可能比较慢，
                    有什么bug跟我说就行了
                    ，我会击尝试修复的，并且我会在未来更新一些新功能，
                    有什么想看的也可以跟我说，我会尝试去做出来的
            </div>
        </div>
    </div>

    <div class="footer">
        <h1>网站作者QQ：2309194142</h1>
        <p>作者邮箱：2309194142@qq.com</p>
    </div>
</body>

</html>
