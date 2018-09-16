## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/YixiaoHuang/YixiaoHuang.com/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/YixiaoHuang/YixiaoHuang.com/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>简历生成器</title>
    <link rel="stylesheet" href="static/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal-default-theme.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal.min.js"></script>
    <script src="static/js/script.js"></script>
</head>

<body>
    <div class="container" id="cv">
        <div class="side">
            <div class="me">
                <div class="portrait"></div>
                <div class="remodal remodal-img" data-remodal-id="portrait-modal">
                    <h3>请输入图片URL地址：</h3>
                    <br/>
                    <input type="text" id="avatar-url">
                    <button data-remodal-action="confirm" class="remodal-confirm">确定</button>
                </div>
                <h1 id="username" >ekCit</h1>
                <h4 id="persona-tag" >Python / Web / 互联网教育</h4>
            </div>
            <div class="profile info-unit">
                <h2 class="info-header"><i class="iconfont icon-person"></i> <span class="info-title">基本信息</span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label">姓名</label><span class="label-value">XXX</span></li>
                    <li>
                        <label class="left-label">学历</label><span class="label-value">本科</span></li>
                    <li>
                        <label class="left-label">毕业院校</label><span class="label-value">北京邮电大学</span></li>
                    <li>
                        <label class="left-label">毕业年份</label><span class="label-value">2017</span></li>
                </ul>
            </div>
            <div class="contact info-unit">
                <h2 class="info-header"><i class="iconfont icon-call"></i> <span class="info-title">联系方式</span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label">手机</label><span class="label-value">182XXXXXXXX</span></li>
                    <li>
                        <label class="left-label">邮箱</label><span class="label-value">crmrc2014@gmail.com</span></li>
                    <li>
                        <label class="left-label">个人主页</label><span class="label-value">exit-tixe.me</span></li>
                    <li>
                        <label class="left-label">Github</label><span class="label-value">github.com/ekCit</span></li>
                </ul>
            </div>
            <div class="skill info-unit">
                <h2 class="info-header"><i class="iconfont icon-star"></i> <span class="info-title">技能点</span></h2>
                <hr>
                <ul class="progress-list">
                    <li>
                        <label class="left-label">Python</label>
                        <progress value="80" max="100"></progress>
                    </li>
                    <li>
                        <label class="left-label">html/css</label>
                        <progress value="70" max="100"></progress>
                    </li>
                    <li>
                        <label class="left-label">Javascript</label>
                        <progress value="60" max="100"></progress>
                    </li>
                    <li>
                        <label class="left-label">机器学习</label>
                        <progress value="60" max="100"></progress>
                    </li>
                </ul>
            </div>
            <div class="stack info-unit">
                <h2 class="info-header"><i class="iconfont icon-build"></i> <span class="info-title">技术栈</span></h2>
                <hr>
                <ul class="stack-list">
                    <li>
                        <label class="left-label">前端</label><span class="label-value">jQuery、Angular.js、React.js</span></li>
                    </li>
                    <li>
                        <label class="left-label">后端</label><span class="label-value">Flask、Django、Twisted、Node.js、MongoDB、MySQL、Redis</span></li>
                    </li>
                    <li>
                        <label class="left-label">其它</label><span class="label-value">我全都是瞎写的。</span></li>
                    </li>
                </ul>
            </div>

            <div class="code info-unit">
                <h2 class="info-header"><i class="iconfont icon-weixin"></i> <span class="info-title">个人微信</span></h2>
                <hr>
                <div class="weixin">
                    <img src="static/image/weixin.png" alt="">

                </div>
            </div>
            <div class="remodal remodal-img" data-remodal-id="weixin-modal">
                <h3>请输入图片URL地址：</h3>
                <br/>
                <input type="text" id="weixin-url">
                <button data-remodal-action="confirm" class="remodal-confirm">确定</button>
            </div>
        </div>
        <div class="main">
            <div class="education info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-education"></i> <span class="info-title">教育经历</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>北京邮电大学 - 网络工程专业（本科）2012-2017</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                        </p>
                    </li>
                </ul>
            </div>
            <div class="work info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-work"></i> <span class="info-title">工作经历</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>北京创客空间－实习生（实习）</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                        </p>
                    </li>
                    <li>
                        <h3>实验楼－课程内容（实习）</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </p>
                    </li>
                </ul class="experience-list">
            </div>
            <div class="project info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-project"></i> <span class="info-title">个人项目</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>基于 Qt 5 的文本编辑器</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam。Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                            <br/>
                        </p>
                    </li>
                    <li>
                        <h3>基于 Flask 的主机监视系统</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </p>
                    </li>
                    <li>
                        <h3>基于 Live2D 与 clmtrackr 的山寨 Facerig</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </p>
                    </li>
                    <li>
                        <h3>如果项目太少，可以在实验楼上找项目做啊:D</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </p>
                    </li>
                </ul>
            </div>
            <div class="trophy info-unit">
                <h2 class="info-header"><i class="iconfont icon-trophy"></i> <span class="info-title">奖项与证书</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>小学生作文二等奖</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam。
                        </p>
                    </li> 
                    <li>
                        <h3>曾获统一冰红茶“再来一瓶”奖</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam。
                        </p>
                    </li> 
                    <li>
                        <h3>这一行也是为了凑版面</h3>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam。
                        </p>
                    </li>                     
            </div>
            <div class="aboutme info-unit right-paragraph">
                <h2 class="info-header"><i class="iconfont icon-flower"></i> <span class="info-title">自我评价</span></h2>
                <hr>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
            </div>
        </div>
    </div>
</body>

</html>
