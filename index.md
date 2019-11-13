<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="./css/common.css">
    <link rel="stylesheet" href="./icon_font/iconfont.css">
    <style>
    #projectTitle .projectTitle_text{ margin: 21px 0 0 22px;}
    #projectTitle .projectTitle_text h2{ font-size: 24px; line-height: 25px; margin-bottom: 10px;}
    #projectTitle .projectTitle_text p{ font-size: 14px; line-height: 30px; display: inline-block;}
    #projectTitle .projectTitle_text span{ font-size: 14px; color: #999999;}
    #projectTitle .projectTitle_text i{ font-size: 24px; margin-left: 10px;}
    #projectTitle .projectTitle_img{ margin: 20px 20px 0 0;}
    
    #projectList{ margin-top: 12px;}
    #projectList .projectList_btns{ height: 54px; background: #f1f9fc; border-top: 1px #e0eaef; border-bottom: 1px #dbe7ed solid;}
    #projectList .projectList_btns ul{ padding: 14px 0 0 20px;}
    #projectList .projectList_btns li{ float: left; width: 108px; height: 39px; border: 1px #dbe7ed solid; border-bottom: none; background: #fbfeff; color: #666; text-align: center; line-height: 39px; margin-right: 12px; border-radius: 5px 5px 0 0; cursor: pointer;}
    #projectList .projectList_btns li.active{ color: white; background: #018ffb;position: relative;}

    #projectList .projectList_cons{ margin: 20px;}
    #projectList .projectList_cons>div{ display: none;}
    #projectList .projectList_cons>div.show{ display: block;}
    #projectList .zl_upload1 , #projectList .zl_upload2 { width: 110px; height: 32px; line-height: 32px; text-align: center; font-size: 14px; color: white;  border-radius: 5px; cursor: pointer; }
    #projectList .zl_upload1 label, #projectList .zl_upload2 label{ cursor: pointer;}
    #projectList .zl_upload1 i, #projectList .zl_upload2 i{ margin-right: 5px;}
    #projectList .zl_upload1 input{ display: none;}
    #projectList .zl_upload2 input{ display: none; }
    #projectList .zl_upload1{ background: green; }
    #projectList .zl_upload2{ background: skyblue; margin-left: 20px;}
    #projectList .zl_search{ width: 210px; height: 30px; border: 1px #dbe7ed solid; border-radius: 5px; overflow: hidden;}
    #projectList .zl_search input{ border: none; width: 177px; height: 100%; color: #999; font-size: 14px; text-indent: 9px; position: relative; top: -3px; outline: slateblue;}
    #projectList .zl_search button{ width: 32px; height: 32px; border: none; border-left: 1px #dbe7cd solid; background: #fdfdfd;}
    #projectList .zl_search i{ font-size: 18px; font-weight: bold; color: #a1c6d4;}

    #projectList .zl_table{ clear: both;}
    #projectList .zl_table tr{ }
    #projectList .zl_table th{ }
    #projectList .zl_table td{ }
    </style>
</head>
<body>
    <header id="header">
        <hgroup class="header_logo l">
            <h1 class="l">
                <img src="./img/logo.jpg" alt="">
            </h1>
            <h2 class="l">内部管理平台</h2>
        </hgroup>
        <ul class="header_nav r">
            <li>
                <i class="iconfont icon-aixin"></i>欢迎您,管理员
            </li>
            <li>
                <i class="iconfont icon-shezhi"></i><a href="#">修改密码</a>
            </li>
            <li>
                <i class="iconfont icon-huiyuan"></i><a href="http://www.shcifco.com">公司官网</a>
            </li>
            <li>
                <i class="iconfont icon-shibai"></i><a href="#">退出</a>
            </li>
        </ul>
    </header>
    <aside id="menu" class="l">
        <ul>
            <li class="active">
                <a href="#">
                    <i class='iconfont icon-sousuo'></i>
                    <p>项目管理<p>
                </a>
            </li>
            <li>
                <a href="#">
                    <i class='iconfont icon-weixin'></i>
                    <p>用户管理<p>
                </a>
            </li>
            <li>
                <a href="#">
                    <i class='iconfont icon-bangzhu'></i>
                    <p>系统设置<p>
                </a>
            </li>
        </ul>
    </aside>
    <main id="main">
        <section class="main_container">
           <section id="projectTitle" class="clear">
               <div class="projectTitle_text l">
                   <h2>主要投资策略、投资方向及其风险特征等<i class="iconfont icon-shezhi"></i></h2>
                   <p>期货市场：</p><span>趋势交易、套利对冲、量化套利等投资策略</span><br>
                   <p>期权市场:</p><span>期权交易组合、量化交易等投资策略</span><br>
                   <p>股票市场:</p><span>多因子策略、择时投资策略、动量交易等投资策略</span><br>
                   <p>债券市场:</p><span>固定收益策略、可转债交易等投资策略</span><br>
               </div>
               <div class="projectTitle_img r">
                   <img src="./img/ewm.png" alt="">
               </div>
           </section>
           <section id="projectList">
               <div class="projectList_btns">
                   <ul>
                       <li>职能部门</li>
                       <li>资料管理</li>
                       <li>从业资格</li>
                       <li class="active"><div class="tri"></div> 投资咨询</li>
                   </ul>
               </div>
               <div class="projectList_cons">
                   <div>职能部门</div>
                   <div>资料管理</div>
                   <div>从业资格</div>
                   <div class="show">
                       <div class="zl_upload1 l">
                           <label>
                               <input type="file">
                               <i class="iconfont icon-xiazai"></i>单个上传
                           </label>
                       </div>
                       <div class="zl_upload2 l">
                            <label>
                                <input type="file" multiple>
                                <i class="iconfont icon-weixin"></i>批量上传
                            </label>
                        </div>
                       <div class="zl_search r">
                           <input type="text" placeholder="请输入关键字"><button><i class="iconfont icon-sousuo"></i></button>
                       </div>
                       <table class="zl_table">
                           <thead>
                               <tr>
                                   <th><input type="checkbox"></th>
                                   <th>文档名称</th>
                                   <th>文档大小</th>
                                   <th>上传者</th>
                                   <th>上传时间</th>
                                   <th>操作</th>
                               </tr>
                           </thead>
                           <tbody>
                               <tr>
                                   <td><input type="checkbox"></td>
                                   <td><i class="iconfont icon-huiyuan"></i> 安全专项方案.doc</td>
                                   <td>21.3KB</td>
                                   <td>陈文耀</td>
                                   <td>2016-3-14</td>
                                   <td><i class="iconfont icon-bangzhu"></i><i class="iconfont icon-shibai"></i></td>
                               </tr>
                               <tr>
                                   <td><input type="checkbox"></td>
                                   <td><i class="iconfont icon-huiyuan"></i> 安全专项方案.doc</td>
                                   <td>21.3KB</td>
                                   <td>陈文耀</td>
                                   <td>2016-3-14</td>
                                   <td><i class="iconfont icon-bangzhu"></i><i class="iconfont icon-shibai"></i></td>
                               </tr>
                               <tr>
                                   <td><input type="checkbox"></td>
                                   <td><i class="iconfont icon-huiyuan"></i> 安全专项方案.doc</td>
                                   <td>21.3KB</td>
                                   <td>陈文耀</td>
                                   <td>2016-3-14</td>
                                   <td><i class="iconfont icon-bangzhu"></i><i class="iconfont icon-shibai"></i></td>
                               </tr>
                               <tr>
                                   <td><input type="checkbox"></td>
                                   <td><i class="iconfont icon-huiyuan"></i> 安全专项方案.doc</td>
                                   <td>21.3KB</td>
                                   <td>陈文耀</td>
                                   <td>2016-3-14</td>
                                   <td><i class="iconfont icon-bangzhu"></i><i class="iconfont icon-shibai"></i></td>
                               </tr>
                               <tr>
                                   <td><input type="checkbox"></td>
                                   <td><i class="iconfont icon-huiyuan"></i> 安全专项方案.doc</td>
                                   <td>21.3KB</td>
                                   <td>陈文耀</td>
                                   <td>2016-3-14</td>
                                   <td><i class="iconfont icon-bangzhu"></i><i class="iconfont icon-shibai"></i></td>
                               </tr>
                           </tbody>
                       </table>
                   </div>
               </div>
           </section>
        </section>
    </main>
    <footer id="footer">
        上海市浦东新区世纪大道1701号中国钻石交易中心13B 电话：021-60209176 邮编：200122 上海中期期货股份有限公司 版权所有
    </footer>
</body>
</html>
