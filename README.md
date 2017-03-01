# Private-chat-dialog
**私信聊天对话框**
因为公司项目要做个即时聊天功能，需要随里调出私信聊天对话框，自已用Jquery写了个demo.
![enter image description here](http://thumbnail0.baidupcs.com/thumbnail/a5367316f610022e3707791057bbb6e7?fid=3944337783-250528-70714135473082&time=1488355200&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-SvGhebLQ0XAehkU8xfKR95KMTKQ=&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=1384700041350659553&dp-callid=0&size=c710_u400&quality=100)

先全局引入

    <script type="text/javascript">
    $(function() {
       $('.item').perfectScrollbar();
    });
    </script>
 插件用的是divscroll.js
代码贴出来吧


    <!DOCTYPE html>
    <html lang="zh-CN">
    <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>格调装修网</title>
    <link rel="stylesheet" type="text/css" href="Static/css/common-openlayer.css">
    <script type="text/javascript" src="Static/js/jquery-1.12.2.min.js"></script>
    <script type="text/javascript" src="Static/js/divscroll.js"></script> 
    </head>
    
    <body>
    <!--弹出私信聊天框 开始--> 
    <div id="popbox8" class="popbox8">
      <div class="popbox-top3"><span>对话中</span></div>
      <div class="part1">
        <div class="item">
          <div id="popbox3-main" class="popbox3-main">
            <div class="popbox3-main-left">
              <div class="popbox3-main-touxiang"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
              <div class="popbox3-main-txt">
                <div class="org_box"> <span class="org_box_cor cor2"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题</div>
              </div>
            </div>
            <div class="popbox3-main-right">
              <div class="popbox3-main-txt">
                <div class="org_box_right"> <span class="org_box_cor cor4"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比</div>
              </div>
              <div class="popbox3-main-touxiang_right"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
            </div>
            <div class="popbox3-main-right">
              <div class="popbox3-main-txt">
                <div class="org_box_right"> <span class="org_box_cor cor4"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比</div>
              </div>
              <div class="popbox3-main-touxiang_right"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
            </div>
            
             <div class="popbox3-main-left">
              <div class="popbox3-main-touxiang"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
              <div class="popbox3-main-txt">
                <div class="org_box"> <span class="org_box_cor cor2"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题</div>
              </div>
            </div>
             <div class="popbox3-main-right">
              <div class="popbox3-main-txt">
                <div class="org_box_right"> <span class="org_box_cor cor4"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比</div>
              </div>
              <div class="popbox3-main-touxiang_right"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
            </div>
            
             <div class="popbox3-main-left">
              <div class="popbox3-main-touxiang"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
              <div class="popbox3-main-txt">
                <div class="org_box"> <span class="org_box_cor cor2"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题</div>
              </div>
            </div> <div class="popbox3-main-left">
              <div class="popbox3-main-touxiang"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
              <div class="popbox3-main-txt">
                <div class="org_box"> <span class="org_box_cor cor2"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题</div>
              </div>
            </div>
            <div class="popbox3-main-right">
              <div class="popbox3-main-txt">
                <div class="org_box_right"> <span class="org_box_cor cor4"></span>有的朋友比较喜欢用CSS来写,CSS写的话在火狐、IE下就会出现问题 有的朋友比</div>
              </div>
              <div class="popbox3-main-touxiang_right"><img src="Static/images/yuyuezhaobiao/yuyuezhaobiao_img04.jpg" width="135" height="135" /></div>
            </div>
          </div>
        </div>
      </div>
      <div class="popbox3-main-bottm">
        <div class="popbox3-main-bottm-from">
          <form action="" method="post">
            <input type="text" class="popbox3-main-bottm-from_textarea" value="请您输入内容">
            <input type="submit" class="popbox3-main-bottm-from_submit" value="发送"  />
          </form>
        </div>
      </div>
    </div>
    <!--弹出私信聊天框 结束-->
    <script type="text/javascript">
    $(function() {
       $('.item').perfectScrollbar();
    });
    </script>
    
    </body>
    </html>



