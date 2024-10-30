<template>
  <!-- ---------------------抄来的div-------------------- -->
  <div id="___gatsby">
    <div style="outline:none" tabindex="-1" role="group" id="gatsby-focus-wrapper">
      <div class="main-container">
        <section class="layout ant-layout">
          <header class="header-top false ant-layout-header"><a class="logo" title="ai-guru" href="/zh/"><img
                src="/images/logo.png" alt="LaiOffer"></a>
            <ul class="ant-menu hidden-lg-down false ant-menu-light ant-menu-root ant-menu-horizontal" role="menu">
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">

                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                  class="ant-menu-submenu-arrow"></i></div>

              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal highlight ant-menu-submenu-selected"
                role="menuitem">
                
                <el-dropdown>
                  
                  <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>
                    <div class="breathing-dot"></div>
                    <div class="breathing-dot-inner"></div><span>核心课程</span>&nbsp;&nbsp;<i aria-label="icon: down"
                      class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class=""
                        data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i>
                  </span><i class="ant-menu-submenu-arrow"></i></div>

                  <template #dropdown>
                    <el-dropdown-menu>
                      <el-dropdown-item>人工智能与数据科学强化课程</el-dropdown-item>
                      <el-dropdown-item>全栈开发项目实践课程</el-dropdown-item>
                    </el-dropdown-menu>
                  </template>
                </el-dropdown>

                
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal" role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true">
                  <span><span>成功案例</span>&nbsp;&nbsp;<i aria-label="icon: down" class="anticon anticon-down"><svg
                        viewBox="64 64 896 896" focusable="false" class="" data-icon="down" width="1em" height="1em"
                        fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></span><i class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-item" role="menuitem"><a title="正在直播" href="/zh/live/"><span>正在直播</span><img
                    src="/images/activity/live.svg" alt="live"></a></li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal" role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true">
                  <span><span>免费资源</span>&nbsp;&nbsp;<i aria-label="icon: down" class="anticon anticon-down"><svg
                        viewBox="64 64 896 896" focusable="false" class="" data-icon="down" width="1em" height="1em"
                        fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></span><i class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal" role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true">
                  <span><span>关于我们</span>&nbsp;&nbsp;<i aria-label="icon: down" class="anticon anticon-down"><svg
                        viewBox="64 64 896 896" focusable="false" class="" data-icon="down" width="1em" height="1em"
                        fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></span><i class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-item menu-item-aside no-border-bottom" role="menuitem"><a class="btn btn-cta"
                  title="免费试听第一节课" href="/zh/try-for-free/"><span>免费试听</span></a></li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-item menu-item-aside" role="menuitem"><i aria-label="icon: mail"
                  style="font-size:18px;margin:0" class="anticon anticon-mail"><svg viewBox="64 64 896 896"
                    focusable="false" class="" data-icon="mail" width="1em" height="1em" fill="currentColor"
                    aria-hidden="true">
                    <path
                      d="M928 160H96c-17.7 0-32 14.3-32 32v640c0 17.7 14.3 32 32 32h832c17.7 0 32-14.3 32-32V192c0-17.7-14.3-32-32-32zm-40 110.8V792H136V270.8l-27.6-21.5 39.3-50.5 42.8 33.3h643.1l42.8-33.3 39.3 50.5-27.7 21.5zM833.6 232L512 482 190.4 232l-42.8-33.3-39.3 50.5 27.6 21.5 341.6 265.6a55.99 55.99 0 0 0 68.7 0L888 270.8l27.6-21.5-39.3-50.5-42.7 33.2z">
                    </path>
                  </svg></i></li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu" style="display:none"
                role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
              <li class="ant-menu-item menu-item-aside" role="menuitem">
                <div class="ant-btn-group"><button type="button" class="ant-btn"><a title="en"
                      href="/en/course/ai-and-data-engineering/"><span>EN</span></a></button><button type="button"
                    class="ant-btn active ant-btn-two-chinese-chars"><a aria-current="page" title="zh" class=""
                      href="/zh/course/ai-and-data-engineering/"><span>中文</span></a></button></div>
              </li>
              <li class="ant-menu-submenu ant-menu-submenu-horizontal ant-menu-overflowed-submenu"
                style="visibility: hidden; position: absolute; display: none;" role="menuitem">
                <div class="ant-menu-submenu-title" aria-expanded="false" aria-haspopup="true"><span>···</span><i
                    class="ant-menu-submenu-arrow"></i></div>
              </li>
            </ul><button type="button" class="ant-btn btn-mobile-menu hidden-xl-up mobile-menu"></button>
          </header>
          <div id="limitedActivities" class="activities-dot"><span class="activities-home">
              <div class="breathing-dot"></div>
              <div class="breathing-dot-inner"><span>限免活动</span></div>
            </span>
            <div class="activities-samll" style="display: none;">
              <div class="small-activity-set">
                <section class="close-wrapper"><i aria-label="icon: arrows-alt" tabindex="-1"
                    class="anticon anticon-arrows-alt close arrows-alt"><svg viewBox="64 64 896 896" focusable="false"
                      class="" data-icon="arrows-alt" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                      <path
                        d="M855 160.1l-189.2 23.5c-6.6.8-9.3 8.8-4.7 13.5l54.7 54.7-153.5 153.5a8.03 8.03 0 0 0 0 11.3l45.1 45.1c3.1 3.1 8.2 3.1 11.3 0l153.6-153.6 54.7 54.7a7.94 7.94 0 0 0 13.5-4.7L863.9 169a7.9 7.9 0 0 0-8.9-8.9zM416.6 562.3a8.03 8.03 0 0 0-11.3 0L251.8 715.9l-54.7-54.7a7.94 7.94 0 0 0-13.5 4.7L160.1 855c-.6 5.2 3.7 9.5 8.9 8.9l189.2-23.5c6.6-.8 9.3-8.8 4.7-13.5l-54.7-54.7 153.6-153.6c3.1-3.1 3.1-8.2 0-11.3l-45.2-45z">
                      </path>
                    </svg></i><i aria-label="icon: close" tabindex="-1" class="anticon anticon-close close"><svg
                      viewBox="64 64 896 896" focusable="false" class="" data-icon="close" width="1em" height="1em"
                      fill="currentColor" aria-hidden="true">
                      <path
                        d="M563.8 512l262.5-312.9c4.4-5.2.7-13.1-6.1-13.1h-79.8c-4.7 0-9.2 2.1-12.3 5.7L511.6 449.8 295.1 191.7c-3-3.6-7.5-5.7-12.3-5.7H203c-6.8 0-10.5 7.9-6.1 13.1L459.4 512 196.9 824.9A7.95 7.95 0 0 0 203 838h79.8c4.7 0 9.2-2.1 12.3-5.7l216.5-258.1 216.5 258.1c3 3.6 7.5 5.7 12.3 5.7h79.8c6.8 0 10.5-7.9 6.1-13.1L563.8 512z">
                      </path>
                    </svg></i></section>
                <section class="activities-box">
                  <div class="ant-tabs ant-tabs-top ant-tabs-card ant-tabs-no-animation">
                    <div role="tablist" class="ant-tabs-bar ant-tabs-top-bar ant-tabs-card-bar" tabindex="0">
                      <div class="ant-tabs-nav-container"><span unselectable="unselectable"
                          class="ant-tabs-tab-prev ant-tabs-tab-btn-disabled"><span class="ant-tabs-tab-prev-icon"><i
                              aria-label="icon: left" class="anticon anticon-left ant-tabs-tab-prev-icon-target"><svg
                                viewBox="64 64 896 896" focusable="false" class="" data-icon="left" width="1em"
                                height="1em" fill="currentColor" aria-hidden="true">
                                <path
                                  d="M724 218.3V141c0-6.7-7.7-10.4-12.9-6.3L260.3 486.8a31.86 31.86 0 0 0 0 50.3l450.8 352.1c5.3 4.1 12.9.4 12.9-6.3v-77.3c0-4.9-2.3-9.6-6.1-12.6l-360-281 360-281.1c3.8-3 6.1-7.7 6.1-12.6z">
                                </path>
                              </svg></i></span></span><span unselectable="unselectable"
                          class="ant-tabs-tab-next ant-tabs-tab-btn-disabled"><span class="ant-tabs-tab-next-icon"><i
                              aria-label="icon: right" class="anticon anticon-right ant-tabs-tab-next-icon-target"><svg
                                viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em"
                                height="1em" fill="currentColor" aria-hidden="true">
                                <path
                                  d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                                </path>
                              </svg></i></span></span>
                        <div class="ant-tabs-nav-wrap">
                          <div class="ant-tabs-nav-scroll">
                            <div class="ant-tabs-nav ant-tabs-nav-animated">
                              <div>
                                <div role="tab" aria-disabled="false" aria-selected="true"
                                  class="ant-tabs-tab-active ant-tabs-tab">软件工程求职</div>
                                <div role="tab" aria-disabled="false" aria-selected="false" class=" ant-tabs-tab">数据科学求职
                                </div>
                              </div>
                              <div class="ant-tabs-ink-bar ant-tabs-ink-bar-animated"
                                style="display: block; transform: translate3d(0px, 0px, 0px); width: 0px;"></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div tabindex="0" role="presentation"
                      style="width: 0px; height: 0px; overflow: hidden; position: absolute;"></div>
                    <div
                      class="ant-tabs-content ant-tabs-content-no-animated ant-tabs-top-content ant-tabs-card-content">
                      <div role="tabpanel" aria-hidden="false" class="ant-tabs-tabpane ant-tabs-tabpane-active">
                        <div tabindex="0" role="presentation"
                          style="width: 0px; height: 0px; overflow: hidden; position: absolute;"></div>
                        <div class="small-box">
                          <section class="banner"
                            style="background-image: url(&quot;https://cn-lms-data.oss-cn-shenzhen.aliyuncs.com/lpm_files/ae7030ba-eeed-4c01-9f7c-a4344fed7906.png&quot;);">
                          </section>
                          <section class="small-main">
                            <section class="samll-header">
                              <h3 class="title"> 近期直播讲座预告</h3>
                              <div class="lecture-main">
                                <p class="title2"> 讲座1：前谷歌面试官</p>
                                <p class="title1"> 北美CS/Data最新面试趋势与求职攻略</p>
                              </div>
                            </section>
                            <section class="samll-side-footer">
                              <div class="title"><img class="side-qrcode"
                                  src="https://cn-lms-data.oss-cn-shenzhen.aliyuncs.com/lpm_files/4ec493c9-1bd0-4e14-ae24-b22e9215e59d.jpg"
                                  alt="laioffer qrcode"><span>扫描二维码，添加顾问免费报名直播讲座！</span></div>
                              <div class="checkout"><span class="cursor"><span>其他方式报名</span><i aria-label="icon: right"
                                    class="anticon anticon-right"><svg viewBox="64 64 896 896" focusable="false"
                                      class="" data-icon="right" width="1em" height="1em" fill="currentColor"
                                      aria-hidden="true">
                                      <path
                                        d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                                      </path>
                                    </svg></i></span></div>
                            </section>
                          </section>
                        </div>
                        <div tabindex="0" role="presentation"
                          style="width: 0px; height: 0px; overflow: hidden; position: absolute;"></div>
                      </div>
                      <div role="tabpanel" aria-hidden="true" class="ant-tabs-tabpane ant-tabs-tabpane-inactive"></div>
                    </div>
                    <div tabindex="0" role="presentation"
                      style="width: 0px; height: 0px; overflow: hidden; position: absolute;"></div>
                  </div>
                </section>
              </div>
            </div>
          </div>
          <main class="ant-layout-content" style="min-height:100vh">
            <div class="course-detail ai-and-data-engineering">
              <div class="course-header page-header container "><video id="backgroundVideo" class="background-video"
                  poster="/images/shapes/video-bg.png" preload="metadata" autoplay="" loop="" muted="" playsinline="">
                  <track kind="captions" label="人工智能与数据科学强化课程">
                  <source type="video/mp4" src="https://www.laioffer.com/videos/ai-main.mp4">
                </video>
                <div class="background"></div>
                <div class="background2"></div>
                <div class="content">
                  <h1 class="page-title">
                    <div>人工智能与数据科学强化课程</div>
                  </h1>
                  <p class="page-sub-title">从这里，踏上人工智能与数据科学创新之路</p>
                  <div class="btn-bar"><a class="ant-btn btn-action inverted" title="免费试听第一节课"
                      href="/zh/try-for-free/?t=ai-and-data-engineering"><span>免费试听</span></a><button type="button"
                      class="ant-btn btn-link inverted undefined"><span>查看课表</span></button></div>
                </div>
              </div>
              <div class="course-summary float-container ">
                <div class="ant-row-flex ant-row-flex-center summary-bar  undefined"
                  style="margin-left:-16px;margin-right:-16px;margin:0">
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-20 ant-col-md-8">
                    <p><span>课程时长</span></p>
                    <h3>16<!-- --> <!-- -->周</h3><small>每周5节课, 每节课2-3小时</small>
                  </div>
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-20 ant-col-md-8">
                    <p><span>下次开课</span></p>
                    <div style="padding-top:4px">
                      <h3><span>即将开课</span></h3><small><span>关注我们获取最新信息</span></small>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-20 ant-col-md-8">
                    <p><span>建议预修课程</span></p>
                    <h3><span>无</span></h3><small><span>适合所有学生</span></small>
                  </div>
                </div>
              </div>
              <div class="course-intro-container content-container container" id="overview">
                <div class="ant-row-flex ant-row-flex-center" style="margin-left:-20px;margin-right:-20px">
                  <div style="padding-left:20px;padding-right:20px" class="ant-col ant-col-xs-24 ant-col-md-16">
                    <div class="promotion">
                      <div class="markdown-content">
                        <h2 id="商业分析与数据科学两大方向，强化培养面试技能！">商业分析与数据科学两大方向，强化培养面试技能！</h2>
                        <p>针对学员的职业规划，分商业分析和数据科学两个方向教学。前两个月共同上课，夯实基础，后一个月，分班上课，有针对性的准备面试。两个方向课程时间不冲突，您如果学有余力，也可以全方面准备。
                        </p>
                      </div>
                    </div>
                    <div class="markdown-content">
                      <p>由近20位工业界一线的数据科学家和机器学习专家联合授课，师生比高达1:5。100+课时，结合人工智能与数据科学岗位要求，从编程能力、模型理解、项目经验三个角度提升您的综合实力。</p>
                      <p>课程案例包括用户黏性分析、文本聚类、Spark程序开发、深度学习等多个数据科学领域当前热门问题。</p>
                      <p>本课程已帮助众多学员拿到科技、金融、咨询等行业数据科学家、机器学习工程师、数据分析、商业分析等岗位offer。</p>
                    </div>
                  </div>
                  <div style="padding-left:20px;padding-right:20px" class="ant-col ant-col-xs-24 ant-col-md-8">
                    <div class="ant-card ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-thumbnail">
                          <div class="background"></div><img src="https://www.laioffer.com/videos/data-bg.gif"
                            alt="AI &amp; Data Engineering Introduction">
                        </div>
                        <div class="card-content"><small><span>试听课</span></small>
                          <h2 class="title"><span>课程概述</span></h2>
                          <p class="subtitle"><span>主讲老师：Nathan老师</span></p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div id="tracks" class="tracks content-container container">
                <h2 class="main-title"><span>一门课程，两条路径</span>
                  <div class="dash"></div>
                </h2>
                <p class="sub-title"><span>根据不同的职业路径，您可以选择商业分析或数据科学两个课程。两门课程资源共享，帮助您横向拓宽发展机会，收获理想的offer。</span></p>
                <div class="ant-row-flex ant-row-flex-center" style="margin-left:-16px;margin-right:-16px">
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-24 ant-col-md-12">
                    <div data-id="3" class="ant-card ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-head"
                          style="background-image:url(&quot;/images/graphs/business-analyst.png&quot;)">
                          <div class="background pink"></div>
                          <h3>Track I</h3>
                          <h2><span>商业分析Track</span></h2>
                        </div>
                        <div class="card-content">
                          <p class="description"><span>注重加强您的案例分析能力和数理统计知识，夯实SQL和Python基础，帮助您顺利通过商业分析岗位面试。</span></p>
                          <div class="tag-container">
                            <div class="tag">Data Analysis</div>
                            <div class="tag">Data Manipulation</div>
                            <div class="tag">Data Visualization</div>
                            <div class="tag">Business Communication</div>
                            <div class="tag">Case Studies</div>
                          </div>
                          <ul class="bullets">
                            <li><span>基于商业分析岗位的面试要求，为您定制合适的学习方案。</span></li>
                            <li><span>4+ Data Challenge和Case Study项目，帮您提升简历，拿到面试机会。</span></li>
                            <li><span>课程设置了一系列数据可视化、数据操作及商业软实力课程。</span></li>
                            <li><span>由在IT、金融、能源、咨询等行业有多年商业分析经验的老师授课。</span></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-24 ant-col-md-12">
                    <div data-id="4" class="ant-card ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-head"
                          style="background-image:url(&quot;/images/graphs/coding-screen.png&quot;)">
                          <div class="background"></div>
                          <h3>Track II</h3>
                          <h2><span>数据科学Track</span></h2>
                        </div>
                        <div class="card-content">
                          <p class="description"><span>为您深入讲解分布式系统和深度学习等前沿知识，并通过4+个机器学习项目帮助您拿到数据科学岗位offer。</span></p>
                          <div class="tag-container">
                            <div class="tag">Big Data</div>
                            <div class="tag">Deep Learning</div>
                            <div class="tag">Machine Learning</div>
                            <div class="tag">Apache Spark</div>
                            <div class="tag">TensorFlow</div>
                          </div>
                          <ul class="bullets">
                            <li><span>课程涵盖数据科学岗位所需的编程、模型、统计、大数据系统、深度学习等重要知识点。</span></li>
                            <li><span>手把手教您完成4+个机器学习前沿项目。</span></li>
                            <li><span>通过模拟面试课程，帮您解密数据科学岗位面试。</span></li>
                            <li><span>由Apache Spark核心开发工程师和数据科学家亲自授课。</span></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <section id="projects" class="projects-container content-container container">
                <h2 class="main-title"><span>10+ 热门Spark、Machine Learning与Business Analysis项目</span>
                  <div class="dash"></div>
                </h2>
                <div class="float-container">
                  <ul class="ant-timeline">
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>银行用户流失预测与分析</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/3PRVN97sskbngcWODU20cO/3f31194f9d1742ab80c4a3b39b5ca19e/_____________2019-11-07_______12.00.03.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>用户流失是一个常见的商业指标。不同行业都会根据这个指标调整公司策略、留住当前用户。因此，如何高效分析这个指标，将会极大影响公司的策略和发展。</p>
                              <p>
                                本项目以用户银行数据信息为例，带领学员应用多种监督学习模型(例如逻辑回归，随进森林)对银行用户流失进行预测和分析，并进一步分析影响流失的关键因素，为提高用户留存做出更好的商业决策。通过本项目，您将学到如何使用Pandas做数据探索、数据分析、数据预处理，以及如何通过Sklearn使用机器学习模型。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Pandas</div>
                              <div class="tag">Customer Churn Prediction and Analysis</div>
                              <div class="tag">Sklearn</div>
                              <div class="tag">Machine learning</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>电商平台用户评价分析与自然语言处理</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/2TZXmdtXXzSZbTKVjuL4CD/e922ba6cbeee94ed228e0da158f2add6/ecommerce-review.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                随着互联网的兴起，用户也越来越愿意表达自己的想法。特别是在网上购物方面，我们可以明显地发现，用户在购物前会参考他人的经验，在购物后也愿意加上自己的评价和购买建议。通过对用户评价的分析，公司可以更好地了解用户的想法和需求，也可以更有针对性地做出商业决策。在本项目中，我们会使用机器学习的方法来分析某知名电商的用户评价数据，从文本中发现一些隐含信息和内在联系，进而在未来使用这些信息来帮助我们解决一些商业问题，如提高转化率。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">TFIDF</div>
                              <div class="tag">PCA</div>
                              <div class="tag">Python</div>
                              <div class="tag"> K-means cluster</div>
                              <div class="tag">Latent Dirichlet Analysis</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>旧金山犯罪数据分析和预警</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/360bPF7VhYGyUgmsaOkcWE/15a0d4cdfcd322717452c8442b6add9e/san-francisco-crime-data-analysis-prediction.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>大数据分析是算法工程师必备的技能，合格的算法工程师需要掌握从数据收集到数据建模的整个流程，最后才能保证从数据中发现可能的规律，并建立机器学习模型。</p>
                              <p>本项目以旧金山地区犯罪数据为例，带领学员建立从数据采集、清洗、存储、分析的一整套数据分析的工作流。通过对于不同地区犯罪数据，天气数据的分析和建模，建立可能的犯罪事件预测机制。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Spark RDD</div>
                              <div class="tag">Spark SQL</div>
                              <div class="tag">OLAP</div>
                              <div class="tag">Regression</div>
                              <div class="tag">Data Pipeline</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>Movie Lense和Netflix 电影数据分析和推荐系统</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/5SsTFeEAHCQMqa8CkSAc8Y/f129fbc092abc7d2de48750d86ed7d63/netflix-recommendation.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                推荐系统是互联网公司的现金奶牛。无论是Google、Facebook等IT巨头，还是Uber、Airbnb、Pinterest各类初创公司，都需要一套高性能的推荐系统。推荐系统的设计与开发能力是各大顶尖科技公司普遍看重的能力之一。
                              </p>
                              <p>本项目带领您成为推荐系统设计与开发专家。本项目以Netflix电影数据为训练数据，带领学员掌握主流的推荐系统的算法，并熟练使用Spark Machine learning
                                pipeline建立自己的协同过滤算法，并部署推荐系统到生产型环境。</p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Recommendation System</div>
                              <div class="tag">Collaborative Filtering</div>
                              <div class="tag">Matrix Factorization</div>
                              <div class="tag">Spark ALS Model</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>Google Gstore销售预测与市场分析</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/1rGAIrepL1dfNSc6mCF50o/73ee47f7937a6cbcfd8749b84d074d14/GStore-tumbnail.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>Kaggle比赛是每一个DS/DA的炼金石，能够在Kaggle比赛中取得好的排名，是自我能力的最佳体现，也是公司判断人才非常重要的标准。在本期课程中，我们以Google
                                Gstore销售预测为范例，带领同学们熟练运用业界常用的LGBM, PyTorch
                                DeepModel来实现自己的算法，帮助同学们熟悉Kaggle比赛中常用的打法，并且在Kaggle比赛中取得好的名次。</p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">LGBM</div>
                              <div class="tag">PyTorch DeepModel</div>
                              <div class="tag">Kaggle</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>基于Auto-Encoder-Decoder 的电影推荐</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/q6Q5VkbPAOCKKG0ciUMQQ/151a2e42da8f420300c141cec46c77e3/coder-01.jpg?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>随着深度学习技术的飞速发展，越来越多的互联网公司开始在推荐系统中使用深度学习。相对于传统的推荐系统，深度学习可以实现端到端的学习。</p>
                              <p>
                                本项目以深度学习模型auto-encoder-decoder网络为基础，以imdb电影数据为训练数据，使用tensorflow建立auto-encoder-decoder模型。通过模型提取用户及电影特征，最终实现电影的自动推荐。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Auto-encoder-decoder</div>
                              <div class="tag">Recommendation System</div>
                              <div class="tag">Tensorflow</div>
                              <div class="tag">Movie Recommendation</div>
                              <div class="tag">End-to-end Training</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>基于LSTM深度学习模型的股票大盘指数预测</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/2YkurQadR62AOUkoK2A0gu/72ca1a74b529557f69a28f6bd94638ef/stock-index-prediction.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>时间序列（Time
                                Series）是我们在日常生活和社会工作中十分常见的一种数据，它是通过将一系列时间点上的观测值按等时间间隔测量来获取的数据集合，比如商业活动中，服装公司的年销售量；每日股票的价格波动；气象学中某城市的年降水量，月平均气温；城市污染PM2.5
                                指数 等等，因此对时间序列的研究广泛存在于各行各业。</p>
                              <p>
                                本项目以LSTM为基础，以股票数据作为训练数据，带您通过TensorFlow，建立时间序列数据分析的深度学习模型。最终实现个股的伴随时间的未来变化趋势，以及对应的大盘指数的变化预测和分析。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Time Series Data</div>
                              <div class="tag">LSTM</div>
                              <div class="tag">RNN</div>
                              <div class="tag">TensorFlow</div>
                              <div class="tag">Stock Price Prediction</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>纽约出租车数据与股市走向关系分析</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/6q24P4AV8WEaeYiK8S2gYS/39a5ff136c74ba0016fc0102021f191b/nyc-taxi.jpg?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                随着计算机技术的提高，我们现在很容易从不相关的数据中挖掘出隐藏的信息。比如十八世纪的时候，股票价格会随着来往的船只而波动，因为来往的商船传递着最新的消息。又有研究发现，公司高管拜访白宫的出入记录可以预测未来该公司股票的走向。这里，我们将遵循相同的思路，分析研究纽约出租车和股市的关系。看似纷繁复杂的纽约交通是否隐藏着有趣的信息呢？
                              </p>
                              <p>在大作业的实战中，同学们将会运用之前学习过的所有知识来合理探索数据，包括商业问题的数据化，提出合理问题，并对数据进行归纳整理，选择合理统计模型，验证猜想。</p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Python Dashboard</div>
                              <div class="tag">Segmentation Analysis</div>
                              <div class="tag">Statistical Model</div>
                              <div class="tag">Poisson Regression</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>E-Commerce营销策略优化</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/3O0ruV5PDqWKKGwU282qmM/df9e14bca03732972581f947d5c55f40/e-commerce.jpg?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                2017年，全球零售电子商务营业额达到了2.290万亿美元，约占零售总额的10.1%，预计到2021年将达到4.479万亿美元。2018年是线上线下零售革命——“未来零售”落地生根发芽、蓬勃发展的一年。
                              </p>
                              <p>在本项目中，同学会通过分析某知名电商网站销量和产品信息，系统化的学习个性化设计，新顾客吸引与鼓励顾客再购物方法，商业推销途径优化，然后建立一个网页产品销量预测模型。</p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">E-commerce</div>
                              <div class="tag">Business Analysis</div>
                              <div class="tag">Data Visualization</div>
                              <div class="tag">Product Insight</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>数据可视化与Tableau应用举例</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/1tZUEyvM0eVxWGFzIdJl4v/949638178e435ed8fde6389ba88fdb1f/data-visualization.jpg?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>“一图胜千言”。如何利用可视化来理解和沟通数据已经成为现代数据分析不可或缺的能力。 在本项目中，
                                我们将一起学习可视化的基本原理和最佳实践，用Tableau对其经典数据集Global Superstore Retail
                                Data做探索性数据分析和汇报总结；并使用Matplotlib, Seaborn and Pandas实现Python数据可视化分析。 </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Tableau</div>
                              <div class="tag">Python</div>
                              <div class="tag">Data Visualization</div>
                              <div class="tag">Data Analysis</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>Fintech 用户信用评级建模分析与金融风险控制</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/2xQCRPgaLWvdohfBH25NFD/0743707704de5cbfaf294979af59c3aa/risk-control.png?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                数据挖掘和数据分析是互联网金融风险控制中最重要的一环。在大数据时代，银行和互联网金融公司在控制金融风险上进行了大量的投入。在过去的几年，大量的小型借贷，P2P公司所面临的金融风险成为了其成长的魔咒。但是国外P2P鼻祖Lending
                                Club、国内的阿里金融都能够做到较好地控制小贷风险。本项目利用LendingClub的实际案例，帮助同学学习互联网金融公司及传统银行怎样通过分析，建模来融合多维，多来源的数据，区分正常用户和欺诈用户，降低贷款风险。
                              </p>
                              <p>在项目结束后，同学可以独立完成数据的特征挖掘，能够自己动手开发基于机器学习的金融分析模型，能够熟练掌握各种分类算法，并且可以用业界数据解决任何互联网金融或银行的实际问题。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Risk Control</div>
                              <div class="tag">Credit Risk Model</div>
                              <div class="tag">Fraud Labeling</div>
                              <div class="tag">Machine Learning</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="ant-timeline-item ant-timeline-item-last">
                      <div class="ant-timeline-item-tail"></div>
                      <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                      <div class="ant-timeline-item-content">
                        <h4>Anomaly Detection数据异常检测与处理</h4>
                        <div class="project">
                          <div class="thumbnail"
                            style="background-image:url(//images.ctfassets.net/04k2xg9gplcj/4Hye0uZT8kQiceawIa08qC/9a204e6dc9d33bfad8bbae61e4e3b5d7/________________________.jpg?w=400&amp;q=100)">
                          </div>
                          <div class="description">
                            <div class="markdown-content">
                              <p>
                                在金融业、电商业以及共享行业等诸多商业领域中，往往伴随着黑产相关的欺诈风险。这些交易涉及直接金钱损失。如何在海量数据中有效的鉴别少量欺诈交易、降低损失而维持较好的客户体验，是各大公司艰巨的挑战。在本项目中，我们将一起分析处理某知名电商交易数据，通过系统的洞察数据中关联/模式，建立完整机器学习解决方案，基于数据给出切实可行的商业建议，最小化企业欺诈损失。
                              </p>
                            </div>
                            <div class="tag-container">
                              <div class="tag">Payment Fraud Detection</div>
                              <div class="tag">Machine Learning</div>
                              <div class="tag">Pattern Study</div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </section>
              <div id="instructors" class="instructor-team content-container container">
                <h2 class="main-title"><span>工业界资深专家，培养一流数据科学人才</span>
                  <div class="dash"></div>
                </h2>
                <p class="sub-title"><span>课程由20余位老师实时直播授课，为您提供紧贴工业界，系统的知识讲解和求职指导。<br><br>授课团队由Google, Facebook, Airbnb,
                    McKinsey &amp; Company, Linkedin等科技、咨询公司的Senior Data Scientist、Machine Learning Engineer和Business
                    Analyst组成。<br><br>还有Apache Spark、Apache Hadoop的代码贡献者和管理者委员会成员亲自授课。</span></p><img
                  src="/images/graphs/ai-team-01.svg"
                  alt="Our team consists of senior data scientist, machine learning engineer, and business analyst from Google, Facebook, McKinsey &amp; Company, Hortonworks, Apache Spark, Apache Hadoop, etc.">
              </div>
              <section id="highlights" class="highlight-container content-container container">
                <h2 class="main-title"><span>读懂人工智能，充实您的求职技能点</span>
                  <div class="dash"></div>
                </h2>
                <div class="ant-row-flex" style="margin-left:-16px;margin-right:-16px">
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">20余位Google, McKinsey等科技、咨询公司的资深数据科学家、机器学习工程师和商业分析师实时实时直播授课。教师团队还有Apache
                          Spark、Hadoop的管理者委员会成员。</div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/7lg1fTfPvUaYuAuoCOG8M/8358b3ed9a234939163ca17ca5275270/software-engineers-working-on-project-and-2GV8F4X.jpg?h=216&amp;q=100"
                            srcset="" alt="2018-09-13-Data-Hightlight1"></div>
                        <div class="card-content">
                          <h2 class="title">工业界一线专家</h2>
                          <h3 class="subtitle">直播授课</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">10+节统计课程全面更新，针对数据科学面试的面试趋势，强化培训case study及实验设计应考技能。
                        </div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/5q7nFbCRTasQgcOgWMWusa/01086f252dae2c35ff22cf593f8e6843/AdobeStock_208157740.jpeg?h=216&amp;q=100"
                            srcset="" alt="2018-09-13-Data-highlight2"></div>
                        <div class="card-content">
                          <h2 class="title">统计模块全面更新</h2>
                          <h3 class="subtitle">全方位增强实力</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">
                          基于数据科学岗位的面试要求的，依托来Offer超强算法与编程的教学经验，用30+Python课程，帮助您快速入门，建立算法和编程知识体系，自信应对面试。</div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/45DRmTjDHaeoE8uGEmwiKM/35b9fa3e0a355bdaf5231a38d77761b8/AdobeStock_127621002.jpeg?h=216&amp;q=100"
                            srcset="" alt="2018-09-13-Data-hightlight3"></div>
                        <div class="card-content">
                          <h2 class="title">30+ Python课程</h2>
                          <h3 class="subtitle">夯实编程基础</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">本课程针对学员的不同职业规划，分商业分析和数据科学两个方向教学，由资深数据科学家和高级商业分析师，针对不同岗位的面试要求，有针对性的帮您提升。
                        </div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/5Y2tj9a7T2EyesAMsoIumK/1bc89ddff5268d2d65910a09862a88d6/AdobeStock_160384780.jpeg?h=216&amp;q=100"
                            srcset="" alt="2018-09-13-Data-hightlight4"></div>
                        <div class="card-content">
                          <h2 class="title">BA与DS两个方向</h2>
                          <h3 class="subtitle">分班教学</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">
                          来自一线科技/咨询公司的老师们，还会为您量身修改简历，并培训同学对简历中各项内容的英文描述能力。同时，他们还会与您进行1V1的模拟面试，帮您抓住面试机会。</div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/4ZByqZb84U8qcOQY8iuoAQ/2ef483be742091692d440da4b572c6af/programmer-and-ux-ui-designer-working-in-a-softwar-R2GNX2U.jpg?h=216&amp;q=100"
                            srcset="" alt="2018-09-12-SDE-liangdian3"></div>
                        <div class="card-content">
                          <h2 class="title">个性化简历修改</h2>
                          <h3 class="subtitle">模拟面试</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px"
                    class="ant-col ant-col-xs-24 ant-col-sm-12 ant-col-xl-8">
                    <div class="ant-card highlight ant-card-hoverable">
                      <div class="ant-card-body" style="padding:0">
                        <div class="card-cover">
                          来Offer与硅谷众多一线IT公司人力资源部门及猎头公司均保持良好的合作关系，拥有超过千人、遍布硅谷各大IT公司的强大校友资源，为您提供强有力的内推支持。
                        </div>
                        <div class="card-thumbnail"><img
                            src="//images.ctfassets.net/04k2xg9gplcj/W2MgCmskYC6UQuowWAqQs/75efa7f928d9ae67fda9c21919bb9ff8/listening-with-attention-P9EPXJ4.jpg?h=216&amp;q=100"
                            srcset="" alt="2018-09-12-SDE-liangdian5"></div>
                        <div class="card-content">
                          <h2 class="title">强大内推网络</h2>
                          <h3 class="subtitle">助力求职</h3>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </section>
              <div id="syllabus" class="syllabus-container content-container container">
                <h2 class="main-title"><span>课程大纲</span>
                  <div class="dash"></div>
                </h2>
                <div class="syllabus-section float-container">
                  <div class="label "><span>第1部分</span></div>
                  <div class="syllabus-detail">
                    <h3 class="title">机器学习理论+Python编程基础</h3>
                    <p class="description">您将学习Python语法、基本的线性数据结构和搜索算法、以及工业界主流的传统机器学习模型，夯实数据科学基础。</p>
                    <p class="frequency"><strong><span>上课频率</span></strong>: <!-- -->1个月，每周5节课，每节课2-3小时</p>
                    <div class="timeline-container collapse">
                      <ul class="ant-timeline">
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第1周</span></h4>
                            <p>Introduction of Data Science</p>
                            <p>Fundamentals of Probability</p>
                            <p>[Coding] Python Basics 1 variable and syntax</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第2周</span></h4>
                            <p>[Coding] Python Basics 2 function and class</p>
                            <p> Linear Regression &amp; Logistic Regression I</p>
                            <p>[Coding] Python Basics 3 base data structure</p>
                            <p>[Coding] Python Binary Search</p>
                            <p>Logistic Regression II &amp; Regularization</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第3周</span></h4>
                            <p>[Coding] Python Array Basic Sorting</p>
                            <p>Model Evaluation</p>
                            <p>[Coding] Python LinkedList and Recursion I</p>
                            <p>[Coding] Python LinkedList &amp; Recrusion I cont</p>
                            <p>Nonlinear Models I</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item ant-timeline-item-last">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第4周</span></h4>
                            <p>[Coding] Python Practice</p>
                            <p>Nonlinear Models II &amp; Feature Selection</p>
                            <p>[Coding] Python Advanced Sorting and Practice</p>
                            <p>[Coding] Python Review</p>
                            <p>PCA &amp; Unsupervised Learning</p>
                          </div>
                        </li>
                      </ul>
                    </div>
                  </div><button class="btn-link" type="button"><i aria-label="icon: down"
                      class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class=""
                        data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></button>
                </div>
                <div class="syllabus-section float-container">
                  <div class="label "><span>第2部分</span></div>
                  <div class="syllabus-detail">
                    <h3 class="title">概率与统计知识 &amp; Python编程进阶</h3>
                    <p class="description">您将进一步学习Python、数据结构和算法知识，锻炼Coding能力，并学习数理统计、概率等相关的重要知识点。</p>
                    <p class="frequency"><strong><span>上课频率</span></strong>: <!-- -->3周，每周5节课，每节课2-3小时</p>
                    <div class="timeline-container collapse">
                      <ul class="ant-timeline">
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第5周</span></h4>
                            <p>Data Manipulation in Python 1</p>
                            <p>[Coding] Python Queue and Stack</p>
                            <p>[Coding] Python Advanced Sorting and Practice</p>
                            <p>Data Manipulation in Python 2</p>
                            <p>[Coding] Python Review</p>
                            <p>[Coding] Python Review</p>
                            <p>[Coding] Exam 1</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第6周</span></h4>
                            <p>Machine Learning Project 1 - Customer Churn Prediction</p>
                            <p>[Coding] Python Binary Tree</p>
                            <p>[Coding] Recursion II - recursion on tree</p>
                            <p>Machine Learning Project 2 - NLP and Topic Modeling</p>
                            <p>[Coding] Python Practice</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第7周</span></h4>
                            <p>Introduction to statistics</p>
                            <p>[Coding] Python Binary Search Tree</p>
                            <p>[Coding] Python review</p>
                            <p>Resume and Interview Preparation I</p>
                            <p>Resume and Interview Preparation II</p>
                            <p>A/B testing 1</p>
                            <p>[Coding] Python Heap</p>
                            <p>A/B testing 2</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第8周</span></h4>
                            <p>A/B testing 3</p>
                            <p>[Coding] Python Review</p>
                            <p>A/B testing 4</p>
                            <p>Inference in regression</p>
                          </div>
                        </li>
                        <li class="ant-timeline-item ant-timeline-item-last">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第9周</span></h4>
                            <p>[Coding] String I</p>
                            <p>SQL I</p>
                            <p>[Coding] Recursion III DFS</p>
                            <p>[Coding] Recursion III DFS cont</p>
                            <p>SQL II</p>
                          </div>
                        </li>
                      </ul>
                    </div>
                  </div><button class="btn-link" type="button"><i aria-label="icon: down"
                      class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class=""
                        data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></button>
                </div>
                <div class="syllabus-section float-container">
                  <div class="label "><span>第3部分</span></div>
                  <div class="syllabus-detail">
                    <h3 class="title">OA经典案例分析与简历辅导</h3>
                    <p class="description">本阶段，您将学习经典Online Assessment破题思路，了解如何选择track，并获得深入准备和提升简历。</p>
                    <p class="frequency"><strong><span>上课频率</span></strong>: <!-- -->2 周, 每周5节课，每节课2-3小时</p>
                    <div class="timeline-container collapse">
                      <ul class="ant-timeline">
                        <li class="ant-timeline-item ant-timeline-item-last">
                          <div class="ant-timeline-item-tail"></div>
                          <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                          <div class="ant-timeline-item-content">
                            <h4><span>第10周</span></h4>
                            <p>[Coding] Exam 2</p>
                            <p>SQL III</p>
                            <p>Stats review</p>
                            <p>[Coding] Probability, Sampling, Randomization</p>
                            <p>Resume and interview preparation</p>
                            <p>Career guide: BA vs DS </p>
                            <p>Online Assessment - deep dive 1</p>
                            <p>Online Assessment - deep dive 2</p>
                          </div>
                        </li>
                      </ul>
                    </div>
                  </div><button class="btn-link" type="button"><i aria-label="icon: down"
                      class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class=""
                        data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></button>
                </div>
                <div class="syllabus-section float-container">
                  <div class="label "><span>第4部分</span></div>
                  <div class="ant-tabs ant-tabs-top ant-tabs-line">
                    <div role="tablist" class="ant-tabs-bar ant-tabs-top-bar" tabindex="0">
                      <div class="ant-tabs-nav-container ant-tabs-nav-container-scrolling"><span
                          unselectable="unselectable"
                          class="ant-tabs-tab-prev ant-tabs-tab-btn-disabled ant-tabs-tab-arrow-show"><span
                            class="ant-tabs-tab-prev-icon"><i aria-label="icon: left"
                              class="anticon anticon-left ant-tabs-tab-prev-icon-target"><svg viewBox="64 64 896 896"
                                focusable="false" class="" data-icon="left" width="1em" height="1em" fill="currentColor"
                                aria-hidden="true">
                                <path
                                  d="M724 218.3V141c0-6.7-7.7-10.4-12.9-6.3L260.3 486.8a31.86 31.86 0 0 0 0 50.3l450.8 352.1c5.3 4.1 12.9.4 12.9-6.3v-77.3c0-4.9-2.3-9.6-6.1-12.6l-360-281 360-281.1c3.8-3 6.1-7.7 6.1-12.6z">
                                </path>
                              </svg></i></span></span><span unselectable="unselectable"
                          class="ant-tabs-tab-next ant-tabs-tab-arrow-show"><span class="ant-tabs-tab-next-icon"><i
                              aria-label="icon: right" class="anticon anticon-right ant-tabs-tab-next-icon-target"><svg
                                viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em"
                                height="1em" fill="currentColor" aria-hidden="true">
                                <path
                                  d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                                </path>
                              </svg></i></span></span>
                        <div class="ant-tabs-nav-wrap">
                          <div class="ant-tabs-nav-scroll">
                            <div class="ant-tabs-nav ant-tabs-nav-animated">
                              <div>
                                <div role="tab" aria-disabled="false" aria-selected="true"
                                  class="ant-tabs-tab-active ant-tabs-tab">商业/数据分析Track</div>
                                <div role="tab" aria-disabled="false" aria-selected="false" class=" ant-tabs-tab">
                                  数据科学/工程Track</div>
                              </div>
                              <div class="ant-tabs-ink-bar ant-tabs-ink-bar-animated"
                                style="display: block; transform: translate3d(0px, 0px, 0px); width: 207px;"></div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div tabindex="0" style="width:0;height:0;overflow:hidden;position:absolute" role="presentation">
                    </div>
                    <div class="ant-tabs-content ant-tabs-content-animated ant-tabs-top-content" style="margin-left:0%">
                      <div role="tabpanel" aria-hidden="false" class="ant-tabs-tabpane ant-tabs-tabpane-active">
                        <div tabindex="0" style="width:0;height:0;overflow:hidden;position:absolute"
                          role="presentation"></div>
                        <div class="syllabus-detail">
                          <p class="description">4+案例分析与项目实战，加强您的分析能力和统计知识，夯实SQL和Python基础，提升沟通等软实力，帮助您顺利通过商业分析岗位面试。</p>
                          <p class="frequency"><strong><span>上课频率</span></strong>: <!-- -->1个月，每周4节课，每节课2-3小时</p>
                          <div class="timeline-container collapse">
                            <ul class="ant-timeline">
                              <li class="ant-timeline-item">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第11周</span></h4>
                                  <p>BA track introduction</p>
                                  <p>BA track mock interview</p>
                                  <p>[Coding-for-BA] Queue, Stack</p>
                                </div>
                              </li>
                              <li class="ant-timeline-item">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第12周</span></h4>
                                  <p>eCommerce deep dive 1: System design</p>
                                  <p>eCommerce deep dive 2: Data driven marketing </p>
                                  <p>eCommerce deep dive 3: Data lab </p>
                                  <p>[Coding-for-BA] HashTable</p>
                                </div>
                              </li>
                              <li class="ant-timeline-item">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第13周</span></h4>
                                  <p>eCommerce deep dive 4: Data lab </p>
                                  <p>Data visualization In Tableau</p>
                                  <p>Data visualization in Python</p>
                                  <p>[Coding-for-BA] String practice</p>
                                </div>
                              </li>
                              <li class="ant-timeline-item">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第14周</span></h4>
                                  <p>Case study deep dive 1</p>
                                  <p>Case study deep dive 2</p>
                                  <p>Case study deep dive 3</p>
                                  <p>Anomaly Detection 1</p>
                                </div>
                              </li>
                              <li class="ant-timeline-item">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第15周</span></h4>
                                  <p>Anomaly Detection 2</p>
                                  <p>Anomaly Detection 3</p>
                                  <p>Supply chain data 1</p>
                                  <p>Supply chain data 2</p>
                                </div>
                              </li>
                              <li class="ant-timeline-item ant-timeline-item-last">
                                <div class="ant-timeline-item-tail"></div>
                                <div class="ant-timeline-item-head ant-timeline-item-head-blue"></div>
                                <div class="ant-timeline-item-content">
                                  <h4><span>第16周</span></h4>
                                  <p>Review of BA/DA track</p>
                                </div>
                              </li>
                            </ul>
                          </div>
                        </div>
                        <div tabindex="0" style="width:0;height:0;overflow:hidden;position:absolute"
                          role="presentation"></div>
                      </div>
                      <div role="tabpanel" aria-hidden="true" class="ant-tabs-tabpane ant-tabs-tabpane-inactive"></div>
                    </div>
                    <div tabindex="0" style="width:0;height:0;overflow:hidden;position:absolute" role="presentation">
                    </div>
                  </div><button class="btn-link" type="button"><i aria-label="icon: down"
                      class="anticon anticon-down"><svg viewBox="64 64 896 896" focusable="false" class=""
                        data-icon="down" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                        <path
                          d="M884 256h-75c-5.1 0-9.9 2.5-12.9 6.6L512 654.2 227.9 262.6c-3-4.1-7.8-6.6-12.9-6.6h-75c-6.5 0-10.3 7.4-6.5 12.7l352.6 486.1c12.8 17.6 39 17.6 51.7 0l352.6-486.1c3.9-5.3.1-12.7-6.4-12.7z">
                        </path>
                      </svg></i></button>
                </div>
                <div class="disclaimer">* <span>每期课程均有不同程度的修改，实际课纲以上课公布为准</span></div>
              </div>
              <div id="faq" class="faq-container content-container container">
                <h2 class="main-title"><span>常见问题</span>
                  <div class="dash"></div>
                </h2>
                <div class="ant-collapse ant-collapse-borderless ant-collapse-icon-position-left">
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>来Offer的上课方式是怎样的？可以远程听课吗？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>数据课程的师生比例是多少？每个学生都能1对1辅导吗？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>如果缺席课程/效果不理想，能否重新听课？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>课程结业后，如果还需要求职帮助，怎么办？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>上课是老师讲完项目回家自己做，还是老师带着做？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>数据课程一开始，我就要决定上哪个Track吗？</div>
                  </div>
                  <div class="ant-collapse-item faq float-container">
                    <div class="ant-collapse-header" role="button" tabindex="0" aria-expanded="false"><i
                        aria-label="icon: right" class="anticon anticon-right ant-collapse-arrow"><svg
                          viewBox="64 64 896 896" focusable="false" class="" data-icon="right" width="1em" height="1em"
                          fill="currentColor" aria-hidden="true">
                          <path
                            d="M765.7 486.8L314.9 134.7A7.97 7.97 0 0 0 302 141v77.3c0 4.9 2.3 9.6 6.1 12.6l360 281.1-360 281.1c-3.9 3-6.1 7.7-6.1 12.6V883c0 6.7 7.7 10.4 12.9 6.3l450.8-352.1a31.96 31.96 0 0 0 0-50.4z">
                          </path>
                        </svg></i>如果选择了数据课程某个track，就只能上这个track的内容吗？</div>
                  </div>
                </div>
              </div>
              <div id="priceChart" class="price-chart-container content-container container">
                <div class="ant-row-flex ant-row-flex-center" style="margin-left:-16px;margin-right:-16px">
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-24 ant-col-md-12">
                    <div class="float-container" style="justify-content:space-between">
                      <div class="price-chart">
                        <p><span>即将开课，关注我们获取最新信息</span></p>
                        <h3>了解详情可扫码添加顾问</h3>
                      </div>
                      <ul class="features">
                        <li title="班主任责任制，及时追踪进度">班主任责任制，及时追踪进度</li>
                        <li title="5大互动平台，7天24小时答疑">5大互动平台，7天24小时答疑</li>
                        <li title="全明星导师，全程实时直播授课">全明星导师，全程实时直播授课</li>
                        <li title="1v1简历修改与内推">1v1简历修改与内推</li>
                        <li title="10大工业级别项目，提高动手能力">10大工业级别项目，提高动手能力</li>
                        <li title="30+ Python课程，突破编程面试">30+ Python课程，突破编程面试</li>
                      </ul><a class="ant-btn btn-action" title="免费试听第一节课"
                        href="/zh/try-for-free/?t=ai-and-data-engineering"><span>免费试听</span></a>
                    </div>
                  </div>
                  <div style="padding-left:16px;padding-right:16px" class="ant-col ant-col-xs-24 ant-col-md-12">
                    <div class="float-container"><img class="qr-code"
                        src="//images.ctfassets.net/04k2xg9gplcj/5gMscCZ4dby7o6r4BwGL3m/9b062ea2182f31944dc7c7e87e957d26/1861673411444_.pic.jpg?w=400&amp;q=100"
                        alt="QR Code">
                      <p><span>扫描上方二维码<br>联系来Offer课程顾问</span></p>
                      <h3><span>咨询课程与报名</span></h3>
                    </div>
                  </div>
                </div>
              </div>
              <div class="side-nav undefined">
                <div class="">
                  <div>
                    <ul class="">
                      <li class="active"><a data-href="#overview"><span>课程概述</span></a></li>
                      <li class=""><a data-href="#tracks"><span>职业路径</span></a></li>
                      <li class=""><a data-href="#projects"><span>实战项目</span></a></li>
                      <li class=""><a data-href="#instructors"><span>讲师团队</span></a></li>
                      <li class=""><a data-href="#highlights"><span>课程亮点</span></a></li>
                      <li class=""><a data-href="#syllabus"><span>课程大纲</span></a></li>
                      <li class=""><a data-href="#faq"><span>常见问题</span></a></li>
                    </ul><a class="ant-btn btn-action" title="免费试听第一节课" style="height:70px;line-height:1.2"
                      href="/zh/try-for-free/?t=ai-and-data-engineering"><small><span>即将开课</span></small><span>免费试听</span></a>
                  </div>
                </div>
              </div>
            </div>
          </main>
          <div class="footer container">
            <div class="mask">
              <div class="mask-inner"></div>
            </div>
            <div class="ant-row-flex ant-row-flex-center">
              <div class="ant-col resource-column ant-col-xs-22 ant-col-md-5">
                <h4><span>核心课程</span></h4><a title="软件工程师旗舰核心课程"
                  href="/zh/course/software-development/"><span>软件工程师旗舰核心课程</span></a><a title="全栈开发项目实践课程"
                  href="/zh/course/full-stack-development/"><span>全栈开发项目实践课程</span></a><a aria-current="page"
                  title="人工智能与数据科学强化课程" class=""
                  href="/zh/course/ai-and-data-engineering/"><span>人工智能与数据科学强化课程</span></a><a title="华尔街金融工程重度就业课程"
                  href="/zh/course/financial-engineering/"><span>华尔街金融工程重度就业课程</span></a><a title="高级工程师系统设计课程"
                  href="/zh/course/system-design/"><span>高级工程师系统设计课程</span></a><a title="无人车系统课程"
                  href="/zh/course/self-driving-car/"><span>无人车系统课程</span></a><a title="UX工业实战课程"
                  href="/zh/course/ui-ux-design/"><span>UX工业实战课程</span></a>
              </div>
              <div class="ant-col resource-column ant-col-xs-22 ant-col-md-4">
                <h4><span>产品</span></h4><a href="https://www.laicode.io" target="_blank" rel="noopener noreferrer"
                  title="LaiCode"><span>LaiCode</span></a><a href="https://learning.laioffer.com" target="_blank"
                  rel="noopener noreferrer" title="Learning Mangement System"><span>Learning Mangement System</span></a>
              </div>
              <div class="ant-col resource-column ant-col-xs-22 ant-col-md-4">
                <h4><span>资源，资讯 &amp; 案例</span></h4><a title="新闻 &amp; 活动" href="/zh/news/"><span>新闻 &amp;
                    活动</span></a><a title="精品视频" href="/zh/videos/"><span>精品视频</span></a><a title="技术博客"
                  href="/zh/blogs/"><span>技术博客</span></a><a title="学员心得" href="/zh/stories/"><span>学员心得</span></a><a
                  title="每周Offer榜" href="/zh/offer-board/"><span>每周Offer榜</span></a><a title="证书验证"
                  href="/zh/certificates/"><span>证书验证</span></a>
              </div>
              <div class="ant-col resource-column ant-col-xs-22 ant-col-md-4">
                <h4><span>消费者信息</span></h4><a href="/static/2023 LaiOffer Catalog-15d7e9351424c5be2bc914de866753df.pdf"
                  target="_blank" rel="noopener noreferrer" title="Catalog"><span>Catalog</span></a><a
                  href="https://www.bppe.ca.gov/" target="_blank" rel="noopener noreferrer"
                  title="BPPE"><span>BPPE</span></a><a
                  href="/static/LaiOffer School Performance Fact Sheet-5a41d7573db5f2ddb2afefa697714a15.pdf"
                  target="_blank" rel="noopener noreferrer" title="Fact Sheets"><span>Fact Sheets</span></a><a
                  rel="noopener noreferrer" disabled="" title="BPPE Annual Report"><span>BPPE Annual Report</span></a>
              </div>
              <div class="ant-col resource-column ant-col-xs-22 ant-col-md-3">
                <h4><span>关于我们</span></h4><a title="团队介绍" href="/zh/about/"><span>团队介绍</span></a><a title="加入我们"
                  href="/zh/careers/"><span>加入我们</span></a><a title="政策 &amp; 条款" href="/zh/privacy-terms/"><span>政策
                    &amp; 条款</span></a>
              </div>
            </div>
            <div class="ant-row-flex ant-row-flex-center social-media">
              <div class="ant-col qr-code ant-col-xs-22 ant-col-sm-12 ant-col-md-6"></div>
              <div class="ant-col ant-col-xs-22 ant-col-sm-12 ant-col-md-12">©&nbsp;<span>LaiOffer</span></div>
              <div class="ant-col ant-col-xs-22 ant-col-sm-12 ant-col-md-6"><a
                  href="https://www.linkedin.com/company/18092350/" target="_blank" rel="noopener noreferrer"
                  title="LaiOffer on LinkedIn"><i aria-label="icon: linkedin" class="anticon anticon-linkedin"><svg
                      viewBox="64 64 896 896" focusable="false" class="" data-icon="linkedin" width="1em" height="1em"
                      fill="currentColor" aria-hidden="true">
                      <path
                        d="M847.7 112H176.3c-35.5 0-64.3 28.8-64.3 64.3v671.4c0 35.5 28.8 64.3 64.3 64.3h671.4c35.5 0 64.3-28.8 64.3-64.3V176.3c0-35.5-28.8-64.3-64.3-64.3zm0 736c-447.8-.1-671.7-.2-671.7-.3.1-447.8.2-671.7.3-671.7 447.8.1 671.7.2 671.7.3-.1 447.8-.2 671.7-.3 671.7zM230.6 411.9h118.7v381.8H230.6zm59.4-52.2c37.9 0 68.8-30.8 68.8-68.8a68.8 68.8 0 1 0-137.6 0c-.1 38 30.7 68.8 68.8 68.8zm252.3 245.1c0-49.8 9.5-98 71.2-98 60.8 0 61.7 56.9 61.7 101.2v185.7h118.6V584.3c0-102.8-22.2-181.9-142.3-181.9-57.7 0-96.4 31.7-112.3 61.7h-1.6v-52.2H423.7v381.8h118.6V604.8z">
                      </path>
                    </svg></i></a><a href="mailto: ask@laioffer.com" title="Email LaiOffer"><i aria-label="icon: mail"
                    class="anticon anticon-mail"><svg viewBox="64 64 896 896" focusable="false" class=""
                      data-icon="mail" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                      <path
                        d="M928 160H96c-17.7 0-32 14.3-32 32v640c0 17.7 14.3 32 32 32h832c17.7 0 32-14.3 32-32V192c0-17.7-14.3-32-32-32zm-40 110.8V792H136V270.8l-27.6-21.5 39.3-50.5 42.8 33.3h643.1l42.8-33.3 39.3 50.5-27.7 21.5zM833.6 232L512 482 190.4 232l-42.8-33.3-39.3 50.5 27.6 21.5 341.6 265.6a55.99 55.99 0 0 0 68.7 0L888 270.8l27.6-21.5-39.3-50.5-42.7 33.2z">
                      </path>
                    </svg></i></a><a href="https://www.youtube.com/channel/UC12XyYzyyZwFiIgafl_Ga6w" target="_blank"
                  rel="noopener noreferrer" title="LaiOffer on YouTube"><i aria-label="icon: youtube"
                    class="anticon anticon-youtube"><svg viewBox="64 64 896 896" focusable="false" class=""
                      data-icon="youtube" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                      <path
                        d="M960 509.2c0-2.2 0-4.7-.1-7.6-.1-8.1-.3-17.2-.5-26.9-.8-27.9-2.2-55.7-4.4-81.9-3-36.1-7.4-66.2-13.4-88.8a139.52 139.52 0 0 0-98.3-98.5c-28.3-7.6-83.7-12.3-161.7-15.2-37.1-1.4-76.8-2.3-116.5-2.8-13.9-.2-26.8-.3-38.4-.4h-29.4c-11.6.1-24.5.2-38.4.4-39.7.5-79.4 1.4-116.5 2.8-78 3-133.5 7.7-161.7 15.2A139.35 139.35 0 0 0 82.4 304C76.3 326.6 72 356.7 69 392.8c-2.2 26.2-3.6 54-4.4 81.9-.3 9.7-.4 18.8-.5 26.9 0 2.9-.1 5.4-.1 7.6v5.6c0 2.2 0 4.7.1 7.6.1 8.1.3 17.2.5 26.9.8 27.9 2.2 55.7 4.4 81.9 3 36.1 7.4 66.2 13.4 88.8 12.8 47.9 50.4 85.7 98.3 98.5 28.2 7.6 83.7 12.3 161.7 15.2 37.1 1.4 76.8 2.3 116.5 2.8 13.9.2 26.8.3 38.4.4h29.4c11.6-.1 24.5-.2 38.4-.4 39.7-.5 79.4-1.4 116.5-2.8 78-3 133.5-7.7 161.7-15.2 47.9-12.8 85.5-50.5 98.3-98.5 6.1-22.6 10.4-52.7 13.4-88.8 2.2-26.2 3.6-54 4.4-81.9.3-9.7.4-18.8.5-26.9 0-2.9.1-5.4.1-7.6v-5.6zm-72 5.2c0 2.1 0 4.4-.1 7.1-.1 7.8-.3 16.4-.5 25.7-.7 26.6-2.1 53.2-4.2 77.9-2.7 32.2-6.5 58.6-11.2 76.3-6.2 23.1-24.4 41.4-47.4 47.5-21 5.6-73.9 10.1-145.8 12.8-36.4 1.4-75.6 2.3-114.7 2.8-13.7.2-26.4.3-37.8.3h-28.6l-37.8-.3c-39.1-.5-78.2-1.4-114.7-2.8-71.9-2.8-124.9-7.2-145.8-12.8-23-6.2-41.2-24.4-47.4-47.5-4.7-17.7-8.5-44.1-11.2-76.3-2.1-24.7-3.4-51.3-4.2-77.9-.3-9.3-.4-18-.5-25.7 0-2.7-.1-5.1-.1-7.1v-4.8c0-2.1 0-4.4.1-7.1.1-7.8.3-16.4.5-25.7.7-26.6 2.1-53.2 4.2-77.9 2.7-32.2 6.5-58.6 11.2-76.3 6.2-23.1 24.4-41.4 47.4-47.5 21-5.6 73.9-10.1 145.8-12.8 36.4-1.4 75.6-2.3 114.7-2.8 13.7-.2 26.4-.3 37.8-.3h28.6l37.8.3c39.1.5 78.2 1.4 114.7 2.8 71.9 2.8 124.9 7.2 145.8 12.8 23 6.2 41.2 24.4 47.4 47.5 4.7 17.7 8.5 44.1 11.2 76.3 2.1 24.7 3.4 51.3 4.2 77.9.3 9.3.4 18 .5 25.7 0 2.7.1 5.1.1 7.1v4.8zM423 646l232-135-232-133z">
                      </path>
                    </svg></i></a><a href="https://www.zhihu.com/people/laioffer" target="_blank"
                  rel="noopener noreferrer" title="LaiOffer on Zhihu"><i aria-label="icon: zhihu"
                    class="anticon anticon-zhihu"><svg viewBox="64 64 896 896" focusable="false" class=""
                      data-icon="zhihu" width="1em" height="1em" fill="currentColor" aria-hidden="true">
                      <path
                        d="M564.7 230.1V803h60l25.2 71.4L756.3 803h131.5V230.1H564.7zm247.7 497h-59.9l-75.1 50.4-17.8-50.4h-18V308.3h170.7v418.8zM526.1 486.9H393.3c2.1-44.9 4.3-104.3 6.6-172.9h130.9l-.1-8.1c0-.6-.2-14.7-2.3-29.1-2.1-15-6.6-34.9-21-34.9H287.8c4.4-20.6 15.7-69.7 29.4-93.8l6.4-11.2-12.9-.7c-.8 0-19.6-.9-41.4 10.6-35.7 19-51.7 56.4-58.7 84.4-18.4 73.1-44.6 123.9-55.7 145.6-3.3 6.4-5.3 10.2-6.2 12.8-1.8 4.9-.8 9.8 2.8 13 10.5 9.5 38.2-2.9 38.5-3 .6-.3 1.3-.6 2.2-1 13.9-6.3 55.1-25 69.8-84.5h56.7c.7 32.2 3.1 138.4 2.9 172.9h-141l-2.1 1.5c-23.1 16.9-30.5 63.2-30.8 65.2l-1.4 9.2h167c-12.3 78.3-26.5 113.4-34 127.4-3.7 7-7.3 14-10.7 20.8-21.3 42.2-43.4 85.8-126.3 153.6-3.6 2.8-7 8-4.8 13.7 2.4 6.3 9.3 9.1 24.6 9.1 5.4 0 11.8-.3 19.4-1 49.9-4.4 100.8-18 135.1-87.6 17-35.1 31.7-71.7 43.9-108.9L497 850l5-12c.8-1.9 19-46.3 5.1-95.9l-.5-1.8-108.1-123-22 16.6c6.4-26.1 10.6-49.9 12.5-71.1h158.7v-8c0-40.1-18.5-63.9-19.2-64.9l-2.4-3z">
                      </path>
                    </svg></i></a></div>
            </div>
          </div>
        </section>
      </div>
    </div>
  </div>



</template>

<script setup>
// JavaScript code here if needed
import { ElDropdownMenu, ElDropdownItem, ElDropdown} from 'element-plus';

</script>



<!-- ------------------------------抄来的css --------------------------------->

<style data-href="/styles.d401b3ad94880594b932.css">
body,
html {
  width: 100%;
  height: 100%
}

input::-ms-clear,
input::-ms-reveal {
  display: none
}

*,
:after,
:before {
  box-sizing: border-box
}

html {
  font-family: sans-serif;
  line-height: 1.15;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%;
  -ms-overflow-style: scrollbar;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
}

@-ms-viewport {
  width: device-width
}

article,
aside,
dialog,
figcaption,
figure,
footer,
header,
hgroup,
main,
nav,
section {
  display: block
}

body {
  margin: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol;
  font-variant: tabular-nums;
  line-height: 1.5;
  background-color: #fff;
  font-feature-settings: "tnum"
}

[tabindex="-1"]:focus {
  outline: none !important
}

.el-dropdown1{
  background-color: white;
  color: white;
}

hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin-top: 0;
  margin-bottom: .5em;
  color: rgba(0, 0, 0, .85);
  font-weight: 500
}

p {
  margin-top: 0;
  margin-bottom: 1em
}

abbr[data-original-title],
abbr[title] {
  text-decoration: underline;
  -webkit-text-decoration: underline dotted;
  text-decoration: underline dotted;
  border-bottom: 0;
  cursor: help
}

address {
  margin-bottom: 1em;
  font-style: normal;
  line-height: inherit
}

input[type=number],
input[type=password],
input[type=text],
textarea {
  -webkit-appearance: none
}

dl,
ol,
ul {
  margin-top: 0;
  margin-bottom: 1em
}

ol ol,
ol ul,
ul ol,
ul ul {
  margin-bottom: 0
}

dt {
  font-weight: 500
}

dd {
  margin-bottom: .5em;
  margin-left: 0
}

blockquote {
  margin: 0 0 1em
}

dfn {
  font-style: italic
}

b,
strong {
  font-weight: bolder
}

small {
  font-size: 80%
}

sub,
sup {
  position: relative;
  font-size: 75%;
  line-height: 0;
  vertical-align: baseline
}

sub {
  bottom: -.25em
}

sup {
  top: -.5em
}

a {
  color: #03a9f4;
  text-decoration: none;
  background-color: transparent;
  outline: none;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s;
  -webkit-text-decoration-skip: objects
}

a:hover {
  color: #2bc3ff
}

a:active {
  color: #0086cf
}

a:active,
a:hover {
  text-decoration: none;
  outline: 0
}

a[disabled] {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed;
  pointer-events: none
}

code,
kbd,
pre,
samp {
  font-size: 1em;
  font-family: SFMono-Regular, Consolas, Liberation Mono, Menlo, Courier, monospace
}

pre {
  margin-top: 0;
  margin-bottom: 1em;
  overflow: auto
}

figure {
  margin: 0 0 1em
}

img {
  vertical-align: middle;
  border-style: none
}

svg:not(:root) {
  overflow: hidden
}

[role=button],
a,
area,
button,
input:not([type=range]),
label,
select,
summary,
textarea {
  touch-action: manipulation
}

table {
  border-collapse: collapse
}

caption {
  padding-top: .75em;
  padding-bottom: .3em;
  color: rgba(0, 0, 0, .45);
  text-align: left;
  caption-side: bottom
}

th {
  text-align: inherit
}

button,
input,
optgroup,
select,
textarea {
  margin: 0;
  color: inherit;
  font-size: inherit;
  font-family: inherit;
  line-height: inherit
}

button,
input {
  overflow: visible
}

button,
select {
  text-transform: none
}

[type=reset],
[type=submit],
button,
html [type=button] {
  -webkit-appearance: button
}

[type=button]::-moz-focus-inner,
[type=reset]::-moz-focus-inner,
[type=submit]::-moz-focus-inner,
button::-moz-focus-inner {
  padding: 0;
  border-style: none
}

input[type=checkbox],
input[type=radio] {
  box-sizing: border-box;
  padding: 0
}

input[type=date],
input[type=datetime-local],
input[type=month],
input[type=time] {
  -webkit-appearance: listbox
}

textarea {
  overflow: auto;
  resize: vertical
}

fieldset {
  min-width: 0;
  margin: 0;
  padding: 0;
  border: 0
}

legend {
  display: block;
  width: 100%;
  max-width: 100%;
  margin-bottom: .5em;
  padding: 0;
  color: inherit;
  font-size: 1.5em;
  line-height: inherit;
  white-space: normal
}

progress {
  vertical-align: baseline
}

[type=number]::-webkit-inner-spin-button,
[type=number]::-webkit-outer-spin-button {
  height: auto
}

[type=search] {
  outline-offset: -2px;
  -webkit-appearance: none
}

[type=search]::-webkit-search-cancel-button,
[type=search]::-webkit-search-decoration {
  -webkit-appearance: none
}

::-webkit-file-upload-button {
  font: inherit;
  -webkit-appearance: button
}

output {
  display: inline-block
}

summary {
  display: list-item
}

template {
  display: none
}

[hidden] {
  display: none !important
}

mark {
  padding: .2em;
  background-color: #feffe6
}

::selection {
  color: #fff;
  background: #03a9f4
}

.clearfix {
  zoom: 1
}

.clearfix:after,
.clearfix:before {
  display: table;
  content: ""
}

.clearfix:after {
  clear: both
}

.anticon {
  display: inline-block;
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale
}

.anticon>* {
  line-height: 1
}

.anticon svg {
  display: inline-block
}

.anticon:before {
  display: none
}

.anticon .anticon-icon {
  display: block
}

.anticon[tabindex] {
  cursor: pointer
}

.anticon-spin,
.anticon-spin:before {
  display: inline-block;
  -webkit-animation: loadingCircle 1s linear infinite;
  animation: loadingCircle 1s linear infinite
}

.fade-appear,
.fade-enter,
.fade-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.fade-appear.fade-appear-active,
.fade-enter.fade-enter-active {
  -webkit-animation-name: antFadeIn;
  animation-name: antFadeIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.fade-leave.fade-leave-active {
  -webkit-animation-name: antFadeOut;
  animation-name: antFadeOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.fade-appear,
.fade-enter {
  opacity: 0
}

.fade-appear,
.fade-enter,
.fade-leave {
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear
}

@-webkit-keyframes antFadeIn {
  0% {
    opacity: 0
  }

  to {
    opacity: 1
  }
}

@keyframes antFadeIn {
  0% {
    opacity: 0
  }

  to {
    opacity: 1
  }
}

@-webkit-keyframes antFadeOut {
  0% {
    opacity: 1
  }

  to {
    opacity: 0
  }
}

@keyframes antFadeOut {
  0% {
    opacity: 1
  }

  to {
    opacity: 0
  }
}

.move-up-appear,
.move-up-enter,
.move-up-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.move-up-appear.move-up-appear-active,
.move-up-enter.move-up-enter-active {
  -webkit-animation-name: antMoveUpIn;
  animation-name: antMoveUpIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.move-up-leave.move-up-leave-active {
  -webkit-animation-name: antMoveUpOut;
  animation-name: antMoveUpOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.move-up-appear,
.move-up-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.move-up-leave {
  -webkit-animation-timing-function: cubic-bezier(.6, .04, .98, .34);
  animation-timing-function: cubic-bezier(.6, .04, .98, .34)
}

.move-down-appear,
.move-down-enter,
.move-down-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.move-down-appear.move-down-appear-active,
.move-down-enter.move-down-enter-active {
  -webkit-animation-name: antMoveDownIn;
  animation-name: antMoveDownIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.move-down-leave.move-down-leave-active {
  -webkit-animation-name: antMoveDownOut;
  animation-name: antMoveDownOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.move-down-appear,
.move-down-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.move-down-leave {
  -webkit-animation-timing-function: cubic-bezier(.6, .04, .98, .34);
  animation-timing-function: cubic-bezier(.6, .04, .98, .34)
}

.move-left-appear,
.move-left-enter,
.move-left-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.move-left-appear.move-left-appear-active,
.move-left-enter.move-left-enter-active {
  -webkit-animation-name: antMoveLeftIn;
  animation-name: antMoveLeftIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.move-left-leave.move-left-leave-active {
  -webkit-animation-name: antMoveLeftOut;
  animation-name: antMoveLeftOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.move-left-appear,
.move-left-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.move-left-leave {
  -webkit-animation-timing-function: cubic-bezier(.6, .04, .98, .34);
  animation-timing-function: cubic-bezier(.6, .04, .98, .34)
}

.move-right-appear,
.move-right-enter,
.move-right-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.move-right-appear.move-right-appear-active,
.move-right-enter.move-right-enter-active {
  -webkit-animation-name: antMoveRightIn;
  animation-name: antMoveRightIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.move-right-leave.move-right-leave-active {
  -webkit-animation-name: antMoveRightOut;
  animation-name: antMoveRightOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.move-right-appear,
.move-right-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.move-right-leave {
  -webkit-animation-timing-function: cubic-bezier(.6, .04, .98, .34);
  animation-timing-function: cubic-bezier(.6, .04, .98, .34)
}

@-webkit-keyframes antMoveDownIn {
  0% {
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antMoveDownIn {
  0% {
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antMoveDownOut {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antMoveDownOut {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateY(100%);
    transform: translateY(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes antMoveLeftIn {
  0% {
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antMoveLeftIn {
  0% {
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antMoveLeftOut {
  0% {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antMoveLeftOut {
  0% {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateX(-100%);
    transform: translateX(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes antMoveRightIn {
  0% {
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antMoveRightIn {
  0% {
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antMoveRightOut {
  0% {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antMoveRightOut {
  0% {
    -webkit-transform: translateX(0);
    transform: translateX(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes antMoveUpIn {
  0% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antMoveUpIn {
  0% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antMoveUpOut {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antMoveUpOut {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes loadingCircle {
  to {
    -webkit-transform: rotate(1turn);
    transform: rotate(1turn)
  }
}

@keyframes loadingCircle {
  to {
    -webkit-transform: rotate(1turn);
    transform: rotate(1turn)
  }
}

[ant-click-animating-without-extra-node=true],
[ant-click-animating=true] {
  position: relative
}

html {
  --antd-wave-shadow-color: #03a9f4
}

.ant-click-animating-node,
[ant-click-animating-without-extra-node=true]:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  display: block;
  border-radius: inherit;
  box-shadow: 0 0 0 0 #03a9f4;
  box-shadow: 0 0 0 0 var(--antd-wave-shadow-color);
  opacity: .2;
  -webkit-animation: fadeEffect 2s cubic-bezier(.08, .82, .17, 1), waveEffect .4s cubic-bezier(.08, .82, .17, 1);
  animation: fadeEffect 2s cubic-bezier(.08, .82, .17, 1), waveEffect .4s cubic-bezier(.08, .82, .17, 1);
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
  content: "";
  pointer-events: none
}

@-webkit-keyframes waveEffect {
  to {
    box-shadow: 0 0 0 #03a9f4;
    box-shadow: 0 0 0 6px var(--antd-wave-shadow-color)
  }
}

@keyframes waveEffect {
  to {
    box-shadow: 0 0 0 #03a9f4;
    box-shadow: 0 0 0 6px var(--antd-wave-shadow-color)
  }
}

@-webkit-keyframes fadeEffect {
  to {
    opacity: 0
  }
}

@keyframes fadeEffect {
  to {
    opacity: 0
  }
}

.slide-up-appear,
.slide-up-enter,
.slide-up-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.slide-up-appear.slide-up-appear-active,
.slide-up-enter.slide-up-enter-active {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.slide-up-leave.slide-up-leave-active {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.slide-up-appear,
.slide-up-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.23, 1, .32, 1);
  animation-timing-function: cubic-bezier(.23, 1, .32, 1)
}

.slide-up-leave {
  -webkit-animation-timing-function: cubic-bezier(.755, .05, .855, .06);
  animation-timing-function: cubic-bezier(.755, .05, .855, .06)
}

.slide-down-appear,
.slide-down-enter,
.slide-down-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.slide-down-appear.slide-down-appear-active,
.slide-down-enter.slide-down-enter-active {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.slide-down-leave.slide-down-leave-active {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.slide-down-appear,
.slide-down-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.23, 1, .32, 1);
  animation-timing-function: cubic-bezier(.23, 1, .32, 1)
}

.slide-down-leave {
  -webkit-animation-timing-function: cubic-bezier(.755, .05, .855, .06);
  animation-timing-function: cubic-bezier(.755, .05, .855, .06)
}

.slide-left-appear,
.slide-left-enter,
.slide-left-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.slide-left-appear.slide-left-appear-active,
.slide-left-enter.slide-left-enter-active {
  -webkit-animation-name: antSlideLeftIn;
  animation-name: antSlideLeftIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.slide-left-leave.slide-left-leave-active {
  -webkit-animation-name: antSlideLeftOut;
  animation-name: antSlideLeftOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.slide-left-appear,
.slide-left-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.23, 1, .32, 1);
  animation-timing-function: cubic-bezier(.23, 1, .32, 1)
}

.slide-left-leave {
  -webkit-animation-timing-function: cubic-bezier(.755, .05, .855, .06);
  animation-timing-function: cubic-bezier(.755, .05, .855, .06)
}

.slide-right-appear,
.slide-right-enter,
.slide-right-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.slide-right-appear.slide-right-appear-active,
.slide-right-enter.slide-right-enter-active {
  -webkit-animation-name: antSlideRightIn;
  animation-name: antSlideRightIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.slide-right-leave.slide-right-leave-active {
  -webkit-animation-name: antSlideRightOut;
  animation-name: antSlideRightOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.slide-right-appear,
.slide-right-enter {
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.23, 1, .32, 1);
  animation-timing-function: cubic-bezier(.23, 1, .32, 1)
}

.slide-right-leave {
  -webkit-animation-timing-function: cubic-bezier(.755, .05, .855, .06);
  animation-timing-function: cubic-bezier(.755, .05, .855, .06)
}

@-webkit-keyframes antSlideUpIn {
  0% {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antSlideUpIn {
  0% {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antSlideUpOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antSlideUpOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes antSlideDownIn {
  0% {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 1
  }
}

@keyframes antSlideDownIn {
  0% {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 1
  }
}

@-webkit-keyframes antSlideDownOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 0
  }
}

@keyframes antSlideDownOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(.8);
    transform: scaleY(.8);
    -webkit-transform-origin: 100% 100%;
    transform-origin: 100% 100%;
    opacity: 0
  }
}

@-webkit-keyframes antSlideLeftIn {
  0% {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antSlideLeftIn {
  0% {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antSlideLeftOut {
  0% {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antSlideLeftOut {
  0% {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@-webkit-keyframes antSlideRightIn {
  0% {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 1
  }
}

@keyframes antSlideRightIn {
  0% {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 1
  }
}

@-webkit-keyframes antSlideRightOut {
  0% {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 0
  }
}

@keyframes antSlideRightOut {
  0% {
    -webkit-transform: scaleX(1);
    transform: scaleX(1);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleX(.8);
    transform: scaleX(.8);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
    opacity: 0
  }
}

.swing-appear,
.swing-enter {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.swing-appear.swing-appear-active,
.swing-enter.swing-enter-active {
  -webkit-animation-name: antSwingIn;
  animation-name: antSwingIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

@-webkit-keyframes antSwingIn {

  0%,
  to {
    -webkit-transform: translateX(0);
    transform: translateX(0)
  }

  20% {
    -webkit-transform: translateX(-10px);
    transform: translateX(-10px)
  }

  40% {
    -webkit-transform: translateX(10px);
    transform: translateX(10px)
  }

  60% {
    -webkit-transform: translateX(-5px);
    transform: translateX(-5px)
  }

  80% {
    -webkit-transform: translateX(5px);
    transform: translateX(5px)
  }
}

@keyframes antSwingIn {

  0%,
  to {
    -webkit-transform: translateX(0);
    transform: translateX(0)
  }

  20% {
    -webkit-transform: translateX(-10px);
    transform: translateX(-10px)
  }

  40% {
    -webkit-transform: translateX(10px);
    transform: translateX(10px)
  }

  60% {
    -webkit-transform: translateX(-5px);
    transform: translateX(-5px)
  }

  80% {
    -webkit-transform: translateX(5px);
    transform: translateX(5px)
  }
}

.zoom-appear,
.zoom-enter,
.zoom-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-appear.zoom-appear-active,
.zoom-enter.zoom-enter-active {
  -webkit-animation-name: antZoomIn;
  animation-name: antZoomIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-leave.zoom-leave-active {
  -webkit-animation-name: antZoomOut;
  animation-name: antZoomOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-appear,
.zoom-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-big-appear,
.zoom-big-enter,
.zoom-big-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-big-appear.zoom-big-appear-active,
.zoom-big-enter.zoom-big-enter-active {
  -webkit-animation-name: antZoomBigIn;
  animation-name: antZoomBigIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-big-leave.zoom-big-leave-active {
  -webkit-animation-name: antZoomBigOut;
  animation-name: antZoomBigOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-big-appear,
.zoom-big-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-big-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-big-fast-appear,
.zoom-big-fast-enter,
.zoom-big-fast-leave {
  -webkit-animation-duration: .1s;
  animation-duration: .1s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-big-fast-appear.zoom-big-fast-appear-active,
.zoom-big-fast-enter.zoom-big-fast-enter-active {
  -webkit-animation-name: antZoomBigIn;
  animation-name: antZoomBigIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-big-fast-leave.zoom-big-fast-leave-active {
  -webkit-animation-name: antZoomBigOut;
  animation-name: antZoomBigOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-big-fast-appear,
.zoom-big-fast-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-big-fast-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-up-appear,
.zoom-up-enter,
.zoom-up-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-up-appear.zoom-up-appear-active,
.zoom-up-enter.zoom-up-enter-active {
  -webkit-animation-name: antZoomUpIn;
  animation-name: antZoomUpIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-up-leave.zoom-up-leave-active {
  -webkit-animation-name: antZoomUpOut;
  animation-name: antZoomUpOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-up-appear,
.zoom-up-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-up-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-down-appear,
.zoom-down-enter,
.zoom-down-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-down-appear.zoom-down-appear-active,
.zoom-down-enter.zoom-down-enter-active {
  -webkit-animation-name: antZoomDownIn;
  animation-name: antZoomDownIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-down-leave.zoom-down-leave-active {
  -webkit-animation-name: antZoomDownOut;
  animation-name: antZoomDownOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-down-appear,
.zoom-down-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-down-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-left-appear,
.zoom-left-enter,
.zoom-left-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-left-appear.zoom-left-appear-active,
.zoom-left-enter.zoom-left-enter-active {
  -webkit-animation-name: antZoomLeftIn;
  animation-name: antZoomLeftIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-left-leave.zoom-left-leave-active {
  -webkit-animation-name: antZoomLeftOut;
  animation-name: antZoomLeftOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-left-appear,
.zoom-left-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-left-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

.zoom-right-appear,
.zoom-right-enter,
.zoom-right-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.zoom-right-appear.zoom-right-appear-active,
.zoom-right-enter.zoom-right-enter-active {
  -webkit-animation-name: antZoomRightIn;
  animation-name: antZoomRightIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.zoom-right-leave.zoom-right-leave-active {
  -webkit-animation-name: antZoomRightOut;
  animation-name: antZoomRightOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.zoom-right-appear,
.zoom-right-enter {
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-animation-timing-function: cubic-bezier(.08, .82, .17, 1);
  animation-timing-function: cubic-bezier(.08, .82, .17, 1)
}

.zoom-right-leave {
  -webkit-animation-timing-function: cubic-bezier(.78, .14, .15, .86);
  animation-timing-function: cubic-bezier(.78, .14, .15, .86)
}

@-webkit-keyframes antZoomIn {
  0% {
    -webkit-transform: scale(.2);
    transform: scale(.2);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: 1
  }
}

@keyframes antZoomIn {
  0% {
    -webkit-transform: scale(.2);
    transform: scale(.2);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: 1
  }
}

@-webkit-keyframes antZoomOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(.2);
    transform: scale(.2);
    opacity: 0
  }
}

@keyframes antZoomOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(.2);
    transform: scale(.2);
    opacity: 0
  }
}

@-webkit-keyframes antZoomBigIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: 1
  }
}

@keyframes antZoomBigIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: 1
  }
}

@-webkit-keyframes antZoomBigOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: 0
  }
}

@keyframes antZoomBigOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: 0
  }
}

@-webkit-keyframes antZoomUpIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0
  }
}

@keyframes antZoomUpIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0
  }
}

@-webkit-keyframes antZoomUpOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0;
    opacity: 0
  }
}

@keyframes antZoomUpOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 0;
    transform-origin: 50% 0;
    opacity: 0
  }
}

@-webkit-keyframes antZoomLeftIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%
  }
}

@keyframes antZoomLeftIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%
  }
}

@-webkit-keyframes antZoomLeftOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%;
    opacity: 0
  }
}

@keyframes antZoomLeftOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 0 50%;
    transform-origin: 0 50%;
    opacity: 0
  }
}

@-webkit-keyframes antZoomRightIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%
  }
}

@keyframes antZoomRightIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%
  }
}

@-webkit-keyframes antZoomRightOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%;
    opacity: 0
  }
}

@keyframes antZoomRightOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 100% 50%;
    transform-origin: 100% 50%;
    opacity: 0
  }
}

@-webkit-keyframes antZoomDownIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%
  }
}

@keyframes antZoomDownIn {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%;
    opacity: 0
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%
  }
}

@-webkit-keyframes antZoomDownOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%;
    opacity: 0
  }
}

@keyframes antZoomDownOut {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%
  }

  to {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    -webkit-transform-origin: 50% 100%;
    transform-origin: 50% 100%;
    opacity: 0
  }
}

.ant-motion-collapse-legacy {
  overflow: hidden
}

.ant-motion-collapse,
.ant-motion-collapse-legacy-active {
  -webkit-transition: height .15s cubic-bezier(.645, .045, .355, 1), opacity .15s cubic-bezier(.645, .045, .355, 1) !important;
  transition: height .15s cubic-bezier(.645, .045, .355, 1), opacity .15s cubic-bezier(.645, .045, .355, 1) !important
}

.ant-motion-collapse {
  overflow: hidden
}

.ant-affix {
  position: fixed;
  z-index: 10
}

.ant-alert {
  box-sizing: border-box;
  margin: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  padding: 8px 15px 8px 37px;
  word-wrap: break-word;
  border-radius: 4px
}

.ant-alert.ant-alert-no-icon {
  padding: 8px 15px
}

.ant-alert.ant-alert-closable {
  padding-right: 30px
}

.ant-alert-icon {
  position: absolute;
  top: 11.5px;
  left: 16px
}

.ant-alert-description {
  display: none;
  font-size: 14px;
  line-height: 22px
}

.ant-alert-success {
  background-color: #f6ffed;
  border: 1px solid #b7eb8f
}

.ant-alert-success .ant-alert-icon {
  color: #52c41a
}

.ant-alert-info {
  background-color: #e6f7ff;
  border: 1px solid #91d5ff
}

.ant-alert-info .ant-alert-icon {
  color: #1890ff
}

.ant-alert-warning {
  background-color: #fffbe6;
  border: 1px solid #ffe58f
}

.ant-alert-warning .ant-alert-icon {
  color: #faad14
}

.ant-alert-error {
  background-color: #fff1f0;
  border: 1px solid #ffa39e
}

.ant-alert-error .ant-alert-icon {
  color: #f5222d
}

.ant-alert-close-icon {
  position: absolute;
  top: 8px;
  right: 16px;
  overflow: hidden;
  font-size: 12px;
  line-height: 22px;
  background-color: transparent;
  border: none;
  cursor: pointer
}

.ant-alert-close-icon .anticon-close {
  color: rgba(0, 0, 0, .45);
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-alert-close-icon .anticon-close:hover {
  color: rgba(0, 0, 0, .75)
}

.ant-alert-close-text {
  color: rgba(0, 0, 0, .45);
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-alert-close-text:hover {
  color: rgba(0, 0, 0, .75)
}

.ant-alert-with-description {
  position: relative;
  padding: 15px 15px 15px 64px;
  color: rgba(0, 0, 0, .65);
  line-height: 1.5;
  border-radius: 4px
}

.ant-alert-with-description.ant-alert-no-icon {
  padding: 15px
}

.ant-alert-with-description .ant-alert-icon {
  position: absolute;
  top: 16px;
  left: 24px;
  font-size: 24px
}

.ant-alert-with-description .ant-alert-close-icon {
  position: absolute;
  top: 16px;
  right: 16px;
  font-size: 14px;
  cursor: pointer
}

.ant-alert-with-description .ant-alert-message {
  display: block;
  margin-bottom: 4px;
  color: rgba(0, 0, 0, .85);
  font-size: 16px
}

.ant-alert-message {
  color: rgba(0, 0, 0, .85)
}

.ant-alert-with-description .ant-alert-description {
  display: block
}

.ant-alert.ant-alert-close {
  height: 0 !important;
  margin: 0;
  padding-top: 0;
  padding-bottom: 0;
  -webkit-transform-origin: 50% 0;
  transform-origin: 50% 0;
  -webkit-transition: all .3s cubic-bezier(.78, .14, .15, .86);
  transition: all .3s cubic-bezier(.78, .14, .15, .86)
}

.ant-alert-slide-up-leave {
  -webkit-animation: antAlertSlideUpOut .3s cubic-bezier(.78, .14, .15, .86);
  animation: antAlertSlideUpOut .3s cubic-bezier(.78, .14, .15, .86);
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both
}

.ant-alert-banner {
  margin-bottom: 0;
  border: 0;
  border-radius: 0
}

@-webkit-keyframes antAlertSlideUpIn {
  0% {
    -webkit-transform: scaleY(0);
    transform: scaleY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@keyframes antAlertSlideUpIn {
  0% {
    -webkit-transform: scaleY(0);
    transform: scaleY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }

  to {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }
}

@-webkit-keyframes antAlertSlideUpOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(0);
    transform: scaleY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

@keyframes antAlertSlideUpOut {
  0% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 1
  }

  to {
    -webkit-transform: scaleY(0);
    transform: scaleY(0);
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
    opacity: 0
  }
}

.ant-anchor {
  box-sizing: border-box;
  margin: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  padding: 0 0 0 2px
}

.ant-anchor-wrapper {
  margin-left: -4px;
  padding-left: 4px;
  overflow: auto;
  background-color: #fff
}

.ant-anchor-ink {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%
}

.ant-anchor-ink:before {
  position: relative;
  display: block;
  width: 2px;
  height: 100%;
  margin: 0 auto;
  background-color: #e8e8e8;
  content: " "
}

.ant-anchor-ink-ball {
  position: absolute;
  left: 50%;
  display: none;
  width: 8px;
  height: 8px;
  background-color: #fff;
  border: 2px solid #03a9f4;
  border-radius: 8px;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  -webkit-transition: top .3s ease-in-out;
  transition: top .3s ease-in-out
}

.ant-anchor-ink-ball.visible {
  display: inline-block
}

.ant-anchor.fixed .ant-anchor-ink .ant-anchor-ink-ball {
  display: none
}

.ant-anchor-link {
  padding: 7px 0 7px 16px;
  line-height: 1.143
}

.ant-anchor-link-title {
  position: relative;
  display: block;
  margin-bottom: 6px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  white-space: nowrap;
  text-overflow: ellipsis;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-anchor-link-title:only-child {
  margin-bottom: 0
}

.ant-anchor-link-active>.ant-anchor-link-title {
  color: #03a9f4
}

.ant-anchor-link .ant-anchor-link {
  padding-top: 5px;
  padding-bottom: 5px
}

.ant-select-auto-complete {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-select-auto-complete.ant-select .ant-select-selection {
  border: 0;
  box-shadow: none
}

.ant-select-auto-complete.ant-select .ant-select-selection__rendered {
  height: 100%;
  margin-right: 0;
  margin-left: 0;
  line-height: 32px
}

.ant-select-auto-complete.ant-select .ant-select-selection__placeholder {
  margin-right: 12px;
  margin-left: 12px
}

.ant-select-auto-complete.ant-select .ant-select-selection--single {
  height: auto
}

.ant-select-auto-complete.ant-select .ant-select-search--inline {
  position: static;
  float: left
}

.ant-select-auto-complete.ant-select-allow-clear .ant-select-selection:hover .ant-select-selection__rendered {
  margin-right: 0 !important
}

.ant-select-auto-complete.ant-select .ant-input {
  height: 32px;
  line-height: 1.5;
  background: transparent;
  border-width: 1px
}

.ant-select-auto-complete.ant-select .ant-input:focus,
.ant-select-auto-complete.ant-select .ant-input:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-select-auto-complete.ant-select .ant-input[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1;
  background-color: transparent
}

.ant-select-auto-complete.ant-select .ant-input[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-select-auto-complete.ant-select-lg .ant-select-selection__rendered {
  line-height: 40px
}

.ant-select-auto-complete.ant-select-lg .ant-input {
  height: 40px;
  padding-top: 6px;
  padding-bottom: 6px
}

.ant-select-auto-complete.ant-select-sm .ant-select-selection__rendered {
  line-height: 24px
}

.ant-select-auto-complete.ant-select-sm .ant-input {
  height: 24px;
  padding-top: 1px;
  padding-bottom: 1px
}

.ant-input-group>.ant-select-auto-complete .ant-select-search__field.ant-input-affix-wrapper {
  display: inline;
  float: none
}

.ant-avatar {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  overflow: hidden;
  color: #fff;
  white-space: nowrap;
  text-align: center;
  vertical-align: middle;
  background: #ccc;
  width: 32px;
  height: 32px;
  line-height: 32px;
  border-radius: 50%
}

.ant-avatar-image {
  background: transparent
}

.ant-avatar-string {
  position: absolute;
  left: 50%;
  -webkit-transform-origin: 0 center;
  transform-origin: 0 center
}

.ant-avatar.ant-avatar-icon {
  font-size: 18px
}

.ant-avatar-lg {
  width: 40px;
  height: 40px;
  line-height: 40px;
  border-radius: 50%
}

.ant-avatar-lg-string {
  position: absolute;
  left: 50%;
  -webkit-transform-origin: 0 center;
  transform-origin: 0 center
}

.ant-avatar-lg.ant-avatar-icon {
  font-size: 24px
}

.ant-avatar-sm {
  width: 24px;
  height: 24px;
  line-height: 24px;
  border-radius: 50%
}

.ant-avatar-sm-string {
  position: absolute;
  left: 50%;
  -webkit-transform-origin: 0 center;
  transform-origin: 0 center
}

.ant-avatar-sm.ant-avatar-icon {
  font-size: 14px
}

.ant-avatar-square {
  border-radius: 4px
}

.ant-avatar>img {
  display: block;
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover
}

.ant-back-top {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: fixed;
  right: 100px;
  bottom: 50px;
  z-index: 10;
  width: 40px;
  height: 40px;
  cursor: pointer
}

.ant-back-top-content {
  width: 40px;
  height: 40px;
  overflow: hidden;
  color: #fff;
  text-align: center;
  background-color: rgba(0, 0, 0, .45);
  border-radius: 20px
}

.ant-back-top-content,
.ant-back-top-content:hover {
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-back-top-content:hover {
  background-color: rgba(0, 0, 0, .65)
}

.ant-back-top-icon {
  width: 14px;
  height: 16px;
  margin: 12px auto;
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACQAAAAoCAYAAACWwljjAAAABGdBTUEAALGPC/xhBQAAAbtJREFUWAntmMtKw0AUhhMvS5cuxILgQlRUpIggIoKIIoigG1eC+AA+jo+i6FIXBfeuXIgoeKVeitVWJX5HWhhDksnUpp3FDPyZk3Nm5nycmZKkXhAEOXSA3lG7muTeRzmfy6HneUvIhnYkQK+Q9NhAA0Opg0vBEhjBKHiyb8iGMyQMOYuK41BcBSypAL+MYXSKjtFAW7EAGEO3qN4uMQbbAkXiSfRQJ1H6a+yhlkKRcAoVFYiweYNjtCVQJJpBz2GCiPt7fBOZQpFgDpUikse5HgnkM4Fi4QX0Fpc5wf9EbLqpUCy4jMoJSXWhFwbMNgWKhVbRhy5jirhs9fy/oFhgHVVTJEs7RLZ8sSEoJm6iz7SZDMbJ+/OKERQTttCXQRLToRUmrKWCYuA2+jbN0MB4OQobYShfdTCgn/sL1K36M7TLrN3n+758aPy2rrpR6+/od5E8tf/A1uLS9aId5T7J3CNYihkQ4D9PiMdMC7mp4rjB9kjFjZp8BlnVHJBuO1yFXIV0FdDF3RlyFdJVQBdv5AxVdIsq8apiZ2PyYO1EVykesGfZEESsCkweyR8MUW+V8uJ1gkYipmpdP1pm2aJVPEGzAAAAAElFTkSuQmCC) 100%/100% no-repeat
}

@media screen and (max-width:768px) {
  .ant-back-top {
    right: 60px
  }
}

@media screen and (max-width:480px) {
  .ant-back-top {
    right: 20px
  }
}

.ant-badge {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  color: unset;
  line-height: 1
}

.ant-badge-count {
  z-index: 10;
  min-width: 20px;
  height: 20px;
  padding: 0 6px;
  color: #fff;
  font-weight: 400;
  font-size: 12px;
  line-height: 20px;
  white-space: nowrap;
  text-align: center;
  background: #f5222d;
  border-radius: 10px;
  box-shadow: 0 0 0 1px #fff
}

.ant-badge-count a,
.ant-badge-count a:hover {
  color: #fff
}

.ant-badge-multiple-words {
  padding: 0 8px
}

.ant-badge-dot {
  z-index: 10;
  width: 6px;
  height: 6px;
  background: #f5222d;
  border-radius: 100%;
  box-shadow: 0 0 0 1px #fff
}

.ant-badge-count,
.ant-badge-dot,
.ant-badge .ant-scroll-number-custom-component {
  position: absolute;
  top: 0;
  right: 0;
  -webkit-transform: translate(50%, -50%);
  transform: translate(50%, -50%);
  -webkit-transform-origin: 100% 0;
  transform-origin: 100% 0
}

.ant-badge-status {
  line-height: inherit;
  vertical-align: baseline
}

.ant-badge-status-dot {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 6px;
  height: 6px;
  vertical-align: middle;
  border-radius: 50%
}

.ant-badge-status-success {
  background-color: #52c41a
}

.ant-badge-status-processing {
  position: relative;
  background-color: #1890ff
}

.ant-badge-status-processing:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #1890ff;
  border-radius: 50%;
  -webkit-animation: antStatusProcessing 1.2s ease-in-out infinite;
  animation: antStatusProcessing 1.2s ease-in-out infinite;
  content: ""
}

.ant-badge-status-default {
  background-color: #d9d9d9
}

.ant-badge-status-error {
  background-color: #f5222d
}

.ant-badge-status-warning {
  background-color: #faad14
}

.ant-badge-status-magenta,
.ant-badge-status-pink {
  background: #eb2f96
}

.ant-badge-status-red {
  background: #f5222d
}

.ant-badge-status-volcano {
  background: #fa541c
}

.ant-badge-status-orange {
  background: #fa8c16
}

.ant-badge-status-yellow {
  background: #fadb14
}

.ant-badge-status-gold {
  background: #faad14
}

.ant-badge-status-cyan {
  background: #13c2c2
}

.ant-badge-status-lime {
  background: #a0d911
}

.ant-badge-status-green {
  background: #52c41a
}

.ant-badge-status-blue {
  background: #1890ff
}

.ant-badge-status-geekblue {
  background: #2f54eb
}

.ant-badge-status-purple {
  background: #722ed1
}

.ant-badge-status-text {
  margin-left: 8px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px
}

.ant-badge-zoom-appear,
.ant-badge-zoom-enter {
  -webkit-animation: antZoomBadgeIn .3s cubic-bezier(.12, .4, .29, 1.46);
  animation: antZoomBadgeIn .3s cubic-bezier(.12, .4, .29, 1.46);
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both
}

.ant-badge-zoom-leave {
  -webkit-animation: antZoomBadgeOut .3s cubic-bezier(.71, -.46, .88, .6);
  animation: antZoomBadgeOut .3s cubic-bezier(.71, -.46, .88, .6);
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both
}

.ant-badge-not-a-wrapper:not(.ant-badge-status) {
  vertical-align: middle
}

.ant-badge-not-a-wrapper .ant-scroll-number {
  position: relative;
  top: auto;
  display: block
}

.ant-badge-not-a-wrapper .ant-badge-count {
  -webkit-transform: none;
  transform: none
}

@-webkit-keyframes antStatusProcessing {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: .5
  }

  to {
    -webkit-transform: scale(2.4);
    transform: scale(2.4);
    opacity: 0
  }
}

@keyframes antStatusProcessing {
  0% {
    -webkit-transform: scale(.8);
    transform: scale(.8);
    opacity: .5
  }

  to {
    -webkit-transform: scale(2.4);
    transform: scale(2.4);
    opacity: 0
  }
}

.ant-scroll-number {
  overflow: hidden
}

.ant-scroll-number-only {
  display: inline-block;
  height: 20px;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-scroll-number-only>p {
  height: 20px;
  margin: 0
}

.ant-scroll-number-symbol {
  vertical-align: top
}

@-webkit-keyframes antZoomBadgeIn {
  0% {
    -webkit-transform: scale(0) translate(50%, -50%);
    transform: scale(0) translate(50%, -50%);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1) translate(50%, -50%);
    transform: scale(1) translate(50%, -50%)
  }
}

@keyframes antZoomBadgeIn {
  0% {
    -webkit-transform: scale(0) translate(50%, -50%);
    transform: scale(0) translate(50%, -50%);
    opacity: 0
  }

  to {
    -webkit-transform: scale(1) translate(50%, -50%);
    transform: scale(1) translate(50%, -50%)
  }
}

@-webkit-keyframes antZoomBadgeOut {
  0% {
    -webkit-transform: scale(1) translate(50%, -50%);
    transform: scale(1) translate(50%, -50%)
  }

  to {
    -webkit-transform: scale(0) translate(50%, -50%);
    transform: scale(0) translate(50%, -50%);
    opacity: 0
  }
}

@keyframes antZoomBadgeOut {
  0% {
    -webkit-transform: scale(1) translate(50%, -50%);
    transform: scale(1) translate(50%, -50%)
  }

  to {
    -webkit-transform: scale(0) translate(50%, -50%);
    transform: scale(0) translate(50%, -50%);
    opacity: 0
  }
}

.ant-breadcrumb {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-breadcrumb .anticon {
  font-size: 14px
}

.ant-breadcrumb a {
  color: rgba(0, 0, 0, .45);
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-breadcrumb a:hover {
  color: #2bc3ff
}

.ant-breadcrumb>span:last-child,
.ant-breadcrumb>span:last-child a {
  color: rgba(0, 0, 0, .65)
}

.ant-breadcrumb>span:last-child .ant-breadcrumb-separator {
  display: none
}

.ant-breadcrumb-separator {
  margin: 0 8px;
  color: rgba(0, 0, 0, .45)
}

.ant-breadcrumb-link>.anticon+span,
.ant-breadcrumb-overlay-link>.anticon {
  margin-left: 4px
}

.ant-btn {
  line-height: 1.5;
  position: relative;
  display: inline-block;
  font-weight: 400;
  white-space: nowrap;
  text-align: center;
  background-image: none;
  box-shadow: 0 2px 0 rgba(0, 0, 0, .015);
  cursor: pointer;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  touch-action: manipulation;
  height: 32px;
  padding: 0 15px;
  font-size: 14px;
  border-radius: 4px;
  color: rgba(0, 0, 0, .65);
  background-color: #fff;
  border: 1px solid #d9d9d9
}

.ant-btn>.anticon {
  line-height: 1
}

.ant-btn,
.ant-btn:active,
.ant-btn:focus {
  outline: 0
}

.ant-btn:not([disabled]):hover {
  text-decoration: none
}

.ant-btn:not([disabled]):active {
  outline: 0;
  box-shadow: none
}

.ant-btn.disabled,
.ant-btn[disabled] {
  cursor: not-allowed
}

.ant-btn.disabled>*,
.ant-btn[disabled]>* {
  pointer-events: none
}

.ant-btn-lg {
  height: 40px;
  padding: 0 15px;
  font-size: 16px;
  border-radius: 4px
}

.ant-btn-sm {
  height: 24px;
  padding: 0 7px;
  font-size: 14px;
  border-radius: 4px
}

.ant-btn>a:only-child {
  color: currentColor
}

.ant-btn>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn:focus,
.ant-btn:hover {
  color: #2bc3ff;
  background-color: #fff;
  border-color: #2bc3ff
}

.ant-btn:focus>a:only-child,
.ant-btn:hover>a:only-child {
  color: currentColor
}

.ant-btn:focus>a:only-child:after,
.ant-btn:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn.active,
.ant-btn:active {
  color: #0086cf;
  background-color: #fff;
  border-color: #0086cf
}

.ant-btn.active>a:only-child,
.ant-btn:active>a:only-child {
  color: currentColor
}

.ant-btn.active>a:only-child:after,
.ant-btn:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-disabled,
.ant-btn-disabled.active,
.ant-btn-disabled:active,
.ant-btn-disabled:focus,
.ant-btn-disabled:hover,
.ant-btn.disabled,
.ant-btn.disabled.active,
.ant-btn.disabled:active,
.ant-btn.disabled:focus,
.ant-btn.disabled:hover,
.ant-btn[disabled],
.ant-btn[disabled].active,
.ant-btn[disabled]:active,
.ant-btn[disabled]:focus,
.ant-btn[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-disabled.active>a:only-child,
.ant-btn-disabled:active>a:only-child,
.ant-btn-disabled:focus>a:only-child,
.ant-btn-disabled:hover>a:only-child,
.ant-btn-disabled>a:only-child,
.ant-btn.disabled.active>a:only-child,
.ant-btn.disabled:active>a:only-child,
.ant-btn.disabled:focus>a:only-child,
.ant-btn.disabled:hover>a:only-child,
.ant-btn.disabled>a:only-child,
.ant-btn[disabled].active>a:only-child,
.ant-btn[disabled]:active>a:only-child,
.ant-btn[disabled]:focus>a:only-child,
.ant-btn[disabled]:hover>a:only-child,
.ant-btn[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-disabled.active>a:only-child:after,
.ant-btn-disabled:active>a:only-child:after,
.ant-btn-disabled:focus>a:only-child:after,
.ant-btn-disabled:hover>a:only-child:after,
.ant-btn-disabled>a:only-child:after,
.ant-btn.disabled.active>a:only-child:after,
.ant-btn.disabled:active>a:only-child:after,
.ant-btn.disabled:focus>a:only-child:after,
.ant-btn.disabled:hover>a:only-child:after,
.ant-btn.disabled>a:only-child:after,
.ant-btn[disabled].active>a:only-child:after,
.ant-btn[disabled]:active>a:only-child:after,
.ant-btn[disabled]:focus>a:only-child:after,
.ant-btn[disabled]:hover>a:only-child:after,
.ant-btn[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn.active,
.ant-btn:active,
.ant-btn:focus,
.ant-btn:hover {
  text-decoration: none;
  background: #fff
}

.ant-btn>i,
.ant-btn>span {
  display: inline-block;
  -webkit-transition: margin-left .3s cubic-bezier(.645, .045, .355, 1);
  transition: margin-left .3s cubic-bezier(.645, .045, .355, 1);
  pointer-events: none
}

.ant-btn-primary {
  color: #fff;
  background-color: #03a9f4;
  border-color: #03a9f4;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, .12);
  box-shadow: 0 2px 0 rgba(0, 0, 0, .045)
}

.ant-btn-primary>a:only-child {
  color: currentColor
}

.ant-btn-primary>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-primary:focus,
.ant-btn-primary:hover {
  color: #fff;
  background-color: #2bc3ff;
  border-color: #2bc3ff
}

.ant-btn-primary:focus>a:only-child,
.ant-btn-primary:hover>a:only-child {
  color: currentColor
}

.ant-btn-primary:focus>a:only-child:after,
.ant-btn-primary:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-primary.active,
.ant-btn-primary:active {
  color: #fff;
  background-color: #0086cf;
  border-color: #0086cf
}

.ant-btn-primary.active>a:only-child,
.ant-btn-primary:active>a:only-child {
  color: currentColor
}

.ant-btn-primary.active>a:only-child:after,
.ant-btn-primary:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-primary-disabled,
.ant-btn-primary-disabled.active,
.ant-btn-primary-disabled:active,
.ant-btn-primary-disabled:focus,
.ant-btn-primary-disabled:hover,
.ant-btn-primary.disabled,
.ant-btn-primary.disabled.active,
.ant-btn-primary.disabled:active,
.ant-btn-primary.disabled:focus,
.ant-btn-primary.disabled:hover,
.ant-btn-primary[disabled],
.ant-btn-primary[disabled].active,
.ant-btn-primary[disabled]:active,
.ant-btn-primary[disabled]:focus,
.ant-btn-primary[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-primary-disabled.active>a:only-child,
.ant-btn-primary-disabled:active>a:only-child,
.ant-btn-primary-disabled:focus>a:only-child,
.ant-btn-primary-disabled:hover>a:only-child,
.ant-btn-primary-disabled>a:only-child,
.ant-btn-primary.disabled.active>a:only-child,
.ant-btn-primary.disabled:active>a:only-child,
.ant-btn-primary.disabled:focus>a:only-child,
.ant-btn-primary.disabled:hover>a:only-child,
.ant-btn-primary.disabled>a:only-child,
.ant-btn-primary[disabled].active>a:only-child,
.ant-btn-primary[disabled]:active>a:only-child,
.ant-btn-primary[disabled]:focus>a:only-child,
.ant-btn-primary[disabled]:hover>a:only-child,
.ant-btn-primary[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-primary-disabled.active>a:only-child:after,
.ant-btn-primary-disabled:active>a:only-child:after,
.ant-btn-primary-disabled:focus>a:only-child:after,
.ant-btn-primary-disabled:hover>a:only-child:after,
.ant-btn-primary-disabled>a:only-child:after,
.ant-btn-primary.disabled.active>a:only-child:after,
.ant-btn-primary.disabled:active>a:only-child:after,
.ant-btn-primary.disabled:focus>a:only-child:after,
.ant-btn-primary.disabled:hover>a:only-child:after,
.ant-btn-primary.disabled>a:only-child:after,
.ant-btn-primary[disabled].active>a:only-child:after,
.ant-btn-primary[disabled]:active>a:only-child:after,
.ant-btn-primary[disabled]:focus>a:only-child:after,
.ant-btn-primary[disabled]:hover>a:only-child:after,
.ant-btn-primary[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-group .ant-btn-primary:not(:first-child):not(:last-child) {
  border-right-color: #2bc3ff;
  border-left-color: #2bc3ff
}

.ant-btn-group .ant-btn-primary:not(:first-child):not(:last-child):disabled {
  border-color: #d9d9d9
}

.ant-btn-group .ant-btn-primary:first-child:not(:last-child) {
  border-right-color: #2bc3ff
}

.ant-btn-group .ant-btn-primary:first-child:not(:last-child)[disabled] {
  border-right-color: #d9d9d9
}

.ant-btn-group .ant-btn-primary+.ant-btn-primary,
.ant-btn-group .ant-btn-primary:last-child:not(:first-child) {
  border-left-color: #2bc3ff
}

.ant-btn-group .ant-btn-primary+.ant-btn-primary[disabled],
.ant-btn-group .ant-btn-primary:last-child:not(:first-child)[disabled] {
  border-left-color: #d9d9d9
}

.ant-btn-ghost {
  color: rgba(0, 0, 0, .65);
  background-color: transparent;
  border-color: #d9d9d9
}

.ant-btn-ghost>a:only-child {
  color: currentColor
}

.ant-btn-ghost>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-ghost:focus,
.ant-btn-ghost:hover {
  color: #2bc3ff;
  background-color: transparent;
  border-color: #2bc3ff
}

.ant-btn-ghost:focus>a:only-child,
.ant-btn-ghost:hover>a:only-child {
  color: currentColor
}

.ant-btn-ghost:focus>a:only-child:after,
.ant-btn-ghost:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-ghost.active,
.ant-btn-ghost:active {
  color: #0086cf;
  background-color: transparent;
  border-color: #0086cf
}

.ant-btn-ghost.active>a:only-child,
.ant-btn-ghost:active>a:only-child {
  color: currentColor
}

.ant-btn-ghost.active>a:only-child:after,
.ant-btn-ghost:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-ghost-disabled,
.ant-btn-ghost-disabled.active,
.ant-btn-ghost-disabled:active,
.ant-btn-ghost-disabled:focus,
.ant-btn-ghost-disabled:hover,
.ant-btn-ghost.disabled,
.ant-btn-ghost.disabled.active,
.ant-btn-ghost.disabled:active,
.ant-btn-ghost.disabled:focus,
.ant-btn-ghost.disabled:hover,
.ant-btn-ghost[disabled],
.ant-btn-ghost[disabled].active,
.ant-btn-ghost[disabled]:active,
.ant-btn-ghost[disabled]:focus,
.ant-btn-ghost[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-ghost-disabled.active>a:only-child,
.ant-btn-ghost-disabled:active>a:only-child,
.ant-btn-ghost-disabled:focus>a:only-child,
.ant-btn-ghost-disabled:hover>a:only-child,
.ant-btn-ghost-disabled>a:only-child,
.ant-btn-ghost.disabled.active>a:only-child,
.ant-btn-ghost.disabled:active>a:only-child,
.ant-btn-ghost.disabled:focus>a:only-child,
.ant-btn-ghost.disabled:hover>a:only-child,
.ant-btn-ghost.disabled>a:only-child,
.ant-btn-ghost[disabled].active>a:only-child,
.ant-btn-ghost[disabled]:active>a:only-child,
.ant-btn-ghost[disabled]:focus>a:only-child,
.ant-btn-ghost[disabled]:hover>a:only-child,
.ant-btn-ghost[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-ghost-disabled.active>a:only-child:after,
.ant-btn-ghost-disabled:active>a:only-child:after,
.ant-btn-ghost-disabled:focus>a:only-child:after,
.ant-btn-ghost-disabled:hover>a:only-child:after,
.ant-btn-ghost-disabled>a:only-child:after,
.ant-btn-ghost.disabled.active>a:only-child:after,
.ant-btn-ghost.disabled:active>a:only-child:after,
.ant-btn-ghost.disabled:focus>a:only-child:after,
.ant-btn-ghost.disabled:hover>a:only-child:after,
.ant-btn-ghost.disabled>a:only-child:after,
.ant-btn-ghost[disabled].active>a:only-child:after,
.ant-btn-ghost[disabled]:active>a:only-child:after,
.ant-btn-ghost[disabled]:focus>a:only-child:after,
.ant-btn-ghost[disabled]:hover>a:only-child:after,
.ant-btn-ghost[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-dashed {
  color: rgba(0, 0, 0, .65);
  background-color: #fff;
  border-color: #d9d9d9;
  border-style: dashed
}

.ant-btn-dashed>a:only-child {
  color: currentColor
}

.ant-btn-dashed>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-dashed:focus,
.ant-btn-dashed:hover {
  color: #2bc3ff;
  background-color: #fff;
  border-color: #2bc3ff
}

.ant-btn-dashed:focus>a:only-child,
.ant-btn-dashed:hover>a:only-child {
  color: currentColor
}

.ant-btn-dashed:focus>a:only-child:after,
.ant-btn-dashed:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-dashed.active,
.ant-btn-dashed:active {
  color: #0086cf;
  background-color: #fff;
  border-color: #0086cf
}

.ant-btn-dashed.active>a:only-child,
.ant-btn-dashed:active>a:only-child {
  color: currentColor
}

.ant-btn-dashed.active>a:only-child:after,
.ant-btn-dashed:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-dashed-disabled,
.ant-btn-dashed-disabled.active,
.ant-btn-dashed-disabled:active,
.ant-btn-dashed-disabled:focus,
.ant-btn-dashed-disabled:hover,
.ant-btn-dashed.disabled,
.ant-btn-dashed.disabled.active,
.ant-btn-dashed.disabled:active,
.ant-btn-dashed.disabled:focus,
.ant-btn-dashed.disabled:hover,
.ant-btn-dashed[disabled],
.ant-btn-dashed[disabled].active,
.ant-btn-dashed[disabled]:active,
.ant-btn-dashed[disabled]:focus,
.ant-btn-dashed[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-dashed-disabled.active>a:only-child,
.ant-btn-dashed-disabled:active>a:only-child,
.ant-btn-dashed-disabled:focus>a:only-child,
.ant-btn-dashed-disabled:hover>a:only-child,
.ant-btn-dashed-disabled>a:only-child,
.ant-btn-dashed.disabled.active>a:only-child,
.ant-btn-dashed.disabled:active>a:only-child,
.ant-btn-dashed.disabled:focus>a:only-child,
.ant-btn-dashed.disabled:hover>a:only-child,
.ant-btn-dashed.disabled>a:only-child,
.ant-btn-dashed[disabled].active>a:only-child,
.ant-btn-dashed[disabled]:active>a:only-child,
.ant-btn-dashed[disabled]:focus>a:only-child,
.ant-btn-dashed[disabled]:hover>a:only-child,
.ant-btn-dashed[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-dashed-disabled.active>a:only-child:after,
.ant-btn-dashed-disabled:active>a:only-child:after,
.ant-btn-dashed-disabled:focus>a:only-child:after,
.ant-btn-dashed-disabled:hover>a:only-child:after,
.ant-btn-dashed-disabled>a:only-child:after,
.ant-btn-dashed.disabled.active>a:only-child:after,
.ant-btn-dashed.disabled:active>a:only-child:after,
.ant-btn-dashed.disabled:focus>a:only-child:after,
.ant-btn-dashed.disabled:hover>a:only-child:after,
.ant-btn-dashed.disabled>a:only-child:after,
.ant-btn-dashed[disabled].active>a:only-child:after,
.ant-btn-dashed[disabled]:active>a:only-child:after,
.ant-btn-dashed[disabled]:focus>a:only-child:after,
.ant-btn-dashed[disabled]:hover>a:only-child:after,
.ant-btn-dashed[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-danger {
  color: #fff;
  background-color: #ff4d4f;
  border-color: #ff4d4f;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, .12);
  box-shadow: 0 2px 0 rgba(0, 0, 0, .045)
}

.ant-btn-danger>a:only-child {
  color: currentColor
}

.ant-btn-danger>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-danger:focus,
.ant-btn-danger:hover {
  color: #fff;
  background-color: #ff7875;
  border-color: #ff7875
}

.ant-btn-danger:focus>a:only-child,
.ant-btn-danger:hover>a:only-child {
  color: currentColor
}

.ant-btn-danger:focus>a:only-child:after,
.ant-btn-danger:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-danger.active,
.ant-btn-danger:active {
  color: #fff;
  background-color: #d9363e;
  border-color: #d9363e
}

.ant-btn-danger.active>a:only-child,
.ant-btn-danger:active>a:only-child {
  color: currentColor
}

.ant-btn-danger.active>a:only-child:after,
.ant-btn-danger:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-danger-disabled,
.ant-btn-danger-disabled.active,
.ant-btn-danger-disabled:active,
.ant-btn-danger-disabled:focus,
.ant-btn-danger-disabled:hover,
.ant-btn-danger.disabled,
.ant-btn-danger.disabled.active,
.ant-btn-danger.disabled:active,
.ant-btn-danger.disabled:focus,
.ant-btn-danger.disabled:hover,
.ant-btn-danger[disabled],
.ant-btn-danger[disabled].active,
.ant-btn-danger[disabled]:active,
.ant-btn-danger[disabled]:focus,
.ant-btn-danger[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-danger-disabled.active>a:only-child,
.ant-btn-danger-disabled:active>a:only-child,
.ant-btn-danger-disabled:focus>a:only-child,
.ant-btn-danger-disabled:hover>a:only-child,
.ant-btn-danger-disabled>a:only-child,
.ant-btn-danger.disabled.active>a:only-child,
.ant-btn-danger.disabled:active>a:only-child,
.ant-btn-danger.disabled:focus>a:only-child,
.ant-btn-danger.disabled:hover>a:only-child,
.ant-btn-danger.disabled>a:only-child,
.ant-btn-danger[disabled].active>a:only-child,
.ant-btn-danger[disabled]:active>a:only-child,
.ant-btn-danger[disabled]:focus>a:only-child,
.ant-btn-danger[disabled]:hover>a:only-child,
.ant-btn-danger[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-danger-disabled.active>a:only-child:after,
.ant-btn-danger-disabled:active>a:only-child:after,
.ant-btn-danger-disabled:focus>a:only-child:after,
.ant-btn-danger-disabled:hover>a:only-child:after,
.ant-btn-danger-disabled>a:only-child:after,
.ant-btn-danger.disabled.active>a:only-child:after,
.ant-btn-danger.disabled:active>a:only-child:after,
.ant-btn-danger.disabled:focus>a:only-child:after,
.ant-btn-danger.disabled:hover>a:only-child:after,
.ant-btn-danger.disabled>a:only-child:after,
.ant-btn-danger[disabled].active>a:only-child:after,
.ant-btn-danger[disabled]:active>a:only-child:after,
.ant-btn-danger[disabled]:focus>a:only-child:after,
.ant-btn-danger[disabled]:hover>a:only-child:after,
.ant-btn-danger[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-link {
  color: #03a9f4;
  background-color: transparent;
  border-color: transparent;
  box-shadow: none
}

.ant-btn-link>a:only-child {
  color: currentColor
}

.ant-btn-link>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-link:focus,
.ant-btn-link:hover {
  color: #2bc3ff;
  background-color: transparent;
  border-color: #2bc3ff
}

.ant-btn-link:focus>a:only-child,
.ant-btn-link:hover>a:only-child {
  color: currentColor
}

.ant-btn-link:focus>a:only-child:after,
.ant-btn-link:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-link.active,
.ant-btn-link:active {
  color: #0086cf;
  background-color: transparent;
  border-color: #0086cf
}

.ant-btn-link.active>a:only-child,
.ant-btn-link:active>a:only-child {
  color: currentColor
}

.ant-btn-link.active>a:only-child:after,
.ant-btn-link:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-link-disabled,
.ant-btn-link-disabled.active,
.ant-btn-link-disabled:active,
.ant-btn-link-disabled:focus,
.ant-btn-link-disabled:hover,
.ant-btn-link.disabled,
.ant-btn-link.disabled.active,
.ant-btn-link.disabled:active,
.ant-btn-link.disabled:focus,
.ant-btn-link.disabled:hover,
.ant-btn-link[disabled],
.ant-btn-link[disabled].active,
.ant-btn-link[disabled]:active,
.ant-btn-link[disabled]:focus,
.ant-btn-link[disabled]:hover {
  background-color: #f5f5f5;
  border-color: #d9d9d9
}

.ant-btn-link:active,
.ant-btn-link:focus,
.ant-btn-link:hover {
  border-color: transparent
}

.ant-btn-link-disabled,
.ant-btn-link-disabled.active,
.ant-btn-link-disabled:active,
.ant-btn-link-disabled:focus,
.ant-btn-link-disabled:hover,
.ant-btn-link.disabled,
.ant-btn-link.disabled.active,
.ant-btn-link.disabled:active,
.ant-btn-link.disabled:focus,
.ant-btn-link.disabled:hover,
.ant-btn-link[disabled],
.ant-btn-link[disabled].active,
.ant-btn-link[disabled]:active,
.ant-btn-link[disabled]:focus,
.ant-btn-link[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: transparent;
  border-color: transparent;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-link-disabled.active>a:only-child,
.ant-btn-link-disabled:active>a:only-child,
.ant-btn-link-disabled:focus>a:only-child,
.ant-btn-link-disabled:hover>a:only-child,
.ant-btn-link-disabled>a:only-child,
.ant-btn-link.disabled.active>a:only-child,
.ant-btn-link.disabled:active>a:only-child,
.ant-btn-link.disabled:focus>a:only-child,
.ant-btn-link.disabled:hover>a:only-child,
.ant-btn-link.disabled>a:only-child,
.ant-btn-link[disabled].active>a:only-child,
.ant-btn-link[disabled]:active>a:only-child,
.ant-btn-link[disabled]:focus>a:only-child,
.ant-btn-link[disabled]:hover>a:only-child,
.ant-btn-link[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-link-disabled.active>a:only-child:after,
.ant-btn-link-disabled:active>a:only-child:after,
.ant-btn-link-disabled:focus>a:only-child:after,
.ant-btn-link-disabled:hover>a:only-child:after,
.ant-btn-link-disabled>a:only-child:after,
.ant-btn-link.disabled.active>a:only-child:after,
.ant-btn-link.disabled:active>a:only-child:after,
.ant-btn-link.disabled:focus>a:only-child:after,
.ant-btn-link.disabled:hover>a:only-child:after,
.ant-btn-link.disabled>a:only-child:after,
.ant-btn-link[disabled].active>a:only-child:after,
.ant-btn-link[disabled]:active>a:only-child:after,
.ant-btn-link[disabled]:focus>a:only-child:after,
.ant-btn-link[disabled]:hover>a:only-child:after,
.ant-btn-link[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-icon-only {
  width: 32px;
  height: 32px;
  padding: 0;
  font-size: 16px;
  border-radius: 4px
}

.ant-btn-icon-only.ant-btn-lg {
  width: 40px;
  height: 40px;
  padding: 0;
  font-size: 18px;
  border-radius: 4px
}

.ant-btn-icon-only.ant-btn-sm {
  width: 24px;
  height: 24px;
  padding: 0;
  font-size: 14px;
  border-radius: 4px
}

.ant-btn-round {
  height: 32px;
  padding: 0 16px;
  font-size: 14px;
  border-radius: 32px
}

.ant-btn-round.ant-btn-lg {
  height: 40px;
  padding: 0 20px;
  font-size: 16px;
  border-radius: 40px
}

.ant-btn-round.ant-btn-sm {
  height: 24px;
  padding: 0 12px;
  font-size: 14px;
  border-radius: 24px
}

.ant-btn-round.ant-btn-icon-only {
  width: auto
}

.ant-btn-circle,
.ant-btn-circle-outline {
  min-width: 32px;
  padding-right: 0;
  padding-left: 0;
  text-align: center;
  border-radius: 50%
}

.ant-btn-circle-outline.ant-btn-lg,
.ant-btn-circle.ant-btn-lg {
  min-width: 40px;
  border-radius: 50%
}

.ant-btn-circle-outline.ant-btn-sm,
.ant-btn-circle.ant-btn-sm {
  min-width: 24px;
  border-radius: 50%
}

.ant-btn:before {
  position: absolute;
  top: -1px;
  right: -1px;
  bottom: -1px;
  left: -1px;
  z-index: 1;
  display: none;
  background: #fff;
  border-radius: inherit;
  opacity: .35;
  -webkit-transition: opacity .2s;
  transition: opacity .2s;
  content: "";
  pointer-events: none
}

.ant-btn .anticon {
  -webkit-transition: margin-left .3s cubic-bezier(.645, .045, .355, 1);
  transition: margin-left .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-btn .anticon.anticon-minus>svg,
.ant-btn .anticon.anticon-plus>svg {
  shape-rendering: optimizeSpeed
}

.ant-btn.ant-btn-loading {
  position: relative;
  pointer-events: none
}

.ant-btn.ant-btn-loading:before {
  display: block
}

.ant-btn.ant-btn-loading:not(.ant-btn-circle):not(.ant-btn-circle-outline):not(.ant-btn-icon-only) {
  padding-left: 29px
}

.ant-btn.ant-btn-loading:not(.ant-btn-circle):not(.ant-btn-circle-outline):not(.ant-btn-icon-only) .anticon:not(:last-child) {
  margin-left: -14px
}

.ant-btn-sm.ant-btn-loading:not(.ant-btn-circle):not(.ant-btn-circle-outline):not(.ant-btn-icon-only) {
  padding-left: 24px
}

.ant-btn-sm.ant-btn-loading:not(.ant-btn-circle):not(.ant-btn-circle-outline):not(.ant-btn-icon-only) .anticon {
  margin-left: -17px
}

.ant-btn-group {
  display: inline-block
}

.ant-btn-group,
.ant-btn-group>.ant-btn,
.ant-btn-group>span>.ant-btn {
  position: relative
}

.ant-btn-group>.ant-btn.active,
.ant-btn-group>.ant-btn:active,
.ant-btn-group>.ant-btn:focus,
.ant-btn-group>.ant-btn:hover,
.ant-btn-group>span>.ant-btn.active,
.ant-btn-group>span>.ant-btn:active,
.ant-btn-group>span>.ant-btn:focus,
.ant-btn-group>span>.ant-btn:hover {
  z-index: 2
}

.ant-btn-group>.ant-btn:disabled,
.ant-btn-group>span>.ant-btn:disabled {
  z-index: 0
}

.ant-btn-group-lg>.ant-btn,
.ant-btn-group-lg>span>.ant-btn {
  height: 40px;
  padding: 0 15px;
  font-size: 16px;
  border-radius: 0;
  line-height: 38px
}

.ant-btn-group-lg>.ant-btn.ant-btn-icon-only {
  width: 40px;
  height: 40px;
  padding-right: 0;
  padding-left: 0
}

.ant-btn-group-sm>.ant-btn,
.ant-btn-group-sm>span>.ant-btn {
  height: 24px;
  padding: 0 7px;
  font-size: 14px;
  border-radius: 0;
  line-height: 22px
}

.ant-btn-group-sm>.ant-btn>.anticon,
.ant-btn-group-sm>span>.ant-btn>.anticon {
  font-size: 14px
}

.ant-btn-group-sm>.ant-btn.ant-btn-icon-only {
  width: 24px;
  height: 24px;
  padding-right: 0;
  padding-left: 0
}

.ant-btn+.ant-btn-group,
.ant-btn-group+.ant-btn,
.ant-btn-group+.ant-btn-group,
.ant-btn-group .ant-btn+.ant-btn,
.ant-btn-group .ant-btn+span,
.ant-btn-group>span+span,
.ant-btn-group span+.ant-btn {
  margin-left: -1px
}

.ant-btn-group .ant-btn-primary+.ant-btn:not(.ant-btn-primary):not([disabled]) {
  border-left-color: transparent
}

.ant-btn-group .ant-btn {
  border-radius: 0
}

.ant-btn-group>.ant-btn:first-child,
.ant-btn-group>span:first-child>.ant-btn {
  margin-left: 0
}

.ant-btn-group>.ant-btn:only-child,
.ant-btn-group>span:only-child>.ant-btn {
  border-radius: 4px
}

.ant-btn-group>.ant-btn:first-child:not(:last-child),
.ant-btn-group>span:first-child:not(:last-child)>.ant-btn {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px
}

.ant-btn-group>.ant-btn:last-child:not(:first-child),
.ant-btn-group>span:last-child:not(:first-child)>.ant-btn {
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px
}

.ant-btn-group-sm>.ant-btn:only-child,
.ant-btn-group-sm>span:only-child>.ant-btn {
  border-radius: 4px
}

.ant-btn-group-sm>.ant-btn:first-child:not(:last-child),
.ant-btn-group-sm>span:first-child:not(:last-child)>.ant-btn {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px
}

.ant-btn-group-sm>.ant-btn:last-child:not(:first-child),
.ant-btn-group-sm>span:last-child:not(:first-child)>.ant-btn {
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px
}

.ant-btn-group>.ant-btn-group {
  float: left
}

.ant-btn-group>.ant-btn-group:not(:first-child):not(:last-child)>.ant-btn {
  border-radius: 0
}

.ant-btn-group>.ant-btn-group:first-child:not(:last-child)>.ant-btn:last-child {
  padding-right: 8px;
  border-top-right-radius: 0;
  border-bottom-right-radius: 0
}

.ant-btn-group>.ant-btn-group:last-child:not(:first-child)>.ant-btn:first-child {
  padding-left: 8px;
  border-top-left-radius: 0;
  border-bottom-left-radius: 0
}

.ant-btn:active>span,
.ant-btn:focus>span {
  position: relative
}

.ant-btn>.anticon+span,
.ant-btn>span+.anticon {
  margin-left: 8px
}

.ant-btn-background-ghost {
  color: #fff;
  background: transparent !important;
  border-color: #fff
}

.ant-btn-background-ghost.ant-btn-primary {
  color: #03a9f4;
  background-color: transparent;
  border-color: #03a9f4;
  text-shadow: none
}

.ant-btn-background-ghost.ant-btn-primary>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-primary>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-primary:focus,
.ant-btn-background-ghost.ant-btn-primary:hover {
  color: #2bc3ff;
  background-color: transparent;
  border-color: #2bc3ff
}

.ant-btn-background-ghost.ant-btn-primary:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-primary:hover>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-primary:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-primary.active,
.ant-btn-background-ghost.ant-btn-primary:active {
  color: #0086cf;
  background-color: transparent;
  border-color: #0086cf
}

.ant-btn-background-ghost.ant-btn-primary.active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary:active>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-primary.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-primary-disabled,
.ant-btn-background-ghost.ant-btn-primary-disabled.active,
.ant-btn-background-ghost.ant-btn-primary-disabled:active,
.ant-btn-background-ghost.ant-btn-primary-disabled:focus,
.ant-btn-background-ghost.ant-btn-primary-disabled:hover,
.ant-btn-background-ghost.ant-btn-primary.disabled,
.ant-btn-background-ghost.ant-btn-primary.disabled.active,
.ant-btn-background-ghost.ant-btn-primary.disabled:active,
.ant-btn-background-ghost.ant-btn-primary.disabled:focus,
.ant-btn-background-ghost.ant-btn-primary.disabled:hover,
.ant-btn-background-ghost.ant-btn-primary[disabled],
.ant-btn-background-ghost.ant-btn-primary[disabled].active,
.ant-btn-background-ghost.ant-btn-primary[disabled]:active,
.ant-btn-background-ghost.ant-btn-primary[disabled]:focus,
.ant-btn-background-ghost.ant-btn-primary[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-background-ghost.ant-btn-primary-disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary-disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary-disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-primary-disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-primary-disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-primary.disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary.disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary.disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-primary.disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-primary.disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-primary[disabled].active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary[disabled]:active>a:only-child,
.ant-btn-background-ghost.ant-btn-primary[disabled]:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-primary[disabled]:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-primary[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-primary-disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary-disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary-disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary-disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary-disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary.disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary.disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary.disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary.disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary.disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary[disabled].active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary[disabled]:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary[disabled]:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary[disabled]:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-primary[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-danger {
  color: #ff4d4f;
  background-color: transparent;
  border-color: #ff4d4f;
  text-shadow: none
}

.ant-btn-background-ghost.ant-btn-danger>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-danger>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-danger:focus,
.ant-btn-background-ghost.ant-btn-danger:hover {
  color: #ff7875;
  background-color: transparent;
  border-color: #ff7875
}

.ant-btn-background-ghost.ant-btn-danger:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-danger:hover>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-danger:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-danger.active,
.ant-btn-background-ghost.ant-btn-danger:active {
  color: #d9363e;
  background-color: transparent;
  border-color: #d9363e
}

.ant-btn-background-ghost.ant-btn-danger.active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger:active>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-danger.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-danger-disabled,
.ant-btn-background-ghost.ant-btn-danger-disabled.active,
.ant-btn-background-ghost.ant-btn-danger-disabled:active,
.ant-btn-background-ghost.ant-btn-danger-disabled:focus,
.ant-btn-background-ghost.ant-btn-danger-disabled:hover,
.ant-btn-background-ghost.ant-btn-danger.disabled,
.ant-btn-background-ghost.ant-btn-danger.disabled.active,
.ant-btn-background-ghost.ant-btn-danger.disabled:active,
.ant-btn-background-ghost.ant-btn-danger.disabled:focus,
.ant-btn-background-ghost.ant-btn-danger.disabled:hover,
.ant-btn-background-ghost.ant-btn-danger[disabled],
.ant-btn-background-ghost.ant-btn-danger[disabled].active,
.ant-btn-background-ghost.ant-btn-danger[disabled]:active,
.ant-btn-background-ghost.ant-btn-danger[disabled]:focus,
.ant-btn-background-ghost.ant-btn-danger[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-background-ghost.ant-btn-danger-disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger-disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger-disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-danger-disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-danger-disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-danger.disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger.disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger.disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-danger.disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-danger.disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-danger[disabled].active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger[disabled]:active>a:only-child,
.ant-btn-background-ghost.ant-btn-danger[disabled]:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-danger[disabled]:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-danger[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-danger-disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger-disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger-disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger-disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger-disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger.disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger.disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger.disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger.disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger.disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger[disabled].active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger[disabled]:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger[disabled]:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger[disabled]:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-danger[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-link {
  color: #03a9f4;
  background-color: transparent;
  border-color: transparent;
  text-shadow: none;
  color: #fff
}

.ant-btn-background-ghost.ant-btn-link>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-link>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-link:focus,
.ant-btn-background-ghost.ant-btn-link:hover {
  color: #2bc3ff;
  background-color: transparent;
  border-color: transparent
}

.ant-btn-background-ghost.ant-btn-link:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-link:hover>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-link:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-link.active,
.ant-btn-background-ghost.ant-btn-link:active {
  color: #0086cf;
  background-color: transparent;
  border-color: transparent
}

.ant-btn-background-ghost.ant-btn-link.active>a:only-child,
.ant-btn-background-ghost.ant-btn-link:active>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-link.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-background-ghost.ant-btn-link-disabled,
.ant-btn-background-ghost.ant-btn-link-disabled.active,
.ant-btn-background-ghost.ant-btn-link-disabled:active,
.ant-btn-background-ghost.ant-btn-link-disabled:focus,
.ant-btn-background-ghost.ant-btn-link-disabled:hover,
.ant-btn-background-ghost.ant-btn-link.disabled,
.ant-btn-background-ghost.ant-btn-link.disabled.active,
.ant-btn-background-ghost.ant-btn-link.disabled:active,
.ant-btn-background-ghost.ant-btn-link.disabled:focus,
.ant-btn-background-ghost.ant-btn-link.disabled:hover,
.ant-btn-background-ghost.ant-btn-link[disabled],
.ant-btn-background-ghost.ant-btn-link[disabled].active,
.ant-btn-background-ghost.ant-btn-link[disabled]:active,
.ant-btn-background-ghost.ant-btn-link[disabled]:focus,
.ant-btn-background-ghost.ant-btn-link[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-btn-background-ghost.ant-btn-link-disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-link-disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-link-disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-link-disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-link-disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-link.disabled.active>a:only-child,
.ant-btn-background-ghost.ant-btn-link.disabled:active>a:only-child,
.ant-btn-background-ghost.ant-btn-link.disabled:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-link.disabled:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-link.disabled>a:only-child,
.ant-btn-background-ghost.ant-btn-link[disabled].active>a:only-child,
.ant-btn-background-ghost.ant-btn-link[disabled]:active>a:only-child,
.ant-btn-background-ghost.ant-btn-link[disabled]:focus>a:only-child,
.ant-btn-background-ghost.ant-btn-link[disabled]:hover>a:only-child,
.ant-btn-background-ghost.ant-btn-link[disabled]>a:only-child {
  color: currentColor
}

.ant-btn-background-ghost.ant-btn-link-disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link-disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link-disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link-disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link-disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link.disabled.active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link.disabled:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link.disabled:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link.disabled:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link.disabled>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link[disabled].active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link[disabled]:active>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link[disabled]:focus>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link[disabled]:hover>a:only-child:after,
.ant-btn-background-ghost.ant-btn-link[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-btn-two-chinese-chars:first-letter {
  letter-spacing: .34em
}

.ant-btn-two-chinese-chars>:not(.anticon) {
  margin-right: -.34em;
  letter-spacing: .34em
}

.ant-btn-block {
  width: 100%
}

.ant-btn:empty {
  vertical-align: top
}

a.ant-btn {
  padding-top: .1px;
  line-height: 30px
}

a.ant-btn-lg {
  line-height: 38px
}

a.ant-btn-sm {
  line-height: 22px
}

.ant-fullcalendar {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  border-top: 1px solid #d9d9d9;
  outline: none
}

.ant-select.ant-fullcalendar-year-select {
  min-width: 90px
}

.ant-select.ant-fullcalendar-year-select.ant-select-sm {
  min-width: 70px
}

.ant-select.ant-fullcalendar-month-select {
  min-width: 80px;
  margin-left: 8px
}

.ant-select.ant-fullcalendar-month-select.ant-select-sm {
  min-width: 70px
}

.ant-fullcalendar-header {
  padding: 11px 16px 11px 0;
  text-align: right
}

.ant-fullcalendar-header .ant-select-dropdown {
  text-align: left
}

.ant-fullcalendar-header .ant-radio-group {
  margin-left: 8px;
  text-align: left
}

.ant-fullcalendar-header label.ant-radio-button {
  height: 22px;
  padding: 0 10px;
  line-height: 20px
}

.ant-fullcalendar-date-panel {
  position: relative;
  outline: none
}

.ant-fullcalendar-calendar-body {
  padding: 8px 12px
}

.ant-fullcalendar table {
  width: 100%;
  max-width: 100%;
  height: 256px;
  background-color: transparent;
  border-collapse: collapse
}

.ant-fullcalendar table,
.ant-fullcalendar td,
.ant-fullcalendar th {
  border: 0
}

.ant-fullcalendar td {
  position: relative
}

.ant-fullcalendar-calendar-table {
  margin-bottom: 0;
  border-spacing: 0
}

.ant-fullcalendar-column-header {
  width: 33px;
  padding: 0;
  line-height: 18px;
  text-align: center
}

.ant-fullcalendar-column-header .ant-fullcalendar-column-header-inner {
  display: block;
  font-weight: 400
}

.ant-fullcalendar-week-number-header .ant-fullcalendar-column-header-inner {
  display: none
}

.ant-fullcalendar-date,
.ant-fullcalendar-month {
  text-align: center;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-fullcalendar-value {
  display: block;
  width: 24px;
  height: 24px;
  margin: 0 auto;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  line-height: 24px;
  background: transparent;
  border-radius: 2px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-fullcalendar-value:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-fullcalendar-value:active {
  color: #fff;
  background: #03a9f4
}

.ant-fullcalendar-month-panel-cell .ant-fullcalendar-value {
  width: 48px
}

.ant-fullcalendar-month-panel-current-cell .ant-fullcalendar-value,
.ant-fullcalendar-today .ant-fullcalendar-value {
  box-shadow: inset 0 0 0 1px #03a9f4
}

.ant-fullcalendar-month-panel-selected-cell .ant-fullcalendar-value,
.ant-fullcalendar-selected-day .ant-fullcalendar-value {
  color: #fff;
  background: #03a9f4
}

.ant-fullcalendar-disabled-cell-first-of-row .ant-fullcalendar-value {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px
}

.ant-fullcalendar-disabled-cell-last-of-row .ant-fullcalendar-value {
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px
}

.ant-fullcalendar-last-month-cell .ant-fullcalendar-value,
.ant-fullcalendar-next-month-btn-day .ant-fullcalendar-value {
  color: rgba(0, 0, 0, .25)
}

.ant-fullcalendar-month-panel-table {
  width: 100%;
  table-layout: fixed;
  border-collapse: separate
}

.ant-fullcalendar-content {
  position: absolute;
  bottom: -9px;
  left: 0;
  width: 100%
}

.ant-fullcalendar-fullscreen {
  border-top: 0
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-table {
  table-layout: fixed
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-header .ant-radio-group {
  margin-left: 16px
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-header label.ant-radio-button {
  height: 32px;
  line-height: 30px
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-date,
.ant-fullcalendar-fullscreen .ant-fullcalendar-month {
  display: block;
  height: 116px;
  margin: 0 4px;
  padding: 4px 8px;
  color: rgba(0, 0, 0, .65);
  text-align: left;
  border-top: 2px solid #e8e8e8;
  -webkit-transition: background .3s;
  transition: background .3s
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-date:hover,
.ant-fullcalendar-fullscreen .ant-fullcalendar-month:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-date:active,
.ant-fullcalendar-fullscreen .ant-fullcalendar-month:active {
  background: #a6efff
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-column-header {
  padding-right: 12px;
  padding-bottom: 5px;
  text-align: right
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-value {
  width: auto;
  text-align: right;
  background: transparent
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-today .ant-fullcalendar-value {
  color: rgba(0, 0, 0, .65)
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-month-panel-current-cell .ant-fullcalendar-month,
.ant-fullcalendar-fullscreen .ant-fullcalendar-today .ant-fullcalendar-date {
  background: transparent;
  border-top-color: #03a9f4
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-month-panel-current-cell .ant-fullcalendar-value,
.ant-fullcalendar-fullscreen .ant-fullcalendar-today .ant-fullcalendar-value {
  box-shadow: none
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-month-panel-selected-cell .ant-fullcalendar-month,
.ant-fullcalendar-fullscreen .ant-fullcalendar-selected-day .ant-fullcalendar-date {
  background: #e6fbff
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-month-panel-selected-cell .ant-fullcalendar-value,
.ant-fullcalendar-fullscreen .ant-fullcalendar-selected-day .ant-fullcalendar-value {
  color: #03a9f4
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-last-month-cell .ant-fullcalendar-date,
.ant-fullcalendar-fullscreen .ant-fullcalendar-next-month-btn-day .ant-fullcalendar-date {
  color: rgba(0, 0, 0, .25)
}

.ant-fullcalendar-fullscreen .ant-fullcalendar-content {
  position: static;
  width: auto;
  height: 88px;
  overflow-y: auto
}

.ant-fullcalendar-disabled-cell .ant-fullcalendar-date,
.ant-fullcalendar-disabled-cell .ant-fullcalendar-date:hover {
  cursor: not-allowed
}

.ant-fullcalendar-disabled-cell:not(.ant-fullcalendar-today) .ant-fullcalendar-date,
.ant-fullcalendar-disabled-cell:not(.ant-fullcalendar-today) .ant-fullcalendar-date:hover {
  background: transparent
}

.ant-fullcalendar-disabled-cell .ant-fullcalendar-value {
  width: auto;
  color: rgba(0, 0, 0, .25);
  border-radius: 0;
  cursor: not-allowed
}

.ant-card {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  background: #fff;
  border-radius: 2px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-card-hoverable {
  cursor: pointer
}

.ant-card-hoverable:hover {
  border-color: rgba(0, 0, 0, .09);
  box-shadow: 0 2px 8px rgba(0, 0, 0, .09)
}

.ant-card-bordered {
  border: 1px solid #e8e8e8
}

.ant-card-head {
  min-height: 48px;
  margin-bottom: -1px;
  padding: 0 24px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  background: transparent;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 2px 2px 0 0;
  zoom: 1
}

.ant-card-head:after,
.ant-card-head:before {
  display: table;
  content: ""
}

.ant-card-head:after {
  clear: both
}

.ant-card-head-wrapper {
  display: flex;
  align-items: center
}

.ant-card-head-title {
  display: inline-block;
  flex: 1 1;
  padding: 16px 0;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-card-head .ant-tabs {
  clear: both;
  margin-bottom: -17px;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  font-size: 14px
}

.ant-card-head .ant-tabs-bar {
  border-bottom: 1px solid #e8e8e8
}

.ant-card-extra {
  float: right;
  margin-left: auto;
  padding: 16px 0;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  font-size: 14px
}

.ant-card-body {
  padding: 24px;
  zoom: 1
}

.ant-card-body:after,
.ant-card-body:before {
  display: table;
  content: ""
}

.ant-card-body:after {
  clear: both
}

.ant-card-contain-grid:not(.ant-card-loading) .ant-card-body {
  margin: -1px 0 0 -1px;
  padding: 0
}

.ant-card-grid {
  float: left;
  width: 33.33%;
  padding: 24px;
  border: 0;
  border-radius: 0;
  box-shadow: 1px 0 0 0 #e8e8e8, 0 1px 0 0 #e8e8e8, 1px 1px 0 0 #e8e8e8, inset 1px 0 0 0 #e8e8e8, inset 0 1px 0 0 #e8e8e8;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-card-grid-hoverable:hover {
  position: relative;
  z-index: 1;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-card-contain-tabs>.ant-card-head .ant-card-head-title {
  min-height: 32px;
  padding-bottom: 0
}

.ant-card-contain-tabs>.ant-card-head .ant-card-extra {
  padding-bottom: 0
}

.ant-card-cover>* {
  display: block;
  width: 100%
}

.ant-card-cover img {
  border-radius: 2px 2px 0 0
}

.ant-card-actions {
  margin: 0;
  padding: 0;
  list-style: none;
  background: #fafafa;
  border-top: 1px solid #e8e8e8;
  zoom: 1
}

.ant-card-actions:after,
.ant-card-actions:before {
  display: table;
  content: ""
}

.ant-card-actions:after {
  clear: both
}

.ant-card-actions>li {
  float: left;
  margin: 12px 0;
  color: rgba(0, 0, 0, .45);
  text-align: center
}

.ant-card-actions>li>span {
  position: relative;
  display: block;
  min-width: 32px;
  font-size: 14px;
  line-height: 22px;
  cursor: pointer
}

.ant-card-actions>li>span:hover {
  color: #03a9f4;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-card-actions>li>span>.anticon,
.ant-card-actions>li>span a:not(.ant-btn) {
  display: inline-block;
  width: 100%;
  color: rgba(0, 0, 0, .45);
  line-height: 22px;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-card-actions>li>span>.anticon:hover,
.ant-card-actions>li>span a:not(.ant-btn):hover {
  color: #03a9f4
}

.ant-card-actions>li>span>.anticon {
  font-size: 16px;
  line-height: 22px
}

.ant-card-actions>li:not(:last-child) {
  border-right: 1px solid #e8e8e8
}

.ant-card-type-inner .ant-card-head {
  padding: 0 24px;
  background: #fafafa
}

.ant-card-type-inner .ant-card-head-title {
  padding: 12px 0;
  font-size: 14px
}

.ant-card-type-inner .ant-card-body {
  padding: 16px 24px
}

.ant-card-type-inner .ant-card-extra {
  padding: 13.5px 0
}

.ant-card-meta {
  margin: -4px 0;
  zoom: 1
}

.ant-card-meta:after,
.ant-card-meta:before {
  display: table;
  content: ""
}

.ant-card-meta:after {
  clear: both
}

.ant-card-meta-avatar {
  float: left;
  padding-right: 16px
}

.ant-card-meta-detail {
  overflow: hidden
}

.ant-card-meta-detail>div:not(:last-child) {
  margin-bottom: 8px
}

.ant-card-meta-title {
  overflow: hidden;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-card-meta-description {
  color: rgba(0, 0, 0, .45)
}

.ant-card-loading {
  overflow: hidden
}

.ant-card-loading .ant-card-body {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-card-loading-content p {
  margin: 0
}

.ant-card-loading-block {
  height: 14px;
  margin: 4px 0;
  background: -webkit-gradient(linear, left top, right top, from(rgba(207, 216, 220, .2)), color-stop(rgba(207, 216, 220, .4)), to(rgba(207, 216, 220, .2)));
  background: linear-gradient(90deg, rgba(207, 216, 220, .2), rgba(207, 216, 220, .4), rgba(207, 216, 220, .2));
  background-size: 600% 600%;
  border-radius: 2px;
  -webkit-animation: card-loading 1.4s ease infinite;
  animation: card-loading 1.4s ease infinite
}

@-webkit-keyframes card-loading {

  0%,
  to {
    background-position: 0 50%
  }

  50% {
    background-position: 100% 50%
  }
}

@keyframes card-loading {

  0%,
  to {
    background-position: 0 50%
  }

  50% {
    background-position: 100% 50%
  }
}

.ant-card-small>.ant-card-head {
  min-height: 36px;
  padding: 0 12px;
  font-size: 14px
}

.ant-card-small>.ant-card-head>.ant-card-head-wrapper>.ant-card-head-title {
  padding: 8px 0
}

.ant-card-small>.ant-card-head>.ant-card-head-wrapper>.ant-card-extra {
  padding: 8px 0;
  font-size: 14px
}

.ant-card-small>.ant-card-body {
  padding: 12px
}

.ant-carousel {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-carousel .slick-slider {
  position: relative;
  display: block;
  box-sizing: border-box;
  -webkit-touch-callout: none;
  touch-action: pan-y;
  -webkit-tap-highlight-color: transparent
}

.ant-carousel .slick-list {
  position: relative;
  display: block;
  margin: 0;
  padding: 0;
  overflow: hidden
}

.ant-carousel .slick-list:focus {
  outline: none
}

.ant-carousel .slick-list.dragging {
  cursor: pointer
}

.ant-carousel .slick-list .slick-slide {
  pointer-events: none
}

.ant-carousel .slick-list .slick-slide.slick-active {
  pointer-events: auto
}

.ant-carousel .slick-slider .slick-list,
.ant-carousel .slick-slider .slick-track {
  -webkit-transform: translateZ(0);
  transform: translateZ(0)
}

.ant-carousel .slick-track {
  position: relative;
  top: 0;
  left: 0;
  display: block
}

.ant-carousel .slick-track:after,
.ant-carousel .slick-track:before {
  display: table;
  content: ""
}

.ant-carousel .slick-track:after {
  clear: both
}

.slick-loading .ant-carousel .slick-track {
  visibility: hidden
}

.ant-carousel .slick-slide {
  display: none;
  float: left;
  height: 100%;
  min-height: 1px
}

[dir=rtl] .ant-carousel .slick-slide {
  float: right
}

.ant-carousel .slick-slide img {
  display: block
}

.ant-carousel .slick-slide.slick-loading img {
  display: none
}

.ant-carousel .slick-slide.dragging img {
  pointer-events: none
}

.ant-carousel .slick-initialized .slick-slide {
  display: block
}

.ant-carousel .slick-loading .slick-slide {
  visibility: hidden
}

.ant-carousel .slick-vertical .slick-slide {
  display: block;
  height: auto;
  border: 1px solid transparent
}

.ant-carousel .slick-arrow.slick-hidden {
  display: none
}

.ant-carousel .slick-next,
.ant-carousel .slick-prev {
  position: absolute;
  top: 50%;
  display: block;
  width: 20px;
  height: 20px;
  margin-top: -10px;
  padding: 0;
  font-size: 0;
  line-height: 0;
  border: 0;
  cursor: pointer
}

.ant-carousel .slick-next,
.ant-carousel .slick-next:focus,
.ant-carousel .slick-next:hover,
.ant-carousel .slick-prev,
.ant-carousel .slick-prev:focus,
.ant-carousel .slick-prev:hover {
  color: transparent;
  background: transparent;
  outline: none
}

.ant-carousel .slick-next:focus:before,
.ant-carousel .slick-next:hover:before,
.ant-carousel .slick-prev:focus:before,
.ant-carousel .slick-prev:hover:before {
  opacity: 1
}

.ant-carousel .slick-next.slick-disabled:before,
.ant-carousel .slick-prev.slick-disabled:before {
  opacity: .25
}

.ant-carousel .slick-prev {
  left: -25px
}

.ant-carousel .slick-prev:before {
  content: "\2190"
}

.ant-carousel .slick-next {
  right: -25px
}

.ant-carousel .slick-next:before {
  content: "\2192"
}

.ant-carousel .slick-dots {
  position: absolute;
  display: block;
  width: 100%;
  height: 3px;
  margin: 0;
  padding: 0;
  text-align: center;
  list-style: none
}

.ant-carousel .slick-dots-bottom {
  bottom: 12px
}

.ant-carousel .slick-dots-top {
  top: 12px
}

.ant-carousel .slick-dots li {
  position: relative;
  display: inline-block;
  margin: 0 2px;
  padding: 0;
  text-align: center;
  vertical-align: top
}

.ant-carousel .slick-dots li button {
  display: block;
  width: 16px;
  height: 3px;
  padding: 0;
  color: transparent;
  font-size: 0;
  background: #fff;
  border: 0;
  border-radius: 1px;
  outline: none;
  cursor: pointer;
  opacity: .3;
  -webkit-transition: all .5s;
  transition: all .5s
}

.ant-carousel .slick-dots li button:focus,
.ant-carousel .slick-dots li button:hover {
  opacity: .75
}

.ant-carousel .slick-dots li.slick-active button {
  width: 24px;
  background: #fff;
  opacity: 1
}

.ant-carousel .slick-dots li.slick-active button:focus,
.ant-carousel .slick-dots li.slick-active button:hover {
  opacity: 1
}

.ant-carousel-vertical .slick-dots {
  top: 50%;
  bottom: auto;
  width: 3px;
  height: auto;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-carousel-vertical .slick-dots-left {
  left: 12px
}

.ant-carousel-vertical .slick-dots-right {
  right: 12px
}

.ant-carousel-vertical .slick-dots li {
  margin: 0 2px;
  vertical-align: baseline
}

.ant-carousel-vertical .slick-dots li button {
  width: 3px;
  height: 16px
}

.ant-carousel-vertical .slick-dots li.slick-active button {
  width: 3px;
  height: 24px
}

.ant-cascader {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-cascader-input.ant-input {
  position: static;
  width: 100%;
  padding-right: 24px;
  background-color: transparent !important;
  cursor: pointer
}

.ant-cascader-picker-show-search .ant-cascader-input.ant-input {
  position: relative
}

.ant-cascader-picker {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  background-color: #fff;
  border-radius: 4px;
  outline: 0;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-cascader-picker-with-value .ant-cascader-picker-label {
  color: transparent
}

.ant-cascader-picker-disabled {
  color: rgba(0, 0, 0, .25);
  background: #f5f5f5;
  cursor: not-allowed
}

.ant-cascader-picker-disabled .ant-cascader-input {
  cursor: not-allowed
}

.ant-cascader-picker:focus .ant-cascader-input {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-cascader-picker-show-search.ant-cascader-picker-focused {
  color: rgba(0, 0, 0, .25)
}

.ant-cascader-picker-label {
  position: absolute;
  top: 50%;
  left: 0;
  width: 100%;
  height: 20px;
  margin-top: -10px;
  padding: 0 20px 0 12px;
  overflow: hidden;
  line-height: 20px;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-cascader-picker-clear {
  position: absolute;
  top: 50%;
  right: 12px;
  z-index: 2;
  width: 12px;
  height: 12px;
  margin-top: -6px;
  color: rgba(0, 0, 0, .25);
  font-size: 12px;
  line-height: 12px;
  background: #fff;
  cursor: pointer;
  opacity: 0;
  -webkit-transition: color .3s ease, opacity .15s ease;
  transition: color .3s ease, opacity .15s ease
}

.ant-cascader-picker-clear:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-cascader-picker:hover .ant-cascader-picker-clear {
  opacity: 1
}

.ant-cascader-picker-arrow {
  position: absolute;
  top: 50%;
  right: 12px;
  z-index: 1;
  width: 12px;
  height: 12px;
  margin-top: -6px;
  color: rgba(0, 0, 0, .25);
  font-size: 12px;
  line-height: 12px;
  -webkit-transition: -webkit-transform .2s;
  transition: -webkit-transform .2s;
  transition: transform .2s;
  transition: transform .2s, -webkit-transform .2s
}

.ant-cascader-picker-arrow.ant-cascader-picker-arrow-expand {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.ant-cascader-picker-label:hover+.ant-cascader-input {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-cascader-picker-small .ant-cascader-picker-arrow,
.ant-cascader-picker-small .ant-cascader-picker-clear {
  right: 8px
}

.ant-cascader-menus {
  position: absolute;
  z-index: 1050;
  font-size: 14px;
  white-space: nowrap;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-cascader-menus ol,
.ant-cascader-menus ul {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-cascader-menus-empty,
.ant-cascader-menus-hidden {
  display: none
}

.ant-cascader-menus.slide-up-appear.slide-up-appear-active.ant-cascader-menus-placement-bottomLeft,
.ant-cascader-menus.slide-up-enter.slide-up-enter-active.ant-cascader-menus-placement-bottomLeft {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn
}

.ant-cascader-menus.slide-up-appear.slide-up-appear-active.ant-cascader-menus-placement-topLeft,
.ant-cascader-menus.slide-up-enter.slide-up-enter-active.ant-cascader-menus-placement-topLeft {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn
}

.ant-cascader-menus.slide-up-leave.slide-up-leave-active.ant-cascader-menus-placement-bottomLeft {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut
}

.ant-cascader-menus.slide-up-leave.slide-up-leave-active.ant-cascader-menus-placement-topLeft {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut
}

.ant-cascader-menu {
  display: inline-block;
  min-width: 111px;
  height: 180px;
  margin: 0;
  padding: 0;
  overflow: auto;
  vertical-align: top;
  list-style: none;
  border-right: 1px solid #e8e8e8;
  -ms-overflow-style: -ms-autohiding-scrollbar
}

.ant-cascader-menu:first-child {
  border-radius: 4px 0 0 4px
}

.ant-cascader-menu:last-child {
  margin-right: -1px;
  border-right-color: transparent;
  border-radius: 0 4px 4px 0
}

.ant-cascader-menu:only-child {
  border-radius: 4px
}

.ant-cascader-menu-item {
  padding: 5px 12px;
  line-height: 22px;
  white-space: nowrap;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-cascader-menu-item:hover {
  background: #e8f8ff
}

.ant-cascader-menu-item-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-cascader-menu-item-disabled:hover {
  background: transparent
}

.ant-cascader-menu-item-active:not(.ant-cascader-menu-item-disabled),
.ant-cascader-menu-item-active:not(.ant-cascader-menu-item-disabled):hover {
  font-weight: 600;
  background-color: #fafafa
}

.ant-cascader-menu-item-expand {
  position: relative;
  padding-right: 24px
}

.ant-cascader-menu-item-expand .ant-cascader-menu-item-expand-icon,
.ant-cascader-menu-item-loading-icon {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  position: absolute;
  right: 12px;
  color: rgba(0, 0, 0, .45)
}

:root .ant-cascader-menu-item-expand .ant-cascader-menu-item-expand-icon,
:root .ant-cascader-menu-item-loading-icon {
  font-size: 12px
}

.ant-cascader-menu-item .ant-cascader-menu-item-keyword {
  color: #f5222d
}

@-webkit-keyframes antCheckboxEffect {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: .5
  }

  to {
    -webkit-transform: scale(1.6);
    transform: scale(1.6);
    opacity: 0
  }
}

@keyframes antCheckboxEffect {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: .5
  }

  to {
    -webkit-transform: scale(1.6);
    transform: scale(1.6);
    opacity: 0
  }
}

.ant-checkbox {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  top: -.09em;
  display: inline-block;
  line-height: 1;
  white-space: nowrap;
  vertical-align: middle;
  outline: none;
  cursor: pointer
}

.ant-checkbox-input:focus+.ant-checkbox-inner,
.ant-checkbox-wrapper:hover .ant-checkbox-inner,
.ant-checkbox:hover .ant-checkbox-inner {
  border-color: #03a9f4
}

.ant-checkbox-checked:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #03a9f4;
  border-radius: 2px;
  visibility: hidden;
  -webkit-animation: antCheckboxEffect .36s ease-in-out;
  animation: antCheckboxEffect .36s ease-in-out;
  -webkit-animation-fill-mode: backwards;
  animation-fill-mode: backwards;
  content: ""
}

.ant-checkbox-wrapper:hover .ant-checkbox:after,
.ant-checkbox:hover:after {
  visibility: visible
}

.ant-checkbox-inner {
  position: relative;
  top: 0;
  left: 0;
  display: block;
  width: 16px;
  height: 16px;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 2px;
  border-collapse: separate;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-checkbox-inner:after {
  position: absolute;
  top: 50%;
  left: 21%;
  display: table;
  width: 5.71428571px;
  height: 9.14285714px;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(0) translate(-50%, -50%);
  transform: rotate(45deg) scale(0) translate(-50%, -50%);
  opacity: 0;
  -webkit-transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  content: " "
}

.ant-checkbox-input {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  width: 100%;
  height: 100%;
  cursor: pointer;
  opacity: 0
}

.ant-checkbox-checked .ant-checkbox-inner:after {
  position: absolute;
  display: table;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(1) translate(-50%, -50%);
  transform: rotate(45deg) scale(1) translate(-50%, -50%);
  opacity: 1;
  -webkit-transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  content: " "
}

.ant-checkbox-checked .ant-checkbox-inner {
  background-color: #03a9f4;
  border-color: #03a9f4
}

.ant-checkbox-disabled {
  cursor: not-allowed
}

.ant-checkbox-disabled.ant-checkbox-checked .ant-checkbox-inner:after {
  border-color: rgba(0, 0, 0, .25);
  -webkit-animation-name: none;
  animation-name: none
}

.ant-checkbox-disabled .ant-checkbox-input {
  cursor: not-allowed
}

.ant-checkbox-disabled .ant-checkbox-inner {
  background-color: #f5f5f5;
  border-color: #d9d9d9 !important
}

.ant-checkbox-disabled .ant-checkbox-inner:after {
  border-color: #f5f5f5;
  border-collapse: separate;
  -webkit-animation-name: none;
  animation-name: none
}

.ant-checkbox-disabled+span {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-checkbox-disabled:hover:after,
.ant-checkbox-wrapper:hover .ant-checkbox-disabled:after {
  visibility: hidden
}

.ant-checkbox-wrapper {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  line-height: unset;
  cursor: pointer
}

.ant-checkbox-wrapper.ant-checkbox-wrapper-disabled {
  cursor: not-allowed
}

.ant-checkbox-wrapper+.ant-checkbox-wrapper {
  margin-left: 8px
}

.ant-checkbox+span {
  padding-right: 8px;
  padding-left: 8px
}

.ant-checkbox-group {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block
}

.ant-checkbox-group-item {
  display: inline-block;
  margin-right: 8px
}

.ant-checkbox-group-item:last-child {
  margin-right: 0
}

.ant-checkbox-group-item+.ant-checkbox-group-item {
  margin-left: 0
}

.ant-checkbox-indeterminate .ant-checkbox-inner {
  background-color: #fff;
  border-color: #d9d9d9
}

.ant-checkbox-indeterminate .ant-checkbox-inner:after {
  top: 50%;
  left: 50%;
  width: 8px;
  height: 8px;
  background-color: #03a9f4;
  border: 0;
  -webkit-transform: translate(-50%, -50%) scale(1);
  transform: translate(-50%, -50%) scale(1);
  opacity: 1;
  content: " "
}

.ant-checkbox-indeterminate.ant-checkbox-disabled .ant-checkbox-inner:after {
  background-color: rgba(0, 0, 0, .25);
  border-color: rgba(0, 0, 0, .25)
}

.ant-collapse {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  background-color: #fafafa;
  border: 1px solid #d9d9d9;
  border-bottom: 0;
  border-radius: 4px
}

.ant-collapse>.ant-collapse-item {
  border-bottom: 1px solid #d9d9d9
}

.ant-collapse>.ant-collapse-item:last-child,
.ant-collapse>.ant-collapse-item:last-child>.ant-collapse-header {
  border-radius: 0 0 4px 4px
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header {
  position: relative;
  padding: 12px 16px 12px 40px;
  color: rgba(0, 0, 0, .85);
  line-height: 22px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow {
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: absolute;
  top: 50%;
  left: 16px;
  display: inline-block;
  font-size: 12px;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow>* {
  line-height: 1
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow svg {
  display: inline-block
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow:before {
  display: none
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow .ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow-icon {
  display: block
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow svg {
  -webkit-transition: -webkit-transform .24s;
  transition: -webkit-transform .24s;
  transition: transform .24s;
  transition: transform .24s, -webkit-transform .24s
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header .ant-collapse-extra {
  float: right
}

.ant-collapse>.ant-collapse-item>.ant-collapse-header:focus {
  outline: none
}

.ant-collapse>.ant-collapse-item.ant-collapse-no-arrow>.ant-collapse-header {
  padding-left: 12px
}

.ant-collapse-icon-position-right>.ant-collapse-item>.ant-collapse-header {
  padding: 12px 40px 12px 16px
}

.ant-collapse-icon-position-right>.ant-collapse-item>.ant-collapse-header .ant-collapse-arrow {
  right: 16px;
  left: auto
}

.ant-collapse-anim-active {
  -webkit-transition: height .2s cubic-bezier(.215, .61, .355, 1);
  transition: height .2s cubic-bezier(.215, .61, .355, 1)
}

.ant-collapse-content {
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  background-color: #fff;
  border-top: 1px solid #d9d9d9
}

.ant-collapse-content>.ant-collapse-content-box {
  padding: 16px
}

.ant-collapse-content-inactive {
  display: none
}

.ant-collapse-item:last-child>.ant-collapse-content {
  border-radius: 0 0 4px 4px
}

.ant-collapse-borderless {
  background-color: #fff;
  border: 0
}

.ant-collapse-borderless>.ant-collapse-item {
  border-bottom: 1px solid #d9d9d9
}

.ant-collapse-borderless>.ant-collapse-item:last-child,
.ant-collapse-borderless>.ant-collapse-item:last-child .ant-collapse-header {
  border-radius: 0
}

.ant-collapse-borderless>.ant-collapse-item>.ant-collapse-content {
  background-color: transparent;
  border-top: 0
}

.ant-collapse-borderless>.ant-collapse-item>.ant-collapse-content>.ant-collapse-content-box {
  padding-top: 4px
}

.ant-collapse .ant-collapse-item-disabled>.ant-collapse-header,
.ant-collapse .ant-collapse-item-disabled>.ant-collapse-header>.arrow {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-comment {
  position: relative
}

.ant-comment-inner {
  display: flex;
  padding: 16px 0
}

.ant-comment-avatar {
  position: relative;
  flex-shrink: 0;
  margin-right: 12px;
  cursor: pointer
}

.ant-comment-avatar img {
  width: 32px;
  height: 32px;
  border-radius: 50%
}

.ant-comment-content {
  position: relative;
  flex: 1 1 auto;
  min-width: 1px;
  font-size: 14px;
  word-wrap: break-word
}

.ant-comment-content-author {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  margin-bottom: 4px;
  font-size: 14px
}

.ant-comment-content-author>a,
.ant-comment-content-author>span {
  padding-right: 8px;
  font-size: 12px;
  line-height: 18px
}

.ant-comment-content-author-name {
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-comment-content-author-name>*,
.ant-comment-content-author-name>:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-comment-content-author-time {
  color: #ccc;
  white-space: nowrap;
  cursor: auto
}

.ant-comment-content-detail p {
  white-space: pre-wrap
}

.ant-comment-actions {
  margin-top: 12px;
  padding-left: 0
}

.ant-comment-actions>li {
  display: inline-block;
  color: rgba(0, 0, 0, .45)
}

.ant-comment-actions>li>span {
  padding-right: 10px;
  color: rgba(0, 0, 0, .45);
  font-size: 12px;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-comment-actions>li>span:hover {
  color: #595959
}

.ant-comment-nested {
  margin-left: 44px
}

.ant-calendar-picker-container {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  z-index: 1050;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol
}

.ant-calendar-picker-container.slide-up-appear.slide-up-appear-active.ant-calendar-picker-container-placement-topLeft,
.ant-calendar-picker-container.slide-up-appear.slide-up-appear-active.ant-calendar-picker-container-placement-topRight,
.ant-calendar-picker-container.slide-up-enter.slide-up-enter-active.ant-calendar-picker-container-placement-topLeft,
.ant-calendar-picker-container.slide-up-enter.slide-up-enter-active.ant-calendar-picker-container-placement-topRight {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn
}

.ant-calendar-picker-container.slide-up-appear.slide-up-appear-active.ant-calendar-picker-container-placement-bottomLeft,
.ant-calendar-picker-container.slide-up-appear.slide-up-appear-active.ant-calendar-picker-container-placement-bottomRight,
.ant-calendar-picker-container.slide-up-enter.slide-up-enter-active.ant-calendar-picker-container-placement-bottomLeft,
.ant-calendar-picker-container.slide-up-enter.slide-up-enter-active.ant-calendar-picker-container-placement-bottomRight {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn
}

.ant-calendar-picker-container.slide-up-leave.slide-up-leave-active.ant-calendar-picker-container-placement-topLeft,
.ant-calendar-picker-container.slide-up-leave.slide-up-leave-active.ant-calendar-picker-container-placement-topRight {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut
}

.ant-calendar-picker-container.slide-up-leave.slide-up-leave-active.ant-calendar-picker-container-placement-bottomLeft,
.ant-calendar-picker-container.slide-up-leave.slide-up-leave-active.ant-calendar-picker-container-placement-bottomRight {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut
}

.ant-calendar-picker {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  outline: none;
  cursor: text;
  -webkit-transition: opacity .3s;
  transition: opacity .3s
}

.ant-calendar-picker-input {
  outline: none
}

.ant-calendar-picker-input.ant-input {
  line-height: 1.5
}

.ant-calendar-picker-input.ant-input-sm {
  padding-top: 0;
  padding-bottom: 0
}

.ant-calendar-picker:hover .ant-calendar-picker-input:not(.ant-input-disabled) {
  border-color: #2bc3ff
}

.ant-calendar-picker:focus .ant-calendar-picker-input:not(.ant-input-disabled) {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-calendar-picker-clear,
.ant-calendar-picker-icon {
  position: absolute;
  top: 50%;
  right: 12px;
  z-index: 1;
  width: 14px;
  height: 14px;
  margin-top: -7px;
  font-size: 12px;
  line-height: 14px;
  -webkit-transition: all .3s;
  transition: all .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-calendar-picker-clear {
  z-index: 2;
  color: rgba(0, 0, 0, .25);
  font-size: 14px;
  background: #fff;
  cursor: pointer;
  opacity: 0;
  pointer-events: none
}

.ant-calendar-picker-clear:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-calendar-picker:hover .ant-calendar-picker-clear {
  opacity: 1;
  pointer-events: auto
}

.ant-calendar-picker-icon {
  display: inline-block;
  color: rgba(0, 0, 0, .25);
  font-size: 14px;
  line-height: 1
}

.ant-calendar-picker-small .ant-calendar-picker-clear,
.ant-calendar-picker-small .ant-calendar-picker-icon {
  right: 8px
}

.ant-calendar {
  position: relative;
  width: 280px;
  font-size: 14px;
  line-height: 1.5;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #fff;
  border-radius: 4px;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-calendar-input-wrap {
  height: 34px;
  padding: 6px 10px;
  border-bottom: 1px solid #e8e8e8
}

.ant-calendar-input {
  width: 100%;
  height: 22px;
  color: rgba(0, 0, 0, .65);
  background: #fff;
  border: 0;
  outline: 0;
  cursor: auto
}

.ant-calendar-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-calendar-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-calendar-week-number {
  width: 286px
}

.ant-calendar-week-number-cell {
  text-align: center
}

.ant-calendar-header {
  height: 40px;
  line-height: 40px;
  text-align: center;
  border-bottom: 1px solid #e8e8e8;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-calendar-header a:hover {
  color: #2bc3ff
}

.ant-calendar-header .ant-calendar-century-select,
.ant-calendar-header .ant-calendar-decade-select,
.ant-calendar-header .ant-calendar-month-select,
.ant-calendar-header .ant-calendar-year-select {
  display: inline-block;
  padding: 0 2px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  line-height: 40px
}

.ant-calendar-header .ant-calendar-century-select-arrow,
.ant-calendar-header .ant-calendar-decade-select-arrow,
.ant-calendar-header .ant-calendar-month-select-arrow,
.ant-calendar-header .ant-calendar-year-select-arrow {
  display: none
}

.ant-calendar-header .ant-calendar-next-century-btn,
.ant-calendar-header .ant-calendar-next-decade-btn,
.ant-calendar-header .ant-calendar-next-month-btn,
.ant-calendar-header .ant-calendar-next-year-btn,
.ant-calendar-header .ant-calendar-prev-century-btn,
.ant-calendar-header .ant-calendar-prev-decade-btn,
.ant-calendar-header .ant-calendar-prev-month-btn,
.ant-calendar-header .ant-calendar-prev-year-btn {
  position: absolute;
  top: 0;
  display: inline-block;
  padding: 0 5px;
  color: rgba(0, 0, 0, .45);
  font-size: 16px;
  font-family: Arial, Hiragino Sans GB, Microsoft Yahei, "Microsoft Sans Serif", sans-serif;
  line-height: 40px
}

.ant-calendar-header .ant-calendar-prev-century-btn,
.ant-calendar-header .ant-calendar-prev-decade-btn,
.ant-calendar-header .ant-calendar-prev-year-btn {
  left: 7px;
  height: 100%
}

.ant-calendar-header .ant-calendar-prev-century-btn:after,
.ant-calendar-header .ant-calendar-prev-century-btn:before,
.ant-calendar-header .ant-calendar-prev-decade-btn:after,
.ant-calendar-header .ant-calendar-prev-decade-btn:before,
.ant-calendar-header .ant-calendar-prev-year-btn:after,
.ant-calendar-header .ant-calendar-prev-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-header .ant-calendar-prev-century-btn:hover:after,
.ant-calendar-header .ant-calendar-prev-century-btn:hover:before,
.ant-calendar-header .ant-calendar-prev-decade-btn:hover:after,
.ant-calendar-header .ant-calendar-prev-decade-btn:hover:before,
.ant-calendar-header .ant-calendar-prev-year-btn:hover:after,
.ant-calendar-header .ant-calendar-prev-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-header .ant-calendar-prev-century-btn:after,
.ant-calendar-header .ant-calendar-prev-decade-btn:after,
.ant-calendar-header .ant-calendar-prev-year-btn:after {
  display: none;
  position: relative;
  left: -3px;
  display: inline-block
}

.ant-calendar-header .ant-calendar-next-century-btn,
.ant-calendar-header .ant-calendar-next-decade-btn,
.ant-calendar-header .ant-calendar-next-year-btn {
  right: 7px;
  height: 100%
}

.ant-calendar-header .ant-calendar-next-century-btn:after,
.ant-calendar-header .ant-calendar-next-century-btn:before,
.ant-calendar-header .ant-calendar-next-decade-btn:after,
.ant-calendar-header .ant-calendar-next-decade-btn:before,
.ant-calendar-header .ant-calendar-next-year-btn:after,
.ant-calendar-header .ant-calendar-next-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-header .ant-calendar-next-century-btn:hover:after,
.ant-calendar-header .ant-calendar-next-century-btn:hover:before,
.ant-calendar-header .ant-calendar-next-decade-btn:hover:after,
.ant-calendar-header .ant-calendar-next-decade-btn:hover:before,
.ant-calendar-header .ant-calendar-next-year-btn:hover:after,
.ant-calendar-header .ant-calendar-next-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-header .ant-calendar-next-century-btn:after,
.ant-calendar-header .ant-calendar-next-decade-btn:after,
.ant-calendar-header .ant-calendar-next-year-btn:after {
  display: none
}

.ant-calendar-header .ant-calendar-next-century-btn:after,
.ant-calendar-header .ant-calendar-next-century-btn:before,
.ant-calendar-header .ant-calendar-next-decade-btn:after,
.ant-calendar-header .ant-calendar-next-decade-btn:before,
.ant-calendar-header .ant-calendar-next-year-btn:after,
.ant-calendar-header .ant-calendar-next-year-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-header .ant-calendar-next-century-btn:before,
.ant-calendar-header .ant-calendar-next-decade-btn:before,
.ant-calendar-header .ant-calendar-next-year-btn:before {
  position: relative;
  left: 3px
}

.ant-calendar-header .ant-calendar-next-century-btn:after,
.ant-calendar-header .ant-calendar-next-decade-btn:after,
.ant-calendar-header .ant-calendar-next-year-btn:after {
  display: inline-block
}

.ant-calendar-header .ant-calendar-prev-month-btn {
  left: 29px;
  height: 100%
}

.ant-calendar-header .ant-calendar-prev-month-btn:after,
.ant-calendar-header .ant-calendar-prev-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-header .ant-calendar-prev-month-btn:hover:after,
.ant-calendar-header .ant-calendar-prev-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-header .ant-calendar-prev-month-btn:after {
  display: none
}

.ant-calendar-header .ant-calendar-next-month-btn {
  right: 29px;
  height: 100%
}

.ant-calendar-header .ant-calendar-next-month-btn:after,
.ant-calendar-header .ant-calendar-next-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-header .ant-calendar-next-month-btn:hover:after,
.ant-calendar-header .ant-calendar-next-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-header .ant-calendar-next-month-btn:after {
  display: none
}

.ant-calendar-header .ant-calendar-next-month-btn:after,
.ant-calendar-header .ant-calendar-next-month-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-body {
  padding: 8px 12px
}

.ant-calendar table {
  width: 100%;
  max-width: 100%;
  background-color: transparent;
  border-collapse: collapse
}

.ant-calendar table,
.ant-calendar td,
.ant-calendar th {
  text-align: center;
  border: 0
}

.ant-calendar-calendar-table {
  margin-bottom: 0;
  border-spacing: 0
}

.ant-calendar-column-header {
  width: 33px;
  padding: 6px 0;
  line-height: 18px;
  text-align: center
}

.ant-calendar-column-header .ant-calendar-column-header-inner {
  display: block;
  font-weight: 400
}

.ant-calendar-week-number-header .ant-calendar-column-header-inner {
  display: none
}

.ant-calendar-cell {
  height: 30px;
  padding: 3px 0
}

.ant-calendar-date {
  display: block;
  width: 24px;
  height: 24px;
  margin: 0 auto;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  line-height: 22px;
  text-align: center;
  background: transparent;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-calendar-date-panel {
  position: relative;
  outline: none
}

.ant-calendar-date:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-calendar-date:active {
  color: #fff;
  background: #2bc3ff
}

.ant-calendar-today .ant-calendar-date {
  color: #03a9f4;
  font-weight: 700;
  border-color: #03a9f4
}

.ant-calendar-selected-day .ant-calendar-date {
  background: #a6efff
}

.ant-calendar-last-month-cell .ant-calendar-date,
.ant-calendar-last-month-cell .ant-calendar-date:hover,
.ant-calendar-next-month-btn-day .ant-calendar-date,
.ant-calendar-next-month-btn-day .ant-calendar-date:hover {
  color: rgba(0, 0, 0, .25);
  background: transparent;
  border-color: transparent
}

.ant-calendar-disabled-cell .ant-calendar-date {
  position: relative;
  width: auto;
  color: rgba(0, 0, 0, .25);
  background: #f5f5f5;
  border: 1px solid transparent;
  border-radius: 0;
  cursor: not-allowed
}

.ant-calendar-disabled-cell .ant-calendar-date:hover {
  background: #f5f5f5
}

.ant-calendar-disabled-cell.ant-calendar-selected-day .ant-calendar-date:before {
  position: absolute;
  top: -1px;
  left: 5px;
  width: 24px;
  height: 24px;
  background: rgba(0, 0, 0, .1);
  border-radius: 2px;
  content: ""
}

.ant-calendar-disabled-cell.ant-calendar-today .ant-calendar-date {
  position: relative;
  padding-right: 5px;
  padding-left: 5px
}

.ant-calendar-disabled-cell.ant-calendar-today .ant-calendar-date:before {
  position: absolute;
  top: -1px;
  left: 5px;
  width: 24px;
  height: 24px;
  border: 1px solid rgba(0, 0, 0, .25);
  border-radius: 2px;
  content: " "
}

.ant-calendar-disabled-cell-first-of-row .ant-calendar-date {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px
}

.ant-calendar-disabled-cell-last-of-row .ant-calendar-date {
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px
}

.ant-calendar-footer {
  padding: 0 12px;
  line-height: 38px;
  border-top: 1px solid #e8e8e8
}

.ant-calendar-footer:empty {
  border-top: 0
}

.ant-calendar-footer-btn {
  display: block;
  text-align: center
}

.ant-calendar-footer-extra {
  text-align: left
}

.ant-calendar .ant-calendar-clear-btn,
.ant-calendar .ant-calendar-today-btn {
  display: inline-block;
  margin: 0 0 0 8px;
  text-align: center
}

.ant-calendar .ant-calendar-clear-btn-disabled,
.ant-calendar .ant-calendar-today-btn-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-calendar .ant-calendar-clear-btn:only-child,
.ant-calendar .ant-calendar-today-btn:only-child {
  margin: 0
}

.ant-calendar .ant-calendar-clear-btn {
  position: absolute;
  top: 7px;
  right: 5px;
  display: none;
  width: 20px;
  height: 20px;
  margin: 0;
  overflow: hidden;
  line-height: 20px;
  text-align: center;
  text-indent: -76px
}

.ant-calendar .ant-calendar-clear-btn:after {
  display: inline-block;
  width: 20px;
  color: rgba(0, 0, 0, .25);
  font-size: 14px;
  line-height: 1;
  text-indent: 43px;
  -webkit-transition: color .3s ease;
  transition: color .3s ease
}

.ant-calendar .ant-calendar-clear-btn:hover:after {
  color: rgba(0, 0, 0, .45)
}

.ant-calendar .ant-calendar-ok-btn {
  position: relative;
  display: inline-block;
  font-weight: 400;
  white-space: nowrap;
  text-align: center;
  background-image: none;
  box-shadow: 0 2px 0 rgba(0, 0, 0, .015);
  cursor: pointer;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  touch-action: manipulation;
  height: 32px;
  color: #fff;
  background-color: #03a9f4;
  border: 1px solid #03a9f4;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, .12);
  box-shadow: 0 2px 0 rgba(0, 0, 0, .045);
  height: 24px;
  padding: 0 7px;
  font-size: 14px;
  border-radius: 4px;
  line-height: 22px
}

.ant-calendar .ant-calendar-ok-btn>.anticon {
  line-height: 1
}

.ant-calendar .ant-calendar-ok-btn,
.ant-calendar .ant-calendar-ok-btn:active,
.ant-calendar .ant-calendar-ok-btn:focus {
  outline: 0
}

.ant-calendar .ant-calendar-ok-btn:not([disabled]):hover {
  text-decoration: none
}

.ant-calendar .ant-calendar-ok-btn:not([disabled]):active {
  outline: 0;
  box-shadow: none
}

.ant-calendar .ant-calendar-ok-btn.disabled,
.ant-calendar .ant-calendar-ok-btn[disabled] {
  cursor: not-allowed
}

.ant-calendar .ant-calendar-ok-btn.disabled>*,
.ant-calendar .ant-calendar-ok-btn[disabled]>* {
  pointer-events: none
}

.ant-calendar .ant-calendar-ok-btn-lg {
  height: 40px;
  padding: 0 15px;
  font-size: 16px;
  border-radius: 4px
}

.ant-calendar .ant-calendar-ok-btn-sm {
  height: 24px;
  padding: 0 7px;
  font-size: 14px;
  border-radius: 4px
}

.ant-calendar .ant-calendar-ok-btn>a:only-child {
  color: currentColor
}

.ant-calendar .ant-calendar-ok-btn>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-calendar .ant-calendar-ok-btn:focus,
.ant-calendar .ant-calendar-ok-btn:hover {
  color: #fff;
  background-color: #2bc3ff;
  border-color: #2bc3ff
}

.ant-calendar .ant-calendar-ok-btn:focus>a:only-child,
.ant-calendar .ant-calendar-ok-btn:hover>a:only-child {
  color: currentColor
}

.ant-calendar .ant-calendar-ok-btn:focus>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn:hover>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-calendar .ant-calendar-ok-btn.active,
.ant-calendar .ant-calendar-ok-btn:active {
  color: #fff;
  background-color: #0086cf;
  border-color: #0086cf
}

.ant-calendar .ant-calendar-ok-btn.active>a:only-child,
.ant-calendar .ant-calendar-ok-btn:active>a:only-child {
  color: currentColor
}

.ant-calendar .ant-calendar-ok-btn.active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn:active>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-calendar .ant-calendar-ok-btn-disabled,
.ant-calendar .ant-calendar-ok-btn-disabled.active,
.ant-calendar .ant-calendar-ok-btn-disabled:active,
.ant-calendar .ant-calendar-ok-btn-disabled:focus,
.ant-calendar .ant-calendar-ok-btn-disabled:hover,
.ant-calendar .ant-calendar-ok-btn.disabled,
.ant-calendar .ant-calendar-ok-btn.disabled.active,
.ant-calendar .ant-calendar-ok-btn.disabled:active,
.ant-calendar .ant-calendar-ok-btn.disabled:focus,
.ant-calendar .ant-calendar-ok-btn.disabled:hover,
.ant-calendar .ant-calendar-ok-btn[disabled],
.ant-calendar .ant-calendar-ok-btn[disabled].active,
.ant-calendar .ant-calendar-ok-btn[disabled]:active,
.ant-calendar .ant-calendar-ok-btn[disabled]:focus,
.ant-calendar .ant-calendar-ok-btn[disabled]:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9;
  text-shadow: none;
  box-shadow: none
}

.ant-calendar .ant-calendar-ok-btn-disabled.active>a:only-child,
.ant-calendar .ant-calendar-ok-btn-disabled:active>a:only-child,
.ant-calendar .ant-calendar-ok-btn-disabled:focus>a:only-child,
.ant-calendar .ant-calendar-ok-btn-disabled:hover>a:only-child,
.ant-calendar .ant-calendar-ok-btn-disabled>a:only-child,
.ant-calendar .ant-calendar-ok-btn.disabled.active>a:only-child,
.ant-calendar .ant-calendar-ok-btn.disabled:active>a:only-child,
.ant-calendar .ant-calendar-ok-btn.disabled:focus>a:only-child,
.ant-calendar .ant-calendar-ok-btn.disabled:hover>a:only-child,
.ant-calendar .ant-calendar-ok-btn.disabled>a:only-child,
.ant-calendar .ant-calendar-ok-btn[disabled].active>a:only-child,
.ant-calendar .ant-calendar-ok-btn[disabled]:active>a:only-child,
.ant-calendar .ant-calendar-ok-btn[disabled]:focus>a:only-child,
.ant-calendar .ant-calendar-ok-btn[disabled]:hover>a:only-child,
.ant-calendar .ant-calendar-ok-btn[disabled]>a:only-child {
  color: currentColor
}

.ant-calendar .ant-calendar-ok-btn-disabled.active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn-disabled:active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn-disabled:focus>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn-disabled:hover>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn-disabled>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn.disabled.active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn.disabled:active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn.disabled:focus>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn.disabled:hover>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn.disabled>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn[disabled].active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn[disabled]:active>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn[disabled]:focus>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn[disabled]:hover>a:only-child:after,
.ant-calendar .ant-calendar-ok-btn[disabled]>a:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  content: ""
}

.ant-calendar-range-picker-input {
  width: 44%;
  height: 99%;
  text-align: center;
  background-color: transparent;
  border: 0;
  outline: 0
}

.ant-calendar-range-picker-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-calendar-range-picker-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-range-picker-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-range-picker-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-calendar-range-picker-input[disabled] {
  cursor: not-allowed
}

.ant-calendar-range-picker-separator {
  display: inline-block;
  min-width: 10px;
  height: 100%;
  color: rgba(0, 0, 0, .45);
  white-space: nowrap;
  text-align: center;
  vertical-align: top;
  pointer-events: none
}

.ant-calendar-range {
  width: 552px;
  overflow: hidden
}

.ant-calendar-range .ant-calendar-date-panel:after {
  display: block;
  clear: both;
  height: 0;
  visibility: hidden;
  content: "."
}

.ant-calendar-range-part {
  position: relative;
  width: 50%
}

.ant-calendar-range-left {
  float: left
}

.ant-calendar-range-left .ant-calendar-time-picker-inner {
  border-right: 1px solid #e8e8e8
}

.ant-calendar-range-right {
  float: right
}

.ant-calendar-range-right .ant-calendar-time-picker-inner {
  border-left: 1px solid #e8e8e8
}

.ant-calendar-range-middle {
  position: absolute;
  left: 50%;
  z-index: 1;
  height: 34px;
  margin: 1px 0 0;
  padding: 0 200px 0 0;
  color: rgba(0, 0, 0, .45);
  line-height: 34px;
  text-align: center;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  pointer-events: none
}

.ant-calendar-range-right .ant-calendar-date-input-wrap {
  margin-left: -90px
}

.ant-calendar-range.ant-calendar-time .ant-calendar-range-middle {
  padding: 0 10px 0 0;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%)
}

.ant-calendar-range .ant-calendar-today :not(.ant-calendar-disabled-cell) :not(.ant-calendar-last-month-cell) :not(.ant-calendar-next-month-btn-day) .ant-calendar-date {
  color: #03a9f4;
  background: #a6efff;
  border-color: #03a9f4
}

.ant-calendar-range .ant-calendar-selected-end-date .ant-calendar-date,
.ant-calendar-range .ant-calendar-selected-start-date .ant-calendar-date {
  color: #fff;
  background: #03a9f4;
  border: 1px solid transparent
}

.ant-calendar-range .ant-calendar-selected-end-date .ant-calendar-date:hover,
.ant-calendar-range .ant-calendar-selected-start-date .ant-calendar-date:hover {
  background: #03a9f4
}

.ant-calendar-range.ant-calendar-time .ant-calendar-range-right .ant-calendar-date-input-wrap {
  margin-left: 0
}

.ant-calendar-range .ant-calendar-input-wrap {
  position: relative;
  height: 34px
}

.ant-calendar-range .ant-calendar-input,
.ant-calendar-range .ant-calendar-time-picker-input {
  position: relative;
  display: inline-block;
  width: 100%;
  height: 32px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5;
  background-color: #fff;
  background-image: none;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s;
  height: 24px;
  padding: 4px 0;
  line-height: 24px;
  border: 0;
  box-shadow: none
}

.ant-calendar-range .ant-calendar-input::-moz-placeholder,
.ant-calendar-range .ant-calendar-time-picker-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-calendar-range .ant-calendar-input:-ms-input-placeholder,
.ant-calendar-range .ant-calendar-time-picker-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-range .ant-calendar-input::-webkit-input-placeholder,
.ant-calendar-range .ant-calendar-time-picker-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-calendar-range .ant-calendar-input:placeholder-shown,
.ant-calendar-range .ant-calendar-time-picker-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-calendar-range .ant-calendar-input:hover,
.ant-calendar-range .ant-calendar-time-picker-input:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-calendar-range .ant-calendar-input:focus,
.ant-calendar-range .ant-calendar-time-picker-input:focus {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-calendar-range .ant-calendar-input-disabled,
.ant-calendar-range .ant-calendar-time-picker-input-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-calendar-range .ant-calendar-input-disabled:hover,
.ant-calendar-range .ant-calendar-time-picker-input-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-calendar-range .ant-calendar-input[disabled],
.ant-calendar-range .ant-calendar-time-picker-input[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-calendar-range .ant-calendar-input[disabled]:hover,
.ant-calendar-range .ant-calendar-time-picker-input[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-calendar-range .ant-calendar-input,
textarea.ant-calendar-range .ant-calendar-time-picker-input {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-calendar-range .ant-calendar-input-lg,
.ant-calendar-range .ant-calendar-time-picker-input-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-calendar-range .ant-calendar-input-sm,
.ant-calendar-range .ant-calendar-time-picker-input-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-calendar-range .ant-calendar-input:focus,
.ant-calendar-range .ant-calendar-time-picker-input:focus {
  box-shadow: none
}

.ant-calendar-range .ant-calendar-time-picker-icon {
  display: none
}

.ant-calendar-range.ant-calendar-week-number {
  width: 574px
}

.ant-calendar-range.ant-calendar-week-number .ant-calendar-range-part {
  width: 286px
}

.ant-calendar-range .ant-calendar-decade-panel,
.ant-calendar-range .ant-calendar-month-panel,
.ant-calendar-range .ant-calendar-year-panel {
  top: 34px
}

.ant-calendar-range .ant-calendar-month-panel .ant-calendar-year-panel {
  top: 0
}

.ant-calendar-range .ant-calendar-decade-panel-table,
.ant-calendar-range .ant-calendar-month-panel-table,
.ant-calendar-range .ant-calendar-year-panel-table {
  height: 208px
}

.ant-calendar-range .ant-calendar-in-range-cell {
  position: relative;
  border-radius: 0
}

.ant-calendar-range .ant-calendar-in-range-cell>div {
  position: relative;
  z-index: 1
}

.ant-calendar-range .ant-calendar-in-range-cell:before {
  position: absolute;
  top: 4px;
  right: 0;
  bottom: 4px;
  left: 0;
  display: block;
  background: #e8f8ff;
  border: 0;
  border-radius: 0;
  content: ""
}

.ant-calendar-range .ant-calendar-footer-extra {
  float: left
}

div.ant-calendar-range-quick-selector {
  text-align: left
}

div.ant-calendar-range-quick-selector>a {
  margin-right: 8px
}

.ant-calendar-range .ant-calendar-decade-panel-header,
.ant-calendar-range .ant-calendar-header,
.ant-calendar-range .ant-calendar-month-panel-header,
.ant-calendar-range .ant-calendar-year-panel-header {
  border-bottom: 0
}

.ant-calendar-range .ant-calendar-body,
.ant-calendar-range .ant-calendar-decade-panel-body,
.ant-calendar-range .ant-calendar-month-panel-body,
.ant-calendar-range .ant-calendar-year-panel-body {
  border-top: 1px solid #e8e8e8
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker {
  top: 68px;
  z-index: 2;
  width: 100%;
  height: 207px
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker-panel {
  height: 267px;
  margin-top: -34px
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker-inner {
  height: 100%;
  padding-top: 40px;
  background: none
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker-combobox {
  display: inline-block;
  height: 100%;
  background-color: #fff;
  border-top: 1px solid #e8e8e8
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker-select {
  height: 100%
}

.ant-calendar-range.ant-calendar-time .ant-calendar-time-picker-select ul {
  max-height: 100%
}

.ant-calendar-range.ant-calendar-time .ant-calendar-footer .ant-calendar-time-picker-btn {
  margin-right: 8px
}

.ant-calendar-range.ant-calendar-time .ant-calendar-today-btn {
  height: 22px;
  margin: 8px 12px;
  line-height: 22px
}

.ant-calendar-range-with-ranges.ant-calendar-time .ant-calendar-time-picker {
  height: 233px
}

.ant-calendar-range.ant-calendar-show-time-picker .ant-calendar-body {
  border-top-color: transparent
}

.ant-calendar-time-picker {
  position: absolute;
  top: 40px;
  width: 100%;
  background-color: #fff
}

.ant-calendar-time-picker-panel {
  position: absolute;
  z-index: 1050;
  width: 100%
}

.ant-calendar-time-picker-inner {
  position: relative;
  display: inline-block;
  width: 100%;
  overflow: hidden;
  font-size: 14px;
  line-height: 1.5;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  outline: none
}

.ant-calendar-time-picker-column-1,
.ant-calendar-time-picker-column-1 .ant-calendar-time-picker-select,
.ant-calendar-time-picker-combobox {
  width: 100%
}

.ant-calendar-time-picker-column-2 .ant-calendar-time-picker-select {
  width: 50%
}

.ant-calendar-time-picker-column-3 .ant-calendar-time-picker-select {
  width: 33.33%
}

.ant-calendar-time-picker-column-4 .ant-calendar-time-picker-select {
  width: 25%
}

.ant-calendar-time-picker-input-wrap {
  display: none
}

.ant-calendar-time-picker-select {
  position: relative;
  float: left;
  height: 226px;
  overflow: hidden;
  font-size: 14px;
  border-right: 1px solid #e8e8e8
}

.ant-calendar-time-picker-select:hover {
  overflow-y: auto
}

.ant-calendar-time-picker-select:first-child {
  margin-left: 0;
  border-left: 0
}

.ant-calendar-time-picker-select:last-child {
  border-right: 0
}

.ant-calendar-time-picker-select ul {
  width: 100%;
  max-height: 206px;
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-calendar-time-picker-select li {
  width: 100%;
  height: 24px;
  margin: 0;
  line-height: 24px;
  text-align: center;
  list-style: none;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-calendar-time-picker-select li:last-child:after {
  display: block;
  height: 202px;
  content: ""
}

.ant-calendar-time-picker-select li:hover {
  background: #e8f8ff
}

.ant-calendar-time-picker-select li:focus {
  color: #03a9f4;
  font-weight: 600;
  outline: none
}

li.ant-calendar-time-picker-select-option-selected {
  font-weight: 600;
  background: #f5f5f5
}

li.ant-calendar-time-picker-select-option-disabled {
  color: rgba(0, 0, 0, .25)
}

li.ant-calendar-time-picker-select-option-disabled:hover {
  background: transparent;
  cursor: not-allowed
}

.ant-calendar-time .ant-calendar-day-select {
  display: inline-block;
  padding: 0 2px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  line-height: 34px
}

.ant-calendar-time .ant-calendar-footer {
  position: relative;
  height: auto
}

.ant-calendar-time .ant-calendar-footer-btn {
  text-align: right
}

.ant-calendar-time .ant-calendar-footer .ant-calendar-today-btn {
  float: left;
  margin: 0
}

.ant-calendar-time .ant-calendar-footer .ant-calendar-time-picker-btn {
  display: inline-block;
  margin-right: 8px
}

.ant-calendar-time .ant-calendar-footer .ant-calendar-time-picker-btn-disabled {
  color: rgba(0, 0, 0, .25)
}

.ant-calendar-month-panel {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 10;
  background: #fff;
  border-radius: 4px;
  outline: none
}

.ant-calendar-month-panel>div {
  display: flex;
  flex-direction: column;
  height: 100%
}

.ant-calendar-month-panel-hidden {
  display: none
}

.ant-calendar-month-panel-header {
  height: 40px;
  line-height: 40px;
  text-align: center;
  border-bottom: 1px solid #e8e8e8;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  position: relative
}

.ant-calendar-month-panel-header a:hover {
  color: #2bc3ff
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-century-select,
.ant-calendar-month-panel-header .ant-calendar-month-panel-decade-select,
.ant-calendar-month-panel-header .ant-calendar-month-panel-month-select,
.ant-calendar-month-panel-header .ant-calendar-month-panel-year-select {
  display: inline-block;
  padding: 0 2px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  line-height: 40px
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-century-select-arrow,
.ant-calendar-month-panel-header .ant-calendar-month-panel-decade-select-arrow,
.ant-calendar-month-panel-header .ant-calendar-month-panel-month-select-arrow,
.ant-calendar-month-panel-header .ant-calendar-month-panel-year-select-arrow {
  display: none
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn {
  position: absolute;
  top: 0;
  display: inline-block;
  padding: 0 5px;
  color: rgba(0, 0, 0, .45);
  font-size: 16px;
  font-family: Arial, Hiragino Sans GB, Microsoft Yahei, "Microsoft Sans Serif", sans-serif;
  line-height: 40px
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn {
  left: 7px;
  height: 100%
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn:hover:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn:hover:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-year-btn:after {
  display: none;
  position: relative;
  left: -3px;
  display: inline-block
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn {
  right: 7px;
  height: 100%
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:hover:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:hover:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:after {
  display: none
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:before,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:before {
  position: relative;
  left: 3px
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-century-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-decade-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-year-btn:after {
  display: inline-block
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn {
  left: 29px;
  height: 100%
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-prev-month-btn:after {
  display: none
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn {
  right: 29px;
  height: 100%
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:hover:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:after {
  display: none
}

.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:after,
.ant-calendar-month-panel-header .ant-calendar-month-panel-next-month-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-month-panel-body {
  flex: 1 1
}

.ant-calendar-month-panel-footer {
  border-top: 1px solid #e8e8e8
}

.ant-calendar-month-panel-footer .ant-calendar-footer-extra {
  padding: 0 12px
}

.ant-calendar-month-panel-table {
  width: 100%;
  height: 100%;
  table-layout: fixed;
  border-collapse: separate
}

.ant-calendar-month-panel-selected-cell .ant-calendar-month-panel-month,
.ant-calendar-month-panel-selected-cell .ant-calendar-month-panel-month:hover {
  color: #fff;
  background: #03a9f4
}

.ant-calendar-month-panel-cell {
  text-align: center
}

.ant-calendar-month-panel-cell-disabled .ant-calendar-month-panel-month,
.ant-calendar-month-panel-cell-disabled .ant-calendar-month-panel-month:hover {
  color: rgba(0, 0, 0, .25);
  background: #f5f5f5;
  cursor: not-allowed
}

.ant-calendar-month-panel-month {
  display: inline-block;
  height: 24px;
  margin: 0 auto;
  padding: 0 8px;
  color: rgba(0, 0, 0, .65);
  line-height: 24px;
  text-align: center;
  background: transparent;
  border-radius: 2px;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-calendar-month-panel-month:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-calendar-year-panel {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 10;
  background: #fff;
  border-radius: 4px;
  outline: none
}

.ant-calendar-year-panel>div {
  display: flex;
  flex-direction: column;
  height: 100%
}

.ant-calendar-year-panel-hidden {
  display: none
}

.ant-calendar-year-panel-header {
  height: 40px;
  line-height: 40px;
  text-align: center;
  border-bottom: 1px solid #e8e8e8;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  position: relative
}

.ant-calendar-year-panel-header a:hover {
  color: #2bc3ff
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-century-select,
.ant-calendar-year-panel-header .ant-calendar-year-panel-decade-select,
.ant-calendar-year-panel-header .ant-calendar-year-panel-month-select,
.ant-calendar-year-panel-header .ant-calendar-year-panel-year-select {
  display: inline-block;
  padding: 0 2px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  line-height: 40px
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-century-select-arrow,
.ant-calendar-year-panel-header .ant-calendar-year-panel-decade-select-arrow,
.ant-calendar-year-panel-header .ant-calendar-year-panel-month-select-arrow,
.ant-calendar-year-panel-header .ant-calendar-year-panel-year-select-arrow {
  display: none
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn {
  position: absolute;
  top: 0;
  display: inline-block;
  padding: 0 5px;
  color: rgba(0, 0, 0, .45);
  font-size: 16px;
  font-family: Arial, Hiragino Sans GB, Microsoft Yahei, "Microsoft Sans Serif", sans-serif;
  line-height: 40px
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn {
  left: 7px;
  height: 100%
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn:hover:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn:hover:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-year-btn:after {
  display: none;
  position: relative;
  left: -3px;
  display: inline-block
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn {
  right: 7px;
  height: 100%
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:hover:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:hover:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:after {
  display: none
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:before,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:before {
  position: relative;
  left: 3px
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-century-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-decade-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-year-btn:after {
  display: inline-block
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn {
  left: 29px;
  height: 100%
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-prev-month-btn:after {
  display: none
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn {
  right: 29px;
  height: 100%
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:hover:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:after {
  display: none
}

.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:after,
.ant-calendar-year-panel-header .ant-calendar-year-panel-next-month-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-year-panel-body {
  flex: 1 1
}

.ant-calendar-year-panel-footer {
  border-top: 1px solid #e8e8e8
}

.ant-calendar-year-panel-footer .ant-calendar-footer-extra {
  padding: 0 12px
}

.ant-calendar-year-panel-table {
  width: 100%;
  height: 100%;
  table-layout: fixed;
  border-collapse: separate
}

.ant-calendar-year-panel-cell {
  text-align: center
}

.ant-calendar-year-panel-year {
  display: inline-block;
  height: 24px;
  margin: 0 auto;
  padding: 0 8px;
  color: rgba(0, 0, 0, .65);
  line-height: 24px;
  text-align: center;
  background: transparent;
  border-radius: 2px;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-calendar-year-panel-year:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-calendar-year-panel-selected-cell .ant-calendar-year-panel-year,
.ant-calendar-year-panel-selected-cell .ant-calendar-year-panel-year:hover {
  color: #fff;
  background: #03a9f4
}

.ant-calendar-year-panel-last-decade-cell .ant-calendar-year-panel-year,
.ant-calendar-year-panel-next-decade-cell .ant-calendar-year-panel-year {
  color: rgba(0, 0, 0, .25);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-calendar-decade-panel {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 10;
  display: flex;
  flex-direction: column;
  background: #fff;
  border-radius: 4px;
  outline: none
}

.ant-calendar-decade-panel-hidden {
  display: none
}

.ant-calendar-decade-panel-header {
  height: 40px;
  line-height: 40px;
  text-align: center;
  border-bottom: 1px solid #e8e8e8;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  position: relative
}

.ant-calendar-decade-panel-header a:hover {
  color: #2bc3ff
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-century-select,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-decade-select,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-month-select,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-year-select {
  display: inline-block;
  padding: 0 2px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  line-height: 40px
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-century-select-arrow,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-decade-select-arrow,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-month-select-arrow,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-year-select-arrow {
  display: none
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn {
  position: absolute;
  top: 0;
  display: inline-block;
  padding: 0 5px;
  color: rgba(0, 0, 0, .45);
  font-size: 16px;
  font-family: Arial, Hiragino Sans GB, Microsoft Yahei, "Microsoft Sans Serif", sans-serif;
  line-height: 40px
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn {
  left: 7px;
  height: 100%
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn:hover:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn:hover:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-year-btn:after {
  display: none;
  position: relative;
  left: -3px;
  display: inline-block
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn {
  right: 7px;
  height: 100%
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:hover:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:hover:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:after {
  display: none
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:before,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:before {
  position: relative;
  left: 3px
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-century-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-decade-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-year-btn:after {
  display: inline-block
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn {
  left: 29px;
  height: 100%
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-prev-month-btn:after {
  display: none
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn {
  right: 29px;
  height: 100%
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:before {
  position: relative;
  top: -1px;
  display: inline-block;
  width: 8px;
  height: 8px;
  vertical-align: middle;
  border: 0 solid #aaa;
  border-width: 1.5px 0 0 1.5px;
  border-radius: 1px;
  -webkit-transform: rotate(-45deg) scale(.8);
  transform: rotate(-45deg) scale(.8);
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:hover:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:hover:before {
  border-color: rgba(0, 0, 0, .65)
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:after {
  display: none
}

.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:after,
.ant-calendar-decade-panel-header .ant-calendar-decade-panel-next-month-btn:before {
  -webkit-transform: rotate(135deg) scale(.8);
  transform: rotate(135deg) scale(.8)
}

.ant-calendar-decade-panel-body {
  flex: 1 1
}

.ant-calendar-decade-panel-footer {
  border-top: 1px solid #e8e8e8
}

.ant-calendar-decade-panel-footer .ant-calendar-footer-extra {
  padding: 0 12px
}

.ant-calendar-decade-panel-table {
  width: 100%;
  height: 100%;
  table-layout: fixed;
  border-collapse: separate
}

.ant-calendar-decade-panel-cell {
  white-space: nowrap;
  text-align: center
}

.ant-calendar-decade-panel-decade {
  display: inline-block;
  height: 24px;
  margin: 0 auto;
  padding: 0 6px;
  color: rgba(0, 0, 0, .65);
  line-height: 24px;
  text-align: center;
  background: transparent;
  border-radius: 2px;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-calendar-decade-panel-decade:hover {
  background: #e8f8ff;
  cursor: pointer
}

.ant-calendar-decade-panel-selected-cell .ant-calendar-decade-panel-decade,
.ant-calendar-decade-panel-selected-cell .ant-calendar-decade-panel-decade:hover {
  color: #fff;
  background: #03a9f4
}

.ant-calendar-decade-panel-last-century-cell .ant-calendar-decade-panel-decade,
.ant-calendar-decade-panel-next-century-cell .ant-calendar-decade-panel-decade {
  color: rgba(0, 0, 0, .25);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-calendar-month .ant-calendar-month-header-wrap {
  position: relative;
  height: 288px
}

.ant-calendar-month .ant-calendar-month-panel,
.ant-calendar-month .ant-calendar-year-panel {
  top: 0;
  height: 100%
}

.ant-calendar-week-number-cell {
  opacity: .5
}

.ant-calendar-week-number .ant-calendar-body tr {
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-calendar-week-number .ant-calendar-body tr:hover {
  background: #e6fbff
}

.ant-calendar-week-number .ant-calendar-body tr.ant-calendar-active-week {
  font-weight: 700;
  background: #a6efff
}

.ant-calendar-week-number .ant-calendar-body tr .ant-calendar-selected-day .ant-calendar-date,
.ant-calendar-week-number .ant-calendar-body tr .ant-calendar-selected-day:hover .ant-calendar-date {
  color: rgba(0, 0, 0, .65);
  background: transparent
}

.ant-descriptions-title {
  margin-bottom: 20px;
  color: rgba(0, 0, 0, .85);
  font-weight: 700;
  font-size: 16px;
  line-height: 1.5
}

.ant-descriptions-view {
  width: 100%;
  overflow: hidden;
  border-radius: 4px
}

.ant-descriptions-view table {
  width: 100%;
  table-layout: fixed
}

.ant-descriptions-row>td,
.ant-descriptions-row>th {
  padding-bottom: 16px
}

.ant-descriptions-row:last-child {
  border-bottom: none
}

.ant-descriptions-item-label {
  color: rgba(0, 0, 0, .85);
  font-weight: 400;
  font-size: 14px;
  line-height: 1.5;
  white-space: nowrap
}

.ant-descriptions-item-label:after {
  position: relative;
  top: -.5px;
  margin: 0 8px 0 2px;
  content: " "
}

.ant-descriptions-item-colon:after {
  content: ":"
}

.ant-descriptions-item-no-label:after {
  margin: 0;
  content: ""
}

.ant-descriptions-item-content {
  display: table-cell;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5
}

.ant-descriptions-item {
  padding-bottom: 0
}

.ant-descriptions-item>span {
  display: inline-block
}

.ant-descriptions-middle .ant-descriptions-row>td,
.ant-descriptions-middle .ant-descriptions-row>th {
  padding-bottom: 12px
}

.ant-descriptions-small .ant-descriptions-row>td,
.ant-descriptions-small .ant-descriptions-row>th {
  padding-bottom: 8px
}

.ant-descriptions-bordered .ant-descriptions-view {
  border: 1px solid #e8e8e8
}

.ant-descriptions-bordered .ant-descriptions-view>table {
  table-layout: auto
}

.ant-descriptions-bordered .ant-descriptions-item-content,
.ant-descriptions-bordered .ant-descriptions-item-label {
  padding: 16px 24px;
  border-right: 1px solid #e8e8e8
}

.ant-descriptions-bordered .ant-descriptions-item-content:last-child,
.ant-descriptions-bordered .ant-descriptions-item-label:last-child {
  border-right: none
}

.ant-descriptions-bordered .ant-descriptions-item-label {
  background-color: #fafafa
}

.ant-descriptions-bordered .ant-descriptions-item-label:after {
  display: none
}

.ant-descriptions-bordered .ant-descriptions-row {
  border-bottom: 1px solid #e8e8e8
}

.ant-descriptions-bordered .ant-descriptions-row:last-child {
  border-bottom: none
}

.ant-descriptions-bordered.ant-descriptions-middle .ant-descriptions-item-content,
.ant-descriptions-bordered.ant-descriptions-middle .ant-descriptions-item-label {
  padding: 12px 24px
}

.ant-descriptions-bordered.ant-descriptions-small .ant-descriptions-item-content,
.ant-descriptions-bordered.ant-descriptions-small .ant-descriptions-item-label {
  padding: 8px 16px
}

.ant-divider {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  background: #e8e8e8
}

.ant-divider,
.ant-divider-vertical {
  position: relative;
  top: -.06em;
  display: inline-block;
  width: 1px;
  height: .9em;
  margin: 0 8px;
  vertical-align: middle
}

.ant-divider-horizontal {
  display: block;
  clear: both;
  width: 100%;
  min-width: 100%;
  height: 1px;
  margin: 24px 0
}

.ant-divider-horizontal.ant-divider-with-text-center,
.ant-divider-horizontal.ant-divider-with-text-left,
.ant-divider-horizontal.ant-divider-with-text-right {
  display: table;
  margin: 16px 0;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  white-space: nowrap;
  text-align: center;
  background: transparent
}

.ant-divider-horizontal.ant-divider-with-text-center:after,
.ant-divider-horizontal.ant-divider-with-text-center:before,
.ant-divider-horizontal.ant-divider-with-text-left:after,
.ant-divider-horizontal.ant-divider-with-text-left:before,
.ant-divider-horizontal.ant-divider-with-text-right:after,
.ant-divider-horizontal.ant-divider-with-text-right:before {
  position: relative;
  top: 50%;
  display: table-cell;
  width: 50%;
  border-top: 1px solid #e8e8e8;
  -webkit-transform: translateY(50%);
  transform: translateY(50%);
  content: ""
}

.ant-divider-horizontal.ant-divider-with-text-left .ant-divider-inner-text,
.ant-divider-horizontal.ant-divider-with-text-right .ant-divider-inner-text {
  display: inline-block;
  padding: 0 10px
}

.ant-divider-horizontal.ant-divider-with-text-left:before {
  top: 50%;
  width: 5%
}

.ant-divider-horizontal.ant-divider-with-text-left:after,
.ant-divider-horizontal.ant-divider-with-text-right:before {
  top: 50%;
  width: 95%
}

.ant-divider-horizontal.ant-divider-with-text-right:after {
  top: 50%;
  width: 5%
}

.ant-divider-inner-text {
  display: inline-block;
  padding: 0 24px
}

.ant-divider-dashed {
  background: none;
  border: dashed #e8e8e8;
  border-width: 1px 0 0
}

.ant-divider-horizontal.ant-divider-with-text-center.ant-divider-dashed,
.ant-divider-horizontal.ant-divider-with-text-left.ant-divider-dashed,
.ant-divider-horizontal.ant-divider-with-text-right.ant-divider-dashed {
  border-top: 0
}

.ant-divider-horizontal.ant-divider-with-text-center.ant-divider-dashed:after,
.ant-divider-horizontal.ant-divider-with-text-center.ant-divider-dashed:before,
.ant-divider-horizontal.ant-divider-with-text-left.ant-divider-dashed:after,
.ant-divider-horizontal.ant-divider-with-text-left.ant-divider-dashed:before,
.ant-divider-horizontal.ant-divider-with-text-right.ant-divider-dashed:after,
.ant-divider-horizontal.ant-divider-with-text-right.ant-divider-dashed:before {
  border-style: dashed none none
}

.ant-divider-vertical.ant-divider-dashed {
  border-width: 0 0 0 1px
}

.ant-drawer {
  position: fixed;
  z-index: 1000;
  width: 0;
  height: 100%;
  -webkit-transition: height 0s ease .3s, width 0s ease .3s, -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: height 0s ease .3s, width 0s ease .3s, -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), height 0s ease .3s, width 0s ease .3s;
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), height 0s ease .3s, width 0s ease .3s, -webkit-transform .3s cubic-bezier(.7, .3, .1, 1)
}

.ant-drawer>* {
  -webkit-transition: box-shadow .3s cubic-bezier(.7, .3, .1, 1), -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: box-shadow .3s cubic-bezier(.7, .3, .1, 1), -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), box-shadow .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), box-shadow .3s cubic-bezier(.7, .3, .1, 1), -webkit-transform .3s cubic-bezier(.7, .3, .1, 1)
}

.ant-drawer-content-wrapper {
  position: absolute
}

.ant-drawer .ant-drawer-content {
  width: 100%;
  height: 100%
}

.ant-drawer-left,
.ant-drawer-right {
  top: 0;
  width: 0;
  height: 100%
}

.ant-drawer-left .ant-drawer-content-wrapper,
.ant-drawer-right .ant-drawer-content-wrapper {
  height: 100%
}

.ant-drawer-left.ant-drawer-open,
.ant-drawer-right.ant-drawer-open {
  width: 100%;
  -webkit-transition: -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), -webkit-transform .3s cubic-bezier(.7, .3, .1, 1)
}

.ant-drawer-left.ant-drawer-open.no-mask,
.ant-drawer-right.ant-drawer-open.no-mask {
  width: 0
}

.ant-drawer-left.ant-drawer-open .ant-drawer-content-wrapper {
  box-shadow: 2px 0 8px rgba(0, 0, 0, .15)
}

.ant-drawer-right,
.ant-drawer-right .ant-drawer-content-wrapper {
  right: 0
}

.ant-drawer-right.ant-drawer-open .ant-drawer-content-wrapper {
  box-shadow: -2px 0 8px rgba(0, 0, 0, .15)
}

.ant-drawer-right.ant-drawer-open.no-mask {
  right: 1px;
  -webkit-transform: translateX(1px);
  transform: translateX(1px)
}

.ant-drawer-bottom,
.ant-drawer-top {
  left: 0;
  width: 100%;
  height: 0%
}

.ant-drawer-bottom .ant-drawer-content-wrapper,
.ant-drawer-top .ant-drawer-content-wrapper {
  width: 100%
}

.ant-drawer-bottom.ant-drawer-open,
.ant-drawer-top.ant-drawer-open {
  height: 100%;
  -webkit-transition: -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: -webkit-transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1);
  transition: transform .3s cubic-bezier(.7, .3, .1, 1), -webkit-transform .3s cubic-bezier(.7, .3, .1, 1)
}

.ant-drawer-bottom.ant-drawer-open.no-mask,
.ant-drawer-top.ant-drawer-open.no-mask {
  height: 0%
}

.ant-drawer-top {
  top: 0
}

.ant-drawer-top.ant-drawer-open .ant-drawer-content-wrapper {
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-drawer-bottom,
.ant-drawer-bottom .ant-drawer-content-wrapper {
  bottom: 0
}

.ant-drawer-bottom.ant-drawer-open .ant-drawer-content-wrapper {
  box-shadow: 0 -2px 8px rgba(0, 0, 0, .15)
}

.ant-drawer-bottom.ant-drawer-open.no-mask {
  bottom: 1px;
  -webkit-transform: translateY(1px);
  transform: translateY(1px)
}

.ant-drawer.ant-drawer-open .ant-drawer-mask {
  height: 100%;
  opacity: 1;
  -webkit-transition: none;
  transition: none;
  -webkit-animation: antdDrawerFadeIn .3s cubic-bezier(.7, .3, .1, 1);
  animation: antdDrawerFadeIn .3s cubic-bezier(.7, .3, .1, 1)
}

.ant-drawer-title {
  margin: 0;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  line-height: 22px
}

.ant-drawer-content {
  position: relative;
  z-index: 1;
  background-color: #fff;
  background-clip: padding-box;
  border: 0
}

.ant-drawer-close {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 10;
  display: block;
  width: 56px;
  height: 56px;
  padding: 0;
  color: rgba(0, 0, 0, .45);
  font-weight: 700;
  font-size: 16px;
  font-style: normal;
  line-height: 56px;
  text-align: center;
  text-transform: none;
  text-decoration: none;
  background: transparent;
  border: 0;
  outline: 0;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s;
  text-rendering: auto
}

.ant-drawer-close:focus,
.ant-drawer-close:hover {
  color: rgba(0, 0, 0, .75);
  text-decoration: none
}

.ant-drawer-header {
  position: relative;
  padding: 16px 24px;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 4px 4px 0 0
}

.ant-drawer-header,
.ant-drawer-header-no-title {
  color: rgba(0, 0, 0, .65);
  background: #fff
}

.ant-drawer-body {
  padding: 24px;
  font-size: 14px;
  line-height: 1.5;
  word-wrap: break-word
}

.ant-drawer-mask {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 0;
  background-color: rgba(0, 0, 0, .45);
  opacity: 0;
  filter: alpha(opacity=45);
  -webkit-transition: opacity .3s linear, height 0s ease .3s;
  transition: opacity .3s linear, height 0s ease .3s
}

.ant-drawer-open-content {
  box-shadow: 0 4px 12px rgba(0, 0, 0, .15)
}

@-webkit-keyframes antdDrawerFadeIn {
  0% {
    opacity: 0
  }

  to {
    opacity: 1
  }
}

@keyframes antdDrawerFadeIn {
  0% {
    opacity: 0
  }

  to {
    opacity: 1
  }
}

.ant-dropdown {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  top: -9999px;
  left: -9999px;
  z-index: 1050;
  display: block
}

.ant-dropdown:before {
  position: absolute;
  top: -7px;
  right: 0;
  bottom: -7px;
  left: -7px;
  z-index: -9999;
  opacity: .0001;
  content: " "
}

.ant-dropdown-wrap {
  position: relative
}

.ant-dropdown-wrap .ant-btn>.anticon-down {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

:root .ant-dropdown-wrap .ant-btn>.anticon-down {
  font-size: 12px
}

.ant-dropdown-wrap .anticon-down:before {
  -webkit-transition: -webkit-transform .2s;
  transition: -webkit-transform .2s;
  transition: transform .2s;
  transition: transform .2s, -webkit-transform .2s
}

.ant-dropdown-wrap-open .anticon-down:before {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.ant-dropdown-hidden,
.ant-dropdown-menu-hidden {
  display: none
}

.ant-dropdown-menu {
  position: relative;
  margin: 0;
  padding: 4px 0;
  text-align: left;
  list-style-type: none;
  background-color: #fff;
  background-clip: padding-box;
  border-radius: 4px;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15);
  -webkit-transform: translateZ(0)
}

.ant-dropdown-menu-item-group-title {
  padding: 5px 12px;
  color: rgba(0, 0, 0, .45);
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-dropdown-menu-submenu-popup {
  position: absolute;
  z-index: 1050
}

.ant-dropdown-menu-submenu-popup>.ant-dropdown-menu {
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0
}

.ant-dropdown-menu-submenu-popup li,
.ant-dropdown-menu-submenu-popup ul {
  list-style: none
}

.ant-dropdown-menu-submenu-popup ul {
  margin-right: .3em;
  margin-left: .3em
}

.ant-dropdown-menu-item,
.ant-dropdown-menu-submenu-title {
  clear: both;
  margin: 0;
  padding: 5px 12px;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
  white-space: nowrap;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-dropdown-menu-item>span>.anticon:first-child,
.ant-dropdown-menu-submenu-title>span>.anticon:first-child {
  min-width: 12px;
  margin-right: 8px;
  font-size: 12px
}

.ant-dropdown-menu-item>a,
.ant-dropdown-menu-submenu-title>a {
  display: block;
  margin: -5px -12px;
  padding: 5px 12px;
  color: rgba(0, 0, 0, .65);
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-dropdown-menu-item-selected,
.ant-dropdown-menu-item-selected>a,
.ant-dropdown-menu-submenu-title-selected,
.ant-dropdown-menu-submenu-title-selected>a {
  color: #03a9f4;
  background-color: #e8f8ff
}

.ant-dropdown-menu-item:hover,
.ant-dropdown-menu-submenu-title:hover {
  background-color: #e8f8ff
}

.ant-dropdown-menu-item-disabled,
.ant-dropdown-menu-submenu-title-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-dropdown-menu-item-disabled:hover,
.ant-dropdown-menu-submenu-title-disabled:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #fff;
  cursor: not-allowed
}

.ant-dropdown-menu-item-divider,
.ant-dropdown-menu-submenu-title-divider {
  height: 1px;
  margin: 4px 0;
  overflow: hidden;
  line-height: 0;
  background-color: #e8e8e8
}

.ant-dropdown-menu-item .ant-dropdown-menu-submenu-arrow,
.ant-dropdown-menu-submenu-title .ant-dropdown-menu-submenu-arrow {
  position: absolute;
  right: 8px
}

.ant-dropdown-menu-item .ant-dropdown-menu-submenu-arrow-icon,
.ant-dropdown-menu-submenu-title .ant-dropdown-menu-submenu-arrow-icon {
  color: rgba(0, 0, 0, .45);
  font-style: normal;
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

:root .ant-dropdown-menu-item .ant-dropdown-menu-submenu-arrow-icon,
:root .ant-dropdown-menu-submenu-title .ant-dropdown-menu-submenu-arrow-icon {
  font-size: 12px
}

.ant-dropdown-menu-submenu-title {
  padding-right: 26px
}

.ant-dropdown-menu-submenu-vertical {
  position: relative
}

.ant-dropdown-menu-submenu-vertical>.ant-dropdown-menu {
  position: absolute;
  top: 0;
  left: 100%;
  min-width: 100%;
  margin-left: 4px;
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0
}

.ant-dropdown-menu-submenu.ant-dropdown-menu-submenu-disabled .ant-dropdown-menu-submenu-title,
.ant-dropdown-menu-submenu.ant-dropdown-menu-submenu-disabled .ant-dropdown-menu-submenu-title .ant-dropdown-menu-submenu-arrow-icon {
  color: rgba(0, 0, 0, .25);
  background-color: #fff;
  cursor: not-allowed
}

.ant-dropdown-menu-submenu-selected .ant-dropdown-menu-submenu-title {
  color: #03a9f4
}

.ant-dropdown.slide-down-appear.slide-down-appear-active.ant-dropdown-placement-bottomCenter,
.ant-dropdown.slide-down-appear.slide-down-appear-active.ant-dropdown-placement-bottomLeft,
.ant-dropdown.slide-down-appear.slide-down-appear-active.ant-dropdown-placement-bottomRight,
.ant-dropdown.slide-down-enter.slide-down-enter-active.ant-dropdown-placement-bottomCenter,
.ant-dropdown.slide-down-enter.slide-down-enter-active.ant-dropdown-placement-bottomLeft,
.ant-dropdown.slide-down-enter.slide-down-enter-active.ant-dropdown-placement-bottomRight {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn
}

.ant-dropdown.slide-up-appear.slide-up-appear-active.ant-dropdown-placement-topCenter,
.ant-dropdown.slide-up-appear.slide-up-appear-active.ant-dropdown-placement-topLeft,
.ant-dropdown.slide-up-appear.slide-up-appear-active.ant-dropdown-placement-topRight,
.ant-dropdown.slide-up-enter.slide-up-enter-active.ant-dropdown-placement-topCenter,
.ant-dropdown.slide-up-enter.slide-up-enter-active.ant-dropdown-placement-topLeft,
.ant-dropdown.slide-up-enter.slide-up-enter-active.ant-dropdown-placement-topRight {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn
}

.ant-dropdown.slide-down-leave.slide-down-leave-active.ant-dropdown-placement-bottomCenter,
.ant-dropdown.slide-down-leave.slide-down-leave-active.ant-dropdown-placement-bottomLeft,
.ant-dropdown.slide-down-leave.slide-down-leave-active.ant-dropdown-placement-bottomRight {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut
}

.ant-dropdown.slide-up-leave.slide-up-leave-active.ant-dropdown-placement-topCenter,
.ant-dropdown.slide-up-leave.slide-up-leave-active.ant-dropdown-placement-topLeft,
.ant-dropdown.slide-up-leave.slide-up-leave-active.ant-dropdown-placement-topRight {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut
}

.ant-dropdown-link>.anticon.anticon-down,
.ant-dropdown-trigger>.anticon.anticon-down {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

:root .ant-dropdown-link>.anticon.anticon-down,
:root .ant-dropdown-trigger>.anticon.anticon-down {
  font-size: 12px
}

.ant-dropdown-button {
  white-space: nowrap
}

.ant-dropdown-button.ant-btn-group>.ant-btn:last-child:not(:first-child) {
  padding-right: 8px;
  padding-left: 8px
}

.ant-dropdown-button .anticon.anticon-down {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

:root .ant-dropdown-button .anticon.anticon-down {
  font-size: 12px
}

.ant-dropdown-menu-dark,
.ant-dropdown-menu-dark .ant-dropdown-menu {
  background: #fff
}

.ant-dropdown-menu-dark .ant-dropdown-menu-item,
.ant-dropdown-menu-dark .ant-dropdown-menu-item .ant-dropdown-menu-submenu-arrow:after,
.ant-dropdown-menu-dark .ant-dropdown-menu-item>a,
.ant-dropdown-menu-dark .ant-dropdown-menu-item>a .ant-dropdown-menu-submenu-arrow:after,
.ant-dropdown-menu-dark .ant-dropdown-menu-submenu-title,
.ant-dropdown-menu-dark .ant-dropdown-menu-submenu-title .ant-dropdown-menu-submenu-arrow:after {
  color: hsla(0, 0%, 100%, .65)
}

.ant-dropdown-menu-dark .ant-dropdown-menu-item:hover,
.ant-dropdown-menu-dark .ant-dropdown-menu-item>a:hover,
.ant-dropdown-menu-dark .ant-dropdown-menu-submenu-title:hover {
  color: #fff;
  background: transparent
}

.ant-dropdown-menu-dark .ant-dropdown-menu-item-selected,
.ant-dropdown-menu-dark .ant-dropdown-menu-item-selected:hover,
.ant-dropdown-menu-dark .ant-dropdown-menu-item-selected>a {
  color: #fff;
  background: #03a9f4
}

.ant-empty {
  margin: 0 8px;
  font-size: 14px;
  line-height: 22px;
  text-align: center
}

.ant-empty-image {
  height: 100px;
  margin-bottom: 8px
}

.ant-empty-image img {
  height: 100%
}

.ant-empty-image svg {
  height: 100%;
  margin: auto
}

.ant-empty-description {
  margin: 0
}

.ant-empty-footer {
  margin-top: 16px
}

.ant-empty-normal {
  margin: 32px 0;
  color: rgba(0, 0, 0, .25)
}

.ant-empty-normal .ant-empty-image {
  height: 40px
}

.ant-empty-small {
  margin: 8px 0;
  color: rgba(0, 0, 0, .25)
}

.ant-empty-small .ant-empty-image {
  height: 35px
}

.ant-form {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-form legend {
  display: block;
  width: 100%;
  margin-bottom: 20px;
  padding: 0;
  color: rgba(0, 0, 0, .45);
  font-size: 16px;
  line-height: inherit;
  border: 0;
  border-bottom: 1px solid #d9d9d9
}

.ant-form label {
  font-size: 14px
}

.ant-form input[type=search] {
  box-sizing: border-box
}

.ant-form input[type=checkbox],
.ant-form input[type=radio] {
  line-height: normal
}

.ant-form input[type=file] {
  display: block
}

.ant-form input[type=range] {
  display: block;
  width: 100%
}

.ant-form select[multiple],
.ant-form select[size] {
  height: auto
}

.ant-form input[type=checkbox]:focus,
.ant-form input[type=file]:focus,
.ant-form input[type=radio]:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px
}

.ant-form output {
  display: block;
  padding-top: 15px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5
}

.ant-form-item-required:before {
  display: inline-block;
  margin-right: 4px;
  color: #f5222d;
  font-size: 14px;
  font-family: SimSun, sans-serif;
  line-height: 1;
  content: "*"
}

.ant-form-hide-required-mark .ant-form-item-required:before {
  display: none
}

.ant-form-item-label>label {
  color: rgba(0, 0, 0, .85)
}

.ant-form-item-label>label:after {
  content: ":";
  position: relative;
  top: -.5px;
  margin: 0 8px 0 2px
}

.ant-form-item-label>label.ant-form-item-no-colon:after {
  content: " "
}

.ant-form-item {
  box-sizing: border-box;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  margin: 0 0 24px;
  vertical-align: top
}

.ant-form-item label {
  position: relative
}

.ant-form-item label>.anticon {
  font-size: 14px;
  vertical-align: top
}

.ant-form-item-control {
  position: relative;
  line-height: 40px;
  zoom: 1
}

.ant-form-item-control:after,
.ant-form-item-control:before {
  display: table;
  content: ""
}

.ant-form-item-control:after {
  clear: both
}

.ant-form-item-children {
  position: relative
}

.ant-form-item-with-help {
  margin-bottom: 5px
}

.ant-form-item-label {
  display: inline-block;
  overflow: hidden;
  line-height: 39.9999px;
  white-space: nowrap;
  text-align: right;
  vertical-align: middle
}

.ant-form-item-label-left {
  text-align: left
}

.ant-form-item .ant-switch {
  margin: 2px 0 4px
}

.ant-form-explain,
.ant-form-extra {
  clear: both;
  min-height: 22px;
  margin-top: -2px;
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 1.5;
  -webkit-transition: color .3s cubic-bezier(.215, .61, .355, 1);
  transition: color .3s cubic-bezier(.215, .61, .355, 1)
}

.ant-form-explain {
  margin-bottom: -1px
}

.ant-form-extra {
  padding-top: 4px
}

.ant-form-text {
  display: inline-block;
  padding-right: 8px
}

.ant-form-split {
  display: block;
  text-align: center
}

form .has-feedback .ant-input {
  padding-right: 24px
}

form .has-feedback .ant-input-password-icon {
  margin-right: 18px
}

form .has-feedback :not(.ant-input-group-addon)>.ant-select .ant-select-arrow,
form .has-feedback :not(.ant-input-group-addon)>.ant-select .ant-select-selection__clear,
form .has-feedback>.ant-select .ant-select-arrow,
form .has-feedback>.ant-select .ant-select-selection__clear {
  right: 28px
}

form .has-feedback :not(.ant-input-group-addon)>.ant-select .ant-select-selection-selected-value,
form .has-feedback>.ant-select .ant-select-selection-selected-value {
  padding-right: 42px
}

form .has-feedback .ant-cascader-picker-arrow {
  margin-right: 17px
}

form .has-feedback .ant-calendar-picker-clear,
form .has-feedback .ant-calendar-picker-icon,
form .has-feedback .ant-cascader-picker-clear,
form .has-feedback .ant-input-search:not(.ant-input-search-enter-button) .ant-input-suffix,
form .has-feedback .ant-time-picker-clear,
form .has-feedback .ant-time-picker-icon {
  right: 28px
}

form .ant-mentions,
form textarea.ant-input {
  height: auto;
  margin-bottom: 4px
}

form .ant-upload {
  background: transparent
}

form input[type=checkbox],
form input[type=radio] {
  width: 14px;
  height: 14px
}

form .ant-checkbox-inline,
form .ant-radio-inline {
  display: inline-block;
  margin-left: 8px;
  font-weight: 400;
  vertical-align: middle;
  cursor: pointer
}

form .ant-checkbox-inline:first-child,
form .ant-radio-inline:first-child {
  margin-left: 0
}

form .ant-checkbox-vertical,
form .ant-radio-vertical {
  display: block
}

form .ant-checkbox-vertical+.ant-checkbox-vertical,
form .ant-radio-vertical+.ant-radio-vertical {
  margin-left: 0
}

form .ant-input-number+.ant-form-text {
  margin-left: 8px
}

form .ant-input-number-handler-wrap {
  z-index: 2
}

form .ant-cascader-picker,
form .ant-select {
  width: 100%
}

form .ant-input-group .ant-cascader-picker,
form .ant-input-group .ant-select {
  width: auto
}

form .ant-input-group-wrapper,
form :not(.ant-input-group-wrapper)>.ant-input-group {
  position: relative;
  top: -1px;
  display: inline-block;
  vertical-align: middle
}

.ant-col-24.ant-form-item-label,
.ant-col-xl-24.ant-form-item-label,
.ant-form-vertical .ant-form-item-label {
  display: block;
  margin: 0;
  padding: 0 0 8px;
  line-height: 1.5;
  white-space: normal;
  text-align: left
}

.ant-col-24.ant-form-item-label label:after,
.ant-col-xl-24.ant-form-item-label label:after,
.ant-form-vertical .ant-form-item-label label:after {
  display: none
}

.ant-form-vertical .ant-form-item {
  padding-bottom: 8px
}

.ant-form-vertical .ant-form-item-control {
  line-height: 1.5
}

.ant-form-vertical .ant-form-explain {
  margin-top: 2px;
  margin-bottom: -5px
}

.ant-form-vertical .ant-form-extra {
  margin-top: 2px;
  margin-bottom: -4px
}

@media (max-width:575px) {

  .ant-form-item-control-wrapper,
  .ant-form-item-label {
    display: block;
    width: 100%
  }

  .ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-form-item-label label:after {
    display: none
  }

  .ant-col-xs-24.ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-col-xs-24.ant-form-item-label label:after {
    display: none
  }
}

@media (max-width:767px) {
  .ant-col-sm-24.ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-col-sm-24.ant-form-item-label label:after {
    display: none
  }
}

@media (max-width:991px) {
  .ant-col-md-24.ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-col-md-24.ant-form-item-label label:after {
    display: none
  }
}

@media (max-width:1199px) {
  .ant-col-lg-24.ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-col-lg-24.ant-form-item-label label:after {
    display: none
  }
}

@media (max-width:1599px) {
  .ant-col-xl-24.ant-form-item-label {
    display: block;
    margin: 0;
    padding: 0 0 8px;
    line-height: 1.5;
    white-space: normal;
    text-align: left
  }

  .ant-col-xl-24.ant-form-item-label label:after {
    display: none
  }
}

.ant-form-inline .ant-form-item {
  display: inline-block;
  margin-right: 16px;
  margin-bottom: 0
}

.ant-form-inline .ant-form-item-with-help {
  margin-bottom: 24px
}

.ant-form-inline .ant-form-item>.ant-form-item-control-wrapper,
.ant-form-inline .ant-form-item>.ant-form-item-label {
  display: inline-block;
  vertical-align: top
}

.ant-form-inline .ant-form-text,
.ant-form-inline .has-feedback {
  display: inline-block
}

.has-error.has-feedback .ant-form-item-children-icon,
.has-success.has-feedback .ant-form-item-children-icon,
.has-warning.has-feedback .ant-form-item-children-icon,
.is-validating.has-feedback .ant-form-item-children-icon {
  position: absolute;
  top: 50%;
  right: 0;
  z-index: 1;
  width: 32px;
  height: 20px;
  margin-top: -10px;
  font-size: 14px;
  line-height: 20px;
  text-align: center;
  visibility: visible;
  -webkit-animation: zoomIn .3s cubic-bezier(.12, .4, .29, 1.46);
  animation: zoomIn .3s cubic-bezier(.12, .4, .29, 1.46);
  pointer-events: none
}

.has-error.has-feedback .ant-form-item-children-icon svg,
.has-success.has-feedback .ant-form-item-children-icon svg,
.has-warning.has-feedback .ant-form-item-children-icon svg,
.is-validating.has-feedback .ant-form-item-children-icon svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.has-success.has-feedback .ant-form-item-children-icon {
  color: #52c41a;
  -webkit-animation-name: diffZoomIn1 !important;
  animation-name: diffZoomIn1 !important
}

.has-warning .ant-form-explain,
.has-warning .ant-form-split {
  color: #faad14
}

.has-warning .ant-input,
.has-warning .ant-input:hover {
  background-color: #fff;
  border-color: #faad14
}

.has-warning .ant-input:focus {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-warning .ant-input:not([disabled]):hover {
  border-color: #faad14
}

.has-warning .ant-calendar-picker-open .ant-calendar-picker-input {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-warning .ant-input-affix-wrapper .ant-input,
.has-warning .ant-input-affix-wrapper .ant-input:hover {
  background-color: #fff;
  border-color: #faad14
}

.has-warning .ant-input-affix-wrapper .ant-input:focus {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-warning .ant-input-affix-wrapper:hover .ant-input:not(.ant-input-disabled) {
  border-color: #faad14
}

.has-warning .ant-input-prefix {
  color: #faad14
}

.has-warning .ant-input-group-addon {
  color: #faad14;
  background-color: #fff;
  border-color: #faad14
}

.has-warning .has-feedback {
  color: #faad14
}

.has-warning.has-feedback .ant-form-item-children-icon {
  color: #faad14;
  -webkit-animation-name: diffZoomIn3 !important;
  animation-name: diffZoomIn3 !important
}

.has-warning .ant-select-selection,
.has-warning .ant-select-selection:hover {
  border-color: #faad14
}

.has-warning .ant-select-focused .ant-select-selection,
.has-warning .ant-select-open .ant-select-selection {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-warning .ant-calendar-picker-icon:after,
.has-warning .ant-cascader-picker-arrow,
.has-warning .ant-picker-icon:after,
.has-warning .ant-select-arrow,
.has-warning .ant-time-picker-icon:after {
  color: #faad14
}

.has-warning .ant-input-number,
.has-warning .ant-time-picker-input {
  border-color: #faad14
}

.has-warning .ant-input-number-focused,
.has-warning .ant-input-number:focus,
.has-warning .ant-time-picker-input-focused,
.has-warning .ant-time-picker-input:focus {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-warning .ant-input-number:not([disabled]):hover,
.has-warning .ant-time-picker-input:not([disabled]):hover {
  border-color: #faad14
}

.has-warning .ant-cascader-picker:focus .ant-cascader-input {
  border-color: #ffc53d;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(250, 173, 20, .2)
}

.has-error .ant-form-explain,
.has-error .ant-form-split {
  color: #f5222d
}

.has-error .ant-input,
.has-error .ant-input:hover {
  background-color: #fff;
  border-color: #f5222d
}

.has-error .ant-input:focus {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-input:not([disabled]):hover {
  border-color: #f5222d
}

.has-error .ant-calendar-picker-open .ant-calendar-picker-input {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-input-affix-wrapper .ant-input,
.has-error .ant-input-affix-wrapper .ant-input:hover {
  background-color: #fff;
  border-color: #f5222d
}

.has-error .ant-input-affix-wrapper .ant-input:focus {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-input-affix-wrapper:hover .ant-input:not(.ant-input-disabled) {
  border-color: #f5222d
}

.has-error .ant-input-prefix {
  color: #f5222d
}

.has-error .ant-input-group-addon {
  color: #f5222d;
  background-color: #fff;
  border-color: #f5222d
}

.has-error .has-feedback {
  color: #f5222d
}

.has-error.has-feedback .ant-form-item-children-icon {
  color: #f5222d;
  -webkit-animation-name: diffZoomIn2 !important;
  animation-name: diffZoomIn2 !important
}

.has-error .ant-select-selection,
.has-error .ant-select-selection:hover {
  border-color: #f5222d
}

.has-error .ant-select-focused .ant-select-selection,
.has-error .ant-select-open .ant-select-selection {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-select.ant-select-auto-complete .ant-input:focus {
  border-color: #f5222d
}

.has-error .ant-input-group-addon .ant-select-selection {
  border-color: transparent;
  box-shadow: none
}

.has-error .ant-calendar-picker-icon:after,
.has-error .ant-cascader-picker-arrow,
.has-error .ant-picker-icon:after,
.has-error .ant-select-arrow,
.has-error .ant-time-picker-icon:after {
  color: #f5222d
}

.has-error .ant-input-number,
.has-error .ant-time-picker-input {
  border-color: #f5222d
}

.has-error .ant-input-number-focused,
.has-error .ant-input-number:focus,
.has-error .ant-time-picker-input-focused,
.has-error .ant-time-picker-input:focus {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-input-number:not([disabled]):hover,
.has-error .ant-mention-wrapper .ant-mention-editor,
.has-error .ant-mention-wrapper .ant-mention-editor:not([disabled]):hover,
.has-error .ant-time-picker-input:not([disabled]):hover {
  border-color: #f5222d
}

.has-error .ant-cascader-picker:focus .ant-cascader-input,
.has-error .ant-mention-wrapper.ant-mention-active:not([disabled]) .ant-mention-editor,
.has-error .ant-mention-wrapper .ant-mention-editor:not([disabled]):focus {
  border-color: #ff4d4f;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(245, 34, 45, .2)
}

.has-error .ant-transfer-list {
  border-color: #f5222d
}

.has-error .ant-transfer-list-search:not([disabled]) {
  border-color: #d9d9d9
}

.has-error .ant-transfer-list-search:not([disabled]):hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.has-error .ant-transfer-list-search:not([disabled]):focus {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.is-validating.has-feedback .ant-form-item-children-icon {
  display: inline-block;
  color: #03a9f4
}

.ant-advanced-search-form .ant-form-item {
  margin-bottom: 24px
}

.ant-advanced-search-form .ant-form-item-with-help {
  margin-bottom: 5px
}

.show-help-appear,
.show-help-enter,
.show-help-leave {
  -webkit-animation-duration: .3s;
  animation-duration: .3s;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.show-help-appear.show-help-appear-active,
.show-help-enter.show-help-enter-active {
  -webkit-animation-name: antShowHelpIn;
  animation-name: antShowHelpIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.show-help-leave.show-help-leave-active {
  -webkit-animation-name: antShowHelpOut;
  animation-name: antShowHelpOut;
  -webkit-animation-play-state: running;
  animation-play-state: running;
  pointer-events: none
}

.show-help-appear,
.show-help-enter {
  opacity: 0
}

.show-help-appear,
.show-help-enter,
.show-help-leave {
  -webkit-animation-timing-function: cubic-bezier(.645, .045, .355, 1);
  animation-timing-function: cubic-bezier(.645, .045, .355, 1)
}

@-webkit-keyframes antShowHelpIn {
  0% {
    -webkit-transform: translateY(-5px);
    transform: translateY(-5px);
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    opacity: 1
  }
}

@keyframes antShowHelpIn {
  0% {
    -webkit-transform: translateY(-5px);
    transform: translateY(-5px);
    opacity: 0
  }

  to {
    -webkit-transform: translateY(0);
    transform: translateY(0);
    opacity: 1
  }
}

@-webkit-keyframes antShowHelpOut {
  to {
    -webkit-transform: translateY(-5px);
    transform: translateY(-5px);
    opacity: 0
  }
}

@keyframes antShowHelpOut {
  to {
    -webkit-transform: translateY(-5px);
    transform: translateY(-5px);
    opacity: 0
  }
}

@-webkit-keyframes diffZoomIn1 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@keyframes diffZoomIn1 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@-webkit-keyframes diffZoomIn2 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@keyframes diffZoomIn2 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@-webkit-keyframes diffZoomIn3 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@keyframes diffZoomIn3 {
  0% {
    -webkit-transform: scale(0);
    transform: scale(0)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

.ant-row {
  position: relative;
  height: auto;
  margin-right: 0;
  margin-left: 0;
  zoom: 1;
  display: block;
  box-sizing: border-box
}

.ant-row:after,
.ant-row:before {
  display: table;
  content: ""
}

.ant-row:after {
  clear: both
}

.ant-row-flex {
  display: flex;
  flex-flow: row wrap
}

.ant-row-flex:after,
.ant-row-flex:before {
  display: flex
}

.ant-row-flex-start {
  justify-content: flex-start
}

.ant-row-flex-center {
  justify-content: center
}

.ant-row-flex-end {
  justify-content: flex-end
}

.ant-row-flex-space-between {
  justify-content: space-between
}

.ant-row-flex-space-around {
  justify-content: space-around
}

.ant-row-flex-top {
  align-items: flex-start
}

.ant-row-flex-middle {
  align-items: center
}

.ant-row-flex-bottom {
  align-items: flex-end
}

.ant-col {
  position: relative;
  min-height: 1px
}

.ant-col-1,
.ant-col-2,
.ant-col-3,
.ant-col-4,
.ant-col-5,
.ant-col-6,
.ant-col-7,
.ant-col-8,
.ant-col-9,
.ant-col-10,
.ant-col-11,
.ant-col-12,
.ant-col-13,
.ant-col-14,
.ant-col-15,
.ant-col-16,
.ant-col-17,
.ant-col-18,
.ant-col-19,
.ant-col-20,
.ant-col-21,
.ant-col-22,
.ant-col-23,
.ant-col-24,
.ant-col-lg-1,
.ant-col-lg-2,
.ant-col-lg-3,
.ant-col-lg-4,
.ant-col-lg-5,
.ant-col-lg-6,
.ant-col-lg-7,
.ant-col-lg-8,
.ant-col-lg-9,
.ant-col-lg-10,
.ant-col-lg-11,
.ant-col-lg-12,
.ant-col-lg-13,
.ant-col-lg-14,
.ant-col-lg-15,
.ant-col-lg-16,
.ant-col-lg-17,
.ant-col-lg-18,
.ant-col-lg-19,
.ant-col-lg-20,
.ant-col-lg-21,
.ant-col-lg-22,
.ant-col-lg-23,
.ant-col-lg-24,
.ant-col-md-1,
.ant-col-md-2,
.ant-col-md-3,
.ant-col-md-4,
.ant-col-md-5,
.ant-col-md-6,
.ant-col-md-7,
.ant-col-md-8,
.ant-col-md-9,
.ant-col-md-10,
.ant-col-md-11,
.ant-col-md-12,
.ant-col-md-13,
.ant-col-md-14,
.ant-col-md-15,
.ant-col-md-16,
.ant-col-md-17,
.ant-col-md-18,
.ant-col-md-19,
.ant-col-md-20,
.ant-col-md-21,
.ant-col-md-22,
.ant-col-md-23,
.ant-col-md-24,
.ant-col-sm-1,
.ant-col-sm-2,
.ant-col-sm-3,
.ant-col-sm-4,
.ant-col-sm-5,
.ant-col-sm-6,
.ant-col-sm-7,
.ant-col-sm-8,
.ant-col-sm-9,
.ant-col-sm-10,
.ant-col-sm-11,
.ant-col-sm-12,
.ant-col-sm-13,
.ant-col-sm-14,
.ant-col-sm-15,
.ant-col-sm-16,
.ant-col-sm-17,
.ant-col-sm-18,
.ant-col-sm-19,
.ant-col-sm-20,
.ant-col-sm-21,
.ant-col-sm-22,
.ant-col-sm-23,
.ant-col-sm-24,
.ant-col-xs-1,
.ant-col-xs-2,
.ant-col-xs-3,
.ant-col-xs-4,
.ant-col-xs-5,
.ant-col-xs-6,
.ant-col-xs-7,
.ant-col-xs-8,
.ant-col-xs-9,
.ant-col-xs-10,
.ant-col-xs-11,
.ant-col-xs-12,
.ant-col-xs-13,
.ant-col-xs-14,
.ant-col-xs-15,
.ant-col-xs-16,
.ant-col-xs-17,
.ant-col-xs-18,
.ant-col-xs-19,
.ant-col-xs-20,
.ant-col-xs-21,
.ant-col-xs-22,
.ant-col-xs-23,
.ant-col-xs-24 {
  position: relative;
  padding-right: 0;
  padding-left: 0
}

.ant-col-1,
.ant-col-2,
.ant-col-3,
.ant-col-4,
.ant-col-5,
.ant-col-6,
.ant-col-7,
.ant-col-8,
.ant-col-9,
.ant-col-10,
.ant-col-11,
.ant-col-12,
.ant-col-13,
.ant-col-14,
.ant-col-15,
.ant-col-16,
.ant-col-17,
.ant-col-18,
.ant-col-19,
.ant-col-20,
.ant-col-21,
.ant-col-22,
.ant-col-23,
.ant-col-24 {
  flex: 0 0 auto;
  float: left
}

.ant-col-24 {
  display: block;
  box-sizing: border-box;
  width: 100%
}

.ant-col-push-24 {
  left: 100%
}

.ant-col-pull-24 {
  right: 100%
}

.ant-col-offset-24 {
  margin-left: 100%
}

.ant-col-order-24 {
  order: 24
}

.ant-col-23 {
  display: block;
  box-sizing: border-box;
  width: 95.83333333%
}

.ant-col-push-23 {
  left: 95.83333333%
}

.ant-col-pull-23 {
  right: 95.83333333%
}

.ant-col-offset-23 {
  margin-left: 95.83333333%
}

.ant-col-order-23 {
  order: 23
}

.ant-col-22 {
  display: block;
  box-sizing: border-box;
  width: 91.66666667%
}

.ant-col-push-22 {
  left: 91.66666667%
}

.ant-col-pull-22 {
  right: 91.66666667%
}

.ant-col-offset-22 {
  margin-left: 91.66666667%
}

.ant-col-order-22 {
  order: 22
}

.ant-col-21 {
  display: block;
  box-sizing: border-box;
  width: 87.5%
}

.ant-col-push-21 {
  left: 87.5%
}

.ant-col-pull-21 {
  right: 87.5%
}

.ant-col-offset-21 {
  margin-left: 87.5%
}

.ant-col-order-21 {
  order: 21
}

.ant-col-20 {
  display: block;
  box-sizing: border-box;
  width: 83.33333333%
}

.ant-col-push-20 {
  left: 83.33333333%
}

.ant-col-pull-20 {
  right: 83.33333333%
}

.ant-col-offset-20 {
  margin-left: 83.33333333%
}

.ant-col-order-20 {
  order: 20
}

.ant-col-19 {
  display: block;
  box-sizing: border-box;
  width: 79.16666667%
}

.ant-col-push-19 {
  left: 79.16666667%
}

.ant-col-pull-19 {
  right: 79.16666667%
}

.ant-col-offset-19 {
  margin-left: 79.16666667%
}

.ant-col-order-19 {
  order: 19
}

.ant-col-18 {
  display: block;
  box-sizing: border-box;
  width: 75%
}

.ant-col-push-18 {
  left: 75%
}

.ant-col-pull-18 {
  right: 75%
}

.ant-col-offset-18 {
  margin-left: 75%
}

.ant-col-order-18 {
  order: 18
}

.ant-col-17 {
  display: block;
  box-sizing: border-box;
  width: 70.83333333%
}

.ant-col-push-17 {
  left: 70.83333333%
}

.ant-col-pull-17 {
  right: 70.83333333%
}

.ant-col-offset-17 {
  margin-left: 70.83333333%
}

.ant-col-order-17 {
  order: 17
}

.ant-col-16 {
  display: block;
  box-sizing: border-box;
  width: 66.66666667%
}

.ant-col-push-16 {
  left: 66.66666667%
}

.ant-col-pull-16 {
  right: 66.66666667%
}

.ant-col-offset-16 {
  margin-left: 66.66666667%
}

.ant-col-order-16 {
  order: 16
}

.ant-col-15 {
  display: block;
  box-sizing: border-box;
  width: 62.5%
}

.ant-col-push-15 {
  left: 62.5%
}

.ant-col-pull-15 {
  right: 62.5%
}

.ant-col-offset-15 {
  margin-left: 62.5%
}

.ant-col-order-15 {
  order: 15
}

.ant-col-14 {
  display: block;
  box-sizing: border-box;
  width: 58.33333333%
}

.ant-col-push-14 {
  left: 58.33333333%
}

.ant-col-pull-14 {
  right: 58.33333333%
}

.ant-col-offset-14 {
  margin-left: 58.33333333%
}

.ant-col-order-14 {
  order: 14
}

.ant-col-13 {
  display: block;
  box-sizing: border-box;
  width: 54.16666667%
}

.ant-col-push-13 {
  left: 54.16666667%
}

.ant-col-pull-13 {
  right: 54.16666667%
}

.ant-col-offset-13 {
  margin-left: 54.16666667%
}

.ant-col-order-13 {
  order: 13
}

.ant-col-12 {
  display: block;
  box-sizing: border-box;
  width: 50%
}

.ant-col-push-12 {
  left: 50%
}

.ant-col-pull-12 {
  right: 50%
}

.ant-col-offset-12 {
  margin-left: 50%
}

.ant-col-order-12 {
  order: 12
}

.ant-col-11 {
  display: block;
  box-sizing: border-box;
  width: 45.83333333%
}

.ant-col-push-11 {
  left: 45.83333333%
}

.ant-col-pull-11 {
  right: 45.83333333%
}

.ant-col-offset-11 {
  margin-left: 45.83333333%
}

.ant-col-order-11 {
  order: 11
}

.ant-col-10 {
  display: block;
  box-sizing: border-box;
  width: 41.66666667%
}

.ant-col-push-10 {
  left: 41.66666667%
}

.ant-col-pull-10 {
  right: 41.66666667%
}

.ant-col-offset-10 {
  margin-left: 41.66666667%
}

.ant-col-order-10 {
  order: 10
}

.ant-col-9 {
  display: block;
  box-sizing: border-box;
  width: 37.5%
}

.ant-col-push-9 {
  left: 37.5%
}

.ant-col-pull-9 {
  right: 37.5%
}

.ant-col-offset-9 {
  margin-left: 37.5%
}

.ant-col-order-9 {
  order: 9
}

.ant-col-8 {
  display: block;
  box-sizing: border-box;
  width: 33.33333333%
}

.ant-col-push-8 {
  left: 33.33333333%
}

.ant-col-pull-8 {
  right: 33.33333333%
}

.ant-col-offset-8 {
  margin-left: 33.33333333%
}

.ant-col-order-8 {
  order: 8
}

.ant-col-7 {
  display: block;
  box-sizing: border-box;
  width: 29.16666667%
}

.ant-col-push-7 {
  left: 29.16666667%
}

.ant-col-pull-7 {
  right: 29.16666667%
}

.ant-col-offset-7 {
  margin-left: 29.16666667%
}

.ant-col-order-7 {
  order: 7
}

.ant-col-6 {
  display: block;
  box-sizing: border-box;
  width: 25%
}

.ant-col-push-6 {
  left: 25%
}

.ant-col-pull-6 {
  right: 25%
}

.ant-col-offset-6 {
  margin-left: 25%
}

.ant-col-order-6 {
  order: 6
}

.ant-col-5 {
  display: block;
  box-sizing: border-box;
  width: 20.83333333%
}

.ant-col-push-5 {
  left: 20.83333333%
}

.ant-col-pull-5 {
  right: 20.83333333%
}

.ant-col-offset-5 {
  margin-left: 20.83333333%
}

.ant-col-order-5 {
  order: 5
}

.ant-col-4 {
  display: block;
  box-sizing: border-box;
  width: 16.66666667%
}

.ant-col-push-4 {
  left: 16.66666667%
}

.ant-col-pull-4 {
  right: 16.66666667%
}

.ant-col-offset-4 {
  margin-left: 16.66666667%
}

.ant-col-order-4 {
  order: 4
}

.ant-col-3 {
  display: block;
  box-sizing: border-box;
  width: 12.5%
}

.ant-col-push-3 {
  left: 12.5%
}

.ant-col-pull-3 {
  right: 12.5%
}

.ant-col-offset-3 {
  margin-left: 12.5%
}

.ant-col-order-3 {
  order: 3
}

.ant-col-2 {
  display: block;
  box-sizing: border-box;
  width: 8.33333333%
}

.ant-col-push-2 {
  left: 8.33333333%
}

.ant-col-pull-2 {
  right: 8.33333333%
}

.ant-col-offset-2 {
  margin-left: 8.33333333%
}

.ant-col-order-2 {
  order: 2
}

.ant-col-1 {
  display: block;
  box-sizing: border-box;
  width: 4.16666667%
}

.ant-col-push-1 {
  left: 4.16666667%
}

.ant-col-pull-1 {
  right: 4.16666667%
}

.ant-col-offset-1 {
  margin-left: 4.16666667%
}

.ant-col-order-1 {
  order: 1
}

.ant-col-0 {
  display: none
}

.ant-col-offset-0 {
  margin-left: 0
}

.ant-col-order-0 {
  order: 0
}

.ant-col-xs-1,
.ant-col-xs-2,
.ant-col-xs-3,
.ant-col-xs-4,
.ant-col-xs-5,
.ant-col-xs-6,
.ant-col-xs-7,
.ant-col-xs-8,
.ant-col-xs-9,
.ant-col-xs-10,
.ant-col-xs-11,
.ant-col-xs-12,
.ant-col-xs-13,
.ant-col-xs-14,
.ant-col-xs-15,
.ant-col-xs-16,
.ant-col-xs-17,
.ant-col-xs-18,
.ant-col-xs-19,
.ant-col-xs-20,
.ant-col-xs-21,
.ant-col-xs-22,
.ant-col-xs-23,
.ant-col-xs-24 {
  flex: 0 0 auto;
  float: left
}

.ant-col-xs-24 {
  display: block;
  box-sizing: border-box;
  width: 100%
}

.ant-col-xs-push-24 {
  left: 100%
}

.ant-col-xs-pull-24 {
  right: 100%
}

.ant-col-xs-offset-24 {
  margin-left: 100%
}

.ant-col-xs-order-24 {
  order: 24
}

.ant-col-xs-23 {
  display: block;
  box-sizing: border-box;
  width: 95.83333333%
}

.ant-col-xs-push-23 {
  left: 95.83333333%
}

.ant-col-xs-pull-23 {
  right: 95.83333333%
}

.ant-col-xs-offset-23 {
  margin-left: 95.83333333%
}

.ant-col-xs-order-23 {
  order: 23
}

.ant-col-xs-22 {
  display: block;
  box-sizing: border-box;
  width: 91.66666667%
}

.ant-col-xs-push-22 {
  left: 91.66666667%
}

.ant-col-xs-pull-22 {
  right: 91.66666667%
}

.ant-col-xs-offset-22 {
  margin-left: 91.66666667%
}

.ant-col-xs-order-22 {
  order: 22
}

.ant-col-xs-21 {
  display: block;
  box-sizing: border-box;
  width: 87.5%
}

.ant-col-xs-push-21 {
  left: 87.5%
}

.ant-col-xs-pull-21 {
  right: 87.5%
}

.ant-col-xs-offset-21 {
  margin-left: 87.5%
}

.ant-col-xs-order-21 {
  order: 21
}

.ant-col-xs-20 {
  display: block;
  box-sizing: border-box;
  width: 83.33333333%
}

.ant-col-xs-push-20 {
  left: 83.33333333%
}

.ant-col-xs-pull-20 {
  right: 83.33333333%
}

.ant-col-xs-offset-20 {
  margin-left: 83.33333333%
}

.ant-col-xs-order-20 {
  order: 20
}

.ant-col-xs-19 {
  display: block;
  box-sizing: border-box;
  width: 79.16666667%
}

.ant-col-xs-push-19 {
  left: 79.16666667%
}

.ant-col-xs-pull-19 {
  right: 79.16666667%
}

.ant-col-xs-offset-19 {
  margin-left: 79.16666667%
}

.ant-col-xs-order-19 {
  order: 19
}

.ant-col-xs-18 {
  display: block;
  box-sizing: border-box;
  width: 75%
}

.ant-col-xs-push-18 {
  left: 75%
}

.ant-col-xs-pull-18 {
  right: 75%
}

.ant-col-xs-offset-18 {
  margin-left: 75%
}

.ant-col-xs-order-18 {
  order: 18
}

.ant-col-xs-17 {
  display: block;
  box-sizing: border-box;
  width: 70.83333333%
}

.ant-col-xs-push-17 {
  left: 70.83333333%
}

.ant-col-xs-pull-17 {
  right: 70.83333333%
}

.ant-col-xs-offset-17 {
  margin-left: 70.83333333%
}

.ant-col-xs-order-17 {
  order: 17
}

.ant-col-xs-16 {
  display: block;
  box-sizing: border-box;
  width: 66.66666667%
}

.ant-col-xs-push-16 {
  left: 66.66666667%
}

.ant-col-xs-pull-16 {
  right: 66.66666667%
}

.ant-col-xs-offset-16 {
  margin-left: 66.66666667%
}

.ant-col-xs-order-16 {
  order: 16
}

.ant-col-xs-15 {
  display: block;
  box-sizing: border-box;
  width: 62.5%
}

.ant-col-xs-push-15 {
  left: 62.5%
}

.ant-col-xs-pull-15 {
  right: 62.5%
}

.ant-col-xs-offset-15 {
  margin-left: 62.5%
}

.ant-col-xs-order-15 {
  order: 15
}

.ant-col-xs-14 {
  display: block;
  box-sizing: border-box;
  width: 58.33333333%
}

.ant-col-xs-push-14 {
  left: 58.33333333%
}

.ant-col-xs-pull-14 {
  right: 58.33333333%
}

.ant-col-xs-offset-14 {
  margin-left: 58.33333333%
}

.ant-col-xs-order-14 {
  order: 14
}

.ant-col-xs-13 {
  display: block;
  box-sizing: border-box;
  width: 54.16666667%
}

.ant-col-xs-push-13 {
  left: 54.16666667%
}

.ant-col-xs-pull-13 {
  right: 54.16666667%
}

.ant-col-xs-offset-13 {
  margin-left: 54.16666667%
}

.ant-col-xs-order-13 {
  order: 13
}

.ant-col-xs-12 {
  display: block;
  box-sizing: border-box;
  width: 50%
}

.ant-col-xs-push-12 {
  left: 50%
}

.ant-col-xs-pull-12 {
  right: 50%
}

.ant-col-xs-offset-12 {
  margin-left: 50%
}

.ant-col-xs-order-12 {
  order: 12
}

.ant-col-xs-11 {
  display: block;
  box-sizing: border-box;
  width: 45.83333333%
}

.ant-col-xs-push-11 {
  left: 45.83333333%
}

.ant-col-xs-pull-11 {
  right: 45.83333333%
}

.ant-col-xs-offset-11 {
  margin-left: 45.83333333%
}

.ant-col-xs-order-11 {
  order: 11
}

.ant-col-xs-10 {
  display: block;
  box-sizing: border-box;
  width: 41.66666667%
}

.ant-col-xs-push-10 {
  left: 41.66666667%
}

.ant-col-xs-pull-10 {
  right: 41.66666667%
}

.ant-col-xs-offset-10 {
  margin-left: 41.66666667%
}

.ant-col-xs-order-10 {
  order: 10
}

.ant-col-xs-9 {
  display: block;
  box-sizing: border-box;
  width: 37.5%
}

.ant-col-xs-push-9 {
  left: 37.5%
}

.ant-col-xs-pull-9 {
  right: 37.5%
}

.ant-col-xs-offset-9 {
  margin-left: 37.5%
}

.ant-col-xs-order-9 {
  order: 9
}

.ant-col-xs-8 {
  display: block;
  box-sizing: border-box;
  width: 33.33333333%
}

.ant-col-xs-push-8 {
  left: 33.33333333%
}

.ant-col-xs-pull-8 {
  right: 33.33333333%
}

.ant-col-xs-offset-8 {
  margin-left: 33.33333333%
}

.ant-col-xs-order-8 {
  order: 8
}

.ant-col-xs-7 {
  display: block;
  box-sizing: border-box;
  width: 29.16666667%
}

.ant-col-xs-push-7 {
  left: 29.16666667%
}

.ant-col-xs-pull-7 {
  right: 29.16666667%
}

.ant-col-xs-offset-7 {
  margin-left: 29.16666667%
}

.ant-col-xs-order-7 {
  order: 7
}

.ant-col-xs-6 {
  display: block;
  box-sizing: border-box;
  width: 25%
}

.ant-col-xs-push-6 {
  left: 25%
}

.ant-col-xs-pull-6 {
  right: 25%
}

.ant-col-xs-offset-6 {
  margin-left: 25%
}

.ant-col-xs-order-6 {
  order: 6
}

.ant-col-xs-5 {
  display: block;
  box-sizing: border-box;
  width: 20.83333333%
}

.ant-col-xs-push-5 {
  left: 20.83333333%
}

.ant-col-xs-pull-5 {
  right: 20.83333333%
}

.ant-col-xs-offset-5 {
  margin-left: 20.83333333%
}

.ant-col-xs-order-5 {
  order: 5
}

.ant-col-xs-4 {
  display: block;
  box-sizing: border-box;
  width: 16.66666667%
}

.ant-col-xs-push-4 {
  left: 16.66666667%
}

.ant-col-xs-pull-4 {
  right: 16.66666667%
}

.ant-col-xs-offset-4 {
  margin-left: 16.66666667%
}

.ant-col-xs-order-4 {
  order: 4
}

.ant-col-xs-3 {
  display: block;
  box-sizing: border-box;
  width: 12.5%
}

.ant-col-xs-push-3 {
  left: 12.5%
}

.ant-col-xs-pull-3 {
  right: 12.5%
}

.ant-col-xs-offset-3 {
  margin-left: 12.5%
}

.ant-col-xs-order-3 {
  order: 3
}

.ant-col-xs-2 {
  display: block;
  box-sizing: border-box;
  width: 8.33333333%
}

.ant-col-xs-push-2 {
  left: 8.33333333%
}

.ant-col-xs-pull-2 {
  right: 8.33333333%
}

.ant-col-xs-offset-2 {
  margin-left: 8.33333333%
}

.ant-col-xs-order-2 {
  order: 2
}

.ant-col-xs-1 {
  display: block;
  box-sizing: border-box;
  width: 4.16666667%
}

.ant-col-xs-push-1 {
  left: 4.16666667%
}

.ant-col-xs-pull-1 {
  right: 4.16666667%
}

.ant-col-xs-offset-1 {
  margin-left: 4.16666667%
}

.ant-col-xs-order-1 {
  order: 1
}

.ant-col-xs-0 {
  display: none
}

.ant-col-push-0 {
  left: auto
}

.ant-col-pull-0 {
  right: auto
}

.ant-col-xs-push-0 {
  left: auto
}

.ant-col-xs-pull-0 {
  right: auto
}

.ant-col-xs-offset-0 {
  margin-left: 0
}

.ant-col-xs-order-0 {
  order: 0
}

@media (min-width:576px) {

  .ant-col-sm-1,
  .ant-col-sm-2,
  .ant-col-sm-3,
  .ant-col-sm-4,
  .ant-col-sm-5,
  .ant-col-sm-6,
  .ant-col-sm-7,
  .ant-col-sm-8,
  .ant-col-sm-9,
  .ant-col-sm-10,
  .ant-col-sm-11,
  .ant-col-sm-12,
  .ant-col-sm-13,
  .ant-col-sm-14,
  .ant-col-sm-15,
  .ant-col-sm-16,
  .ant-col-sm-17,
  .ant-col-sm-18,
  .ant-col-sm-19,
  .ant-col-sm-20,
  .ant-col-sm-21,
  .ant-col-sm-22,
  .ant-col-sm-23,
  .ant-col-sm-24 {
    flex: 0 0 auto;
    float: left
  }

  .ant-col-sm-24 {
    display: block;
    box-sizing: border-box;
    width: 100%
  }

  .ant-col-sm-push-24 {
    left: 100%
  }

  .ant-col-sm-pull-24 {
    right: 100%
  }

  .ant-col-sm-offset-24 {
    margin-left: 100%
  }

  .ant-col-sm-order-24 {
    order: 24
  }

  .ant-col-sm-23 {
    display: block;
    box-sizing: border-box;
    width: 95.83333333%
  }

  .ant-col-sm-push-23 {
    left: 95.83333333%
  }

  .ant-col-sm-pull-23 {
    right: 95.83333333%
  }

  .ant-col-sm-offset-23 {
    margin-left: 95.83333333%
  }

  .ant-col-sm-order-23 {
    order: 23
  }

  .ant-col-sm-22 {
    display: block;
    box-sizing: border-box;
    width: 91.66666667%
  }

  .ant-col-sm-push-22 {
    left: 91.66666667%
  }

  .ant-col-sm-pull-22 {
    right: 91.66666667%
  }

  .ant-col-sm-offset-22 {
    margin-left: 91.66666667%
  }

  .ant-col-sm-order-22 {
    order: 22
  }

  .ant-col-sm-21 {
    display: block;
    box-sizing: border-box;
    width: 87.5%
  }

  .ant-col-sm-push-21 {
    left: 87.5%
  }

  .ant-col-sm-pull-21 {
    right: 87.5%
  }

  .ant-col-sm-offset-21 {
    margin-left: 87.5%
  }

  .ant-col-sm-order-21 {
    order: 21
  }

  .ant-col-sm-20 {
    display: block;
    box-sizing: border-box;
    width: 83.33333333%
  }

  .ant-col-sm-push-20 {
    left: 83.33333333%
  }

  .ant-col-sm-pull-20 {
    right: 83.33333333%
  }

  .ant-col-sm-offset-20 {
    margin-left: 83.33333333%
  }

  .ant-col-sm-order-20 {
    order: 20
  }

  .ant-col-sm-19 {
    display: block;
    box-sizing: border-box;
    width: 79.16666667%
  }

  .ant-col-sm-push-19 {
    left: 79.16666667%
  }

  .ant-col-sm-pull-19 {
    right: 79.16666667%
  }

  .ant-col-sm-offset-19 {
    margin-left: 79.16666667%
  }

  .ant-col-sm-order-19 {
    order: 19
  }

  .ant-col-sm-18 {
    display: block;
    box-sizing: border-box;
    width: 75%
  }

  .ant-col-sm-push-18 {
    left: 75%
  }

  .ant-col-sm-pull-18 {
    right: 75%
  }

  .ant-col-sm-offset-18 {
    margin-left: 75%
  }

  .ant-col-sm-order-18 {
    order: 18
  }

  .ant-col-sm-17 {
    display: block;
    box-sizing: border-box;
    width: 70.83333333%
  }

  .ant-col-sm-push-17 {
    left: 70.83333333%
  }

  .ant-col-sm-pull-17 {
    right: 70.83333333%
  }

  .ant-col-sm-offset-17 {
    margin-left: 70.83333333%
  }

  .ant-col-sm-order-17 {
    order: 17
  }

  .ant-col-sm-16 {
    display: block;
    box-sizing: border-box;
    width: 66.66666667%
  }

  .ant-col-sm-push-16 {
    left: 66.66666667%
  }

  .ant-col-sm-pull-16 {
    right: 66.66666667%
  }

  .ant-col-sm-offset-16 {
    margin-left: 66.66666667%
  }

  .ant-col-sm-order-16 {
    order: 16
  }

  .ant-col-sm-15 {
    display: block;
    box-sizing: border-box;
    width: 62.5%
  }

  .ant-col-sm-push-15 {
    left: 62.5%
  }

  .ant-col-sm-pull-15 {
    right: 62.5%
  }

  .ant-col-sm-offset-15 {
    margin-left: 62.5%
  }

  .ant-col-sm-order-15 {
    order: 15
  }

  .ant-col-sm-14 {
    display: block;
    box-sizing: border-box;
    width: 58.33333333%
  }

  .ant-col-sm-push-14 {
    left: 58.33333333%
  }

  .ant-col-sm-pull-14 {
    right: 58.33333333%
  }

  .ant-col-sm-offset-14 {
    margin-left: 58.33333333%
  }

  .ant-col-sm-order-14 {
    order: 14
  }

  .ant-col-sm-13 {
    display: block;
    box-sizing: border-box;
    width: 54.16666667%
  }

  .ant-col-sm-push-13 {
    left: 54.16666667%
  }

  .ant-col-sm-pull-13 {
    right: 54.16666667%
  }

  .ant-col-sm-offset-13 {
    margin-left: 54.16666667%
  }

  .ant-col-sm-order-13 {
    order: 13
  }

  .ant-col-sm-12 {
    display: block;
    box-sizing: border-box;
    width: 50%
  }

  .ant-col-sm-push-12 {
    left: 50%
  }

  .ant-col-sm-pull-12 {
    right: 50%
  }

  .ant-col-sm-offset-12 {
    margin-left: 50%
  }

  .ant-col-sm-order-12 {
    order: 12
  }

  .ant-col-sm-11 {
    display: block;
    box-sizing: border-box;
    width: 45.83333333%
  }

  .ant-col-sm-push-11 {
    left: 45.83333333%
  }

  .ant-col-sm-pull-11 {
    right: 45.83333333%
  }

  .ant-col-sm-offset-11 {
    margin-left: 45.83333333%
  }

  .ant-col-sm-order-11 {
    order: 11
  }

  .ant-col-sm-10 {
    display: block;
    box-sizing: border-box;
    width: 41.66666667%
  }

  .ant-col-sm-push-10 {
    left: 41.66666667%
  }

  .ant-col-sm-pull-10 {
    right: 41.66666667%
  }

  .ant-col-sm-offset-10 {
    margin-left: 41.66666667%
  }

  .ant-col-sm-order-10 {
    order: 10
  }

  .ant-col-sm-9 {
    display: block;
    box-sizing: border-box;
    width: 37.5%
  }

  .ant-col-sm-push-9 {
    left: 37.5%
  }

  .ant-col-sm-pull-9 {
    right: 37.5%
  }

  .ant-col-sm-offset-9 {
    margin-left: 37.5%
  }

  .ant-col-sm-order-9 {
    order: 9
  }

  .ant-col-sm-8 {
    display: block;
    box-sizing: border-box;
    width: 33.33333333%
  }

  .ant-col-sm-push-8 {
    left: 33.33333333%
  }

  .ant-col-sm-pull-8 {
    right: 33.33333333%
  }

  .ant-col-sm-offset-8 {
    margin-left: 33.33333333%
  }

  .ant-col-sm-order-8 {
    order: 8
  }

  .ant-col-sm-7 {
    display: block;
    box-sizing: border-box;
    width: 29.16666667%
  }

  .ant-col-sm-push-7 {
    left: 29.16666667%
  }

  .ant-col-sm-pull-7 {
    right: 29.16666667%
  }

  .ant-col-sm-offset-7 {
    margin-left: 29.16666667%
  }

  .ant-col-sm-order-7 {
    order: 7
  }

  .ant-col-sm-6 {
    display: block;
    box-sizing: border-box;
    width: 25%
  }

  .ant-col-sm-push-6 {
    left: 25%
  }

  .ant-col-sm-pull-6 {
    right: 25%
  }

  .ant-col-sm-offset-6 {
    margin-left: 25%
  }

  .ant-col-sm-order-6 {
    order: 6
  }

  .ant-col-sm-5 {
    display: block;
    box-sizing: border-box;
    width: 20.83333333%
  }

  .ant-col-sm-push-5 {
    left: 20.83333333%
  }

  .ant-col-sm-pull-5 {
    right: 20.83333333%
  }

  .ant-col-sm-offset-5 {
    margin-left: 20.83333333%
  }

  .ant-col-sm-order-5 {
    order: 5
  }

  .ant-col-sm-4 {
    display: block;
    box-sizing: border-box;
    width: 16.66666667%
  }

  .ant-col-sm-push-4 {
    left: 16.66666667%
  }

  .ant-col-sm-pull-4 {
    right: 16.66666667%
  }

  .ant-col-sm-offset-4 {
    margin-left: 16.66666667%
  }

  .ant-col-sm-order-4 {
    order: 4
  }

  .ant-col-sm-3 {
    display: block;
    box-sizing: border-box;
    width: 12.5%
  }

  .ant-col-sm-push-3 {
    left: 12.5%
  }

  .ant-col-sm-pull-3 {
    right: 12.5%
  }

  .ant-col-sm-offset-3 {
    margin-left: 12.5%
  }

  .ant-col-sm-order-3 {
    order: 3
  }

  .ant-col-sm-2 {
    display: block;
    box-sizing: border-box;
    width: 8.33333333%
  }

  .ant-col-sm-push-2 {
    left: 8.33333333%
  }

  .ant-col-sm-pull-2 {
    right: 8.33333333%
  }

  .ant-col-sm-offset-2 {
    margin-left: 8.33333333%
  }

  .ant-col-sm-order-2 {
    order: 2
  }

  .ant-col-sm-1 {
    display: block;
    box-sizing: border-box;
    width: 4.16666667%
  }

  .ant-col-sm-push-1 {
    left: 4.16666667%
  }

  .ant-col-sm-pull-1 {
    right: 4.16666667%
  }

  .ant-col-sm-offset-1 {
    margin-left: 4.16666667%
  }

  .ant-col-sm-order-1 {
    order: 1
  }

  .ant-col-sm-0 {
    display: none
  }

  .ant-col-push-0 {
    left: auto
  }

  .ant-col-pull-0 {
    right: auto
  }

  .ant-col-sm-push-0 {
    left: auto
  }

  .ant-col-sm-pull-0 {
    right: auto
  }

  .ant-col-sm-offset-0 {
    margin-left: 0
  }

  .ant-col-sm-order-0 {
    order: 0
  }
}

@media (min-width:768px) {

  .ant-col-md-1,
  .ant-col-md-2,
  .ant-col-md-3,
  .ant-col-md-4,
  .ant-col-md-5,
  .ant-col-md-6,
  .ant-col-md-7,
  .ant-col-md-8,
  .ant-col-md-9,
  .ant-col-md-10,
  .ant-col-md-11,
  .ant-col-md-12,
  .ant-col-md-13,
  .ant-col-md-14,
  .ant-col-md-15,
  .ant-col-md-16,
  .ant-col-md-17,
  .ant-col-md-18,
  .ant-col-md-19,
  .ant-col-md-20,
  .ant-col-md-21,
  .ant-col-md-22,
  .ant-col-md-23,
  .ant-col-md-24 {
    flex: 0 0 auto;
    float: left
  }

  .ant-col-md-24 {
    display: block;
    box-sizing: border-box;
    width: 100%
  }

  .ant-col-md-push-24 {
    left: 100%
  }

  .ant-col-md-pull-24 {
    right: 100%
  }

  .ant-col-md-offset-24 {
    margin-left: 100%
  }

  .ant-col-md-order-24 {
    order: 24
  }

  .ant-col-md-23 {
    display: block;
    box-sizing: border-box;
    width: 95.83333333%
  }

  .ant-col-md-push-23 {
    left: 95.83333333%
  }

  .ant-col-md-pull-23 {
    right: 95.83333333%
  }

  .ant-col-md-offset-23 {
    margin-left: 95.83333333%
  }

  .ant-col-md-order-23 {
    order: 23
  }

  .ant-col-md-22 {
    display: block;
    box-sizing: border-box;
    width: 91.66666667%
  }

  .ant-col-md-push-22 {
    left: 91.66666667%
  }

  .ant-col-md-pull-22 {
    right: 91.66666667%
  }

  .ant-col-md-offset-22 {
    margin-left: 91.66666667%
  }

  .ant-col-md-order-22 {
    order: 22
  }

  .ant-col-md-21 {
    display: block;
    box-sizing: border-box;
    width: 87.5%
  }

  .ant-col-md-push-21 {
    left: 87.5%
  }

  .ant-col-md-pull-21 {
    right: 87.5%
  }

  .ant-col-md-offset-21 {
    margin-left: 87.5%
  }

  .ant-col-md-order-21 {
    order: 21
  }

  .ant-col-md-20 {
    display: block;
    box-sizing: border-box;
    width: 83.33333333%
  }

  .ant-col-md-push-20 {
    left: 83.33333333%
  }

  .ant-col-md-pull-20 {
    right: 83.33333333%
  }

  .ant-col-md-offset-20 {
    margin-left: 83.33333333%
  }

  .ant-col-md-order-20 {
    order: 20
  }

  .ant-col-md-19 {
    display: block;
    box-sizing: border-box;
    width: 79.16666667%
  }

  .ant-col-md-push-19 {
    left: 79.16666667%
  }

  .ant-col-md-pull-19 {
    right: 79.16666667%
  }

  .ant-col-md-offset-19 {
    margin-left: 79.16666667%
  }

  .ant-col-md-order-19 {
    order: 19
  }

  .ant-col-md-18 {
    display: block;
    box-sizing: border-box;
    width: 75%
  }

  .ant-col-md-push-18 {
    left: 75%
  }

  .ant-col-md-pull-18 {
    right: 75%
  }

  .ant-col-md-offset-18 {
    margin-left: 75%
  }

  .ant-col-md-order-18 {
    order: 18
  }

  .ant-col-md-17 {
    display: block;
    box-sizing: border-box;
    width: 70.83333333%
  }

  .ant-col-md-push-17 {
    left: 70.83333333%
  }

  .ant-col-md-pull-17 {
    right: 70.83333333%
  }

  .ant-col-md-offset-17 {
    margin-left: 70.83333333%
  }

  .ant-col-md-order-17 {
    order: 17
  }

  .ant-col-md-16 {
    display: block;
    box-sizing: border-box;
    width: 66.66666667%
  }

  .ant-col-md-push-16 {
    left: 66.66666667%
  }

  .ant-col-md-pull-16 {
    right: 66.66666667%
  }

  .ant-col-md-offset-16 {
    margin-left: 66.66666667%
  }

  .ant-col-md-order-16 {
    order: 16
  }

  .ant-col-md-15 {
    display: block;
    box-sizing: border-box;
    width: 62.5%
  }

  .ant-col-md-push-15 {
    left: 62.5%
  }

  .ant-col-md-pull-15 {
    right: 62.5%
  }

  .ant-col-md-offset-15 {
    margin-left: 62.5%
  }

  .ant-col-md-order-15 {
    order: 15
  }

  .ant-col-md-14 {
    display: block;
    box-sizing: border-box;
    width: 58.33333333%
  }

  .ant-col-md-push-14 {
    left: 58.33333333%
  }

  .ant-col-md-pull-14 {
    right: 58.33333333%
  }

  .ant-col-md-offset-14 {
    margin-left: 58.33333333%
  }

  .ant-col-md-order-14 {
    order: 14
  }

  .ant-col-md-13 {
    display: block;
    box-sizing: border-box;
    width: 54.16666667%
  }

  .ant-col-md-push-13 {
    left: 54.16666667%
  }

  .ant-col-md-pull-13 {
    right: 54.16666667%
  }

  .ant-col-md-offset-13 {
    margin-left: 54.16666667%
  }

  .ant-col-md-order-13 {
    order: 13
  }

  .ant-col-md-12 {
    display: block;
    box-sizing: border-box;
    width: 50%
  }

  .ant-col-md-push-12 {
    left: 50%
  }

  .ant-col-md-pull-12 {
    right: 50%
  }

  .ant-col-md-offset-12 {
    margin-left: 50%
  }

  .ant-col-md-order-12 {
    order: 12
  }

  .ant-col-md-11 {
    display: block;
    box-sizing: border-box;
    width: 45.83333333%
  }

  .ant-col-md-push-11 {
    left: 45.83333333%
  }

  .ant-col-md-pull-11 {
    right: 45.83333333%
  }

  .ant-col-md-offset-11 {
    margin-left: 45.83333333%
  }

  .ant-col-md-order-11 {
    order: 11
  }

  .ant-col-md-10 {
    display: block;
    box-sizing: border-box;
    width: 41.66666667%
  }

  .ant-col-md-push-10 {
    left: 41.66666667%
  }

  .ant-col-md-pull-10 {
    right: 41.66666667%
  }

  .ant-col-md-offset-10 {
    margin-left: 41.66666667%
  }

  .ant-col-md-order-10 {
    order: 10
  }

  .ant-col-md-9 {
    display: block;
    box-sizing: border-box;
    width: 37.5%
  }

  .ant-col-md-push-9 {
    left: 37.5%
  }

  .ant-col-md-pull-9 {
    right: 37.5%
  }

  .ant-col-md-offset-9 {
    margin-left: 37.5%
  }

  .ant-col-md-order-9 {
    order: 9
  }

  .ant-col-md-8 {
    display: block;
    box-sizing: border-box;
    width: 33.33333333%
  }

  .ant-col-md-push-8 {
    left: 33.33333333%
  }

  .ant-col-md-pull-8 {
    right: 33.33333333%
  }

  .ant-col-md-offset-8 {
    margin-left: 33.33333333%
  }

  .ant-col-md-order-8 {
    order: 8
  }

  .ant-col-md-7 {
    display: block;
    box-sizing: border-box;
    width: 29.16666667%
  }

  .ant-col-md-push-7 {
    left: 29.16666667%
  }

  .ant-col-md-pull-7 {
    right: 29.16666667%
  }

  .ant-col-md-offset-7 {
    margin-left: 29.16666667%
  }

  .ant-col-md-order-7 {
    order: 7
  }

  .ant-col-md-6 {
    display: block;
    box-sizing: border-box;
    width: 25%
  }

  .ant-col-md-push-6 {
    left: 25%
  }

  .ant-col-md-pull-6 {
    right: 25%
  }

  .ant-col-md-offset-6 {
    margin-left: 25%
  }

  .ant-col-md-order-6 {
    order: 6
  }

  .ant-col-md-5 {
    display: block;
    box-sizing: border-box;
    width: 20.83333333%
  }

  .ant-col-md-push-5 {
    left: 20.83333333%
  }

  .ant-col-md-pull-5 {
    right: 20.83333333%
  }

  .ant-col-md-offset-5 {
    margin-left: 20.83333333%
  }

  .ant-col-md-order-5 {
    order: 5
  }

  .ant-col-md-4 {
    display: block;
    box-sizing: border-box;
    width: 16.66666667%
  }

  .ant-col-md-push-4 {
    left: 16.66666667%
  }

  .ant-col-md-pull-4 {
    right: 16.66666667%
  }

  .ant-col-md-offset-4 {
    margin-left: 16.66666667%
  }

  .ant-col-md-order-4 {
    order: 4
  }

  .ant-col-md-3 {
    display: block;
    box-sizing: border-box;
    width: 12.5%
  }

  .ant-col-md-push-3 {
    left: 12.5%
  }

  .ant-col-md-pull-3 {
    right: 12.5%
  }

  .ant-col-md-offset-3 {
    margin-left: 12.5%
  }

  .ant-col-md-order-3 {
    order: 3
  }

  .ant-col-md-2 {
    display: block;
    box-sizing: border-box;
    width: 8.33333333%
  }

  .ant-col-md-push-2 {
    left: 8.33333333%
  }

  .ant-col-md-pull-2 {
    right: 8.33333333%
  }

  .ant-col-md-offset-2 {
    margin-left: 8.33333333%
  }

  .ant-col-md-order-2 {
    order: 2
  }

  .ant-col-md-1 {
    display: block;
    box-sizing: border-box;
    width: 4.16666667%
  }

  .ant-col-md-push-1 {
    left: 4.16666667%
  }

  .ant-col-md-pull-1 {
    right: 4.16666667%
  }

  .ant-col-md-offset-1 {
    margin-left: 4.16666667%
  }

  .ant-col-md-order-1 {
    order: 1
  }

  .ant-col-md-0 {
    display: none
  }

  .ant-col-push-0 {
    left: auto
  }

  .ant-col-pull-0 {
    right: auto
  }

  .ant-col-md-push-0 {
    left: auto
  }

  .ant-col-md-pull-0 {
    right: auto
  }

  .ant-col-md-offset-0 {
    margin-left: 0
  }

  .ant-col-md-order-0 {
    order: 0
  }
}

@media (min-width:992px) {

  .ant-col-lg-1,
  .ant-col-lg-2,
  .ant-col-lg-3,
  .ant-col-lg-4,
  .ant-col-lg-5,
  .ant-col-lg-6,
  .ant-col-lg-7,
  .ant-col-lg-8,
  .ant-col-lg-9,
  .ant-col-lg-10,
  .ant-col-lg-11,
  .ant-col-lg-12,
  .ant-col-lg-13,
  .ant-col-lg-14,
  .ant-col-lg-15,
  .ant-col-lg-16,
  .ant-col-lg-17,
  .ant-col-lg-18,
  .ant-col-lg-19,
  .ant-col-lg-20,
  .ant-col-lg-21,
  .ant-col-lg-22,
  .ant-col-lg-23,
  .ant-col-lg-24 {
    flex: 0 0 auto;
    float: left
  }

  .ant-col-lg-24 {
    display: block;
    box-sizing: border-box;
    width: 100%
  }

  .ant-col-lg-push-24 {
    left: 100%
  }

  .ant-col-lg-pull-24 {
    right: 100%
  }

  .ant-col-lg-offset-24 {
    margin-left: 100%
  }

  .ant-col-lg-order-24 {
    order: 24
  }

  .ant-col-lg-23 {
    display: block;
    box-sizing: border-box;
    width: 95.83333333%
  }

  .ant-col-lg-push-23 {
    left: 95.83333333%
  }

  .ant-col-lg-pull-23 {
    right: 95.83333333%
  }

  .ant-col-lg-offset-23 {
    margin-left: 95.83333333%
  }

  .ant-col-lg-order-23 {
    order: 23
  }

  .ant-col-lg-22 {
    display: block;
    box-sizing: border-box;
    width: 91.66666667%
  }

  .ant-col-lg-push-22 {
    left: 91.66666667%
  }

  .ant-col-lg-pull-22 {
    right: 91.66666667%
  }

  .ant-col-lg-offset-22 {
    margin-left: 91.66666667%
  }

  .ant-col-lg-order-22 {
    order: 22
  }

  .ant-col-lg-21 {
    display: block;
    box-sizing: border-box;
    width: 87.5%
  }

  .ant-col-lg-push-21 {
    left: 87.5%
  }

  .ant-col-lg-pull-21 {
    right: 87.5%
  }

  .ant-col-lg-offset-21 {
    margin-left: 87.5%
  }

  .ant-col-lg-order-21 {
    order: 21
  }

  .ant-col-lg-20 {
    display: block;
    box-sizing: border-box;
    width: 83.33333333%
  }

  .ant-col-lg-push-20 {
    left: 83.33333333%
  }

  .ant-col-lg-pull-20 {
    right: 83.33333333%
  }

  .ant-col-lg-offset-20 {
    margin-left: 83.33333333%
  }

  .ant-col-lg-order-20 {
    order: 20
  }

  .ant-col-lg-19 {
    display: block;
    box-sizing: border-box;
    width: 79.16666667%
  }

  .ant-col-lg-push-19 {
    left: 79.16666667%
  }

  .ant-col-lg-pull-19 {
    right: 79.16666667%
  }

  .ant-col-lg-offset-19 {
    margin-left: 79.16666667%
  }

  .ant-col-lg-order-19 {
    order: 19
  }

  .ant-col-lg-18 {
    display: block;
    box-sizing: border-box;
    width: 75%
  }

  .ant-col-lg-push-18 {
    left: 75%
  }

  .ant-col-lg-pull-18 {
    right: 75%
  }

  .ant-col-lg-offset-18 {
    margin-left: 75%
  }

  .ant-col-lg-order-18 {
    order: 18
  }

  .ant-col-lg-17 {
    display: block;
    box-sizing: border-box;
    width: 70.83333333%
  }

  .ant-col-lg-push-17 {
    left: 70.83333333%
  }

  .ant-col-lg-pull-17 {
    right: 70.83333333%
  }

  .ant-col-lg-offset-17 {
    margin-left: 70.83333333%
  }

  .ant-col-lg-order-17 {
    order: 17
  }

  .ant-col-lg-16 {
    display: block;
    box-sizing: border-box;
    width: 66.66666667%
  }

  .ant-col-lg-push-16 {
    left: 66.66666667%
  }

  .ant-col-lg-pull-16 {
    right: 66.66666667%
  }

  .ant-col-lg-offset-16 {
    margin-left: 66.66666667%
  }

  .ant-col-lg-order-16 {
    order: 16
  }

  .ant-col-lg-15 {
    display: block;
    box-sizing: border-box;
    width: 62.5%
  }

  .ant-col-lg-push-15 {
    left: 62.5%
  }

  .ant-col-lg-pull-15 {
    right: 62.5%
  }

  .ant-col-lg-offset-15 {
    margin-left: 62.5%
  }

  .ant-col-lg-order-15 {
    order: 15
  }

  .ant-col-lg-14 {
    display: block;
    box-sizing: border-box;
    width: 58.33333333%
  }

  .ant-col-lg-push-14 {
    left: 58.33333333%
  }

  .ant-col-lg-pull-14 {
    right: 58.33333333%
  }

  .ant-col-lg-offset-14 {
    margin-left: 58.33333333%
  }

  .ant-col-lg-order-14 {
    order: 14
  }

  .ant-col-lg-13 {
    display: block;
    box-sizing: border-box;
    width: 54.16666667%
  }

  .ant-col-lg-push-13 {
    left: 54.16666667%
  }

  .ant-col-lg-pull-13 {
    right: 54.16666667%
  }

  .ant-col-lg-offset-13 {
    margin-left: 54.16666667%
  }

  .ant-col-lg-order-13 {
    order: 13
  }

  .ant-col-lg-12 {
    display: block;
    box-sizing: border-box;
    width: 50%
  }

  .ant-col-lg-push-12 {
    left: 50%
  }

  .ant-col-lg-pull-12 {
    right: 50%
  }

  .ant-col-lg-offset-12 {
    margin-left: 50%
  }

  .ant-col-lg-order-12 {
    order: 12
  }

  .ant-col-lg-11 {
    display: block;
    box-sizing: border-box;
    width: 45.83333333%
  }

  .ant-col-lg-push-11 {
    left: 45.83333333%
  }

  .ant-col-lg-pull-11 {
    right: 45.83333333%
  }

  .ant-col-lg-offset-11 {
    margin-left: 45.83333333%
  }

  .ant-col-lg-order-11 {
    order: 11
  }

  .ant-col-lg-10 {
    display: block;
    box-sizing: border-box;
    width: 41.66666667%
  }

  .ant-col-lg-push-10 {
    left: 41.66666667%
  }

  .ant-col-lg-pull-10 {
    right: 41.66666667%
  }

  .ant-col-lg-offset-10 {
    margin-left: 41.66666667%
  }

  .ant-col-lg-order-10 {
    order: 10
  }

  .ant-col-lg-9 {
    display: block;
    box-sizing: border-box;
    width: 37.5%
  }

  .ant-col-lg-push-9 {
    left: 37.5%
  }

  .ant-col-lg-pull-9 {
    right: 37.5%
  }

  .ant-col-lg-offset-9 {
    margin-left: 37.5%
  }

  .ant-col-lg-order-9 {
    order: 9
  }

  .ant-col-lg-8 {
    display: block;
    box-sizing: border-box;
    width: 33.33333333%
  }

  .ant-col-lg-push-8 {
    left: 33.33333333%
  }

  .ant-col-lg-pull-8 {
    right: 33.33333333%
  }

  .ant-col-lg-offset-8 {
    margin-left: 33.33333333%
  }

  .ant-col-lg-order-8 {
    order: 8
  }

  .ant-col-lg-7 {
    display: block;
    box-sizing: border-box;
    width: 29.16666667%
  }

  .ant-col-lg-push-7 {
    left: 29.16666667%
  }

  .ant-col-lg-pull-7 {
    right: 29.16666667%
  }

  .ant-col-lg-offset-7 {
    margin-left: 29.16666667%
  }

  .ant-col-lg-order-7 {
    order: 7
  }

  .ant-col-lg-6 {
    display: block;
    box-sizing: border-box;
    width: 25%
  }

  .ant-col-lg-push-6 {
    left: 25%
  }

  .ant-col-lg-pull-6 {
    right: 25%
  }

  .ant-col-lg-offset-6 {
    margin-left: 25%
  }

  .ant-col-lg-order-6 {
    order: 6
  }

  .ant-col-lg-5 {
    display: block;
    box-sizing: border-box;
    width: 20.83333333%
  }

  .ant-col-lg-push-5 {
    left: 20.83333333%
  }

  .ant-col-lg-pull-5 {
    right: 20.83333333%
  }

  .ant-col-lg-offset-5 {
    margin-left: 20.83333333%
  }

  .ant-col-lg-order-5 {
    order: 5
  }

  .ant-col-lg-4 {
    display: block;
    box-sizing: border-box;
    width: 16.66666667%
  }

  .ant-col-lg-push-4 {
    left: 16.66666667%
  }

  .ant-col-lg-pull-4 {
    right: 16.66666667%
  }

  .ant-col-lg-offset-4 {
    margin-left: 16.66666667%
  }

  .ant-col-lg-order-4 {
    order: 4
  }

  .ant-col-lg-3 {
    display: block;
    box-sizing: border-box;
    width: 12.5%
  }

  .ant-col-lg-push-3 {
    left: 12.5%
  }

  .ant-col-lg-pull-3 {
    right: 12.5%
  }

  .ant-col-lg-offset-3 {
    margin-left: 12.5%
  }

  .ant-col-lg-order-3 {
    order: 3
  }

  .ant-col-lg-2 {
    display: block;
    box-sizing: border-box;
    width: 8.33333333%
  }

  .ant-col-lg-push-2 {
    left: 8.33333333%
  }

  .ant-col-lg-pull-2 {
    right: 8.33333333%
  }

  .ant-col-lg-offset-2 {
    margin-left: 8.33333333%
  }

  .ant-col-lg-order-2 {
    order: 2
  }

  .ant-col-lg-1 {
    display: block;
    box-sizing: border-box;
    width: 4.16666667%
  }

  .ant-col-lg-push-1 {
    left: 4.16666667%
  }

  .ant-col-lg-pull-1 {
    right: 4.16666667%
  }

  .ant-col-lg-offset-1 {
    margin-left: 4.16666667%
  }

  .ant-col-lg-order-1 {
    order: 1
  }

  .ant-col-lg-0 {
    display: none
  }

  .ant-col-push-0 {
    left: auto
  }

  .ant-col-pull-0 {
    right: auto
  }

  .ant-col-lg-push-0 {
    left: auto
  }

  .ant-col-lg-pull-0 {
    right: auto
  }

  .ant-col-lg-offset-0 {
    margin-left: 0
  }

  .ant-col-lg-order-0 {
    order: 0
  }
}

@media (min-width:1200px) {

  .ant-col-xl-1,
  .ant-col-xl-2,
  .ant-col-xl-3,
  .ant-col-xl-4,
  .ant-col-xl-5,
  .ant-col-xl-6,
  .ant-col-xl-7,
  .ant-col-xl-8,
  .ant-col-xl-9,
  .ant-col-xl-10,
  .ant-col-xl-11,
  .ant-col-xl-12,
  .ant-col-xl-13,
  .ant-col-xl-14,
  .ant-col-xl-15,
  .ant-col-xl-16,
  .ant-col-xl-17,
  .ant-col-xl-18,
  .ant-col-xl-19,
  .ant-col-xl-20,
  .ant-col-xl-21,
  .ant-col-xl-22,
  .ant-col-xl-23,
  .ant-col-xl-24 {
    flex: 0 0 auto;
    float: left
  }

  .ant-col-xl-24 {
    display: block;
    box-sizing: border-box;
    width: 100%
  }

  .ant-col-xl-push-24 {
    left: 100%
  }

  .ant-col-xl-pull-24 {
    right: 100%
  }

  .ant-col-xl-offset-24 {
    margin-left: 100%
  }

  .ant-col-xl-order-24 {
    order: 24
  }

  .ant-col-xl-23 {
    display: block;
    box-sizing: border-box;
    width: 95.83333333%
  }

  .ant-col-xl-push-23 {
    left: 95.83333333%
  }

  .ant-col-xl-pull-23 {
    right: 95.83333333%
  }

  .ant-col-xl-offset-23 {
    margin-left: 95.83333333%
  }

  .ant-col-xl-order-23 {
    order: 23
  }

  .ant-col-xl-22 {
    display: block;
    box-sizing: border-box;
    width: 91.66666667%
  }

  .ant-col-xl-push-22 {
    left: 91.66666667%
  }

  .ant-col-xl-pull-22 {
    right: 91.66666667%
  }

  .ant-col-xl-offset-22 {
    margin-left: 91.66666667%
  }

  .ant-col-xl-order-22 {
    order: 22
  }

  .ant-col-xl-21 {
    display: block;
    box-sizing: border-box;
    width: 87.5%
  }

  .ant-col-xl-push-21 {
    left: 87.5%
  }

  .ant-col-xl-pull-21 {
    right: 87.5%
  }

  .ant-col-xl-offset-21 {
    margin-left: 87.5%
  }

  .ant-col-xl-order-21 {
    order: 21
  }

  .ant-col-xl-20 {
    display: block;
    box-sizing: border-box;
    width: 83.33333333%
  }

  .ant-col-xl-push-20 {
    left: 83.33333333%
  }

  .ant-col-xl-pull-20 {
    right: 83.33333333%
  }

  .ant-col-xl-offset-20 {
    margin-left: 83.33333333%
  }

  .ant-col-xl-order-20 {
    order: 20
  }

  .ant-col-xl-19 {
    display: block;
    box-sizing: border-box;
    width: 79.16666667%
  }

  .ant-col-xl-push-19 {
    left: 79.16666667%
  }

  .ant-col-xl-pull-19 {
    right: 79.16666667%
  }

  .ant-col-xl-offset-19 {
    margin-left: 79.16666667%
  }

  .ant-col-xl-order-19 {
    order: 19
  }

  .ant-col-xl-18 {
    display: block;
    box-sizing: border-box;
    width: 75%
  }

  .ant-col-xl-push-18 {
    left: 75%
  }

  .ant-col-xl-pull-18 {
    right: 75%
  }

  .ant-col-xl-offset-18 {
    margin-left: 75%
  }

  .ant-col-xl-order-18 {
    order: 18
  }

  .ant-col-xl-17 {
    display: block;
    box-sizing: border-box;
    width: 70.83333333%
  }

  .ant-col-xl-push-17 {
    left: 70.83333333%
  }

  .ant-col-xl-pull-17 {
    right: 70.83333333%
  }

  .ant-col-xl-offset-17 {
    margin-left: 70.83333333%
  }

  .ant-col-xl-order-17 {
    order: 17
  }

  .ant-col-xl-16 {
    display: block;
    box-sizing: border-box;
    width: 66.66666667%
  }

  .ant-col-xl-push-16 {
    left: 66.66666667%
  }

  .ant-col-xl-pull-16 {
    right: 66.66666667%
  }

  .ant-col-xl-offset-16 {
    margin-left: 66.66666667%
  }

  .ant-col-xl-order-16 {
    order: 16
  }

  .ant-col-xl-15 {
    display: block;
    box-sizing: border-box;
    width: 62.5%
  }

  .ant-col-xl-push-15 {
    left: 62.5%
  }

  .ant-col-xl-pull-15 {
    right: 62.5%
  }

  .ant-col-xl-offset-15 {
    margin-left: 62.5%
  }

  .ant-col-xl-order-15 {
    order: 15
  }

  .ant-col-xl-14 {
    display: block;
    box-sizing: border-box;
    width: 58.33333333%
  }

  .ant-col-xl-push-14 {
    left: 58.33333333%
  }

  .ant-col-xl-pull-14 {
    right: 58.33333333%
  }

  .ant-col-xl-offset-14 {
    margin-left: 58.33333333%
  }

  .ant-col-xl-order-14 {
    order: 14
  }

  .ant-col-xl-13 {
    display: block;
    box-sizing: border-box;
    width: 54.16666667%
  }

  .ant-col-xl-push-13 {
    left: 54.16666667%
  }

  .ant-col-xl-pull-13 {
    right: 54.16666667%
  }

  .ant-col-xl-offset-13 {
    margin-left: 54.16666667%
  }

  .ant-col-xl-order-13 {
    order: 13
  }

  .ant-col-xl-12 {
    display: block;
    box-sizing: border-box;
    width: 50%
  }

  .ant-col-xl-push-12 {
    left: 50%
  }

  .ant-col-xl-pull-12 {
    right: 50%
  }

  .ant-col-xl-offset-12 {
    margin-left: 50%
  }

  .ant-col-xl-order-12 {
    order: 12
  }

  .ant-col-xl-11 {
    display: block;
    box-sizing: border-box;
    width: 45.83333333%
  }

  .ant-col-xl-push-11 {
    left: 45.83333333%
  }

  .ant-col-xl-pull-11 {
    right: 45.83333333%
  }

  .ant-col-xl-offset-11 {
    margin-left: 45.83333333%
  }

  .ant-col-xl-order-11 {
    order: 11
  }

  .ant-col-xl-10 {
    display: block;
    box-sizing: border-box;
    width: 41.66666667%
  }

  .ant-col-xl-push-10 {
    left: 41.66666667%
  }

  .ant-col-xl-pull-10 {
    right: 41.66666667%
  }

  .ant-col-xl-offset-10 {
    margin-left: 41.66666667%
  }

  .ant-col-xl-order-10 {
    order: 10
  }

  .ant-col-xl-9 {
    display: block;
    box-sizing: border-box;
    width: 37.5%
  }

  .ant-col-xl-push-9 {
    left: 37.5%
  }

  .ant-col-xl-pull-9 {
    right: 37.5%
  }

  .ant-col-xl-offset-9 {
    margin-left: 37.5%
  }

  .ant-col-xl-order-9 {
    order: 9
  }

  .ant-col-xl-8 {
    display: block;
    box-sizing: border-box;
    width: 33.33333333%
  }

  .ant-col-xl-push-8 {
    left: 33.33333333%
  }

  .ant-col-xl-pull-8 {
    right: 33.33333333%
  }

  .ant-col-xl-offset-8 {
    margin-left: 33.33333333%
  }

  .ant-col-xl-order-8 {
    order: 8
  }

  .ant-col-xl-7 {
    display: block;
    box-sizing: border-box;
    width: 29.16666667%
  }

  .ant-col-xl-push-7 {
    left: 29.16666667%
  }

  .ant-col-xl-pull-7 {
    right: 29.16666667%
  }

  .ant-col-xl-offset-7 {
    margin-left: 29.16666667%
  }

  .ant-col-xl-order-7 {
    order: 7
  }

  .ant-col-xl-6 {
    display: block;
    box-sizing: border-box;
    width: 25%
  }

  .ant-col-xl-push-6 {
    left: 25%
  }

  .ant-col-xl-pull-6 {
    right: 25%
  }

  .ant-col-xl-offset-6 {
    margin-left: 25%
  }

  .ant-col-xl-order-6 {
    order: 6
  }

  .ant-col-xl-5 {
    display: block;
    box-sizing: border-box;
    width: 20.83333333%
  }

  .ant-col-xl-push-5 {
    left: 20.83333333%
  }

  .ant-col-xl-pull-5 {
    right: 20.83333333%
  }

  .ant-col-xl-offset-5 {
    margin-left: 20.83333333%
  }

  .ant-col-xl-order-5 {
    order: 5
  }

  .ant-col-xl-4 {
    display: block;
    box-sizing: border-box;
    width: 16.66666667%
  }

  .ant-col-xl-push-4 {
    left: 16.66666667%
  }

  .ant-col-xl-pull-4 {
    right: 16.66666667%
  }

  .ant-col-xl-offset-4 {
    margin-left: 16.66666667%
  }

  .ant-col-xl-order-4 {
    order: 4
  }

  .ant-col-xl-3 {
    display: block;
    box-sizing: border-box;
    width: 12.5%
  }

  .ant-col-xl-push-3 {
    left: 12.5%
  }

  .ant-col-xl-pull-3 {
    right: 12.5%
  }

  .ant-col-xl-offset-3 {
    margin-left: 12.5%
  }

  .ant-col-xl-order-3 {
    order: 3
  }

  .ant-col-xl-2 {
    display: block;
    box-sizing: border-box;
    width: 8.33333333%
  }

  .ant-col-xl-push-2 {
    left: 8.33333333%
  }

  .ant-col-xl-pull-2 {
    right: 8.33333333%
  }

  .ant-col-xl-offset-2 {
    margin-left: 8.33333333%
  }

  .ant-col-xl-order-2 {
    order: 2
  }

  .ant-col-xl-1 {
    display: block;
    box-sizing: border-box;
    width: 4.16666667%
  }

  .ant-col-xl-push-1 {
    left: 4.16666667%
  }

  .ant-col-xl-pull-1 {
    right: 4.16666667%
  }

  .ant-col-xl-offset-1 {
    margin-left: 4.16666667%
  }

  .ant-col-xl-order-1 {
    order: 1
  }

  .ant-col-xl-0 {
    display: none
  }

  .ant-col-push-0 {
    left: auto
  }

  .ant-col-pull-0 {
    right: auto
  }

  .ant-col-xl-push-0 {
    left: auto
  }

  .ant-col-xl-pull-0 {
    right: auto
  }

  .ant-col-xl-offset-0 {
    margin-left: 0
  }

  .ant-col-xl-order-0 {
    order: 0
  }
}

@media (min-width:1600px) {

  .ant-col-xxl-1,
  .ant-col-xxl-2,
  .ant-col-xxl-3,
  .ant-col-xxl-4,
  .ant-col-xxl-5,
  .ant-col-xxl-6,
  .ant-col-xxl-7,
  .ant-col-xxl-8,
  .ant-col-xxl-9,
  .ant-col-xxl-10,
  .ant-col-xxl-11,
  .ant-col-xxl-12,
  .ant-col-xxl-13,
  .ant-col-xxl-14,
  .ant-col-xxl-15,
  .ant-col-xxl-16,
  .ant-col-xxl-17,
  .ant-col-xxl-18,
  .ant-col-xxl-19,
  .ant-col-xxl-20,
  .ant-col-xxl-21,
  .ant-col-xxl-22,
  .ant-col-xxl-23,
  .ant-col-xxl-24 {
    flex: 0 0 auto;
    float: left
  }

  .ant-col-xxl-24 {
    display: block;
    box-sizing: border-box;
    width: 100%
  }

  .ant-col-xxl-push-24 {
    left: 100%
  }

  .ant-col-xxl-pull-24 {
    right: 100%
  }

  .ant-col-xxl-offset-24 {
    margin-left: 100%
  }

  .ant-col-xxl-order-24 {
    order: 24
  }

  .ant-col-xxl-23 {
    display: block;
    box-sizing: border-box;
    width: 95.83333333%
  }

  .ant-col-xxl-push-23 {
    left: 95.83333333%
  }

  .ant-col-xxl-pull-23 {
    right: 95.83333333%
  }

  .ant-col-xxl-offset-23 {
    margin-left: 95.83333333%
  }

  .ant-col-xxl-order-23 {
    order: 23
  }

  .ant-col-xxl-22 {
    display: block;
    box-sizing: border-box;
    width: 91.66666667%
  }

  .ant-col-xxl-push-22 {
    left: 91.66666667%
  }

  .ant-col-xxl-pull-22 {
    right: 91.66666667%
  }

  .ant-col-xxl-offset-22 {
    margin-left: 91.66666667%
  }

  .ant-col-xxl-order-22 {
    order: 22
  }

  .ant-col-xxl-21 {
    display: block;
    box-sizing: border-box;
    width: 87.5%
  }

  .ant-col-xxl-push-21 {
    left: 87.5%
  }

  .ant-col-xxl-pull-21 {
    right: 87.5%
  }

  .ant-col-xxl-offset-21 {
    margin-left: 87.5%
  }

  .ant-col-xxl-order-21 {
    order: 21
  }

  .ant-col-xxl-20 {
    display: block;
    box-sizing: border-box;
    width: 83.33333333%
  }

  .ant-col-xxl-push-20 {
    left: 83.33333333%
  }

  .ant-col-xxl-pull-20 {
    right: 83.33333333%
  }

  .ant-col-xxl-offset-20 {
    margin-left: 83.33333333%
  }

  .ant-col-xxl-order-20 {
    order: 20
  }

  .ant-col-xxl-19 {
    display: block;
    box-sizing: border-box;
    width: 79.16666667%
  }

  .ant-col-xxl-push-19 {
    left: 79.16666667%
  }

  .ant-col-xxl-pull-19 {
    right: 79.16666667%
  }

  .ant-col-xxl-offset-19 {
    margin-left: 79.16666667%
  }

  .ant-col-xxl-order-19 {
    order: 19
  }

  .ant-col-xxl-18 {
    display: block;
    box-sizing: border-box;
    width: 75%
  }

  .ant-col-xxl-push-18 {
    left: 75%
  }

  .ant-col-xxl-pull-18 {
    right: 75%
  }

  .ant-col-xxl-offset-18 {
    margin-left: 75%
  }

  .ant-col-xxl-order-18 {
    order: 18
  }

  .ant-col-xxl-17 {
    display: block;
    box-sizing: border-box;
    width: 70.83333333%
  }

  .ant-col-xxl-push-17 {
    left: 70.83333333%
  }

  .ant-col-xxl-pull-17 {
    right: 70.83333333%
  }

  .ant-col-xxl-offset-17 {
    margin-left: 70.83333333%
  }

  .ant-col-xxl-order-17 {
    order: 17
  }

  .ant-col-xxl-16 {
    display: block;
    box-sizing: border-box;
    width: 66.66666667%
  }

  .ant-col-xxl-push-16 {
    left: 66.66666667%
  }

  .ant-col-xxl-pull-16 {
    right: 66.66666667%
  }

  .ant-col-xxl-offset-16 {
    margin-left: 66.66666667%
  }

  .ant-col-xxl-order-16 {
    order: 16
  }

  .ant-col-xxl-15 {
    display: block;
    box-sizing: border-box;
    width: 62.5%
  }

  .ant-col-xxl-push-15 {
    left: 62.5%
  }

  .ant-col-xxl-pull-15 {
    right: 62.5%
  }

  .ant-col-xxl-offset-15 {
    margin-left: 62.5%
  }

  .ant-col-xxl-order-15 {
    order: 15
  }

  .ant-col-xxl-14 {
    display: block;
    box-sizing: border-box;
    width: 58.33333333%
  }

  .ant-col-xxl-push-14 {
    left: 58.33333333%
  }

  .ant-col-xxl-pull-14 {
    right: 58.33333333%
  }

  .ant-col-xxl-offset-14 {
    margin-left: 58.33333333%
  }

  .ant-col-xxl-order-14 {
    order: 14
  }

  .ant-col-xxl-13 {
    display: block;
    box-sizing: border-box;
    width: 54.16666667%
  }

  .ant-col-xxl-push-13 {
    left: 54.16666667%
  }

  .ant-col-xxl-pull-13 {
    right: 54.16666667%
  }

  .ant-col-xxl-offset-13 {
    margin-left: 54.16666667%
  }

  .ant-col-xxl-order-13 {
    order: 13
  }

  .ant-col-xxl-12 {
    display: block;
    box-sizing: border-box;
    width: 50%
  }

  .ant-col-xxl-push-12 {
    left: 50%
  }

  .ant-col-xxl-pull-12 {
    right: 50%
  }

  .ant-col-xxl-offset-12 {
    margin-left: 50%
  }

  .ant-col-xxl-order-12 {
    order: 12
  }

  .ant-col-xxl-11 {
    display: block;
    box-sizing: border-box;
    width: 45.83333333%
  }

  .ant-col-xxl-push-11 {
    left: 45.83333333%
  }

  .ant-col-xxl-pull-11 {
    right: 45.83333333%
  }

  .ant-col-xxl-offset-11 {
    margin-left: 45.83333333%
  }

  .ant-col-xxl-order-11 {
    order: 11
  }

  .ant-col-xxl-10 {
    display: block;
    box-sizing: border-box;
    width: 41.66666667%
  }

  .ant-col-xxl-push-10 {
    left: 41.66666667%
  }

  .ant-col-xxl-pull-10 {
    right: 41.66666667%
  }

  .ant-col-xxl-offset-10 {
    margin-left: 41.66666667%
  }

  .ant-col-xxl-order-10 {
    order: 10
  }

  .ant-col-xxl-9 {
    display: block;
    box-sizing: border-box;
    width: 37.5%
  }

  .ant-col-xxl-push-9 {
    left: 37.5%
  }

  .ant-col-xxl-pull-9 {
    right: 37.5%
  }

  .ant-col-xxl-offset-9 {
    margin-left: 37.5%
  }

  .ant-col-xxl-order-9 {
    order: 9
  }

  .ant-col-xxl-8 {
    display: block;
    box-sizing: border-box;
    width: 33.33333333%
  }

  .ant-col-xxl-push-8 {
    left: 33.33333333%
  }

  .ant-col-xxl-pull-8 {
    right: 33.33333333%
  }

  .ant-col-xxl-offset-8 {
    margin-left: 33.33333333%
  }

  .ant-col-xxl-order-8 {
    order: 8
  }

  .ant-col-xxl-7 {
    display: block;
    box-sizing: border-box;
    width: 29.16666667%
  }

  .ant-col-xxl-push-7 {
    left: 29.16666667%
  }

  .ant-col-xxl-pull-7 {
    right: 29.16666667%
  }

  .ant-col-xxl-offset-7 {
    margin-left: 29.16666667%
  }

  .ant-col-xxl-order-7 {
    order: 7
  }

  .ant-col-xxl-6 {
    display: block;
    box-sizing: border-box;
    width: 25%
  }

  .ant-col-xxl-push-6 {
    left: 25%
  }

  .ant-col-xxl-pull-6 {
    right: 25%
  }

  .ant-col-xxl-offset-6 {
    margin-left: 25%
  }

  .ant-col-xxl-order-6 {
    order: 6
  }

  .ant-col-xxl-5 {
    display: block;
    box-sizing: border-box;
    width: 20.83333333%
  }

  .ant-col-xxl-push-5 {
    left: 20.83333333%
  }

  .ant-col-xxl-pull-5 {
    right: 20.83333333%
  }

  .ant-col-xxl-offset-5 {
    margin-left: 20.83333333%
  }

  .ant-col-xxl-order-5 {
    order: 5
  }

  .ant-col-xxl-4 {
    display: block;
    box-sizing: border-box;
    width: 16.66666667%
  }

  .ant-col-xxl-push-4 {
    left: 16.66666667%
  }

  .ant-col-xxl-pull-4 {
    right: 16.66666667%
  }

  .ant-col-xxl-offset-4 {
    margin-left: 16.66666667%
  }

  .ant-col-xxl-order-4 {
    order: 4
  }

  .ant-col-xxl-3 {
    display: block;
    box-sizing: border-box;
    width: 12.5%
  }

  .ant-col-xxl-push-3 {
    left: 12.5%
  }

  .ant-col-xxl-pull-3 {
    right: 12.5%
  }

  .ant-col-xxl-offset-3 {
    margin-left: 12.5%
  }

  .ant-col-xxl-order-3 {
    order: 3
  }

  .ant-col-xxl-2 {
    display: block;
    box-sizing: border-box;
    width: 8.33333333%
  }

  .ant-col-xxl-push-2 {
    left: 8.33333333%
  }

  .ant-col-xxl-pull-2 {
    right: 8.33333333%
  }

  .ant-col-xxl-offset-2 {
    margin-left: 8.33333333%
  }

  .ant-col-xxl-order-2 {
    order: 2
  }

  .ant-col-xxl-1 {
    display: block;
    box-sizing: border-box;
    width: 4.16666667%
  }

  .ant-col-xxl-push-1 {
    left: 4.16666667%
  }

  .ant-col-xxl-pull-1 {
    right: 4.16666667%
  }

  .ant-col-xxl-offset-1 {
    margin-left: 4.16666667%
  }

  .ant-col-xxl-order-1 {
    order: 1
  }

  .ant-col-xxl-0 {
    display: none
  }

  .ant-col-push-0 {
    left: auto
  }

  .ant-col-pull-0 {
    right: auto
  }

  .ant-col-xxl-push-0 {
    left: auto
  }

  .ant-col-xxl-pull-0 {
    right: auto
  }

  .ant-col-xxl-offset-0 {
    margin-left: 0
  }

  .ant-col-xxl-order-0 {
    order: 0
  }
}

.ant-input {
  box-sizing: border-box;
  margin: 0;
  font-variant: tabular-nums;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  width: 100%;
  height: 32px;
  padding: 4px 11px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5;
  background-color: #fff;
  background-image: none;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-input:focus,
.ant-input:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-input:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-input-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-input-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-input[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-input[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-input {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-input-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-input-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-input-group {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: table;
  width: 100%;
  border-collapse: separate;
  border-spacing: 0
}

.ant-input-group[class*=col-] {
  float: none;
  padding-right: 0;
  padding-left: 0
}

.ant-input-group>[class*=col-] {
  padding-right: 8px
}

.ant-input-group>[class*=col-]:last-child {
  padding-right: 0
}

.ant-input-group-addon,
.ant-input-group-wrap,
.ant-input-group>.ant-input {
  display: table-cell
}

.ant-input-group-addon:not(:first-child):not(:last-child),
.ant-input-group-wrap:not(:first-child):not(:last-child),
.ant-input-group>.ant-input:not(:first-child):not(:last-child) {
  border-radius: 0
}

.ant-input-group-addon,
.ant-input-group-wrap {
  width: 1px;
  white-space: nowrap;
  vertical-align: middle
}

.ant-input-group-wrap>* {
  display: block !important
}

.ant-input-group .ant-input {
  float: left;
  width: 100%;
  margin-bottom: 0;
  text-align: inherit
}

.ant-input-group .ant-input:focus,
.ant-input-group .ant-input:hover {
  z-index: 1;
  border-right-width: 1px
}

.ant-input-group-addon {
  position: relative;
  padding: 0 11px;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  font-size: 14px;
  text-align: center;
  background-color: #fafafa;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-input-group-addon .ant-select {
  margin: -5px -11px
}

.ant-input-group-addon .ant-select .ant-select-selection {
  margin: -1px;
  background-color: inherit;
  border: 1px solid transparent;
  box-shadow: none
}

.ant-input-group-addon .ant-select-focused .ant-select-selection,
.ant-input-group-addon .ant-select-open .ant-select-selection {
  color: #03a9f4
}

.ant-input-group-addon>i:only-child:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  content: ""
}

.ant-input-group-addon:first-child,
.ant-input-group-addon:first-child .ant-select .ant-select-selection,
.ant-input-group>.ant-input:first-child,
.ant-input-group>.ant-input:first-child .ant-select .ant-select-selection {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0
}

.ant-input-group>.ant-input-affix-wrapper:not(:first-child) .ant-input {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0
}

.ant-input-group>.ant-input-affix-wrapper:not(:last-child) .ant-input {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0
}

.ant-input-group-addon:first-child {
  border-right: 0
}

.ant-input-group-addon:last-child {
  border-left: 0
}

.ant-input-group-addon:last-child,
.ant-input-group-addon:last-child .ant-select .ant-select-selection,
.ant-input-group>.ant-input:last-child,
.ant-input-group>.ant-input:last-child .ant-select .ant-select-selection {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0
}

.ant-input-group-lg .ant-input,
.ant-input-group-lg>.ant-input-group-addon {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-input-group-sm .ant-input,
.ant-input-group-sm>.ant-input-group-addon {
  height: 24px;
  padding: 1px 7px
}

.ant-input-group-lg .ant-select-selection--single {
  height: 40px
}

.ant-input-group-sm .ant-select-selection--single {
  height: 24px
}

.ant-input-group .ant-input-affix-wrapper {
  display: table-cell;
  float: left;
  width: 100%
}

.ant-input-group.ant-input-group-compact {
  display: block;
  zoom: 1
}

.ant-input-group.ant-input-group-compact:after,
.ant-input-group.ant-input-group-compact:before {
  display: table;
  content: ""
}

.ant-input-group.ant-input-group-compact:after {
  clear: both
}

.ant-input-group.ant-input-group-compact-addon:not(:first-child):not(:last-child),
.ant-input-group.ant-input-group-compact-wrap:not(:first-child):not(:last-child),
.ant-input-group.ant-input-group-compact>.ant-input:not(:first-child):not(:last-child) {
  border-right-width: 1px
}

.ant-input-group.ant-input-group-compact-addon:not(:first-child):not(:last-child):focus,
.ant-input-group.ant-input-group-compact-addon:not(:first-child):not(:last-child):hover,
.ant-input-group.ant-input-group-compact-wrap:not(:first-child):not(:last-child):focus,
.ant-input-group.ant-input-group-compact-wrap:not(:first-child):not(:last-child):hover,
.ant-input-group.ant-input-group-compact>.ant-input:not(:first-child):not(:last-child):focus,
.ant-input-group.ant-input-group-compact>.ant-input:not(:first-child):not(:last-child):hover {
  z-index: 1
}

.ant-input-group.ant-input-group-compact>* {
  display: inline-block;
  float: none;
  vertical-align: top;
  border-radius: 0
}

.ant-input-group.ant-input-group-compact>:not(:last-child) {
  margin-right: -1px;
  border-right-width: 1px
}

.ant-input-group.ant-input-group-compact .ant-input {
  float: none
}

.ant-input-group.ant-input-group-compact>.ant-calendar-picker .ant-input,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker .ant-input,
.ant-input-group.ant-input-group-compact>.ant-mention-wrapper .ant-mention-editor,
.ant-input-group.ant-input-group-compact>.ant-select-auto-complete .ant-input,
.ant-input-group.ant-input-group-compact>.ant-select>.ant-select-selection,
.ant-input-group.ant-input-group-compact>.ant-time-picker .ant-time-picker-input {
  border-right-width: 1px;
  border-radius: 0
}

.ant-input-group.ant-input-group-compact>.ant-calendar-picker .ant-input:focus,
.ant-input-group.ant-input-group-compact>.ant-calendar-picker .ant-input:hover,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker .ant-input:focus,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker .ant-input:hover,
.ant-input-group.ant-input-group-compact>.ant-mention-wrapper .ant-mention-editor:focus,
.ant-input-group.ant-input-group-compact>.ant-mention-wrapper .ant-mention-editor:hover,
.ant-input-group.ant-input-group-compact>.ant-select-auto-complete .ant-input:focus,
.ant-input-group.ant-input-group-compact>.ant-select-auto-complete .ant-input:hover,
.ant-input-group.ant-input-group-compact>.ant-select>.ant-select-selection:focus,
.ant-input-group.ant-input-group-compact>.ant-select>.ant-select-selection:hover,
.ant-input-group.ant-input-group-compact>.ant-time-picker .ant-time-picker-input:focus,
.ant-input-group.ant-input-group-compact>.ant-time-picker .ant-time-picker-input:hover {
  z-index: 1
}

.ant-input-group.ant-input-group-compact>.ant-calendar-picker:first-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker:first-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-mention-wrapper:first-child .ant-mention-editor,
.ant-input-group.ant-input-group-compact>.ant-select-auto-complete:first-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-select:first-child>.ant-select-selection,
.ant-input-group.ant-input-group-compact>.ant-time-picker:first-child .ant-time-picker-input,
.ant-input-group.ant-input-group-compact>:first-child {
  border-top-left-radius: 4px;
  border-bottom-left-radius: 4px
}

.ant-input-group.ant-input-group-compact>.ant-calendar-picker:last-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker-focused:last-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-cascader-picker:last-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-mention-wrapper:last-child .ant-mention-editor,
.ant-input-group.ant-input-group-compact>.ant-select-auto-complete:last-child .ant-input,
.ant-input-group.ant-input-group-compact>.ant-select:last-child>.ant-select-selection,
.ant-input-group.ant-input-group-compact>.ant-time-picker:last-child .ant-time-picker-input,
.ant-input-group.ant-input-group-compact>:last-child {
  border-right-width: 1px;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px
}

.ant-input-group.ant-input-group-compact>.ant-select-auto-complete .ant-input {
  vertical-align: top
}

.ant-input-group-wrapper {
  display: inline-block;
  width: 100%;
  text-align: start;
  vertical-align: top
}

.ant-input-affix-wrapper {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  width: 100%;
  text-align: start
}

.ant-input-affix-wrapper:hover .ant-input:not(.ant-input-disabled) {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-input-affix-wrapper .ant-input {
  position: relative;
  text-align: inherit
}

.ant-input-affix-wrapper .ant-input-prefix,
.ant-input-affix-wrapper .ant-input-suffix {
  position: absolute;
  top: 50%;
  z-index: 2;
  display: flex;
  align-items: center;
  color: rgba(0, 0, 0, .65);
  line-height: 0;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-input-affix-wrapper .ant-input-prefix :not(.anticon),
.ant-input-affix-wrapper .ant-input-suffix :not(.anticon) {
  line-height: 1.5
}

.ant-input-affix-wrapper .ant-input-disabled~.ant-input-suffix .anticon {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-input-affix-wrapper .ant-input-prefix {
  left: 12px
}

.ant-input-affix-wrapper .ant-input-suffix {
  right: 12px
}

.ant-input-affix-wrapper .ant-input:not(:first-child) {
  padding-left: 30px
}

.ant-input-affix-wrapper .ant-input:not(:last-child) {
  padding-right: 30px
}

.ant-input-affix-wrapper.ant-input-affix-wrapper-with-clear-btn .ant-input:not(:last-child) {
  padding-right: 49px
}

.ant-input-affix-wrapper .ant-input {
  min-height: 100%
}

.ant-input-password-icon {
  color: rgba(0, 0, 0, .45);
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-input-password-icon:hover {
  color: #333
}

.ant-input-clear-icon {
  color: rgba(0, 0, 0, .25);
  font-size: 12px;
  vertical-align: 0;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-input-clear-icon:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-input-clear-icon:active {
  color: rgba(0, 0, 0, .65)
}

.ant-input-clear-icon+i {
  margin-left: 6px
}

.ant-input-search-icon {
  color: rgba(0, 0, 0, .45);
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-input-search-icon:hover {
  color: rgba(0, 0, 0, .8)
}

.ant-input-search-enter-button input {
  border-right: 0
}

.ant-input-search-enter-button+.ant-input-group-addon,
.ant-input-search-enter-button input+.ant-input-group-addon {
  padding: 0;
  border: 0
}

.ant-input-search-enter-button+.ant-input-group-addon .ant-input-search-button,
.ant-input-search-enter-button input+.ant-input-group-addon .ant-input-search-button {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0
}

.ant-input-number {
  box-sizing: border-box;
  font-variant: tabular-nums;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  width: 100%;
  height: 32px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5;
  background-color: #fff;
  background-image: none;
  -webkit-transition: all .3s;
  transition: all .3s;
  display: inline-block;
  width: 90px;
  margin: 0;
  padding: 0;
  border: 1px solid #d9d9d9;
  border-radius: 4px
}

.ant-input-number::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-input-number:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-input-number::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-input-number:placeholder-shown {
  text-overflow: ellipsis
}

.ant-input-number:focus {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-input-number[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-input-number[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-input-number {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-input-number-lg {
  height: 40px;
  padding: 6px 11px
}

.ant-input-number-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-input-number-handler {
  position: relative;
  display: block;
  width: 100%;
  height: 50%;
  overflow: hidden;
  color: rgba(0, 0, 0, .45);
  font-weight: 700;
  line-height: 0;
  text-align: center;
  -webkit-transition: all .1s linear;
  transition: all .1s linear
}

.ant-input-number-handler:active {
  background: #f4f4f4
}

.ant-input-number-handler:hover .ant-input-number-handler-down-inner,
.ant-input-number-handler:hover .ant-input-number-handler-up-inner {
  color: #2bc3ff
}

.ant-input-number-handler-down-inner,
.ant-input-number-handler-up-inner {
  display: inline-block;
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: absolute;
  right: 4px;
  width: 12px;
  height: 12px;
  color: rgba(0, 0, 0, .45);
  line-height: 12px;
  -webkit-transition: all .1s linear;
  transition: all .1s linear;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-input-number-handler-down-inner>*,
.ant-input-number-handler-up-inner>* {
  line-height: 1
}

.ant-input-number-handler-down-inner svg,
.ant-input-number-handler-up-inner svg {
  display: inline-block
}

.ant-input-number-handler-down-inner:before,
.ant-input-number-handler-up-inner:before {
  display: none
}

.ant-input-number-handler-down-inner .ant-input-number-handler-down-inner-icon,
.ant-input-number-handler-down-inner .ant-input-number-handler-up-inner-icon,
.ant-input-number-handler-up-inner .ant-input-number-handler-down-inner-icon,
.ant-input-number-handler-up-inner .ant-input-number-handler-up-inner-icon {
  display: block
}

.ant-input-number-focused,
.ant-input-number:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-input-number-focused {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-input-number-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-input-number-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-input-number-disabled .ant-input-number-input {
  cursor: not-allowed
}

.ant-input-number-disabled .ant-input-number-handler-wrap {
  display: none
}

.ant-input-number-input {
  width: 100%;
  height: 30px;
  padding: 0 11px;
  text-align: left;
  background-color: transparent;
  border: 0;
  border-radius: 4px;
  outline: 0;
  -webkit-transition: all .3s linear;
  transition: all .3s linear;
  -moz-appearance: textfield !important
}

.ant-input-number-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-input-number-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-input-number-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-input-number-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-input-number-input[type=number]::-webkit-inner-spin-button,
.ant-input-number-input[type=number]::-webkit-outer-spin-button {
  margin: 0;
  -webkit-appearance: none
}

.ant-input-number-lg {
  padding: 0;
  font-size: 16px
}

.ant-input-number-lg input {
  height: 38px
}

.ant-input-number-sm {
  padding: 0
}

.ant-input-number-sm input {
  height: 22px;
  padding: 0 7px
}

.ant-input-number-handler-wrap {
  position: absolute;
  top: 0;
  right: 0;
  width: 22px;
  height: 100%;
  background: #fff;
  border-left: 1px solid #d9d9d9;
  border-radius: 0 4px 4px 0;
  opacity: 0;
  -webkit-transition: opacity .24s linear .1s;
  transition: opacity .24s linear .1s
}

.ant-input-number-handler-wrap .ant-input-number-handler .ant-input-number-handler-down-inner,
.ant-input-number-handler-wrap .ant-input-number-handler .ant-input-number-handler-up-inner {
  display: inline-block;
  font-size: 12px;
  font-size: 7px\9;
  -webkit-transform: scale(.58333333) rotate(0deg);
  transform: scale(.58333333) rotate(0deg);
  min-width: auto;
  margin-right: 0
}

:root .ant-input-number-handler-wrap .ant-input-number-handler .ant-input-number-handler-down-inner,
:root .ant-input-number-handler-wrap .ant-input-number-handler .ant-input-number-handler-up-inner {
  font-size: 12px
}

.ant-input-number-handler-wrap:hover .ant-input-number-handler {
  height: 40%
}

.ant-input-number:hover .ant-input-number-handler-wrap {
  opacity: 1
}

.ant-input-number-handler-up {
  border-top-right-radius: 4px;
  cursor: pointer
}

.ant-input-number-handler-up-inner {
  top: 50%;
  margin-top: -5px;
  text-align: center
}

.ant-input-number-handler-up:hover {
  height: 60% !important
}

.ant-input-number-handler-down {
  top: 0;
  border-top: 1px solid #d9d9d9;
  border-bottom-right-radius: 4px;
  cursor: pointer
}

.ant-input-number-handler-down-inner {
  top: 50%;
  margin-top: -6px;
  text-align: center
}

.ant-input-number-handler-down:hover {
  height: 60% !important
}

.ant-input-number-handler-down-disabled,
.ant-input-number-handler-up-disabled {
  cursor: not-allowed
}

.ant-input-number-handler-down-disabled:hover .ant-input-number-handler-down-inner,
.ant-input-number-handler-up-disabled:hover .ant-input-number-handler-up-inner {
  color: rgba(0, 0, 0, .25)
}

.ant-layout {
  display: flex;
  flex: auto;
  flex-direction: column;
  min-height: 0;
  background: #fff
}

.ant-layout,
.ant-layout * {
  box-sizing: border-box
}

.ant-layout.ant-layout-has-sider {
  flex-direction: row
}

.ant-layout.ant-layout-has-sider>.ant-layout,
.ant-layout.ant-layout-has-sider>.ant-layout-content {
  overflow-x: hidden
}

.ant-layout-footer,
.ant-layout-header {
  flex: 0 0 auto
}

.ant-layout-header {
  height: 64px;
  padding: 0 36px;
  line-height: 64px;
  background: #fff
}

.ant-layout-footer {
  padding: 24px 36px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  background: #fff
}

.ant-layout-content {
  flex: auto;
  min-height: 0
}

.ant-layout-sider {
  position: relative;
  min-width: 0;
  background: #fff;
  -webkit-transition: all .2s;
  transition: all .2s
}

.ant-layout-sider-children {
  height: 100%;
  margin-top: -.1px;
  padding-top: .1px
}

.ant-layout-sider-has-trigger {
  padding-bottom: 48px
}

.ant-layout-sider-right {
  order: 1
}

.ant-layout-sider-trigger {
  position: fixed;
  bottom: 0;
  z-index: 1;
  height: 48px;
  color: #fff;
  line-height: 48px;
  text-align: center;
  background: #002140;
  cursor: pointer;
  -webkit-transition: all .2s;
  transition: all .2s
}

.ant-layout-sider-zero-width>* {
  overflow: hidden
}

.ant-layout-sider-zero-width-trigger {
  position: absolute;
  top: 64px;
  right: -36px;
  z-index: 1;
  width: 36px;
  height: 42px;
  color: #fff;
  font-size: 18px;
  line-height: 42px;
  text-align: center;
  background: #fff;
  border-radius: 0 4px 4px 0;
  cursor: pointer;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-layout-sider-zero-width-trigger:hover {
  background: #fff
}

.ant-layout-sider-zero-width-trigger-right {
  left: -36px;
  border-radius: 4px 0 0 4px
}

.ant-layout-sider-light {
  background: #fff
}

.ant-layout-sider-light .ant-layout-sider-trigger,
.ant-layout-sider-light .ant-layout-sider-zero-width-trigger {
  color: rgba(0, 0, 0, .65);
  background: #fff
}

.ant-list {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative
}

.ant-list * {
  outline: none
}

.ant-list-pagination {
  margin-top: 24px;
  text-align: right
}

.ant-list-more {
  margin-top: 12px;
  text-align: center
}

.ant-list-more button {
  padding-right: 32px;
  padding-left: 32px
}

.ant-list-spin {
  min-height: 40px;
  text-align: center
}

.ant-list-empty-text {
  padding: 16px;
  color: rgba(0, 0, 0, .25);
  font-size: 14px;
  text-align: center
}

.ant-list-items {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-list-item {
  display: flex;
  align-items: center;
  padding: 12px 0
}

.ant-list-item-content {
  color: rgba(0, 0, 0, .65)
}

.ant-list-item-meta {
  display: flex;
  flex: 1 1;
  align-items: flex-start;
  font-size: 0
}

.ant-list-item-meta-avatar {
  margin-right: 16px
}

.ant-list-item-meta-content {
  flex: 1 0
}

.ant-list-item-meta-title {
  margin-bottom: 4px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 22px
}

.ant-list-item-meta-title>a {
  color: rgba(0, 0, 0, .65);
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-list-item-meta-title>a:hover {
  color: #03a9f4
}

.ant-list-item-meta-description {
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 22px
}

.ant-list-item-action {
  flex: 0 0 auto;
  margin-left: 48px;
  padding: 0;
  font-size: 0;
  list-style: none
}

.ant-list-item-action>li {
  position: relative;
  display: inline-block;
  padding: 0 8px;
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 22px;
  text-align: center;
  cursor: pointer
}

.ant-list-item-action>li:first-child {
  padding-left: 0
}

.ant-list-item-action-split {
  position: absolute;
  top: 50%;
  right: 0;
  width: 1px;
  height: 14px;
  margin-top: -7px;
  background-color: #e8e8e8
}

.ant-list-footer,
.ant-list-header {
  background: transparent
}

.ant-list-footer,
.ant-list-header {
  padding-top: 12px;
  padding-bottom: 12px
}

.ant-list-empty {
  padding: 16px 0;
  color: rgba(0, 0, 0, .45);
  font-size: 12px;
  text-align: center
}

.ant-list-split .ant-list-item {
  border-bottom: 1px solid #e8e8e8
}

.ant-list-split .ant-list-item:last-child {
  border-bottom: none
}

.ant-list-split .ant-list-header {
  border-bottom: 1px solid #e8e8e8
}

.ant-list-loading .ant-list-spin-nested-loading {
  min-height: 32px
}

.ant-list-something-after-last-item .ant-spin-container>.ant-list-items>.ant-list-item:last-child {
  border-bottom: 1px solid #e8e8e8
}

.ant-list-lg .ant-list-item {
  padding-top: 16px;
  padding-bottom: 16px
}

.ant-list-sm .ant-list-item {
  padding-top: 8px;
  padding-bottom: 8px
}

.ant-list-vertical .ant-list-item {
  align-items: normal
}

.ant-list-vertical .ant-list-item-main {
  display: block;
  flex: 1 1
}

.ant-list-vertical .ant-list-item-extra {
  margin-left: 40px
}

.ant-list-vertical .ant-list-item-meta {
  margin-bottom: 16px
}

.ant-list-vertical .ant-list-item-meta-title {
  margin-bottom: 12px;
  color: rgba(0, 0, 0, .85);
  font-size: 16px;
  line-height: 24px
}

.ant-list-vertical .ant-list-item-action {
  margin-top: 16px;
  margin-left: auto
}

.ant-list-vertical .ant-list-item-action>li {
  padding: 0 16px
}

.ant-list-vertical .ant-list-item-action>li:first-child {
  padding-left: 0
}

.ant-list-grid .ant-col>.ant-list-item {
  display: block;
  max-width: 100%;
  margin-bottom: 16px;
  padding-top: 0;
  padding-bottom: 0;
  border-bottom: none
}

.ant-list-item-no-flex {
  display: block
}

.ant-list:not(.ant-list-vertical) .ant-list-item-no-flex .ant-list-item-action {
  float: right
}

.ant-list-bordered {
  border: 1px solid #d9d9d9;
  border-radius: 4px
}

.ant-list-bordered .ant-list-footer,
.ant-list-bordered .ant-list-header,
.ant-list-bordered .ant-list-item {
  padding-right: 24px;
  padding-left: 24px
}

.ant-list-bordered .ant-list-item {
  border-bottom: 1px solid #e8e8e8
}

.ant-list-bordered .ant-list-pagination {
  margin: 16px 24px
}

.ant-list-bordered.ant-list-sm .ant-list-item {
  padding-right: 16px;
  padding-left: 16px
}

.ant-list-bordered.ant-list-sm .ant-list-footer,
.ant-list-bordered.ant-list-sm .ant-list-header {
  padding: 8px 16px
}

.ant-list-bordered.ant-list-lg .ant-list-footer,
.ant-list-bordered.ant-list-lg .ant-list-header {
  padding: 16px 24px
}

@media screen and (max-width:768px) {

  .ant-list-item-action,
  .ant-list-vertical .ant-list-item-extra {
    margin-left: 24px
  }
}

@media screen and (max-width:576px) {
  .ant-list-item {
    flex-wrap: wrap
  }

  .ant-list-item-action {
    margin-left: 12px
  }

  .ant-list-vertical .ant-list-item {
    flex-wrap: wrap-reverse
  }

  .ant-list-vertical .ant-list-item-main {
    min-width: 220px
  }

  .ant-list-vertical .ant-list-item-extra {
    margin: auto auto 16px
  }
}

.ant-mentions-wrapper {
  box-sizing: border-box;
  margin: 0;
  font-size: 14px;
  font-variant: tabular-nums;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  vertical-align: middle
}

.ant-mentions-wrapper,
.ant-mentions-wrapper .ant-mentions-editor {
  padding: 0;
  color: rgba(0, 0, 0, .65);
  line-height: 1.5;
  position: relative;
  width: 100%
}

.ant-mentions-wrapper .ant-mentions-editor {
  display: inline-block;
  height: 32px;
  font-size: 14px;
  background-color: #fff;
  background-image: none;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s;
  display: block;
  height: auto;
  min-height: 32px
}

.ant-mentions-wrapper .ant-mentions-editor::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-mentions-wrapper .ant-mentions-editor:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-mentions-wrapper .ant-mentions-editor::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-mentions-wrapper .ant-mentions-editor:placeholder-shown {
  text-overflow: ellipsis
}

.ant-mentions-wrapper .ant-mentions-editor:focus,
.ant-mentions-wrapper .ant-mentions-editor:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-mentions-wrapper .ant-mentions-editor:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-mentions-wrapper .ant-mentions-editor-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions-wrapper .ant-mentions-editor-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-mentions-wrapper .ant-mentions-editor[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions-wrapper .ant-mentions-editor[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-mentions-wrapper .ant-mentions-editor {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-mentions-wrapper .ant-mentions-editor-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-mentions-wrapper .ant-mentions-editor-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-mentions-wrapper .ant-mentions-editor-wrapper {
  height: auto;
  overflow-y: auto
}

.ant-mentions-wrapper.ant-mentions-active:not(.disabled) .ant-mentions-editor {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-mentions-wrapper.disabled .ant-mentions-editor {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions-wrapper.disabled .ant-mentions-editor:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-mentions-wrapper .public-DraftEditorPlaceholder-root {
  position: absolute;
  pointer-events: none
}

.ant-mentions-wrapper .public-DraftEditorPlaceholder-root .public-DraftEditorPlaceholder-inner {
  height: auto;
  padding: 5px 11px;
  color: #bfbfbf;
  white-space: pre-wrap;
  word-wrap: break-word;
  outline: none;
  opacity: 1
}

.ant-mentions-wrapper .DraftEditor-editorContainer .public-DraftEditor-content {
  height: auto;
  padding: 5px 11px
}

.ant-mentions-dropdown {
  min-width: 120px;
  max-height: 250px;
  margin: 1.5em 0 0;
  overflow-x: hidden;
  overflow-y: auto
}

.ant-mentions-dropdown-placement-top {
  margin-top: -.1em
}

.ant-mentions-dropdown-notfound.ant-mentions-dropdown-item {
  color: rgba(0, 0, 0, .25)
}

.ant-mentions-dropdown-notfound.ant-mentions-dropdown-item .anticon-loading {
  display: block;
  color: #03a9f4;
  text-align: center
}

.ant-mentions-dropdown-item {
  position: relative;
  display: block;
  padding: 5px 12px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  line-height: 22px;
  white-space: nowrap;
  text-overflow: ellipsis;
  cursor: pointer;
  -webkit-transition: background .3s;
  transition: background .3s
}

.ant-mentions-dropdown-item-active,
.ant-mentions-dropdown-item.focus,
.ant-mentions-dropdown-item:hover {
  background-color: #e8f8ff
}

.ant-mentions-dropdown-item-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-mentions-dropdown-item-disabled:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #fff;
  cursor: not-allowed
}

.ant-mentions-dropdown-item-selected,
.ant-mentions-dropdown-item-selected:hover {
  color: rgba(0, 0, 0, .65);
  font-weight: 700;
  background-color: #f5f5f5
}

.ant-mentions-dropdown-item-divider {
  height: 1px;
  margin: 1px 0;
  overflow: hidden;
  line-height: 0;
  background-color: #e8e8e8
}

.ant-mentions {
  box-sizing: border-box;
  margin: 0;
  font-variant: tabular-nums;
  list-style: none;
  font-feature-settings: "tnum";
  width: 100%;
  height: 32px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  background-color: #fff;
  background-image: none;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s;
  position: relative;
  display: inline-block;
  height: auto;
  padding: 0;
  overflow: hidden;
  line-height: 1.5;
  white-space: pre-wrap;
  vertical-align: bottom
}

.ant-mentions::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-mentions:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-mentions::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-mentions:placeholder-shown {
  text-overflow: ellipsis
}

.ant-mentions:focus,
.ant-mentions:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-mentions:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-mentions-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-mentions[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-mentions {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-mentions-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-mentions-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-mentions-disabled>textarea {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-mentions-disabled>textarea:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-mentions-focused {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-mentions-measure,
.ant-mentions>textarea {
  min-height: 30px;
  margin: 0;
  padding: 4px 11px;
  overflow: inherit;
  overflow-x: hidden;
  overflow-y: auto;
  font-weight: inherit;
  font-size: inherit;
  font-family: inherit;
  font-style: inherit;
  font-variant: inherit;
  font-size-adjust: inherit;
  font-stretch: inherit;
  line-height: inherit;
  direction: inherit;
  letter-spacing: inherit;
  white-space: inherit;
  text-align: inherit;
  vertical-align: top;
  word-wrap: break-word;
  word-break: inherit;
  -moz-tab-size: inherit;
  -o-tab-size: inherit;
  tab-size: inherit
}

.ant-mentions>textarea {
  width: 100%;
  border: none;
  outline: none;
  resize: none
}

.ant-mentions>textarea::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-mentions>textarea:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-mentions>textarea::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-mentions>textarea:placeholder-shown {
  text-overflow: ellipsis
}

.ant-mentions>textarea:-moz-read-only {
  cursor: default
}

.ant-mentions>textarea:read-only {
  cursor: default
}

.ant-mentions-measure {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: -1;
  color: transparent;
  pointer-events: none
}

.ant-mentions-measure>span {
  display: inline-block;
  min-height: 1em
}

.ant-mentions-dropdown {
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  top: -9999px;
  left: -9999px;
  z-index: 1050;
  box-sizing: border-box;
  font-size: 14px;
  font-variant: normal;
  background-color: #fff;
  border-radius: 4px;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-mentions-dropdown-hidden {
  display: none
}

.ant-mentions-dropdown-menu {
  max-height: 250px;
  margin-bottom: 0;
  padding-left: 0;
  overflow: auto;
  list-style: none;
  outline: none
}

.ant-mentions-dropdown-menu-item {
  position: relative;
  display: block;
  min-width: 100px;
  padding: 5px 12px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  line-height: 22px;
  white-space: nowrap;
  text-overflow: ellipsis;
  cursor: pointer;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-mentions-dropdown-menu-item:hover {
  background-color: #e8f8ff
}

.ant-mentions-dropdown-menu-item:first-child {
  border-radius: 4px 4px 0 0
}

.ant-mentions-dropdown-menu-item:last-child {
  border-radius: 0 0 4px 4px
}

.ant-mentions-dropdown-menu-item-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-mentions-dropdown-menu-item-disabled:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #fff;
  cursor: not-allowed
}

.ant-mentions-dropdown-menu-item-selected {
  color: rgba(0, 0, 0, .65);
  font-weight: 600;
  background-color: #fafafa
}

.ant-mentions-dropdown-menu-item-active {
  background-color: #e8f8ff
}

.ant-menu {
  box-sizing: border-box;
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  font-feature-settings: "tnum";
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  line-height: 0;
  list-style: none;
  background: #fff;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15);
  -webkit-transition: background .3s, width .2s;
  transition: background .3s, width .2s;
  zoom: 1
}

.ant-menu:after,
.ant-menu:before {
  display: table;
  content: ""
}

.ant-menu:after {
  clear: both
}

.ant-menu ol,
.ant-menu ul {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-menu-hidden {
  display: none
}

.ant-menu-item-group-title {
  padding: 8px 16px;
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 1.5;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-menu-submenu,
.ant-menu-submenu-inline {
  -webkit-transition: border-color .3s cubic-bezier(.645, .045, .355, 1), background .3s cubic-bezier(.645, .045, .355, 1), padding .15s cubic-bezier(.645, .045, .355, 1);
  transition: border-color .3s cubic-bezier(.645, .045, .355, 1), background .3s cubic-bezier(.645, .045, .355, 1), padding .15s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-submenu-selected {
  color: #03a9f4
}

.ant-menu-item:active,
.ant-menu-submenu-title:active {
  background: #e8f8ff
}

.ant-menu-submenu .ant-menu-sub {
  cursor: auto;
  -webkit-transition: background .3s cubic-bezier(.645, .045, .355, 1), padding .3s cubic-bezier(.645, .045, .355, 1);
  transition: background .3s cubic-bezier(.645, .045, .355, 1), padding .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-item>a {
  display: block;
  color: rgba(0, 0, 0, .65)
}

.ant-menu-item>a:hover {
  color: #03a9f4
}

.ant-menu-item>a:before {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: transparent;
  content: ""
}

.ant-menu-item-divider {
  height: 1px;
  overflow: hidden;
  line-height: 0;
  background-color: #e8e8e8
}

.ant-menu-item-active,
.ant-menu-item:hover,
.ant-menu-submenu-active,
.ant-menu-submenu-title:hover,
.ant-menu:not(.ant-menu-inline) .ant-menu-submenu-open {
  color: #03a9f4
}

.ant-menu-horizontal .ant-menu-item,
.ant-menu-horizontal .ant-menu-submenu {
  margin-top: -1px
}

.ant-menu-horizontal>.ant-menu-item-active,
.ant-menu-horizontal>.ant-menu-item:hover,
.ant-menu-horizontal>.ant-menu-submenu .ant-menu-submenu-title:hover {
  background-color: transparent
}

.ant-menu-item-selected,
.ant-menu-item-selected>a,
.ant-menu-item-selected>a:hover {
  color: #03a9f4
}

.ant-menu:not(.ant-menu-horizontal) .ant-menu-item-selected {
  background-color: #e8f8ff
}

.ant-menu-inline,
.ant-menu-vertical,
.ant-menu-vertical-left {
  border-right: 1px solid #e8e8e8
}

.ant-menu-vertical-right {
  border-left: 1px solid #e8e8e8
}

.ant-menu-vertical-left.ant-menu-sub,
.ant-menu-vertical-right.ant-menu-sub,
.ant-menu-vertical.ant-menu-sub {
  min-width: 160px;
  padding: 0;
  border-right: 0;
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0
}

.ant-menu-vertical-left.ant-menu-sub .ant-menu-item,
.ant-menu-vertical-right.ant-menu-sub .ant-menu-item,
.ant-menu-vertical.ant-menu-sub .ant-menu-item {
  left: 0;
  margin-left: 0;
  border-right: 0
}

.ant-menu-vertical-left.ant-menu-sub .ant-menu-item:after,
.ant-menu-vertical-right.ant-menu-sub .ant-menu-item:after,
.ant-menu-vertical.ant-menu-sub .ant-menu-item:after {
  border-right: 0
}

.ant-menu-vertical-left.ant-menu-sub>.ant-menu-item,
.ant-menu-vertical-left.ant-menu-sub>.ant-menu-submenu,
.ant-menu-vertical-right.ant-menu-sub>.ant-menu-item,
.ant-menu-vertical-right.ant-menu-sub>.ant-menu-submenu,
.ant-menu-vertical.ant-menu-sub>.ant-menu-item,
.ant-menu-vertical.ant-menu-sub>.ant-menu-submenu {
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0
}

.ant-menu-horizontal.ant-menu-sub {
  min-width: 114px
}

.ant-menu-item,
.ant-menu-submenu-title {
  position: relative;
  display: block;
  margin: 0;
  padding: 0 20px;
  white-space: nowrap;
  cursor: pointer;
  -webkit-transition: color .3s cubic-bezier(.645, .045, .355, 1), border-color .3s cubic-bezier(.645, .045, .355, 1), background .3s cubic-bezier(.645, .045, .355, 1), padding .15s cubic-bezier(.645, .045, .355, 1);
  transition: color .3s cubic-bezier(.645, .045, .355, 1), border-color .3s cubic-bezier(.645, .045, .355, 1), background .3s cubic-bezier(.645, .045, .355, 1), padding .15s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-item .anticon,
.ant-menu-submenu-title .anticon {
  min-width: 14px;
  margin-right: 10px;
  font-size: 14px;
  -webkit-transition: font-size .15s cubic-bezier(.215, .61, .355, 1), margin .3s cubic-bezier(.645, .045, .355, 1);
  transition: font-size .15s cubic-bezier(.215, .61, .355, 1), margin .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-item .anticon+span,
.ant-menu-submenu-title .anticon+span {
  opacity: 1;
  -webkit-transition: opacity .3s cubic-bezier(.645, .045, .355, 1), width .3s cubic-bezier(.645, .045, .355, 1);
  transition: opacity .3s cubic-bezier(.645, .045, .355, 1), width .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu>.ant-menu-item-divider {
  height: 1px;
  margin: 1px 0;
  padding: 0;
  overflow: hidden;
  line-height: 0;
  background-color: #e8e8e8
}

.ant-menu-submenu-popup {
  position: absolute;
  z-index: 1050;
  background: #fff;
  border-radius: 4px
}

.ant-menu-submenu-popup .submenu-title-wrapper {
  padding-right: 20px
}

.ant-menu-submenu-popup:before {
  position: absolute;
  top: -7px;
  right: 0;
  bottom: 0;
  left: 0;
  opacity: .0001;
  content: " "
}

.ant-menu-submenu>.ant-menu {
  background-color: #fff;
  border-radius: 4px
}

.ant-menu-submenu>.ant-menu-submenu-title:after {
  -webkit-transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title .ant-menu-submenu-arrow,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title .ant-menu-submenu-arrow,
.ant-menu-submenu-vertical>.ant-menu-submenu-title .ant-menu-submenu-arrow {
  position: absolute;
  top: 50%;
  right: 16px;
  width: 10px;
  -webkit-transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical>.ant-menu-submenu-title .ant-menu-submenu-arrow:before {
  position: absolute;
  width: 6px;
  height: 1.5px;
  background: #fff;
  background: rgba(0, 0, 0, .65)\9;
  background-image: -webkit-gradient(linear, left top, right top, from(rgba(0, 0, 0, .65)), to(rgba(0, 0, 0, .65)));
  background-image: linear-gradient(90deg, rgba(0, 0, 0, .65), rgba(0, 0, 0, .65));
  background-image: none\9;
  border-radius: 2px;
  -webkit-transition: background .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: background .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: background .3s cubic-bezier(.645, .045, .355, 1), transform .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1);
  transition: background .3s cubic-bezier(.645, .045, .355, 1), transform .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  content: ""
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical>.ant-menu-submenu-title .ant-menu-submenu-arrow:before {
  -webkit-transform: rotate(45deg) translateY(-2px);
  transform: rotate(45deg) translateY(-2px)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical>.ant-menu-submenu-title .ant-menu-submenu-arrow:after {
  -webkit-transform: rotate(-45deg) translateY(2px);
  transform: rotate(-45deg) translateY(2px)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:after,
.ant-menu-submenu-inline>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-left>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical-right>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:before,
.ant-menu-submenu-vertical>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:after,
.ant-menu-submenu-vertical>.ant-menu-submenu-title:hover .ant-menu-submenu-arrow:before {
  background: -webkit-gradient(linear, left top, right top, from(#03a9f4), to(#03a9f4));
  background: linear-gradient(90deg, #03a9f4, #03a9f4)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:before {
  -webkit-transform: rotate(-45deg) translateX(2px);
  transform: rotate(-45deg) translateX(2px)
}

.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:after {
  -webkit-transform: rotate(45deg) translateX(-2px);
  transform: rotate(45deg) translateX(-2px)
}

.ant-menu-submenu-open.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow {
  -webkit-transform: translateY(-2px);
  transform: translateY(-2px)
}

.ant-menu-submenu-open.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:after {
  -webkit-transform: rotate(-45deg) translateX(-2px);
  transform: rotate(-45deg) translateX(-2px)
}

.ant-menu-submenu-open.ant-menu-submenu-inline>.ant-menu-submenu-title .ant-menu-submenu-arrow:before {
  -webkit-transform: rotate(45deg) translateX(2px);
  transform: rotate(45deg) translateX(2px)
}

.ant-menu-vertical-left .ant-menu-submenu-selected,
.ant-menu-vertical-left .ant-menu-submenu-selected>a,
.ant-menu-vertical-right .ant-menu-submenu-selected,
.ant-menu-vertical-right .ant-menu-submenu-selected>a,
.ant-menu-vertical .ant-menu-submenu-selected,
.ant-menu-vertical .ant-menu-submenu-selected>a {
  color: #03a9f4
}

.ant-menu-horizontal {
  line-height: 46px;
  white-space: nowrap;
  border: 0;
  border-bottom: 1px solid #e8e8e8;
  box-shadow: none
}

.ant-menu-horizontal>.ant-menu-item,
.ant-menu-horizontal>.ant-menu-submenu {
  position: relative;
  top: 1px;
  display: inline-block;
  vertical-align: bottom;
  border-bottom: 2px solid transparent
}

.ant-menu-horizontal>.ant-menu-item-active,
.ant-menu-horizontal>.ant-menu-item-open,
.ant-menu-horizontal>.ant-menu-item-selected,
.ant-menu-horizontal>.ant-menu-item:hover,
.ant-menu-horizontal>.ant-menu-submenu-active,
.ant-menu-horizontal>.ant-menu-submenu-open,
.ant-menu-horizontal>.ant-menu-submenu-selected,
.ant-menu-horizontal>.ant-menu-submenu:hover {
  color: #03a9f4;
  border-bottom: 2px solid #03a9f4
}

.ant-menu-horizontal>.ant-menu-item>a {
  display: block;
  color: rgba(0, 0, 0, .65)
}

.ant-menu-horizontal>.ant-menu-item>a:hover {
  color: #03a9f4
}

.ant-menu-horizontal>.ant-menu-item>a:before {
  bottom: -2px
}

.ant-menu-horizontal>.ant-menu-item-selected>a {
  color: #03a9f4
}

.ant-menu-horizontal:after {
  display: block;
  clear: both;
  height: 0;
  content: " "
}

.ant-menu-inline .ant-menu-item,
.ant-menu-vertical-left .ant-menu-item,
.ant-menu-vertical-right .ant-menu-item,
.ant-menu-vertical .ant-menu-item {
  position: relative
}

.ant-menu-inline .ant-menu-item:after,
.ant-menu-vertical-left .ant-menu-item:after,
.ant-menu-vertical-right .ant-menu-item:after,
.ant-menu-vertical .ant-menu-item:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  border-right: 3px solid #03a9f4;
  -webkit-transform: scaleY(.0001);
  transform: scaleY(.0001);
  opacity: 0;
  -webkit-transition: opacity .15s cubic-bezier(.215, .61, .355, 1), -webkit-transform .15s cubic-bezier(.215, .61, .355, 1);
  transition: opacity .15s cubic-bezier(.215, .61, .355, 1), -webkit-transform .15s cubic-bezier(.215, .61, .355, 1);
  transition: transform .15s cubic-bezier(.215, .61, .355, 1), opacity .15s cubic-bezier(.215, .61, .355, 1);
  transition: transform .15s cubic-bezier(.215, .61, .355, 1), opacity .15s cubic-bezier(.215, .61, .355, 1), -webkit-transform .15s cubic-bezier(.215, .61, .355, 1);
  content: ""
}

.ant-menu-inline .ant-menu-item,
.ant-menu-inline .ant-menu-submenu-title,
.ant-menu-vertical-left .ant-menu-item,
.ant-menu-vertical-left .ant-menu-submenu-title,
.ant-menu-vertical-right .ant-menu-item,
.ant-menu-vertical-right .ant-menu-submenu-title,
.ant-menu-vertical .ant-menu-item,
.ant-menu-vertical .ant-menu-submenu-title {
  height: 40px;
  margin-top: 4px;
  margin-bottom: 4px;
  padding: 0 16px;
  overflow: hidden;
  font-size: 14px;
  line-height: 40px;
  text-overflow: ellipsis
}

.ant-menu-inline .ant-menu-submenu,
.ant-menu-vertical-left .ant-menu-submenu,
.ant-menu-vertical-right .ant-menu-submenu,
.ant-menu-vertical .ant-menu-submenu {
  padding-bottom: .01px
}

.ant-menu-inline .ant-menu-item:not(:last-child),
.ant-menu-vertical-left .ant-menu-item:not(:last-child),
.ant-menu-vertical-right .ant-menu-item:not(:last-child),
.ant-menu-vertical .ant-menu-item:not(:last-child) {
  margin-bottom: 8px
}

.ant-menu-inline>.ant-menu-item,
.ant-menu-inline>.ant-menu-submenu>.ant-menu-submenu-title,
.ant-menu-vertical-left>.ant-menu-item,
.ant-menu-vertical-left>.ant-menu-submenu>.ant-menu-submenu-title,
.ant-menu-vertical-right>.ant-menu-item,
.ant-menu-vertical-right>.ant-menu-submenu>.ant-menu-submenu-title,
.ant-menu-vertical>.ant-menu-item,
.ant-menu-vertical>.ant-menu-submenu>.ant-menu-submenu-title {
  height: 40px;
  line-height: 40px
}

.ant-menu-inline {
  width: 100%
}

.ant-menu-inline .ant-menu-item-selected:after,
.ant-menu-inline .ant-menu-selected:after {
  -webkit-transform: scaleY(1);
  transform: scaleY(1);
  opacity: 1;
  -webkit-transition: opacity .15s cubic-bezier(.645, .045, .355, 1), -webkit-transform .15s cubic-bezier(.645, .045, .355, 1);
  transition: opacity .15s cubic-bezier(.645, .045, .355, 1), -webkit-transform .15s cubic-bezier(.645, .045, .355, 1);
  transition: transform .15s cubic-bezier(.645, .045, .355, 1), opacity .15s cubic-bezier(.645, .045, .355, 1);
  transition: transform .15s cubic-bezier(.645, .045, .355, 1), opacity .15s cubic-bezier(.645, .045, .355, 1), -webkit-transform .15s cubic-bezier(.645, .045, .355, 1)
}

.ant-menu-inline .ant-menu-item,
.ant-menu-inline .ant-menu-submenu-title {
  width: calc(100% + 1px)
}

.ant-menu-inline .ant-menu-submenu-title {
  padding-right: 34px
}

.ant-menu-inline-collapsed {
  width: 80px
}

.ant-menu-inline-collapsed>.ant-menu-item,
.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-item,
.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-submenu>.ant-menu-submenu-title,
.ant-menu-inline-collapsed>.ant-menu-submenu>.ant-menu-submenu-title {
  left: 0;
  padding: 0 32px !important;
  text-overflow: clip
}

.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-item .ant-menu-submenu-arrow,
.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-submenu>.ant-menu-submenu-title .ant-menu-submenu-arrow,
.ant-menu-inline-collapsed>.ant-menu-item .ant-menu-submenu-arrow,
.ant-menu-inline-collapsed>.ant-menu-submenu>.ant-menu-submenu-title .ant-menu-submenu-arrow {
  display: none
}

.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-item .anticon,
.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-submenu>.ant-menu-submenu-title .anticon,
.ant-menu-inline-collapsed>.ant-menu-item .anticon,
.ant-menu-inline-collapsed>.ant-menu-submenu>.ant-menu-submenu-title .anticon {
  margin: 0;
  font-size: 16px;
  line-height: 40px
}

.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-item .anticon+span,
.ant-menu-inline-collapsed>.ant-menu-item-group>.ant-menu-item-group-list>.ant-menu-submenu>.ant-menu-submenu-title .anticon+span,
.ant-menu-inline-collapsed>.ant-menu-item .anticon+span,
.ant-menu-inline-collapsed>.ant-menu-submenu>.ant-menu-submenu-title .anticon+span {
  display: inline-block;
  max-width: 0;
  opacity: 0
}

.ant-menu-inline-collapsed-tooltip {
  pointer-events: none
}

.ant-menu-inline-collapsed-tooltip .anticon {
  display: none
}

.ant-menu-inline-collapsed-tooltip a {
  color: hsla(0, 0%, 100%, .85)
}

.ant-menu-inline-collapsed .ant-menu-item-group-title {
  padding-right: 4px;
  padding-left: 4px;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-menu-item-group-list {
  margin: 0;
  padding: 0
}

.ant-menu-item-group-list .ant-menu-item,
.ant-menu-item-group-list .ant-menu-submenu-title {
  padding: 0 16px 0 28px
}

.ant-menu-root.ant-menu-inline,
.ant-menu-root.ant-menu-vertical,
.ant-menu-root.ant-menu-vertical-left,
.ant-menu-root.ant-menu-vertical-right {
  box-shadow: none
}

.ant-menu-sub.ant-menu-inline {
  padding: 0;
  border: 0;
  border-radius: 0;
  box-shadow: none
}

.ant-menu-sub.ant-menu-inline>.ant-menu-item,
.ant-menu-sub.ant-menu-inline>.ant-menu-submenu>.ant-menu-submenu-title {
  height: 40px;
  line-height: 40px;
  list-style-position: inside;
  list-style-type: disc
}

.ant-menu-sub.ant-menu-inline .ant-menu-item-group-title {
  padding-left: 32px
}

.ant-menu-item-disabled,
.ant-menu-submenu-disabled {
  color: rgba(0, 0, 0, .25) !important;
  background: none;
  border-color: transparent !important;
  cursor: not-allowed
}

.ant-menu-item-disabled>a,
.ant-menu-submenu-disabled>a {
  color: rgba(0, 0, 0, .25) !important;
  pointer-events: none
}

.ant-menu-item-disabled>.ant-menu-submenu-title,
.ant-menu-submenu-disabled>.ant-menu-submenu-title {
  color: rgba(0, 0, 0, .25) !important;
  cursor: not-allowed
}

.ant-menu-item-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-item-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-submenu-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-submenu-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before {
  background: rgba(0, 0, 0, .25) !important
}

.ant-menu-dark,
.ant-menu-dark .ant-menu-sub {
  color: hsla(0, 0%, 100%, .65);
  background: #fff
}

.ant-menu-dark .ant-menu-sub .ant-menu-submenu-title .ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-title .ant-menu-submenu-arrow {
  opacity: .45;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-menu-dark .ant-menu-sub .ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-sub .ant-menu-submenu-title .ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-title .ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-title .ant-menu-submenu-arrow:before {
  background: #fff
}

.ant-menu-dark.ant-menu-submenu-popup {
  background: transparent
}

.ant-menu-dark .ant-menu-inline.ant-menu-sub {
  background: #000c17;
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, .45)
}

.ant-menu-dark.ant-menu-horizontal {
  border-bottom: 0
}

.ant-menu-dark.ant-menu-horizontal>.ant-menu-item,
.ant-menu-dark.ant-menu-horizontal>.ant-menu-submenu {
  top: 0;
  margin-top: 0;
  border-color: #fff;
  border-bottom: 0
}

.ant-menu-dark.ant-menu-horizontal>.ant-menu-item>a:before {
  bottom: 0
}

.ant-menu-dark .ant-menu-item,
.ant-menu-dark .ant-menu-item-group-title,
.ant-menu-dark .ant-menu-item>a {
  color: hsla(0, 0%, 100%, .65)
}

.ant-menu-dark.ant-menu-inline,
.ant-menu-dark.ant-menu-vertical,
.ant-menu-dark.ant-menu-vertical-left,
.ant-menu-dark.ant-menu-vertical-right {
  border-right: 0
}

.ant-menu-dark.ant-menu-inline .ant-menu-item,
.ant-menu-dark.ant-menu-vertical-left .ant-menu-item,
.ant-menu-dark.ant-menu-vertical-right .ant-menu-item,
.ant-menu-dark.ant-menu-vertical .ant-menu-item {
  left: 0;
  margin-left: 0;
  border-right: 0
}

.ant-menu-dark.ant-menu-inline .ant-menu-item:after,
.ant-menu-dark.ant-menu-vertical-left .ant-menu-item:after,
.ant-menu-dark.ant-menu-vertical-right .ant-menu-item:after,
.ant-menu-dark.ant-menu-vertical .ant-menu-item:after {
  border-right: 0
}

.ant-menu-dark.ant-menu-inline .ant-menu-item,
.ant-menu-dark.ant-menu-inline .ant-menu-submenu-title {
  width: 100%
}

.ant-menu-dark .ant-menu-item-active,
.ant-menu-dark .ant-menu-item:hover,
.ant-menu-dark .ant-menu-submenu-active,
.ant-menu-dark .ant-menu-submenu-open,
.ant-menu-dark .ant-menu-submenu-selected,
.ant-menu-dark .ant-menu-submenu-title:hover {
  color: #fff;
  background-color: transparent
}

.ant-menu-dark .ant-menu-item-active>a,
.ant-menu-dark .ant-menu-item:hover>a,
.ant-menu-dark .ant-menu-submenu-active>a,
.ant-menu-dark .ant-menu-submenu-open>a,
.ant-menu-dark .ant-menu-submenu-selected>a,
.ant-menu-dark .ant-menu-submenu-title:hover>a {
  color: #fff
}

.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow {
  opacity: 1
}

.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-item-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-item:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-active>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-open>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-selected>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title:hover>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-title:hover>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before {
  background: #fff
}

.ant-menu-dark .ant-menu-item:hover {
  background-color: transparent
}

.ant-menu-dark .ant-menu-item-selected {
  color: #fff;
  border-right: 0
}

.ant-menu-dark .ant-menu-item-selected:after {
  border-right: 0
}

.ant-menu-dark .ant-menu-item-selected .anticon,
.ant-menu-dark .ant-menu-item-selected .anticon+span,
.ant-menu-dark .ant-menu-item-selected>a,
.ant-menu-dark .ant-menu-item-selected>a:hover {
  color: #fff
}

.ant-menu-submenu-popup.ant-menu-dark .ant-menu-item-selected,
.ant-menu.ant-menu-dark .ant-menu-item-selected {
  background-color: #03a9f4
}

.ant-menu-dark .ant-menu-item-disabled,
.ant-menu-dark .ant-menu-item-disabled>a,
.ant-menu-dark .ant-menu-submenu-disabled,
.ant-menu-dark .ant-menu-submenu-disabled>a {
  color: hsla(0, 0%, 100%, .35) !important;
  opacity: .8
}

.ant-menu-dark .ant-menu-item-disabled>.ant-menu-submenu-title,
.ant-menu-dark .ant-menu-submenu-disabled>.ant-menu-submenu-title {
  color: hsla(0, 0%, 100%, .35) !important
}

.ant-menu-dark .ant-menu-item-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-item-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before,
.ant-menu-dark .ant-menu-submenu-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:after,
.ant-menu-dark .ant-menu-submenu-disabled>.ant-menu-submenu-title>.ant-menu-submenu-arrow:before {
  background: hsla(0, 0%, 100%, .35) !important
}

.ant-message {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: fixed;
  top: 16px;
  left: 0;
  z-index: 1010;
  width: 100%;
  pointer-events: none
}

.ant-message-notice {
  padding: 8px;
  text-align: center
}

.ant-message-notice:first-child {
  margin-top: -8px
}

.ant-message-notice-content {
  display: inline-block;
  padding: 10px 16px;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, .15);
  pointer-events: all
}

.ant-message-success .anticon {
  color: #52c41a
}

.ant-message-error .anticon {
  color: #f5222d
}

.ant-message-warning .anticon {
  color: #faad14
}

.ant-message-info .anticon,
.ant-message-loading .anticon {
  color: #1890ff
}

.ant-message .anticon {
  position: relative;
  top: 1px;
  margin-right: 8px;
  font-size: 16px
}

.ant-message-notice.move-up-leave.move-up-leave-active {
  overflow: hidden;
  -webkit-animation-name: MessageMoveOut;
  animation-name: MessageMoveOut;
  -webkit-animation-duration: .3s;
  animation-duration: .3s
}

@-webkit-keyframes MessageMoveOut {
  0% {
    max-height: 150px;
    padding: 8px;
    opacity: 1
  }

  to {
    max-height: 0;
    padding: 0;
    opacity: 0
  }
}

@keyframes MessageMoveOut {
  0% {
    max-height: 150px;
    padding: 8px;
    opacity: 1
  }

  to {
    max-height: 0;
    padding: 0;
    opacity: 0
  }
}

.ant-modal {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  top: 100px;
  width: auto;
  margin: 0 auto;
  padding: 0 0 24px;
  pointer-events: none
}

.ant-modal-wrap {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1000;
  overflow: auto;
  outline: 0;
  -webkit-overflow-scrolling: touch
}

.ant-modal-title {
  margin: 0;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;
  word-wrap: break-word
}

.ant-modal-content {
  position: relative;
  background-color: #fff;
  background-clip: padding-box;
  border: 0;
  border-radius: 4px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, .15);
  pointer-events: auto
}

.ant-modal-close {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 10;
  padding: 0;
  color: rgba(0, 0, 0, .45);
  font-weight: 700;
  line-height: 1;
  text-decoration: none;
  background: transparent;
  border: 0;
  outline: 0;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-modal-close-x {
  display: block;
  width: 56px;
  height: 56px;
  font-size: 16px;
  font-style: normal;
  line-height: 56px;
  text-align: center;
  text-transform: none;
  text-rendering: auto
}

.ant-modal-close:focus,
.ant-modal-close:hover {
  color: rgba(0, 0, 0, .75);
  text-decoration: none
}

.ant-modal-header {
  padding: 16px 24px;
  color: rgba(0, 0, 0, .65);
  background: #fff;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 4px 4px 0 0
}

.ant-modal-body {
  padding: 24px;
  font-size: 14px;
  line-height: 1.5;
  word-wrap: break-word
}

.ant-modal-footer {
  padding: 10px 16px;
  text-align: right;
  background: transparent;
  border-top: 1px solid #e8e8e8;
  border-radius: 0 0 4px 4px
}

.ant-modal-footer button+button {
  margin-bottom: 0;
  margin-left: 8px
}

.ant-modal.zoom-appear,
.ant-modal.zoom-enter {
  -webkit-transform: none;
  transform: none;
  opacity: 0;
  -webkit-animation-duration: .3s;
  animation-duration: .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-modal-mask {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1000;
  height: 100%;
  background-color: rgba(0, 0, 0, .45);
  filter: alpha(opacity=50)
}

.ant-modal-mask-hidden {
  display: none
}

.ant-modal-open {
  overflow: hidden
}

.ant-modal-centered {
  text-align: center
}

.ant-modal-centered:before {
  display: inline-block;
  width: 0;
  height: 100%;
  vertical-align: middle;
  content: ""
}

.ant-modal-centered .ant-modal {
  top: 0;
  display: inline-block;
  text-align: left;
  vertical-align: middle
}

@media (max-width:767px) {
  .ant-modal {
    max-width: calc(100vw - 16px);
    margin: 8px auto
  }

  .ant-modal-centered .ant-modal {
    flex: 1 1
  }
}

.ant-modal-confirm .ant-modal-close,
.ant-modal-confirm .ant-modal-header {
  display: none
}

.ant-modal-confirm .ant-modal-body {
  padding: 32px 32px 24px
}

.ant-modal-confirm-body-wrapper {
  zoom: 1
}

.ant-modal-confirm-body-wrapper:after,
.ant-modal-confirm-body-wrapper:before {
  display: table;
  content: ""
}

.ant-modal-confirm-body-wrapper:after {
  clear: both
}

.ant-modal-confirm-body .ant-modal-confirm-title {
  display: block;
  overflow: hidden;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  font-size: 16px;
  line-height: 1.4
}

.ant-modal-confirm-body .ant-modal-confirm-content {
  margin-top: 8px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px
}

.ant-modal-confirm-body>.anticon {
  float: left;
  margin-right: 16px;
  font-size: 22px
}

.ant-modal-confirm-body>.anticon+.ant-modal-confirm-title+.ant-modal-confirm-content {
  margin-left: 38px
}

.ant-modal-confirm .ant-modal-confirm-btns {
  float: right;
  margin-top: 24px
}

.ant-modal-confirm .ant-modal-confirm-btns button+button {
  margin-bottom: 0;
  margin-left: 8px
}

.ant-modal-confirm-error .ant-modal-confirm-body>.anticon {
  color: #f5222d
}

.ant-modal-confirm-confirm .ant-modal-confirm-body>.anticon,
.ant-modal-confirm-warning .ant-modal-confirm-body>.anticon {
  color: #faad14
}

.ant-modal-confirm-info .ant-modal-confirm-body>.anticon {
  color: #1890ff
}

.ant-modal-confirm-success .ant-modal-confirm-body>.anticon {
  color: #52c41a
}

.ant-notification {
  box-sizing: border-box;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: fixed;
  z-index: 1010;
  width: 384px;
  max-width: calc(100vw - 32px);
  margin: 0 24px 0 0
}

.ant-notification-bottomLeft,
.ant-notification-topLeft {
  margin-right: 0;
  margin-left: 24px
}

.ant-notification-bottomLeft .ant-notification-fade-appear.ant-notification-fade-appear-active,
.ant-notification-bottomLeft .ant-notification-fade-enter.ant-notification-fade-enter-active,
.ant-notification-topLeft .ant-notification-fade-appear.ant-notification-fade-appear-active,
.ant-notification-topLeft .ant-notification-fade-enter.ant-notification-fade-enter-active {
  -webkit-animation-name: NotificationLeftFadeIn;
  animation-name: NotificationLeftFadeIn
}

.ant-notification-close-icon {
  font-size: 14px;
  cursor: pointer
}

.ant-notification-notice {
  position: relative;
  margin-bottom: 16px;
  padding: 16px 24px;
  overflow: hidden;
  line-height: 1.5;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, .15)
}

.ant-notification-notice-message {
  display: inline-block;
  margin-bottom: 8px;
  color: rgba(0, 0, 0, .85);
  font-size: 16px;
  line-height: 24px
}

.ant-notification-notice-message-single-line-auto-margin {
  display: block;
  width: calc(264px - 100%);
  max-width: 4px;
  background-color: transparent;
  pointer-events: none
}

.ant-notification-notice-message-single-line-auto-margin:before {
  display: block;
  content: ""
}

.ant-notification-notice-description {
  font-size: 14px
}

.ant-notification-notice-closable .ant-notification-notice-message {
  padding-right: 24px
}

.ant-notification-notice-with-icon .ant-notification-notice-message {
  margin-bottom: 4px;
  margin-left: 48px;
  font-size: 16px
}

.ant-notification-notice-with-icon .ant-notification-notice-description {
  margin-left: 48px;
  font-size: 14px
}

.ant-notification-notice-icon {
  position: absolute;
  margin-left: 4px;
  font-size: 24px;
  line-height: 24px
}

.anticon.ant-notification-notice-icon-success {
  color: #52c41a
}

.anticon.ant-notification-notice-icon-info {
  color: #1890ff
}

.anticon.ant-notification-notice-icon-warning {
  color: #faad14
}

.anticon.ant-notification-notice-icon-error {
  color: #f5222d
}

.ant-notification-notice-close {
  position: absolute;
  top: 16px;
  right: 22px;
  color: rgba(0, 0, 0, .45);
  outline: none
}

.ant-notification-notice-close:hover {
  color: rgba(0, 0, 0, .67)
}

.ant-notification-notice-btn {
  float: right;
  margin-top: 16px
}

.ant-notification .notification-fade-effect {
  -webkit-animation-duration: .24s;
  animation-duration: .24s;
  -webkit-animation-timing-function: cubic-bezier(.645, .045, .355, 1);
  animation-timing-function: cubic-bezier(.645, .045, .355, 1);
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both
}

.ant-notification-fade-appear,
.ant-notification-fade-enter {
  opacity: 0;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.ant-notification-fade-appear,
.ant-notification-fade-enter,
.ant-notification-fade-leave {
  -webkit-animation-duration: .24s;
  animation-duration: .24s;
  -webkit-animation-timing-function: cubic-bezier(.645, .045, .355, 1);
  animation-timing-function: cubic-bezier(.645, .045, .355, 1);
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both
}

.ant-notification-fade-leave {
  -webkit-animation-duration: .2s;
  animation-duration: .2s;
  -webkit-animation-play-state: paused;
  animation-play-state: paused
}

.ant-notification-fade-appear.ant-notification-fade-appear-active,
.ant-notification-fade-enter.ant-notification-fade-enter-active {
  -webkit-animation-name: NotificationFadeIn;
  animation-name: NotificationFadeIn;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

.ant-notification-fade-leave.ant-notification-fade-leave-active {
  -webkit-animation-name: NotificationFadeOut;
  animation-name: NotificationFadeOut;
  -webkit-animation-play-state: running;
  animation-play-state: running
}

@-webkit-keyframes NotificationFadeIn {
  0% {
    left: 384px;
    opacity: 0
  }

  to {
    left: 0;
    opacity: 1
  }
}

@keyframes NotificationFadeIn {
  0% {
    left: 384px;
    opacity: 0
  }

  to {
    left: 0;
    opacity: 1
  }
}

@-webkit-keyframes NotificationLeftFadeIn {
  0% {
    right: 384px;
    opacity: 0
  }

  to {
    right: 0;
    opacity: 1
  }
}

@keyframes NotificationLeftFadeIn {
  0% {
    right: 384px;
    opacity: 0
  }

  to {
    right: 0;
    opacity: 1
  }
}

@-webkit-keyframes NotificationFadeOut {
  0% {
    max-height: 150px;
    margin-bottom: 16px;
    padding-top: 16px 24px;
    padding-bottom: 16px 24px;
    opacity: 1
  }

  to {
    max-height: 0;
    margin-bottom: 0;
    padding-top: 0;
    padding-bottom: 0;
    opacity: 0
  }
}

@keyframes NotificationFadeOut {
  0% {
    max-height: 150px;
    margin-bottom: 16px;
    padding-top: 16px 24px;
    padding-bottom: 16px 24px;
    opacity: 1
  }

  to {
    max-height: 0;
    margin-bottom: 0;
    padding-top: 0;
    padding-bottom: 0;
    opacity: 0
  }
}

.ant-page-header {
  box-sizing: border-box;
  margin: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  padding: 16px 24px;
  background-color: #fff
}

.ant-page-header-ghost {
  background-color: inherit
}

.ant-page-header.has-breadcrumb {
  padding-top: 12px
}

.ant-page-header.has-footer {
  padding-bottom: 0
}

.ant-page-header-back {
  float: left;
  margin: 8px 16px 8px 0;
  font-size: 16px;
  line-height: 1
}

.ant-page-header-back-button {
  color: #03a9f4;
  text-decoration: none;
  outline: none;
  -webkit-transition: color .3s;
  transition: color .3s;
  color: #000;
  cursor: pointer
}

.ant-page-header-back-button:focus,
.ant-page-header-back-button:hover {
  color: #2bc3ff
}

.ant-page-header-back-button:active {
  color: #0086cf
}

.ant-page-header .ant-divider-vertical {
  height: 14px;
  margin: 0 12px;
  vertical-align: middle
}

.ant-breadcrumb+.ant-page-header-heading {
  margin-top: 8px
}

.ant-page-header-heading {
  width: 100%;
  overflow: hidden
}

.ant-page-header-heading-title {
  display: block;
  float: left;
  margin-bottom: 0;
  padding-right: 12px;
  color: rgba(0, 0, 0, .85);
  font-weight: 600;
  font-size: 20px;
  line-height: 32px
}

.ant-page-header-heading .ant-avatar {
  float: left;
  margin-right: 12px
}

.ant-page-header-heading-sub-title {
  float: left;
  margin: 5px 12px 5px 0;
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 22px
}

.ant-page-header-heading-tags {
  float: left;
  margin: 4px 0
}

.ant-page-header-heading-extra {
  float: right
}

.ant-page-header-heading-extra>* {
  margin-left: 8px
}

.ant-page-header-heading-extra>:first-child {
  margin-left: 0
}

.ant-page-header-content {
  padding-top: 12px;
  overflow: hidden
}

.ant-page-header-footer {
  margin-top: 16px
}

.ant-page-header-footer .ant-tabs-bar {
  margin-bottom: 1px;
  border-bottom: 0
}

.ant-page-header-footer .ant-tabs-bar .ant-tabs-nav .ant-tabs-tab {
  padding: 8px;
  font-size: 16px
}

@media (max-width:576px) {
  .ant-page-header-heading-extra {
    display: block;
    float: unset;
    width: 100%;
    padding-top: 12px;
    overflow: hidden
  }
}

.ant-pagination {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  font-feature-settings: "tnum"
}

.ant-pagination,
.ant-pagination ol,
.ant-pagination ul {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-pagination:after {
  display: block;
  clear: both;
  height: 0;
  overflow: hidden;
  visibility: hidden;
  content: " "
}

.ant-pagination-item,
.ant-pagination-total-text {
  display: inline-block;
  height: 32px;
  margin-right: 8px;
  line-height: 30px;
  vertical-align: middle
}

.ant-pagination-item {
  min-width: 32px;
  font-family: Arial;
  text-align: center;
  list-style: none;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  outline: 0;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-pagination-item a {
  display: block;
  padding: 0 6px;
  color: rgba(0, 0, 0, .65);
  -webkit-transition: none;
  transition: none
}

.ant-pagination-item a:hover {
  text-decoration: none
}

.ant-pagination-item:focus,
.ant-pagination-item:hover {
  border-color: #03a9f4;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-pagination-item:focus a,
.ant-pagination-item:hover a {
  color: #03a9f4
}

.ant-pagination-item-active {
  font-weight: 500;
  background: #fff;
  border-color: #03a9f4
}

.ant-pagination-item-active a {
  color: #03a9f4
}

.ant-pagination-item-active:focus,
.ant-pagination-item-active:hover {
  border-color: #2bc3ff
}

.ant-pagination-item-active:focus a,
.ant-pagination-item-active:hover a {
  color: #2bc3ff
}

.ant-pagination-jump-next,
.ant-pagination-jump-prev {
  outline: 0
}

.ant-pagination-jump-next .ant-pagination-item-container,
.ant-pagination-jump-prev .ant-pagination-item-container {
  position: relative
}

.ant-pagination-jump-next .ant-pagination-item-container .ant-pagination-item-link-icon,
.ant-pagination-jump-prev .ant-pagination-item-container .ant-pagination-item-link-icon {
  display: inline-block;
  font-size: 12px;
  font-size: 12px\9;
  -webkit-transform: scale(1) rotate(0deg);
  transform: scale(1) rotate(0deg);
  color: #03a9f4;
  letter-spacing: -1px;
  opacity: 0;
  -webkit-transition: all .2s;
  transition: all .2s
}

:root .ant-pagination-jump-next .ant-pagination-item-container .ant-pagination-item-link-icon,
:root .ant-pagination-jump-prev .ant-pagination-item-container .ant-pagination-item-link-icon {
  font-size: 12px
}

.ant-pagination-jump-next .ant-pagination-item-container .ant-pagination-item-link-icon-svg,
.ant-pagination-jump-prev .ant-pagination-item-container .ant-pagination-item-link-icon-svg {
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.ant-pagination-jump-next .ant-pagination-item-container .ant-pagination-item-ellipsis,
.ant-pagination-jump-prev .ant-pagination-item-container .ant-pagination-item-ellipsis {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  display: block;
  margin: auto;
  color: rgba(0, 0, 0, .25);
  letter-spacing: 2px;
  text-align: center;
  text-indent: .13em;
  opacity: 1;
  -webkit-transition: all .2s;
  transition: all .2s
}

.ant-pagination-jump-next:focus .ant-pagination-item-link-icon,
.ant-pagination-jump-next:hover .ant-pagination-item-link-icon,
.ant-pagination-jump-prev:focus .ant-pagination-item-link-icon,
.ant-pagination-jump-prev:hover .ant-pagination-item-link-icon {
  opacity: 1
}

.ant-pagination-jump-next:focus .ant-pagination-item-ellipsis,
.ant-pagination-jump-next:hover .ant-pagination-item-ellipsis,
.ant-pagination-jump-prev:focus .ant-pagination-item-ellipsis,
.ant-pagination-jump-prev:hover .ant-pagination-item-ellipsis {
  opacity: 0
}

.ant-pagination-jump-next,
.ant-pagination-jump-prev,
.ant-pagination-prev {
  margin-right: 8px
}

.ant-pagination-jump-next,
.ant-pagination-jump-prev,
.ant-pagination-next,
.ant-pagination-prev {
  display: inline-block;
  min-width: 32px;
  height: 32px;
  color: rgba(0, 0, 0, .65);
  font-family: Arial;
  line-height: 32px;
  text-align: center;
  vertical-align: middle;
  list-style: none;
  border-radius: 4px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-pagination-next,
.ant-pagination-prev {
  outline: 0
}

.ant-pagination-next a,
.ant-pagination-prev a {
  color: rgba(0, 0, 0, .65);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-pagination-next:hover a,
.ant-pagination-prev:hover a {
  border-color: #2bc3ff
}

.ant-pagination-next .ant-pagination-item-link,
.ant-pagination-prev .ant-pagination-item-link {
  display: block;
  height: 100%;
  font-size: 12px;
  text-align: center;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  outline: none;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-pagination-next:focus .ant-pagination-item-link,
.ant-pagination-next:hover .ant-pagination-item-link,
.ant-pagination-prev:focus .ant-pagination-item-link,
.ant-pagination-prev:hover .ant-pagination-item-link {
  color: #03a9f4;
  border-color: #03a9f4
}

.ant-pagination-disabled,
.ant-pagination-disabled:focus,
.ant-pagination-disabled:hover {
  cursor: not-allowed
}

.ant-pagination-disabled .ant-pagination-item-link,
.ant-pagination-disabled:focus .ant-pagination-item-link,
.ant-pagination-disabled:focus a,
.ant-pagination-disabled:hover .ant-pagination-item-link,
.ant-pagination-disabled:hover a,
.ant-pagination-disabled a {
  color: rgba(0, 0, 0, .25);
  border-color: #d9d9d9;
  cursor: not-allowed
}

.ant-pagination-slash {
  margin: 0 10px 0 5px
}

.ant-pagination-options {
  display: inline-block;
  margin-left: 16px;
  vertical-align: middle
}

.ant-pagination-options-size-changer.ant-select {
  display: inline-block;
  width: auto;
  margin-right: 8px
}

.ant-pagination-options-quick-jumper {
  display: inline-block;
  height: 32px;
  line-height: 32px;
  vertical-align: top
}

.ant-pagination-options-quick-jumper input {
  position: relative;
  display: inline-block;
  width: 100%;
  height: 32px;
  padding: 4px 11px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  line-height: 1.5;
  background-color: #fff;
  background-image: none;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s;
  width: 50px;
  margin: 0 8px
}

.ant-pagination-options-quick-jumper input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-pagination-options-quick-jumper input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-pagination-options-quick-jumper input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-pagination-options-quick-jumper input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-pagination-options-quick-jumper input:focus,
.ant-pagination-options-quick-jumper input:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-pagination-options-quick-jumper input:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-pagination-options-quick-jumper input-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-pagination-options-quick-jumper input-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-pagination-options-quick-jumper input[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-pagination-options-quick-jumper input[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-pagination-options-quick-jumper input {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-pagination-options-quick-jumper input-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-pagination-options-quick-jumper input-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-pagination-simple .ant-pagination-next,
.ant-pagination-simple .ant-pagination-prev {
  height: 24px;
  line-height: 24px;
  vertical-align: top
}

.ant-pagination-simple .ant-pagination-next .ant-pagination-item-link,
.ant-pagination-simple .ant-pagination-prev .ant-pagination-item-link {
  height: 24px;
  border: 0
}

.ant-pagination-simple .ant-pagination-next .ant-pagination-item-link:after,
.ant-pagination-simple .ant-pagination-prev .ant-pagination-item-link:after {
  height: 24px;
  line-height: 24px
}

.ant-pagination-simple .ant-pagination-simple-pager {
  display: inline-block;
  height: 24px;
  margin-right: 8px
}

.ant-pagination-simple .ant-pagination-simple-pager input {
  box-sizing: border-box;
  height: 100%;
  margin-right: 8px;
  padding: 0 6px;
  text-align: center;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  outline: none;
  -webkit-transition: border-color .3s;
  transition: border-color .3s
}

.ant-pagination-simple .ant-pagination-simple-pager input:hover {
  border-color: #03a9f4
}

.ant-pagination.mini .ant-pagination-simple-pager,
.ant-pagination.mini .ant-pagination-total-text {
  height: 24px;
  line-height: 24px
}

.ant-pagination.mini .ant-pagination-item {
  min-width: 24px;
  height: 24px;
  margin: 0;
  line-height: 22px
}

.ant-pagination.mini .ant-pagination-item:not(.ant-pagination-item-active) {
  background: transparent;
  border-color: transparent
}

.ant-pagination.mini .ant-pagination-next,
.ant-pagination.mini .ant-pagination-prev {
  min-width: 24px;
  height: 24px;
  margin: 0;
  line-height: 24px
}

.ant-pagination.mini .ant-pagination-next .ant-pagination-item-link,
.ant-pagination.mini .ant-pagination-prev .ant-pagination-item-link {
  background: transparent;
  border-color: transparent
}

.ant-pagination.mini .ant-pagination-next .ant-pagination-item-link:after,
.ant-pagination.mini .ant-pagination-prev .ant-pagination-item-link:after {
  height: 24px;
  line-height: 24px
}

.ant-pagination.mini .ant-pagination-jump-next,
.ant-pagination.mini .ant-pagination-jump-prev {
  height: 24px;
  margin-right: 0;
  line-height: 24px
}

.ant-pagination.mini .ant-pagination-options {
  margin-left: 2px
}

.ant-pagination.mini .ant-pagination-options-quick-jumper {
  height: 24px;
  line-height: 24px
}

.ant-pagination.mini .ant-pagination-options-quick-jumper input {
  height: 24px;
  padding: 1px 7px;
  width: 44px
}

.ant-pagination.ant-pagination-disabled {
  cursor: not-allowed
}

.ant-pagination.ant-pagination-disabled .ant-pagination-item {
  background: #f5f5f5;
  border-color: #d9d9d9;
  cursor: not-allowed
}

.ant-pagination.ant-pagination-disabled .ant-pagination-item a {
  color: rgba(0, 0, 0, .25);
  background: transparent;
  border: none;
  cursor: not-allowed
}

.ant-pagination.ant-pagination-disabled .ant-pagination-item-active {
  background: #dbdbdb;
  border-color: transparent
}

.ant-pagination.ant-pagination-disabled .ant-pagination-item-active a {
  color: #fff
}

.ant-pagination.ant-pagination-disabled .ant-pagination-item-link,
.ant-pagination.ant-pagination-disabled .ant-pagination-item-link:focus,
.ant-pagination.ant-pagination-disabled .ant-pagination-item-link:hover {
  color: rgba(0, 0, 0, .45);
  background: #f5f5f5;
  border-color: #d9d9d9;
  cursor: not-allowed
}

.ant-pagination.ant-pagination-disabled .ant-pagination-jump-next:focus .ant-pagination-item-link-icon,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-next:hover .ant-pagination-item-link-icon,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-prev:focus .ant-pagination-item-link-icon,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-prev:hover .ant-pagination-item-link-icon {
  opacity: 0
}

.ant-pagination.ant-pagination-disabled .ant-pagination-jump-next:focus .ant-pagination-item-ellipsis,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-next:hover .ant-pagination-item-ellipsis,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-prev:focus .ant-pagination-item-ellipsis,
.ant-pagination.ant-pagination-disabled .ant-pagination-jump-prev:hover .ant-pagination-item-ellipsis {
  opacity: 1
}

@media only screen and (max-width:992px) {

  .ant-pagination-item-after-jump-prev,
  .ant-pagination-item-before-jump-next {
    display: none
  }
}

@media only screen and (max-width:576px) {
  .ant-pagination-options {
    display: none
  }
}

.ant-popover {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1030;
  font-weight: 400;
  white-space: normal;
  text-align: left;
  cursor: auto;
  -webkit-user-select: text;
  -moz-user-select: text;
  -ms-user-select: text;
  user-select: text
}

.ant-popover:after {
  position: absolute;
  background: hsla(0, 0%, 100%, .01);
  content: ""
}

.ant-popover-hidden {
  display: none
}

.ant-popover-placement-top,
.ant-popover-placement-topLeft,
.ant-popover-placement-topRight {
  padding-bottom: 10px
}

.ant-popover-placement-right,
.ant-popover-placement-rightBottom,
.ant-popover-placement-rightTop {
  padding-left: 10px
}

.ant-popover-placement-bottom,
.ant-popover-placement-bottomLeft,
.ant-popover-placement-bottomRight {
  padding-top: 10px
}

.ant-popover-placement-left,
.ant-popover-placement-leftBottom,
.ant-popover-placement-leftTop {
  padding-right: 10px
}

.ant-popover-inner {
  background-color: #fff;
  background-clip: padding-box;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15);
  box-shadow: 0 0 8px rgba(0, 0, 0, .15)\9
}

@media (-ms-high-contrast:none),
screen and (-ms-high-contrast:active) {
  .ant-popover-inner {
    box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
  }
}

.ant-popover-title {
  min-width: 177px;
  min-height: 32px;
  margin: 0;
  padding: 5px 16px 4px;
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  border-bottom: 1px solid #e8e8e8
}

.ant-popover-inner-content {
  padding: 12px 16px;
  color: rgba(0, 0, 0, .65)
}

.ant-popover-message {
  position: relative;
  padding: 4px 0 12px;
  color: rgba(0, 0, 0, .65);
  font-size: 14px
}

.ant-popover-message>.anticon {
  position: absolute;
  top: 8px;
  color: #faad14;
  font-size: 14px
}

.ant-popover-message-title {
  padding-left: 22px
}

.ant-popover-buttons {
  margin-bottom: 4px;
  text-align: right
}

.ant-popover-buttons button {
  margin-left: 8px
}

.ant-popover-arrow {
  position: absolute;
  display: block;
  width: 8.48528137px;
  height: 8.48528137px;
  background: transparent;
  border-style: solid;
  border-width: 4.24264069px;
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg)
}

.ant-popover-placement-top>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-topLeft>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-topRight>.ant-popover-content>.ant-popover-arrow {
  bottom: 6.2px;
  border-color: transparent #fff #fff transparent;
  box-shadow: 3px 3px 7px rgba(0, 0, 0, .07)
}

.ant-popover-placement-top>.ant-popover-content>.ant-popover-arrow {
  left: 50%;
  -webkit-transform: translateX(-50%) rotate(45deg);
  transform: translateX(-50%) rotate(45deg)
}

.ant-popover-placement-topLeft>.ant-popover-content>.ant-popover-arrow {
  left: 16px
}

.ant-popover-placement-topRight>.ant-popover-content>.ant-popover-arrow {
  right: 16px
}

.ant-popover-placement-right>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-rightBottom>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-rightTop>.ant-popover-content>.ant-popover-arrow {
  left: 6px;
  border-color: transparent transparent #fff #fff;
  box-shadow: -3px 3px 7px rgba(0, 0, 0, .07)
}

.ant-popover-placement-right>.ant-popover-content>.ant-popover-arrow {
  top: 50%;
  -webkit-transform: translateY(-50%) rotate(45deg);
  transform: translateY(-50%) rotate(45deg)
}

.ant-popover-placement-rightTop>.ant-popover-content>.ant-popover-arrow {
  top: 12px
}

.ant-popover-placement-rightBottom>.ant-popover-content>.ant-popover-arrow {
  bottom: 12px
}

.ant-popover-placement-bottom>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-bottomLeft>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-bottomRight>.ant-popover-content>.ant-popover-arrow {
  top: 6px;
  border-color: #fff transparent transparent #fff;
  box-shadow: -2px -2px 5px rgba(0, 0, 0, .06)
}

.ant-popover-placement-bottom>.ant-popover-content>.ant-popover-arrow {
  left: 50%;
  -webkit-transform: translateX(-50%) rotate(45deg);
  transform: translateX(-50%) rotate(45deg)
}

.ant-popover-placement-bottomLeft>.ant-popover-content>.ant-popover-arrow {
  left: 16px
}

.ant-popover-placement-bottomRight>.ant-popover-content>.ant-popover-arrow {
  right: 16px
}

.ant-popover-placement-left>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-leftBottom>.ant-popover-content>.ant-popover-arrow,
.ant-popover-placement-leftTop>.ant-popover-content>.ant-popover-arrow {
  right: 6px;
  border-color: #fff #fff transparent transparent;
  box-shadow: 3px -3px 7px rgba(0, 0, 0, .07)
}

.ant-popover-placement-left>.ant-popover-content>.ant-popover-arrow {
  top: 50%;
  -webkit-transform: translateY(-50%) rotate(45deg);
  transform: translateY(-50%) rotate(45deg)
}

.ant-popover-placement-leftTop>.ant-popover-content>.ant-popover-arrow {
  top: 12px
}

.ant-popover-placement-leftBottom>.ant-popover-content>.ant-popover-arrow {
  bottom: 12px
}

.ant-progress {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block
}

.ant-progress-line {
  position: relative;
  width: 100%;
  font-size: 14px
}

.ant-progress-small.ant-progress-line,
.ant-progress-small.ant-progress-line .ant-progress-text .anticon {
  font-size: 12px
}

.ant-progress-outer {
  display: inline-block;
  width: 100%;
  margin-right: 0;
  padding-right: 0
}

.ant-progress-show-info .ant-progress-outer {
  margin-right: calc(-2em - 8px);
  padding-right: calc(2em + 8px)
}

.ant-progress-inner {
  position: relative;
  display: inline-block;
  width: 100%;
  overflow: hidden;
  vertical-align: middle;
  background-color: #f5f5f5;
  border-radius: 100px
}

.ant-progress-circle-trail {
  stroke: #f5f5f5
}

.ant-progress-circle-path {
  -webkit-animation: ant-progress-appear .3s;
  animation: ant-progress-appear .3s
}

.ant-progress-inner:not(.ant-progress-circle-gradient) .ant-progress-circle-path {
  stroke: #1890ff
}

.ant-progress-bg,
.ant-progress-success-bg {
  position: relative;
  background-color: #1890ff;
  border-radius: 100px;
  -webkit-transition: all .4s cubic-bezier(.08, .82, .17, 1) 0s;
  transition: all .4s cubic-bezier(.08, .82, .17, 1) 0s
}

.ant-progress-success-bg {
  position: absolute;
  top: 0;
  left: 0;
  background-color: #52c41a
}

.ant-progress-text {
  display: inline-block;
  width: 2em;
  margin-left: 8px;
  color: rgba(0, 0, 0, .45);
  font-size: 1em;
  line-height: 1;
  white-space: nowrap;
  text-align: left;
  vertical-align: middle;
  word-break: normal
}

.ant-progress-text .anticon {
  font-size: 14px
}

.ant-progress-status-active .ant-progress-bg:before {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: #fff;
  border-radius: 10px;
  opacity: 0;
  -webkit-animation: ant-progress-active 2.4s cubic-bezier(.23, 1, .32, 1) infinite;
  animation: ant-progress-active 2.4s cubic-bezier(.23, 1, .32, 1) infinite;
  content: ""
}

.ant-progress-status-exception .ant-progress-bg {
  background-color: #f5222d
}

.ant-progress-status-exception .ant-progress-text {
  color: #f5222d
}

.ant-progress-status-exception .ant-progress-inner:not(.ant-progress-circle-gradient) .ant-progress-circle-path {
  stroke: #f5222d
}

.ant-progress-status-success .ant-progress-bg {
  background-color: #52c41a
}

.ant-progress-status-success .ant-progress-text {
  color: #52c41a
}

.ant-progress-status-success .ant-progress-inner:not(.ant-progress-circle-gradient) .ant-progress-circle-path {
  stroke: #52c41a
}

.ant-progress-circle .ant-progress-inner {
  position: relative;
  line-height: 1;
  background-color: transparent
}

.ant-progress-circle .ant-progress-text {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  line-height: 1;
  white-space: normal;
  text-align: center;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%)
}

.ant-progress-circle .ant-progress-text .anticon {
  font-size: 1.16666667em
}

.ant-progress-circle.ant-progress-status-exception .ant-progress-text {
  color: #f5222d
}

.ant-progress-circle.ant-progress-status-success .ant-progress-text {
  color: #52c41a
}

@-webkit-keyframes ant-progress-active {
  0% {
    width: 0;
    opacity: .1
  }

  20% {
    width: 0;
    opacity: .5
  }

  to {
    width: 100%;
    opacity: 0
  }
}

@keyframes ant-progress-active {
  0% {
    width: 0;
    opacity: .1
  }

  20% {
    width: 0;
    opacity: .5
  }

  to {
    width: 100%;
    opacity: 0
  }
}

.ant-radio-group {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  line-height: unset
}

.ant-radio-wrapper {
  margin: 0 8px 0 0
}

.ant-radio,
.ant-radio-wrapper {
  box-sizing: border-box;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  white-space: nowrap;
  cursor: pointer
}

.ant-radio {
  margin: 0;
  line-height: 1;
  vertical-align: sub;
  outline: none
}

.ant-radio-input:focus+.ant-radio-inner,
.ant-radio-wrapper:hover .ant-radio,
.ant-radio:hover .ant-radio-inner {
  border-color: #03a9f4
}

.ant-radio-input:focus+.ant-radio-inner {
  box-shadow: 0 0 0 3px rgba(3, 169, 244, .08)
}

.ant-radio-checked:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #03a9f4;
  border-radius: 50%;
  visibility: hidden;
  -webkit-animation: antRadioEffect .36s ease-in-out;
  animation: antRadioEffect .36s ease-in-out;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
  content: ""
}

.ant-radio-wrapper:hover .ant-radio:after,
.ant-radio:hover:after {
  visibility: visible
}

.ant-radio-inner {
  position: relative;
  top: 0;
  left: 0;
  display: block;
  width: 16px;
  height: 16px;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 100px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-radio-inner:after {
  position: absolute;
  top: 3px;
  left: 3px;
  display: table;
  width: 8px;
  height: 8px;
  background-color: #03a9f4;
  border-top: 0;
  border-left: 0;
  border-radius: 8px;
  -webkit-transform: scale(0);
  transform: scale(0);
  opacity: 0;
  -webkit-transition: all .3s cubic-bezier(.78, .14, .15, .86);
  transition: all .3s cubic-bezier(.78, .14, .15, .86);
  content: " "
}

.ant-radio-input {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  cursor: pointer;
  opacity: 0
}

.ant-radio-checked .ant-radio-inner {
  border-color: #03a9f4
}

.ant-radio-checked .ant-radio-inner:after {
  -webkit-transform: scale(1);
  transform: scale(1);
  opacity: 1;
  -webkit-transition: all .3s cubic-bezier(.78, .14, .15, .86);
  transition: all .3s cubic-bezier(.78, .14, .15, .86)
}

.ant-radio-disabled .ant-radio-inner {
  background-color: #f5f5f5;
  border-color: #d9d9d9 !important;
  cursor: not-allowed
}

.ant-radio-disabled .ant-radio-inner:after {
  background-color: rgba(0, 0, 0, .2)
}

.ant-radio-disabled .ant-radio-input {
  cursor: not-allowed
}

.ant-radio-disabled+span {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

span.ant-radio+* {
  padding-right: 8px;
  padding-left: 8px
}

.ant-radio-button-wrapper {
  position: relative;
  display: inline-block;
  height: 32px;
  margin: 0;
  padding: 0 15px;
  color: rgba(0, 0, 0, .65);
  line-height: 30px;
  background: #fff;
  border: 1px solid #d9d9d9;
  border-top: 1.02px solid #d9d9d9;
  border-left: 0;
  cursor: pointer;
  -webkit-transition: color .3s, background .3s, border-color .3s;
  transition: color .3s, background .3s, border-color .3s
}

.ant-radio-button-wrapper a {
  color: rgba(0, 0, 0, .65)
}

.ant-radio-button-wrapper>.ant-radio-button {
  display: block;
  width: 0;
  height: 0;
  margin-left: 0
}

.ant-radio-group-large .ant-radio-button-wrapper {
  height: 40px;
  font-size: 16px;
  line-height: 38px
}

.ant-radio-group-small .ant-radio-button-wrapper {
  height: 24px;
  padding: 0 7px;
  line-height: 22px
}

.ant-radio-button-wrapper:not(:first-child):before {
  position: absolute;
  top: 0;
  left: -1px;
  display: block;
  width: 1px;
  height: 100%;
  background-color: #d9d9d9;
  content: ""
}

.ant-radio-button-wrapper:first-child {
  border-left: 1px solid #d9d9d9;
  border-radius: 4px 0 0 4px
}

.ant-radio-button-wrapper:last-child {
  border-radius: 0 4px 4px 0
}

.ant-radio-button-wrapper:first-child:last-child {
  border-radius: 4px
}

.ant-radio-button-wrapper:hover {
  position: relative;
  color: #03a9f4
}

.ant-radio-button-wrapper:focus-within {
  outline: 3px solid rgba(3, 169, 244, .06)
}

.ant-radio-button-wrapper .ant-radio-inner,
.ant-radio-button-wrapper input[type=checkbox],
.ant-radio-button-wrapper input[type=radio] {
  width: 0;
  height: 0;
  opacity: 0;
  pointer-events: none
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled) {
  z-index: 1;
  color: #03a9f4;
  background: #fff;
  border-color: #03a9f4;
  box-shadow: -1px 0 0 0 #03a9f4
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):before {
  background-color: #03a9f4 !important;
  opacity: .1
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):first-child {
  border-color: #03a9f4;
  box-shadow: none !important
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):hover {
  color: #2bc3ff;
  border-color: #2bc3ff;
  box-shadow: -1px 0 0 0 #2bc3ff
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):active {
  color: #0086cf;
  border-color: #0086cf;
  box-shadow: -1px 0 0 0 #0086cf
}

.ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):focus-within {
  outline: 3px solid rgba(3, 169, 244, .06)
}

.ant-radio-group-solid .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled) {
  color: #fff;
  background: #03a9f4;
  border-color: #03a9f4
}

.ant-radio-group-solid .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):hover {
  color: #fff;
  background: #2bc3ff;
  border-color: #2bc3ff
}

.ant-radio-group-solid .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):active {
  color: #fff;
  background: #0086cf;
  border-color: #0086cf
}

.ant-radio-group-solid .ant-radio-button-wrapper-checked:not(.ant-radio-button-wrapper-disabled):focus-within {
  outline: 3px solid rgba(3, 169, 244, .06)
}

.ant-radio-button-wrapper-disabled {
  cursor: not-allowed
}

.ant-radio-button-wrapper-disabled,
.ant-radio-button-wrapper-disabled:first-child,
.ant-radio-button-wrapper-disabled:hover {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  border-color: #d9d9d9
}

.ant-radio-button-wrapper-disabled:first-child {
  border-left-color: #d9d9d9
}

.ant-radio-button-wrapper-disabled.ant-radio-button-wrapper-checked {
  color: #fff;
  background-color: #e6e6e6;
  border-color: #d9d9d9;
  box-shadow: none
}

@-webkit-keyframes antRadioEffect {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: .5
  }

  to {
    -webkit-transform: scale(1.6);
    transform: scale(1.6);
    opacity: 0
  }
}

@keyframes antRadioEffect {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1);
    opacity: .5
  }

  to {
    -webkit-transform: scale(1.6);
    transform: scale(1.6);
    opacity: 0
  }
}

@supports (-moz-appearance:meterbar) and (background-blend-mode:difference, normal) {
  .ant-radio {
    vertical-align: text-bottom
  }
}

.ant-rate {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  font-feature-settings: "tnum";
  display: inline-block;
  margin: 0;
  padding: 0;
  color: #fadb14;
  font-size: 20px;
  line-height: unset;
  list-style: none;
  outline: none
}

.ant-rate-disabled .ant-rate-star {
  cursor: default
}

.ant-rate-disabled .ant-rate-star:hover {
  -webkit-transform: scale(1);
  transform: scale(1)
}

.ant-rate-star {
  position: relative;
  display: inline-block;
  margin: 0;
  padding: 0;
  color: inherit;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-rate-star:not(:last-child) {
  margin-right: 8px
}

.ant-rate-star>div:focus {
  outline: 0
}

.ant-rate-star>div:focus,
.ant-rate-star>div:hover {
  -webkit-transform: scale(1.1);
  transform: scale(1.1)
}

.ant-rate-star-first,
.ant-rate-star-second {
  color: #e8e8e8;
  -webkit-transition: all .3s;
  transition: all .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-rate-star-first .anticon,
.ant-rate-star-second .anticon {
  vertical-align: middle
}

.ant-rate-star-first {
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  height: 100%;
  overflow: hidden;
  opacity: 0
}

.ant-rate-star-half .ant-rate-star-first,
.ant-rate-star-half .ant-rate-star-second {
  opacity: 1
}

.ant-rate-star-full .ant-rate-star-second,
.ant-rate-star-half .ant-rate-star-first {
  color: inherit
}

.ant-rate-text {
  display: inline-block;
  margin-left: 8px;
  font-size: 14px
}

.ant-result {
  padding: 48px 32px
}

.ant-result-success .ant-result-icon>.anticon {
  color: #52c41a
}

.ant-result-error .ant-result-icon>.anticon {
  color: #f5222d
}

.ant-result-info .ant-result-icon>.anticon {
  color: #1890ff
}

.ant-result-warning .ant-result-icon>.anticon {
  color: #faad14
}

.ant-result-image {
  width: 250px;
  height: 295px;
  margin: auto
}

.ant-result-icon {
  margin-bottom: 24px;
  text-align: center
}

.ant-result-icon>.anticon {
  font-size: 72px
}

.ant-result-title {
  color: rgba(0, 0, 0, .85);
  font-size: 24px;
  line-height: 1.8;
  text-align: center
}

.ant-result-subtitle {
  color: rgba(0, 0, 0, .45);
  font-size: 14px;
  line-height: 1.6;
  text-align: center
}

.ant-result-extra {
  margin-top: 32px;
  text-align: center
}

.ant-result-extra>* {
  margin-right: 8px
}

.ant-result-extra>:last-child {
  margin-right: 0
}

.ant-result-content {
  margin-top: 24px;
  padding: 24px 40px;
  background-color: #fafafa
}

.ant-select {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  outline: 0
}

.ant-select,
.ant-select ol,
.ant-select ul {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-select>ul>li>a {
  padding: 0;
  background-color: #fff
}

.ant-select-arrow {
  display: inline-block;
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: absolute;
  top: 50%;
  right: 11px;
  margin-top: -6px;
  color: rgba(0, 0, 0, .25);
  font-size: 12px;
  line-height: 1;
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%
}

.ant-select-arrow>* {
  line-height: 1
}

.ant-select-arrow svg {
  display: inline-block
}

.ant-select-arrow:before {
  display: none
}

.ant-select-arrow .ant-select-arrow-icon {
  display: block
}

.ant-select-arrow .ant-select-arrow-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-select-selection {
  display: block;
  box-sizing: border-box;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-top: 1.02px solid #d9d9d9;
  border-radius: 4px;
  outline: none;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-select-selection:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-select-focused .ant-select-selection,
.ant-select-selection:active,
.ant-select-selection:focus {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-select-selection__clear {
  position: absolute;
  top: 50%;
  right: 11px;
  z-index: 1;
  display: inline-block;
  width: 12px;
  height: 12px;
  margin-top: -6px;
  color: rgba(0, 0, 0, .25);
  font-size: 12px;
  font-style: normal;
  line-height: 12px;
  text-align: center;
  text-transform: none;
  background: #fff;
  cursor: pointer;
  opacity: 0;
  -webkit-transition: color .3s ease, opacity .15s ease;
  transition: color .3s ease, opacity .15s ease;
  text-rendering: auto
}

.ant-select-selection__clear:before {
  display: block
}

.ant-select-selection__clear:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-select-selection:hover .ant-select-selection__clear {
  opacity: 1
}

.ant-select-selection-selected-value {
  float: left;
  max-width: 100%;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-select-no-arrow .ant-select-selection-selected-value {
  padding-right: 0
}

.ant-select-disabled {
  color: rgba(0, 0, 0, .25)
}

.ant-select-disabled .ant-select-selection {
  background: #f5f5f5;
  cursor: not-allowed
}

.ant-select-disabled .ant-select-selection:active,
.ant-select-disabled .ant-select-selection:focus,
.ant-select-disabled .ant-select-selection:hover {
  border-color: #d9d9d9;
  box-shadow: none
}

.ant-select-disabled .ant-select-selection__clear {
  display: none;
  visibility: hidden;
  pointer-events: none
}

.ant-select-disabled .ant-select-selection--multiple .ant-select-selection__choice {
  padding-right: 10px;
  color: rgba(0, 0, 0, .33);
  background: #f5f5f5
}

.ant-select-disabled .ant-select-selection--multiple .ant-select-selection__choice__remove {
  display: none
}

.ant-select-selection--single {
  position: relative;
  height: 32px;
  cursor: pointer
}

.ant-select-selection--single .ant-select-selection__rendered {
  margin-right: 24px
}

.ant-select-no-arrow .ant-select-selection__rendered {
  margin-right: 11px
}

.ant-select-selection__rendered {
  position: relative;
  display: block;
  margin-right: 11px;
  margin-left: 11px;
  line-height: 30px
}

.ant-select-selection__rendered:after {
  display: inline-block;
  width: 0;
  visibility: hidden;
  content: ".";
  pointer-events: none
}

.ant-select-lg {
  font-size: 16px
}

.ant-select-lg .ant-select-selection--single {
  height: 40px
}

.ant-select-lg .ant-select-selection__rendered {
  line-height: 38px
}

.ant-select-lg .ant-select-selection--multiple {
  min-height: 40px
}

.ant-select-lg .ant-select-selection--multiple .ant-select-selection__rendered li {
  height: 32px;
  line-height: 32px
}

.ant-select-lg .ant-select-selection--multiple .ant-select-arrow,
.ant-select-lg .ant-select-selection--multiple .ant-select-selection__clear {
  top: 20px
}

.ant-select-sm .ant-select-selection--single {
  height: 24px
}

.ant-select-sm .ant-select-selection__rendered {
  margin-left: 7px;
  line-height: 22px
}

.ant-select-sm .ant-select-selection--multiple {
  min-height: 24px
}

.ant-select-sm .ant-select-selection--multiple .ant-select-selection__rendered li {
  height: 16px;
  line-height: 14px
}

.ant-select-sm .ant-select-selection--multiple .ant-select-arrow,
.ant-select-sm .ant-select-selection--multiple .ant-select-selection__clear {
  top: 12px
}

.ant-select-sm .ant-select-arrow,
.ant-select-sm .ant-select-selection__clear {
  right: 8px
}

.ant-select-disabled .ant-select-selection__choice__remove {
  color: rgba(0, 0, 0, .25);
  cursor: default
}

.ant-select-disabled .ant-select-selection__choice__remove:hover {
  color: rgba(0, 0, 0, .25)
}

.ant-select-search__field__wrap {
  position: relative;
  display: inline-block
}

.ant-select-search__field__placeholder,
.ant-select-selection__placeholder {
  position: absolute;
  top: 50%;
  right: 9px;
  left: 0;
  max-width: 100%;
  height: 20px;
  margin-top: -10px;
  overflow: hidden;
  color: #bfbfbf;
  line-height: 20px;
  white-space: nowrap;
  text-align: left;
  text-overflow: ellipsis
}

.ant-select-search__field__placeholder {
  left: 12px
}

.ant-select-search__field__mirror {
  position: absolute;
  top: 0;
  left: 0;
  white-space: pre;
  opacity: 0;
  pointer-events: none
}

.ant-select-search--inline {
  position: absolute;
  width: 100%;
  height: 100%
}

.ant-select-search--inline .ant-select-search__field__wrap {
  width: 100%;
  height: 100%
}

.ant-select-search--inline .ant-select-search__field {
  width: 100%;
  height: 100%;
  font-size: 100%;
  line-height: 1;
  background: transparent;
  border-width: 0;
  border-radius: 4px;
  outline: 0
}

.ant-select-search--inline>i {
  float: right
}

.ant-select-selection--multiple {
  min-height: 32px;
  padding-bottom: 3px;
  cursor: text;
  zoom: 1
}

.ant-select-selection--multiple:after,
.ant-select-selection--multiple:before {
  display: table;
  content: ""
}

.ant-select-selection--multiple:after {
  clear: both
}

.ant-select-selection--multiple .ant-select-search--inline {
  position: static;
  float: left;
  width: auto;
  max-width: 100%;
  padding: 0
}

.ant-select-selection--multiple .ant-select-search--inline .ant-select-search__field {
  width: .75em;
  max-width: 100%
}

.ant-select-selection--multiple .ant-select-selection__rendered {
  height: auto;
  margin-bottom: -3px;
  margin-left: 5px
}

.ant-select-selection--multiple .ant-select-selection__placeholder {
  margin-left: 6px
}

.ant-select-selection--multiple .ant-select-selection__rendered>ul>li,
.ant-select-selection--multiple>ul>li {
  height: 24px;
  margin-top: 3px;
  line-height: 22px
}

.ant-select-selection--multiple .ant-select-selection__choice {
  position: relative;
  float: left;
  max-width: 99%;
  margin-right: 4px;
  padding: 0 20px 0 10px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  background-color: #fafafa;
  border: 1px solid #e8e8e8;
  border-radius: 2px;
  cursor: default;
  -webkit-transition: padding .3s cubic-bezier(.645, .045, .355, 1);
  transition: padding .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-select-selection--multiple .ant-select-selection__choice__disabled {
  padding: 0 10px
}

.ant-select-selection--multiple .ant-select-selection__choice__content {
  display: inline-block;
  max-width: 100%;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  -webkit-transition: margin .3s cubic-bezier(.645, .045, .355, 1);
  transition: margin .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-select-selection--multiple .ant-select-selection__choice__remove {
  color: inherit;
  font-style: normal;
  line-height: 0;
  text-align: center;
  text-transform: none;
  vertical-align: -.125em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: absolute;
  right: 4px;
  color: rgba(0, 0, 0, .45);
  font-weight: 700;
  line-height: inherit;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s;
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

.ant-select-selection--multiple .ant-select-selection__choice__remove>* {
  line-height: 1
}

.ant-select-selection--multiple .ant-select-selection__choice__remove svg {
  display: inline-block
}

.ant-select-selection--multiple .ant-select-selection__choice__remove:before {
  display: none
}

.ant-select-selection--multiple .ant-select-selection__choice__remove .ant-select-selection--multiple .ant-select-selection__choice__remove-icon {
  display: block
}

:root .ant-select-selection--multiple .ant-select-selection__choice__remove {
  font-size: 12px
}

.ant-select-selection--multiple .ant-select-selection__choice__remove:hover {
  color: rgba(0, 0, 0, .75)
}

.ant-select-selection--multiple .ant-select-arrow,
.ant-select-selection--multiple .ant-select-selection__clear {
  top: 16px
}

.ant-select-allow-clear .ant-select-selection--single .ant-select-selection-selected-value {
  padding-right: 16px
}

.ant-select-allow-clear .ant-select-selection--multiple .ant-select-selection__rendered,
.ant-select-show-arrow .ant-select-selection--multiple .ant-select-selection__rendered {
  margin-right: 20px
}

.ant-select-open .ant-select-arrow-icon svg {
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.ant-select-open .ant-select-selection {
  border-color: #2bc3ff;
  border-right-width: 1px !important;
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-select-combobox .ant-select-arrow {
  display: none
}

.ant-select-combobox .ant-select-search--inline {
  float: none;
  width: 100%;
  height: 100%
}

.ant-select-combobox .ant-select-search__field__wrap {
  width: 100%;
  height: 100%
}

.ant-select-combobox .ant-select-search__field {
  position: relative;
  z-index: 1;
  width: 100%;
  height: 100%;
  box-shadow: none;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1), height 0s;
  transition: all .3s cubic-bezier(.645, .045, .355, 1), height 0s
}

.ant-select-combobox.ant-select-allow-clear .ant-select-selection:hover .ant-select-selection__rendered,
.ant-select-combobox.ant-select-show-arrow .ant-select-selection:hover .ant-select-selection__rendered {
  margin-right: 20px
}

.ant-select-dropdown {
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  top: -9999px;
  left: -9999px;
  z-index: 1050;
  box-sizing: border-box;
  font-size: 14px;
  font-variant: normal;
  background-color: #fff;
  border-radius: 4px;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-select-dropdown.slide-up-appear.slide-up-appear-active.ant-select-dropdown-placement-bottomLeft,
.ant-select-dropdown.slide-up-enter.slide-up-enter-active.ant-select-dropdown-placement-bottomLeft {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn
}

.ant-select-dropdown.slide-up-appear.slide-up-appear-active.ant-select-dropdown-placement-topLeft,
.ant-select-dropdown.slide-up-enter.slide-up-enter-active.ant-select-dropdown-placement-topLeft {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn
}

.ant-select-dropdown.slide-up-leave.slide-up-leave-active.ant-select-dropdown-placement-bottomLeft {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut
}

.ant-select-dropdown.slide-up-leave.slide-up-leave-active.ant-select-dropdown-placement-topLeft {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut
}

.ant-select-dropdown-hidden {
  display: none
}

.ant-select-dropdown-menu {
  max-height: 250px;
  margin-bottom: 0;
  padding-left: 0;
  overflow: auto;
  list-style: none;
  outline: none
}

.ant-select-dropdown-menu-item-group-list {
  margin: 0;
  padding: 0
}

.ant-select-dropdown-menu-item-group-list>.ant-select-dropdown-menu-item {
  padding-left: 20px
}

.ant-select-dropdown-menu-item-group-title {
  height: 32px;
  padding: 0 12px;
  color: rgba(0, 0, 0, .45);
  font-size: 12px;
  line-height: 32px
}

.ant-select-dropdown-menu-item-group-list .ant-select-dropdown-menu-item:first-child:not(:last-child),
.ant-select-dropdown-menu-item-group:not(:last-child) .ant-select-dropdown-menu-item-group-list .ant-select-dropdown-menu-item:last-child {
  border-radius: 0
}

.ant-select-dropdown-menu-item {
  position: relative;
  display: block;
  padding: 5px 12px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  font-weight: 400;
  line-height: 22px;
  white-space: nowrap;
  text-overflow: ellipsis;
  cursor: pointer;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-select-dropdown-menu-item:hover:not(.ant-select-dropdown-menu-item-disabled) {
  background-color: #e8f8ff
}

.ant-select-dropdown-menu-item:first-child {
  border-radius: 4px 4px 0 0
}

.ant-select-dropdown-menu-item:last-child {
  border-radius: 0 0 4px 4px
}

.ant-select-dropdown-menu-item-selected {
  color: rgba(0, 0, 0, .65);
  font-weight: 600;
  background-color: #fafafa
}

.ant-select-dropdown-menu-item-disabled,
.ant-select-dropdown-menu-item-disabled:hover {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-select-dropdown-menu-item-active:not(.ant-select-dropdown-menu-item-disabled) {
  background-color: #e8f8ff
}

.ant-select-dropdown-menu-item-divider {
  height: 1px;
  margin: 1px 0;
  overflow: hidden;
  line-height: 0;
  background-color: #e8e8e8
}

.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item {
  padding-right: 32px
}

.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item .ant-select-selected-icon {
  position: absolute;
  top: 50%;
  right: 12px;
  color: transparent;
  font-weight: 700;
  font-size: 12px;
  text-shadow: 0 .1px 0, .1px 0 0, 0 -.1px 0, -.1px 0;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
  -webkit-transition: all .2s;
  transition: all .2s
}

.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item:hover .ant-select-selected-icon {
  color: rgba(0, 0, 0, .87)
}

.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item-disabled .ant-select-selected-icon {
  display: none
}

.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item-selected .ant-select-selected-icon,
.ant-select-dropdown.ant-select-dropdown--multiple .ant-select-dropdown-menu-item-selected:hover .ant-select-selected-icon {
  display: inline-block;
  color: #03a9f4
}

.ant-select-dropdown--empty.ant-select-dropdown--multiple .ant-select-dropdown-menu-item {
  padding-right: 12px
}

.ant-select-dropdown-container-open .ant-select-dropdown,
.ant-select-dropdown-open .ant-select-dropdown {
  display: block
}

.ant-skeleton {
  display: table;
  width: 100%
}

.ant-skeleton-header {
  display: table-cell;
  padding-right: 16px;
  vertical-align: top
}

.ant-skeleton-header .ant-skeleton-avatar {
  display: inline-block;
  vertical-align: top;
  background: #f2f2f2;
  width: 32px;
  height: 32px;
  line-height: 32px
}

.ant-skeleton-header .ant-skeleton-avatar.ant-skeleton-avatar-circle {
  border-radius: 50%
}

.ant-skeleton-header .ant-skeleton-avatar-lg {
  width: 40px;
  height: 40px;
  line-height: 40px
}

.ant-skeleton-header .ant-skeleton-avatar-lg.ant-skeleton-avatar-circle {
  border-radius: 50%
}

.ant-skeleton-header .ant-skeleton-avatar-sm {
  width: 24px;
  height: 24px;
  line-height: 24px
}

.ant-skeleton-header .ant-skeleton-avatar-sm.ant-skeleton-avatar-circle {
  border-radius: 50%
}

.ant-skeleton-content {
  display: table-cell;
  width: 100%;
  vertical-align: top
}

.ant-skeleton-content .ant-skeleton-title {
  width: 100%;
  height: 16px;
  margin-top: 16px;
  background: #f2f2f2
}

.ant-skeleton-content .ant-skeleton-title+.ant-skeleton-paragraph {
  margin-top: 24px
}

.ant-skeleton-content .ant-skeleton-paragraph {
  padding: 0
}

.ant-skeleton-content .ant-skeleton-paragraph>li {
  width: 100%;
  height: 16px;
  list-style: none;
  background: #f2f2f2
}

.ant-skeleton-content .ant-skeleton-paragraph>li:last-child:not(:first-child):not(:nth-child(2)) {
  width: 61%
}

.ant-skeleton-content .ant-skeleton-paragraph>li+li {
  margin-top: 16px
}

.ant-skeleton-with-avatar .ant-skeleton-content .ant-skeleton-title {
  margin-top: 12px
}

.ant-skeleton-with-avatar .ant-skeleton-content .ant-skeleton-title+.ant-skeleton-paragraph {
  margin-top: 28px
}

.ant-skeleton.ant-skeleton-active .ant-skeleton-avatar,
.ant-skeleton.ant-skeleton-active .ant-skeleton-content .ant-skeleton-paragraph>li,
.ant-skeleton.ant-skeleton-active .ant-skeleton-content .ant-skeleton-title {
  background: -webkit-gradient(linear, left top, right top, color-stop(25%, #f2f2f2), color-stop(37%, #e6e6e6), color-stop(63%, #f2f2f2));
  background: linear-gradient(90deg, #f2f2f2 25%, #e6e6e6 37%, #f2f2f2 63%);
  background-size: 400% 100%;
  -webkit-animation: ant-skeleton-loading 1.4s ease infinite;
  animation: ant-skeleton-loading 1.4s ease infinite
}

@-webkit-keyframes ant-skeleton-loading {
  0% {
    background-position: 100% 50%
  }

  to {
    background-position: 0 50%
  }
}

@keyframes ant-skeleton-loading {
  0% {
    background-position: 100% 50%
  }

  to {
    background-position: 0 50%
  }
}

.ant-slider {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  height: 12px;
  margin: 14px 6px 10px;
  padding: 4px 0;
  cursor: pointer;
  touch-action: none
}

.ant-slider-vertical {
  width: 12px;
  height: 100%;
  margin: 6px 10px;
  padding: 0 4px
}

.ant-slider-vertical .ant-slider-rail {
  width: 4px;
  height: 100%
}

.ant-slider-vertical .ant-slider-track {
  width: 4px
}

.ant-slider-vertical .ant-slider-handle {
  margin-bottom: -7px;
  margin-left: -5px
}

.ant-slider-vertical .ant-slider-mark {
  top: 0;
  left: 12px;
  width: 18px;
  height: 100%
}

.ant-slider-vertical .ant-slider-mark-text {
  left: 4px;
  white-space: nowrap
}

.ant-slider-vertical .ant-slider-step {
  width: 4px;
  height: 100%
}

.ant-slider-vertical .ant-slider-dot {
  top: auto;
  left: 2px;
  margin-bottom: -4px
}

.ant-slider-with-marks {
  margin-bottom: 28px
}

.ant-slider-rail {
  width: 100%;
  background-color: #f5f5f5;
  border-radius: 2px
}

.ant-slider-rail,
.ant-slider-track {
  position: absolute;
  height: 4px;
  -webkit-transition: background-color .3s;
  transition: background-color .3s
}

.ant-slider-track {
  background-color: #7de3ff;
  border-radius: 4px
}

.ant-slider-handle {
  position: absolute;
  width: 14px;
  height: 14px;
  margin-top: -5px;
  background-color: #fff;
  border: 2px solid #7de3ff;
  border-radius: 50%;
  box-shadow: 0;
  cursor: pointer;
  -webkit-transition: border-color .3s, box-shadow .6s, -webkit-transform .3s cubic-bezier(.18, .89, .32, 1.28);
  transition: border-color .3s, box-shadow .6s, -webkit-transform .3s cubic-bezier(.18, .89, .32, 1.28);
  transition: border-color .3s, box-shadow .6s, transform .3s cubic-bezier(.18, .89, .32, 1.28);
  transition: border-color .3s, box-shadow .6s, transform .3s cubic-bezier(.18, .89, .32, 1.28), -webkit-transform .3s cubic-bezier(.18, .89, .32, 1.28)
}

.ant-slider-handle:focus {
  border-color: #35baf6;
  outline: none;
  box-shadow: 0 0 0 5px rgba(3, 169, 244, .2)
}

.ant-slider-handle.ant-tooltip-open {
  border-color: #03a9f4
}

.ant-slider:hover .ant-slider-rail {
  background-color: #e1e1e1
}

.ant-slider:hover .ant-slider-track {
  background-color: #54d4ff
}

.ant-slider:hover .ant-slider-handle:not(.ant-tooltip-open) {
  border-color: #54d4ff
}

.ant-slider-mark {
  position: absolute;
  top: 14px;
  left: 0;
  width: 100%;
  font-size: 14px
}

.ant-slider-mark-text {
  position: absolute;
  display: inline-block;
  color: rgba(0, 0, 0, .45);
  text-align: center;
  word-break: keep-all;
  cursor: pointer
}

.ant-slider-mark-text-active {
  color: rgba(0, 0, 0, .65)
}

.ant-slider-step {
  position: absolute;
  width: 100%;
  height: 4px;
  background: transparent
}

.ant-slider-dot {
  position: absolute;
  top: -2px;
  width: 8px;
  height: 8px;
  background-color: #fff;
  border: 2px solid #e8e8e8;
  border-radius: 50%;
  cursor: pointer
}

.ant-slider-dot,
.ant-slider-dot:first-child,
.ant-slider-dot:last-child {
  margin-left: -4px
}

.ant-slider-dot-active {
  border-color: #81d4fa
}

.ant-slider-disabled {
  cursor: not-allowed
}

.ant-slider-disabled .ant-slider-track {
  background-color: rgba(0, 0, 0, .25) !important
}

.ant-slider-disabled .ant-slider-dot,
.ant-slider-disabled .ant-slider-handle {
  background-color: #fff;
  border-color: rgba(0, 0, 0, .25) !important;
  box-shadow: none;
  cursor: not-allowed
}

.ant-slider-disabled .ant-slider-dot,
.ant-slider-disabled .ant-slider-mark-text {
  cursor: not-allowed !important
}

.ant-spin {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  display: none;
  color: #03a9f4;
  text-align: center;
  vertical-align: middle;
  opacity: 0;
  -webkit-transition: -webkit-transform .3s cubic-bezier(.78, .14, .15, .86);
  transition: -webkit-transform .3s cubic-bezier(.78, .14, .15, .86);
  transition: transform .3s cubic-bezier(.78, .14, .15, .86);
  transition: transform .3s cubic-bezier(.78, .14, .15, .86), -webkit-transform .3s cubic-bezier(.78, .14, .15, .86)
}

.ant-spin-spinning {
  position: static;
  display: inline-block;
  opacity: 1
}

.ant-spin-nested-loading {
  position: relative
}

.ant-spin-nested-loading>div>.ant-spin {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 4;
  display: block;
  width: 100%;
  height: 100%;
  max-height: 400px
}

.ant-spin-nested-loading>div>.ant-spin .ant-spin-dot {
  position: absolute;
  top: 50%;
  left: 50%;
  margin: -10px
}

.ant-spin-nested-loading>div>.ant-spin .ant-spin-text {
  position: absolute;
  top: 50%;
  width: 100%;
  padding-top: 5px;
  text-shadow: 0 1px 2px #fff
}

.ant-spin-nested-loading>div>.ant-spin.ant-spin-show-text .ant-spin-dot {
  margin-top: -20px
}

.ant-spin-nested-loading>div>.ant-spin-sm .ant-spin-dot {
  margin: -7px
}

.ant-spin-nested-loading>div>.ant-spin-sm .ant-spin-text {
  padding-top: 2px
}

.ant-spin-nested-loading>div>.ant-spin-sm.ant-spin-show-text .ant-spin-dot {
  margin-top: -17px
}

.ant-spin-nested-loading>div>.ant-spin-lg .ant-spin-dot {
  margin: -16px
}

.ant-spin-nested-loading>div>.ant-spin-lg .ant-spin-text {
  padding-top: 11px
}

.ant-spin-nested-loading>div>.ant-spin-lg.ant-spin-show-text .ant-spin-dot {
  margin-top: -26px
}

.ant-spin-container {
  position: relative;
  -webkit-transition: opacity .3s;
  transition: opacity .3s
}

.ant-spin-container:after {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 10;
  display: none\9;
  width: 100%;
  height: 100%;
  background: #fff;
  opacity: 0;
  -webkit-transition: all .3s;
  transition: all .3s;
  content: "";
  pointer-events: none
}

.ant-spin-blur {
  clear: both;
  overflow: hidden;
  opacity: .5;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  pointer-events: none
}

.ant-spin-blur:after {
  opacity: .4;
  pointer-events: auto
}

.ant-spin-tip {
  color: rgba(0, 0, 0, .45)
}

.ant-spin-dot {
  position: relative;
  display: inline-block;
  font-size: 20px;
  width: 1em;
  height: 1em
}

.ant-spin-dot-item {
  position: absolute;
  display: block;
  width: 9px;
  height: 9px;
  background-color: #03a9f4;
  border-radius: 100%;
  -webkit-transform: scale(.75);
  transform: scale(.75);
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  opacity: .3;
  -webkit-animation: antSpinMove 1s linear infinite alternate;
  animation: antSpinMove 1s linear infinite alternate
}

.ant-spin-dot-item:first-child {
  top: 0;
  left: 0
}

.ant-spin-dot-item:nth-child(2) {
  top: 0;
  right: 0;
  -webkit-animation-delay: .4s;
  animation-delay: .4s
}

.ant-spin-dot-item:nth-child(3) {
  right: 0;
  bottom: 0;
  -webkit-animation-delay: .8s;
  animation-delay: .8s
}

.ant-spin-dot-item:nth-child(4) {
  bottom: 0;
  left: 0;
  -webkit-animation-delay: 1.2s;
  animation-delay: 1.2s
}

.ant-spin-dot-spin {
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
  -webkit-animation: antRotate 1.2s linear infinite;
  animation: antRotate 1.2s linear infinite
}

.ant-spin-sm .ant-spin-dot {
  font-size: 14px
}

.ant-spin-sm .ant-spin-dot i {
  width: 6px;
  height: 6px
}

.ant-spin-lg .ant-spin-dot {
  font-size: 32px
}

.ant-spin-lg .ant-spin-dot i {
  width: 14px;
  height: 14px
}

.ant-spin.ant-spin-show-text .ant-spin-text {
  display: block
}

@media (-ms-high-contrast:active),
(-ms-high-contrast:none) {
  .ant-spin-blur {
    background: #fff;
    opacity: .5
  }
}

@-webkit-keyframes antSpinMove {
  to {
    opacity: 1
  }
}

@keyframes antSpinMove {
  to {
    opacity: 1
  }
}

@-webkit-keyframes antRotate {
  to {
    -webkit-transform: rotate(405deg);
    transform: rotate(405deg)
  }
}

@keyframes antRotate {
  to {
    -webkit-transform: rotate(405deg);
    transform: rotate(405deg)
  }
}

.ant-statistic {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-statistic-title {
  margin-bottom: 4px;
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-statistic-content {
  color: rgba(0, 0, 0, .85);
  font-size: 24px;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol
}

.ant-statistic-content-value-decimal {
  font-size: 16px
}

.ant-statistic-content-prefix,
.ant-statistic-content-suffix {
  display: inline-block
}

.ant-statistic-content-prefix {
  margin-right: 4px
}

.ant-statistic-content-suffix {
  margin-left: 4px;
  font-size: 16px
}

.ant-steps {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: flex;
  width: 100%;
  font-size: 0
}

.ant-steps-item {
  position: relative;
  display: inline-block;
  flex: 1 1;
  overflow: hidden;
  vertical-align: top
}

.ant-steps-item-container {
  outline: none
}

.ant-steps-item:last-child {
  flex: none
}

.ant-steps-item:last-child>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after,
.ant-steps-item:last-child>.ant-steps-item-container>.ant-steps-item-tail {
  display: none
}

.ant-steps-item-content,
.ant-steps-item-icon {
  display: inline-block;
  vertical-align: top
}

.ant-steps-item-icon {
  width: 32px;
  height: 32px;
  margin-right: 8px;
  font-size: 16px;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol;
  line-height: 32px;
  text-align: center;
  border: 1px solid rgba(0, 0, 0, .25);
  border-radius: 32px;
  -webkit-transition: background-color .3s, border-color .3s;
  transition: background-color .3s, border-color .3s
}

.ant-steps-item-icon>.ant-steps-icon {
  position: relative;
  top: -1px;
  color: #03a9f4;
  line-height: 1
}

.ant-steps-item-tail {
  position: absolute;
  top: 12px;
  left: 0;
  width: 100%;
  padding: 0 10px
}

.ant-steps-item-tail:after {
  display: inline-block;
  width: 100%;
  height: 1px;
  background: #e8e8e8;
  border-radius: 1px;
  -webkit-transition: background .3s;
  transition: background .3s;
  content: ""
}

.ant-steps-item-title {
  position: relative;
  display: inline-block;
  padding-right: 16px;
  color: rgba(0, 0, 0, .65);
  font-size: 16px;
  line-height: 32px
}

.ant-steps-item-title:after {
  position: absolute;
  top: 16px;
  left: 100%;
  display: block;
  width: 9999px;
  height: 1px;
  background: #e8e8e8;
  content: ""
}

.ant-steps-item-subtitle {
  display: inline;
  margin-left: 8px;
  font-weight: 400
}

.ant-steps-item-description,
.ant-steps-item-subtitle {
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-steps-item-wait .ant-steps-item-icon {
  background-color: #fff;
  border-color: rgba(0, 0, 0, .25)
}

.ant-steps-item-wait .ant-steps-item-icon>.ant-steps-icon {
  color: rgba(0, 0, 0, .25)
}

.ant-steps-item-wait .ant-steps-item-icon>.ant-steps-icon .ant-steps-icon-dot {
  background: rgba(0, 0, 0, .25)
}

.ant-steps-item-wait>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title {
  color: rgba(0, 0, 0, .45)
}

.ant-steps-item-wait>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
  background-color: #e8e8e8
}

.ant-steps-item-wait>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-description {
  color: rgba(0, 0, 0, .45)
}

.ant-steps-item-wait>.ant-steps-item-container>.ant-steps-item-tail:after {
  background-color: #e8e8e8
}

.ant-steps-item-process .ant-steps-item-icon {
  background-color: #fff;
  border-color: #03a9f4
}

.ant-steps-item-process .ant-steps-item-icon>.ant-steps-icon {
  color: #03a9f4
}

.ant-steps-item-process .ant-steps-item-icon>.ant-steps-icon .ant-steps-icon-dot {
  background: #03a9f4
}

.ant-steps-item-process>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title {
  color: rgba(0, 0, 0, .85)
}

.ant-steps-item-process>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
  background-color: #e8e8e8
}

.ant-steps-item-process>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-description {
  color: rgba(0, 0, 0, .65)
}

.ant-steps-item-process>.ant-steps-item-container>.ant-steps-item-tail:after {
  background-color: #e8e8e8
}

.ant-steps-item-process .ant-steps-item-icon {
  background: #03a9f4
}

.ant-steps-item-process .ant-steps-item-icon>.ant-steps-icon {
  color: #fff
}

.ant-steps-item-process .ant-steps-item-title {
  font-weight: 500
}

.ant-steps-item-finish .ant-steps-item-icon {
  background-color: #fff;
  border-color: #03a9f4
}

.ant-steps-item-finish .ant-steps-item-icon>.ant-steps-icon {
  color: #03a9f4
}

.ant-steps-item-finish .ant-steps-item-icon>.ant-steps-icon .ant-steps-icon-dot {
  background: #03a9f4
}

.ant-steps-item-finish>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title {
  color: rgba(0, 0, 0, .65)
}

.ant-steps-item-finish>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
  background-color: #03a9f4
}

.ant-steps-item-finish>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-description {
  color: rgba(0, 0, 0, .45)
}

.ant-steps-item-finish>.ant-steps-item-container>.ant-steps-item-tail:after {
  background-color: #03a9f4
}

.ant-steps-item-error .ant-steps-item-icon {
  background-color: #fff;
  border-color: #f5222d
}

.ant-steps-item-error .ant-steps-item-icon>.ant-steps-icon {
  color: #f5222d
}

.ant-steps-item-error .ant-steps-item-icon>.ant-steps-icon .ant-steps-icon-dot {
  background: #f5222d
}

.ant-steps-item-error>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title {
  color: #f5222d
}

.ant-steps-item-error>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
  background-color: #e8e8e8
}

.ant-steps-item-error>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-description {
  color: #f5222d
}

.ant-steps-item-error>.ant-steps-item-container>.ant-steps-item-tail:after {
  background-color: #e8e8e8
}

.ant-steps-item.ant-steps-next-error .ant-steps-item-title:after {
  background: #f5222d
}

.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button] {
  cursor: pointer
}

.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button] .ant-steps-item-description,
.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button] .ant-steps-item-icon .ant-steps-icon,
.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button] .ant-steps-item-title {
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button]:hover .ant-steps-item-description,
.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button]:hover .ant-steps-item-subtitle,
.ant-steps .ant-steps-item:not(.ant-steps-item-active)>.ant-steps-item-container[role=button]:hover .ant-steps-item-title {
  color: #03a9f4
}

.ant-steps .ant-steps-item:not(.ant-steps-item-active):not(.ant-steps-item-process)>.ant-steps-item-container[role=button]:hover .ant-steps-item-icon {
  border-color: #03a9f4
}

.ant-steps .ant-steps-item:not(.ant-steps-item-active):not(.ant-steps-item-process)>.ant-steps-item-container[role=button]:hover .ant-steps-item-icon .ant-steps-icon {
  color: #03a9f4
}

.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item {
  margin-right: 16px;
  white-space: nowrap
}

.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item:last-child {
  margin-right: 0
}

.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item:last-child .ant-steps-item-title {
  padding-right: 0
}

.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item-tail {
  display: none
}

.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item-description {
  max-width: 140px;
  white-space: normal
}

.ant-steps-item-custom .ant-steps-item-icon {
  height: auto;
  background: none;
  border: 0
}

.ant-steps-item-custom .ant-steps-item-icon>.ant-steps-icon {
  top: 0;
  left: .5px;
  width: 32px;
  height: 32px;
  font-size: 24px;
  line-height: 32px
}

.ant-steps-item-custom.ant-steps-item-process .ant-steps-item-icon>.ant-steps-icon {
  color: #03a9f4
}

.ant-steps:not(.ant-steps-vertical) .ant-steps-item-custom .ant-steps-item-icon {
  width: auto
}

.ant-steps-small.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item {
  margin-right: 12px
}

.ant-steps-small.ant-steps-horizontal:not(.ant-steps-label-vertical) .ant-steps-item:last-child {
  margin-right: 0
}

.ant-steps-small .ant-steps-item-icon {
  width: 24px;
  height: 24px;
  font-size: 12px;
  line-height: 24px;
  text-align: center;
  border-radius: 24px
}

.ant-steps-small .ant-steps-item-title {
  padding-right: 12px;
  font-size: 14px;
  line-height: 24px
}

.ant-steps-small .ant-steps-item-title:after {
  top: 12px
}

.ant-steps-small .ant-steps-item-description {
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-steps-small .ant-steps-item-tail {
  top: 8px
}

.ant-steps-small .ant-steps-item-custom .ant-steps-item-icon {
  width: inherit;
  height: inherit;
  line-height: inherit;
  background: none;
  border: 0;
  border-radius: 0
}

.ant-steps-small .ant-steps-item-custom .ant-steps-item-icon>.ant-steps-icon {
  font-size: 24px;
  line-height: 24px;
  -webkit-transform: none;
  transform: none
}

.ant-steps-vertical {
  display: block
}

.ant-steps-vertical .ant-steps-item {
  display: block;
  overflow: visible
}

.ant-steps-vertical .ant-steps-item-icon {
  float: left;
  margin-right: 16px
}

.ant-steps-vertical .ant-steps-item-content {
  display: block;
  min-height: 48px;
  overflow: hidden
}

.ant-steps-vertical .ant-steps-item-title {
  line-height: 32px
}

.ant-steps-vertical .ant-steps-item-description {
  padding-bottom: 12px
}

.ant-steps-vertical>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-tail {
  position: absolute;
  top: 0;
  left: 16px;
  width: 1px;
  height: 100%;
  padding: 38px 0 6px
}

.ant-steps-vertical>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-tail:after {
  width: 1px;
  height: 100%
}

.ant-steps-vertical>.ant-steps-item:not(:last-child)>.ant-steps-item-container>.ant-steps-item-tail {
  display: block
}

.ant-steps-vertical>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
  display: none
}

.ant-steps-vertical.ant-steps-small .ant-steps-item-container .ant-steps-item-tail {
  position: absolute;
  top: 0;
  left: 12px;
  padding: 30px 0 6px
}

.ant-steps-vertical.ant-steps-small .ant-steps-item-container .ant-steps-item-title {
  line-height: 24px
}

@media (max-width:480px) {
  .ant-steps-horizontal.ant-steps-label-horizontal {
    display: block
  }

  .ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item {
    display: block;
    overflow: visible
  }

  .ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item-icon {
    float: left;
    margin-right: 16px
  }

  .ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item-content {
    display: block;
    min-height: 48px;
    overflow: hidden
  }

  .ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item-title {
    line-height: 32px
  }

  .ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item-description {
    padding-bottom: 12px
  }

  .ant-steps-horizontal.ant-steps-label-horizontal>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-tail {
    position: absolute;
    top: 0;
    left: 16px;
    width: 1px;
    height: 100%;
    padding: 38px 0 6px
  }

  .ant-steps-horizontal.ant-steps-label-horizontal>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-tail:after {
    width: 1px;
    height: 100%
  }

  .ant-steps-horizontal.ant-steps-label-horizontal>.ant-steps-item:not(:last-child)>.ant-steps-item-container>.ant-steps-item-tail {
    display: block
  }

  .ant-steps-horizontal.ant-steps-label-horizontal>.ant-steps-item>.ant-steps-item-container>.ant-steps-item-content>.ant-steps-item-title:after {
    display: none
  }

  .ant-steps-horizontal.ant-steps-label-horizontal.ant-steps-small .ant-steps-item-container .ant-steps-item-tail {
    position: absolute;
    top: 0;
    left: 12px;
    padding: 30px 0 6px
  }

  .ant-steps-horizontal.ant-steps-label-horizontal.ant-steps-small .ant-steps-item-container .ant-steps-item-title {
    line-height: 24px
  }
}

.ant-steps-label-vertical .ant-steps-item {
  overflow: visible
}

.ant-steps-label-vertical .ant-steps-item-tail {
  margin-left: 51px;
  padding: 3.5px 24px
}

.ant-steps-label-vertical .ant-steps-item-content {
  display: block;
  width: 104px;
  margin-top: 8px;
  text-align: center
}

.ant-steps-label-vertical .ant-steps-item-icon {
  display: inline-block;
  margin-left: 36px
}

.ant-steps-label-vertical .ant-steps-item-title {
  padding-right: 0
}

.ant-steps-label-vertical .ant-steps-item-title:after {
  display: none
}

.ant-steps-label-vertical.ant-steps-small:not(.ant-steps-dot) .ant-steps-item-icon {
  margin-left: 40px
}

.ant-steps-dot .ant-steps-item-title,
.ant-steps-dot.ant-steps-small .ant-steps-item-title {
  line-height: 1.5
}

.ant-steps-dot .ant-steps-item-tail,
.ant-steps-dot.ant-steps-small .ant-steps-item-tail {
  top: 2px;
  width: 100%;
  margin: 0 0 0 70px;
  padding: 0
}

.ant-steps-dot .ant-steps-item-tail:after,
.ant-steps-dot.ant-steps-small .ant-steps-item-tail:after {
  width: calc(100% - 20px);
  height: 3px;
  margin-left: 12px
}

.ant-steps-dot .ant-steps-item:first-child .ant-steps-icon-dot,
.ant-steps-dot.ant-steps-small .ant-steps-item:first-child .ant-steps-icon-dot {
  left: 2px
}

.ant-steps-dot .ant-steps-item-icon,
.ant-steps-dot.ant-steps-small .ant-steps-item-icon {
  width: 8px;
  height: 8px;
  margin-left: 67px;
  padding-right: 0;
  line-height: 8px;
  background: transparent;
  border: 0
}

.ant-steps-dot .ant-steps-item-icon .ant-steps-icon-dot,
.ant-steps-dot.ant-steps-small .ant-steps-item-icon .ant-steps-icon-dot {
  position: relative;
  float: left;
  width: 100%;
  height: 100%;
  border-radius: 100px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-steps-dot .ant-steps-item-icon .ant-steps-icon-dot:after,
.ant-steps-dot.ant-steps-small .ant-steps-item-icon .ant-steps-icon-dot:after {
  position: absolute;
  top: -12px;
  left: -26px;
  width: 60px;
  height: 32px;
  background: rgba(0, 0, 0, .001);
  content: ""
}

.ant-steps-dot .ant-steps-item-content,
.ant-steps-dot.ant-steps-small .ant-steps-item-content {
  width: 140px
}

.ant-steps-dot .ant-steps-item-process .ant-steps-item-icon,
.ant-steps-dot.ant-steps-small .ant-steps-item-process .ant-steps-item-icon {
  width: 10px;
  height: 10px;
  line-height: 10px
}

.ant-steps-dot .ant-steps-item-process .ant-steps-item-icon .ant-steps-icon-dot,
.ant-steps-dot.ant-steps-small .ant-steps-item-process .ant-steps-item-icon .ant-steps-icon-dot {
  top: -1px
}

.ant-steps-vertical.ant-steps-dot .ant-steps-item-icon {
  margin-top: 8px;
  margin-left: 0
}

.ant-steps-vertical.ant-steps-dot .ant-steps-item>.ant-steps-item-container>.ant-steps-item-tail {
  top: 2px;
  left: -9px;
  margin: 0;
  padding: 22px 0 4px
}

.ant-steps-vertical.ant-steps-dot .ant-steps-item:first-child .ant-steps-icon-dot {
  left: 0
}

.ant-steps-vertical.ant-steps-dot .ant-steps-item-process .ant-steps-icon-dot {
  left: -2px
}

.ant-steps-navigation {
  padding-top: 12px
}

.ant-steps-navigation.ant-steps-small .ant-steps-item-container {
  margin-left: -12px
}

.ant-steps-navigation .ant-steps-item {
  overflow: visible;
  text-align: center
}

.ant-steps-navigation .ant-steps-item-container {
  display: inline-block;
  height: 100%;
  margin-left: -16px;
  padding-bottom: 12px;
  text-align: left;
  -webkit-transition: opacity .3s;
  transition: opacity .3s
}

.ant-steps-navigation .ant-steps-item-container .ant-steps-item-content {
  max-width: 140px
}

.ant-steps-navigation .ant-steps-item-container .ant-steps-item-title {
  max-width: 100%;
  padding-right: 0;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-steps-navigation .ant-steps-item-container .ant-steps-item-title:after {
  display: none
}

.ant-steps-navigation .ant-steps-item:not(.ant-steps-item-active) .ant-steps-item-container[role=button] {
  cursor: pointer
}

.ant-steps-navigation .ant-steps-item:not(.ant-steps-item-active) .ant-steps-item-container[role=button]:hover {
  opacity: .85
}

.ant-steps-navigation .ant-steps-item:last-child {
  flex: 1 1
}

.ant-steps-navigation .ant-steps-item:last-child:after {
  display: none
}

.ant-steps-navigation .ant-steps-item:after {
  position: absolute;
  top: 50%;
  left: 100%;
  display: inline-block;
  width: 12px;
  height: 12px;
  margin-top: -14px;
  margin-left: -2px;
  border: 1px solid rgba(0, 0, 0, .25);
  border-bottom: none;
  border-left: none;
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
  content: ""
}

.ant-steps-navigation .ant-steps-item:before {
  position: absolute;
  bottom: 0;
  left: 50%;
  display: inline-block;
  width: 0;
  height: 3px;
  background-color: #03a9f4;
  -webkit-transition: width .3s, left .3s;
  transition: width .3s, left .3s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
  content: ""
}

.ant-steps-navigation .ant-steps-item.ant-steps-item-active:before {
  left: 0;
  width: 100%
}

.ant-steps-flex-not-supported.ant-steps-horizontal.ant-steps-label-horizontal .ant-steps-item {
  margin-left: -16px;
  padding-left: 16px;
  background: #fff
}

.ant-steps-flex-not-supported.ant-steps-horizontal.ant-steps-label-horizontal.ant-steps-small .ant-steps-item {
  margin-left: -12px;
  padding-left: 12px
}

.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item:last-child {
  overflow: hidden
}

.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item:last-child .ant-steps-icon-dot:after {
  right: -200px;
  width: 200px
}

.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item .ant-steps-icon-dot:after,
.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item .ant-steps-icon-dot:before {
  position: absolute;
  top: 0;
  left: -10px;
  width: 10px;
  height: 8px;
  background: #fff;
  content: ""
}

.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item .ant-steps-icon-dot:after {
  right: -10px;
  left: auto
}

.ant-steps-flex-not-supported.ant-steps-dot .ant-steps-item-wait .ant-steps-item-icon>.ant-steps-icon .ant-steps-icon-dot {
  background: #ccc
}

.ant-switch {
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  display: inline-block;
  box-sizing: border-box;
  min-width: 44px;
  height: 22px;
  line-height: 20px;
  vertical-align: middle;
  background-color: rgba(0, 0, 0, .25);
  border: 1px solid transparent;
  border-radius: 100px;
  cursor: pointer;
  -webkit-transition: all .36s;
  transition: all .36s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-switch-inner {
  display: block;
  margin-right: 6px;
  margin-left: 24px;
  color: #fff;
  font-size: 12px
}

.ant-switch-loading-icon,
.ant-switch:after {
  position: absolute;
  top: 1px;
  left: 1px;
  width: 18px;
  height: 18px;
  background-color: #fff;
  border-radius: 18px;
  cursor: pointer;
  -webkit-transition: all .36s cubic-bezier(.78, .14, .15, .86);
  transition: all .36s cubic-bezier(.78, .14, .15, .86);
  content: " "
}

.ant-switch:after {
  box-shadow: 0 2px 4px 0 rgba(0, 35, 11, .2)
}

.ant-switch:not(.ant-switch-disabled):active:after,
.ant-switch:not(.ant-switch-disabled):active:before {
  width: 24px
}

.ant-switch-loading-icon {
  z-index: 1;
  display: none;
  font-size: 12px;
  background: transparent
}

.ant-switch-loading-icon svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.ant-switch-loading .ant-switch-loading-icon {
  display: inline-block;
  color: rgba(0, 0, 0, .65)
}

.ant-switch-checked.ant-switch-loading .ant-switch-loading-icon {
  color: #03a9f4
}

.ant-switch:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-switch:focus:hover {
  box-shadow: none
}

.ant-switch-small {
  min-width: 28px;
  height: 16px;
  line-height: 14px
}

.ant-switch-small .ant-switch-inner {
  margin-right: 3px;
  margin-left: 18px;
  font-size: 12px
}

.ant-switch-small:after {
  width: 12px;
  height: 12px
}

.ant-switch-small:active:after,
.ant-switch-small:active:before {
  width: 16px
}

.ant-switch-small .ant-switch-loading-icon {
  width: 12px;
  height: 12px
}

.ant-switch-small.ant-switch-checked .ant-switch-inner {
  margin-right: 18px;
  margin-left: 3px
}

.ant-switch-small.ant-switch-checked .ant-switch-loading-icon {
  left: 100%;
  margin-left: -13px
}

.ant-switch-small.ant-switch-loading .ant-switch-loading-icon {
  font-weight: 700;
  -webkit-transform: scale(.66667);
  transform: scale(.66667)
}

.ant-switch-checked {
  background-color: #03a9f4
}

.ant-switch-checked .ant-switch-inner {
  margin-right: 24px;
  margin-left: 6px
}

.ant-switch-checked:after {
  left: 100%;
  margin-left: -1px;
  -webkit-transform: translateX(-100%);
  transform: translateX(-100%)
}

.ant-switch-checked .ant-switch-loading-icon {
  left: 100%;
  margin-left: -19px
}

.ant-switch-disabled,
.ant-switch-loading {
  cursor: not-allowed;
  opacity: .4
}

.ant-switch-disabled *,
.ant-switch-disabled:after,
.ant-switch-disabled:before,
.ant-switch-loading *,
.ant-switch-loading:after,
.ant-switch-loading:before {
  cursor: not-allowed
}

@-webkit-keyframes AntSwitchSmallLoadingCircle {
  0% {
    -webkit-transform: rotate(0deg) scale(.66667);
    transform: rotate(0deg) scale(.66667);
    -webkit-transform-origin: 50% 50%;
    transform-origin: 50% 50%
  }

  to {
    -webkit-transform: rotate(1turn) scale(.66667);
    transform: rotate(1turn) scale(.66667);
    -webkit-transform-origin: 50% 50%;
    transform-origin: 50% 50%
  }
}

@keyframes AntSwitchSmallLoadingCircle {
  0% {
    -webkit-transform: rotate(0deg) scale(.66667);
    transform: rotate(0deg) scale(.66667);
    -webkit-transform-origin: 50% 50%;
    transform-origin: 50% 50%
  }

  to {
    -webkit-transform: rotate(1turn) scale(.66667);
    transform: rotate(1turn) scale(.66667);
    -webkit-transform-origin: 50% 50%;
    transform-origin: 50% 50%
  }
}

.ant-table-wrapper {
  zoom: 1
}

.ant-table-wrapper:after,
.ant-table-wrapper:before {
  display: table;
  content: ""
}

.ant-table-wrapper:after {
  clear: both
}

.ant-table {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  clear: both
}

.ant-table-body {
  -webkit-transition: opacity .3s;
  transition: opacity .3s
}

.ant-table-empty .ant-table-body {
  overflow-x: auto !important;
  overflow-y: hidden !important
}

.ant-table table {
  width: 100%;
  text-align: left;
  border-radius: 4px 4px 0 0;
  border-collapse: separate;
  border-spacing: 0
}

.ant-table-layout-fixed table {
  table-layout: fixed
}

.ant-table-thead>tr>th {
  color: rgba(0, 0, 0, .85);
  font-weight: 500;
  text-align: left;
  background: #fafafa;
  border-bottom: 1px solid #e8e8e8;
  -webkit-transition: background .3s ease;
  transition: background .3s ease
}

.ant-table-thead>tr>th[colspan] {
  text-align: center
}

.ant-table-thead>tr>th .ant-table-filter-icon,
.ant-table-thead>tr>th .anticon-filter {
  position: absolute;
  top: 0;
  right: 0;
  width: 28px;
  height: 100%;
  color: #bfbfbf;
  font-size: 12px;
  text-align: center;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-table-thead>tr>th .ant-table-filter-icon>svg,
.ant-table-thead>tr>th .anticon-filter>svg {
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -5px;
  margin-left: -6px
}

.ant-table-thead>tr>th .ant-table-filter-selected.anticon-filter {
  color: #03a9f4
}

.ant-table-thead>tr>th .ant-table-column-sorter {
  display: table-cell;
  vertical-align: middle
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner {
  height: 1em;
  margin-top: .35em;
  margin-left: .57142857em;
  color: #bfbfbf;
  line-height: 1em;
  text-align: center;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-down,
.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-up {
  display: inline-block;
  font-size: 12px;
  font-size: 11px\9;
  -webkit-transform: scale(.91666667) rotate(0deg);
  transform: scale(.91666667) rotate(0deg);
  display: block;
  height: 1em;
  line-height: 1em;
  -webkit-transition: all .3s;
  transition: all .3s
}

:root .ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-down,
:root .ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-up {
  font-size: 12px
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-down.on,
.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner .ant-table-column-sorter-up.on {
  color: #03a9f4
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner-full {
  margin-top: -.15em
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner-full .ant-table-column-sorter-down,
.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner-full .ant-table-column-sorter-up {
  height: .5em;
  line-height: .5em
}

.ant-table-thead>tr>th .ant-table-column-sorter .ant-table-column-sorter-inner-full .ant-table-column-sorter-down {
  margin-top: .125em
}

.ant-table-thead>tr>th.ant-table-column-has-actions {
  position: relative;
  background-clip: padding-box;
  -webkit-background-clip: border-box
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters {
  padding-right: 30px !important
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters .ant-table-filter-icon.ant-table-filter-open,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters .anticon-filter.ant-table-filter-open,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters:hover .ant-table-filter-icon:hover,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters:hover .anticon-filter:hover {
  color: rgba(0, 0, 0, .45);
  background: #e5e5e5
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters:hover .ant-table-filter-icon:active,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-filters:hover .anticon-filter:active {
  color: rgba(0, 0, 0, .65)
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters {
  cursor: pointer
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters:hover,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters:hover .ant-table-filter-icon,
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters:hover .anticon-filter {
  background: #f2f2f2
}

.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters:active .ant-table-column-sorter-down:not(.on),
.ant-table-thead>tr>th.ant-table-column-has-actions.ant-table-column-has-sorters:active .ant-table-column-sorter-up:not(.on) {
  color: rgba(0, 0, 0, .45)
}

.ant-table-thead>tr>th .ant-table-header-column {
  display: inline-block;
  max-width: 100%;
  vertical-align: top
}

.ant-table-thead>tr>th .ant-table-header-column .ant-table-column-sorters {
  display: table
}

.ant-table-thead>tr>th .ant-table-header-column .ant-table-column-sorters>.ant-table-column-title {
  display: table-cell;
  vertical-align: middle
}

.ant-table-thead>tr>th .ant-table-header-column .ant-table-column-sorters>:not(.ant-table-column-sorter) {
  position: relative
}

.ant-table-thead>tr>th .ant-table-header-column .ant-table-column-sorters:before {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: transparent;
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-table-thead>tr>th .ant-table-header-column .ant-table-column-sorters:hover:before {
  background: rgba(0, 0, 0, .04)
}

.ant-table-thead>tr>th.ant-table-column-has-sorters {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-table-thead>tr:first-child>th:first-child {
  border-top-left-radius: 4px
}

.ant-table-thead>tr:first-child>th:last-child {
  border-top-right-radius: 4px
}

.ant-table-thead>tr:not(:last-child)>th[colspan] {
  border-bottom: 0
}

.ant-table-tbody>tr>td {
  border-bottom: 1px solid #e8e8e8;
  -webkit-transition: all .3s, border 0s;
  transition: all .3s, border 0s
}

.ant-table-tbody>tr,
.ant-table-thead>tr {
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-table-tbody>tr.ant-table-row-hover:not(.ant-table-expanded-row):not(.ant-table-row-selected)>td,
.ant-table-tbody>tr:hover:not(.ant-table-expanded-row):not(.ant-table-row-selected)>td,
.ant-table-thead>tr.ant-table-row-hover:not(.ant-table-expanded-row):not(.ant-table-row-selected)>td,
.ant-table-thead>tr:hover:not(.ant-table-expanded-row):not(.ant-table-row-selected)>td {
  background: #e6fbff
}

.ant-table-tbody>tr.ant-table-row-selected>td.ant-table-column-sort,
.ant-table-tbody>tr:hover.ant-table-row-selected>td,
.ant-table-tbody>tr:hover.ant-table-row-selected>td.ant-table-column-sort,
.ant-table-thead>tr.ant-table-row-selected>td.ant-table-column-sort,
.ant-table-thead>tr:hover.ant-table-row-selected>td,
.ant-table-thead>tr:hover.ant-table-row-selected>td.ant-table-column-sort {
  background: #fafafa
}

.ant-table-thead>tr:hover {
  background: none
}

.ant-table-footer {
  position: relative;
  padding: 16px;
  color: rgba(0, 0, 0, .85);
  background: #fafafa;
  border-top: 1px solid #e8e8e8;
  border-radius: 0 0 4px 4px
}

.ant-table-footer:before {
  position: absolute;
  top: -1px;
  left: 0;
  width: 100%;
  height: 1px;
  background: #fafafa;
  content: ""
}

.ant-table.ant-table-bordered .ant-table-footer {
  border: 1px solid #e8e8e8
}

.ant-table-title {
  position: relative;
  top: 1px;
  padding: 16px 0;
  border-radius: 4px 4px 0 0
}

.ant-table.ant-table-bordered .ant-table-title {
  padding-right: 16px;
  padding-left: 16px;
  border: 1px solid #e8e8e8
}

.ant-table-title+.ant-table-content {
  position: relative;
  border-radius: 4px 4px 0 0
}

.ant-table-bordered .ant-table-title+.ant-table-content,
.ant-table-bordered .ant-table-title+.ant-table-content .ant-table-thead>tr:first-child>th,
.ant-table-bordered .ant-table-title+.ant-table-content table,
.ant-table-without-column-header .ant-table-title+.ant-table-content,
.ant-table-without-column-header table {
  border-radius: 0
}

.ant-table-without-column-header.ant-table-bordered.ant-table-empty .ant-table-placeholder {
  border-top: 1px solid #e8e8e8;
  border-radius: 4px
}

.ant-table-tbody>tr.ant-table-row-selected td {
  color: inherit;
  background: #fafafa
}

.ant-table-thead>tr>th.ant-table-column-sort {
  background: #f5f5f5
}

.ant-table-tbody>tr>td.ant-table-column-sort {
  background: rgba(0, 0, 0, .01)
}

.ant-table-tbody>tr>td,
.ant-table-thead>tr>th {
  padding: 16px;
  overflow-wrap: break-word
}

.ant-table-expand-icon-th,
.ant-table-row-expand-icon-cell {
  width: 50px;
  min-width: 50px;
  text-align: center
}

.ant-table-header {
  overflow: hidden;
  background: #fafafa
}

.ant-table-header table {
  border-radius: 4px 4px 0 0
}

.ant-table-loading {
  position: relative
}

.ant-table-loading .ant-table-body {
  background: #fff;
  opacity: .5
}

.ant-table-loading .ant-table-spin-holder {
  position: absolute;
  top: 50%;
  left: 50%;
  height: 20px;
  margin-left: -30px;
  line-height: 20px
}

.ant-table-loading .ant-table-with-pagination {
  margin-top: -20px
}

.ant-table-loading .ant-table-without-pagination {
  margin-top: 10px
}

.ant-table-bordered .ant-table-body>table,
.ant-table-bordered .ant-table-fixed-left table,
.ant-table-bordered .ant-table-fixed-right table,
.ant-table-bordered .ant-table-header>table {
  border: 1px solid #e8e8e8;
  border-right: 0;
  border-bottom: 0
}

.ant-table-bordered.ant-table-empty .ant-table-placeholder {
  border-right: 1px solid #e8e8e8;
  border-left: 1px solid #e8e8e8
}

.ant-table-bordered.ant-table-fixed-header .ant-table-header>table {
  border-bottom: 0
}

.ant-table-bordered.ant-table-fixed-header .ant-table-body>table {
  border-top-left-radius: 0;
  border-top-right-radius: 0
}

.ant-table-bordered.ant-table-fixed-header .ant-table-body-inner>table,
.ant-table-bordered.ant-table-fixed-header .ant-table-header+.ant-table-body>table {
  border-top: 0
}

.ant-table-bordered .ant-table-thead>tr:not(:last-child)>th {
  border-bottom: 1px solid #e8e8e8
}

.ant-table-bordered .ant-table-tbody>tr>td,
.ant-table-bordered .ant-table-thead>tr>th {
  border-right: 1px solid #e8e8e8
}

.ant-table-placeholder {
  position: relative;
  z-index: 1;
  margin-top: -1px;
  padding: 16px;
  color: rgba(0, 0, 0, .25);
  font-size: 14px;
  text-align: center;
  background: #fff;
  border-top: 1px solid #e8e8e8;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 0 0 4px 4px
}

.ant-table-pagination.ant-pagination {
  float: right;
  margin: 16px 0
}

.ant-table-filter-dropdown {
  position: relative;
  min-width: 96px;
  margin-left: -8px;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-table-filter-dropdown .ant-dropdown-menu {
  border: 0;
  border-radius: 4px 4px 0 0;
  box-shadow: none
}

.ant-table-filter-dropdown .ant-dropdown-menu-without-submenu {
  max-height: 400px;
  overflow-x: hidden
}

.ant-table-filter-dropdown .ant-dropdown-menu-item>label+span {
  padding-right: 0
}

.ant-table-filter-dropdown .ant-dropdown-menu-sub {
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-table-filter-dropdown .ant-dropdown-menu .ant-dropdown-submenu-contain-selected .ant-dropdown-menu-submenu-title:after {
  color: #03a9f4;
  font-weight: 700;
  text-shadow: 0 0 2px #a6efff
}

.ant-table-filter-dropdown .ant-dropdown-menu-item {
  overflow: hidden
}

.ant-table-filter-dropdown>.ant-dropdown-menu>.ant-dropdown-menu-item:last-child,
.ant-table-filter-dropdown>.ant-dropdown-menu>.ant-dropdown-menu-submenu:last-child .ant-dropdown-menu-submenu-title {
  border-radius: 0
}

.ant-table-filter-dropdown-btns {
  padding: 7px 8px;
  overflow: hidden;
  border-top: 1px solid #e8e8e8
}

.ant-table-filter-dropdown-link {
  color: #03a9f4
}

.ant-table-filter-dropdown-link:hover {
  color: #2bc3ff
}

.ant-table-filter-dropdown-link:active {
  color: #0086cf
}

.ant-table-filter-dropdown-link.confirm {
  float: left
}

.ant-table-filter-dropdown-link.clear {
  float: right
}

.ant-table-selection {
  white-space: nowrap
}

.ant-table-selection-select-all-custom {
  margin-right: 4px !important
}

.ant-table-selection .anticon-down {
  color: #bfbfbf;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-table-selection-menu {
  min-width: 96px;
  margin-top: 5px;
  margin-left: -30px;
  background: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-table-selection-menu .ant-action-down {
  color: #bfbfbf
}

.ant-table-selection-down {
  display: inline-block;
  padding: 0;
  line-height: 1;
  cursor: pointer
}

.ant-table-selection-down:hover .anticon-down {
  color: rgba(0, 0, 0, .6)
}

.ant-table-row-expand-icon {
  color: #03a9f4;
  text-decoration: none;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s;
  display: inline-block;
  width: 17px;
  height: 17px;
  color: inherit;
  line-height: 13px;
  text-align: center;
  background: #fff;
  border: 1px solid #e8e8e8;
  border-radius: 2px;
  outline: none;
  -webkit-transition: all .3s;
  transition: all .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-table-row-expand-icon:focus,
.ant-table-row-expand-icon:hover {
  color: #2bc3ff
}

.ant-table-row-expand-icon:active {
  color: #0086cf
}

.ant-table-row-expand-icon:active,
.ant-table-row-expand-icon:focus,
.ant-table-row-expand-icon:hover {
  border-color: currentColor
}

.ant-table-row-expanded:after {
  content: "-"
}

.ant-table-row-collapsed:after {
  content: "+"
}

.ant-table-row-spaced {
  visibility: hidden
}

.ant-table-row-spaced:after {
  content: "."
}

.ant-table-row-cell-ellipsis,
.ant-table-row-cell-ellipsis .ant-table-column-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-table-row-cell-ellipsis .ant-table-column-title {
  display: block
}

.ant-table-row-cell-break-word {
  word-wrap: break-word;
  word-break: break-word
}

tr.ant-table-expanded-row,
tr.ant-table-expanded-row:hover {
  background: #fbfbfb
}

tr.ant-table-expanded-row td>.ant-table-wrapper {
  margin: -16px -16px -17px
}

.ant-table .ant-table-row-indent+.ant-table-row-expand-icon {
  margin-right: 8px
}

.ant-table-scroll {
  overflow: auto;
  overflow-x: hidden
}

.ant-table-scroll table {
  min-width: 100%
}

.ant-table-scroll table .ant-table-fixed-columns-in-body {
  visibility: hidden
}

.ant-table-body-inner {
  height: 100%
}

.ant-table-fixed-header>.ant-table-content>.ant-table-scroll>.ant-table-body {
  position: relative;
  background: #fff
}

.ant-table-fixed-header .ant-table-body-inner {
  overflow: scroll
}

.ant-table-fixed-header .ant-table-scroll .ant-table-header {
  margin-bottom: -20px;
  padding-bottom: 20px;
  overflow: scroll;
  opacity: .9999
}

.ant-table-fixed-header .ant-table-scroll .ant-table-header::-webkit-scrollbar {
  border: solid #e8e8e8;
  border-width: 0 0 1px
}

.ant-table-hide-scrollbar {
  scrollbar-color: transparent transparent
}

.ant-table-hide-scrollbar::-webkit-scrollbar {
  background-color: transparent
}

.ant-table-bordered.ant-table-fixed-header .ant-table-scroll .ant-table-header::-webkit-scrollbar {
  border: 1px solid #e8e8e8;
  border-left-width: 0
}

.ant-table-bordered.ant-table-fixed-header .ant-table-scroll .ant-table-header.ant-table-hide-scrollbar .ant-table-thead>tr:only-child>th:last-child {
  border-right-color: transparent
}

.ant-table-fixed-left,
.ant-table-fixed-right {
  position: absolute;
  top: 0;
  z-index: auto;
  overflow: hidden;
  border-radius: 0;
  -webkit-transition: box-shadow .3s ease;
  transition: box-shadow .3s ease
}

.ant-table-fixed-left table,
.ant-table-fixed-right table {
  width: auto;
  background: #fff
}

.ant-table-fixed-header .ant-table-fixed-left .ant-table-body-outer .ant-table-fixed,
.ant-table-fixed-header .ant-table-fixed-right .ant-table-body-outer .ant-table-fixed {
  border-radius: 0
}

.ant-table-fixed-left {
  left: 0;
  box-shadow: 6px 0 6px -4px rgba(0, 0, 0, .15)
}

.ant-table-fixed-left .ant-table-header {
  overflow-y: hidden
}

.ant-table-fixed-left .ant-table-body-inner {
  margin-right: -20px;
  padding-right: 20px
}

.ant-table-fixed-header .ant-table-fixed-left .ant-table-body-inner {
  padding-right: 0
}

.ant-table-fixed-left,
.ant-table-fixed-left table {
  border-radius: 4px 0 0 0
}

.ant-table-fixed-left .ant-table-thead>tr>th:last-child {
  border-top-right-radius: 0
}

.ant-table-fixed-right {
  right: 0;
  box-shadow: -6px 0 6px -4px rgba(0, 0, 0, .15)
}

.ant-table-fixed-right,
.ant-table-fixed-right table {
  border-radius: 0 4px 0 0
}

.ant-table-fixed-right .ant-table-expanded-row {
  color: transparent;
  pointer-events: none
}

.ant-table-fixed-right .ant-table-thead>tr>th:first-child {
  border-top-left-radius: 0
}

.ant-table.ant-table-scroll-position-left .ant-table-fixed-left,
.ant-table.ant-table-scroll-position-right .ant-table-fixed-right {
  box-shadow: none
}

.ant-table colgroup>col.ant-table-selection-col {
  width: 60px
}

.ant-table-thead>tr>th.ant-table-selection-column-custom .ant-table-selection {
  margin-right: -15px
}

.ant-table-tbody>tr>td.ant-table-selection-column,
.ant-table-thead>tr>th.ant-table-selection-column {
  text-align: center
}

.ant-table-tbody>tr>td.ant-table-selection-column .ant-radio-wrapper,
.ant-table-thead>tr>th.ant-table-selection-column .ant-radio-wrapper {
  margin-right: 0
}

.ant-table-row[class*=ant-table-row-level-0] .ant-table-selection-column>span {
  display: inline-block
}

.ant-table-filter-dropdown-submenu .ant-checkbox-wrapper+span,
.ant-table-filter-dropdown .ant-checkbox-wrapper+span {
  padding-left: 8px
}

@supports (-moz-appearance:meterbar) {
  .ant-table-thead>tr>th.ant-table-column-has-actions {
    background-clip: padding-box
  }
}

.ant-table-middle>.ant-table-content>.ant-table-body>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-middle>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-middle>.ant-table-footer,
.ant-table-middle>.ant-table-title {
  padding: 12px 8px
}

.ant-table-middle tr.ant-table-expanded-row td>.ant-table-wrapper {
  margin: -12px -8px -13px
}

.ant-table-small {
  border: 1px solid #e8e8e8;
  border-radius: 4px
}

.ant-table-small>.ant-table-footer,
.ant-table-small>.ant-table-title {
  padding: 8px
}

.ant-table-small>.ant-table-title {
  top: 0;
  border-bottom: 1px solid #e8e8e8
}

.ant-table-small>.ant-table-content>.ant-table-body {
  margin: 0 8px
}

.ant-table-small>.ant-table-content>.ant-table-body>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table,
.ant-table-small>.ant-table-content>.ant-table-header>table,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table {
  border: 0
}

.ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-tbody>tr>td,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-thead>tr>th {
  padding: 8px
}

.ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-header>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-thead>tr>th,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-thead>tr>th {
  background-color: transparent
}

.ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-header>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-thead>tr,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-thead>tr {
  border-bottom: 1px solid #e8e8e8
}

.ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-header>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table>.ant-table-thead>tr>th.ant-table-column-sort,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table>.ant-table-thead>tr>th.ant-table-column-sort {
  background-color: rgba(0, 0, 0, .01)
}

.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-body-outer>.ant-table-body-inner>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-left>.ant-table-header>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-body-outer>.ant-table-body-inner>table,
.ant-table-small>.ant-table-content>.ant-table-fixed-right>.ant-table-header>table,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-body>table,
.ant-table-small>.ant-table-content>.ant-table-scroll>.ant-table-header>table {
  padding: 0
}

.ant-table-small>.ant-table-content .ant-table-header {
  background-color: #fff;
  border-radius: 4px 4px 0 0
}

.ant-table-small>.ant-table-content .ant-table-placeholder,
.ant-table-small>.ant-table-content .ant-table-row:last-child td {
  border-bottom: 0
}

.ant-table-small.ant-table-bordered {
  border-right: 0
}

.ant-table-small.ant-table-bordered .ant-table-title {
  border: 0;
  border-right: 1px solid #e8e8e8;
  border-bottom: 1px solid #e8e8e8
}

.ant-table-small.ant-table-bordered .ant-table-content {
  border-right: 1px solid #e8e8e8
}

.ant-table-small.ant-table-bordered .ant-table-footer {
  border: 0;
  border-top: 1px solid #e8e8e8;
  border-right: 1px solid #e8e8e8
}

.ant-table-small.ant-table-bordered .ant-table-footer:before {
  display: none
}

.ant-table-small.ant-table-bordered .ant-table-placeholder {
  border-right: 0;
  border-bottom: 0;
  border-left: 0
}

.ant-table-small.ant-table-bordered .ant-table-tbody>tr>td:last-child,
.ant-table-small.ant-table-bordered .ant-table-thead>tr:only-child>th:last-child {
  border-right: none
}

.ant-table-small.ant-table-bordered .ant-table-fixed-left .ant-table-tbody>tr>td:last-child,
.ant-table-small.ant-table-bordered .ant-table-fixed-left .ant-table-thead>tr>th:last-child {
  border-right: 1px solid #e8e8e8
}

.ant-table-small.ant-table-bordered .ant-table-fixed-right {
  border-right: 1px solid #e8e8e8;
  border-left: 1px solid #e8e8e8
}

.ant-table-small tr.ant-table-expanded-row td>.ant-table-wrapper {
  margin: -8px -8px -9px
}

.ant-table-small.ant-table-fixed-header>.ant-table-content>.ant-table-scroll>.ant-table-body {
  border-radius: 0 0 4px 4px
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-nav-container {
  height: 40px
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-ink-bar {
  visibility: hidden
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab {
  height: 40px;
  margin: 0 2px 0 0;
  padding: 0 16px;
  line-height: 38px;
  background: #fafafa;
  border: 1px solid #e8e8e8;
  border-radius: 4px 4px 0 0;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab-active {
  height: 40px;
  color: #03a9f4;
  background: #fff;
  border-color: #e8e8e8;
  border-bottom: 1px solid #fff
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab-active:before {
  border-top: 2px solid transparent
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab-disabled {
  color: #03a9f4;
  color: rgba(0, 0, 0, .25)
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab-inactive {
  padding: 0
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-nav-wrap {
  margin-bottom: 0
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab .ant-tabs-close-x {
  width: 16px;
  height: 16px;
  height: 14px;
  margin-right: -5px;
  margin-left: 3px;
  overflow: hidden;
  color: rgba(0, 0, 0, .45);
  font-size: 12px;
  vertical-align: middle;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab .ant-tabs-close-x:hover {
  color: rgba(0, 0, 0, .85)
}

.ant-tabs.ant-tabs-card .ant-tabs-card-content>.ant-tabs-tabpane,
.ant-tabs.ant-tabs-editable-card .ant-tabs-card-content>.ant-tabs-tabpane {
  -webkit-transition: none !important;
  transition: none !important
}

.ant-tabs.ant-tabs-card .ant-tabs-card-content>.ant-tabs-tabpane-inactive,
.ant-tabs.ant-tabs-editable-card .ant-tabs-card-content>.ant-tabs-tabpane-inactive {
  overflow: hidden
}

.ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab:hover .anticon-close {
  opacity: 1
}

.ant-tabs-extra-content {
  line-height: 45px
}

.ant-tabs-extra-content .ant-tabs-new-tab {
  position: relative;
  width: 20px;
  height: 20px;
  color: rgba(0, 0, 0, .65);
  font-size: 12px;
  line-height: 20px;
  text-align: center;
  border: 1px solid #e8e8e8;
  border-radius: 2px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-tabs-extra-content .ant-tabs-new-tab:hover {
  color: #03a9f4;
  border-color: #03a9f4
}

.ant-tabs-extra-content .ant-tabs-new-tab svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.ant-tabs.ant-tabs-large .ant-tabs-extra-content {
  line-height: 56px
}

.ant-tabs.ant-tabs-small .ant-tabs-extra-content {
  line-height: 37px
}

.ant-tabs.ant-tabs-card .ant-tabs-extra-content {
  line-height: 40px
}

.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-nav-container,
.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-nav-container {
  height: 100%
}

.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-tab,
.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-tab {
  margin-bottom: 8px;
  border-bottom: 1px solid #e8e8e8
}

.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-tab-active,
.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-tab-active {
  padding-bottom: 4px
}

.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-tab:last-child,
.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-tab:last-child {
  margin-bottom: 8px
}

.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-new-tab,
.ant-tabs-vertical.ant-tabs-card .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-new-tab {
  width: 90%
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-left .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-nav-wrap {
  margin-right: 0
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-left .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-tab {
  margin-right: 1px;
  border-right: 0;
  border-radius: 4px 0 0 4px
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-left .ant-tabs-card-bar.ant-tabs-left-bar .ant-tabs-tab-active {
  margin-right: -1px;
  padding-right: 18px
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-right .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-nav-wrap {
  margin-left: 0
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-right .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-tab {
  margin-left: 1px;
  border-left: 0;
  border-radius: 0 4px 4px 0
}

.ant-tabs-vertical.ant-tabs-card.ant-tabs-right .ant-tabs-card-bar.ant-tabs-right-bar .ant-tabs-tab-active {
  margin-left: -1px;
  padding-left: 18px
}

.ant-tabs .ant-tabs-card-bar.ant-tabs-bottom-bar .ant-tabs-tab {
  height: auto;
  border-top: 0;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 0 0 4px 4px
}

.ant-tabs .ant-tabs-card-bar.ant-tabs-bottom-bar .ant-tabs-tab-active {
  padding-top: 1px;
  padding-bottom: 0;
  color: #03a9f4
}

.ant-tabs {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  overflow: hidden;
  zoom: 1
}

.ant-tabs:after,
.ant-tabs:before {
  display: table;
  content: ""
}

.ant-tabs:after {
  clear: both
}

.ant-tabs-ink-bar {
  position: absolute;
  bottom: 1px;
  left: 0;
  z-index: 1;
  box-sizing: border-box;
  height: 2px;
  background-color: #03a9f4;
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0
}

.ant-tabs-bar {
  margin: 0 0 16px;
  border-bottom: 1px solid #e8e8e8;
  outline: none
}

.ant-tabs-bar,
.ant-tabs-nav-container {
  -webkit-transition: padding .3s cubic-bezier(.645, .045, .355, 1);
  transition: padding .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs-nav-container {
  position: relative;
  box-sizing: border-box;
  margin-bottom: -1px;
  overflow: hidden;
  font-size: 14px;
  line-height: 1.5;
  white-space: nowrap;
  zoom: 1
}

.ant-tabs-nav-container:after,
.ant-tabs-nav-container:before {
  display: table;
  content: ""
}

.ant-tabs-nav-container:after {
  clear: both
}

.ant-tabs-nav-container-scrolling {
  padding-right: 32px;
  padding-left: 32px
}

.ant-tabs-bottom .ant-tabs-bottom-bar {
  margin-top: 16px;
  margin-bottom: 0;
  border-top: 1px solid #e8e8e8;
  border-bottom: none
}

.ant-tabs-bottom .ant-tabs-bottom-bar .ant-tabs-ink-bar {
  top: 1px;
  bottom: auto
}

.ant-tabs-bottom .ant-tabs-bottom-bar .ant-tabs-nav-container {
  margin-top: -1px;
  margin-bottom: 0
}

.ant-tabs-tab-next,
.ant-tabs-tab-prev {
  position: absolute;
  z-index: 2;
  width: 0;
  height: 100%;
  color: rgba(0, 0, 0, .45);
  text-align: center;
  background-color: transparent;
  border: 0;
  cursor: pointer;
  opacity: 0;
  -webkit-transition: width .3s cubic-bezier(.645, .045, .355, 1), opacity .3s cubic-bezier(.645, .045, .355, 1), color .3s cubic-bezier(.645, .045, .355, 1);
  transition: width .3s cubic-bezier(.645, .045, .355, 1), opacity .3s cubic-bezier(.645, .045, .355, 1), color .3s cubic-bezier(.645, .045, .355, 1);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  pointer-events: none
}

.ant-tabs-tab-next.ant-tabs-tab-arrow-show,
.ant-tabs-tab-prev.ant-tabs-tab-arrow-show {
  width: 32px;
  height: 100%;
  opacity: 1;
  pointer-events: auto
}

.ant-tabs-tab-next:hover,
.ant-tabs-tab-prev:hover {
  color: rgba(0, 0, 0, .65)
}

.ant-tabs-tab-next-icon,
.ant-tabs-tab-prev-icon {
  position: absolute;
  top: 50%;
  left: 50%;
  font-weight: 700;
  font-style: normal;
  font-variant: normal;
  line-height: inherit;
  text-align: center;
  text-transform: none;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%)
}

.ant-tabs-tab-next-icon-target,
.ant-tabs-tab-prev-icon-target {
  display: block;
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg)
}

:root .ant-tabs-tab-next-icon-target,
:root .ant-tabs-tab-prev-icon-target {
  font-size: 12px
}

.ant-tabs-tab-btn-disabled {
  cursor: not-allowed
}

.ant-tabs-tab-btn-disabled,
.ant-tabs-tab-btn-disabled:hover {
  color: rgba(0, 0, 0, .25)
}

.ant-tabs-tab-next {
  right: 2px
}

.ant-tabs-tab-prev {
  left: 0
}

:root .ant-tabs-tab-prev {
  -webkit-filter: none;
  filter: none
}

.ant-tabs-nav-wrap {
  margin-bottom: -1px;
  overflow: hidden
}

.ant-tabs-nav-scroll {
  overflow: hidden;
  white-space: nowrap
}

.ant-tabs-nav {
  position: relative;
  display: inline-block;
  box-sizing: border-box;
  margin: 0;
  padding-left: 0;
  list-style: none;
  -webkit-transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs-nav:after,
.ant-tabs-nav:before {
  display: table;
  content: " "
}

.ant-tabs-nav:after {
  clear: both
}

.ant-tabs-nav .ant-tabs-tab {
  position: relative;
  display: inline-block;
  box-sizing: border-box;
  height: 100%;
  margin: 0 32px 0 0;
  padding: 12px 16px;
  text-decoration: none;
  cursor: pointer;
  -webkit-transition: color .3s cubic-bezier(.645, .045, .355, 1);
  transition: color .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs-nav .ant-tabs-tab:before {
  position: absolute;
  top: -1px;
  left: 0;
  width: 100%;
  border-top: 2px solid transparent;
  border-radius: 4px 4px 0 0;
  -webkit-transition: all .3s;
  transition: all .3s;
  content: "";
  pointer-events: none
}

.ant-tabs-nav .ant-tabs-tab:last-child {
  margin-right: 0
}

.ant-tabs-nav .ant-tabs-tab:hover {
  color: #2bc3ff
}

.ant-tabs-nav .ant-tabs-tab:active {
  color: #0086cf
}

.ant-tabs-nav .ant-tabs-tab .anticon {
  margin-right: 8px
}

.ant-tabs-nav .ant-tabs-tab-active {
  color: #03a9f4;
  font-weight: 500
}

.ant-tabs-nav .ant-tabs-tab-disabled,
.ant-tabs-nav .ant-tabs-tab-disabled:hover {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-tabs .ant-tabs-large-bar .ant-tabs-nav-container {
  font-size: 16px
}

.ant-tabs .ant-tabs-large-bar .ant-tabs-tab {
  padding: 16px
}

.ant-tabs .ant-tabs-small-bar .ant-tabs-nav-container {
  font-size: 14px
}

.ant-tabs .ant-tabs-small-bar .ant-tabs-tab {
  padding: 8px 16px
}

.ant-tabs-content:before {
  display: block;
  overflow: hidden;
  content: ""
}

.ant-tabs .ant-tabs-bottom-content,
.ant-tabs .ant-tabs-top-content {
  width: 100%
}

.ant-tabs .ant-tabs-bottom-content>.ant-tabs-tabpane,
.ant-tabs .ant-tabs-top-content>.ant-tabs-tabpane {
  flex-shrink: 0;
  width: 100%;
  opacity: 1;
  -webkit-transition: opacity .45s;
  transition: opacity .45s
}

.ant-tabs .ant-tabs-bottom-content>.ant-tabs-tabpane-inactive,
.ant-tabs .ant-tabs-top-content>.ant-tabs-tabpane-inactive {
  height: 0;
  padding: 0 !important;
  overflow: hidden;
  opacity: 0;
  pointer-events: none
}

.ant-tabs .ant-tabs-bottom-content>.ant-tabs-tabpane-inactive input,
.ant-tabs .ant-tabs-top-content>.ant-tabs-tabpane-inactive input {
  visibility: hidden
}

.ant-tabs .ant-tabs-bottom-content.ant-tabs-content-animated,
.ant-tabs .ant-tabs-top-content.ant-tabs-content-animated {
  display: flex;
  flex-direction: row;
  -webkit-transition: margin-left .3s cubic-bezier(.645, .045, .355, 1);
  transition: margin-left .3s cubic-bezier(.645, .045, .355, 1);
  will-change: margin-left
}

.ant-tabs .ant-tabs-left-bar,
.ant-tabs .ant-tabs-right-bar {
  height: 100%;
  border-bottom: 0
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab-arrow-show,
.ant-tabs .ant-tabs-right-bar .ant-tabs-tab-arrow-show {
  width: 100%;
  height: 32px
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab,
.ant-tabs .ant-tabs-right-bar .ant-tabs-tab {
  display: block;
  float: none;
  margin: 0 0 16px;
  padding: 8px 24px
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab:last-child,
.ant-tabs .ant-tabs-right-bar .ant-tabs-tab:last-child {
  margin-bottom: 0
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-extra-content,
.ant-tabs .ant-tabs-right-bar .ant-tabs-extra-content {
  text-align: center
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-scroll,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-scroll {
  width: auto
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-container,
.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-wrap,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-container,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-wrap {
  height: 100%
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-container,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-container {
  margin-bottom: 0
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-container.ant-tabs-nav-container-scrolling,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-container.ant-tabs-nav-container-scrolling {
  padding: 32px 0
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-wrap,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-wrap {
  margin-bottom: 0
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav {
  width: 100%
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-ink-bar,
.ant-tabs .ant-tabs-right-bar .ant-tabs-ink-bar {
  top: 0;
  bottom: auto;
  left: auto;
  width: 2px;
  height: auto
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab-next,
.ant-tabs .ant-tabs-right-bar .ant-tabs-tab-next {
  right: 0;
  bottom: 0;
  width: 100%;
  height: 32px
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab-prev,
.ant-tabs .ant-tabs-right-bar .ant-tabs-tab-prev {
  top: 0;
  width: 100%;
  height: 32px
}

.ant-tabs .ant-tabs-left-content,
.ant-tabs .ant-tabs-right-content {
  width: auto;
  margin-top: 0 !important;
  overflow: hidden
}

.ant-tabs .ant-tabs-left-bar {
  float: left;
  margin-right: -1px;
  margin-bottom: 0;
  border-right: 1px solid #e8e8e8
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-tab {
  text-align: right
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-container,
.ant-tabs .ant-tabs-left-bar .ant-tabs-nav-wrap {
  margin-right: -1px
}

.ant-tabs .ant-tabs-left-bar .ant-tabs-ink-bar {
  right: 1px
}

.ant-tabs .ant-tabs-left-content {
  padding-left: 24px;
  border-left: 1px solid #e8e8e8
}

.ant-tabs .ant-tabs-right-bar {
  float: right;
  margin-bottom: 0;
  margin-left: -1px;
  border-left: 1px solid #e8e8e8
}

.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-container,
.ant-tabs .ant-tabs-right-bar .ant-tabs-nav-wrap {
  margin-left: -1px
}

.ant-tabs .ant-tabs-right-bar .ant-tabs-ink-bar {
  left: 1px
}

.ant-tabs .ant-tabs-right-content {
  padding-right: 24px;
  border-right: 1px solid #e8e8e8
}

.ant-tabs-bottom .ant-tabs-ink-bar-animated,
.ant-tabs-top .ant-tabs-ink-bar-animated {
  -webkit-transition: width .3s cubic-bezier(.645, .045, .355, 1), left .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: width .3s cubic-bezier(.645, .045, .355, 1), left .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), width .3s cubic-bezier(.645, .045, .355, 1), left .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), width .3s cubic-bezier(.645, .045, .355, 1), left .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs-left .ant-tabs-ink-bar-animated,
.ant-tabs-right .ant-tabs-ink-bar-animated {
  -webkit-transition: height .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: height .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), height .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1);
  transition: transform .3s cubic-bezier(.645, .045, .355, 1), height .3s cubic-bezier(.645, .045, .355, 1), top .3s cubic-bezier(.645, .045, .355, 1), -webkit-transform .3s cubic-bezier(.645, .045, .355, 1)
}

.ant-tabs-no-animation>.ant-tabs-content>.ant-tabs-content-animated,
.no-flex>.ant-tabs-content>.ant-tabs-content-animated {
  margin-left: 0 !important;
  -webkit-transform: none !important;
  transform: none !important
}

.ant-tabs-no-animation>.ant-tabs-content>.ant-tabs-tabpane-inactive,
.no-flex>.ant-tabs-content>.ant-tabs-tabpane-inactive {
  height: 0;
  padding: 0 !important;
  overflow: hidden;
  opacity: 0;
  pointer-events: none
}

.ant-tabs-no-animation>.ant-tabs-content>.ant-tabs-tabpane-inactive input,
.no-flex>.ant-tabs-content>.ant-tabs-tabpane-inactive input {
  visibility: hidden
}

.ant-tabs-left-content>.ant-tabs-content-animated,
.ant-tabs-right-content>.ant-tabs-content-animated {
  margin-left: 0 !important;
  -webkit-transform: none !important;
  transform: none !important
}

.ant-tabs-left-content>.ant-tabs-tabpane-inactive,
.ant-tabs-right-content>.ant-tabs-tabpane-inactive {
  height: 0;
  padding: 0 !important;
  overflow: hidden;
  opacity: 0;
  pointer-events: none
}

.ant-tabs-left-content>.ant-tabs-tabpane-inactive input,
.ant-tabs-right-content>.ant-tabs-tabpane-inactive input {
  visibility: hidden
}

.ant-tag {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  height: auto;
  margin: 0 8px 0 0;
  padding: 0 7px;
  font-size: 12px;
  line-height: 20px;
  white-space: nowrap;
  background: #fafafa;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  cursor: default;
  opacity: 1;
  -webkit-transition: all .3s cubic-bezier(.78, .14, .15, .86);
  transition: all .3s cubic-bezier(.78, .14, .15, .86)
}

.ant-tag:hover {
  opacity: .85
}

.ant-tag,
.ant-tag a,
.ant-tag a:hover {
  color: rgba(0, 0, 0, .65)
}

.ant-tag>a:first-child:last-child {
  display: inline-block;
  margin: 0 -8px;
  padding: 0 8px
}

.ant-tag .anticon-close {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  margin-left: 3px;
  color: rgba(0, 0, 0, .45);
  font-weight: 700;
  cursor: pointer;
  -webkit-transition: all .3s cubic-bezier(.78, .14, .15, .86);
  transition: all .3s cubic-bezier(.78, .14, .15, .86)
}

:root .ant-tag .anticon-close {
  font-size: 12px
}

.ant-tag .anticon-close:hover {
  color: rgba(0, 0, 0, .85)
}

.ant-tag-has-color {
  border-color: transparent
}

.ant-tag-has-color,
.ant-tag-has-color .anticon-close,
.ant-tag-has-color .anticon-close:hover,
.ant-tag-has-color a,
.ant-tag-has-color a:hover {
  color: #fff
}

.ant-tag-checkable {
  background-color: transparent;
  border-color: transparent
}

.ant-tag-checkable:not(.ant-tag-checkable-checked):hover {
  color: #03a9f4
}

.ant-tag-checkable-checked,
.ant-tag-checkable:active {
  color: #fff
}

.ant-tag-checkable-checked {
  background-color: #03a9f4
}

.ant-tag-checkable:active {
  background-color: #0086cf
}

.ant-tag-hidden {
  display: none
}

.ant-tag-pink {
  color: #eb2f96;
  background: #fff0f6;
  border-color: #ffadd2
}

.ant-tag-pink-inverse {
  color: #fff;
  background: #eb2f96;
  border-color: #eb2f96
}

.ant-tag-magenta {
  color: #eb2f96;
  background: #fff0f6;
  border-color: #ffadd2
}

.ant-tag-magenta-inverse {
  color: #fff;
  background: #eb2f96;
  border-color: #eb2f96
}

.ant-tag-red {
  color: #f5222d;
  background: #fff1f0;
  border-color: #ffa39e
}

.ant-tag-red-inverse {
  color: #fff;
  background: #f5222d;
  border-color: #f5222d
}

.ant-tag-volcano {
  color: #fa541c;
  background: #fff2e8;
  border-color: #ffbb96
}

.ant-tag-volcano-inverse {
  color: #fff;
  background: #fa541c;
  border-color: #fa541c
}

.ant-tag-orange {
  color: #fa8c16;
  background: #fff7e6;
  border-color: #ffd591
}

.ant-tag-orange-inverse {
  color: #fff;
  background: #fa8c16;
  border-color: #fa8c16
}

.ant-tag-yellow {
  color: #fadb14;
  background: #feffe6;
  border-color: #fffb8f
}

.ant-tag-yellow-inverse {
  color: #fff;
  background: #fadb14;
  border-color: #fadb14
}

.ant-tag-gold {
  color: #faad14;
  background: #fffbe6;
  border-color: #ffe58f
}

.ant-tag-gold-inverse {
  color: #fff;
  background: #faad14;
  border-color: #faad14
}

.ant-tag-cyan {
  color: #13c2c2;
  background: #e6fffb;
  border-color: #87e8de
}

.ant-tag-cyan-inverse {
  color: #fff;
  background: #13c2c2;
  border-color: #13c2c2
}

.ant-tag-lime {
  color: #a0d911;
  background: #fcffe6;
  border-color: #eaff8f
}

.ant-tag-lime-inverse {
  color: #fff;
  background: #a0d911;
  border-color: #a0d911
}

.ant-tag-green {
  color: #52c41a;
  background: #f6ffed;
  border-color: #b7eb8f
}

.ant-tag-green-inverse {
  color: #fff;
  background: #52c41a;
  border-color: #52c41a
}

.ant-tag-blue {
  color: #1890ff;
  background: #e6f7ff;
  border-color: #91d5ff
}

.ant-tag-blue-inverse {
  color: #fff;
  background: #1890ff;
  border-color: #1890ff
}

.ant-tag-geekblue {
  color: #2f54eb;
  background: #f0f5ff;
  border-color: #adc6ff
}

.ant-tag-geekblue-inverse {
  color: #fff;
  background: #2f54eb;
  border-color: #2f54eb
}

.ant-tag-purple {
  color: #722ed1;
  background: #f9f0ff;
  border-color: #d3adf7
}

.ant-tag-purple-inverse {
  color: #fff;
  background: #722ed1;
  border-color: #722ed1
}

.ant-time-picker-panel {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  z-index: 1050;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol
}

.ant-time-picker-panel-inner {
  position: relative;
  left: -2px;
  font-size: 14px;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  border-radius: 4px;
  outline: none;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-time-picker-panel-input {
  width: 100%;
  max-width: 154px;
  margin: 0;
  padding: 0;
  line-height: normal;
  border: 0;
  outline: 0;
  cursor: auto
}

.ant-time-picker-panel-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-time-picker-panel-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-time-picker-panel-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-time-picker-panel-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-time-picker-panel-input-wrap {
  position: relative;
  padding: 7px 2px 7px 12px;
  border-bottom: 1px solid #e8e8e8
}

.ant-time-picker-panel-input-invalid {
  border-color: #f5222d
}

.ant-time-picker-panel-narrow .ant-time-picker-panel-input-wrap {
  max-width: 112px
}

.ant-time-picker-panel-select {
  position: relative;
  float: left;
  width: 56px;
  max-height: 192px;
  overflow: hidden;
  font-size: 14px;
  border-left: 1px solid #e8e8e8
}

.ant-time-picker-panel-select:hover {
  overflow-y: auto
}

.ant-time-picker-panel-select:first-child {
  margin-left: 0;
  border-left: 0
}

.ant-time-picker-panel-select:last-child {
  border-right: 0
}

.ant-time-picker-panel-select:only-child {
  width: 100%
}

.ant-time-picker-panel-select ul {
  width: 56px;
  margin: 0;
  padding: 0 0 160px;
  list-style: none
}

.ant-time-picker-panel-select li {
  width: 100%;
  height: 32px;
  margin: 0;
  padding: 0 0 0 12px;
  line-height: 32px;
  text-align: left;
  list-style: none;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-time-picker-panel-select li:focus {
  color: #03a9f4;
  font-weight: 600;
  outline: none
}

.ant-time-picker-panel-select li:hover {
  background: #e8f8ff
}

li.ant-time-picker-panel-select-option-selected {
  font-weight: 600;
  background: #f5f5f5
}

li.ant-time-picker-panel-select-option-selected:hover {
  background: #f5f5f5
}

li.ant-time-picker-panel-select-option-disabled {
  color: rgba(0, 0, 0, .25)
}

li.ant-time-picker-panel-select-option-disabled:hover {
  background: transparent;
  cursor: not-allowed
}

.ant-time-picker-panel-combobox {
  zoom: 1
}

.ant-time-picker-panel-combobox:after,
.ant-time-picker-panel-combobox:before {
  display: table;
  content: ""
}

.ant-time-picker-panel-combobox:after {
  clear: both
}

.ant-time-picker-panel-addon {
  padding: 8px;
  border-top: 1px solid #e8e8e8
}

.ant-time-picker-panel.slide-up-appear.slide-up-appear-active.ant-time-picker-panel-placement-topLeft,
.ant-time-picker-panel.slide-up-appear.slide-up-appear-active.ant-time-picker-panel-placement-topRight,
.ant-time-picker-panel.slide-up-enter.slide-up-enter-active.ant-time-picker-panel-placement-topLeft,
.ant-time-picker-panel.slide-up-enter.slide-up-enter-active.ant-time-picker-panel-placement-topRight {
  -webkit-animation-name: antSlideDownIn;
  animation-name: antSlideDownIn
}

.ant-time-picker-panel.slide-up-appear.slide-up-appear-active.ant-time-picker-panel-placement-bottomLeft,
.ant-time-picker-panel.slide-up-appear.slide-up-appear-active.ant-time-picker-panel-placement-bottomRight,
.ant-time-picker-panel.slide-up-enter.slide-up-enter-active.ant-time-picker-panel-placement-bottomLeft,
.ant-time-picker-panel.slide-up-enter.slide-up-enter-active.ant-time-picker-panel-placement-bottomRight {
  -webkit-animation-name: antSlideUpIn;
  animation-name: antSlideUpIn
}

.ant-time-picker-panel.slide-up-leave.slide-up-leave-active.ant-time-picker-panel-placement-topLeft,
.ant-time-picker-panel.slide-up-leave.slide-up-leave-active.ant-time-picker-panel-placement-topRight {
  -webkit-animation-name: antSlideDownOut;
  animation-name: antSlideDownOut
}

.ant-time-picker-panel.slide-up-leave.slide-up-leave-active.ant-time-picker-panel-placement-bottomLeft,
.ant-time-picker-panel.slide-up-leave.slide-up-leave-active.ant-time-picker-panel-placement-bottomRight {
  -webkit-animation-name: antSlideUpOut;
  animation-name: antSlideUpOut
}

.ant-time-picker {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-size: 14px;
  font-variant: tabular-nums;
  list-style: none;
  font-feature-settings: "tnum";
  width: 128px;
  outline: none;
  cursor: text;
  -webkit-transition: opacity .3s;
  transition: opacity .3s
}

.ant-time-picker,
.ant-time-picker-input {
  color: rgba(0, 0, 0, .65);
  line-height: 1.5;
  position: relative;
  display: inline-block
}

.ant-time-picker-input {
  width: 100%;
  height: 32px;
  padding: 4px 11px;
  font-size: 14px;
  background-color: #fff;
  background-image: none;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-time-picker-input::-moz-placeholder {
  color: #bfbfbf;
  opacity: 1
}

.ant-time-picker-input:-ms-input-placeholder {
  color: #bfbfbf
}

.ant-time-picker-input::-webkit-input-placeholder {
  color: #bfbfbf
}

.ant-time-picker-input:placeholder-shown {
  text-overflow: ellipsis
}

.ant-time-picker-input:focus,
.ant-time-picker-input:hover {
  border-color: #2bc3ff;
  border-right-width: 1px !important
}

.ant-time-picker-input:focus {
  outline: 0;
  box-shadow: 0 0 0 2px rgba(3, 169, 244, .2)
}

.ant-time-picker-input-disabled {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-time-picker-input-disabled:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

textarea.ant-time-picker-input {
  max-width: 100%;
  height: auto;
  min-height: 32px;
  line-height: 1.5;
  vertical-align: bottom;
  -webkit-transition: all .3s, height 0s;
  transition: all .3s, height 0s
}

.ant-time-picker-input-lg {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-time-picker-input-sm {
  height: 24px;
  padding: 1px 7px
}

.ant-time-picker-input[disabled] {
  color: rgba(0, 0, 0, .25);
  background-color: #f5f5f5;
  cursor: not-allowed;
  opacity: 1
}

.ant-time-picker-input[disabled]:hover {
  border-color: #d9d9d9;
  border-right-width: 1px !important
}

.ant-time-picker-open {
  opacity: 0
}

.ant-time-picker-clear,
.ant-time-picker-icon {
  position: absolute;
  top: 50%;
  right: 11px;
  z-index: 1;
  width: 14px;
  height: 14px;
  margin-top: -7px;
  color: rgba(0, 0, 0, .25);
  line-height: 14px;
  -webkit-transition: all .3s cubic-bezier(.645, .045, .355, 1);
  transition: all .3s cubic-bezier(.645, .045, .355, 1);
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-time-picker-clear .ant-time-picker-clock-icon,
.ant-time-picker-icon .ant-time-picker-clock-icon {
  display: block;
  color: rgba(0, 0, 0, .25);
  line-height: 1
}

.ant-time-picker-clear {
  z-index: 2;
  background: #fff;
  opacity: 0;
  pointer-events: none
}

.ant-time-picker-clear:hover {
  color: rgba(0, 0, 0, .45)
}

.ant-time-picker:hover .ant-time-picker-clear {
  opacity: 1;
  pointer-events: auto
}

.ant-time-picker-large .ant-time-picker-input {
  height: 40px;
  padding: 6px 11px;
  font-size: 16px
}

.ant-time-picker-small .ant-time-picker-input {
  height: 24px;
  padding: 1px 7px
}

.ant-time-picker-small .ant-time-picker-clear,
.ant-time-picker-small .ant-time-picker-icon {
  right: 7px
}

@media not all and (min-resolution:0.001dpcm) {
  @supports (-webkit-appearance:none) and (stroke-color:transparent) {
    .ant-input {
      line-height: 1.5
    }
  }
}

.ant-timeline {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  font-feature-settings: "tnum";
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-timeline-item {
  position: relative;
  margin: 0;
  padding: 0 0 20px;
  font-size: 14px;
  list-style: none
}

.ant-timeline-item-tail {
  position: absolute;
  top: 10px;
  left: 4px;
  height: calc(100% - 10px);
  border-left: 2px solid #e8e8e8
}

.ant-timeline-item-pending .ant-timeline-item-head {
  font-size: 12px;
  background-color: transparent
}

.ant-timeline-item-pending .ant-timeline-item-tail {
  display: none
}

.ant-timeline-item-head {
  position: absolute;
  width: 10px;
  height: 10px;
  background-color: #fff;
  border: 2px solid transparent;
  border-radius: 100px
}

.ant-timeline-item-head-blue {
  color: #03a9f4;
  border-color: #03a9f4
}

.ant-timeline-item-head-red {
  color: #f5222d;
  border-color: #f5222d
}

.ant-timeline-item-head-green {
  color: #52c41a;
  border-color: #52c41a
}

.ant-timeline-item-head-gray {
  color: rgba(0, 0, 0, .25);
  border-color: rgba(0, 0, 0, .25)
}

.ant-timeline-item-head-custom {
  position: absolute;
  top: 5.5px;
  left: 5px;
  width: auto;
  height: auto;
  margin-top: 0;
  padding: 3px 1px;
  line-height: 1;
  text-align: center;
  border: 0;
  border-radius: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%)
}

.ant-timeline-item-content {
  position: relative;
  top: -6px;
  margin: 0 0 0 18px;
  word-break: break-word
}

.ant-timeline-item-last>.ant-timeline-item-tail {
  display: none
}

.ant-timeline-item-last>.ant-timeline-item-content {
  min-height: 48px
}

.ant-timeline.ant-timeline-alternate .ant-timeline-item-head,
.ant-timeline.ant-timeline-alternate .ant-timeline-item-head-custom,
.ant-timeline.ant-timeline-alternate .ant-timeline-item-tail,
.ant-timeline.ant-timeline-right .ant-timeline-item-head,
.ant-timeline.ant-timeline-right .ant-timeline-item-head-custom,
.ant-timeline.ant-timeline-right .ant-timeline-item-tail {
  left: 50%
}

.ant-timeline.ant-timeline-alternate .ant-timeline-item-head,
.ant-timeline.ant-timeline-right .ant-timeline-item-head {
  margin-left: -4px
}

.ant-timeline.ant-timeline-alternate .ant-timeline-item-head-custom,
.ant-timeline.ant-timeline-right .ant-timeline-item-head-custom {
  margin-left: 1px
}

.ant-timeline.ant-timeline-alternate .ant-timeline-item-left .ant-timeline-item-content,
.ant-timeline.ant-timeline-right .ant-timeline-item-left .ant-timeline-item-content {
  left: calc(50% - 4px);
  width: calc(50% - 14px);
  text-align: left
}

.ant-timeline.ant-timeline-alternate .ant-timeline-item-right .ant-timeline-item-content,
.ant-timeline.ant-timeline-right .ant-timeline-item-right .ant-timeline-item-content {
  width: calc(50% - 12px);
  margin: 0;
  text-align: right
}

.ant-timeline.ant-timeline-right .ant-timeline-item-right .ant-timeline-item-head,
.ant-timeline.ant-timeline-right .ant-timeline-item-right .ant-timeline-item-head-custom,
.ant-timeline.ant-timeline-right .ant-timeline-item-right .ant-timeline-item-tail {
  left: calc(100% - 6px)
}

.ant-timeline.ant-timeline-right .ant-timeline-item-right .ant-timeline-item-content {
  width: calc(100% - 18px)
}

.ant-timeline.ant-timeline-pending .ant-timeline-item-last .ant-timeline-item-tail {
  display: block;
  height: calc(100% - 14px);
  border-left: 2px dotted #e8e8e8
}

.ant-timeline.ant-timeline-reverse .ant-timeline-item-last .ant-timeline-item-tail {
  display: none
}

.ant-timeline.ant-timeline-reverse .ant-timeline-item-pending .ant-timeline-item-tail {
  top: 15px;
  display: block;
  height: calc(100% - 15px);
  border-left: 2px dotted #e8e8e8
}

.ant-timeline.ant-timeline-reverse .ant-timeline-item-pending .ant-timeline-item-content {
  min-height: 48px
}

.ant-tooltip {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: absolute;
  z-index: 1060;
  display: block;
  max-width: 250px;
  visibility: visible
}

.ant-tooltip-hidden {
  display: none
}

.ant-tooltip-placement-top,
.ant-tooltip-placement-topLeft,
.ant-tooltip-placement-topRight {
  padding-bottom: 8px
}

.ant-tooltip-placement-right,
.ant-tooltip-placement-rightBottom,
.ant-tooltip-placement-rightTop {
  padding-left: 8px
}

.ant-tooltip-placement-bottom,
.ant-tooltip-placement-bottomLeft,
.ant-tooltip-placement-bottomRight {
  padding-top: 8px
}

.ant-tooltip-placement-left,
.ant-tooltip-placement-leftBottom,
.ant-tooltip-placement-leftTop {
  padding-right: 8px
}

.ant-tooltip-inner {
  min-width: 30px;
  min-height: 32px;
  padding: 6px 8px;
  color: #fff;
  text-align: left;
  text-decoration: none;
  word-wrap: break-word;
  background-color: rgba(0, 0, 0, .75);
  border-radius: 4px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.ant-tooltip-arrow {
  position: absolute;
  display: block;
  width: 13.07106781px;
  height: 13.07106781px;
  overflow: hidden;
  background: transparent;
  pointer-events: none
}

.ant-tooltip-arrow:before {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  display: block;
  width: 5px;
  height: 5px;
  margin: auto;
  background-color: rgba(0, 0, 0, .75);
  content: "";
  pointer-events: auto
}

.ant-tooltip-placement-top .ant-tooltip-arrow,
.ant-tooltip-placement-topLeft .ant-tooltip-arrow,
.ant-tooltip-placement-topRight .ant-tooltip-arrow {
  bottom: -5.07106781px
}

.ant-tooltip-placement-top .ant-tooltip-arrow:before,
.ant-tooltip-placement-topLeft .ant-tooltip-arrow:before,
.ant-tooltip-placement-topRight .ant-tooltip-arrow:before {
  box-shadow: 3px 3px 7px rgba(0, 0, 0, .07);
  -webkit-transform: translateY(-6.53553391px) rotate(45deg);
  transform: translateY(-6.53553391px) rotate(45deg)
}

.ant-tooltip-placement-top .ant-tooltip-arrow {
  left: 50%;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%)
}

.ant-tooltip-placement-topLeft .ant-tooltip-arrow {
  left: 13px
}

.ant-tooltip-placement-topRight .ant-tooltip-arrow {
  right: 13px
}

.ant-tooltip-placement-right .ant-tooltip-arrow,
.ant-tooltip-placement-rightBottom .ant-tooltip-arrow,
.ant-tooltip-placement-rightTop .ant-tooltip-arrow {
  left: -5.07106781px
}

.ant-tooltip-placement-right .ant-tooltip-arrow:before,
.ant-tooltip-placement-rightBottom .ant-tooltip-arrow:before,
.ant-tooltip-placement-rightTop .ant-tooltip-arrow:before {
  box-shadow: -3px 3px 7px rgba(0, 0, 0, .07);
  -webkit-transform: translateX(6.53553391px) rotate(45deg);
  transform: translateX(6.53553391px) rotate(45deg)
}

.ant-tooltip-placement-right .ant-tooltip-arrow {
  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-tooltip-placement-rightTop .ant-tooltip-arrow {
  top: 5px
}

.ant-tooltip-placement-rightBottom .ant-tooltip-arrow {
  bottom: 5px
}

.ant-tooltip-placement-left .ant-tooltip-arrow,
.ant-tooltip-placement-leftBottom .ant-tooltip-arrow,
.ant-tooltip-placement-leftTop .ant-tooltip-arrow {
  right: -5.07106781px
}

.ant-tooltip-placement-left .ant-tooltip-arrow:before,
.ant-tooltip-placement-leftBottom .ant-tooltip-arrow:before,
.ant-tooltip-placement-leftTop .ant-tooltip-arrow:before {
  box-shadow: 3px -3px 7px rgba(0, 0, 0, .07);
  -webkit-transform: translateX(-6.53553391px) rotate(45deg);
  transform: translateX(-6.53553391px) rotate(45deg)
}

.ant-tooltip-placement-left .ant-tooltip-arrow {
  top: 50%;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-tooltip-placement-leftTop .ant-tooltip-arrow {
  top: 5px
}

.ant-tooltip-placement-leftBottom .ant-tooltip-arrow {
  bottom: 5px
}

.ant-tooltip-placement-bottom .ant-tooltip-arrow,
.ant-tooltip-placement-bottomLeft .ant-tooltip-arrow,
.ant-tooltip-placement-bottomRight .ant-tooltip-arrow {
  top: -5.07106781px
}

.ant-tooltip-placement-bottom .ant-tooltip-arrow:before,
.ant-tooltip-placement-bottomLeft .ant-tooltip-arrow:before,
.ant-tooltip-placement-bottomRight .ant-tooltip-arrow:before {
  box-shadow: -3px -3px 7px rgba(0, 0, 0, .07);
  -webkit-transform: translateY(6.53553391px) rotate(45deg);
  transform: translateY(6.53553391px) rotate(45deg)
}

.ant-tooltip-placement-bottom .ant-tooltip-arrow {
  left: 50%;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%)
}

.ant-tooltip-placement-bottomLeft .ant-tooltip-arrow {
  left: 13px
}

.ant-tooltip-placement-bottomRight .ant-tooltip-arrow {
  right: 13px
}

.ant-transfer-customize-list {
  display: flex
}

.ant-transfer-customize-list .ant-transfer-operation {
  flex: none;
  align-self: center
}

.ant-transfer-customize-list .ant-transfer-list {
  flex: auto;
  width: auto;
  height: auto;
  min-height: 200px
}

.ant-transfer-customize-list .ant-transfer-list-body-with-search {
  padding-top: 0
}

.ant-transfer-customize-list .ant-transfer-list-body-search-wrapper {
  position: relative;
  padding-bottom: 0
}

.ant-transfer-customize-list .ant-transfer-list-body-customize-wrapper {
  padding: 12px
}

.ant-transfer-customize-list .ant-table-wrapper .ant-table-small {
  border: 0;
  border-radius: 0
}

.ant-transfer-customize-list .ant-table-wrapper .ant-table-small>.ant-table-content>.ant-table-body>table>.ant-table-thead>tr>th {
  background: #fafafa
}

.ant-transfer-customize-list .ant-table-wrapper .ant-table-small>.ant-table-content .ant-table-row:last-child td {
  border-bottom: 1px solid #e8e8e8
}

.ant-transfer-customize-list .ant-table-wrapper .ant-table-small .ant-table-body {
  margin: 0
}

.ant-transfer-customize-list .ant-table-wrapper .ant-table-pagination.ant-pagination {
  margin: 16px 0 4px
}

.ant-transfer {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative
}

.ant-transfer-disabled .ant-transfer-list {
  background: #f5f5f5
}

.ant-transfer-list {
  position: relative;
  display: inline-block;
  width: 180px;
  height: 200px;
  padding-top: 40px;
  vertical-align: middle;
  border: 1px solid #d9d9d9;
  border-radius: 4px
}

.ant-transfer-list-with-footer {
  padding-bottom: 34px
}

.ant-transfer-list-search {
  padding: 0 8px
}

.ant-transfer-list-search-action {
  position: absolute;
  top: 12px;
  right: 12px;
  bottom: 12px;
  width: 28px;
  color: rgba(0, 0, 0, .25);
  line-height: 32px;
  text-align: center
}

.ant-transfer-list-search-action .anticon {
  color: rgba(0, 0, 0, .25);
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-transfer-list-search-action .anticon:hover {
  color: rgba(0, 0, 0, .45)
}

span.ant-transfer-list-search-action {
  pointer-events: none
}

.ant-transfer-list-header {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 8px 12px 9px;
  overflow: hidden;
  color: rgba(0, 0, 0, .65);
  background: #fff;
  border-bottom: 1px solid #e8e8e8;
  border-radius: 4px 4px 0 0
}

.ant-transfer-list-header-title {
  position: absolute;
  right: 12px
}

.ant-transfer-list-header .ant-checkbox-wrapper+span {
  padding-left: 8px
}

.ant-transfer-list-body {
  position: relative;
  height: 100%;
  font-size: 14px
}

.ant-transfer-list-body-search-wrapper {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 12px
}

.ant-transfer-list-body-with-search {
  padding-top: 56px
}

.ant-transfer-list-content {
  height: 100%;
  margin: 0;
  padding: 0;
  overflow: auto;
  list-style: none
}

.ant-transfer-list-content>.LazyLoad {
  -webkit-animation: transferHighlightIn 1s;
  animation: transferHighlightIn 1s
}

.ant-transfer-list-content-item {
  min-height: 32px;
  padding: 6px 12px;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-transfer-list-content-item>span {
  padding-right: 0
}

.ant-transfer-list-content-item-text {
  padding-left: 8px
}

.ant-transfer-list-content-item:not(.ant-transfer-list-content-item-disabled):hover {
  background-color: #e8f8ff;
  cursor: pointer
}

.ant-transfer-list-content-item-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-transfer-list-body-not-found {
  position: absolute;
  top: 50%;
  width: 100%;
  padding-top: 0;
  color: rgba(0, 0, 0, .25);
  text-align: center;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.ant-transfer-list-body-with-search .ant-transfer-list-body-not-found {
  margin-top: 16px
}

.ant-transfer-list-footer {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  border-top: 1px solid #e8e8e8;
  border-radius: 0 0 4px 4px
}

.ant-transfer-operation {
  display: inline-block;
  margin: 0 8px;
  overflow: hidden;
  vertical-align: middle
}

.ant-transfer-operation .ant-btn {
  display: block
}

.ant-transfer-operation .ant-btn:first-child {
  margin-bottom: 4px
}

.ant-transfer-operation .ant-btn .anticon {
  font-size: 12px
}

@-webkit-keyframes transferHighlightIn {
  0% {
    background: #a6efff
  }

  to {
    background: transparent
  }
}

@keyframes transferHighlightIn {
  0% {
    background: #a6efff
  }

  to {
    background: transparent
  }
}

.ant-tree.ant-tree-directory {
  position: relative
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-switcher,
.ant-tree.ant-tree-directory>li span.ant-tree-switcher {
  position: relative;
  z-index: 1
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-switcher.ant-tree-switcher-noop,
.ant-tree.ant-tree-directory>li span.ant-tree-switcher.ant-tree-switcher-noop {
  pointer-events: none
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-checkbox,
.ant-tree.ant-tree-directory>li span.ant-tree-checkbox {
  position: relative;
  z-index: 1
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper {
  border-radius: 0;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper:hover,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper:hover {
  background: transparent
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper:hover:before,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper:hover:before {
  background: #e8f8ff
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper.ant-tree-node-selected,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper.ant-tree-node-selected {
  color: #fff;
  background: transparent
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper:before,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper:before {
  position: absolute;
  right: 0;
  left: 0;
  height: 24px;
  -webkit-transition: all .3s;
  transition: all .3s;
  content: ""
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li span.ant-tree-node-content-wrapper>span,
.ant-tree.ant-tree-directory>li span.ant-tree-node-content-wrapper>span {
  position: relative;
  z-index: 1
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-switcher,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-switcher {
  color: #fff
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-checkbox .ant-tree-checkbox-inner,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-checkbox .ant-tree-checkbox-inner {
  border-color: #03a9f4
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked:after,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked:after {
  border-color: #fff
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked .ant-tree-checkbox-inner,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked .ant-tree-checkbox-inner {
  background: #fff
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked .ant-tree-checkbox-inner:after,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-checkbox.ant-tree-checkbox-checked .ant-tree-checkbox-inner:after {
  border-color: #03a9f4
}

.ant-tree.ant-tree-directory .ant-tree-child-tree>li.ant-tree-treenode-selected>span.ant-tree-node-content-wrapper:before,
.ant-tree.ant-tree-directory>li.ant-tree-treenode-selected>span.ant-tree-node-content-wrapper:before {
  background: #03a9f4
}

.ant-tree-checkbox {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  top: -.09em;
  display: inline-block;
  line-height: 1;
  white-space: nowrap;
  vertical-align: middle;
  outline: none;
  cursor: pointer
}

.ant-tree-checkbox-input:focus+.ant-tree-checkbox-inner,
.ant-tree-checkbox-wrapper:hover .ant-tree-checkbox-inner,
.ant-tree-checkbox:hover .ant-tree-checkbox-inner {
  border-color: #03a9f4
}

.ant-tree-checkbox-checked:after {
  top: 0;
  height: 100%;
  border: 1px solid #03a9f4;
  border-radius: 2px;
  visibility: hidden;
  -webkit-animation: antCheckboxEffect .36s ease-in-out;
  animation: antCheckboxEffect .36s ease-in-out;
  -webkit-animation-fill-mode: backwards;
  animation-fill-mode: backwards;
  content: ""
}

.ant-tree-checkbox-wrapper:hover .ant-tree-checkbox:after,
.ant-tree-checkbox:hover:after {
  visibility: visible
}

.ant-tree-checkbox-inner {
  position: relative;
  top: 0;
  left: 0;
  display: block;
  width: 16px;
  height: 16px;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 2px;
  border-collapse: separate;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-tree-checkbox-inner:after {
  position: absolute;
  top: 50%;
  left: 21%;
  display: table;
  width: 5.71428571px;
  height: 9.14285714px;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(0) translate(-50%, -50%);
  transform: rotate(45deg) scale(0) translate(-50%, -50%);
  opacity: 0;
  -webkit-transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  content: " "
}

.ant-tree-checkbox-input {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  width: 100%;
  height: 100%;
  cursor: pointer;
  opacity: 0
}

.ant-tree-checkbox-checked .ant-tree-checkbox-inner:after {
  position: absolute;
  display: table;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(1) translate(-50%, -50%);
  transform: rotate(45deg) scale(1) translate(-50%, -50%);
  opacity: 1;
  -webkit-transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  content: " "
}

.ant-tree-checkbox-checked .ant-tree-checkbox-inner {
  background-color: #03a9f4;
  border-color: #03a9f4
}

.ant-tree-checkbox-disabled {
  cursor: not-allowed
}

.ant-tree-checkbox-disabled.ant-tree-checkbox-checked .ant-tree-checkbox-inner:after {
  border-color: rgba(0, 0, 0, .25);
  -webkit-animation-name: none;
  animation-name: none
}

.ant-tree-checkbox-disabled .ant-tree-checkbox-input {
  cursor: not-allowed
}

.ant-tree-checkbox-disabled .ant-tree-checkbox-inner {
  background-color: #f5f5f5;
  border-color: #d9d9d9 !important
}

.ant-tree-checkbox-disabled .ant-tree-checkbox-inner:after {
  border-color: #f5f5f5;
  border-collapse: separate;
  -webkit-animation-name: none;
  animation-name: none
}

.ant-tree-checkbox-disabled+span {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-tree-checkbox-disabled:hover:after,
.ant-tree-checkbox-wrapper:hover .ant-tree-checkbox-disabled:after {
  visibility: hidden
}

.ant-tree-checkbox-wrapper {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  line-height: unset;
  cursor: pointer
}

.ant-tree-checkbox-wrapper.ant-tree-checkbox-wrapper-disabled {
  cursor: not-allowed
}

.ant-tree-checkbox-wrapper+.ant-tree-checkbox-wrapper {
  margin-left: 8px
}

.ant-tree-checkbox+span {
  padding-right: 8px;
  padding-left: 8px
}

.ant-tree-checkbox-group {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block
}

.ant-tree-checkbox-group-item {
  display: inline-block;
  margin-right: 8px
}

.ant-tree-checkbox-group-item:last-child {
  margin-right: 0
}

.ant-tree-checkbox-group-item+.ant-tree-checkbox-group-item {
  margin-left: 0
}

.ant-tree-checkbox-indeterminate .ant-tree-checkbox-inner {
  background-color: #fff;
  border-color: #d9d9d9
}

.ant-tree-checkbox-indeterminate .ant-tree-checkbox-inner:after {
  top: 50%;
  left: 50%;
  width: 8px;
  height: 8px;
  background-color: #03a9f4;
  border: 0;
  -webkit-transform: translate(-50%, -50%) scale(1);
  transform: translate(-50%, -50%) scale(1);
  opacity: 1;
  content: " "
}

.ant-tree-checkbox-indeterminate.ant-tree-checkbox-disabled .ant-tree-checkbox-inner:after {
  background-color: rgba(0, 0, 0, .25);
  border-color: rgba(0, 0, 0, .25)
}

.ant-tree {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  margin: 0;
  padding: 0
}

.ant-tree-checkbox-checked:after {
  position: absolute;
  top: 16.67%;
  left: 0;
  width: 100%;
  height: 66.67%
}

.ant-tree ol,
.ant-tree ul {
  margin: 0;
  padding: 0;
  list-style: none
}

.ant-tree li {
  margin: 0;
  padding: 4px 0;
  white-space: nowrap;
  list-style: none;
  outline: 0
}

.ant-tree li span[draggable=true],
.ant-tree li span[draggable] {
  line-height: 20px;
  border-top: 2px solid transparent;
  border-bottom: 2px solid transparent;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -khtml-user-drag: element;
  -webkit-user-drag: element
}

.ant-tree li.drag-over>span[draggable] {
  color: #fff;
  background-color: #03a9f4;
  opacity: .8
}

.ant-tree li.drag-over-gap-top>span[draggable] {
  border-top-color: #03a9f4
}

.ant-tree li.drag-over-gap-bottom>span[draggable] {
  border-bottom-color: #03a9f4
}

.ant-tree li.filter-node>span {
  color: #f5222d !important;
  font-weight: 500 !important
}

.ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-loading-icon,
.ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-loading-icon {
  position: absolute;
  left: 0;
  display: inline-block;
  width: 24px;
  height: 24px;
  color: #03a9f4;
  font-size: 14px;
  -webkit-transform: none;
  transform: none
}

.ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-loading-icon svg,
.ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-loading-icon svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

:root .ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_close:after,
:root .ant-tree li.ant-tree-treenode-loading span.ant-tree-switcher.ant-tree-switcher_open:after {
  opacity: 0
}

.ant-tree li ul {
  margin: 0;
  padding: 0 0 0 18px
}

.ant-tree li .ant-tree-node-content-wrapper {
  display: inline-block;
  height: 24px;
  margin: 0;
  padding: 0 5px;
  color: rgba(0, 0, 0, .65);
  line-height: 24px;
  text-decoration: none;
  vertical-align: top;
  border-radius: 2px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-tree li .ant-tree-node-content-wrapper:hover {
  background-color: #e8f8ff
}

.ant-tree li .ant-tree-node-content-wrapper.ant-tree-node-selected {
  background-color: #a6efff
}

.ant-tree li span.ant-tree-checkbox {
  top: auto;
  height: 24px;
  margin: 0 4px 0 2px;
  padding: 4px 0
}

.ant-tree li span.ant-tree-iconEle,
.ant-tree li span.ant-tree-switcher {
  display: inline-block;
  width: 24px;
  height: 24px;
  margin: 0;
  line-height: 24px;
  text-align: center;
  vertical-align: top;
  border: 0;
  outline: none;
  cursor: pointer
}

.ant-tree li span.ant-tree-switcher {
  position: relative
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher-noop {
  cursor: default
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-select-switcher-icon,
.ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-icon {
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  display: inline-block;
  font-weight: 700
}

:root .ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-select-switcher-icon,
:root .ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-icon {
  font-size: 12px
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-select-switcher-icon svg,
.ant-tree li span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-select-switcher-icon,
.ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon {
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  display: inline-block;
  font-weight: 700
}

:root .ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-select-switcher-icon,
:root .ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon {
  font-size: 12px
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-select-switcher-icon svg,
.ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-tree li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon svg {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg)
}

.ant-tree li:last-child>span.ant-tree-iconEle:before,
.ant-tree li:last-child>span.ant-tree-switcher:before {
  display: none
}

.ant-tree>li:first-child {
  padding-top: 7px
}

.ant-tree>li:last-child {
  padding-bottom: 7px
}

.ant-tree-child-tree>li:first-child {
  padding-top: 8px
}

.ant-tree-child-tree>li:last-child {
  padding-bottom: 0
}

li.ant-tree-treenode-disabled>.ant-tree-node-content-wrapper,
li.ant-tree-treenode-disabled>.ant-tree-node-content-wrapper span,
li.ant-tree-treenode-disabled>span:not(.ant-tree-switcher) {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

li.ant-tree-treenode-disabled>.ant-tree-node-content-wrapper:hover {
  background: transparent
}

.ant-tree-icon__close,
.ant-tree-icon__open {
  margin-right: 2px;
  vertical-align: top
}

.ant-tree.ant-tree-show-line li {
  position: relative
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher {
  color: rgba(0, 0, 0, .45);
  background: #fff
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher-noop .ant-select-switcher-icon,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher-noop .ant-tree-switcher-icon {
  display: inline-block;
  font-weight: 400;
  font-size: 12px
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher-noop .ant-select-switcher-icon svg,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher-noop .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_open .ant-select-switcher-icon,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-icon {
  display: inline-block;
  font-weight: 400;
  font-size: 12px
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_open .ant-select-switcher-icon svg,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_open .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_close .ant-select-switcher-icon,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon {
  display: inline-block;
  font-weight: 400;
  font-size: 12px
}

.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_close .ant-select-switcher-icon svg,
.ant-tree.ant-tree-show-line li span.ant-tree-switcher.ant-tree-switcher_close .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-tree.ant-tree-show-line li:not(:last-child):before {
  position: absolute;
  left: 12px;
  width: 1px;
  height: 100%;
  height: calc(100% - 22px);
  margin: 22px 0 0;
  border-left: 1px solid #d9d9d9;
  content: " "
}

.ant-tree.ant-tree-icon-hide .ant-tree-treenode-loading .ant-tree-iconEle {
  display: none
}

.ant-tree.ant-tree-block-node li .ant-tree-node-content-wrapper {
  width: calc(100% - 24px)
}

.ant-tree.ant-tree-block-node li span.ant-tree-checkbox+.ant-tree-node-content-wrapper {
  width: calc(100% - 46px)
}

.ant-select-tree-checkbox {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  position: relative;
  top: -.09em;
  display: inline-block;
  line-height: 1;
  white-space: nowrap;
  vertical-align: middle;
  outline: none;
  cursor: pointer
}

.ant-select-tree-checkbox-input:focus+.ant-select-tree-checkbox-inner,
.ant-select-tree-checkbox-wrapper:hover .ant-select-tree-checkbox-inner,
.ant-select-tree-checkbox:hover .ant-select-tree-checkbox-inner {
  border-color: #03a9f4
}

.ant-select-tree-checkbox-checked:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #03a9f4;
  border-radius: 2px;
  visibility: hidden;
  -webkit-animation: antCheckboxEffect .36s ease-in-out;
  animation: antCheckboxEffect .36s ease-in-out;
  -webkit-animation-fill-mode: backwards;
  animation-fill-mode: backwards;
  content: ""
}

.ant-select-tree-checkbox-wrapper:hover .ant-select-tree-checkbox:after,
.ant-select-tree-checkbox:hover:after {
  visibility: visible
}

.ant-select-tree-checkbox-inner {
  position: relative;
  top: 0;
  left: 0;
  display: block;
  width: 16px;
  height: 16px;
  background-color: #fff;
  border: 1px solid #d9d9d9;
  border-radius: 2px;
  border-collapse: separate;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-select-tree-checkbox-inner:after {
  position: absolute;
  top: 50%;
  left: 21%;
  display: table;
  width: 5.71428571px;
  height: 9.14285714px;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(0) translate(-50%, -50%);
  transform: rotate(45deg) scale(0) translate(-50%, -50%);
  opacity: 0;
  -webkit-transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  transition: all .1s cubic-bezier(.71, -.46, .88, .6), opacity .1s;
  content: " "
}

.ant-select-tree-checkbox-input {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  width: 100%;
  height: 100%;
  cursor: pointer;
  opacity: 0
}

.ant-select-tree-checkbox-checked .ant-select-tree-checkbox-inner:after {
  position: absolute;
  display: table;
  border: 2px solid #fff;
  border-top: 0;
  border-left: 0;
  -webkit-transform: rotate(45deg) scale(1) translate(-50%, -50%);
  transform: rotate(45deg) scale(1) translate(-50%, -50%);
  opacity: 1;
  -webkit-transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  transition: all .2s cubic-bezier(.12, .4, .29, 1.46) .1s;
  content: " "
}

.ant-select-tree-checkbox-checked .ant-select-tree-checkbox-inner {
  background-color: #03a9f4;
  border-color: #03a9f4
}

.ant-select-tree-checkbox-disabled {
  cursor: not-allowed
}

.ant-select-tree-checkbox-disabled.ant-select-tree-checkbox-checked .ant-select-tree-checkbox-inner:after {
  border-color: rgba(0, 0, 0, .25);
  -webkit-animation-name: none;
  animation-name: none
}

.ant-select-tree-checkbox-disabled .ant-select-tree-checkbox-input {
  cursor: not-allowed
}

.ant-select-tree-checkbox-disabled .ant-select-tree-checkbox-inner {
  background-color: #f5f5f5;
  border-color: #d9d9d9 !important
}

.ant-select-tree-checkbox-disabled .ant-select-tree-checkbox-inner:after {
  border-color: #f5f5f5;
  border-collapse: separate;
  -webkit-animation-name: none;
  animation-name: none
}

.ant-select-tree-checkbox-disabled+span {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-select-tree-checkbox-disabled:hover:after,
.ant-select-tree-checkbox-wrapper:hover .ant-select-tree-checkbox-disabled:after {
  visibility: hidden
}

.ant-select-tree-checkbox-wrapper {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block;
  line-height: unset;
  cursor: pointer
}

.ant-select-tree-checkbox-wrapper.ant-select-tree-checkbox-wrapper-disabled {
  cursor: not-allowed
}

.ant-select-tree-checkbox-wrapper+.ant-select-tree-checkbox-wrapper {
  margin-left: 8px
}

.ant-select-tree-checkbox+span {
  padding-right: 8px;
  padding-left: 8px
}

.ant-select-tree-checkbox-group {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  display: inline-block
}

.ant-select-tree-checkbox-group-item {
  display: inline-block;
  margin-right: 8px
}

.ant-select-tree-checkbox-group-item:last-child {
  margin-right: 0
}

.ant-select-tree-checkbox-group-item+.ant-select-tree-checkbox-group-item {
  margin-left: 0
}

.ant-select-tree-checkbox-indeterminate .ant-select-tree-checkbox-inner {
  background-color: #fff;
  border-color: #d9d9d9
}

.ant-select-tree-checkbox-indeterminate .ant-select-tree-checkbox-inner:after {
  top: 50%;
  left: 50%;
  width: 8px;
  height: 8px;
  background-color: #03a9f4;
  border: 0;
  -webkit-transform: translate(-50%, -50%) scale(1);
  transform: translate(-50%, -50%) scale(1);
  opacity: 1;
  content: " "
}

.ant-select-tree-checkbox-indeterminate.ant-select-tree-checkbox-disabled .ant-select-tree-checkbox-inner:after {
  background-color: rgba(0, 0, 0, .25);
  border-color: rgba(0, 0, 0, .25)
}

.ant-select-tree {
  box-sizing: border-box;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  margin: -4px 0 0;
  padding: 0 4px
}

.ant-select-tree li {
  margin: 8px 0;
  padding: 0;
  white-space: nowrap;
  list-style: none;
  outline: 0
}

.ant-select-tree li.filter-node>span {
  font-weight: 500
}

.ant-select-tree li ul {
  margin: 0;
  padding: 0 0 0 18px
}

.ant-select-tree li .ant-select-tree-node-content-wrapper {
  display: inline-block;
  width: calc(100% - 24px);
  margin: 0;
  padding: 3px 5px;
  color: rgba(0, 0, 0, .65);
  text-decoration: none;
  border-radius: 2px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-select-tree li .ant-select-tree-node-content-wrapper:hover {
  background-color: #e8f8ff
}

.ant-select-tree li .ant-select-tree-node-content-wrapper.ant-select-tree-node-selected {
  background-color: #a6efff
}

.ant-select-tree li span.ant-select-tree-checkbox {
  margin: 0 4px 0 0
}

.ant-select-tree li span.ant-select-tree-checkbox+.ant-select-tree-node-content-wrapper {
  width: calc(100% - 46px)
}

.ant-select-tree li span.ant-select-tree-iconEle,
.ant-select-tree li span.ant-select-tree-switcher {
  display: inline-block;
  width: 24px;
  height: 24px;
  margin: 0;
  line-height: 22px;
  text-align: center;
  vertical-align: middle;
  border: 0;
  outline: none;
  cursor: pointer
}

.ant-select-tree li span.ant-select-icon_loading .ant-select-switcher-loading-icon {
  position: absolute;
  left: 0;
  display: inline-block;
  color: #03a9f4;
  font-size: 14px;
  -webkit-transform: none;
  transform: none
}

.ant-select-tree li span.ant-select-icon_loading .ant-select-switcher-loading-icon svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.ant-select-tree li span.ant-select-tree-switcher {
  position: relative
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher-noop {
  cursor: auto
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-select-switcher-icon,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-tree-switcher-icon {
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  display: inline-block;
  font-weight: 700
}

:root .ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-select-switcher-icon,
:root .ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-tree-switcher-icon {
  font-size: 12px
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-select-switcher-icon svg,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-icon,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-tree-switcher-icon {
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  display: inline-block;
  font-weight: 700
}

:root .ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-icon,
:root .ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-tree-switcher-icon {
  font-size: 12px
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-icon svg,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-tree-switcher-icon svg {
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-icon svg {
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg)
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-loading-icon,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-select-switcher-loading-icon {
  position: absolute;
  left: 0;
  display: inline-block;
  width: 24px;
  height: 24px;
  color: #03a9f4;
  font-size: 14px;
  -webkit-transform: none;
  transform: none
}

.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_close .ant-select-switcher-loading-icon svg,
.ant-select-tree li span.ant-select-tree-switcher.ant-select-tree-switcher_open .ant-select-switcher-loading-icon svg {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto
}

.ant-select-tree-child-tree,
.ant-select-tree .ant-select-tree-treenode-loading .ant-select-tree-iconEle {
  display: none
}

.ant-select-tree-child-tree-open {
  display: block
}

li.ant-select-tree-treenode-disabled>.ant-select-tree-node-content-wrapper,
li.ant-select-tree-treenode-disabled>.ant-select-tree-node-content-wrapper span,
li.ant-select-tree-treenode-disabled>span:not(.ant-select-tree-switcher) {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

li.ant-select-tree-treenode-disabled>.ant-select-tree-node-content-wrapper:hover {
  background: transparent
}

.ant-select-tree-icon__close,
.ant-select-tree-icon__open {
  margin-right: 2px;
  vertical-align: top
}

.ant-select-tree-dropdown {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum"
}

.ant-select-tree-dropdown .ant-select-dropdown-search {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  z-index: 1;
  display: block;
  padding: 4px;
  background: #fff
}

.ant-select-tree-dropdown .ant-select-dropdown-search .ant-select-search__field__wrap {
  width: 100%
}

.ant-select-tree-dropdown .ant-select-dropdown-search .ant-select-search__field {
  box-sizing: border-box;
  width: 100%;
  padding: 4px 7px;
  border: 1px solid #d9d9d9;
  border-radius: 4px;
  outline: none
}

.ant-select-tree-dropdown .ant-select-dropdown-search.ant-select-search--hide {
  display: none
}

.ant-select-tree-dropdown .ant-select-not-found {
  display: block;
  padding: 7px 16px;
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed
}

.ant-typography {
  color: rgba(0, 0, 0, .65)
}

.ant-typography.ant-typography-secondary {
  color: rgba(0, 0, 0, .45)
}

.ant-typography.ant-typography-warning {
  color: #faad14
}

.ant-typography.ant-typography-danger {
  color: #f5222d
}

.ant-typography.ant-typography-disabled {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none
}

.ant-typography p,
div.ant-typography {
  margin-bottom: 1em
}

.ant-typography h1,
h1.ant-typography {
  margin-bottom: .5em;
  color: rgba(0, 0, 0, .85);
  font-weight: 600;
  font-size: 38px;
  line-height: 1.23
}

.ant-typography h2,
h2.ant-typography {
  margin-bottom: .5em;
  color: rgba(0, 0, 0, .85);
  font-weight: 600;
  font-size: 30px;
  line-height: 1.35
}

.ant-typography h3,
h3.ant-typography {
  margin-bottom: .5em;
  color: rgba(0, 0, 0, .85);
  font-weight: 600;
  font-size: 24px;
  line-height: 1.35
}

.ant-typography h4,
h4.ant-typography {
  margin-bottom: .5em;
  color: rgba(0, 0, 0, .85);
  font-weight: 600;
  font-size: 20px;
  line-height: 1.4
}

.ant-typography+h1.ant-typography,
.ant-typography+h2.ant-typography,
.ant-typography+h3.ant-typography,
.ant-typography+h4.ant-typography,
.ant-typography div+h1,
.ant-typography div+h2,
.ant-typography div+h3,
.ant-typography div+h4,
.ant-typography h1+h1,
.ant-typography h1+h2,
.ant-typography h1+h3,
.ant-typography h1+h4,
.ant-typography h2+h1,
.ant-typography h2+h2,
.ant-typography h2+h3,
.ant-typography h2+h4,
.ant-typography h3+h1,
.ant-typography h3+h2,
.ant-typography h3+h3,
.ant-typography h3+h4,
.ant-typography h4+h1,
.ant-typography h4+h2,
.ant-typography h4+h3,
.ant-typography h4+h4,
.ant-typography li+h1,
.ant-typography li+h2,
.ant-typography li+h3,
.ant-typography li+h4,
.ant-typography p+h1,
.ant-typography p+h2,
.ant-typography p+h3,
.ant-typography p+h4,
.ant-typography ul+h1,
.ant-typography ul+h2,
.ant-typography ul+h3,
.ant-typography ul+h4 {
  margin-top: 1.2em
}

span.ant-typography-ellipsis {
  display: inline-block
}

.ant-typography a {
  color: #03a9f4;
  text-decoration: none;
  outline: none;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s
}

.ant-typography a:focus,
.ant-typography a:hover {
  color: #2bc3ff
}

.ant-typography a:active {
  color: #0086cf
}

.ant-typography a:active,
.ant-typography a:hover {
  text-decoration: none
}

.ant-typography a[disabled] {
  color: rgba(0, 0, 0, .25);
  cursor: not-allowed;
  pointer-events: none
}

.ant-typography code {
  margin: 0 .2em;
  padding: .2em .4em .1em;
  font-size: 85%;
  background: rgba(0, 0, 0, .06);
  border: 1px solid rgba(0, 0, 0, .06);
  border-radius: 3px
}

.ant-typography mark {
  padding: 0;
  background-color: #ffe58f
}

.ant-typography ins,
.ant-typography u {
  text-decoration: underline;
  -webkit-text-decoration-skip: ink;
  text-decoration-skip-ink: auto
}

.ant-typography del,
.ant-typography s {
  text-decoration: line-through
}

.ant-typography strong {
  font-weight: 600
}

.ant-typography-copy,
.ant-typography-edit,
.ant-typography-expand {
  color: #03a9f4;
  text-decoration: none;
  outline: none;
  cursor: pointer;
  -webkit-transition: color .3s;
  transition: color .3s;
  margin-left: 8px
}

.ant-typography-copy:focus,
.ant-typography-copy:hover,
.ant-typography-edit:focus,
.ant-typography-edit:hover,
.ant-typography-expand:focus,
.ant-typography-expand:hover {
  color: #2bc3ff
}

.ant-typography-copy:active,
.ant-typography-edit:active,
.ant-typography-expand:active {
  color: #0086cf
}

.ant-typography-copy-success,
.ant-typography-copy-success:focus,
.ant-typography-copy-success:hover {
  color: #52c41a
}

.ant-typography-edit-content {
  position: relative
}

div.ant-typography-edit-content {
  left: -12px;
  margin-top: -5px;
  margin-bottom: calc(1em - 6px)
}

.ant-typography-edit-content-confirm {
  position: absolute;
  right: 10px;
  bottom: 8px;
  color: rgba(0, 0, 0, .45);
  pointer-events: none
}

.ant-typography ol,
.ant-typography ul {
  margin: 0 0 1em;
  padding: 0
}

.ant-typography ol li,
.ant-typography ul li {
  margin: 0 0 0 20px;
  padding: 0 0 0 4px
}

.ant-typography ul li {
  list-style-type: circle
}

.ant-typography ul li li {
  list-style-type: disc
}

.ant-typography ol li {
  list-style-type: decimal
}

.ant-typography-ellipsis-single-line {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-typography-ellipsis-multiple-line {
  display: -webkit-box;
  -webkit-line-clamp: 3;
  /*! autoprefixer: ignore next */
  -webkit-box-orient: vertical;
  overflow: hidden
}

.ant-upload {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  outline: 0
}

.ant-upload p {
  margin: 0
}

.ant-upload-btn {
  display: block;
  width: 100%;
  outline: none
}

.ant-upload input[type=file] {
  cursor: pointer
}

.ant-upload.ant-upload-select {
  display: inline-block
}

.ant-upload.ant-upload-disabled {
  cursor: not-allowed
}

.ant-upload.ant-upload-select-picture-card {
  display: table;
  float: left;
  width: 104px;
  height: 104px;
  margin-right: 8px;
  margin-bottom: 8px;
  text-align: center;
  vertical-align: top;
  background-color: #fafafa;
  border: 1px dashed #d9d9d9;
  border-radius: 4px;
  cursor: pointer;
  -webkit-transition: border-color .3s ease;
  transition: border-color .3s ease
}

.ant-upload.ant-upload-select-picture-card>.ant-upload {
  display: table-cell;
  width: 100%;
  height: 100%;
  padding: 8px;
  text-align: center;
  vertical-align: middle
}

.ant-upload.ant-upload-select-picture-card:hover {
  border-color: #03a9f4
}

.ant-upload.ant-upload-drag {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  background: #fafafa;
  border: 1px dashed #d9d9d9;
  border-radius: 4px;
  cursor: pointer;
  -webkit-transition: border-color .3s;
  transition: border-color .3s
}

.ant-upload.ant-upload-drag .ant-upload {
  padding: 16px 0
}

.ant-upload.ant-upload-drag.ant-upload-drag-hover:not(.ant-upload-disabled) {
  border-color: #0086cf
}

.ant-upload.ant-upload-drag.ant-upload-disabled {
  cursor: not-allowed
}

.ant-upload.ant-upload-drag .ant-upload-btn {
  display: table;
  height: 100%
}

.ant-upload.ant-upload-drag .ant-upload-drag-container {
  display: table-cell;
  vertical-align: middle
}

.ant-upload.ant-upload-drag:not(.ant-upload-disabled):hover {
  border-color: #2bc3ff
}

.ant-upload.ant-upload-drag p.ant-upload-drag-icon {
  margin-bottom: 20px
}

.ant-upload.ant-upload-drag p.ant-upload-drag-icon .anticon {
  color: #2bc3ff;
  font-size: 48px
}

.ant-upload.ant-upload-drag p.ant-upload-text {
  margin: 0 0 4px;
  color: rgba(0, 0, 0, .85);
  font-size: 16px
}

.ant-upload.ant-upload-drag p.ant-upload-hint {
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-upload.ant-upload-drag .anticon-plus {
  color: rgba(0, 0, 0, .25);
  font-size: 30px;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-upload.ant-upload-drag .anticon-plus:hover,
.ant-upload.ant-upload-drag:hover .anticon-plus {
  color: rgba(0, 0, 0, .45)
}

.ant-upload-picture-card-wrapper {
  zoom: 1;
  display: inline-block;
  width: 100%
}

.ant-upload-picture-card-wrapper:after,
.ant-upload-picture-card-wrapper:before {
  display: table;
  content: ""
}

.ant-upload-picture-card-wrapper:after {
  clear: both
}

.ant-upload-list {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: rgba(0, 0, 0, .65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
  zoom: 1
}

.ant-upload-list:after,
.ant-upload-list:before {
  display: table;
  content: ""
}

.ant-upload-list:after {
  clear: both
}

.ant-upload-list-item-list-type-text:hover .ant-upload-list-item-name-icon-count-1 {
  padding-right: 14px
}

.ant-upload-list-item-list-type-text:hover .ant-upload-list-item-name-icon-count-2 {
  padding-right: 28px
}

.ant-upload-list-item {
  position: relative;
  height: 22px;
  margin-top: 8px;
  font-size: 14px
}

.ant-upload-list-item-name {
  display: inline-block;
  width: 100%;
  padding-left: 22px;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis
}

.ant-upload-list-item-name-icon-count-1 {
  padding-right: 14px
}

.ant-upload-list-item-card-actions {
  position: absolute;
  right: 0;
  opacity: 0
}

.ant-upload-list-item-card-actions.picture {
  top: 25px;
  line-height: 1;
  opacity: 1
}

.ant-upload-list-item-card-actions .anticon {
  padding-right: 5px;
  color: rgba(0, 0, 0, .45)
}

.ant-upload-list-item-info {
  height: 100%;
  padding: 0 12px 0 4px;
  -webkit-transition: background-color .3s;
  transition: background-color .3s
}

.ant-upload-list-item-info>span {
  display: block;
  width: 100%;
  height: 100%
}

.ant-upload-list-item-info .anticon-loading,
.ant-upload-list-item-info .anticon-paper-clip {
  position: absolute;
  top: 5px;
  color: rgba(0, 0, 0, .45);
  font-size: 14px
}

.ant-upload-list-item .anticon-close {
  display: inline-block;
  font-size: 12px;
  font-size: 10px\9;
  -webkit-transform: scale(.83333333) rotate(0deg);
  transform: scale(.83333333) rotate(0deg);
  position: absolute;
  top: 6px;
  right: 4px;
  color: rgba(0, 0, 0, .45);
  line-height: 0;
  cursor: pointer;
  opacity: 0;
  -webkit-transition: all .3s;
  transition: all .3s
}

:root .ant-upload-list-item .anticon-close {
  font-size: 12px
}

.ant-upload-list-item .anticon-close:hover {
  color: rgba(0, 0, 0, .65)
}

.ant-upload-list-item:hover .ant-upload-list-item-info {
  background-color: #e8f8ff
}

.ant-upload-list-item:hover .ant-upload-list-item-card-actions,
.ant-upload-list-item:hover .anticon-close {
  opacity: 1
}

.ant-upload-list-item-error,
.ant-upload-list-item-error .ant-upload-list-item-name,
.ant-upload-list-item-error .anticon-paper-clip {
  color: #f5222d
}

.ant-upload-list-item-error .ant-upload-list-item-card-actions {
  opacity: 1
}

.ant-upload-list-item-error .ant-upload-list-item-card-actions .anticon {
  padding-right: 5px;
  color: #f5222d
}

.ant-upload-list-item-progress {
  position: absolute;
  bottom: -12px;
  width: 100%;
  padding-left: 26px;
  font-size: 14px;
  line-height: 0
}

.ant-upload-list-picture-card .ant-upload-list-item,
.ant-upload-list-picture .ant-upload-list-item {
  position: relative;
  height: 66px;
  padding: 8px;
  border: 1px solid #d9d9d9;
  border-radius: 4px
}

.ant-upload-list-picture-card .ant-upload-list-item:hover,
.ant-upload-list-picture .ant-upload-list-item:hover {
  background: transparent
}

.ant-upload-list-picture-card .ant-upload-list-item-error,
.ant-upload-list-picture .ant-upload-list-item-error {
  border-color: #f5222d
}

.ant-upload-list-picture-card .ant-upload-list-item-info,
.ant-upload-list-picture .ant-upload-list-item-info {
  padding: 0
}

.ant-upload-list-picture-card .ant-upload-list-item:hover .ant-upload-list-item-info,
.ant-upload-list-picture .ant-upload-list-item:hover .ant-upload-list-item-info {
  background: transparent
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading,
.ant-upload-list-picture .ant-upload-list-item-uploading {
  border-style: dashed
}

.ant-upload-list-picture-card .ant-upload-list-item-thumbnail,
.ant-upload-list-picture .ant-upload-list-item-thumbnail {
  position: absolute;
  top: 8px;
  left: 8px;
  width: 48px;
  height: 48px;
  font-size: 26px;
  line-height: 54px;
  text-align: center;
  opacity: .8
}

.ant-upload-list-picture-card .ant-upload-list-item-icon,
.ant-upload-list-picture .ant-upload-list-item-icon {
  position: absolute;
  top: 50%;
  left: 50%;
  font-size: 26px;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%)
}

.ant-upload-list-picture-card .ant-upload-list-item-image,
.ant-upload-list-picture .ant-upload-list-item-image {
  max-width: 100%
}

.ant-upload-list-picture-card .ant-upload-list-item-thumbnail img,
.ant-upload-list-picture .ant-upload-list-item-thumbnail img {
  display: block;
  width: 48px;
  height: 48px;
  overflow: hidden
}

.ant-upload-list-picture-card .ant-upload-list-item-name,
.ant-upload-list-picture .ant-upload-list-item-name {
  display: inline-block;
  box-sizing: border-box;
  max-width: 100%;
  margin: 0 0 0 8px;
  padding-right: 8px;
  padding-left: 48px;
  overflow: hidden;
  line-height: 44px;
  white-space: nowrap;
  text-overflow: ellipsis;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-upload-list-picture-card .ant-upload-list-item-name-icon-count-1,
.ant-upload-list-picture .ant-upload-list-item-name-icon-count-1 {
  padding-right: 18px
}

.ant-upload-list-picture-card .ant-upload-list-item-name-icon-count-2,
.ant-upload-list-picture .ant-upload-list-item-name-icon-count-2 {
  padding-right: 36px
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading .ant-upload-list-item-name,
.ant-upload-list-picture .ant-upload-list-item-uploading .ant-upload-list-item-name {
  line-height: 28px
}

.ant-upload-list-picture-card .ant-upload-list-item-progress,
.ant-upload-list-picture .ant-upload-list-item-progress {
  bottom: 14px;
  width: calc(100% - 24px);
  margin-top: 0;
  padding-left: 56px
}

.ant-upload-list-picture-card .anticon-close,
.ant-upload-list-picture .anticon-close {
  position: absolute;
  top: 8px;
  right: 8px;
  line-height: 1;
  opacity: 1
}

.ant-upload-list-picture-card.ant-upload-list:after {
  display: none
}

.ant-upload-list-picture-card .ant-upload-list-item {
  float: left;
  width: 104px;
  height: 104px;
  margin: 0 8px 8px 0
}

.ant-upload-list-picture-card .ant-upload-list-item-info {
  position: relative;
  height: 100%;
  overflow: hidden
}

.ant-upload-list-picture-card .ant-upload-list-item-info:before {
  position: absolute;
  z-index: 1;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, .5);
  opacity: 0;
  -webkit-transition: all .3s;
  transition: all .3s;
  content: " "
}

.ant-upload-list-picture-card .ant-upload-list-item:hover .ant-upload-list-item-info:before {
  opacity: 1
}

.ant-upload-list-picture-card .ant-upload-list-item-actions {
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 10;
  white-space: nowrap;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  opacity: 0;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-delete,
.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-download,
.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-eye-o {
  z-index: 10;
  width: 16px;
  margin: 0 4px;
  color: hsla(0, 0%, 100%, .85);
  font-size: 16px;
  cursor: pointer;
  -webkit-transition: all .3s;
  transition: all .3s
}

.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-delete:hover,
.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-download:hover,
.ant-upload-list-picture-card .ant-upload-list-item-actions .anticon-eye-o:hover {
  color: #fff
}

.ant-upload-list-picture-card .ant-upload-list-item-actions:hover,
.ant-upload-list-picture-card .ant-upload-list-item-info:hover+.ant-upload-list-item-actions {
  opacity: 1
}

.ant-upload-list-picture-card .ant-upload-list-item-thumbnail,
.ant-upload-list-picture-card .ant-upload-list-item-thumbnail img {
  position: static;
  display: block;
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover
}

.ant-upload-list-picture-card .ant-upload-list-item-name {
  display: none;
  margin: 8px 0 0;
  padding: 0;
  line-height: 1.5;
  text-align: center
}

.ant-upload-list-picture-card .anticon-picture+.ant-upload-list-item-name {
  display: block
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading.ant-upload-list-item {
  background-color: #fafafa
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading .ant-upload-list-item-info {
  height: auto
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading .ant-upload-list-item-info .anticon-delete,
.ant-upload-list-picture-card .ant-upload-list-item-uploading .ant-upload-list-item-info .anticon-eye-o,
.ant-upload-list-picture-card .ant-upload-list-item-uploading .ant-upload-list-item-info:before {
  display: none
}

.ant-upload-list-picture-card .ant-upload-list-item-uploading-text {
  margin-top: 18px;
  color: rgba(0, 0, 0, .45)
}

.ant-upload-list-picture-card .ant-upload-list-item-progress {
  bottom: 32px;
  padding-left: 0
}

.ant-upload-list .ant-upload-success-icon {
  color: #52c41a;
  font-weight: 700
}

.ant-upload-list .ant-upload-animate-enter,
.ant-upload-list .ant-upload-animate-inline-enter,
.ant-upload-list .ant-upload-animate-inline-leave,
.ant-upload-list .ant-upload-animate-leave {
  -webkit-animation-duration: .3s;
  animation-duration: .3s;
  -webkit-animation-fill-mode: cubic-bezier(.78, .14, .15, .86);
  animation-fill-mode: cubic-bezier(.78, .14, .15, .86)
}

.ant-upload-list .ant-upload-animate-enter {
  -webkit-animation-name: uploadAnimateIn;
  animation-name: uploadAnimateIn
}

.ant-upload-list .ant-upload-animate-leave {
  -webkit-animation-name: uploadAnimateOut;
  animation-name: uploadAnimateOut
}

.ant-upload-list .ant-upload-animate-inline-enter {
  -webkit-animation-name: uploadAnimateInlineIn;
  animation-name: uploadAnimateInlineIn
}

.ant-upload-list .ant-upload-animate-inline-leave {
  -webkit-animation-name: uploadAnimateInlineOut;
  animation-name: uploadAnimateInlineOut
}

@-webkit-keyframes uploadAnimateIn {
  0% {
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@keyframes uploadAnimateIn {
  0% {
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@-webkit-keyframes uploadAnimateOut {
  to {
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@keyframes uploadAnimateOut {
  to {
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@-webkit-keyframes uploadAnimateInlineIn {
  0% {
    width: 0;
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@keyframes uploadAnimateInlineIn {
  0% {
    width: 0;
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@-webkit-keyframes uploadAnimateInlineOut {
  to {
    width: 0;
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@keyframes uploadAnimateInlineOut {
  to {
    width: 0;
    height: 0;
    margin: 0;
    padding: 0;
    opacity: 0
  }
}

@media (min-width:480px) {
  .hidden-xs-up {
    display: none !important
  }
}

@media (max-width:575px) {
  .hidden-xs-down {
    display: none !important
  }
}

@media (min-width:576px) {
  .hidden-sm-up {
    display: none !important
  }
}

@media (max-width:767px) {
  .hidden-sm-down {
    display: none !important
  }
}

@media (min-width:768px) {
  .hidden-md-up {
    display: none !important
  }
}

@media (max-width:991px) {
  .hidden-md-down {
    display: none !important
  }
}

@media (min-width:992px) {
  .hidden-lg-up {
    display: none !important
  }
}

@media (max-width:1199px) {
  .hidden-lg-down {
    display: none !important
  }
}

@media (min-width:1200px) {
  .hidden-xl-up {
    display: none !important
  }
}

@media (min-width:1599px) {
  .hidden-xl-down {
    display: none !important
  }
}

@media (min-width:1600px) {
  .hidden-xxl-up {
    display: none !important
  }
}

.hidden-xxl-down {
  display: none !important
}

@media (max-width:991px) {
  .hidden-slogan-down {
    z-index: 999;
    margin-bottom: 10px
  }

  .hidden-slogan-down h2 {
    font-size: 16px !important;
    font-weight: 500;
    line-height: 30px !important;
    text-align: center;
    color: #fff;
    margin-bottom: 0
  }
}

.page-not-found {
  background: #eaf8fe;
  height: 100vh
}

.page-not-found .page-header {
  height: 240px
}

.page-not-found .header {
  position: relative;
  margin-top: -3.15%;
  overflow: hidden
}

.page-not-found .header img {
  width: 100%
}

.page-not-found .message {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.page-not-found .message h1 {
  font-size: 48px
}

.page-not-found .message h3 {
  font-size: 32px;
  font-weight: 400
}

.page-not-found .btn-action {
  margin-top: 36px;
  border-radius: 18px
}

@media (max-width:1199px) {
  .page-not-found .message h1 {
    font-size: 40px
  }

  .page-not-found .message h3 {
    font-size: 24px
  }
}

@media (max-width:991px) {
  .page-not-found .message h1 {
    font-size: 36px
  }

  .page-not-found .message h3 {
    font-size: 20px
  }
}

@media (max-width:767px) {
  .page-not-found .header img {
    width: 160%;
    margin: 0 -30%
  }
}

@media (max-width:479px) {
  .page-not-found .message h1 {
    font-size: 30px
  }

  .page-not-found .message h3 {
    font-size: 16px
  }
}

.app-alert {
  height: 48px;
  padding: 12px 36px
}

.contact-form .ant-form-item .ant-form-item-control-wrapper .ant-form-item-control {
  width: 100%
}

.contact-form .ant-form-item.courses-select .ant-form-item-children {
  position: relative;
  display: block;
  height: 32px
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .suffix {
  position: absolute;
  right: 10px;
  top: 10px;
  z-index: 1;
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s;
  font-size: 14px
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .suffix.up {
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection {
  height: 32px;
  padding-left: 11px;
  padding-bottom: 0
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered {
  height: 100%;
  margin: 0;
  padding-right: 26px
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered .ant-select-selection__placeholder {
  margin: 0;
  top: 0;
  height: 30px;
  line-height: 30px
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul {
  height: 30px;
  padding: 3px 0;
  display: flex
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li {
  margin-top: 0;
  height: auto;
  line-height: 22px
}

.contact-form .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li .ant-select-search__field__wrap {
  width: 0;
  overflow: hidden
}

.consultant-courses-options {
  z-index: 9
}

.consultant-courses-options>div {
  overflow: visible !important
}

.consultant-courses-options .ant-select-dropdown-menu {
  overflow: visible;
  padding: 16px 20px;
  max-height: none
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item-group-title {
  height: auto;
  padding-bottom: 8px
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item {
  line-height: 42px
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item:hover .ant-select-selected-icon {
  color: transparent
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item-selected .ant-select-selected-icon {
  color: #fff;
  background-color: #75889a
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item-selected:hover .ant-select-selected-icon {
  color: #fff
}

.consultant-courses-options .ant-select-dropdown-menu .ant-select-dropdown-menu-item .ant-select-selected-icon {
  align-items: center;
  display: inline-flex !important;
  justify-content: center;
  border: 1px solid #75889a;
  width: 20px;
  height: 20px
}

.consultant-courses-options .ant-btn {
  border-radius: 0;
  height: 48px
}

.consultant-courses-options.limited-height .ant-select-dropdown-menu {
  padding-top: 12px;
  padding-bottom: 12px
}

.consultant-courses-options.limited-height .ant-select-dropdown-menu-item {
  line-height: 32px
}

.consultant-courses-options.limited-height .ant-select-dropdown-menu-item-group-list {
  display: flex;
  flex-wrap: wrap
}

.consultant-courses-options.limited-height .ant-select-dropdown-menu-item-group-list>li {
  min-width: 50%;
  white-space: nowrap
}

.consultant-courses-options.limited-height .ant-btn {
  height: 38px
}

.contact-modal .ant-modal-body {
  padding: 24px;
  display: flex
}

.contact-modal .ant-modal-body .contact-container {
  background: #f7fafc;
  padding: 24px;
  margin-right: 24px
}

.contact-modal .ant-modal-body .contact-container:last-child {
  margin-right: 0
}

.contact-modal .ant-modal-body .contact-container .top-area {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  margin-bottom: 24px
}

.contact-modal .ant-modal-body .contact-container .top-area img {
  max-width: 120px
}

.contact-modal .ant-modal-body .contact-container .top-area h3 {
  font-size: 18px;
  font-weight: 600
}

.contact-modal .ant-modal-body .contact-container .top-area p {
  margin-top: 12px;
  margin-bottom: 0
}

.contact-modal .ant-modal-body .contact-container .ant-form .ant-form-item {
  margin-bottom: 18px
}

.contact-modal .ant-modal-body .wechat-container {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  width: 300px;
  flex: 0 0 300px;
  text-align: center
}

.contact-modal .ant-modal-body .wechat-container .top-area {
  margin-bottom: 0
}

.contact-modal .ant-modal-body .email-container {
  width: calc(100% - 324px)
}

.footer {
  position: relative;
  background: #00274b
}

.footer.container {
  overflow: visible;
  padding-bottom: 24px !important
}

.footer .mask {
  position: absolute;
  top: -84px;
  left: 0;
  right: 0;
  overflow: hidden
}

.footer .mask .mask-inner {
  width: 100%;
  height: 84px;
  border-left: 1920px solid transparent;
  border-bottom: 84px solid #00274b
}

.footer .logo {
  height: 48px;
  margin: 0 48px;
  opacity: .15;
  float: right
}

.footer .social-media {
  border-top: 1px solid #435060;
  margin-top: 24px;
  padding-top: 24px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: hsla(0, 0%, 100%, .85)
}

.footer .social-media div[class*=ant-col-] {
  text-align: center
}

.footer .social-media div[class*=ant-col-].qr-code {
  text-align: left
}

.footer .social-media div[class*=ant-col-].qr-code img {
  height: 64px
}

.footer .social-media a {
  line-height: 1;
  color: hsla(0, 0%, 100%, .65);
  -webkit-transition: color .2s ease;
  transition: color .2s ease;
  margin-left: 9px
}

.footer .social-media a .anticon {
  font-size: 22px
}

.footer .social-media a:active,
.footer .social-media a:focus,
.footer .social-media a:hover {
  color: hsla(0, 0%, 100%, .85)
}

.footer .resource-column h4 {
  display: flex;
  align-items: center;
  color: hsla(0, 0%, 100%, .85)
}

.footer .resource-column a {
  display: block;
  margin-top: 6px;
  color: hsla(0, 0%, 100%, .65)
}

.footer .resource-column a:active,
.footer .resource-column a:focus,
.footer .resource-column a:hover {
  color: hsla(0, 0%, 100%, .85)
}

.footer .resource-column a[disabled] {
  color: hsla(0, 0%, 100%, .35)
}

@media (max-width:1199px) {
  .footer .resource-column a {
    font-size: 13px
  }
}

@media (max-width:767px) {
  .footer .social-media {
    flex-flow: column nowrap
  }

  .footer .social-media div[class*=ant-col-] {
    margin-top: 12px
  }

  .footer .social-media div[class*=ant-col-].qr-code {
    margin-top: 0;
    text-align: center
  }

  .footer .resource-column {
    margin-top: 24px
  }
}

.ant-layout-header {
  position: fixed;
  width: 100%;
  box-shadow: inset 0 -1px 0 0 #e9e9e9;
  z-index: 999;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

.ant-layout-header .logo {
  width: 160px;
  height: 32px;
  margin: 16px 28px 16px 0;
  float: left;
  display: flex
}

.ant-layout-header .logo img {
  height: 34px
}

.ant-layout-header .ant-menu.ant-menu-horizontal {
  background: transparent;
  line-height: 64px;
  border-bottom: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu {
  border: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item.highlight,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu.highlight {
  padding-left: 20px
}

@-webkit-keyframes breathing {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  25% {
    -webkit-transform: scale(2);
    transform: scale(2)
  }

  60% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

@keyframes breathing {
  0% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  25% {
    -webkit-transform: scale(2);
    transform: scale(2)
  }

  60% {
    -webkit-transform: scale(1);
    transform: scale(1)
  }

  to {
    -webkit-transform: scale(1);
    transform: scale(1)
  }
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item.highlight .breathing-dot,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item.highlight .breathing-dot-inner,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu.highlight .breathing-dot,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu.highlight .breathing-dot-inner {
  position: absolute;
  top: calc(50% - 8px);
  left: -8px;
  height: 16px;
  width: 16px;
  background: #eb5464;
  border-radius: 50%
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item.highlight .breathing-dot,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu.highlight .breathing-dot {
  opacity: .4;
  -webkit-animation: breathing 2s ease-out infinite normal;
  animation: breathing 2s ease-out infinite normal
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-item.highlight .breathing-dot-inner,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu.highlight .breathing-dot-inner {
  border: 2px solid #fff;
  box-shadow: 0 0 2px #fff
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu>.ant-menu-submenu-title {
  padding-right: 12px
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-item-active,
.ant-layout-header .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-item-selected {
  box-shadow: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-active,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-selected,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-submenu-active,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-submenu-selected {
  box-shadow: inset 0 -3px 0 0 #03a9f4;
  border-bottom: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-active,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-selected {
  color: rgba(0, 0, 0, .65)
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.menu-item-aside {
  float: right;
  height: 64px;
  display: flex;
  align-items: center
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn {
  background: transparent;
  color: rgba(0, 0, 0, .65);
  border: 1px solid #d9d9d9;
  padding: 0 12px
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn a {
  -webkit-transition: none;
  transition: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn a:focus {
  text-decoration: none
}

.ant-layout-header .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn.active {
  background: #e8f8ff
}

.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-active.menu-item-aside,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-item-selected.menu-item-aside,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-submenu-active.menu-item-aside,
.ant-layout-header .ant-menu.ant-menu-horizontal .ant-menu-submenu-selected.menu-item-aside {
  box-shadow: none
}

.ant-layout-header .btn-mobile-menu {
  float: right;
  width: 36px;
  height: 32px;
  margin: 16px 0;
  background: transparent;
  border: none;
  font-weight: 600;
  color: #03a9f4;
  background: url(/images/icons/hamburger-blue.svg) 50% no-repeat;
  background-size: 60%;
  -webkit-transition: background-color .2s ease;
  transition: background-color .2s ease
}

.ant-layout-header .btn-mobile-menu:focus,
.ant-layout-header .btn-mobile-menu:hover {
  background-color: #e8f8ff
}

.ant-layout-header .btn-mobile-menu:active {
  background-color: #c9eeff
}

.ant-layout-header.header-top {
  background: transparent;
  box-shadow: none
}

.ant-layout-header.header-top.landing .ant-menu.ant-menu-horizontal .ant-menu-submenu-title,
.ant-layout-header.header-top.landing .ant-menu.ant-menu-horizontal>.ant-menu-item,
.ant-layout-header.header-top.landing .ant-menu.ant-menu-horizontal>.ant-menu-submenu {
  color: rgba(0, 0, 0, .65) !important
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-item,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu {
  border: none;
  color: hsla(0, 0%, 100%, .8)
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-item>a,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu>a {
  color: hsla(0, 0%, 100%, .8)
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-item>a:active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-item>a:focus,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-item>a:hover,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-submenu-title:active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-submenu-title:focus,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-submenu-title:hover,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu>a:active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu>a:focus,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu>a:hover {
  color: #fff
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-item-active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.ant-menu-submenu .ant-menu-item-selected {
  box-shadow: none
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-selected,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-submenu-active,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-submenu-selected {
  color: #fff;
  box-shadow: inset 0 -3px 0 0 #fff;
  border-bottom: none
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.menu-item-aside {
  float: right;
  height: 64px;
  display: flex;
  align-items: center
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn {
  color: #fff;
  border: 1px solid hsla(0, 0%, 100%, .8)
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal>.menu-item-aside .ant-btn-group .ant-btn.active {
  background: hsla(0, 0%, 100%, .35)
}

.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-active.menu-item-aside,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-active.no-border-bottom,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-selected.menu-item-aside,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-item-selected.no-border-bottom,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-submenu-active.menu-item-aside,
.ant-layout-header.header-top .ant-menu.ant-menu-horizontal .ant-menu-submenu-selected.menu-item-aside {
  box-shadow: none
}

.ant-layout-header.header-top .btn-mobile-menu {
  color: #fff;
  background-image: url(/images/icons/hamburger.svg)
}

.ant-layout-header.header-top .btn-mobile-menu:focus,
.ant-layout-header.header-top .btn-mobile-menu:hover {
  background-color: hsla(0, 0%, 100%, .2)
}

.ant-layout-header.header-top .btn-mobile-menu:active {
  background-color: hsla(0, 0%, 100%, .4)
}

.ant-layout-header.header-normal {
  background: hsla(0, 0%, 100%, .85)
}

.ant-popover .ant-menu.ant-menu-inline {
  border: none;
  width: 360px
}

.ant-popover .ant-menu.ant-menu-inline>.ant-menu-item {
  padding: 0 24px
}

.ant-popover .ant-menu.ant-menu-inline>.menu-item-aside {
  text-align: center;
  margin: 12px 0
}

.ant-popover .ant-menu.ant-menu-inline>.menu-item-aside.ant-menu-item-selected {
  background: transparent
}

.ant-popover .ant-menu.ant-menu-inline>.menu-item-aside.ant-menu-item-selected:after {
  border: none
}

@media (max-width:991px) {
  .ant-layout-header {
    padding: 0 24px
  }
}

@media (max-width:479px) {
  .ant-layout-header {
    padding: 0 18px
  }
}

.container {
  padding: 48px 0;
  max-width: 100%;
  overflow-x: hidden
}

.container>.main-title {
  font-size: 32px;
  padding-bottom: 18px;
  margin-bottom: 36px;
  text-align: center;
  position: relative
}

.container>.main-title .side-link {
  font-size: 16px;
  font-weight: 400;
  position: absolute;
  right: 36px;
  bottom: 0;
  text-transform: lowercase
}

.container>.sub-title {
  margin: -18px auto 36px;
  padding: 0 20%;
  font-size: 16px;
  text-align: center;
  position: relative
}

.container:last-child {
  padding-bottom: 120px
}

.float-container {
  box-shadow: 0 0 2px rgba(0, 0, 0, .15);
  border-radius: 2px;
  background: #fff;
  width: 80%;
  margin: 0 10%;
  padding: 48px;
  position: relative
}

.post-container .markdown-content h1,
.post-container .markdown-content h2 {
  margin-top: 24px
}

.post-container .markdown-content h3,
.post-container .markdown-content h4 {
  margin-top: 18px
}

.post-container .markdown-content h5,
.post-container .markdown-content h6 {
  margin-top: 12px
}

.post-container .markdown-content p {
  margin: 18px 0
}

.post-container .markdown-content ul {
  list-style: square inside none;
  margin: 18px 0
}

.post-container .markdown-content img {
  width: 80%;
  max-width: 640px;
  display: block;
  margin: 25px auto
}

.post-container .markdown-content iframe {
  width: 100%;
  height: 30vw
}

@media (max-width:1199px) {
  .post-container .markdown-content iframe {
    height: 40vw
  }
}

@media (max-width:991px) {
  .post-container .markdown-content iframe {
    height: 50vw
  }
}

@media (max-width:991px) {
  .container {
    padding: 36px 0
  }

  .container>.main-title {
    font-size: 28px
  }

  .container>.sub-title {
    font-size: 13px
  }

  .float-container {
    width: 90%;
    margin: 0 5%;
    padding: 36px
  }
}

.news-side-bar>div {
  background: hsla(0, 0%, 100%, .9)
}

.news-side-bar>div[aria-hidden=true] {
  opacity: 0
}

.news-side-bar h2 {
  margin-bottom: 12px;
  padding: 0 18px
}

.news-side-bar ul {
  list-style: none;
  padding: 0 18px
}

.news-side-bar ul li {
  padding: 6px 0
}

.news-side-bar ul li a {
  color: rgba(0, 0, 0, .45)
}

.news-side-bar ul li a:focus,
.news-side-bar ul li a:hover {
  color: #2bc3ff
}

.news-side-bar ul li a:active {
  color: #0086cf
}

.news-side-bar .subscribe-form {
  margin-top: 24px;
  padding: 24px 18px;
  background: #f5f5f5;
  position: relative
}

.news-side-bar .subscribe-form .button-bar {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  margin: 0
}

.news-side-bar .subscribe-form .ant-btn[type=submit] {
  width: 100%;
  border-top-left-radius: 0;
  border-top-right-radius: 0;
  padding: 0
}

@media (max-width:1199px) {
  .news-side-bar .subscribe-form {
    padding: 12px 12px 18px
  }
}

@media (max-width:991px) {
  .news-side-bar .subscribe-form .ant-btn[type=submit] {
    font-size: 14px
  }
}

.page-header {
  height: 240px;
  padding: 64px 15% 36px;
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  background: #435060;
  overflow: hidden
}

.page-header .background {
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  position: absolute;
  top: 0;
  bottom: 0;
  left: -1px;
  right: -1px
}

.page-header .content {
  flex: 1 1 auto;
  width: 100%;
  height: 100%;
  z-index: 1;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  color: #fff
}

.page-header .content .page-title {
  color: #fff;
  text-align: center;
  display: flex;
  max-width: 100%;
  max-height: 61.6px;
  font-size: 28px;
  line-height: 1.1;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.page-header .content .page-sub-title {
  color: #fff;
  line-height: 1.3;
  text-align: center;
  margin: 12px 0;
  -webkit-box-align: center !important
}

.page-header .content .page-sub-title:last-child {
  margin-bottom: 0
}

a.btn.btn-cta,
button.btn.btn-cta {
  display: inline-block;
  background: #eb2f96;
  margin: 0;
  padding: 0 16px;
  line-height: 32px;
  height: 32px;
  font-size: 14px;
  color: #fff;
  border-radius: 16px;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

a.btn.btn-cta:active,
a.btn.btn-cta:focus,
a.btn.btn-cta:hover,
button.btn.btn-cta:active,
button.btn.btn-cta:focus,
button.btn.btn-cta:hover {
  background: #f759ab;
  color: #fff
}

a.btn-action,
button.btn-action {
  line-height: 36px;
  height: 36px;
  padding: 0 18px;
  font-size: 16px;
  background: #03a9f4;
  color: #fff;
  border: none
}

a.btn-action:focus,
a.btn-action:hover,
button.btn-action:focus,
button.btn-action:hover {
  color: #fff;
  background: #2bc3ff
}

a.btn-action:active,
button.btn-action:active {
  color: #fff;
  background: #0086cf
}

a.btn-action.inverted,
button.btn-action.inverted {
  background: #fff;
  color: #03a9f4
}

a.btn-action.inverted:focus,
a.btn-action.inverted:hover,
button.btn-action.inverted:focus,
button.btn-action.inverted:hover {
  color: #2bc3ff
}

a.btn-action.inverted:active,
button.btn-action.inverted:active {
  color: #0086cf
}

a.btn-link,
button.btn-link {
  line-height: 36px;
  height: 36px;
  padding: 0 18px;
  font-size: 16px;
  color: #03a9f4;
  border: none;
  cursor: pointer;
  background: transparent
}

a.btn-link:focus,
a.btn-link:hover,
button.btn-link:focus,
button.btn-link:hover {
  color: #2bc3ff
}

a.btn-link:active,
button.btn-link:active {
  color: #0086cf
}

a.btn-link.inverted,
button.btn-link.inverted {
  color: #fff;
  border: 2px solid hsla(0, 0%, 100%, .8);
  line-height: 32px
}

a.btn-link.inverted.active,
a.btn-link.inverted:focus,
a.btn-link.inverted:hover,
button.btn-link.inverted.active,
button.btn-link.inverted:focus,
button.btn-link.inverted:hover {
  color: rgba(0, 0, 0, .65);
  background: hsla(0, 0%, 100%, .8)
}

.tag-container {
  display: flex;
  flex-flow: row wrap
}

.tag-container .tag {
  font-size: 12px;
  font-weight: 300;
  color: #0072a7;
  line-height: 24px;
  height: 24px;
  padding: 6px 12px;
  background: #c9eeff;
  display: inline-block;
  border-radius: 12px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 6px 6px 0 0
}

.stats-container {
  display: flex;
  flex-flow: row nowrap;
  align-items: baseline;
  max-width: 100%;
  color: #757575
}

.stats-container>* {
  display: inline-block;
  flex: 0 0 auto;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.stats-container .stats-count {
  font-size: 120%;
  font-weight: 500;
  margin-right: 6px
}

.stats-container .stats-separator {
  font-size: 120%;
  margin: 0 8px
}

.date-badge {
  width: 72px;
  height: 72px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.date-badge .month {
  text-transform: uppercase;
  font-size: 14px;
  line-height: 14px;
  color: #fff
}

.date-badge .day {
  font-size: 26px;
  line-height: 26px;
  color: #fff
}

.video-badge {
  width: 72px;
  height: 72px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.video-badge .play {
  width: 0;
  height: 0;
  border-top: 16px solid transparent;
  border-left: 24px solid #fff;
  border-bottom: 16px solid transparent;
  margin-left: 4px
}

.label {
  width: 164px;
  height: 59px;
  padding: 0 32px 9px 13px;
  background: url(/images/shapes/label.svg) 50% no-repeat;
  position: absolute;
  left: -13px;
  color: #fff;
  font-size: 20px;
  line-height: 20px;
  text-transform: uppercase;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 9
}

.label.highlight {
  background: url(/images/shapes/label-highlight.svg) 50% no-repeat
}

.empty-container {
  width: 100%;
  min-height: 360px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.empty-container .empty-title {
  font-size: 24px
}

.empty-container .empty-message {
  margin-top: 12px
}

.timer {
  display: flex
}

.timer .number {
  line-height: .9;
  font-size: 180%;
  font-weight: 500;
  font-style: normal;
  margin: 0 3px 0 12px;
  color: rgba(0, 0, 0, .65)
}

.timer .number:first-child {
  margin-left: 0
}

.timer span {
  line-height: 1.2;
  font-size: 80%;
  color: rgba(0, 0, 0, .45)
}

.count-down {
  height: 60px;
  font-size: 16px;
  display: flex;
  flex-flow: column nowrap;
  align-items: center
}

.count-down .count-down-label {
  margin-bottom: 6px
}

.dash {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin: auto;
  width: 48px;
  height: 3px;
  background: #03a9f4
}

.image-thumbnail-container {
  position: relative
}

.image-thumbnail-container img {
  width: 100%;
  height: 100%
}

.image-thumbnail-container .video-duration {
  padding: 0 6px;
  background: rgba(0, 0, 0, .8);
  height: 24px;
  line-height: 24px;
  border-radius: 2px;
  color: #fff;
  position: absolute;
  top: 12px;
  right: 12px
}

.categries {
  text-transform: uppercase;
  margin: 0;
  font-size: 11px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.categries,
time {
  color: rgba(0, 0, 0, .45)
}

time {
  font-size: 12px
}

.subscribe-container {
  padding: 36px 15% 120px;
  background: #fff
}

.subscribe-container h3 {
  color: rgba(0, 0, 0, .45);
  text-align: center;
  font-size: 18px;
  margin-bottom: 12px
}

.one-line-form {
  display: flex;
  justify-content: center
}

.one-line-form .ant-form-item,
.one-line-form .ant-form-item-control-wrapper {
  margin: 0
}

.one-line-form input {
  border-top-right-radius: 0;
  border-bottom-right-radius: 0;
  min-width: 264px
}

.one-line-form button {
  border-top-left-radius: 0;
  border-bottom-left-radius: 0
}

@media (max-width:1199px) {
  .video-badge {
    width: 48px;
    height: 48px
  }
}

.activities-dot {
  position: fixed;
  bottom: 0;
  right: 10px;
  z-index: 999
}

.activities-dot .activities-home {
  position: fixed;
  bottom: 100px;
  right: 80px;
  z-index: 99
}

.activities-dot .activities-home .breathing-dot,
.activities-dot .activities-home .breathing-dot-inner {
  cursor: pointer;
  position: absolute;
  top: calc(50% - 25px);
  left: -25px;
  height: 50px;
  width: 50px;
  background: #faa029;
  border-radius: 50%
}

.activities-dot .activities-home .breathing-dot {
  opacity: .4;
  -webkit-animation: breathing 2s ease-out infinite normal;
  animation: breathing 2s ease-out infinite normal
}

.activities-dot .activities-home .breathing-dot-inner {
  border: 2px solid #fff;
  box-shadow: 0 0 2px #fff;
  padding: 6px 11px;
  line-height: 16px
}

.activities-dot .activities-home .breathing-dot-inner span {
  color: #fff;
  font-size: 12px;
  display: inline-block;
  width: 32px
}

.activities-dot .activities-samll {
  position: fixed;
  bottom: 20px;
  right: 10px;
  z-index: 999;
  border-top: none;
  width: 400px;
  -webkit-transform-origin: right bottom;
  transform-origin: right bottom;
  -webkit-transform: scale(.8);
  transform: scale(.8)
}

.activities-dot .activities-samll .small-activity-set {
  position: relative;
  border-radius: 5px
}

.activities-dot .activities-samll .small-activity-set .activities-box .ant-tabs-bar {
  margin: 0 !important
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box {
  margin-top: -1px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box section.banner {
  width: 100%;
  height: 200px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: 400px 200px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main {
  padding: 10px 40px;
  font-family: PingFang SC，medium;
  border: 1px solid #e8e8e8;
  border-top: none;
  border-radius: 0 0 5px 5px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-header {
  border-bottom: 1px solid #ecf0f5
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-header .title {
  font-size: 16px;
  line-height: 30px;
  color: #304d67
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-header .lecture-main .title1 {
  margin: 0;
  color: #304d67;
  font-size: 14px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-header .lecture-main .title2 {
  margin: 0;
  color: #8294a5;
  font-size: 13px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-header .lecture-main .title3 {
  margin-bottom: 10px;
  color: #8294a5;
  font-size: 12px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer {
  text-align: center;
  height: 200px;
  color: #304d67;
  font-size: 16px;
  display: flex;
  justify-content: space-between;
  flex-direction: column
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer .title {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  line-height: 30px
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer .title .side-qrcode {
  margin: 30px 30px 0 0;
  border: 4px solid #c0cedb;
  height: 120px;
  width: 120px;
  display: block
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer .ant-form.ant-form-horizontal.way1-form {
  padding: 0
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer .checkout {
  text-align: right
}

.activities-dot .activities-samll .small-activity-set .activities-box .small-box .small-main .samll-side-footer .checkout .cursor {
  font-size: 12px;
  color: #8291a5;
  cursor: pointer
}

.activities-dot .activities-samll .small-activity-set .close-wrapper {
  position: absolute;
  right: 0;
  top: 40px;
  width: 100%;
  height: 40px;
  z-index: 9999;
  display: flex;
  justify-content: flex-end
}

.activities-dot .activities-samll .small-activity-set .close-wrapper .close {
  color: #fff;
  margin: 5px;
  font-size: 1.2em;
  cursor: pointer
}

.activities-dot .ant-tabs .ant-tabs-bottom-content,
.activities-dot .ant-tabs .ant-tabs-top-content {
  background-color: #fff;
  box-shadow: 0 4px 16px 0 rgba(130, 148, 165, .2);
  border-radius: 5px
}

.activities-dot .ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab {
  color: #304d67
}

.activities-dot .ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab.ant-tabs-tab-active {
  color: #03a9f4
}

.activities-dot .ant-tabs {
  overflow: visible
}

.activities-modal .ant-modal-content {
  background: transparent !important;
  border: none !important
}

.activities-modal .ant-modal-close {
  display: none !important
}

.activities-modal .ant-modal-body {
  padding: 0 !important;
  position: relative
}

.activities-modal .ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab {
  color: #304d67
}

.activities-modal .ant-tabs.ant-tabs-card .ant-tabs-card-bar .ant-tabs-tab.ant-tabs-tab-active {
  color: #03a9f4
}

.activities-modal .ant-tabs-nav-comtainer {
  margin-bottom: 0 !important
}

.activities-modal .activities-big {
  border-radius: 5px
}

.activities-modal .activities-big .panel-activities {
  position: relative
}

.activities-modal .activities-big .panel-activities .activities-box {
  min-height: 200px
}

.activities-modal .activities-big .panel-activities .activities-box .ant-tabs-bar {
  margin: 0 !important;
  border: none
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .banner {
  width: 100%;
  height: 350px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: 700px 350px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main {
  display: flex;
  justify-content: space-between;
  padding: 20px 30px;
  font-family: PingFang SC，medium;
  background-color: #fff;
  border-radius: 0 0 5px 5px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header {
  border-right: 1px solid #ecf0f5;
  width: 50%;
  padding: 0 50px 0 20px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header .title {
  font-size: 18px;
  line-height: 24px;
  color: #304d67
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header .lecture-main {
  line-height: 24px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header .lecture-main .title1 {
  margin: 0;
  color: #304d67;
  font-size: 14px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header .lecture-main .title2 {
  margin: 0;
  color: #8294a5;
  font-size: 13px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-header .lecture-main .title3 {
  margin-bottom: 10px;
  color: #8294a5;
  font-size: 12px
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-footer {
  text-align: center;
  width: 45%;
  padding: 0 30px;
  min-height: 250px;
  color: #304d67;
  line-height: 30px;
  font-size: 16px;
  display: flex;
  justify-content: space-between;
  flex-direction: column
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-footer p {
  padding: 0;
  margin: 0
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-footer .inner-qrcode {
  border: 4px solid #c0cedb;
  height: 100px;
  width: 100px;
  margin: 0 auto;
  display: block
}

.activities-modal .activities-big .panel-activities .activities-box .small-box .small-main .samll-footer .checkout .cursor {
  font-size: 12px;
  color: #8291a5;
  cursor: pointer
}

.activities-modal .activities-big .panel-activities .close-wrapper {
  position: absolute;
  right: 0;
  top: 40px;
  width: 100%;
  height: 40px;
  z-index: 9999;
  display: flex;
  justify-content: flex-end
}

.activities-modal .activities-big .panel-activities .close-wrapper .close {
  color: #fff;
  margin: 5px;
  font-size: 1.2em;
  cursor: pointer
}

.activities-success .success-modal {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 20px 100px;
  text-align: center;
  line-height: 24x
}

.activities-success .success-modal .success-title {
  font-size: 16px;
  font-weight: 700;
  color: #304d67;
  line-height: 30x;
  margin: 10px 0
}

.activities-success .success-modal .success-done {
  font-size: 12px;
  color: #8294a5
}

.activities-success .success-modal .success-code {
  padding: 30px 0
}

.activities-success .success-modal .success-code img {
  width: 120px;
  height: 120px;
  border: 4px solid #ecf0f5
}

.activities-success .success-modal .success-footer {
  font-size: 14px;
  color: #304d67;
  line-height: 30x
}

.activitiesItem-modal .ant-modal-body {
  padding: 0 !important
}

.activitiesItem-modal .ant-modal-close-x {
  color: #fff !important
}

.activitiesItem-modal .activity-box .banner {
  width: 100%;
  height: 250px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: 500px 250px
}

.activitiesItem-modal .activity-box .acticities-item {
  text-align: center;
  padding: 20px 110px 30px;
  height: 310px;
  color: #304d67;
  line-height: 30px;
  font-size: 16px;
  display: flex;
  justify-content: space-between;
  flex-direction: column
}

.activitiesItem-modal .activity-box .acticities-item p {
  padding: 0;
  margin: 0
}

.activitiesItem-modal .activity-box .acticities-item .inner-qrcode {
  border: 4px solid #c0cedb;
  height: 100px;
  width: 100px;
  margin: 25px auto;
  display: block
}

.activitiesItem-modal .activity-box .acticities-item .checkout .cursor {
  font-size: 12px;
  color: #8291a5;
  cursor: pointer
}

@media (max-width:767px) {
  .activities-dot .arrows-alt {
    display: none
  }

  .activities-modal,
  .activities-modal .ant-modal-body {
    display: none !important
  }

  .activities-success .success-modal {
    display: flex;
    flex-direction: column;
    padding: 0 10%;
    text-align: center;
    line-height: 1.5rem;
    font-size: 1rem
  }

  .activities-success .success-modal .success-title {
    font-size: 1rem
  }

  .activities-success .success-modal .success-code,
  .activities-success .success-modal .success-done,
  .activities-success .success-modal .success-footer {
    display: none
  }

  .activitiesItem-modal {
    width: 80% !important
  }

  .activitiesItem-modal .activity-box .form-footer {
    padding: 15px;
    text-align: center
  }

  .activitiesItem-modal .activity-box .form-footer .txt-footer {
    text-align: center
  }
}

.course-detail.ai-and-data-engineering .tracks {
  margin-bottom: 5%
}

.course-detail.ai-and-data-engineering .tracks div[class*=ant-col-] {
  display: flex;
  margin-bottom: 18px
}

.course-detail.ai-and-data-engineering .tracks .ant-card {
  flex: 1 1 auto;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15);
  cursor: pointer;
  overflow: hidden
}

.course-detail.ai-and-data-engineering .tracks .card-head {
  height: 144px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: flex-start;
  position: relative;
  padding: 24px
}

.course-detail.ai-and-data-engineering .tracks .card-head .background {
  background: linear-gradient(225deg, rgba(0, 196, 255, .87), rgba(0, 39, 255, .67));
  opacity: .85;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail.ai-and-data-engineering .tracks .card-head .background.pink {
  background: linear-gradient(225deg, #e32eea, rgba(0, 39, 255, .7))
}

.course-detail.ai-and-data-engineering .tracks .card-head>* {
  position: relative
}

.course-detail.ai-and-data-engineering .tracks .card-head h2 {
  font-size: 28px;
  line-height: 1.1;
  color: #fff
}

.course-detail.ai-and-data-engineering .tracks .card-head h3 {
  font-size: 22px;
  font-weight: 400;
  color: #fff
}

.course-detail.ai-and-data-engineering .tracks .card-content {
  margin: 0;
  padding: 24px;
  width: 100%
}

.course-detail.ai-and-data-engineering .tracks .card-content .description {
  display: flex;
  max-width: 100%;
  max-height: 54.6px;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 14px;
  line-height: 1.3;
  margin: 0 0 18px;
  color: rgba(0, 0, 0, .65)
}

.course-detail.ai-and-data-engineering .tracks .card-content .tag-container {
  height: 60px
}

.course-detail.ai-and-data-engineering .tracks .card-content .bullets {
  list-style: square outside;
  margin: 24px 0 0;
  overflow: hidden
}

.course-detail.ai-and-data-engineering .instructor-team {
  overflow: hidden
}

.course-detail.ai-and-data-engineering .instructor-team img {
  display: inline-block;
  max-width: 80%;
  max-height: 360px;
  margin-bottom: -42px
}

@media (max-width:1199px) {
  .course-detail.ai-and-data-engineering .instructor-team {
    text-align: center
  }
}

@media (max-width:991px) {
  .course-detail.ai-and-data-engineering .tracks div[class*=ant-col-] .card-head h2 {
    font-size: 24px
  }

  .course-detail.ai-and-data-engineering .tracks div[class*=ant-col-] .card-head h3 {
    font-size: 20px
  }

  .course-detail.ai-and-data-engineering .tracks div[class*=ant-col-] .card-content .bullets,
  .course-detail.ai-and-data-engineering .tracks div[class*=ant-col-] .card-content .tag-container {
    height: auto
  }
}

.course-detail {
  background: url(/images/shapes/course-bg.svg) 0 -10% repeat-y;
  background-size: cover;
  overflow: hidden
}

.course-detail .page-header {
  height: 75vh;
  background: #00274b;
  overflow: hidden
}

.course-detail .page-header .background-video {
  background-color: #00274b;
  position: absolute;
  top: 0;
  bottom: 0;
  min-width: 100%;
  height: 75vh;
  -o-object-fit: cover;
  object-fit: cover
}

.course-detail .page-header .background,
.course-detail .page-header .background2 {
  background: linear-gradient(225deg, rgba(0, 196, 255, .5), rgba(0, 39, 255, .8));
  background-repeat: no-repeat;
  background-position: bottom;
  opacity: .4;
  position: absolute;
  height: 100%;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail .page-header .background2 {
  background: rgba(0, 0, 0, .3)
}

.course-detail .page-header .content {
  position: relative;
  padding-bottom: 24px
}

.course-detail .page-header .page-sub-title {
  display: flex;
  max-width: 100%;
  max-height: 36.4px;
  font-size: 14px;
  line-height: 1.3;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  justify-content: center
}

.course-detail .page-header .btn-bar {
  display: flex;
  margin-top: 24px
}

.course-detail .page-header .btn-bar>* {
  margin: 0 12px
}

.course-detail .page-header .btn-bar:first-child {
  margin-left: 0
}

.course-detail .page-header .btn-bar:last-child {
  margin-right: 0
}

.course-detail .page-header .count-down {
  position: absolute;
  bottom: 36px
}

.course-detail .page-header .count-down .timer>* {
  color: #fff
}

.course-detail .container .main-title,
.course-detail .container .sub-title {
  text-align: left;
  padding-left: 10%
}

.course-detail .container .main-title .dash,
.course-detail .container .sub-title .dash {
  margin: 0;
  left: 10%
}

.course-detail .content-container {
  padding: 48px calc(25% + 36px) 48px 10%;
  overflow: visible;
  font-size: 16px
}

.course-detail .content-container .main-title {
  padding-left: 0
}

.course-detail .content-container .main-title .dash {
  left: 0
}

.course-detail .content-container .sub-title {
  padding-left: 0;
  margin-top: -18px
}

.course-detail .content-container p {
  margin-top: 12px
}

.course-detail .content-container p:first-child {
  margin-top: 0
}

.course-detail .content-container .float-container {
  width: 100%;
  margin-left: 0;
  margin-right: 0
}

.course-detail .side-nav {
  position: absolute;
  top: calc(75vh + 156px);
  left: 75%;
  right: 10%
}

.course-detail .side-nav.uk ul>li>a:active,
.course-detail .side-nav.uk ul>li>a:focus,
.course-detail .side-nav.uk ul>li>a:hover {
  background: #ff6c00;
  color: #fff
}

.course-detail .side-nav.uk ul>li.active {
  background: rgba(255, 108, 0, .2)
}

.course-detail .side-nav>div {
  box-shadow: 0 0 2px rgba(0, 0, 0, .15);
  background: hsla(0, 0%, 100%, .9);
  border-radius: 4px;
  overflow: hidden
}

.course-detail .side-nav>div[aria-hidden=true] {
  opacity: 0
}

.course-detail .side-nav ul {
  list-style: none;
  padding: 0;
  margin: 0
}

.course-detail .side-nav ul>li {
  display: flex;
  border-bottom: 1px solid #f0f0f0
}

.course-detail .side-nav ul>li>a {
  flex: 1 1 auto;
  padding: 18px 24px;
  text-align: center;
  font-size: 15px;
  color: rgba(0, 0, 0, .65);
  -webkit-transition: all .2s ease;
  transition: all .2s ease
}

.course-detail .side-nav ul>li>a:active,
.course-detail .side-nav ul>li>a:focus,
.course-detail .side-nav ul>li>a:hover {
  background: #3bbdf8;
  color: #fff
}

.course-detail .side-nav ul>li.active {
  background: #e8f8ff
}

.course-detail .side-nav .btn-action {
  width: 100%;
  height: 60px;
  line-height: 1;
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  border-top-left-radius: 0;
  border-top-right-radius: 0
}

.course-detail .side-nav .btn-action small {
  color: hsla(0, 0%, 100%, .85);
  margin: 0 0 6px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .ant-card {
  position: relative;
  overflow: hidden;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.course-detail .ant-card:active .card-cover,
.course-detail .ant-card:hover .card-cover {
  opacity: 1
}

.course-detail .ant-card .ant-card-body {
  overflow: hidden
}

.course-detail .ant-card .card-cover {
  position: absolute;
  top: 0;
  bottom: 36px;
  left: 0;
  right: 0;
  background: rgba(3, 169, 244, .9);
  color: hsla(0, 0%, 100%, .85);
  z-index: 1;
  padding: 36px;
  opacity: 0;
  -webkit-transition: opacity .2s ease;
  transition: opacity .2s ease
}

.course-detail .ant-card .card-thumbnail {
  position: relative;
  z-index: 0;
  overflow: hidden;
  text-align: center
}

.course-detail .ant-card .card-thumbnail .background {
  background: #bbc9d6;
  opacity: .4;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail .ant-card .card-thumbnail img {
  min-width: 100%;
  height: 216px
}

.course-detail .ant-card .card-content {
  flex: 0 0 auto;
  margin-top: -36px;
  padding: 12px;
  width: 85%;
  background: #fff;
  position: relative;
  z-index: 2
}

.course-detail .ant-card .card-content .title {
  font-size: 16px;
  line-height: 1.5;
  display: flex;
  align-items: center;
  margin-bottom: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .ant-card .card-content .subtitle {
  margin: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .ant-card .btn-link {
  z-index: 3
}

.course-detail .ant-timeline-item-content {
  top: -3px;
  padding-left: 24px
}

.course-detail .ant-timeline-item-content h4 {
  font-size: 18px;
  line-height: 18px;
  font-weight: 400;
  color: #03a9f4;
  margin-bottom: 12px
}

.course-detail .ant-timeline-item-content p {
  margin-bottom: 6px
}

.course-detail .course-summary {
  margin-top: -36px;
  padding: 36px
}

.course-detail .course-summary .summary-bar div[class*=ant-col-] {
  border-left: 3px solid #03a9f4;
  height: 72px
}

.course-detail .course-summary .summary-bar div[class*=ant-col-]>* {
  margin-bottom: 0
}

.course-detail .course-summary .summary-bar div[class*=ant-col-]>p {
  text-transform: uppercase;
  font-size: 16px;
  line-height: 20px;
  color: rgba(0, 0, 0, .65);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .course-summary .summary-bar div[class*=ant-col-]>h3 {
  font-size: 20px;
  font-weight: 400;
  line-height: 30px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .course-summary .summary-bar div[class*=ant-col-]>small {
  font-size: 14px;
  line-height: 20px;
  color: rgba(0, 0, 0, .45)
}

.course-detail .course-summary .summary-bar.highlight div[class*=ant-col-] {
  border-color: #eb2f96
}

.course-detail .course-intro-container .promotion {
  margin-bottom: 18px;
  padding: 12px 18px;
  background: #eb2f94;
  border-radius: 4px
}

.course-detail .course-intro-container .promotion .markdown-content h1,
.course-detail .course-intro-container .promotion .markdown-content h2,
.course-detail .course-intro-container .promotion .markdown-content h3,
.course-detail .course-intro-container .promotion .markdown-content h4,
.course-detail .course-intro-container .promotion .markdown-content h5,
.course-detail .course-intro-container .promotion .markdown-content h6 {
  color: #fff;
  margin: 0
}

.course-detail .course-intro-container .promotion .markdown-content h1,
.course-detail .course-intro-container .promotion .markdown-content h2 {
  font-size: 20px
}

.course-detail .course-intro-container .promotion .markdown-content p {
  color: hsla(0, 0%, 100%, .85);
  margin: 6px 0;
  font-size: 14px
}

.course-detail .course-metrics {
  background: url(/images/graphs/students.jpg) center 40% no-repeat;
  background-size: cover;
  position: relative;
  padding-top: 84px;
  padding-bottom: 120px;
  margin-bottom: -48px;
  overflow: hidden
}

.course-detail .course-metrics .background {
  background-color: #00629f;
  background-image: linear-gradient(-20deg, #00629f, #003cad);
  opacity: .75;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail .course-metrics .mask {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  overflow: hidden
}

.course-detail .course-metrics .mask .mask-inner {
  width: 100%;
  height: 84px;
  border-right: 1920px solid transparent;
  border-bottom: 84px solid #f7fafc
}

.course-detail .course-metrics div[class*=ant-col-] {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  margin-bottom: 12px
}

.course-detail .course-metrics div[class*=ant-col-] .metric {
  width: 180px;
  height: 168px;
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: flex-start
}

.course-detail .course-metrics div[class*=ant-col-] .metric h2 {
  font-size: 48px;
  font-weight: 500;
  line-height: 48px;
  text-align: center;
  color: #fff;
  margin-bottom: 0
}

.course-detail .course-metrics div[class*=ant-col-] .metric h3 {
  font-size: 16px;
  font-weight: 400;
  color: hsla(0, 0%, 100%, .85);
  text-align: center
}

.course-detail .course-metrics div[class*=ant-col-] .metric .dash {
  bottom: 48px;
  width: 36px;
  background: hsla(0, 0%, 100%, .85)
}

.course-detail .course-metrics .metric_slogan {
  color: #fff;
  z-index: 99;
  margin-bottom: 10px
}

.course-detail .course-metrics .metric_slogan h2 span {
  color: #fff
}

.course-detail .course-metrics .btn-bar {
  width: 100%;
  text-align: center
}

.course-detail .course-metrics .btn-bar .btn-link {
  width: 144px;
  margin-right: 24px
}

.course-detail .course-metrics .btn-bar .btn-link:last-child {
  margin-right: 0
}

.course-detail .course-flow .flow-chart {
  display: flex;
  justify-content: flex-start;
  align-items: center
}

.course-detail .disclaimer {
  text-align: center;
  font-size: 12px
}

.course-detail .syllabus-container .syllabus-section {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  margin-bottom: 24px;
  padding: 48px 10%
}

.course-detail .syllabus-container .syllabus-section .label {
  top: 24px
}

.course-detail .syllabus-container .syllabus-section .ant-tabs {
  width: 100%;
  margin-top: 52px;
  font-size: 16px
}

.course-detail .syllabus-container .syllabus-section .ant-tabs .syllabus-detail {
  margin-top: 8px
}

.course-detail .syllabus-container .syllabus-section .ant-tabs .ant-tabs-tab {
  font-size: 20px
}

.course-detail .syllabus-container .syllabus-section .syllabus-detail {
  width: 100%
}

.course-detail .syllabus-container .syllabus-section .syllabus-detail .title {
  width: 100%;
  font-size: 20px;
  margin-top: 60px
}

.course-detail .syllabus-container .syllabus-section .syllabus-detail .description,
.course-detail .syllabus-container .syllabus-section .syllabus-detail .frequency {
  width: 100%
}

.course-detail .syllabus-container .syllabus-section .syllabus-detail .timeline-container {
  width: 100%;
  margin-top: 24px;
  padding-top: 4px;
  overflow: hidden;
  max-height: 9999px;
  -webkit-transition: max-height 1s ease;
  transition: max-height 1s ease
}

.course-detail .syllabus-container .syllabus-section .syllabus-detail .timeline-container.collapse {
  max-height: 0;
  padding: 0;
  overflow: hidden
}

.course-detail .syllabus-container .syllabus-section .btn-link {
  margin: 0 0 -48px;
  background: #e8f8ff
}

.course-detail .instructors {
  padding-bottom: 30px
}

.course-detail .instructors .card-content {
  width: 100%;
  margin-top: 0;
  padding: 24px
}

.course-detail .projects-container {
  position: relative;
  overflow: visible;
  padding-bottom: 24px
}

.course-detail .projects-container .project {
  margin: 12px 0 24px;
  display: flex;
  min-height: 168px
}

.course-detail .projects-container .project .thumbnail {
  flex: 0 0 auto;
  width: 30%;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover
}

.course-detail .projects-container .project .description {
  margin-left: 24px;
  flex: 1 1 auto
}

.course-detail .projects-container .project .description p {
  margin-top: 6px
}

.course-detail .projects-container .project .description .tag-container {
  margin-top: 12px
}

.course-detail .highlight-container {
  padding-bottom: 30px
}

.course-detail .highlight-container div[class*=ant-col-] {
  display: flex;
  margin-bottom: 18px
}

.course-detail .highlight-container .highlight {
  flex: 1 1 auto
}

.course-detail .highlight-container .highlight .card-content {
  height: 72px
}

.course-detail .faq-container .faq {
  width: 100%;
  border: none;
  padding: 12px;
  margin: 0 0 12px
}

.course-detail .faq-container .faq .ant-collapse-header {
  font-size: 16px
}

.course-detail .price-chart-container {
  margin-bottom: 90px;
  padding-top: 24px
}

.course-detail .price-chart-container div[class*=ant-col-] {
  display: flex;
  margin-bottom: 18px
}

.course-detail .price-chart-container .float-container {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center;
  position: relative;
  padding: 36px 0
}

.course-detail .price-chart-container .float-container .qr-code {
  max-width: 60%;
  margin: 12px 0 24px
}

.course-detail .price-chart-container .float-container h2,
.course-detail .price-chart-container .float-container h3,
.course-detail .price-chart-container .float-container p {
  font-size: 16px;
  text-align: center
}

.course-detail .price-chart-container .float-container h2 {
  font-size: 26px;
  color: #03a9f4;
  margin-bottom: 0
}

.course-detail .price-chart-container .float-container h2 small {
  font-size: 60%;
  color: rgba(0, 0, 0, .65)
}

.course-detail .price-chart-container .float-container h3 {
  font-size: 22px;
  margin-bottom: 0
}

.course-detail .price-chart-container .float-container p {
  margin-top: 0;
  margin-bottom: 12px
}

.course-detail .price-chart-container .float-container .price-chart {
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  width: 100%;
  padding: 24px;
  margin: -36px 0 12px;
  background: #03a9f4
}

.course-detail .price-chart-container .float-container .price-chart h3 {
  font-size: 24px;
  color: #fff;
  margin: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: normal
}

.course-detail .price-chart-container .float-container .price-chart .price-cross.old {
  text-decoration: line-through;
  font-size: 18px
}

.course-detail .price-chart-container .float-container .price-chart .promote-tag {
  position: absolute;
  right: 12%;
  bottom: 17%;
  font-size: 16px;
  padding: 2px 8px;
  border-radius: 14px;
  background: #eb2f96
}

.course-detail .price-chart-container .float-container .price-chart h4 {
  color: #fff;
  margin: 0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .price-chart-container .float-container .price-chart p {
  font-size: 16px;
  color: hsla(0, 0%, 100%, .85);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  margin-bottom: 0
}

.course-detail .price-chart-container .float-container .features {
  padding: 12px 0;
  width: 100%;
  margin-bottom: 0
}

.course-detail .price-chart-container .float-container .features li {
  list-style: none;
  padding: 6px 12px;
  text-align: center;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-detail .price-chart-container .float-container .btn-action {
  width: 60%
}

@media (max-width:1199px) {

  .course-detail .container .main-title,
  .course-detail .container .sub-title {
    text-align: center;
    padding-left: 10%;
    padding-right: 10%
  }

  .course-detail .container .main-title .dash,
  .course-detail .container .sub-title .dash {
    margin: auto;
    left: 0
  }

  .course-detail .content-container {
    padding: 36px 10%
  }

  .course-detail .course-metrics {
    padding-top: 84px;
    padding-bottom: 120px
  }

  .course-detail .projects-container .project .thumbnail {
    width: 40%
  }
}

@media (max-width:991px) {

  .course-detail .page-header,
  .course-detail .page-header .background-video {
    height: 82vh
  }

  .course-detail .ant-card .card-cover {
    opacity: 1
  }

  .course-detail .course-summary {
    padding-bottom: 18px
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-] {
    margin-bottom: 18px
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-]>small {
    font-size: 12px
  }

  .course-detail .content-container {
    padding: 36px 5%
  }

  .course-detail .course-metrics {
    padding-top: 72px;
    padding-bottom: 108px
  }

  .course-detail .projects-container .project {
    flex-flow: column nowrap
  }

  .course-detail .projects-container .project .thumbnail {
    width: 60%;
    height: 168px;
    margin-bottom: 12px
  }

  .course-detail .projects-container .project .description {
    margin-left: 0
  }

  .promote-tag {
    right: 8% !important
  }
}

@media (max-width:767px) {

  .course-detail .page-header,
  .course-detail .page-header .background-video {
    height: 90vh
  }

  .course-detail .page-header .count-down {
    bottom: 24px
  }

  .course-detail .projects-container .project .thumbnail {
    width: 80%
  }

  .promote-tag {
    right: 6% !important
  }
}

@media (max-width:479px) {
  .course-detail .course-summary {
    padding: 18px 12px 6px
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-] {
    height: auto
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-]>p {
    font-size: 14px;
    line-height: 18px
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-]>h3 {
    font-size: 18px
  }

  .course-detail .course-summary .summary-bar div[class*=ant-col-]>small {
    display: none
  }
}

.course-detail svg.course-flow-graph {
  width: 944px;
  overflow: visible
}

.course-detail svg.course-flow-graph .dashed-circle,
.course-detail svg.course-flow-graph .path-1,
.course-detail svg.course-flow-graph .path-2,
.course-detail svg.course-flow-graph .path-border,
.course-detail svg.course-flow-graph .path-mobile {
  fill-rule: evenodd
}

.course-detail svg.course-flow-graph .path-1 {
  opacity: .8;
  fill: url(#lineGradient)
}

.course-detail svg.course-flow-graph .path-2 {
  opacity: .8;
  fill: url(#lineGradient2)
}

.course-detail svg.course-flow-graph .path-mobile {
  opacity: .8;
  fill: url(#lineGradientMobile)
}

.course-detail svg.course-flow-graph .path-border {
  opacity: .8;
  stroke: url(#lineGradientMobile)
}

.course-detail svg.course-flow-graph .border,
.course-detail svg.course-flow-graph .border-thin,
.course-detail svg.course-flow-graph .path-border {
  fill: none
}

.course-detail svg.course-flow-graph .border,
.course-detail svg.course-flow-graph .border-thin,
.course-detail svg.course-flow-graph .circle,
.course-detail svg.course-flow-graph .fill-dark-blue-and-border,
.course-detail svg.course-flow-graph .fill-light-blue-and-border,
.course-detail svg.course-flow-graph .fill-light-blue-and-border-thick,
.course-detail svg.course-flow-graph .fill-shadow,
.course-detail svg.course-flow-graph .fill-white-and-border,
.course-detail svg.course-flow-graph .fill-white-and-border-thick {
  stroke: #38b5ee;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10
}

.course-detail svg.course-flow-graph .border,
.course-detail svg.course-flow-graph .circle,
.course-detail svg.course-flow-graph .fill-dark-blue-and-border,
.course-detail svg.course-flow-graph .fill-light-blue-and-border,
.course-detail svg.course-flow-graph .fill-shadow,
.course-detail svg.course-flow-graph .fill-white-and-border {
  stroke-width: 2px
}

.course-detail svg.course-flow-graph .fill-white-and-border,
.course-detail svg.course-flow-graph .fill-white-and-border-thick {
  fill: #fff
}

.course-detail svg.course-flow-graph .fill-dark-blue-and-border {
  fill: #7de1ff
}

.course-detail svg.course-flow-graph .circle,
.course-detail svg.course-flow-graph .fill-light-blue-and-border,
.course-detail svg.course-flow-graph .fill-light-blue-and-border-thick {
  fill: #c5f1ff
}

.course-detail svg.course-flow-graph .fill,
.course-detail svg.course-flow-graph .fill-half-opacity,
.course-detail svg.course-flow-graph .fill-shadow {
  fill: #38b5ee
}

.course-detail svg.course-flow-graph .fill-half-opacity {
  opacity: .5
}

.course-detail svg.course-flow-graph .border-thin {
  stroke-width: 1.5px
}

.course-detail svg.course-flow-graph .fill-light-blue-and-border-thick,
.course-detail svg.course-flow-graph .fill-white-and-border-thick,
.course-detail svg.course-flow-graph .path-border {
  stroke-width: 3px
}

.course-detail svg.course-flow-graph .dashed-line {
  opacity: .9
}

.course-detail svg.course-flow-graph .dash,
.course-detail svg.course-flow-graph .dashed-circle {
  fill: #ff4087
}

.course-detail svg.course-flow-graph .text {
  opacity: .9;
  font-size: 16px;
  fill: #3b454f;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol;
  text-anchor: middle
}

.course-detail svg.course-flow-graph .text.left-align {
  text-anchor: start
}

.course-detail svg.course-flow-graph .text.right-align {
  text-anchor: end
}

.course-detail svg.course-flow-graph.mobile {
  width: 341px
}

.course-detail svg.training-aspects-graph {
  flex: 0 0 432px;
  width: 432px;
  height: 432px
}

.course-detail svg.training-aspects-graph .shape {
  opacity: .8;
  cursor: pointer;
  -webkit-transition: opacity .2s ease;
  transition: opacity .2s ease
}

.course-detail svg.training-aspects-graph .shape.highlight,
.course-detail svg.training-aspects-graph .shape:active,
.course-detail svg.training-aspects-graph .shape:focus,
.course-detail svg.training-aspects-graph .shape:hover {
  opacity: 1
}

.course-detail svg.training-aspects-graph .text {
  fill: #fff;
  font-size: 18px;
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, PingFang SC, Hiragino Sans GB, Microsoft YaHei, Helvetica Neue, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol;
  text-anchor: middle
}

.course-detail svg.training-aspects-graph .top {
  fill: #fadb14
}

.course-detail svg.training-aspects-graph .left {
  fill: #f5222d
}

.course-detail svg.training-aspects-graph .mid-left {
  fill: #fa8c16
}

.course-detail svg.training-aspects-graph .right {
  fill: #03a9f4
}

.course-detail svg.training-aspects-graph .mid-right {
  fill: #52c41a
}

.course-detail svg.training-aspects-graph .mid-bottom {
  fill: #722ed1
}

.course-detail svg.training-aspects-graph .mid {
  fill: #00325c
}

.course-detail.self-driving-car .course-intro-container .promotion {
  display: flex
}

.course-detail.self-driving-car .course-intro-container .promotion .image {
  width: 45%;
  display: flex;
  flex-flow: column;
  align-items: center;
  justify-content: center;
  margin-left: 24px
}

.course-detail.self-driving-car .course-intro-container .promotion .image img {
  width: 100%
}

.course-detail.self-driving-car .course-intro-container .side-container {
  display: flex
}

.course-detail.self-driving-car .course-intro-container .side-container .tech {
  width: 100%;
  background-image: url(/images/graphs/self-driving-car-overview.jpg);
  background-repeat: no-repeat;
  background-position: 100%;
  background-size: cover;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 36px 24px;
  min-height: 240px
}

.course-detail.self-driving-car .course-intro-container .side-container .tech .background {
  background: linear-gradient(225deg, rgba(0, 196, 255, .87), rgba(0, 39, 255, .67));
  opacity: .4;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail.self-driving-car .course-intro-container .side-container .tech>* {
  position: relative
}

.course-detail.self-driving-car .course-intro-container .side-container .tech .content {
  width: 75%
}

.course-detail.self-driving-car .course-intro-container .side-container .tech .content h3 {
  color: #fff;
  font-size: 28px;
  line-height: 1.1
}

.course-detail.self-driving-car .course-intro-container .side-container .tech .content p {
  color: #fff
}

.course-detail.self-driving-car .course-intro-container .side-container .tech img {
  height: 90px;
  margin-left: 12px
}

.course-detail.self-driving-car .values {
  display: flex;
  flex-flow: column nowrap
}

.course-detail.self-driving-car .values .value-item {
  display: flex;
  align-items: center;
  width: 80%;
  overflow: hidden;
  margin: 0;
  padding: 24px 24px 24px 32px
}

.course-detail.self-driving-car .values .value-item:nth-child(odd) {
  margin: 24px 0 24px 96px
}

.course-detail.self-driving-car .values .value-item:nth-child(odd) .border {
  background-image: url(/images/graphs/bg-8.svg)
}

.course-detail.self-driving-car .values .value-item .border {
  width: 9px;
  position: absolute;
  left: 0;
  top: -12px;
  bottom: -12px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 100%;
  background-image: url(/images/graphs/bg-2.svg)
}

.course-detail.self-driving-car .values .value-item .text h2 {
  font-size: 32px;
  font-weight: 700
}

.course-detail.self-driving-car .values .value-item .text h3 {
  font-size: 20px
}

.course-detail.self-driving-car .values .value-item .text p {
  margin-top: 6px
}

.course-detail.self-driving-car .values .value-item>img {
  height: 132px
}

.course-detail.self-driving-car .self-driving-car-training-program div[class*=ant-col-] {
  display: flex;
  margin-bottom: 18px
}

.course-detail.self-driving-car .self-driving-car-training-program .ant-card {
  flex: 1 1 auto;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15);
  cursor: pointer
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head {
  height: 144px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  display: flex;
  flex-flow: column nowrap;
  position: relative;
  padding: 24px
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head .background {
  background: linear-gradient(225deg, rgba(0, 196, 255, .87), rgba(0, 39, 255, .67));
  opacity: .85;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head .background.pink {
  background: linear-gradient(225deg, #e32eea, rgba(0, 39, 255, .7))
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head>* {
  position: relative;
  margin-bottom: 0
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head h2 {
  font-size: 28px;
  line-height: 1.1;
  color: #fff
}

.course-detail.self-driving-car .self-driving-car-training-program .card-head h3 {
  font-size: 22px;
  font-weight: 400;
  color: #fff
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content {
  margin: 0;
  padding: 24px;
  width: 100%
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .description {
  display: flex;
  max-width: 100%;
  max-height: 72.8px;
  -webkit-line-clamp: 4;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 14px;
  line-height: 1.3;
  margin: 18px 0;
  color: rgba(0, 0, 0, .65)
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .tag-container {
  height: 80px
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .logo {
  margin: 24px -24px 0;
  padding: 24px 24px 12px;
  border-top: 1px solid #d9d9d9;
  text-align: center
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .logo img {
  height: 28px
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .highlights {
  display: flex;
  align-items: center;
  margin: 12px 0
}

.course-detail.self-driving-car .self-driving-car-training-program .card-content .highlights .icon {
  flex: 0 0 auto;
  width: 48px;
  height: 48px;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #03a9f4;
  font-size: 24px;
  color: #fff;
  margin-right: 12px
}

.ant-card.course-overview-card {
  height: 284px
}

.ant-card .ant-card-body .content {
  flex: 0 0 auto;
  margin-top: -36px;
  padding: 12px;
  width: 85%;
  background: #fff;
  position: relative;
  z-index: 2
}

@media (max-width:991px) {
  .course-detail.self-driving-car .overview .side-container {
    margin-top: 24px
  }

  .course-detail.self-driving-car .overview .side-container .tech .content h3 {
    font-size: 24px
  }

  .course-detail.self-driving-car .overview .side-container .tech .content p {
    font-size: 14px
  }

  .course-detail.self-driving-car .values .value-item {
    width: 100%
  }

  .course-detail.self-driving-car .values .value-item:nth-child(2n) {
    margin-left: 0
  }

  .course-detail.self-driving-car .values .value-item:nth-child(odd) {
    margin: 24px 0
  }

  .course-detail.self-driving-car .self-driving-car-training-program .card-head h2 {
    font-size: 24px
  }

  .course-detail.self-driving-car .self-driving-car-training-program .card-head h3 {
    font-size: 20px
  }

  .course-detail.self-driving-car .self-driving-car-training-program .card-content .tag-container {
    height: auto
  }
}

@media (max-width:767px) {
  .course-detail.self-driving-car .page-header .content .page-title {
    display: flex;
    max-width: 100%;
    max-height: 92.4px;
    font-size: 28px;
    line-height: 1.1;
    -webkit-line-clamp: 3;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis;
    margin-top: -72px
  }
}

.course-detail.software-development .software-training-program .training-aspects {
  margin: 0 -12.5%
}

.course-detail.software-development .software-training-program .training-aspects .aspect {
  display: flex;
  flex-flow: column nowrap;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

.course-detail.software-development .software-training-program .training-aspects .aspect .icons {
  display: flex;
  align-items: center;
  justify-content: center
}

.course-detail.software-development .software-training-program .training-aspects .aspect .icons img {
  height: 96px
}

.course-detail.software-development .software-training-program .training-aspects .aspect .texts {
  text-align: center;
  margin-bottom: 24px
}

.course-detail.software-development .software-training-program .training-aspects .aspect .texts h3 {
  font-size: 18px
}

.course-detail.software-development .software-training-program .training-aspects .aspect.highlight {
  background-color: #e8f8ff
}

.course-detail.software-development .software-training-program .line {
  height: 2px;
  background: #e8e8e8;
  margin: 24px -50% 24px -20%
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-] {
  cursor: pointer
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-] h3 {
  -webkit-transition: color .2s ease;
  transition: color .2s ease
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-] .dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #e8e8e8;
  -webkit-transition: background .2s ease;
  transition: background .2s ease;
  position: absolute;
  top: -30px
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:active,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:focus,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:hover {
  outline: none
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:active .dot,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:focus .dot,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:hover .dot {
  background: #03a9f4
}

.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:active h3,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:focus h3,
.course-detail.software-development .software-training-program .training-steps div[class*=ant-col-]:hover h3 {
  color: #03a9f4
}

@media (max-width:767px) {
  .course-detail.software-development .software-training-program .training-aspects .aspect .icons img {
    height: 72px
  }

  .course-detail.software-development .software-training-program .training-aspects .aspect .texts h3,
  .course-detail.software-development .software-training-program .training-steps div[class*=ant-col-] h3 {
    font-size: 16px
  }

  .course-detail.software-development .software-training-program .training-steps div[class*=ant-col-] p {
    font-size: 12px
  }
}

@media (max-width:479px) {
  .course-detail.software-development .software-training-program .training-aspects .aspect .icons img {
    height: 64px
  }

  .course-detail.software-development .software-training-program .training-aspects .aspect .texts h3 {
    font-size: 12px
  }
}

.course-feature-content {
  margin: 0 10%
}

.course-feature-card-container {
  width: 330px
}

.course-feature-card-container div:first-of-type {
  flex-direction: column;
  display: flex;
  justify-content: space-between
}

.course-feature-card-container .course-feature-card {
  margin-bottom: 10%
}

.course-feature-card-container .course-feature-card.icon {
  display: flex;
  justify-content: center;
  align-items: center
}

.course-feature-card-container .course-feature-card.icon img {
  height: 90px;
  width: 90px
}

.course-feature-card-container .course-feature-card.title {
  text-align: center;
  font-weight: 700;
  font-size: 18px
}

.course-feature-card-container .course-feature-card.desc {
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 14px;
  line-height: 1.3;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  display: -webkit-box
}

.course-feature-card-container .course-feature-card-button {
  align-self: flex-end;
  margin-top: -5%
}

.course-feature-modal .ant-modal-body {
  display: flex;
  justify-content: center
}

.course-feature-modal .ant-modal-body .course-feature-modal-detail-desc {
  width: 480px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center
}

.course-feature-modal .ant-modal-body .course-feature-modal-detail-desc img {
  height: 120px;
  width: 120px;
  margin-top: 24px;
  margin-bottom: 24px
}

.course-feature-modal .ant-modal-body .course-feature-modal-detail-desc p {
  text-align: center;
  padding-bottom: 20px
}

.student-group-content-image-large {
  display: flex
}

.student-group-content-image-large img {
  height: 100%;
  width: 100%;
  margin: 0 30% 0 10%
}

.student-group-content-image-medium,
.student-group-content-image-mobile {
  display: none
}

.train-plan-wrapper {
  background-size: cover;
  text-align: center;
  padding: 48px 0 120px;
  background-image: url(/images/graphs/contact-bg.jpg);
  position: relative;
  color: #fff
}

.train-plan-wrapper .main-title span {
  color: #fff
}

.train-plan-wrapper .step {
  display: flex;
  flex-flow: column nowrap;
  outline: none
}

.train-plan-wrapper .step:active .indicator .dot,
.train-plan-wrapper .step:focus .indicator .dot,
.train-plan-wrapper .step:hover .indicator .dot {
  background: #03a9f4
}

.train-plan-wrapper .step:first-child .indicator .line {
  width: 50%;
  margin-left: 50%
}

.train-plan-wrapper .step:last-child .indicator .line {
  width: 50%;
  margin-right: 50%
}

.train-plan-wrapper .step .indicator {
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.train-plan-wrapper .step .indicator .dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #e8e8e8;
  margin-top: -7px;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

.train-plan-wrapper .step .indicator .line {
  width: 100%;
  height: 2px;
  background: #e8e8e8
}

.train-plan-wrapper .step .icons {
  display: flex;
  align-items: center;
  justify-content: center
}

.train-plan-wrapper .step .icons img {
  height: 96px;
  margin: 0 -48px 0 -54px
}

.train-plan-wrapper .step .icons img:first-child,
.train-plan-wrapper .step .icons img:last-child {
  margin: 0
}

.train-plan-wrapper .step .texts {
  text-align: center
}

.train-plan-wrapper .step .texts h3 {
  font-size: 18px
}

.train-plan-wrapper .step .texts p {
  padding: 0 20%
}

.course-feature-content {
  display: flex;
  flex-wrap: wrap;
  margin: 0 25% 0 10%
}

.course-feature-content .course-feature-item {
  margin: 24px 12px 24px 0
}

.course-short-desc {
  margin: 48px 30% 48px 10%;
  font-size: 16px
}

@media screen and (max-width:1199px) {
  .student-group-content-image-large {
    display: none
  }

  .student-group-content-image-medium {
    display: flex !important;
    justify-content: center;
    align-items: center
  }

  .student-group-content-image-medium img {
    height: 90%;
    width: 50%
  }

  .student-group-content-image-mobile {
    display: none
  }
}

@media screen and (max-width:767px) {

  .student-group-content-image-large,
  .student-group-content-image-medium {
    display: none !important
  }

  .student-group-content-image-mobile {
    display: flex !important;
    justify-content: center;
    align-items: center
  }

  .student-group-content-image-mobile img {
    height: 50%;
    width: 40%
  }
}

.video-modal .ant-modal-body {
  padding: 0;
  overflow: hidden
}

.course-detail.new {
  background: #fcfcfc
}

.course-summary.new {
  margin-top: -36px;
  padding: 0 36px
}

.course-summary.new .summary-bar div[class*=ant-col-] {
  padding: 28px 0;
  height: 148px;
  width: 20vw;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  border-left: 1px solid #f2f2f2;
  border-color: #f2f2f2 !important
}

.course-summary.new .summary-bar div[class*=ant-col-]:first-child {
  border-left: 0
}

.course-summary.new .summary-bar div[class*=ant-col-]>p {
  font-size: 14px
}

.course-summary.new .summary-bar div[class*=ant-col-]>p:before {
  content: "";
  display: inline-block;
  height: 14px;
  width: 14px;
  background-color: #01a9f4;
  margin-right: 22px
}

.course-summary.new .summary-bar div[class*=ant-col-]>h3 {
  padding-top: 8px
}

.course-summary.new .summary-bar div[class*=ant-col-] small {
  white-space: nowrap
}

.course-summary.new .summary-bar.uk div[class*=ant-col-]>p {
  font-size: 14px
}

.course-summary.new .summary-bar.uk div[class*=ant-col-]>p:before {
  content: "";
  background-color: #ff6c00
}

@media (max-width:991px) {
  .course-summary.new .summary-bar div[class*=ant-col-] {
    margin-bottom: 0 !important
  }
}

@media (max-width:767px) {
  .course-summary.new {
    padding-right: 0
  }

  .course-summary.new .summary-bar {
    padding: 20px 0
  }

  .course-summary.new .summary-bar div[class*=ant-col-] {
    padding: 0;
    margin: 16px 0 !important;
    height: 80px;
    border-color: #f2f2f2 !important
  }

  .course-summary.new .summary-bar div[class*=ant-col-]:first-child {
    border-left: 1px solid #f2f2f2
  }

  .course-summary.new .summary-bar div[class*=ant-col-]>h3 {
    padding-top: 0
  }
}

@media (max-width:479px) {
  .course-summary.new .summary-bar div[class*=ant-col-] {
    height: 56px
  }
}

.target-student.new {
  padding: 48px 25% 48px 10%
}

.target-student.new>h2 {
  color: #06294a;
  font-size: 32px;
  text-align: center;
  margin-bottom: 50px
}

.target-student.new>p {
  text-align: center;
  padding: 0 30px;
  margin-bottom: 6%;
  font-size: 16px;
  color: #45566e
}

.target-student.new .offer-board {
  position: relative
}

.target-student.new .offer-board .offer-board.desktop {
  width: 98%
}

.target-student.new .offer-board .offer-board.mobile {
  display: none
}

.target-student.new .offer-board .offer-board-container {
  box-shadow: 0 6px 12px 0 rgba(137, 157, 181, .16);
  border-top: 6px solid #01a9f4;
  width: 44%;
  padding: 8px 30px;
  position: absolute;
  height: 100%;
  top: 0;
  left: 50%;
  -webkit-transform: translateX(-52%);
  transform: translateX(-52%);
  background-color: #fff;
  overflow: auto
}

.target-student.new .offer-board .offer-board-container::-webkit-scrollbar {
  width: 8px;
  height: 8px;
  border-radius: 1px
}

.target-student.new .offer-board .offer-board-container::-webkit-scrollbar-track {
  background-color: #e2e2e2;
  border-radius: 2px
}

.target-student.new .offer-board .offer-board-container::-webkit-scrollbar-thumb {
  background-color: #bbc9d6;
  outline: 1px solid #708090;
  border-radius: 2px
}

.target-student.new .offer-board .offer-board-container .offer-item {
  display: flex;
  justify-content: space-between;
  padding: 12px;
  align-items: center;
  border-bottom: 1px solid #f4f6fa;
  width: 100%
}

.target-student.new .offer-board .offer-board-container .offer-item img[alt=logo] {
  width: 108px
}

.target-student.new .offer-board .offer-board-container .more-offer {
  height: 64px;
  line-height: 64px;
  text-align: center
}

.target-student.new .case-container {
  padding-top: 10%
}

.target-student.new .case-container .ant-tabs-bar {
  border: 0
}

.target-student.new .case-container .ant-tabs-ink-bar {
  display: none !important
}

.target-student.new .case-container .ant-tabs-nav {
  width: 100%
}

.target-student.new .case-container .ant-tabs-nav>div {
  padding: 0 6%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  justify-items: center
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab .student-case-item {
  position: relative;
  display: flex;
  flex-direction: column;
  text-align: center;
  font-size: 16px
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab .student-case-item img[alt="target group"] {
  height: 140px
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab .student-case-item>p {
  margin-top: 24px;
  white-space: pre-wrap;
  color: #8795a8;
  -webkit-transition: all .5s;
  transition: all .5s;
  height: 60px;
  max-width: 220px
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab:after {
  content: "";
  display: inline-block;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
  border-top: 14px solid #81d7ff;
  position: absolute;
  left: 50%;
  bottom: 0;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  opacity: 0;
  -webkit-transition: opacity .5s;
  transition: opacity .5s
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab-active:after {
  opacity: 1
}

.target-student.new .case-container .ant-tabs-nav .ant-tabs-tab-active .student-case-item>p {
  color: #01a9f4;
  font-size: 18px
}

.target-student.new .case-container .ant-tabs-content {
  height: 180px
}

.target-student.new .case-container .case-detail-container {
  display: flex;
  flex-direction: column
}

.target-student.new .case-container .case-detail-container strong {
  font-size: 64px;
  color: #c6ecff;
  height: 48px
}

.target-student.new .case-container .case-detail-container strong:first-child {
  align-self: flex-start
}

.target-student.new .case-container .case-detail-container strong:last-child {
  align-self: flex-end
}

.target-student.new .case-container .case-detail-container .case-detail {
  color: #8795a8;
  padding: 0 80px;
  text-align: center;
  margin: auto;
  display: flex;
  max-width: 100%;
  max-height: 81px;
  font-size: 18px;
  line-height: 1.5;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

@media (max-width:1199px) {
  .target-student.new {
    padding-right: 10%
  }

  .target-student.new .offer-board.desktop {
    display: none
  }

  .target-student.new .offer-board.mobile {
    display: block !important;
    position: relative;
    -webkit-transform: translate(-50%, -38%);
    transform: translate(-50%, -38%);
    top: 400px;
    left: 50%;
    margin-bottom: 100px
  }

  .target-student.new .offer-board-container {
    height: 400px !important;
    -webkit-transform: translateX(-50%) !important;
    transform: translateX(-50%) !important;
    width: 360px !important
  }

  .target-student.new .case-container {
    padding-top: 146px
  }

  .target-student.new .case-container .ant-tabs-content {
    height: 200px
  }

  .target-student.new .case-container .case-detail-container .case-detail {
    display: flex;
    max-width: 100%;
    max-height: 108px;
    font-size: 18px;
    line-height: 1.5;
    -webkit-line-clamp: 4;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }
}

@media (max-width:767px) {
  .target-student.new {
    padding-left: 5%;
    padding-right: 5%
  }
}

@media (max-width:576px) {
  .target-student.new .case-container .ant-tabs-content {
    height: 300px
  }

  .target-student.new .case-container .case-detail-container .case-detail {
    display: flex;
    max-width: 100%;
    max-height: 189px;
    font-size: 18px;
    line-height: 1.5;
    -webkit-line-clamp: 7;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }
}

@media (max-width:910px) {
  .target-student.new .ant-tabs-nav>div {
    padding: 0 !important
  }

  .target-student.new .ant-tabs-nav .ant-tabs-tab .student-case-item>p {
    height: auto !important
  }

  .target-student.new .ant-tabs-nav .ant-tabs-tab-active .student-case-item>p {
    font-size: 16px !important
  }
}

@media (max-width:400px) {
  .target-student.new .offer-board-container {
    width: 100% !important
  }
}

.banner-container {
  padding: 48px 10%;
  margin-bottom: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  height: 300px
}

.banner-container .title {
  color: #fff;
  text-align: center
}

.banner-container .sub-title {
  margin-bottom: 48px;
  text-align: center
}

.banner-container .btn-row {
  display: flex
}

.banner-container .btn-row .banner-btn {
  margin: 0 12px;
  padding: 0 24px;
  white-space: nowrap;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-decoration: none;
  display: inline-block
}

.banner-container .btn-row .banner-btn.resume {
  background-color: #01a9f4;
  border: 1px solid #01a9f4
}

.banner-container .btn-row .banner-btn.resume:hover {
  background-color: #52c3f5;
  border: 1px solid #52c3f5
}

.banner-container .btn-row .banner-btn.case {
  border: 1px solid #b2efff
}

.banner-container .btn-row .banner-btn.case:hover {
  color: #b2efff
}

.course-header.page-header.new .content .page-sub-title {
  width: 100%
}

.course-header.page-header.new .content .btn-bar .ant-btn {
  border-radius: 0;
  font-size: 14px;
  margin: 0 16px;
  padding: 0 30px;
  height: 40px;
  line-height: 40px
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-action {
  background-color: #01a9f4;
  color: #fff
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-action:focus,
.course-header.page-header.new .content .btn-bar .ant-btn.btn-action:hover {
  background-color: #2bc3ff
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-action:active {
  background-color: #0086cf
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-action.uk {
  background-color: #ff6c00
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-link {
  border: 1px solid #b2efff;
  color: #fff
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-link:focus,
.course-header.page-header.new .content .btn-bar .ant-btn.btn-link:hover {
  background-color: #fff;
  border-color: #fff;
  color: #2bc3ff
}

.course-header.page-header.new .content .btn-bar .ant-btn.btn-link.uk:focus,
.course-header.page-header.new .content .btn-bar .ant-btn.btn-link.uk:hover {
  color: #ff6c00
}

.course-intro-container.new {
  padding: 48px 0 48px 10%
}

.course-intro-container.new>h3 {
  color: #06294a;
  font-size: 24px;
  position: relative;
  padding-bottom: 24px;
  margin-bottom: 1em;
  padding-right: 9%;
  white-space: pre-wrap
}

.course-intro-container.new>h3:before {
  content: "";
  display: inline-block;
  border-bottom: 3px solid #01a9f4;
  width: 72px;
  position: absolute;
  bottom: 0
}

.course-intro-container.new.uk>h3:before {
  content: "";
  border-bottom: 3px solid #ff6c00
}

.course-intro-container.new>div[class*=ant-row-] {
  background-color: #f4f6fa;
  padding-right: calc(28% + 36px)
}

.course-intro-container.new>div[class*=ant-row-] .content {
  padding: 14px
}

.course-intro-container.new>div[class*=ant-row-] .content>div {
  display: flex;
  padding: 14px;
  align-items: center
}

.course-intro-container.new>div[class*=ant-row-] .content>div .markdown-content {
  padding-left: 24px;
  font-size: 14px
}

.course-intro-container.new>div[class*=ant-row-] .content>div .markdown-content>p {
  margin-bottom: 0;
  display: flex;
  max-width: 100%;
  max-height: 84px;
  font-size: 14px;
  line-height: 1.5;
  -webkit-line-clamp: 4;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-intro-container.new>div[class*=ant-row-] .image-container {
  position: relative
}

.course-intro-container.new>div[class*=ant-row-] .image-container img {
  position: absolute;
  right: 0;
  height: 110%;
  top: -20%;
  max-width: 100%
}

@media (max-width:1199px) {
  .course-intro-container.new>div[class*=ant-row-] {
    padding-right: 10%
  }
}

@media (max-width:991px) {
  .course-intro-container.new {
    padding-left: 5%
  }

  .course-intro-container.new>div[class*=ant-row-] {
    padding-right: 5%
  }
}

.course-features-container.new {
  padding-bottom: 140px;
  background: -webkit-gradient(linear, left top, left bottom, from(#fcfcfc), to(#f4f6fa));
  background: linear-gradient(#fcfcfc, #f4f6fa)
}

.course-features-container.new>h2 {
  color: #06294a;
  font-size: 32px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-]:last-child {
  align-self: flex-end
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-btn {
  border-radius: 0;
  padding: 0 30px;
  height: 40px;
  line-height: 40px;
  margin-left: 60px;
  margin-top: 40px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse {
  border: 0;
  background-color: transparent;
  padding-bottom: 4px;
  height: 480px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item {
  border: 0
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header {
  padding: 8px 0
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header .arrow,
.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header>i {
  display: none
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header>div {
  display: -webkit-box;
  max-width: 100%;
  max-height: 90px;
  font-size: 20px;
  line-height: 1.5;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  display: flex;
  padding-right: 60px;
  color: #8795a8;
  -webkit-transition: all .2s;
  transition: all .2s
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header>div>span {
  display: inline-block;
  font-size: 20px;
  color: #81d7ff;
  width: 60px;
  -webkit-transition: all .2s;
  transition: all .2s;
  flex: 0 0 60px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-header .index.uk {
  color: rgba(255, 108, 0, .6)
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-content {
  border: 0;
  background-color: transparent
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-content .ant-collapse-content-box {
  padding-left: 60px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item .ant-collapse-content .ant-collapse-content-box p {
  color: #45566e;
  display: flex;
  max-width: 100%;
  max-height: 147px;
  font-size: 14px;
  line-height: 1.5;
  -webkit-line-clamp: 7;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item-active .ant-collapse-header>div {
  font-size: 26px;
  color: #06294a
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .ant-collapse .ant-collapse-item-active .ant-collapse-header>div>span {
  font-size: 30px
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .image-container {
  position: relative;
  height: 100%
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .image-container img {
  -webkit-transition: opacity .2s;
  transition: opacity .2s;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .image-container .active {
  opacity: 1;
  position: relative
}

.course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-] .image-container .hidden {
  opacity: 0
}

@media (max-width:1599px) {
  .course-features-container.new>div[class*=ant-row-]>div[class*=ant-col-]:last-child {
    align-self: center
  }
}

@media (min-width:1200px) and (max-width:1340px) {
  .course-features-container.new .ant-collapse p {
    display: flex !important;
    max-width: 100% !important;
    max-height: 105px !important;
    font-size: 14px !important;
    line-height: 1.5 !important;
    -webkit-line-clamp: 5 !important;
    -webkit-box-align: start !important;
    flex-direction: row !important;
    overflow: hidden !important;
    text-overflow: ellipsis !important
  }
}

@media (min-width:768px) and (max-width:991px) {
  .course-features-container.new .ant-collapse p {
    display: flex !important;
    max-width: 100% !important;
    max-height: 105px !important;
    font-size: 14px !important;
    line-height: 1.5 !important;
    -webkit-line-clamp: 5 !important;
    -webkit-box-align: start !important;
    flex-direction: row !important;
    overflow: hidden !important;
    text-overflow: ellipsis !important
  }
}

@media (max-width:767px) {
  .course-features-container.new {
    padding-bottom: 100px
  }

  .course-features-container.new .ant-collapse {
    height: 400px !important
  }

  .course-features-container.new .ant-collapse p {
    display: flex !important;
    max-width: 100% !important;
    max-height: 63px !important;
    font-size: 14px !important;
    line-height: 1.5 !important;
    -webkit-line-clamp: 3 !important;
    -webkit-box-align: start !important;
    flex-direction: row !important;
    overflow: hidden !important;
    text-overflow: ellipsis !important
  }

  .course-features-container.new .ant-collapse-content-box {
    padding-bottom: 28px !important;
    height: auto !important
  }

  .course-features-container.new .image-container {
    display: none
  }
}

.syllabus-container.new>h2 {
  color: #06294a;
  font-size: 32px;
  text-align: center;
  margin-bottom: 50px
}

.syllabus-container.new div[class*=ant-row-] {
  padding: 0;
  position: relative;
  box-shadow: 0 6px 12px #eee
}

.syllabus-container.new div[class*=ant-row-] div[class*=ant-col-] {
  position: static
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section {
  padding: 28px 5%;
  margin-bottom: 0
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .tag {
  position: absolute;
  left: 0;
  background-color: #c6ecff;
  color: #01a9f4;
  height: 30px;
  line-height: 30px;
  width: 160px;
  padding-right: 16px;
  text-align: center;
  font-size: 12px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .tag:after {
  content: "";
  display: inline-block;
  border-top: 15px solid transparent;
  border-bottom: 15px solid transparent;
  border-right: 15px solid #fff;
  position: absolute;
  right: 0
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail {
  font-size: 14px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .title {
  color: #06294a
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .description {
  font-size: 14px;
  color: #45566e
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .frequency {
  color: #8795a8
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .project {
  margin-top: 36px;
  margin-bottom: 100px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container {
  padding-bottom: 22px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-tail {
  left: 25px;
  border-color: #b2efff;
  top: 110px;
  height: calc(100% - 110px)
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-head {
  display: none
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content {
  padding-left: 80px;
  padding-top: 4px;
  margin: 0;
  top: -4px;
  color: #45566e
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .week {
  position: absolute;
  left: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 12px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .week .index {
  font-size: 16px;
  height: 52px;
  width: 52px;
  border-radius: 50%;
  border: 4px solid #b2efff;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 22px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .content {
  color: #45566e
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .content>h5 {
  font-size: 14px;
  font-weight: 400;
  margin-top: 28px;
  margin-bottom: 14px;
  color: #45566e
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .content>h5:first-child {
  margin-top: 12px
}

.syllabus-container.new div[class*=ant-row-] .syllabus-section .syllabus-detail .timeline-container .ant-timeline-item-content .content>p {
  font-size: 12px;
  margin-top: 0
}

.syllabus-container.new div[class*=ant-row-] .consult-container {
  padding-bottom: 8%
}

.syllabus-container.new div[class*=ant-row-] .consult-container>.image-container img {
  width: 100%
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container {
  background-color: #f8f9fb;
  margin-top: 44px;
  color: #45566e
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container h4 {
  color: #45566e;
  font-size: 14px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container p {
  font-size: 12px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource {
  padding: 30px 30px 24px;
  border-bottom: 1px solid #ecf0f5
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource>h4 {
  margin-top: 24px;
  margin-bottom: 30px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item {
  margin-right: 0;
  width: 100%;
  margin-bottom: 20px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item .ant-form-item-control-wrapper {
  width: 100%
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-explain {
  margin-top: 2px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item-children i {
  font-size: 18px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item-children .ant-input-affix-wrapper>input {
  height: 44px;
  border-radius: 0;
  padding-left: 38px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item-children button {
  border-radius: 0;
  padding: 0 20px;
  height: 40px;
  line-height: 40px;
  border-left: 0
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item-children button[disabled] {
  color: #fff;
  background-color: #03a9f4;
  border-color: #03a9f4
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children {
  position: relative;
  display: block;
  height: 44px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .prefix {
  position: absolute;
  left: 12px;
  top: 14px;
  z-index: 1
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .suffix {
  position: absolute;
  right: 10px;
  top: 15px;
  z-index: 1;
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s;
  font-size: 14px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .suffix.up {
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection {
  height: 44px;
  border-radius: 0;
  padding-left: 38px;
  padding-bottom: 0
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered {
  height: 100%;
  margin: 0;
  padding-right: 26px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered .ant-select-selection__placeholder {
  margin: 0;
  top: 0;
  height: 42px;
  line-height: 42px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul {
  height: 42px;
  padding: 3px 0;
  display: flex
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li {
  margin-top: 0;
  height: auto;
  line-height: 34px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li .ant-select-search__field__wrap {
  width: 0;
  overflow: hidden
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow {
  top: 50%
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .resource .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow i {
  font-size: 14px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .question {
  padding: 20px 30px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .question p {
  margin-bottom: 30px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .question .image-container {
  text-align: center
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .question .image-container img {
  width: 110px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .case {
  padding: 20px 30px;
  background-color: #f0f3f8;
  display: flex;
  align-items: center;
  justify-content: space-between
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .case>h4 {
  margin-bottom: 0;
  display: flex;
  margin-right: 16px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .case>h4 span {
  display: inline-block;
  padding-left: 12px
}

.syllabus-container.new div[class*=ant-row-] .consult-container .contact-container .case .btn {
  font-size: 13px;
  padding: 0 16px;
  height: 40px;
  display: inline-flex;
  align-items: center;
  color: #01a9f4;
  text-decoration: none;
  border: 2px solid #01a9f4;
  white-space: nowrap
}

.syllabus-container.new .disclaimer {
  text-align: right;
  padding-top: 42px
}

.price-chart-container.new {
  padding-bottom: 56px;
  margin-bottom: 0;
  min-height: calc(100vh - 148px);
  display: grid;
  grid-template-rows: 110px auto;
  background: -webkit-gradient(linear, left top, left bottom, from(#fcfcfc), to(#f6f8fa));
  background: linear-gradient(#fcfcfc, #f6f8fa)
}

.price-chart-container.new.uk>div[class*=ant-row-]>div[class*=ant-col-] .price-chart {
  grid-template-rows: 96px auto;
  height: 40vh
}

.price-chart-container.new.uk>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features {
  display: flex;
  flex-direction: column;
  justify-content: space-between
}

.price-chart-container.new>h2 {
  color: #06294a;
  font-size: 32px;
  text-align: center;
  margin-bottom: 50px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart {
  width: 100%;
  background-color: #fff;
  box-shadow: 0 6px 12px rgba(236, 240, 245, .5);
  display: grid;
  grid-template-rows: 108px auto
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .title {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  width: 100%;
  background: #03a9f4
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .title h4 {
  color: hsla(0, 0%, 100%, .85);
  font-size: 16px;
  overflow: hidden;
  text-overflow: ellipsis;
  margin-bottom: 0
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .title h3 {
  color: #fff;
  font-size: 24px;
  margin: 0;
  overflow: hidden;
  text-overflow: ellipsis
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .title h3 small {
  font-size: 66%;
  display: inline-block;
  padding-right: 2px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .hour {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  color: #01a9f4;
  padding: 0 28px 0 40px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .hour span {
  font-size: 66%
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .hour span big {
  font-size: 30px;
  font-weight: 600
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features {
  padding-bottom: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features .feature {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 16% 0 40px;
  height: 16%;
  min-height: 42px;
  font-size: 14px;
  color: #304e67
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features .feature:nth-child(odd) {
  background-color: rgba(129, 215, 255, .08)
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features .feature i {
  color: #01a9f4;
  font-size: 20px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features .feature i.uk {
  color: #ff6c00
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .price-chart .features .feature.uk:nth-child(odd) {
  background-color: rgba(255, 108, 0, .08)
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container {
  background-color: #fff;
  box-shadow: 0 20px 40px rgba(85, 107, 128, .1);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 100%;
  padding-top: 30px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .time {
  padding: 0 30px 24px;
  color: #556b80;
  font-size: 14px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .discount {
  color: #304e67;
  padding: 6px 30px 0
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .discount>h2 {
  font-size: 24px;
  color: #01a9f4
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .discount>h2 small {
  color: #304e67;
  display: block;
  padding: 8px 0
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .discount>h3 {
  font-size: 20px;
  margin-bottom: 0
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .qr-container {
  color: #304e67;
  font-size: 14px;
  padding: 0 30px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .qr-container .image-container {
  text-align: center;
  padding-bottom: 32px;
  padding-top: 20px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .qr-container .image-container img {
  width: 130px
}

.price-chart-container.new>div[class*=ant-row-]>div[class*=ant-col-] .contact-container .ant-btn {
  border-radius: 0;
  height: 64px;
  line-height: 64px
}

.price-chart-container.new.uk {
  min-height: unset
}

.catalog-course-card {
  background-color: #fff;
  box-shadow: 0 6px 12px #eee;
  display: flex !important;
  align-items: center;
  height: 296px
}

.catalog-course-card .image-container {
  height: 100%;
  overflow: hidden;
  background-position: 50%;
  background-size: cover;
  background-repeat: no-repeat
}

.catalog-course-card .content {
  padding: 32px 32px 72px;
  height: 100%;
  position: relative;
  border: 1px solid #e9edf1;
  border-left: 0
}

.catalog-course-card .content>h2 {
  font-size: 24px;
  color: #06294a
}

.catalog-course-card .content .class-hour {
  color: #01a9f4;
  font-size: 14px
}

.catalog-course-card .content .class-hour.uk {
  color: #ff6c00
}

.catalog-course-card .content .time>span {
  display: inline-block;
  margin-bottom: 6px
}

.catalog-course-card .content .time .count-down {
  align-items: flex-start
}

.catalog-course-card .content .time .count-down .count-down-label {
  display: none
}

.catalog-course-card .content .ant-btn {
  position: absolute;
  right: 32px;
  bottom: 32px;
  border-radius: 0;
  margin: 0;
  padding: 0 30px;
  height: 40px;
  line-height: 40px
}

@media (max-width:767px) {
  .catalog-course-card {
    height: auto
  }

  .catalog-course-card .image-container {
    height: 250px
  }

  .catalog-course-card .content {
    height: 266px
  }
}

@media (max-width:575px) {
  .catalog-course-card {
    height: auto
  }

  .catalog-course-card .image-container {
    height: 220px
  }

  .catalog-course-card .content {
    height: 276px;
    padding-top: 24px;
    padding-bottom: 64px
  }

  .catalog-course-card .content>h2 {
    font-size: 22px;
    color: #06294a
  }

  .catalog-course-card .content .time .timer .number {
    font-size: 144%
  }

  .catalog-course-card .content .time .timer span {
    white-space: nowrap
  }

  .catalog-course-card .content .ant-btn {
    bottom: 24px
  }
}

.course-carousel-container.new {
  display: flex;
  justify-content: center;
  padding-bottom: 120px;
  background: -webkit-gradient(linear, left top, left bottom, from(#f6f8fa), to(#f4f6fa));
  background: linear-gradient(#f6f8fa, #f4f6fa)
}

.course-carousel-container.new .ant-carousel {
  width: 50%
}

.course-carousel-container.new .ant-carousel .slick-arrow {
  height: 60px;
  width: 60px;
  border-radius: 50%;
  background-color: #fff;
  border: 1px solid #e9edf1;
  box-shadow: 0 6px 12px #eee;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #304e67;
  z-index: 1;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%)
}

.course-carousel-container.new .ant-carousel .slick-arrow i {
  font-size: 26px
}

.course-carousel-container.new .ant-carousel .slick-arrow.slick-prev {
  left: -60px
}

.course-carousel-container.new .ant-carousel .slick-arrow.slick-next {
  right: -60px
}

.course-carousel-container.new .ant-carousel .slick-list {
  overflow: visible
}

.course-carousel-container.new .ant-carousel .slick-list .slick-slide {
  opacity: .4;
  -webkit-transition: opacity .6s;
  transition: opacity .6s
}

.course-carousel-container.new .ant-carousel .slick-list .slick-slide>div {
  padding: 0 32px
}

.course-carousel-container.new .ant-carousel .slick-list .slick-slide .ant-btn {
  cursor: default
}

.course-carousel-container.new .ant-carousel .slick-list .slick-slide.slick-active {
  opacity: 1
}

.course-carousel-container.new .ant-carousel .slick-list .slick-slide.slick-active .ant-btn {
  cursor: pointer
}

.course-carousel-container.new .ant-btn-primary.uk {
  background-color: #ff6c00;
  border-color: transparent
}

.course-carousel-container.new .btn.uk {
  background-color: rgba(255, 108, 0, .3);
  border-color: transparent
}

@media (max-width:1599px) {
  .course-carousel-container.new .ant-carousel {
    width: 64%
  }
}

@media (max-width:1199px) {
  .course-carousel-container.new .ant-carousel {
    width: 70%
  }
}

@media (max-width:991px) {
  .course-carousel-container.new .ant-carousel {
    width: 84%
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-prev {
    left: -24px
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-next {
    right: -24px
  }
}

@media (max-width:767px) {
  .course-carousel-container.new .ant-carousel {
    width: 97%
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-prev {
    left: 0
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-next {
    right: 0
  }

  .course-carousel-container.new .catalog-course-card {
    height: auto
  }

  .course-carousel-container.new .catalog-course-card .image-container {
    height: 250px
  }

  .course-carousel-container.new .catalog-course-card .content {
    height: 266px
  }
}

@media (max-width:575px) {
  .course-carousel-container.new .ant-carousel {
    width: 104%
  }

  .course-carousel-container.new .ant-carousel .slick-arrow {
    height: 44px;
    width: 44px
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-prev {
    left: 14px
  }

  .course-carousel-container.new .ant-carousel .slick-arrow.slick-next {
    right: 14px
  }

  .course-carousel-container.new .ant-carousel .slick-arrow i {
    font-size: 22px
  }

  .course-carousel-container.new .ant-carousel .slick-list .slick-slide>div {
    padding: 0 16px
  }

  .course-carousel-container.new .catalog-course-card {
    height: auto
  }

  .course-carousel-container.new .catalog-course-card .image-container {
    height: 220px
  }

  .course-carousel-container.new .catalog-course-card .content {
    height: 276px;
    padding-top: 24px;
    padding-bottom: 64px
  }

  .course-carousel-container.new .catalog-course-card .content>h2 {
    font-size: 22px;
    color: #06294a
  }

  .course-carousel-container.new .catalog-course-card .content .time .timer .number {
    font-size: 144%
  }

  .course-carousel-container.new .catalog-course-card .content .time .timer span {
    white-space: nowrap
  }

  .course-carousel-container.new .catalog-course-card .content .ant-btn {
    bottom: 24px
  }
}

.course-faq-container.new {
  background-color: #fcfcfc;
  padding-top: 100px;
  padding-bottom: 100px
}

.course-faq-container.new>h2 {
  color: #06294a;
  font-size: 32px;
  text-align: center;
  margin-bottom: 70px
}

.course-faq-container.new>.content {
  display: flex;
  position: relative
}

.course-faq-container.new>.content .divider {
  position: absolute;
  left: 50%;
  top: 84px;
  bottom: 8px;
  border-left: 1px solid #dddfe0
}

.course-faq-container.new>.content>div:not(.divider) .icon-container {
  position: relative;
  height: 80px
}

.course-faq-container.new>.content>div:not(.divider) .icon-container span {
  display: inline-block;
  width: 32px;
  height: 20px;
  position: absolute;
  border-radius: 4px 4px 0 0
}

.course-faq-container.new>.content>div:not(.divider) .icon-container span:first-child {
  background-color: #01a4f4
}

.course-faq-container.new>.content>div:not(.divider) .icon-container span:first-child:before {
  content: "";
  border-left: 10px solid #01a4f4;
  border-bottom: 6px solid transparent;
  position: absolute;
  top: 100%;
  left: 0
}

.course-faq-container.new>.content>div:not(.divider) .icon-container span:last-child {
  background-color: #c6ecff;
  top: 14px;
  left: 10px
}

.course-faq-container.new>.content>div:not(.divider) .icon-container span:last-child:before {
  content: "";
  border-right: 10px solid #c6ecff;
  border-bottom: 6px solid transparent;
  position: absolute;
  top: 100%;
  right: 0
}

.course-faq-container.new>.content>div:not(.divider):first-child .ant-collapse {
  padding-right: 60px
}

.course-faq-container.new>.content>div:not(.divider):last-child {
  padding-left: 40px
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse {
  background-color: transparent
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item {
  padding: 0;
  box-shadow: none;
  background-color: transparent;
  border-bottom: 0
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-header {
  padding: 0
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-header .arrow,
.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-header>i {
  display: none
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-header>div {
  min-height: 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 16px;
  color: #304e67;
  line-height: 1.5
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-header>div i {
  font-size: 20px;
  color: #01a9f4;
  padding-left: 24px
}

.course-faq-container.new>.content>div:not(.divider) .ant-collapse .ant-collapse-item .ant-collapse-content-box {
  padding: 8px 2px
}

@media (max-width:767px) {
  .course-faq-container.new>h2 {
    margin-bottom: 50px
  }

  .course-faq-container.new>.content .divider {
    display: none
  }

  .course-faq-container.new>.content>div:not(.divider):first-child .ant-collapse {
    padding-right: 0
  }

  .course-faq-container.new>.content>div:not(.divider):last-child {
    padding-left: 0
  }

  .course-faq-container.new>.content>div:not(.divider):last-child .icon-container {
    display: none
  }
}

.course-consultant-container.new {
  background-color: #f8fafb;
  padding-bottom: 100px
}

.course-consultant-container.new .ant-form-item {
  padding-bottom: 24px;
  margin: 0;
  width: 100%;
  height: 72px
}

.course-consultant-container.new .ant-form-item .ant-form-item-children,
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper {
  width: 100%
}

.course-consultant-container.new .ant-form-item .ant-form-item-children .ant-input-affix-wrapper>input,
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper .ant-input-affix-wrapper>input {
  height: 48px;
  border-radius: 0;
  padding-left: 42px;
  border-color: #d8dee2
}

.course-consultant-container.new .ant-form-item .ant-form-item-children button,
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper button {
  border-radius: 0;
  height: 48px;
  display: inline-flex;
  align-items: center;
  justify-content: center
}

.course-consultant-container.new .ant-form-item .ant-form-item-children button[disabled],
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper button[disabled] {
  color: #fff;
  background-color: #03a9f4;
  border-color: #03a9f4
}

.course-consultant-container.new .ant-form-item .ant-form-item-children .ant-input-affix-wrapper .ant-input-prefix i,
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper .ant-input-affix-wrapper .ant-input-prefix i {
  font-size: 22px;
  color: #bbc9d6
}

.course-consultant-container.new .ant-form-item .ant-form-item-children .ant-form-explain,
.course-consultant-container.new .ant-form-item .ant-form-item-control-wrapper .ant-form-explain {
  margin-top: 2px
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix {
  left: 1px;
  top: 1px;
  bottom: 1px;
  -webkit-transform: none;
  transform: none
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div {
  display: flex;
  align-items: center;
  height: 100%
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div .ant-select {
  background-color: #f8fafb;
  border-right: 1px solid #d8dee2;
  display: flex;
  align-items: center;
  height: 100%
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div .ant-select .ant-select-selection {
  background: none;
  border: 0;
  box-shadow: none;
  display: flex
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div .ant-select .ant-select-selection .ant-select-selection__rendered {
  display: flex;
  align-items: center
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div .ant-select .ant-select-selection .ant-select-arrow {
  right: 8px
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div .ant-select .ant-select-selection .ant-select-arrow i {
  font-size: 14px
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-prefix>div>span {
  color: #192841;
  font-size: 14px;
  display: inline-block;
  padding: 0 10px;
  border-right: 1px solid #dfe9f0
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-affix-wrapper.phone input {
  padding-left: 118px
}

.course-consultant-container.new .ant-form-item.contact-information .ant-input-affix-wrapper.email input {
  padding-left: 80px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children {
  position: relative;
  display: block;
  height: 48px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .prefix {
  position: absolute;
  left: 12px;
  top: 16px;
  z-index: 1;
  font-size: 21px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .suffix {
  position: absolute;
  right: 10px;
  top: 18px;
  z-index: 1;
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .suffix.up {
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection {
  height: 48px;
  border-radius: 0;
  padding-left: 42px;
  padding-bottom: 0
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered {
  height: 100%;
  margin: 0;
  padding-right: 26px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered .ant-select-selection__placeholder {
  margin: 0;
  top: 0;
  height: 46px;
  line-height: 46px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul {
  height: 46px;
  padding: 3px 0;
  display: flex
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li {
  margin-top: 0;
  height: auto;
  line-height: 34px
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li .ant-select-search__field__wrap {
  width: 0;
  overflow: hidden
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow {
  top: 50%
}

.course-consultant-container.new .ant-form-item.courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow i {
  font-size: 14px
}

.course-consultant-container.new .ant-select-dropdown li {
  line-height: 26px
}

.course-consultant-container.new .ant-select-dropdown li i {
  font-size: 22px
}

.consultant-courses-options.course-consultant .ant-select-dropdown-menu-item-group-list>li {
  width: 100%
}

.course-test-container.new {
  margin-bottom: 100px;
  background-size: cover;
  padding-bottom: 60px;
  padding-top: 68px
}

.course-test-container.new>h2 {
  color: #fff;
  font-size: 32px;
  margin-bottom: 1.8em
}

.course-test-container.new div[class*=ant-row-] div[class*=ant-col-] h3 {
  color: #81d7ff;
  font-size: 22px
}

.course-test-container.new div[class*=ant-row-] div[class*=ant-col-] h3 img {
  margin-right: 20px
}

.course-test-container.new div[class*=ant-row-] div[class*=ant-col-] .description {
  color: #fff;
  font-size: 14px;
  white-space: pre-wrap;
  margin-bottom: 2.6em
}

.course-test-container.new div[class*=ant-row-] div[class*=ant-col-] .ant-btn {
  width: 220px;
  height: 48px;
  line-height: 48px;
  color: #fff;
  text-decoration: none;
  display: inline-block;
  border-radius: 0;
  background-color: #01a9f4;
  border: 1px solid #01a9f4
}

.course-test-container.new div[class*=ant-row-] div[class*=ant-col-] .ant-btn:hover {
  background-color: #52c3f5;
  border: 1px solid #52c3f5
}

.course-projects-container {
  background-color: #f8f9fb;
  padding-top: 160px;
  padding-bottom: 160px
}

.course-projects-container>h2 {
  color: #06294a;
  font-size: 32px;
  text-align: center;
  margin-bottom: 50px;
  white-space: pre-wrap
}

.course-projects-container .projects {
  background: #fff;
  border-top: 10px solid #01a9f4;
  padding: 0 40px
}

.course-projects-container .projects.uk {
  border-top: 10px solid #ff6c00
}

.course-projects-container .projects.uk .project-item {
  border-bottom: 10px solid rgba(255, 108, 0, .3)
}

.course-projects-container .projects.uk .project-item .keywords-container .keywords>span {
  background-color: rgba(255, 108, 0, .15);
  color: #ff6c00
}

.course-projects-container .projects .project-item {
  padding: 36px 0;
  border-bottom: 10px solid #c6ecff
}

.course-projects-container .projects .project-item:last-child {
  border-bottom: 0
}

.course-projects-container .projects .project-item .image-container {
  height: 100%;
  overflow: hidden
}

.course-projects-container .projects .project-item .image-container img {
  min-width: 100%;
  min-height: 100%;
  -o-object-fit: cover;
  object-fit: cover
}

.course-projects-container .projects .project-item .content {
  padding: 4px 40px 0;
  height: 240px;
  overflow: hidden
}

.course-projects-container .projects .project-item .content>h3 {
  color: #06294a;
  font-size: 22px
}

.course-projects-container .projects .project-item .content>p {
  color: #06294a;
  display: flex;
  max-width: 100%;
  max-height: 147px;
  font-size: 14px;
  line-height: 1.5;
  -webkit-line-clamp: 7;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.course-projects-container .projects .project-item .keywords-container {
  background-color: #f8f9fb;
  padding: 12px 24px;
  display: grid;
  grid-template-rows: 32px auto 50px
}

.course-projects-container .projects .project-item .keywords-container>h4 {
  font-size: 16px;
  color: #06294a
}

.course-projects-container .projects .project-item .keywords-container .keywords {
  margin: 4px 0 20px;
  display: flex;
  max-width: 100%;
  max-height: 132px;
  font-size: 44px;
  line-height: 1;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  flex-wrap: wrap
}

.course-projects-container .projects .project-item .keywords-container .keywords>span {
  display: inline-block;
  height: 24px;
  line-height: 24px;
  background-color: rgba(3, 169, 244, .08);
  border-radius: 15px;
  color: #3b7b9d;
  font-size: 12px;
  padding: 0 10px;
  margin: 8px 20px 8px 0
}

.course-projects-container .projects .project-item .keywords-container .btn {
  justify-self: end;
  font-size: 13px;
  padding: 0 36px;
  height: 40px;
  display: inline-flex;
  align-items: center;
  color: #01a9f4;
  text-decoration: none;
  border: 2px solid #01a9f4;
  white-space: nowrap
}

@media (max-width:767px) {
  .course-projects-container {
    padding-top: 100px;
    padding-bottom: 100px
  }

  .course-projects-container .projects .project-item .content {
    padding: 0 0 16px;
    height: auto;
    overflow: hidden
  }
}

.course-detail.uk .uk-course-goal {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0 10%
}

.course-detail.uk .uk-course-goal h1 {
  margin-bottom: 2%;
  align-self: flex-start
}

.course-detail.uk .uk-course-goal .highlight-container {
  display: flex;
  align-self: flex-start
}

.course-detail.uk .uk-course-goal .highlight-container .uk-highlight-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 200px;
  margin-right: 128px
}

.course-detail.uk .uk-course-goal .highlight-container .uk-highlight-item h3 {
  margin: 12px 0
}

.course-detail.uk .uk-course-goal .highlight-container .uk-highlight-item div {
  text-align: center
}

.course-detail.uk .target-student {
  margin: 5% 10%;
  display: flex;
  flex-direction: column;
  align-items: center
}

.course-detail.uk .target-student h1 {
  margin-bottom: 2%;
  align-self: flex-start
}

.course-detail.uk .target-student .item-container {
  display: flex;
  width: 80%;
  align-self: flex-start
}

.course-detail.uk .target-student .item-container .item {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 250px;
  height: 300px;
  padding: 25px 15px 30px;
  text-align: center;
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  margin-right: 32px
}

.course-detail.uk .target-student .item-container .item img {
  height: 90px;
  width: 90px
}

.course-detail.uk .target-student .item-container .item .title {
  color: #06294a;
  font-size: 18px;
  height: 32px;
  margin: 24px 0
}

.course-detail.uk .target-student .item-container .item .desc {
  text-align: center
}

.course-detail.uk .uk-banner {
  height: 350px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center
}

.course-detail.uk .uk-banner h2 {
  color: #fff;
  font-size: 32px
}

.course-detail.uk .uk-banner div {
  color: #fff;
  text-align: center;
  width: 39%;
  font-size: 16px
}

.course-detail.uk .uk-banner a {
  margin-top: 24px;
  padding: 12px 28px;
  color: #fff;
  background-color: #ff6c00
}

.course-detail.uk .uk-program-syllabus {
  margin: 0 10%;
  display: flex;
  flex-direction: column
}

.course-detail.uk .uk-program-syllabus h1 {
  align-self: flex-start;
  margin-bottom: 2%;
  margin-top: 5%
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item {
  display: flex;
  padding: 12px;
  margin-bottom: 30px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  max-width: 980px;
  height: 250px
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left {
  width: 700px;
  height: 210px
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left .phase {
  height: 32px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 166px;
  color: #ff6c00
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left h3 {
  margin-top: 3%;
  margin-left: 5%
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left .frequency {
  margin-left: 5%
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left .frequency i {
  margin-right: 12px
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left .frequency span {
  color: #8795a8
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .left .detail-container {
  margin-left: 5%;
  margin-top: 16px
}

.course-detail.uk .uk-program-syllabus .syllabus-container .syllabus-item .right img {
  width: 250px;
  height: 100%
}

.contact {
  position: relative;
  overflow: hidden;
  background: url(/images/graphs/contact-bg.jpg) 50% no-repeat;
  background-size: cover;
  text-align: center;
  padding: 48px 0 120px
}

.contact,
.contact .main-title {
  color: #fff
}

.contact .sub-title {
  color: hsla(0, 0%, 100%, .8)
}

.courses {
  position: relative;
  background: #f7fafc
}

.courses div[class*=ant-col-] {
  margin-bottom: 32px
}

.courses .gutter-row {
  width: 480px
}

.courses .ant-card {
  height: 428px;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.courses .ant-card:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.courses .card-head {
  height: 210px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  position: relative
}

.courses .card-head .title {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 80%;
  background: #fff;
  padding: 24px 24px 0;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: flex-start
}

.courses .card-head .title h3 {
  font-size: 22px;
  line-height: 28px;
  margin-bottom: 3px
}

.courses .card-head .title .promotional-line {
  font-size: 14px;
  color: rgba(0, 0, 0, .45)
}

.courses .card-head .promotional-badge {
  position: absolute;
  top: -4px;
  right: 24px;
  height: 48px
}

.courses .card-content {
  padding: 24px
}

.courses .card-content .description {
  display: flex;
  max-width: 100%;
  max-height: 54.6px;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  font-size: 14px;
  line-height: 1.3;
  margin: 0 0 18px;
  color: rgba(0, 0, 0, .65)
}

.courses .card-content .tag-container {
  height: 60px;
  overflow: hidden
}

.courses .stats-container {
  justify-content: center;
  padding: 6px;
  border-top: 1px solid #e8e8e8
}

#courseSoftwareDevelopment {
  background-color: #eb2f96
}

#courseAiDataEngineering,
#courseFullstackDevelopment {
  background-color: #03a9f4
}

.card-content-wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  background-color: #fbfbfb;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.card-content-wrapper span {
  font-size: 16px;
  font-weight: 400;
  color: #8294a5
}

@media (max-width:991px) {
  .courses {
    padding-bottom: 18px
  }

  .courses div[class*=ant-col-] {
    margin-bottom: 18px
  }

  .courses .ant-card {
    height: auto
  }
}

@media (max-width:500px) {

  .card-content-wrapper,
  .gutter-row {
    width: 330px !important
  }
}

.how-it-works {
  position: relative;
  background: #fff
}

.how-it-works .step {
  display: flex;
  flex-flow: column nowrap;
  outline: none
}

.how-it-works .step:active .indicator .dot,
.how-it-works .step:focus .indicator .dot,
.how-it-works .step:hover .indicator .dot {
  background: #03a9f4
}

.how-it-works .step:first-child .indicator .line {
  width: 50%;
  margin-left: 50%
}

.how-it-works .step:last-child .indicator .line {
  width: 50%;
  margin-right: 50%
}

.how-it-works .step .indicator {
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.how-it-works .step .indicator .dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #e8e8e8;
  margin-top: -7px;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

.how-it-works .step .indicator .line {
  width: 100%;
  height: 2px;
  background: #e8e8e8
}

.how-it-works .step .icons {
  display: flex;
  align-items: center;
  justify-content: center
}

.how-it-works .step .icons img {
  height: 96px;
  margin: 0 -48px 0 -54px
}

.how-it-works .step .icons img:first-child,
.how-it-works .step .icons img:last-child {
  margin: 0
}

.how-it-works .step .texts {
  text-align: center
}

.how-it-works .step .texts h3 {
  font-size: 18px
}

.how-it-works .step .texts p {
  padding: 0 20%
}

@media (max-width:1199px) {
  .how-it-works .step .texts {
    text-align: center
  }

  .how-it-works .step .texts h3 {
    font-size: 16px
  }

  .how-it-works .step .texts p {
    font-size: 13px;
    padding: 0 10%
  }
}

@media (max-width:767px) {
  .how-it-works .step .icons img {
    height: 64px;
    margin: 0 -28px 0 -32px
  }
}

@media (max-width:479px) {
  .how-it-works .step .texts p {
    display: none
  }
}

.instructors {
  position: relative;
  background: #f7fafc;
  padding-bottom: 24px
}

.instructors .gutter-row {
  display: flex;
  margin-bottom: 32px
}

.instructors .ant-card {
  flex: 1 1 auto;
  position: relative;
  overflow: hidden;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.instructors .ant-card:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.instructors .card-head {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center;
  padding: 24px;
  border-bottom: 1px solid #e9e9e9
}

.instructors .card-head .profile-image {
  width: 84px;
  height: 84px;
  border-radius: 50%;
  overflow: hidden
}

.instructors .card-head h3 {
  font-size: 20px;
  font-weight: 300;
  margin: 12px 0 0
}

.instructors .card-head .stats-container {
  align-items: center;
  justify-content: center;
  height: 21px
}

.instructors .card-content {
  padding: 24px;
  margin-bottom: 24px
}

.instructors .card-content .description {
  display: flex;
  max-width: 100%;
  max-height: 33.6px;
  font-size: 14px;
  line-height: 1.2;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.instructors .card-content section {
  margin-top: 12px
}

.instructors .card-content section:first-child {
  margin-top: 0
}

.instructors .card-content section ul {
  list-style: square outside;
  margin-top: 6px;
  padding-left: 24px;
  font-size: 12px;
  max-height: 72px;
  overflow: hidden
}

.instructors .btn-link {
  position: absolute;
  bottom: 6px;
  right: 6px;
  font-size: 14px;
  text-transform: lowercase;
  outline: none
}

.profile-image.profile-1 {
  border: 2px solid #eb2f96
}

.profile-image.profile-2 {
  border: 2px solid #13c2c2
}

.profile-image.profile-3 {
  border: 2px solid #03a9f4
}

.profile-image.profile-4 {
  border: 2px solid #fa8c16
}

.profile-image.profile-5 {
  border: 2px solid #fadb14
}

.profile-image.profile-6 {
  border: 2px solid #722ed1
}

.profile-image.profile-7 {
  border: 2px solid #f5222d
}

.profile-image.profile-8 {
  border: 2px solid #52c41a
}

.profile-image.profile--1 {
  border: 2px solid #0068a8
}

.profile-image.profile-0 {
  border: 2px solid #ad4e00
}

.profile-image.profile-9 {
  border: 2px solid #ad8b00
}

.instructor-modal .ant-modal-title {
  height: 96px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.instructor-modal .ant-modal-title .profile-image {
  width: 84px;
  height: 84px;
  border-radius: 50%;
  overflow: hidden;
  margin-top: -48px
}

.instructor-modal .ant-modal-title h3 {
  font-size: 20px;
  font-weight: 300;
  margin: 12px 0 3px
}

.instructor-modal .ant-modal-title .stats-container {
  align-items: center;
  justify-content: center;
  font-size: 14px;
  line-height: 21px;
  font-weight: 400
}

.instructor-modal .ant-modal-body {
  padding: 24px
}

.instructor-modal .ant-modal-body section {
  margin-top: 12px
}

.instructor-modal .ant-modal-body section ul {
  list-style: square outside;
  margin-top: 6px;
  padding-left: 24px
}

@media (max-width:767px) {
  .instructors {
    padding-bottom: 18px
  }

  .instructors div[class*=ant-col-] {
    margin-bottom: 18px
  }

  .instructors .ant-card {
    height: auto
  }
}

.metrics {
  position: relative;
  background: url(/images/graphs/students.jpg) center 40% no-repeat;
  background-size: cover;
  padding: 60px 0 120px
}

.metrics .dash {
  bottom: 24px;
  width: 36px;
  background: hsla(0, 0%, 100%, .85)
}

.metrics .background {
  background-color: #00629f;
  background-image: linear-gradient(-20deg, #00629f, #003cad);
  opacity: .75;
  top: 0
}

.metrics .background,
.metrics .mask {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0
}

.metrics .mask {
  overflow: hidden
}

.metrics .mask .mask-inner {
  width: 100%;
  height: 84px;
  border-right: 1920px solid transparent;
  border-bottom: 84px solid #fff
}

.metrics div[class*=ant-col-],
.metrics div[class*=ant-col-] .metric {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  justify-content: center
}

.metrics div[class*=ant-col-] .metric {
  width: 180px;
  height: 180px
}

.metrics div[class*=ant-col-] .metric h2 {
  font-size: 48px;
  font-weight: 500;
  line-height: 48px;
  text-align: center;
  color: #fff;
  margin-bottom: 0
}

.metrics div[class*=ant-col-] .metric h3 {
  font-size: 16px;
  font-weight: 400;
  color: hsla(0, 0%, 100%, .85);
  text-align: center
}

.metrics .metric_slogan {
  color: #fff;
  z-index: 99
}

.metrics .metric_slogan h2 {
  font-size: 40px;
  font-weight: 500;
  line-height: 180px;
  text-align: center;
  color: #fff;
  margin-bottom: 0
}

.metrics .metric_slogan h2 span {
  color: #fff
}

@media (max-width:1199px) {
  .metrics {
    padding-top: 48px
  }
}

@media (max-width:767px) {
  .metrics {
    padding-top: 36px
  }

  .metrics div[class*=ant-col-] .metric {
    width: 120px;
    height: 120px
  }

  .metrics div[class*=ant-col-] .metric h2 {
    font-size: 36px;
    line-height: 36px
  }

  .metrics div[class*=ant-col-] .metric h3 {
    font-size: 12px
  }
}

@media (max-width:479px) {
  .metrics {
    padding-top: 24px
  }

  .metrics div[class*=ant-col-] {
    width: 50%
  }
}

.news {
  position: relative;
  background: #fff
}

.news .ant-card {
  position: relative;
  height: 320px;
  background-repeat: no-repeat;
  background-position: top;
  background-size: cover;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.news .ant-card:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.news .ant-card .card-content {
  height: 85px;
  background: url(/images/shapes/label-square.svg) no-repeat 0 0;
  position: absolute;
  bottom: 24px;
  left: -18px;
  right: 0;
  display: flex;
  flex-flow: row nowrap;
  justify-content: flex-start;
  align-items: flex-start
}

.news .ant-card .card-content .title {
  background: #fff;
  flex: 1 1 auto;
  height: 72px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  margin-right: 12px;
  padding: 6px 18px
}

.news .ant-card .card-content .title h3 {
  font-size: 17px;
  display: flex;
  max-width: 100%;
  max-height: 35.2px;
  font-size: 16px;
  line-height: 1.1;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  margin-bottom: 3px
}

.news .ant-card .card-content .title p {
  color: rgba(0, 0, 0, .45);
  margin-bottom: 0
}

.news .ant-card .card-content .date-badge {
  flex: 0 0 auto
}

@media (max-width:1199px) {
  .news .ant-card .card-content .title h3 {
    display: flex;
    max-width: 100%;
    max-height: 35.2px;
    font-size: 16px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }
}

@media (max-width:767px) {
  .news {
    padding-bottom: 18px
  }

  .news div[class*=ant-col-] {
    margin-bottom: 18px
  }
}

.offers {
  position: relative;
  background: #fff;
  overflow: hidden
}

.offers .main-title {
  display: flex;
  justify-content: center
}

.offers .main-title .badge {
  display: inline-block;
  height: 60px;
  margin: -6px 0 0 12px
}

.offers .offer-board {
  position: relative;
  flex-flow: column nowrap;
  align-items: center;
  background: url(/images/graphs/cpp-offerboard-background.svg) no-repeat 50%
}

.offers .offer-board .offer-board-inner {
  box-shadow: 0 6px 12px 0 rgba(137, 157, 181, .16);
  border-top: 5px solid #03a9f4;
  position: relative;
  width: 580px;
  margin: 0 auto;
  background-color: #fff;
  z-index: 99;
  height: 550px;
  overflow: auto
}

.offers .offer-board .offer-board-inner::-webkit-scrollbar {
  width: 8px;
  height: 8px;
  border-radius: 1px
}

.offers .offer-board .offer-board-inner::-webkit-scrollbar-track {
  background-color: #e2e2e2;
  border-radius: 2px
}

.offers .offer-board .offer-board-inner::-webkit-scrollbar-thumb {
  background-color: #bbc9d6;
  outline: 1px solid #708090;
  border-radius: 2px
}

.offers .offer-board .offer-board-inner .offer-list-inner {
  width: 100%;
  margin-bottom: 24px;
  overflow: hidden;
  max-height: 99999px;
  -webkit-transition: max-height 1.5s ease;
  transition: max-height 1.5s ease
}

.offers .offer-board .offer-board-inner .offer-list-inner.collapse {
  max-height: 1860px
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row {
  padding-bottom: 12px
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row:first-child .list-week-col .dot {
  box-shadow: 3px -3px 0 0 #fff
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row:last-child {
  padding-bottom: 0
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row:last-child .list-week-col {
  margin-bottom: 0
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer {
  box-shadow: inset -2px 0 0 #d9d9d9;
  margin: 6px 0 -18px;
  padding: 0 30px 0 5px;
  display: flex;
  flex-flow: column nowrap;
  align-items: flex-end;
  position: relative
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer h3 {
  color: #03a9f4;
  font-size: 16px;
  line-height: 24px
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer .dot {
  width: 18px;
  height: 18px;
  border-radius: 50%;
  border: 3px solid #03a9f4;
  background: #fff;
  position: absolute;
  top: 3px;
  right: -8px
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer .badge {
  height: 72px;
  margin: -18px 0 -12px
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] {
  line-height: 36px;
  height: 36px;
  padding: 0 24px;
  font-size: 14px;
  display: flex;
  align-items: center;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offers .offer-board .offer-board-inner .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] img {
  max-width: 96px;
  max-height: 24px;
  width: unset
}

.offers .offer-board .offer-board-inner .add-on-container {
  background-color: #fafafa;
  width: 100%;
  text-align: center;
  margin-top: 6px;
  padding: 12px 0
}

.offers .offer-board .offer-board-inner .add-on-container h2 {
  padding: 12px;
  font-size: 14px;
  color: rgba(0, 0, 0, .65)
}

.offers .offer-board .offer-board-inner .add-on-container img {
  padding: 12px
}

.offers .offer-board .offer-board-inner .list-header {
  width: 100%
}

.offers .offer-board .offer-board-inner .list-header div[class*=ant-col-] {
  line-height: 48px;
  height: 48px;
  padding: 0 24px;
  font-size: 18px;
  font-weight: 500;
  text-align: left;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offers .offer-board .more-offer {
  margin: 20px auto;
  text-align: center;
  position: absolute;
  background-color: #fff;
  bottom: -60px;
  left: 0;
  right: 0;
  z-index: 999;
  height: 40px;
  line-height: 40px;
  width: 580px;
  box-shadow: -5px 5px 10px -4px rgba(137, 157, 181, .16)
}

.offers .offer-board .more-offer .btn-slide {
  color: #03a9f4;
  cursor: pointer
}

.offers .offers-container {
  flex: 0 0 auto;
  display: flex;
  flex-flow: column wrap;
  justify-content: space-between;
  align-items: center;
  height: 400px;
  padding-bottom: 68px;
  -webkit-transition: transform .3s ease;
  -webkit-transition: -webkit-transform .3s ease;
  transition: -webkit-transform .3s ease;
  transition: transform .3s ease;
  transition: transform .3s ease, -webkit-transform .3s ease
}

.offers .offers-container .offer-item {
  width: 206px;
  height: 56px;
  background: #f8f8f8;
  border-radius: 32px;
  display: flex;
  align-items: center;
  margin: 12px 18px;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15);
  -webkit-transition: box-shadow .2s ease;
  transition: box-shadow .2s ease;
  overflow: hidden
}

.offers .offers-container .offer-item .image-container {
  flex: 0 0 52px;
  margin: 0 8px 0 2px;
  padding: 2px;
  width: 52px;
  height: 52px;
  border-radius: 50%;
  overflow: hidden;
  background: #fff
}

.offers .offers-container .offer-item .image-container img {
  width: 48px;
  height: 48px;
  border-radius: 50%
}

.offers .offers-container .offer-item .info-container {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center
}

.offers .offers-container .offer-item .info-container>* {
  margin-bottom: 0
}

.offers .offers-container .offer-item .info-container h5 {
  font-size: 14px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  line-height: 22px
}

.offers .offers-container .offer-item .info-container p {
  font-size: 12px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offers .offers-container .offer-item:nth-child(4n) {
  margin-left: 72px
}

.offers .offers-container .offer-item:nth-child(4n+1) {
  margin-left: -48px
}

.offers .offers-container .offer-item:nth-child(4n+2) {
  margin-left: 36px
}

.offers .offers-container .offer-item:nth-child(4n+3) {
  margin-left: -18px
}

.offers .offers-container .offer-item.active {
  background: #f2fbff;
  box-shadow: 0 0 4px #3bbdf8
}

.offers .offers-container .offer-item.active.highlight {
  background: rgba(255, 240, 246, .65);
  box-shadow: 0 0 4px rgba(247, 89, 171, .65)
}

.offers .offers-container .offer-item.offer-see-all {
  background: transparent;
  justify-content: center;
  font-size: 16px;
  text-transform: lowercase;
  -webkit-transition: background .2s ease;
  transition: background .2s ease
}

.offers .offers-container .offer-item.offer-see-all:focus,
.offers .offers-container .offer-item.offer-see-all:hover {
  background: #f8f8f8
}

.offers .offers-container .offer-item.offer-see-all:active {
  background: #f0f0f0
}

.offers .week-slide {
  position: absolute;
  bottom: 36px;
  width: 100%;
  display: flex;
  justify-content: center
}

.offers .week-slide .btn-slide {
  -webkit-appearance: none;
  height: 32px;
  line-height: 32px;
  border-radius: 16px;
  background: #fff;
  border: none;
  outline: none;
  margin: 0 6px;
  padding: 0 16px;
  cursor: pointer;
  -webkit-transition: all .2s ease;
  transition: all .2s ease
}

.offers .week-slide .btn-slide:active,
.offers .week-slide .btn-slide:hover {
  background: #f5f5f5;
  color: rgba(0, 0, 0, .65)
}

.offers .week-slide .btn-slide.active {
  background: #03a9f4;
  color: #fff
}

.offers .week-slide .btn-slide.active.highlight {
  background: #eb2f96
}

.offers .week-slide .btn-slide.offer-see-all {
  color: rgba(0, 0, 0, .65);
  text-transform: lowercase
}

.offers .week-slide .btn-slide.offer-see-all:focus,
.offers .week-slide .btn-slide.offer-see-all:hover {
  color: #2bc3ff
}

.offers .week-slide .btn-slide.offer-see-all:active {
  color: #0086cf
}

@media (max-width:1199px) {
  .offers .offers-carousel .week-container .weekly-offers-container {
    height: 228px
  }

  .offers .offers-carousel .week-container .weekly-offers-container .offer-item {
    width: 216px;
    height: 48px;
    border-radius: 24px;
    margin: 0
  }

  .offers .offers-carousel .week-container .weekly-offers-container .offer-item .image-container {
    flex: 0 0 44px;
    margin: 0 4px 0 2px;
    padding: 2px;
    width: 44px;
    height: 44px
  }

  .offers .offers-carousel .week-container .weekly-offers-container .offer-item .image-container img {
    width: 40px;
    height: 40px
  }
}

.parallax {
  width: 100%;
  height: 85vh;
  display: flex;
  flex-flow: column nowrap;
  overflow: hidden;
  background: #00274b
}

.parallax,
.parallax>* {
  position: relative
}

.parallax .background-graphic,
.parallax .background-video {
  position: fixed;
  left: 0;
  bottom: 24px;
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  -webkit-transition: transform .2s ease;
  -webkit-transition: -webkit-transform .2s ease;
  transition: -webkit-transform .2s ease;
  transition: transform .2s ease;
  transition: transform .2s ease, -webkit-transform .2s ease
}

.parallax .background-graphic {
  background: url(/images/shapes/software-bg.svg) 0 no-repeat;
  background-size: cover
}

.parallax .background-video {
  background-color: #686a70
}

.parallax .btn-video-mute {
  position: absolute;
  right: 36px;
  bottom: 96px;
  width: 44px;
  height: 44px;
  border: none;
  border-radius: 50%;
  background: url(/images/icons/voice.svg) 50% no-repeat;
  background-color: rgba(0, 0, 0, .5);
  opacity: .8;
  outline: none;
  cursor: pointer;
  z-index: 2;
  -webkit-transition: opacity .2s ease;
  transition: opacity .2s ease
}

.parallax .btn-video-mute:active,
.parallax .btn-video-mute:focus,
.parallax .btn-video-mute:hover {
  opacity: 1
}

.parallax .btn-video-mute.mute {
  background-image: url(/images/icons/mute.svg)
}

.parallax .main-area {
  flex: 1 1 auto;
  padding: 0 72px;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  background: rgba(0, 0, 0, .2)
}

.parallax .main-area .tagline {
  max-width: 40%
}

.parallax .main-area .tagline h1 {
  font-size: 40px;
  color: #fff;
  line-height: 48px
}

.parallax .main-area .tagline h3 {
  font-size: 18px;
  color: hsla(0, 0%, 100%, .85);
  margin-top: 12px;
  font-weight: 400
}

.parallax .main-area .tagline .action-bar {
  display: flex;
  padding-top: 24px;
  align-items: center
}

.parallax .main-area .tagline .action-bar .btn.btn-cta {
  line-height: 48px;
  height: 48px;
  padding: 0 24px;
  margin: 0 12px 0 0;
  border-radius: 24px;
  font-size: 18px
}

.parallax .mask {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  overflow: hidden
}

.parallax .mask .mask-inner {
  width: 100%;
  height: 84px;
  border-left: 1920px solid transparent;
  border-bottom: 84px solid #f7fafc
}

@media (max-width:1199px) {
  .parallax .main-area .tagline {
    max-width: 60%
  }
}

@media (max-width:991px) {
  .parallax .main-area {
    background: transparent
  }

  .parallax .main-area .tagline {
    max-width: 100%;
    text-align: center
  }

  .parallax .main-area .tagline h1 {
    font-size: 36px;
    line-height: 44px
  }

  .parallax .main-area .tagline .action-bar {
    justify-content: center
  }

  .parallax .main-area .tagline .action-bar .btn.btn-cta {
    width: 156px;
    line-height: 36px;
    height: 36px;
    margin: 0 12px 0 0;
    padding: 0 18px;
    border-radius: 18px;
    font-size: 14px
  }
}

@media (max-width:767px) {
  .parallax .main-area .tagline .action-bar {
    flex-flow: column
  }

  .parallax .main-area .tagline .action-bar .btn.btn-cta {
    margin: 0 0 12px
  }
}

.way1-form {
  padding: 10px 0
}

.way1-form .ant-form-item {
  margin-bottom: 5px
}

.way1-form .way-title {
  font-size: 16px
}

.way1-form .big-way-title,
.way1-form .way-title {
  font-family: PingFang SC，medium;
  line-height: 24px;
  color: #304d67
}

.way1-form .big-way-title {
  text-align: center;
  font-size: 18px
}

.way1-form .way1-input {
  background-color: #eee;
  height: 30px
}

.way1-form .way1-button {
  width: 100%
}

.way1-form .qrcode {
  height: 100px;
  max-width: 100%;
  margin: 15px 0 10px
}

.way1-form .scan-text {
  text-align: center
}

.way2-form {
  display: flex;
  justify-content: flex-start;
  flex-flow: row-reverse;
  margin-bottom: 10px;
  align-self: center
}

.way2-form img.qrcode {
  width: 80px;
  height: 80px;
  border: 4px solid #c0cedb
}

.way2-form .way-title {
  font-family: PingFang SC，medium;
  font-size: 16px;
  line-height: 24px;
  color: #304d67;
  flex: 1 1;
  padding: 10px 20px
}

.big-way2-form {
  text-align: center;
  height: 210px
}

.big-way2-form img.qrcode {
  width: 120px;
  border: 4px solid #c0cedb;
  margin-bottom: 20px
}

.big-way2-form .way-title {
  font-family: PingFang SC，medium;
  font-size: 18px;
  line-height: 24px;
  color: #304d67;
  flex: 1 1;
  padding: 10px 20px
}

.activities {
  position: relative;
  -webkit-transition: width .5s;
  transition: width .5s;
  background: #f7fafc
}

.activities .index-activity {
  width: 80%;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  position: relative;
  margin: 20px 0 48px
}

.activities .index-activity .activity-item {
  width: 30%;
  min-width: 200px;
  min-height: 200px;
  height: 100%;
  margin: 0 10%
}

.activities .index-activity .activity-item .activity-name {
  font-size: 22px;
  line-height: 50px;
  color: #304d67;
  text-align: center
}

.activities .index-activity .activity-item .activity-main {
  background: #fff;
  font-size: 12px;
  color: #304d67;
  border: 1px solid #ecf0f5;
  box-shadow: 0 2px 8px 0 rgba(130, 148, 165, .1), 0 2px 8px 0 rgba(130, 148, 165, .1);
  height: calc(100% - 50px)
}

.activities .index-activity .activity-item .activity-main .img-deatail {
  height: calc(100% - 60px)
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-img {
  width: 100%;
  padding-bottom: 50%;
  height: 0;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: 100% 100%
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail {
  padding: 20px 20px 0
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single {
  display: flex;
  justify-content: flex-start;
  padding-bottom: 10px
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single .activity-num {
  width: 20%;
  font-size: 22px;
  color: #91dafa;
  text-align: center
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single .activity-num2 {
  width: 20%;
  font-size: 22px;
  color: #faba91;
  text-align: center
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single .activity-join {
  width: calc(80% - 10px);
  margin-left: 10px
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single .activity-join .acitivty-title {
  font-size: 12px;
  color: #8294a5
}

.activities .index-activity .activity-item .activity-main .img-deatail .activity-detail .acitivty-single .activity-join .acitivty-inner-name {
  font-size: 16px
}

.activities .index-activity .activity-item .activity-main .acitivty-btn {
  border-top: 1px solid #ecf0f5;
  height: 60px;
  line-height: 60px;
  text-align: center
}

.activities .index-activity .activity-more {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  width: 15%;
  position: absolute;
  bottom: 20px;
  left: 50%;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%)
}

.activities .index-activity .activity-more .activity-img {
  width: 100%;
  padding-top: 125%;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  background-image: url(/images/activity/tracks.svg);
  margin-bottom: 20px
}

.activities .index-activity .activity-more .acitivty-btn {
  text-align: center
}

@media (max-width:1199px) {
  .activities .activity-item {
    width: 330px !important;
    min-height: 200px
  }

  .activities .index-activity .activity-more {
    display: none !important
  }
}

@media (max-width:767px) {
  .activities {
    padding-bottom: 18px
  }

  .activities div[class*=ant-col-] {
    margin-bottom: 18px
  }
}

.news-list {
  min-height: 100vh
}

.news-list .page-header {
  padding-left: 8.33333%;
  padding-right: 8.33333%;
  height: 360px
}

.news-list .page-header div[class*=ant-row] {
  width: 100%;
  height: 100%
}

.news-list .page-header div[class*=ant-row] .gutter-row {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: flex-start;
  height: 100%
}

.news-list .page-header div[class*=ant-row] .gutter-row:last-child {
  align-items: flex-end
}

.news-list .page-header div[class*=ant-row] .gutter-row>* {
  margin: 0
}

.news-list .page-header div[class*=ant-row] .gutter-row .categries {
  color: hsla(0, 0%, 100%, .85);
  font-size: 14px
}

.news-list .page-header div[class*=ant-row] .gutter-row .page-title {
  margin: 6px 0 24px;
  text-align: left;
  display: flex;
  max-width: 100%;
  max-height: 70.4px;
  font-size: 32px;
  line-height: 1.1;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.news-list .page-header div[class*=ant-row] .gutter-row .page-title a {
  color: #fff
}

.news-list .page-header div[class*=ant-row] .gutter-row .page-title a:active,
.news-list .page-header div[class*=ant-row] .gutter-row .page-title a:focus,
.news-list .page-header div[class*=ant-row] .gutter-row .page-title a:hover {
  color: #e8f8ff
}

.news-list .page-header div[class*=ant-row] .gutter-row .author-bar {
  display: flex;
  align-items: center
}

.news-list .page-header div[class*=ant-row] .gutter-row .author-bar .profile-image {
  flex: 0 0 36px;
  margin-right: 12px
}

.news-list .page-header div[class*=ant-row] .gutter-row .author-bar .profile-image>* {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: hsla(0, 0%, 100%, .8);
  display: flex;
  justify-content: center;
  align-items: center
}

.news-list .page-header div[class*=ant-row] .gutter-row .author-bar .profile-info h5 {
  color: #fff;
  font-size: 16px;
  line-height: 18px;
  margin-bottom: 0
}

.news-list .page-header div[class*=ant-row] .gutter-row .author-bar .profile-info time {
  font-size: 14px;
  color: hsla(0, 0%, 100%, .8)
}

.news-list .page-header div[class*=ant-row] .gutter-row .thumbnail {
  max-width: 100%;
  max-height: 100%
}

.news-list .news-item {
  margin: 24px 0
}

.news-list .news-item .news-header h2 {
  color: #03a9f4;
  -webkit-transition: color .2s ease;
  transition: color .2s ease
}

.news-list .news-item .news-header h2:focus,
.news-list .news-item .news-header h2:hover {
  color: #2bc3ff
}

.news-list .news-item .news-header h2:active {
  color: #0086cf
}

.news-list .news-item-container {
  margin: 24px 0
}

.news-list .news-item-container .news-item {
  margin: 0
}

.news-list .news-image img {
  max-width: 100%;
  max-height: 100%
}

.news-list .video-item-container {
  display: flex;
  justify-content: center
}

.news-list .video-item {
  width: 372px;
  margin: 36px 24px 36px 0
}

.news-list .video-item .ant-card {
  overflow: hidden
}

.news-list .video-item .ant-card .card-thumbnail {
  height: 209px;
  background: #000;
  display: flex;
  justify-content: center;
  align-items: center
}

.news-list .video-item .ant-card .card-thumbnail img {
  width: 100%
}

.news-list .video-item .ant-card .card-content {
  padding: 12px;
  background: #f5f5f5;
  height: 93px;
  position: relative
}

.news-list .video-item .ant-card .card-content .duration {
  padding: 0 6px;
  background: rgba(0, 0, 0, .8);
  height: 24px;
  line-height: 24px;
  border-radius: 2px;
  color: #fff;
  position: absolute;
  top: -36px;
  right: 12px
}

.news-list .video-item .ant-card .card-content h2 {
  display: -webkit-flex;
  height: 48px;
  align-items: center;
  display: flex;
  max-width: 100%;
  max-height: 48px;
  font-size: 16px;
  line-height: 1.5;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.news-list .video-item .ant-card .card-content time {
  color: rgba(0, 0, 0, .45)
}

@media (max-width:991px) {
  .news-list .page-header {
    padding-left: 4.16666%;
    padding-right: 4.16666%
  }
}

@media (max-width:479px) {
  .news-list .page-header div[class*=ant-row-] .gutter-row .page-title {
    display: flex;
    max-width: 100%;
    max-height: 61.6px;
    font-size: 28px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }
}

.news-post {
  min-height: 100vh
}

.news-post .page-header {
  padding-left: 8.33333%;
  padding-right: 8.33333%;
  min-height: 264px
}

.news-post .page-header .categries {
  color: hsla(0, 0%, 100%, .85);
  font-size: 14px
}

.news-post .page-header .page-title {
  margin: 6px 0 24px;
  display: flex;
  max-width: 100%;
  max-height: 83.2px;
  font-size: 32px;
  line-height: 1.3;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.news-post .page-header .author-bar {
  display: flex;
  align-items: center
}

.news-post .page-header .author-bar .profile-image {
  flex: 0 0 36px;
  margin-right: 12px
}

.news-post .page-header .author-bar .profile-image>* {
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background: hsla(0, 0%, 100%, .8);
  display: flex;
  justify-content: center;
  align-items: center
}

.news-post .page-header .author-bar .profile-info h5 {
  color: #fff;
  font-size: 16px;
  line-height: 18px
}

.news-post .page-header .author-bar .profile-info time {
  font-size: 14px;
  color: hsla(0, 0%, 100%, .8)
}

.live-list {
  min-height: 100vh;
  background: #f5f7fa
}

.live-list .page-header {
  padding-left: 8.33333%;
  padding-right: 8.33333%;
  height: 240px
}

.live-list .page-header .page-title {
  margin: 6px 0 24px;
  font-size: 32px
}

.live-list .page-header .page-sub-title {
  color: #fff;
  margin: 0 !important
}

.live-list .container {
  position: relative
}

.live-list .container .gutter-row-header {
  width: 80%;
  display: flex;
  justify-content: space-between
}

.live-list .container .live-contain-list {
  width: 80%;
  display: flex;
  justify-content: flex-start;
  flex-wrap: wrap;
  padding: 30px 20px
}

.live-list .container .live-contain-list .live-item {
  min-width: 330px;
  width: 31.33%;
  border: 1px solid #ecf0f5;
  box-shadow: 0 0 2px #ecf0f5;
  background: #fff;
  margin-bottom: 30px;
  position: relative;
  margin-right: 3%
}

.live-list .container .live-contain-list .live-item .live-main {
  height: calc(100% - 80px)
}

.live-list .container .live-contain-list .live-item .live-main .live-item-img {
  width: 100%;
  padding-top: 50%;
  height: 0;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: 100% 100%
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main {
  padding: 24px 24px 10px;
  position: relative
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-date {
  position: absolute;
  left: 24px;
  top: -36px;
  width: 60px;
  height: 60px;
  border: 1px solid #ecf0f5;
  border-radius: 3px;
  box-shadow: 0 2px 8px 0 rgba(130, 148, 165, .1), 0 2px 8px 0 rgba(130, 148, 165, .1);
  color: #304d67;
  text-align: center;
  background: #fff
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-date .date-num {
  font-size: 28px;
  line-height: 36px
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-date .month {
  font-size: 14px;
  line-height: 20px
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-title {
  line-height: 30px;
  font-size: 20px;
  color: #304d67;
  margin-top: 10px
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-start-time {
  line-height: 24px;
  font-size: 12px;
  color: #8291a5
}

.live-list .container .live-contain-list .live-item .live-main .live-item-main .live-mark .mark-single {
  display: inline-block;
  border-radius: 15px;
  height: 20px;
  font-size: 12px;
  color: #0072a7;
  line-height: 20px;
  padding: 0 5px;
  margin-right: 5px;
  background: #c9eeff
}

.live-list .container .live-contain-list .live-item .live-item-footer {
  margin: 0 24px;
  height: 80px;
  font-size: 12px;
  color: #8291a5;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  border-top: 1px solid #f5f7fa
}

.live-list .container .live-contain-list .live-item .live-item-footer .time-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #304d67;
  margin-bottom: 20px
}

.live-list .container .live-contain-list .live-item .live-item-footer .time-footer .live-timer {
  font-size: 12px;
  color: #8291a5
}

.live-list .container .live-contain-list .live-item .live-item-footer .time-footer .live-timer span {
  margin-right: 3px
}

.live-list .container .live-contain-list .live-item .live-item-footer .time-footer .last-btn {
  margin-left: 20px
}

.live-list .container .live-contain-list .live-item .live-item-hot {
  position: absolute;
  right: 0;
  top: 0
}

.live-list .container .live-contain-list .live-item:nth-child(3n) {
  margin-right: 0
}

.live-list .container .live-contain-calendar {
  width: calc(80% - 40px);
  background: #fff;
  margin: 20px
}

.live-list .container .live-contain-calendar .calendar {
  margin: 0
}

.live-list .container .live-contain-calendar .calendar .events .live-events-hot {
  -webkit-transform: scale(.5);
  transform: scale(.5);
  -webkit-transform-origin: right top;
  transform-origin: right top;
  position: absolute;
  top: -2px;
  right: -2px
}

.live-list .container .live-contain-calendar .calendar .events .event-single {
  position: relative;
  border-radius: 3px;
  color: #fff;
  line-height: 20px;
  padding: 5px 14px 5px 5px;
  margin-bottom: 10px
}

.live-list .container .live-contain-calendar .calendar .events .event-single .event-title {
  font-size: 14px
}

.live-list .container .live-contain-calendar .calendar .events .event-single .event-time {
  font-size: 12px
}

.live-list .container .live-contain-calendar .calendar .ant-fullcalendar-content::-webkit-scrollbar {
  width: 2px
}

.live-list .container .live-contain-calendar .calendar .ant-fullcalendar-column-header .ant-fullcalendar-column-header-inner {
  padding: 10px 0
}

.live-list .container .live-contain-calendar .calendar table {
  border-collapse: collapse
}

.live-list .container .live-contain-calendar .calendar table,
.live-list .container .live-contain-calendar .calendar td,
.live-list .container .live-contain-calendar .calendar th {
  border: 1px solid #c0cedb;
  text-align: left
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar {
  height: calc(100% - 10px);
  overflow: hidden
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel {
  height: calc(100% - 10px);
  overflow: auto
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-calendar-date {
  margin: 0;
  padding: 0;
  border: none
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-calendar-date-content {
  min-height: 130px;
  overflow-y: auto;
  overflow-x: hidden
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-calendar-date-value {
  margin-left: 10px;
  line-height: 24px
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-cell-selected .ant-picker-calendar-date-value {
  border-radius: 50%;
  background: #03a9f4;
  height: 24px;
  width: 24px;
  color: #fff;
  text-indent: 3px;
  -webkit-transition: all;
  transition: all
}

.live-list .container .live-contain-calendar .calendar .ant-picker-cell .ant-picker-cell-in-view .ant-picker-cell-today .ant-picker-cell-selected {
  border-radius: 50%;
  background: #03a9f4
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-calendar-date {
  padding-top: 10px !important
}

.live-list .container .live-contain-calendar .calendar .ant-picker-calendar-full .ant-picker-panel .ant-picker-body th {
  padding: 0 10px;
  line-height: 30px;
  font-size: 14px;
  font-weight: 700
}

.live-list .container .live-contain-calendar .calendar .ant-tag {
  margin: 0 !important
}

.live-list .container .live-contain-calendar .calendar .ant-fullcalendar-fullscreen .ant-fullcalendar-date,
.live-list .container .live-contain-calendar .calendar .ant-fullcalendar-fullscreen .ant-fullcalendar-month {
  border: none;
  margin: 0
}

.live-list .container .live-contain-calendar .calendar .ant-fullcalendar-fullscreen .ant-fullcalendar-column-header {
  padding-left: 10px
}

.live-list .container .live-contain-calendar .calendar .ant-radio-group.ant-radio-group-outline.ant-radio-group-default .ant-radio-button-wrapper:first-child,
.live-list .container .live-contain-calendar .calendar .ant-radio-group.ant-radio-group-outline.ant-radio-group-default .ant-radio-button-wrapper:nth-child(2) {
  display: none !important
}

.live-list .ant-fullcalendar-fullscreen .ant-fullcalendar-value {
  text-align: left;
  width: 24px;
  height: 24px;
  line-height: 24px;
  margin-right: 80%;
  border-radius: 50%;
  padding-left: 2px;
  margin-bottom: 1px
}

.live-list .ant-fullcalendar-fullscreen .ant-fullcalendar-month-panel-selected-cell .ant-fullcalendar-value,
.live-list .ant-fullcalendar-fullscreen .ant-fullcalendar-selected-day .ant-fullcalendar-value {
  color: #fff;
  background: #03a9f4
}

.live-list .live-list .calendar table,
.live-list .live-list .calendar td,
.live-list .live-list .calendar th {
  padding-top: 0 !important
}

.live-list .live-list .calendar .ant-fullcalendar-fullscreen .ant-fullcalendar-column-heade {
  padding: 10px
}

.live-list .ant-fullcalendar-fullscreen .ant-fullcalendar-content {
  overflow-x: hidden
}

@media (max-width:992px) {
  .container .live-contain-list .live-item {
    width: 41.66666667%
  }
}

@media (max-width:991px) {
  .live-list .page-header {
    padding-left: 4.16666%;
    padding-right: 4.16666%
  }
}

@media (max-width:479px) {
  .live-list .page-header div[class*=ant-row-] .gutter-row .page-title {
    display: flex;
    max-width: 100%;
    max-height: 61.6px;
    font-size: 28px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }

  .live-list .ant-radio-group.ant-radio-group-outline:nth-child(2) {
    display: none
  }

  .live-list .container .live-contain-list .live-item {
    width: 330px
  }
}

.event-modal .ant-modal-body {
  padding: 0 !important
}

.event-modal .ant-modal-close-x {
  color: #fff !important
}

.event-modal .event-box .event-img {
  width: 100%;
  height: 250px;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover
}

.event-modal .event-box .event-main {
  padding: 40px;
  position: relative;
  display: flex;
  justify-content: space-between
}

.event-modal .event-box .event-main .event-time {
  position: absolute;
  left: 40px;
  top: -30px;
  height: 60px;
  width: 60px;
  line-height: 24px;
  text-align: center;
  color: #304d67;
  border: 1px solid #ecf0f5;
  border-radius: 3px;
  box-shadow: 0 2px 8px 0 rgba(130, 148, 165, .1), 0 2px 8px 0 rgba(130, 148, 165, .1);
  background: #fff
}

.event-modal .event-box .event-main .event-time .date {
  font-size: 28px;
  padding: 5px
}

.event-modal .event-box .event-main .event-time .month {
  font-size: 14px
}

.event-modal .event-box .event-main .event-left {
  border-right: 1px solid #ecf0f5;
  width: 55%
}

.event-modal .event-box .event-main .event-left .left-title {
  font-size: 22px;
  color: #304d67;
  line-height: 40px
}

.event-modal .event-box .event-main .event-left .left-speck {
  font-size: 12px;
  line-height: 24px;
  color: #8291a5
}

.event-modal .event-box .event-main .event-left .left-txt {
  font-size: 14px;
  color: #304d67;
  line-height: 24px;
  margin-top: 20px
}

.event-modal .event-box .event-main .event-right {
  text-align: center;
  width: 45%;
  padding-left: 30px;
  min-height: 250px;
  color: #304d67;
  line-height: 30px;
  font-size: 16px;
  display: flex;
  justify-content: space-between;
  flex-direction: column
}

.event-modal .event-box .event-main .event-right p {
  padding: 0;
  margin: 0
}

.event-modal .event-box .event-main .event-right .inner-qrcode {
  border: 4px solid #c0cedb;
  height: 100px;
  width: 100px;
  margin: 0 auto;
  display: block
}

.event-modal .event-box .event-main .event-right .checkout .cursor {
  font-size: 12px;
  color: #8291a5;
  cursor: pointer
}

@media (max-width:479px) {
  .event-modal .event-box .event-main {
    padding: 40px;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: flex-start
  }

  .event-modal .event-box .event-main .event-left,
  .event-modal .event-box .event-main .event-right {
    width: 100%
  }
}

.video-section {
  background: #f7fafc
}

.video-section .video-container {
  padding: 24px 10%
}

.video-item {
  width: 100%;
  margin: 16px 0
}

.video-item .ant-card {
  overflow: hidden
}

.video-item .ant-card .card-thumbnail {
  background: #000;
  position: relative
}

.video-item .ant-card .card-thumbnail img {
  width: 100%
}

.video-item .ant-card .card-thumbnail .duration {
  padding: 0 6px;
  background: rgba(0, 0, 0, .85);
  height: 24px;
  line-height: 24px;
  border-radius: 2px;
  color: #fff;
  position: absolute;
  top: 12px;
  right: 12px
}

.video-item .ant-card .card-content {
  margin-top: -36px;
  padding: 12px;
  width: 80%;
  background: #fff;
  height: 115px;
  position: relative
}

.video-item .ant-card .card-content h2 {
  display: -webkit-flex;
  height: 48px;
  align-items: center;
  margin-bottom: 6px;
  display: flex;
  max-width: 100%;
  max-height: 48px;
  font-size: 16px;
  line-height: 1.5;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

@media (max-width:480px) {
  .video-item-container {
    width: 100%
  }
}

.video-list .video-carousel-container {
  position: relative
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video {
  width: 100%;
  height: 80vh;
  position: relative;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .background {
  background: -webkit-gradient(linear, left bottom, left top, from(rgba(0, 0, 0, .85)), color-stop(45%, rgba(0, 0, 0, .2)), color-stop(75%, rgba(0, 0, 0, .05)), to(rgba(0, 0, 0, .5)));
  background: linear-gradient(0deg, rgba(0, 0, 0, .85), rgba(0, 0, 0, .2) 45%, rgba(0, 0, 0, .05) 75%, rgba(0, 0, 0, .5));
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info {
  position: absolute;
  top: 32%;
  left: 10%
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info>* {
  margin: 0
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .title {
  color: #fff;
  margin: 6px 0 24px;
  display: flex;
  max-width: 100%;
  max-height: 70.4px;
  font-size: 32px;
  line-height: 1.1;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .categries {
  text-transform: uppercase;
  color: hsla(0, 0%, 100%, .8)
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar {
  display: flex;
  padding-top: 24px;
  align-items: center
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar .ant-btn {
  height: 36px;
  line-height: 34px;
  font-size: 16px;
  margin-right: 12px
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar .btn.btn-link {
  border-radius: 4px;
  line-height: 32px;
  height: 36px;
  padding: 0 15px;
  border: 2px solid #fff;
  color: #fff;
  opacity: .8;
  outline: none;
  -webkit-transition: opacity .2s ease;
  transition: opacity .2s ease
}

.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar .btn.btn-link:active,
.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar .btn.btn-link:focus,
.video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .action-bar .btn.btn-link:hover {
  opacity: 1
}

.video-list .video-carousel-container .ant-carousel .slick-dots {
  display: none !important
}

.video-list .video-carousel-container .carousel-thumbnail-container {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 28px
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container .image-thumbnail-title {
  position: absolute;
  color: #fff;
  bottom: 15%;
  padding-left: 5%;
  padding-right: 10%;
  z-index: 10;
  display: flex;
  max-width: 100%;
  max-height: 38.4px;
  font-size: 16px;
  line-height: 1.2;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container .image-wrapper {
  border: 3px solid transparent;
  display: flex;
  align-items: flex-start;
  -webkit-transition: all .2s ease;
  transition: all .2s ease
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container .image-wrapper img {
  -webkit-filter: brightness(50%);
  filter: brightness(50%);
  width: 100%;
  height: 100%;
  -webkit-transition: all .2s ease;
  transition: all .2s ease
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container.active .image-thumbnail-title {
  display: none
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container.active .image-wrapper {
  width: 100%;
  height: 100%;
  box-shadow: 0 0 0 3px hsla(0, 0%, 100%, .8);
  -webkit-transform: scale(1.03);
  transform: scale(1.03);
  overflow: hidden
}

.video-list .video-carousel-container .carousel-thumbnail-container .image-thumbnail-container.active .image-wrapper img {
  -webkit-filter: brightness(100%);
  filter: brightness(100%);
  -webkit-transform: scale(1.03);
  transform: scale(1.03)
}

.video-list .section {
  padding: 36px 10%
}

.video-list .section:last-child {
  padding-bottom: 72px
}

.video-list .section .title {
  display: flex;
  padding: 12px 0;
  justify-content: space-between;
  align-items: flex-end
}

.video-list .section .title h3 {
  text-transform: uppercase;
  font-size: 26px;
  margin-bottom: 0
}

.video-list .section .title a {
  text-transform: lowercase
}

.video-list .grid-section {
  background: #f7fafc
}

.video-list .list-with-featured-section .feature-video {
  padding-top: 79px
}

.video-list .list-with-featured-section .feature-video .categries {
  margin: 24px 0 0;
  font-size: 12px
}

.video-list .list-with-featured-section .feature-video .feature-video-title {
  font-size: 20px;
  line-height: 1.4;
  margin: 0 0 18px
}

.video-list .list-with-featured-section .feature-video .feature-video-desc {
  margin-bottom: 12px;
  display: flex;
  max-width: 100%;
  max-height: 91px;
  font-size: 14px;
  line-height: 1.3;
  -webkit-line-clamp: 5;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.video-list .list-with-featured-section .feature-video .button-container {
  margin: 24px 0
}

.video-list .list-with-featured-section .feature-video time {
  font-size: 14px
}

.video-list .list-with-featured-section .video-list {
  padding-top: 16px
}

.video-list .list-with-featured-section .video-list .video-list-item {
  margin-bottom: 32px
}

.video-list .list-with-featured-section .video-list .video-list-item:last-child {
  margin-bottom: 0
}

.video-list .list-with-featured-section .video-list .video-list-item .list-item-title {
  margin-bottom: 18px;
  display: flex;
  max-width: 100%;
  max-height: 50.4px;
  font-size: 18px;
  line-height: 1.4;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.video-list .list-with-featured-section .video-list .video-list-item .list-item-desc {
  margin-bottom: 9px;
  display: flex;
  max-width: 100%;
  max-height: 72.8px;
  font-size: 14px;
  line-height: 1.3;
  -webkit-line-clamp: 4;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

@media (max-width:1199px) {
  .video-list .video-carousel-container .carousel-thumbnail-container {
    bottom: 18px
  }

  .video-list .list-title-container h3 {
    font-size: 24px
  }
}

@media (max-width:991px) {
  .video-list .video-carousel-container .ant-carousel .slick-slide {
    height: 70vh
  }

  .video-list .video-carousel-container .ant-carousel .slick-dots {
    display: block !important
  }

  .video-list .list-title-container h3 {
    font-size: 18px
  }
}

@media (max-width:767px) {
  .video-list .video-carousel-container .ant-carousel .slick-slide {
    height: 70vh
  }

  .video-list .video-carousel-container .ant-carousel .slick-slide .featured-video .hero-info .title {
    display: flex;
    max-width: 100%;
    max-height: 52.8px;
    font-size: 24px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }

  .video-list .video-container {
    padding: 12px 5%
  }
}

@media (max-width:479px) {
  .video-list .video-carousel-container .ant-carousel .slick-slide {
    height: 70vh
  }

  .video-list .video-carousel-container .ant-carousel .slick-slide .hero-info .title {
    display: flex;
    max-width: 100%;
    max-height: 61.6px;
    font-size: 28px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis
  }
}

.video-post {
  background: #f7fafc;
  min-height: 100vh
}

.video-post .page-header {
  padding-top: 0;
  padding-bottom: 0
}

.video-post .video-container {
  padding: 24px 10%
}

.video-post .video-container .video-content {
  margin-bottom: 5%
}

.video-post .video-container .video-content>h2 {
  margin-bottom: 0
}

.video-post .video-container .video-content .video-content-title {
  height: 36px;
  display: flex;
  align-items: center
}

.video-post .video-container iframe {
  width: 100%;
  height: 30vw;
  padding-bottom: 12px
}

.video-post .video-container .tag-container {
  padding-top: 12px;
  padding-bottom: 12px
}

.video-post .video-container .video-sidebar-title {
  height: 36px;
  display: flex;
  align-items: center
}

.video-post .video-container .video-side-bar-items {
  list-style: none;
  padding: 0
}

.video-post .video-container .video-side-bar-items .video-item {
  margin-top: 20px;
  margin-bottom: 24px
}

.video-post .video-container .markdown-content {
  border-top: 1px solid #d9d9d9;
  margin-top: 24px;
  padding-top: 24px
}

@media (max-width:767px) {
  .video-post .video-container iframe {
    top: 0;
    left: 0;
    right: 0;
    height: 55vw
  }
}

@media (min-width:576px) and (max-width:991px) {
  .video-post .video-container iframe {
    height: 46vw
  }
}

.about .container .goal-cards-container {
  margin: 0 10%
}

.about .container .goal-cards-container .goal-card {
  text-align: center
}

.about .container .goal-cards-container .goal-card .image-container {
  width: 75px;
  margin: auto
}

.about .container .goal-cards-container .goal-card .content-wrapper h3 {
  font-size: 20px;
  margin: 12px 0 3px
}

.about .timeline-container {
  padding: 48px 20%
}

.about .timeline-container .ant-timeline-item-content {
  top: -3px;
  padding-left: 24px
}

.about .timeline-container .ant-timeline-item-content h3 {
  font-size: 18px;
  line-height: 18px;
  font-weight: 400;
  color: #03a9f4;
  margin-bottom: 6px
}

.about .contact-info-container {
  padding: 48px 20% 96px;
  background-size: cover;
  background-image: url(/images/graphs/map.jpg);
  background-position: 50%
}

.about .contact-info-container .contact-info {
  background: hsla(0, 0%, 100%, .7);
  padding: 24px 0;
  margin-top: -12px
}

.about .contact-info-container div[class*=ant-col-] .contact-info-title {
  text-align: center
}

.about .contact-info-container div[class*=ant-col-] .contact-info-item {
  position: relative;
  padding-left: 48px
}

.about .contact-info-container div[class*=ant-col-] .contact-info-item .contact-info-item-icon {
  position: absolute;
  left: 0
}

@media (max-width:1199px) {

  .about .contact-info-container,
  .about .timeline-container {
    padding: 18px 10%
  }
}

@media (max-width:991px) {
  .about .container .goal-cards-container {
    margin: 0
  }

  .about .contact-info-container,
  .about .timeline-container {
    padding: 18px 5%
  }
}

@media (max-width:479px) {
  .about .contact-info-container {
    margin: 0 12px
  }
}

.offer-board .float-container {
  margin-top: -24px;
  margin-bottom: 96px;
  padding: 0
}

.offer-board .logo-bar {
  flex: 0 0 84px;
  padding: 24px 36px
}

.offer-board .logo-bar div[class*=ant-col-] {
  display: flex;
  justify-content: center;
  align-items: center
}

.offer-board .logo-bar div[class*=ant-col-] img {
  display: inline-block;
  max-height: 24px;
  max-width: 100%
}

.offer-board .metrics-bar {
  flex: 0 0 84px;
  padding: 24px 36px
}

.offer-board .metrics-bar div[class*=ant-col-] {
  display: flex;
  justify-content: center;
  align-items: center
}

.offer-board .metrics-bar div[class*=ant-col-]>* {
  margin-bottom: 0
}

.offer-board .metrics-bar div[class*=ant-col-] h2 {
  font-size: 24px;
  font-weight: 500;
  color: #a5b6c6
}

.offer-board .metrics-bar div[class*=ant-col-] h3 {
  margin-left: 12px;
  color: rgba(165, 182, 198, .8);
  font-size: 14px;
  line-height: 1.1
}

.offer-board .offer-list {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  border-top: 1px solid #d9d9d9
}

.offer-board .offer-list .list-header {
  width: 100%
}

.offer-board .offer-list .list-header div[class*=ant-col-] {
  line-height: 48px;
  height: 48px;
  padding: 0 24px;
  font-size: 18px;
  font-weight: 500;
  text-align: left;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offer-board .offer-list .offer-list-inner {
  width: 100%;
  margin-bottom: 24px;
  overflow: hidden;
  max-height: 99999px;
  -webkit-transition: max-height 1.5s ease;
  transition: max-height 1.5s ease
}

.offer-board .offer-list .offer-list-inner.collapse {
  max-height: 1860px
}

.offer-board .offer-list .offer-list-inner .list-row {
  padding-bottom: 12px
}

.offer-board .offer-list .offer-list-inner .list-row:first-child .list-week-col .dot {
  box-shadow: 3px -3px 0 0 #fff
}

.offer-board .offer-list .offer-list-inner .list-row:last-child {
  padding-bottom: 0
}

.offer-board .offer-list .offer-list-inner .list-row:last-child .list-week-col {
  margin-bottom: 0
}

.offer-board .offer-list .offer-list-inner .list-row .list-week-col {
  box-shadow: inset -2px 0 0 #d9d9d9;
  margin: 6px 0 -18px;
  padding: 0 36px 0 0;
  display: flex;
  flex-flow: column nowrap;
  align-items: flex-end;
  position: relative
}

.offer-board .offer-list .offer-list-inner .list-row .list-week-col h3 {
  color: #03a9f4;
  font-size: 20px;
  line-height: 24px
}

.offer-board .offer-list .offer-list-inner .list-row .list-week-col .dot {
  width: 18px;
  height: 18px;
  border-radius: 50%;
  border: 3px solid #03a9f4;
  background: #fff;
  position: absolute;
  top: 3px;
  right: -8px
}

.offer-board .offer-list .offer-list-inner .list-row .list-week-col .badge {
  height: 72px;
  margin: -18px 0 -12px
}

.offer-board .offer-list .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] {
  line-height: 36px;
  height: 36px;
  padding: 0 24px;
  font-size: 14px;
  display: flex;
  align-items: center;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offer-board .offer-list .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] img {
  max-width: 96px;
  max-height: 24px;
  width: unset
}

.offer-board .offer-list .btn-link {
  background: #e8f8ff
}

.offer-board .offer-list .add-on-container {
  background-color: #fafafa;
  width: 100%;
  text-align: center;
  margin-top: 6px;
  padding: 12px 0
}

.offer-board .offer-list .add-on-container h2 {
  padding: 12px;
  font-size: 14px;
  color: rgba(0, 0, 0, .65)
}

.offer-board .offer-list .add-on-container img {
  padding: 12px
}

@media (max-width:767px) {
  .offer-board .offer-list .list-header div[class*=ant-col-] {
    line-height: 32px;
    height: 32px;
    font-size: 14px
  }

  .offer-board .offer-list .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] img {
    max-width: 100%
  }
}

.featured-stories-header {
  padding: 0;
  position: relative
}

.featured-stories-header>.title {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  font-size: 50px
}

.featured-stories-header>.ant-btn {
  position: absolute;
  color: #fff;
  background: transparent;
  border: none;
  z-index: 10;
  font-size: 48px;
  top: 42%;
  left: 12px;
  opacity: .8;
  -webkit-transition: opacity .2s ease;
  transition: opacity .2s ease
}

.featured-stories-header>.ant-btn:focus,
.featured-stories-header>.ant-btn:hover {
  opacity: .9
}

.featured-stories-header>.ant-btn:active {
  opacity: 1
}

.featured-stories-header .featured-stories-carousel {
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story {
  height: 60vh;
  padding: 96px 72px 72px;
  position: relative;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .background {
  background: rgba(0, 0, 0, .6);
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote {
  position: absolute;
  font-size: 108px;
  line-height: 84px
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote img {
  width: 64px
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote.top-left {
  top: 108px;
  left: 15%
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote.bottom-right {
  bottom: 84px;
  right: 15%;
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story h2 {
  flex: 0 0 auto;
  position: relative;
  display: block;
  width: 100%;
  padding: 0 20%;
  color: #fff;
  text-align: center;
  display: flex;
  max-width: 100%;
  max-height: 52.8px;
  font-size: 24px;
  line-height: 1.1;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .testimonial {
  flex: 1 1 auto;
  position: relative;
  display: block;
  padding: 0 20%;
  margin-top: 24px;
  color: hsla(0, 0%, 100%, .85);
  display: flex;
  max-width: 100%;
  max-height: 57.6px;
  font-size: 16px;
  line-height: 1.2;
  -webkit-line-clamp: 3;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story footer {
  flex: 0 0 auto;
  width: 100%;
  position: relative;
  display: block;
  font-size: 16px;
  padding: 0 20%;
  margin-top: 18px;
  color: hsla(0, 0%, 100%, .85);
  text-align: right
}

.featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .ant-btn {
  flex: 0 0 auto;
  display: flex;
  justify-content: center;
  align-items: center
}

.featured-stories-header .featured-stories-carousel .slick-dots {
  margin-bottom: 24px
}

.stories .story-container {
  padding: 48px 10% 16px;
  background: #f7fafc
}

.stories .story-container div[class*=ant-col-] {
  margin-bottom: 32px
}

.stories .story-container .story-item {
  width: 100%
}

.stories .story-container .story-item .ant-card {
  overflow: hidden;
  height: 274px;
  box-shadow: 0 0 2px rgba(0, 0, 0, .15)
}

.stories .story-container .story-item .ant-card:hover {
  box-shadow: 0 2px 8px rgba(0, 0, 0, .15)
}

.stories .story-container .story-item .ant-card .card-thumbnail {
  background: #f5f5f5;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 168px;
  overflow: hidden
}

.stories .story-container .story-item .ant-card .card-thumbnail img {
  width: 100%
}

.stories .story-container .story-item .ant-card .card-content {
  padding: 18px 24px;
  background: #fff;
  height: 106px;
  position: relative
}

.stories .story-container .story-item .ant-card .card-content .duration {
  padding: 0 6px;
  background: rgba(0, 0, 0, .8);
  height: 24px;
  line-height: 24px;
  border-radius: 2px;
  color: #fff;
  position: absolute;
  top: -36px;
  right: 12px
}

.stories .story-container .story-item .ant-card .card-content h2 {
  display: -webkit-flex;
  height: 48px;
  align-items: center;
  display: flex;
  max-width: 100%;
  max-height: 48px;
  font-size: 16px;
  line-height: 1.5;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.stories .story-container .story-item .ant-card .card-content .author {
  color: rgba(0, 0, 0, .45);
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.stories .button-container {
  display: flex;
  justify-content: center;
  align-items: center
}

.stories .button-container .ant-btn {
  height: 36px
}

@media (max-width:991px) {
  .featured-stories-header .featured-stories-carousel .featured-story .quote.top-left {
    left: 5%
  }

  .featured-stories-header .featured-stories-carousel .featured-story .quote.bottom-right {
    bottom: 60px;
    right: 5%
  }

  .featured-stories-header .featured-stories-carousel .featured-story footer,
  .featured-stories-header .featured-stories-carousel .featured-story h2 {
    padding: 0 10%
  }

  .stories .story-container {
    padding: 36px 5% 4px
  }
}

@media (max-width:767px) {
  .featured-stories-header .featured-stories-carousel .featured-story-container .featured-story {
    padding: 96px 24px 48px
  }

  .featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote.top-left {
    top: 96px;
    left: 0
  }

  .featured-stories-header .featured-stories-carousel .featured-story-container .featured-story .quote.bottom-right {
    bottom: 48px;
    right: 0
  }

  .featured-stories-header .featured-stories-carousel .featured-story-container .featured-story h2 {
    display: flex;
    max-width: 100%;
    max-height: 44px;
    font-size: 20px;
    line-height: 1.1;
    -webkit-line-clamp: 2;
    -webkit-box-align: start;
    flex-direction: row;
    overflow: hidden;
    text-overflow: ellipsis;
    padding: 0
  }

  .featured-stories-header .featured-stories-carousel .featured-story-container .featured-story footer {
    padding: 0
  }
}

.story-post .story-header {
  height: 45vh;
  padding: 72px 15% 36px;
  position: relative;
  background-repeat: no-repeat;
  background-position: 50%;
  background-size: cover;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center
}

.story-post .story-header .background {
  background: rgba(0, 0, 0, .5);
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0
}

.story-post .story-header .categries {
  position: relative;
  text-transform: uppercase;
  color: hsla(0, 0%, 100%, .8)
}

.story-post .story-header .page-title {
  margin: 6px 0 24px;
  display: flex;
  max-width: 100%;
  max-height: 83.2px;
  font-size: 32px;
  line-height: 1.3;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis;
  position: relative;
  color: #fff
}

.story-post .story-header .author-bar {
  display: flex;
  align-items: center;
  position: relative
}

.story-post .story-header .author-bar .profile-info h5 {
  color: #fff;
  font-size: 16px;
  line-height: 18px
}

.story-post .story-header .author-bar .profile-info time {
  font-size: 14px;
  color: hsla(0, 0%, 100%, .8)
}

.story-post .summary {
  border-left: 3px solid #03a9f4;
  margin: 36px 15% 0;
  padding: 18px 24px 18px 36px;
  font-size: 16px;
  color: rgba(0, 0, 0, .85)
}

.story-post .post-container {
  padding: 36px 15%
}

.cs-report {
  font-size: 14px
}

.cs-report .page-header {
  height: 70vh;
  padding-bottom: 200px
}

.cs-report .page-header .content .page-title {
  margin-bottom: 54px;
  font-size: 36px
}

.cs-report .page-header .content .btn-bar {
  white-space: nowrap
}

.cs-report .page-header .content .btn-bar .ant-btn {
  border-radius: 0;
  font-size: 14px;
  margin: 0 16px;
  padding: 0 30px;
  height: 40px;
  line-height: 40px
}

.cs-report .page-header .content .btn-bar .ant-btn.inverted {
  background-color: #01a9f4;
  color: #fff
}

.cs-report .page-header .content .btn-bar .ant-btn.inverted:hover {
  background-color: #2bc3ff
}

.cs-report .page-header .content .btn-bar .ant-btn.inverted:active {
  background-color: #0086cf
}

.cs-report .page-header .content .btn-bar .ant-btn.btn-link {
  border: 1px solid #b2efff;
  color: #fff
}

.cs-report .page-header .content .btn-bar .ant-btn.btn-link:hover {
  background-color: #fff;
  border-color: #fff;
  color: #2bc3ff
}

.cs-report .content-container {
  border-radius: 0;
  margin-top: -10%;
  border: 1px solid #e9edf1;
  box-shadow: 0 6px 12px rgba(236, 240, 245, .5);
  padding: 0;
  color: #304e67
}

.cs-report .content-container img {
  width: 100%
}

.cs-report .content-container .btn-action {
  height: 44px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0 40px;
  border-radius: 0;
  background-color: #01a9f4;
  color: #fff;
  font-size: 15px
}

.cs-report .content-container .btn-action:hover {
  background-color: #2bc3ff
}

.cs-report .content-container .btn-action:active {
  background-color: #0086cf
}

.cs-report .content-container p {
  line-height: 1.8
}

.cs-report .content-container p span {
  color: #01a9f4
}

.cs-report .content-container h2 {
  color: #304e67;
  font-size: 24px;
  font-weight: 600;
  margin-bottom: 20px
}

.cs-report .content-container h2 span {
  color: #01a9f4
}

.cs-report .content-container .link-board-container {
  background-color: #fff;
  border: 1px solid #e9edf1;
  box-shadow: 0 6px 12px #eee;
  padding: 18px 40px;
  display: flex;
  flex-direction: column
}

.cs-report .content-container .link-board-container .content {
  display: flex;
  align-items: center;
  margin-bottom: 12px
}

.cs-report .content-container .link-board-container .content img {
  max-height: 60px;
  width: 60px
}

.cs-report .content-container .link-board-container .content>div {
  font-size: 12px;
  color: #304e67;
  padding-left: 20px
}

.cs-report .content-container .link-board-container .content>div p+p {
  margin-top: 4px
}

.cs-report .content-container .link-board-container .content>div p {
  white-space: nowrap;
  margin-bottom: 0
}

.cs-report .content-container .link-board-container a {
  width: 100%
}

.cs-report .content-container .h1b-container {
  background: -webkit-gradient(linear, left top, left bottom, from(transparent), to(#f3fbff)) no-repeat;
  background: linear-gradient(transparent, #f3fbff) no-repeat;
  background-size: 100% 40%;
  background-position: bottom
}

.cs-report .content-container .h1b-container .overseas {
  background: url(/images/graphs/report-overseas-bg.svg) no-repeat;
  background-size: 102%;
  background-position: 0 10%;
  height: calc(100vh - 16px);
  padding: 2% 7% 2% 7.2%
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-] {
  height: 50%
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-] p {
  align-self: flex-end
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].title {
  padding-left: 20px
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].description {
  display: flex;
  flex-direction: column;
  align-items: flex-end
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].description img {
  width: 90%
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].description p {
  width: 66%;
  padding-top: 28px;
  margin-bottom: 0
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].bar {
  padding-left: 40px
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].bar img {
  width: auto;
  height: 100%;
  -webkit-transform: translate(-6%, 6%);
  transform: translate(-6%, 6%)
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].h1b {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  justify-content: flex-end
}

.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].h1b h2,
.cs-report .content-container .h1b-container .overseas div[class*=ant-col-].h1b p {
  width: 86%
}

.cs-report .content-container .h1b-container .jobs {
  padding: 4% 7% 7%
}

.cs-report .content-container .h1b-container .jobs .title p {
  width: 48%;
  margin-bottom: 42px;
  margin-top: 20px
}

.cs-report .content-container .h1b-container .age {
  padding: 4% 7%;
  position: relative
}

.cs-report .content-container .h1b-container .age>img {
  margin-top: -6%;
  height: 68vh;
  width: auto;
  margin-left: 24px
}

.cs-report .content-container .h1b-container .age div[class*=ant-col-] {
  position: absolute;
  right: 0;
  padding-left: 70px;
  padding-right: 7%;
  top: 16px
}

.cs-report .content-container .h1b-container .offer-board {
  margin-top: -10%;
  padding: 0 7% 8%;
  align-items: flex-end
}

.cs-report .content-container .h1b-container .offer-board .img-container {
  position: relative
}

.cs-report .content-container .h1b-container .offer-board .img-container a {
  position: absolute;
  border-radius: 0;
  bottom: 16%;
  right: 24%;
  padding: 0 60px
}

.cs-report .content-container .h1b-container .offer-board p {
  width: 88%;
  margin-bottom: 0
}

.cs-report .content-container .jobs-container {
  padding: 7% 0
}

.cs-report .content-container .jobs-container .employment {
  padding: 0 7%
}

.cs-report .content-container .jobs-container .employment h2 {
  margin-bottom: 42px
}

.cs-report .content-container .jobs-container .employment .link {
  display: flex;
  justify-content: flex-end;
  align-self: center
}

.cs-report .content-container .jobs-container .employment .img-container {
  margin-top: 32px
}

.cs-report .content-container .jobs-container .new-graduation {
  padding: 8% 7% 2%;
  position: relative;
  display: flex;
  justify-content: flex-end
}

.cs-report .content-container .jobs-container .new-graduation>img {
  height: calc(100vh - 96px);
  margin: -24px 28px 0;
  width: auto
}

.cs-report .content-container .jobs-container .new-graduation div[class*=ant-col-] {
  position: absolute;
  left: 7%;
  top: 8%;
  display: flex;
  flex-direction: column;
  align-items: flex-start
}

.cs-report .content-container .jobs-container .new-graduation div[class*=ant-col-] h2 {
  margin-bottom: 42px
}

.cs-report .content-container .jobs-container .new-graduation div[class*=ant-col-]>p {
  margin-bottom: 36px
}

.cs-report .content-container .jobs-container .offer-rate {
  background: -webkit-gradient(linear, left top, left bottom, from(transparent), to(#f3fbff)) no-repeat;
  background: linear-gradient(transparent, #f3fbff) no-repeat
}

.cs-report .content-container .jobs-container .offer-rate>div[class*=ant-row-] {
  align-items: center
}

.cs-report .content-container .jobs-container .offer-rate .sex-rate {
  padding: 0 8%
}

.cs-report .content-container .jobs-container .offer-rate .sex-rate div[class*=ant-col-] {
  display: flex;
  flex-direction: column;
  align-items: flex-start
}

.cs-report .content-container .jobs-container .offer-rate .sex-rate div[class*=ant-col-].img-container {
  align-items: flex-end
}

.cs-report .content-container .jobs-container .offer-rate .sex-rate div[class*=ant-col-]>h2 {
  margin-bottom: 42px
}

.cs-report .content-container .jobs-container .offer-rate .sex-rate div[class*=ant-col-]>p {
  margin-bottom: 64px
}

.cs-report .content-container .jobs-container .offer-rate .inexperience-rate {
  padding: 40px 7%
}

.cs-report .content-container .jobs-container .offer-rate .inexperience-rate p {
  margin-bottom: 56px
}

.cs-report .content-container .jobs-container .offer-rate .tranfar-major-rate {
  padding: 0 7%
}

.cs-report .content-container .jobs-container .offer-rate .tranfar-major-rate img {
  width: 92%
}

.cs-report .content-container .jobs-container .offer-rate .major-rate {
  padding-left: 7%;
  padding-top: 80px
}

.cs-report .content-container .jobs-container .offer-rate .major-rate .link {
  display: flex;
  align-self: flex-end;
  padding-bottom: 64px
}

.cs-report .content-container .jobs-container .location {
  padding: 7%
}

.cs-report .content-container .jobs-container .location h2 {
  margin-bottom: 48px
}

.cs-report .content-container .jobs-container .location img {
  margin-top: 24px
}

.cs-report .content-container .recruitment-container {
  background: -webkit-gradient(linear, left top, left bottom, from(transparent), to(#f3fbff)) no-repeat;
  background: linear-gradient(transparent, #f3fbff) no-repeat;
  background-size: 100% 40%;
  background-position: bottom;
  padding-bottom: 400px
}

.cs-report .content-container .recruitment-container .resume {
  padding: 3% 7%
}

.cs-report .content-container .recruitment-container .resume h2 {
  line-height: 2
}

.cs-report .content-container .recruitment-container .resume p {
  margin-top: 24px;
  margin-bottom: 24px
}

.cs-report .content-container .recruitment-container .course {
  padding: 4% 7%
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col] {
  padding-top: 16px;
  padding-bottom: 16px
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a {
  padding: 24px 24px 24px 32px;
  box-shadow: 0 6px 12px #eee;
  background-color: #fff;
  border: 1px solid #e9edf1;
  display: block;
  -webkit-transform: all .2s;
  transform: all .2s
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a:hover {
  background-color: #effaff
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a h4 {
  display: flex;
  align-items: center;
  height: 36px
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a h4 span {
  font-size: 14px;
  color: #06294a;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a h4 img {
  width: 30px;
  display: inline-block;
  padding-right: 10px
}

.cs-report .content-container .recruitment-container .course div[class*=ant-col]>a p {
  font-size: 12px;
  color: #556b80;
  height: 3.6em;
  overflow: hidden;
  margin-bottom: 0
}

.cs-report .content-container .recruitment-container .requirement {
  padding: 4% 7%
}

.cs-report .content-container .recruitment-container .requirement .img-container p {
  margin-top: 36px;
  width: 76%
}

.cs-report .consult-container {
  padding: 0 5.6% 20%;
  box-shadow: none;
  background: transparent;
  margin-top: -414px
}

.cs-report .consult-container h4 {
  color: #45566e;
  font-size: 16px
}

.cs-report .consult-container>div[class*=ant-row] {
  background-color: rgba(198, 236, 255, .3);
  padding: 48px 60px
}

.cs-report .consult-container>div[class*=ant-row] .resource {
  padding-right: 80px;
  border-right: 1px solid #c6ecff
}

.cs-report .consult-container>div[class*=ant-row] .resource>img {
  width: 68px
}

.cs-report .consult-container>div[class*=ant-row] .resource>h4 {
  margin-top: 32px;
  margin-bottom: 32px
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form {
  display: grid;
  grid-template-columns: 1fr auto
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item {
  margin-right: 0
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item .ant-form-item-control-wrapper {
  width: 100%
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-explain {
  margin-top: 2px
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item-children i {
  font-size: 18px
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item-children input {
  height: 40px;
  border-radius: 0;
  padding-left: 38px
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item-children button {
  border-radius: 0;
  padding: 0 20px;
  height: 40px;
  line-height: 40px;
  border-left: 0
}

.cs-report .consult-container>div[class*=ant-row] .resource .ant-form-item-children button[disabled] {
  color: #fff;
  background-color: #03a9f4;
  border-color: #03a9f4
}

.cs-report .consult-container>div[class*=ant-row] .question {
  padding-left: 100px
}

.cs-report .consult-container>div[class*=ant-row] .question p {
  margin-bottom: 28px
}

.cs-report .consult-container>div[class*=ant-row] .question .image-container img {
  width: 110px
}

@media (max-width:767px) {
  .cs-report>.float-container {
    margin-top: -22%
  }

  .cs-report>.float-container h2 {
    font-size: 16px;
    font-weight: 400;
    text-align: center
  }

  .cs-report>.float-container h2 br {
    display: none
  }

  .cs-report>.float-container p,
  .cs-report>.float-container p span {
    color: #45566e
  }

  .cs-report>.float-container .link-board-container {
    display: none
  }

  .cs-report>.float-container .h1b-container {
    background: none
  }

  .cs-report>.float-container .h1b-container .overseas {
    background: none;
    height: auto
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-] {
    height: auto
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].title {
    display: none
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].description img {
    order: 1;
    padding: 40px 16px
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].description p {
    width: 100%
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].bar {
    padding-left: 0;
    order: 1
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].bar img {
    width: 100%;
    padding: 0 16px
  }

  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].h1b h2,
  .cs-report>.float-container .h1b-container .overseas div[class*=ant-col-].h1b p {
    width: 100%
  }

  .cs-report>.float-container .h1b-container .jobs .title p {
    width: 100%;
    margin-bottom: 28px
  }

  .cs-report>.float-container .h1b-container .jobs img {
    padding: 4px 8px
  }

  .cs-report>.float-container .h1b-container .age {
    display: none
  }

  .cs-report>.float-container .h1b-container .offer-board {
    margin-top: 0
  }

  .cs-report>.float-container .h1b-container .offer-board .img-container {
    order: 1
  }

  .cs-report>.float-container .h1b-container .offer-board p {
    width: 100%;
    padding-left: 0;
    margin: 20px 0 32px
  }

  .cs-report>.float-container .jobs-container {
    padding-top: 0
  }

  .cs-report>.float-container .jobs-container .employment,
  .cs-report>.float-container .jobs-container .new-graduation {
    display: none
  }

  .cs-report>.float-container .jobs-container .offer-rate {
    background: none;
    padding: 0 8%
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] {
    padding: 0
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row].major-rate {
    display: none
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] div[class*=ant-col-] {
    align-items: stretch
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] div[class*=ant-col-]>h2 {
    margin-bottom: 16px;
    margin-top: 20px
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] div[class*=ant-col-]>p {
    margin-bottom: 0
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] div[class*=ant-col-].img-container {
    order: 1;
    padding-top: 16px;
    padding-bottom: 16px
  }

  .cs-report>.float-container .jobs-container .offer-rate div[class*=ant-row] div[class*=ant-col-].img-container>img {
    margin-left: 0;
    width: 100%
  }

  .cs-report>.float-container .jobs-container .location {
    padding-top: 2%
  }

  .cs-report>.float-container .jobs-container .location h2 {
    margin-bottom: 16px;
    margin-top: 16px
  }

  .cs-report>.float-container .jobs-container .location img {
    margin-top: 20px
  }

  .cs-report>.float-container .recruitment-container {
    background: none;
    padding-bottom: 2%
  }

  .cs-report>.float-container .recruitment-container .resume {
    padding-top: 0
  }

  .cs-report>.float-container .recruitment-container .resume h2 {
    line-height: 1.5;
    margin-bottom: 0
  }

  .cs-report>.float-container .recruitment-container .resume p {
    margin-top: 12px
  }

  .cs-report>.float-container .recruitment-container .resume img {
    padding-bottom: 20px
  }

  .cs-report>.float-container .recruitment-container .course {
    padding-left: 12%;
    padding-right: 12%
  }

  .cs-report>.float-container .recruitment-container .course div[class*=ant-col]>a img {
    width: 32px !important
  }

  .cs-report>.float-container .recruitment-container .requirement .img-container {
    order: 1
  }

  .cs-report>.float-container .recruitment-container .requirement .img-container p {
    width: 100%
  }

  .cs-report .consult-container {
    padding: 10% 0 0;
    margin: 0;
    width: 100%
  }

  .cs-report .consult-container>div[class*=ant-row] {
    background-color: rgba(198, 236, 255, .3);
    padding: 48px 60px
  }

  .cs-report .consult-container>div[class*=ant-row] .resource {
    padding-right: 0;
    border-right: 0
  }

  .cs-report .consult-container>div[class*=ant-row] .question {
    padding-left: 0;
    padding-top: 32px
  }
}

.try-for-free {
  min-height: 80vh;
  background-color: #f5f7fa
}

.try-for-free .page-description {
  font-size: 14px;
  width: 80%;
  text-align: center
}

.try-for-free .fallback-form {
  padding: 44px 0 140px;
  width: 80%;
  margin: 0 auto
}

.try-for-free .fallback-form>.tip {
  text-align: right;
  padding-bottom: 8px;
  color: #8294a5
}

.try-for-free .fallback-form .fallback-form-right {
  display: flex;
  flex-direction: column;
  justify-content: space-between
}

.try-for-free .fallback-form .method-container {
  background-color: #fff;
  box-shadow: 0 0 2px rgba(6, 41, 74, .16);
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: relative;
  margin-bottom: 40px
}

.try-for-free .fallback-form .method-container .method-index {
  position: absolute;
  left: -12px;
  top: 20px;
  color: #fff;
  background-color: #03a9f4;
  font-size: 16px;
  text-align: center;
  line-height: 36px;
  padding: 0 24px 0 16px;
  z-index: 1
}

.try-for-free .fallback-form .method-container .method-index:before {
  content: "";
  position: absolute;
  border-top: 8px solid #098bc6;
  border-left: 12px solid transparent;
  left: 0;
  top: 100%
}

.try-for-free .fallback-form .method-container .method-index:after {
  content: "";
  position: absolute;
  border-bottom: 40px solid #fff;
  border-left: 20px solid transparent;
  right: -1px;
  top: -1px
}

.try-for-free .fallback-form .method-container .method-index.uk {
  background-color: #ff6c00
}

.try-for-free .fallback-form .method-container .method-index.uk:before {
  border-top: 8px solid #ff6c00
}

.try-for-free .fallback-form .method-container .helper-message {
  margin: 10px;
  text-align: center;
  font-size: 16px;
  color: #556b80
}

.try-for-free .fallback-form .method-container .helper-message span {
  display: block
}

.try-for-free .fallback-form .scan-qr-code {
  flex: 1 1;
  padding-left: 20px;
  padding-right: 20px
}

.try-for-free .fallback-form .scan-qr-code img {
  height: 160px;
  width: 160px;
  margin-bottom: 18px
}

.try-for-free .fallback-form .send-email {
  flex: 1 1;
  padding-left: 20px;
  padding-right: 20px
}

.try-for-free .fallback-form .send-email .anticon {
  color: #e9edf1;
  font-size: 70px !important
}

.try-for-free .fallback-form .send-email h3 {
  font-weight: 600;
  font-size: 24px;
  margin-top: 16px;
  text-align: center;
  line-height: 48px;
  margin-bottom: 8px;
  color: #06294a
}

.try-for-free .new-contact-form {
  padding: 72px 6% 30px;
  width: 100%
}

.try-for-free .new-contact-form .contact-divider {
  height: 44px;
  display: inline-flex;
  align-items: center;
  justify-content: center
}

.try-for-free .new-contact-form .ant-form-item-with-help {
  margin-bottom: 0
}

.try-for-free .new-contact-form .ant-form-item-children {
  display: flex
}

.try-for-free .new-contact-form .required {
  color: #f5222d;
  font-size: 20px;
  padding-top: 4px;
  width: 18px
}

.try-for-free .new-contact-form .ant-form-explain {
  padding-left: 17px;
  margin-top: 0;
  height: 24px
}

.try-for-free .new-contact-form .ant-input-affix-wrapper {
  height: 44px
}

.try-for-free .new-contact-form .ant-input-affix-wrapper .ant-input:not(:first-child) {
  padding-left: 36px
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children {
  position: relative;
  display: flex;
  height: 44px
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .prefix {
  position: absolute;
  left: 30px;
  top: 16px;
  z-index: 1
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .suffix {
  position: absolute;
  right: 12px;
  top: 16px;
  z-index: 1;
  -webkit-transition: -webkit-transform .3s;
  transition: -webkit-transform .3s;
  transition: transform .3s;
  transition: transform .3s, -webkit-transform .3s
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .suffix.up {
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
  -webkit-transform: rotate(180deg);
  transform: rotate(180deg)
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children>.courses-select-container {
  width: calc(100% - 18px)
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection {
  height: 44px
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered {
  height: 100%;
  margin-left: 28px;
  margin-right: 32px
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul {
  padding-left: 6px;
  height: 36px;
  display: flex
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li {
  height: 36px;
  line-height: 34px
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-selection__rendered ul li .ant-select-search__field__wrap {
  width: 0;
  overflow: hidden
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow {
  top: 50%
}

.try-for-free .new-contact-form .courses-select .ant-form-item-children .ant-select-selection .ant-select-arrow i {
  font-size: 14px
}

.try-for-free .new-contact-form .message-field {
  padding-top: 16px;
  margin-bottom: 16px
}

.try-for-free .new-contact-form .message-field .ant-form-item-label {
  font-size: 14px;
  color: #556b80
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper {
  background-color: #f8f9fb;
  padding: 22px
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper .ant-form-item-children {
  display: flex;
  flex-direction: column
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper .checkboxs-container,
.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper .checkboxs-container div[class*=ant-col-] {
  padding-bottom: 6px
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper .checkboxs-container div[class*=ant-col-] .ant-checkbox-wrapper {
  color: #1c3e5b
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper textarea::-webkit-scrollbar {
  width: 8px;
  height: 8px;
  border-radius: 1px
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper textarea::-webkit-scrollbar-track {
  background-color: #e2e2e2;
  border-radius: 2px
}

.try-for-free .new-contact-form .message-field .ant-form-item-control-wrapper textarea::-webkit-scrollbar-thumb {
  background-color: #bbc9d6;
  outline: 1px solid #708090;
  border-radius: 2px
}

.try-for-free .new-contact-form .agreement-field {
  margin-bottom: 8px
}

.try-for-free .new-contact-form .submit-field .ant-form-item-control {
  display: flex;
  justify-content: flex-end
}

.try-for-free .new-contact-form .submit-field .ant-form-item-control .ant-btn-primary {
  height: 44px;
  width: 180px;
  border-radius: 4px;
  font-size: 16px
}

.try-for-free .new-contact-form .submit-field .ant-form-item-control .ant-btn-primary[disabled] {
  opacity: .4;
  background-color: #03a9f4;
  color: #fff;
  border: 0
}

.try-for-free .new-contact-form .tip_form {
  margin-top: -5px;
  margin-left: 20px;
  margin-bottom: 10px
}

.consultation-modal .ant-modal-body {
  padding: 0
}

.consultation-modal .ant-modal-body iframe {
  border: none;
  width: 100%;
  height: 680px
}

@media (max-width:991px) {
  .scan-qr-code {
    padding-top: 48px;
    padding-bottom: 48px
  }

  .send-email {
    padding-top: 56px;
    padding-bottom: 56px
  }
}

@media (max-width:767px) {
  .fallback-form {
    padding-bottom: 14%
  }

  .contact-divider {
    margin-top: -24px
  }

  .contact-divider+div[class*=ant-col-] {
    padding-left: 24px !important
  }
}

.faq .questions-container {
  width: 80%;
  margin: 0 10%
}

.faq .questions-container .ant-collapse-header {
  font-size: 16px;
  font-weight: 500
}

.faq .questions-container .ant-collapse-content {
  padding: 0 36px
}

.faq .questions-container .ant-collapse-content .markdown-content {
  font-size: 14px
}

.faq .questions-container .ant-collapse-content .markdown-content ul {
  margin: 6px 0;
  list-style: square outside;
  padding-left: 12px
}

.faq .questions-container .ant-collapse-content .markdown-content li {
  margin-bottom: 6px
}

.faq .questions-container .ant-collapse-content .markdown-content li:last-child {
  margin-bottom: 0
}

.faq .questions-container .ant-collapse-content .markdown-content p {
  margin: 6px 0
}

.faq .send-email-container {
  width: 50%;
  margin: -24px auto;
  text-align: center
}

.faq .send-email-container .ant-btn {
  margin: 24px 0
}

@media (max-width:991px) {
  .faq .questions-container {
    width: 90%;
    margin: 0 5%
  }

  .faq .send-email-container {
    width: 80%
  }
}

.certificates .page-header .certificate-form {
  padding: 24px 0 0;
  width: 100%;
  height: 87px
}

.certificates .certificate-container {
  margin-top: -36px;
  margin-bottom: 108px;
  padding: 60px 5%;
  overflow: hidden
}

.certificates .certificate-container .certificate-empty {
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: center
}

.certificates .certificate-container .certificate-empty .text {
  max-width: 100%;
  height: 96px
}

.certificates .certificate-container .certificate-empty .stamp {
  position: absolute;
  height: 192px;
  right: -10%;
  bottom: -84px
}

.course-certificate.ai-camp .cls-12,
.course-certificate.ai-camp .curve-2,
.course-certificate.ai-camp .curve-3,
.course-certificate.ai-camp .curve-4,
.course-certificate.ai-camp .curve-5,
.course-certificate.ai-camp .line,
.course-certificate.ai-camp .line-2 {
  fill: none
}

.course-certificate.ai-camp .curve-2,
.course-certificate.ai-camp .curve-3,
.course-certificate.ai-camp .curve-4 {
  stroke: #505d65
}

.course-certificate.ai-camp .border,
.course-certificate.ai-camp .curve-2,
.course-certificate.ai-camp .curve-3,
.course-certificate.ai-camp .curve-4,
.course-certificate.ai-camp .line-2 {
  stroke-linecap: round;
  stroke-linejoin: round
}

.course-certificate.ai-camp .curve-2 {
  stroke-width: .2px
}

.course-certificate.ai-camp .curve {
  fill: #4e5c62
}

.course-certificate.ai-camp .curve-3 {
  stroke-width: .4px
}

.course-certificate.ai-camp .curve-4,
.course-certificate.ai-camp .curve-5 {
  stroke-width: .3px
}

.course-certificate.ai-camp .shape {
  fill: #416980
}

.course-certificate.ai-camp .border,
.course-certificate.ai-camp .cls-12,
.course-certificate.ai-camp .curve-5 {
  stroke: #416980
}

.course-certificate.ai-camp .cls-12,
.course-certificate.ai-camp .curve-5,
.course-certificate.ai-camp .line {
  stroke-miterlimit: 10
}

.course-certificate.ai-camp .line-2 {
  stroke: #4f575f
}

.course-certificate.ai-camp .border,
.course-certificate.ai-camp .line,
.course-certificate.ai-camp .line-2 {
  stroke-width: .5px
}

.course-certificate.ai-camp .line-3 {
  fill: #4f575f
}

.course-certificate.ai-camp .line {
  stroke: #2f302f
}

.course-certificate.ai-camp .cert-id {
  font-size: 11.73px
}

.course-certificate.ai-camp .name {
  font-size: 44px
}

.course-certificate.ai-camp .date {
  font-size: 16px
}

.course-certificate.course .curve-2,
.course-certificate.course .line {
  fill: #505d65
}

.course-certificate.course .curve-3 {
  fill: #416980
}

.course-certificate.course .line {
  fill: none;
  stroke: #35464c;
  stroke-miterlimit: 10
}

.course-certificate.course .border,
.course-certificate.course .line,
.course-certificate.course .line-2 {
  stroke-width: .5px
}

.course-certificate.course .curve-4 {
  fill: #4f575f
}

.course-certificate.course .name {
  font-size: 30px
}

.course-certificate.course .date {
  font-size: 16px
}

.course-certificate.course .cert-id {
  font-size: 13px
}

.course-certificate.course .duration {
  font-size: 16px
}

.course-certificate .main-bg {
  fill: #f0f5f7
}

.course-certificate .band-bottom {
  fill: #30525e
}

.course-certificate .band-shadow {
  fill: #284953
}

.course-certificate .band-top {
  fill: #446879
}

.course-certificate .bg,
.course-certificate .border {
  fill: #fff
}

.course-certificate .cert-id,
.course-certificate .char,
.course-certificate .date,
.course-certificate .duration,
.course-certificate .name {
  fill: #4b585d;
  font-family: TimesNewRomanPSMT, Times New Roman
}

.course-certificate .date,
.course-certificate .name {
  text-anchor: middle
}

.honored-certificate .main-bg {
  fill: #fff
}

.honored-certificate .sub-bg {
  fill: #f5fbfc
}

.honored-certificate .border {
  fill: #29697f
}

.honored-certificate .cert-id,
.honored-certificate .char,
.honored-certificate .char-4,
.honored-certificate .course,
.honored-certificate .name,
.honored-certificate .title {
  fill: #274d69
}

.honored-certificate .char,
.honored-certificate .char-2,
.honored-certificate .char-3,
.honored-certificate .char-4,
.honored-certificate .title {
  font-family: TimesNewRomanPSMT, Times New Roman
}

.honored-certificate .name {
  font-size: 31.01px
}

.honored-certificate .course,
.honored-certificate .name {
  font-family: Times-Bold, Times;
  font-weight: 700
}

.honored-certificate .course {
  font-size: 25.1px
}

.honored-certificate .border-thin {
  fill: #2b8493
}

.honored-certificate .shape {
  fill: #c9eaf2
}

.honored-certificate .title {
  font-size: 12.71px
}

.honored-certificate .char {
  font-size: 15.51px
}

.honored-certificate .char-2 {
  fill: #2e6472
}

.honored-certificate .char-3 {
  fill: #416980
}

.honored-certificate .char-4 {
  font-size: 12px;
  font-weight: 700
}

.honored-certificate .cert-id {
  font-size: 12.19px;
  font-family: Arial
}

.honored-certificate .line {
  fill: none;
  stroke: #35464c;
  stroke-miterlimit: 10;
  stroke-width: .5px
}

.careers .positions-container {
  background-color: #f7fafc;
  min-height: 100vh
}

.job-post-card {
  width: 80%;
  margin: 0 auto 18px
}

.job-post-card:last-child {
  margin-bottom: 0
}

.job-post-card h3 {
  color: #20b9f9;
  font-size: 24px
}

.job-post-card .job-info {
  font-size: 14px;
  font-weight: 400;
  color: rgba(0, 0, 0, .45);
  white-space: nowrap
}

.job-post-card .job-info span {
  padding-left: 12px
}

.job-post-card .apply-btn-wrapper {
  display: flex;
  justify-content: flex-end;
  margin: auto
}

@media (max-width:991px) {
  .job-post-card .apply-btn-wrapper {
    display: flex;
    justify-content: center;
    margin: auto
  }
}

@media (max-width:767px) {
  .job-post-card .apply-btn-wrapper {
    display: flex;
    justify-content: center;
    margin: auto
  }
}

.job-post {
  min-height: 100vh
}

.job-post .page-header {
  padding-left: 8.33333%;
  padding-right: 8.33333%
}

.job-post div[class*=ant-row] {
  width: 100%;
  height: 100%
}

.job-post div[class*=ant-row] .gutter-row {
  display: flex;
  flex-flow: column nowrap;
  justify-content: center;
  align-items: flex-start;
  height: 100%
}

.job-post div[class*=ant-row] .gutter-row .page-title {
  margin: 6px 0;
  text-align: left;
  display: flex;
  max-width: 100%;
  max-height: 83.2px;
  font-size: 32px;
  line-height: 1.3;
  -webkit-line-clamp: 2;
  -webkit-box-align: start;
  flex-direction: row;
  overflow: hidden;
  text-overflow: ellipsis
}

.job-post div[class*=ant-row] .gutter-row .job-info {
  font-size: 16px
}

.job-post div[class*=ant-row] .gutter-row .job-info>* {
  color: hsla(0, 0%, 100%, .85);
  font-size: 14px
}

.job-post div[class*=ant-row] .gutter-row .job-info span {
  padding-left: 24px
}

.job-post div[class*=ant-row] .gutter-row .apply-btn {
  background-color: #fff;
  color: #20b9f9
}

.job-post .job-detail-container {
  width: 80%;
  padding-left: 8.33333%;
  padding-right: 8.33333%
}

.job-post .job-detail-container p {
  margin: 12px 0;
  font-size: 14px
}

.job-post .job-detail-container ul {
  list-style: square inside;
  margin-top: 6px;
  font-size: 14px;
  overflow: hidden
}

@media (max-width:991px) {
  .news-post .page-header {
    padding-left: 4.16666%;
    padding-right: 4.16666%
  }
}

@media (max-width:767px) {
  .job-post .page-header div[class*=ant-row] .gutter-row {
    height: auto;
    align-items: center
  }

  .job-post .page-header div[class*=ant-row] .gutter-row .job-info span {
    padding-left: 12px
  }

  .job-post .job-detail-container {
    width: 100%;
    padding-left: 8.33333%;
    padding-right: 8.33333%
  }
}

.privacy-terms .privacy-terms-container {
  text-align: center;
  width: 70%;
  margin: auto
}

.privacy-terms .privacy-terms-container .ant-tabs-tabpane {
  text-align: left
}

.privacy-terms .privacy-terms-container .ant-tabs-tabpane h2,
.privacy-terms .privacy-terms-container .ant-tabs-tabpane h3,
.privacy-terms .privacy-terms-container .ant-tabs-tabpane p {
  padding: 6px 0
}

.privacy-terms .privacy-terms-container .ant-tabs-tabpane ul {
  list-style: square inside;
  margin-top: 6px;
  font-size: 14px;
  overflow: hidden
}

.privacy-terms .privacy-terms-container .ant-tabs-tabpane ul li {
  padding: 6px 0
}

.lem-header {
  height: 720px
}

#lem-header-overlay {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, .5);
  z-index: 1
}

.lem-nav-header {
  display: grid;
  grid-template-columns: 0 50% 50% 0
}

.lem-nav-header .logo-container-icon {
  align-self: flex-start
}

.lem-nav-header .logo-container-icon img {
  height: 96px;
  width: 96px;
  margin-top: 24px;
  margin-left: 120px
}

.lem-nav-header .button-container {
  display: flex;
  padding-right: 120px;
  justify-content: flex-end
}

.lem-nav-header .button-container .btn-enroll {
  display: inline-block;
  background: #eb2f96;
  padding: 0 16px;
  line-height: 32px;
  height: 32px;
  font-size: 14px;
  -webkit-transition: background .2s ease;
  transition: background .2s ease;
  color: #f4f6fa;
  border-radius: 16px;
  margin: 48px 0 0;
  border: none
}

.btn-enroll.sub,
.btn-enroll.sub:hover {
  background-color: transparent
}

.btn-enroll.sub:hover {
  border-color: #f4f6fa;
  color: #f4f6fa
}

.lem-header-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: #f4f6fa
}

.lem-header-content .lem-title {
  font-size: 40px;
  font-weight: 700;
  margin-bottom: 20px;
  align-self: center;
  word-wrap: none
}

.lem-header-content .lem-subtitle {
  font-size: 18px;
  margin-top: 12px;
  margin-bottom: 9px;
  align-self: center
}

.lem-header-content .lem-goal-header {
  font-size: 40px;
  font-weight: 700;
  margin-top: 60px;
  margin-bottom: 20px;
  align-self: center;
  text-align: center
}

.lem-header-content .lem-goal-content {
  font-size: 18px;
  margin-top: 12px;
  text-align: center;
  margin-bottom: 36px;
  width: 960px;
  align-self: center
}

.lem-header-content button {
  align-self: center;
  border-radius: 6px;
  background-color: transparent;
  color: #f4f6fa;
  padding: 4px 36px
}

.lem-quote {
  background-color: #03a9f4;
  width: 720px;
  height: 330px;
  margin-left: 10%;
  margin-top: -80px;
  z-index: 1;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: #f4f6fa
}

.lem-quote .quote-content {
  width: 60%;
  display: flex;
  flex-direction: column
}

.lem-quote .quote-content span {
  font-size: 60px;
  height: 40px
}

.lem-quote .quote-content .left {
  margin-left: -40px
}

.lem-quote .quote-content .right {
  margin-right: -30px;
  align-self: flex-end
}

.lem-quote .quote-content strong {
  font-size: 16px !important
}

.lem-quote .quote-author-container {
  display: flex;
  align-self: flex-start;
  padding-left: 120px
}

.lem-quote .quote-author-container img {
  border-radius: 50%;
  height: 60px
}

.lem-quote .quote-author-container .quote-info {
  margin-left: 12px;
  display: flex;
  justify-content: flex-end;
  flex-direction: column
}

#valuesLEM {
  margin-top: 60px
}

#valuesLEM .value-item.float-container {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  width: 820px;
  margin-bottom: 24px
}

#valuesLEM .value-item.float-container img {
  height: 96px;
  width: 96px;
  margin-left: 24px
}

#valuesLEM .value-item.float-container p {
  width: 600px
}

#valuesLEM .value-item.float-container:nth-child(3) {
  margin-left: 100px
}

.student-case {
  margin-right: 24px;
  width: 275px
}

.student-desc,
.student-education-background {
  padding-left: 28px;
  padding-right: 28px
}

.student-education-background {
  padding-top: 36px
}

.student-education-background .background-header {
  font-weight: 700;
  margin-right: 8px
}

.student-desc {
  padding-top: 36px;
  height: 200px;
  overflow: hidden;
  text-overflow: ellipsis
}

.student-card {
  width: 280px;
  margin-right: 24px
}

.student-card .student-name {
  height: 90px;
  padding-top: 30px
}

.student-card .student-name h2 {
  font-size: 32px;
  padding-bottom: 18px;
  margin-bottom: 36px;
  position: relative;
  height: 80px
}

.student-card .student-name .dash {
  background-color: #03a9f4
}

.card-buttom {
  margin-top: 36px;
  display: flex;
  justify-content: flex-end;
  padding: 20px
}

.program-flow {
  display: flex;
  flex-direction: column
}

.program-flow .program-icon {
  display: flex
}

.program-flow .program-flow-content {
  padding-left: 10%;
  padding-right: 24%;
  height: 500px
}

.program-flow .program-flow-image {
  height: 100%;
  width: 90%
}

.program-flow .program-flow-image-mobile {
  display: none;
  height: 100%
}

.nav-button {
  width: 100%;
  height: 58px;
  border: none;
  color: #fff;
  background-color: #03a9f4;
  border-radius: 0
}

.main-title-lem span {
  color: #fff
}

.main-title-lem .dash-lem {
  position: absolute;
  bottom: 0;
  left: 0;
  top: -120px;
  right: 0;
  margin: auto;
  width: 48px;
  height: 3px;
  background: #03a9f4
}

.project-footer {
  text-align: center;
  color: #03a9f4;
  border-top: 1px solid #f4f6fa;
  padding-top: 20px
}

.instructor-company-wrapper,
.instructor-education-wrapper {
  padding: 48px 25% 48px 10%;
  width: 100%;
  display: flex;
  justify-content: flex-end;
  flex-direction: column
}

.instructor-company-wrapper .main-title,
.instructor-education-wrapper .main-title {
  font-size: 32px;
  padding-bottom: 18px;
  margin-bottom: 36px;
  text-align: center;
  position: relative;
  text-align: left
}

.instructor-company-wrapper .main-title .dash,
.instructor-education-wrapper .main-title .dash {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  margin-left: 0;
  width: 48px;
  height: 3px;
  background: #03a9f4
}

.instructor-company-line,
.instructor-education-line {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  margin-bottom: 24px
}

.instructor-company-line .logo-container,
.instructor-education-line .logo-container {
  height: 132px;
  width: 180px;
  margin-right: 24px;
  display: flex;
  justify-content: center;
  align-items: center
}

.instructor-company-line .logo-container img,
.instructor-education-line .logo-container img {
  height: 120px;
  width: 120px
}

@media screen and (max-width:960px) {
  .lem-goal-content {
    width: 500px !important
  }

  .program-flow .program-flow-image {
    display: none
  }

  .program-flow-image-mobile {
    display: flex !important;
    justify-content: center;
    align-items: center
  }

  .program-flow-image-mobile img {
    height: 100%;
    width: 100%
  }
}

@media screen and (max-width:720px) {
  .lem-goal-content {
    width: 330px !important
  }

  .lem-quote {
    height: 660px;
    width: 330px;
    margin: -72px auto auto
  }

  .lem-nav-header {
    display: none
  }

  .lem-header-content {
    margin-top: 36px
  }

  .student-case {
    margin-bottom: 24px
  }

  .value-item.float-container {
    width: 330px !important;
    margin-left: 10% !important;
    height: auto
  }

  .value-item.float-container p {
    width: auto !important
  }

  .instructor-company-line,
  .instructor-education-line {
    flex-direction: column
  }
}

.partners {
  margin-bottom: 10%
}

.content .page-title {
  margin-top: 24px;
  overflow: visible !important
}

.content .page-sub-title {
  margin-bottom: 24px !important;
  width: 500px;
  text-align: center
}

.content .become-partner-btn {
  background-color: transparent;
  border-radius: 24px;
  padding: 5px 24px;
  color: #fff;
  border: 1px solid #fff
}

.content .become-partner-btn:hover {
  border: 1px solid #fcc3e0;
  color: #fcc3e0
}

.partners-content-section {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-top: 36px
}

.partners-content-section .partners-header {
  font-size: 24px;
  font-weight: 800;
  margin-bottom: 24px;
  display: flex
}

.partners-content-section .partners-header .dash {
  width: 48px;
  height: 3px;
  background: #03a9f4
}

.partners-content-section .partners-header span {
  margin-bottom: 24px
}

.partners-content-section .partners-sub-title {
  width: 480px;
  text-align: center;
  margin-bottom: 36px
}

.partners-content-section .partner-logos-line {
  display: flex;
  justify-content: center;
  align-items: center
}

.partners-content-section .partner-logos-line .logo-container {
  height: 84px;
  width: 180px;
  margin-right: 24px;
  display: flex;
  justify-content: center;
  align-items: center
}

.partners-content-section .partner-logos-line .logo-container img {
  height: 120px;
  width: 120px
}

.partners-button-row {
  display: flex;
  justify-content: center
}

.magic-name {
  width: 200px
}

@media screen and (max-width:1000px) {
  .partners-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center
  }

  .partner-logos-line {
    display: flex;
    flex-direction: column
  }
}

@media screen and (max-width:576px) {

  .page-sub-title,
  .partners-sub-title {
    width: 330px !important
  }
}

.catalog .courses-container {
  padding: 60px 15%;
  background-color: #fcfcfc
}

.catalog .courses-container .catalog-course-card {
  margin-bottom: 50px;
  box-shadow: none;
  -webkit-transition: box-shadow .2s;
  transition: box-shadow .2s
}

.catalog .courses-container .catalog-course-card:hover {
  box-shadow: 0 2px 16px #eee
}

.landing-page {
  position: relative;
  background-size: 1300px;
  background-repeat: no-repeat;
  overflow-x: hidden
}

.landing-page h1,
.landing-page h2,
.landing-page h3 {
  color: #00274b
}

.landing-page .landing-background-video {
  width: 56%;
  height: auto
}

.landing-page .landing-background-video:focus {
  outline: none
}

.landing-page .arrow-container {
  display: flex;
  justify-content: center
}

.landing-page .right-qr-code {
  position: fixed;
  right: 0;
  top: 72px;
  padding: 8px;
  width: 136px;
  background-color: #fff;
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 6px #f4f6fa;
  z-index: 2;
  display: flex;
  flex-direction: column
}

.landing-page .right-qr-code span {
  position: relative;
  margin-bottom: 6px
}

.landing-page .right-qr-code span i {
  color: #03a9f4;
  position: absolute;
  right: 0;
  bottom: 0
}

.landing-page .right-qr-code img {
  width: 120px
}

.landing-page .main-area {
  height: 90vh;
  padding: 10%;
  margin-bottom: 56px;
  position: relative;
  display: flex;
  justify-content: space-between
}

.landing-page .main-area .landing-form {
  position: relative;
  width: 35%;
  z-index: 1;
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa;
  background-color: #fff;
  height: -webkit-fit-content;
  height: fit-content;
  padding: 40px;
  display: flex;
  flex-direction: column;
  justify-content: space-between
}

.landing-page .main-area .landing-form .ant-form-item-children {
  display: flex
}

.landing-page .main-area .landing-form .required {
  color: #f5222d;
  font-size: 20px;
  padding-top: 4px;
  width: 18px
}

.landing-page .main-area .landing-form .title {
  border-bottom: 4px solid #03a9f4;
  width: -webkit-fit-content;
  width: fit-content;
  font-size: 26px
}

.landing-page .main-area .landing-form .sub-title {
  box-shadow: inset 0 -12px #c9eeff;
  color: #758293;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page .main-area .landing-form .input {
  height: 40px;
  border-radius: 2px
}

.landing-page .main-area .landing-form .trial-btn .ant-btn {
  background-color: #03a9f4;
  color: #fff;
  border-radius: 0;
  border: none;
  margin-bottom: 16px;
  width: 100%
}

.landing-page .main-area .landing-form .trial-btn .ant-btn.disable,
.landing-page .main-area .landing-form .trial-btn .ant-btn:disabled {
  background-color: #8bdbff
}

.landing-page .main-area .landing-form .lower {
  display: grid;
  grid-template-columns: auto 120px;
  grid-column-gap: 32px;
  justify-content: space-between;
  padding-top: 16px;
  border-top: 1px solid #e9ecf0
}

.landing-page .main-area .landing-form .lower .left span {
  margin-top: 16px;
  display: flex;
  position: relative
}

.landing-page .main-area .landing-form .lower .left i {
  color: #03a9f4;
  position: absolute;
  right: 0;
  bottom: 0
}

.landing-page .main-area .landing-form .lower .qr-code-container img {
  border: 4px solid #c9eeff;
  width: 120px
}

.landing-page .main-area .landing-form .arrow-container {
  position: absolute;
  bottom: -64px;
  left: 0;
  width: 100%
}

.landing-page .main-area .landing-form .arrow-container img {
  height: 56px
}

.landing-page .mask {
  position: absolute;
  bottom: -120px;
  left: 0;
  right: 0;
  overflow: hidden
}

.landing-page .mask .mask-inner {
  width: 100%;
  height: 84px;
  border-left: 1920px solid transparent;
  border-bottom: 84px solid #f7fafc
}

.landing-page .mask .mask-lower {
  width: 100%;
  height: 84px;
  border-right: 1920px solid transparent;
  border-top: 84px solid #f7fafc
}

.landing-page .mask .content {
  display: flex;
  justify-content: flex-end;
  background-color: #f7fafc;
  padding: 16px 10%;
  position: relative
}

.landing-page .mask .content .text {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly
}

.landing-page .mask .content .text h2 {
  box-shadow: inset 0 -12px #c6eee2;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page .mask .content .text .orange {
  color: #ff8a18;
  font-size: 16px
}

.landing-page .mask .content .draw {
  height: 100px;
  width: 100px;
  border-radius: 50%;
  background-color: rgba(24, 193, 132, .2);
  position: absolute;
  bottom: 48px;
  cursor: pointer
}

.landing-page .mask .content .draw.i {
  background-color: rgba(24, 193, 132, .5);
  -webkit-transform: scale(.85);
  transform: scale(.85);
  position: absolute;
  top: 0
}

.landing-page .mask .content .draw.ii {
  background-color: #18c184;
  -webkit-transform: scale(.8);
  transform: scale(.8);
  position: absolute;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  font-size: 20px
}

.landing-page .mask .content .draw.ii span {
  font-size: 24px
}

.landing-page .mask .content .draw:hover .draw.ii {
  -webkit-transform: scale(1);
  transform: scale(1);
  -webkit-transition: all .5s ease;
  transition: all .5s ease
}

.landing-page .landing-middle {
  padding: 10% 10% 5%;
  display: flex;
  justify-content: space-between;
  background-size: contain;
  background-repeat: no-repeat
}

.landing-page .landing-middle .middle-cards {
  width: 45%
}

.landing-page .landing-middle .middle-cards .header {
  padding: 16px 0 24px;
  display: flex;
  justify-content: space-between;
  position: relative;
  align-items: center
}

.landing-page .landing-middle .middle-cards .header .blue {
  height: 3px;
  background-color: #3bbdf8;
  width: 56px;
  position: absolute;
  top: 0
}

.landing-page .landing-middle .left .offer-card {
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa;
  padding: 32px 16px 24px;
  display: flex;
  flex-direction: column;
  width: 70%;
  background-color: #fff;
  margin-top: -20px
}

.landing-page .landing-middle .left .offer-card.c1,
.landing-page .landing-middle .left .offer-card.c3 {
  margin-left: 30%
}

.landing-page .landing-middle .left .offer-card .logo {
  display: flex;
  justify-content: flex-end
}

.landing-page .landing-middle .left .offer-card .logo img {
  height: 24px;
  margin-bottom: 8px
}

.landing-page .landing-middle .left .offer-card .title {
  font-weight: 500;
  margin-bottom: 8px
}

.landing-page .landing-middle .left .offer-card .content {
  display: grid;
  grid-template-columns: 28% auto;
  font-size: 12px;
  color: #98a3b1
}

.landing-page .landing-middle .left .offer-card .content .content {
  display: flex;
  flex-direction: column
}

.landing-page .landing-middle .right .course-card {
  display: flex;
  background: #fff;
  margin-bottom: 30px;
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa
}

.landing-page .landing-middle .right .course-card img {
  height: 108px;
  width: 108px;
  -o-object-fit: cover;
  object-fit: cover
}

.landing-page .landing-middle .right .course-card .right {
  height: 108px;
  padding: 14px;
  width: calc(100% - 108px);
  position: relative
}

.landing-page .landing-middle .right .course-card .right .subtitle {
  display: flex;
  align-items: center;
  justify-content: space-between
}

.landing-page .landing-middle .right .course-card .right .subtitle span {
  color: #3bbdf8;
  width: 75%
}

.landing-page .landing-middle .right .course-card .right .subtitle .ant-btn {
  border: 0;
  border-radius: 0;
  background-color: #03a9f4;
  margin-left: 8px;
  display: flex;
  position: absolute;
  right: 14px;
  bottom: 14px;
  align-items: center
}

.landing-page .landing-middle .right .course-card .right .subtitle .ant-btn span {
  color: #fff
}

.landing-page .landing-middle .right .course-card .right .subtitle .ant-btn:hover {
  background-color: #3bbdf8
}

.landing-page .banner {
  margin: 32px -15%;
  font-size: 20px;
  color: #fff;
  padding: 16px 0;
  text-align: center
}

.landing-page .qr-code-panel {
  width: 40%;
  padding: 56px;
  background-color: #fff;
  box-shadow: 0 0 10px #f4f6fa;
  border: 1px solid #e9ecf0;
  border-top: 3px solid #03a9f4
}

.landing-page .qr-code-panel .code-container {
  display: grid;
  grid-template-columns: auto 18px 160px;
  align-items: center;
  padding: 16px
}

.landing-page .qr-code-panel .code-container i {
  color: #03a9f4
}

.landing-page .qr-code-panel .code-container img {
  height: 160px;
  width: 160px;
  border: 4px solid #c9eeff
}

.landing-page .qr-code-panel .code-container span {
  font-weight: 600
}

.landing-page-draw-modal .ant-modal-header {
  border: 0;
  padding: 32px 24px 0
}

.landing-page-draw-modal .ant-modal-title {
  text-align: center;
  font-weight: 700;
  font-size: 30px;
  color: #00274b
}

.landing-page-draw-modal .lower-decor {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  border-bottom: 3px solid #00274b;
  margin-top: -36px
}

.landing-page-draw-modal .cards-container {
  display: flex;
  padding: 50px 160px 0;
  width: 1110px;
  height: 378px
}

.landing-page-draw-modal .cards-container .card-wrapper {
  width: 229px;
  height: 328px;
  position: absolute;
  -webkit-perspective: 800px;
  perspective: 800px;
  z-index: 1
}

.landing-page-draw-modal .cards-container .card-wrapper:hover {
  -webkit-transform: translateY(-4px);
  transform: translateY(-4px)
}

.landing-page-draw-modal .cards-container .card-wrapper.hidden {
  display: none
}

.landing-page-draw-modal .cards-container .card-wrapper.c1 {
  margin-left: 0
}

.landing-page-draw-modal .cards-container .card-wrapper.c2 {
  margin-left: 275.5px
}

.landing-page-draw-modal .cards-container .card-wrapper.c3 {
  margin-left: 551px
}

.landing-page-draw-modal .cards-container .card-wrapper.chosen {
  opacity: 0;
  -webkit-transition: opacity .5s ease;
  transition: opacity .5s ease
}

.landing-page-draw-modal .cards-container .card-wrapper.chosen.chosen-card {
  opacity: 1;
  -webkit-transition: all 1s ease;
  transition: all 1s ease;
  margin-left: 275.5px;
  -webkit-transform: scale(1.2);
  transform: scale(1.2)
}

.landing-page-draw-modal .cards-container .card-wrapper .card-container {
  position: relative;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  cursor: pointer;
  width: 100%;
  height: 100%;
  -webkit-transition: all 4s ease;
  transition: all 4s ease
}

.landing-page-draw-modal .cards-container .card-wrapper .card-container .card__face {
  position: absolute;
  height: 100%;
  width: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden
}

.landing-page-draw-modal .cards-container .card-wrapper .card-container .card__face--back {
  -webkit-transform: rotateY(180deg);
  transform: rotateY(180deg)
}

.landing-page-draw-modal .cards-container .card-wrapper .card-container.show-front {
  -webkit-transform: rotateY(0deg);
  transform: rotateY(0deg)
}

.landing-page-draw-modal .cards-container .card-wrapper .card-container.show-back {
  -webkit-transform: rotateY(1260deg);
  transform: rotateY(1260deg)
}

.landing-page-draw-modal .cards-container.chosen {
  display: flex;
  justify-content: space-between;
  align-items: center
}

.landing-page-draw-modal .cards-container .circle {
  opacity: 0;
  -webkit-transition: opacity .5s;
  transition: opacity .5s
}

.landing-page-draw-modal .cards-container .circle.visible {
  opacity: 1
}

.landing-page-draw-modal .cards-container .circle.left {
  margin-bottom: 80px;
  margin-left: 48px
}

.landing-page-draw-modal .cards-container .circle.right {
  margin-right: 64px;
  margin-top: 96px
}

.landing-page-draw-modal .cards-container .square {
  opacity: 0;
  -webkit-transition: opacity .5s;
  transition: opacity .5s;
  position: absolute
}

.landing-page-draw-modal .cards-container .square.visible {
  opacity: 1
}

.landing-page-draw-modal .cards-container .square.right {
  right: 200px
}

.landing-page-draw-modal .mobile {
  display: none
}

.landing-page-email-modal .ant-modal-header {
  border: 0;
  padding: 32px 24px 0
}

.landing-page-email-modal .ant-modal-title {
  text-align: center;
  font-size: 20px;
  color: #00274b
}

.landing-page-email-modal h2,
.landing-page-email-modal h3,
.landing-page-email-modal h4 {
  color: #00274b
}

.landing-page-qr-modal .ant-modal-header {
  border: 0;
  padding: 32px 24px 0
}

.landing-page-qr-modal .ant-modal-title {
  text-align: center;
  font-size: 20px;
  color: #00274b
}

.landing-page-qr-modal h2,
.landing-page-qr-modal h3,
.landing-page-qr-modal h4 {
  color: #00274b
}

.landing-page-qr-modal .ant-modal-body {
  padding: 32px 32px 64px;
  display: flex;
  flex-direction: column;
  align-items: center
}

.landing-page-qr-modal .ant-modal-body img {
  height: 220px;
  border: 8px solid #c9eeff
}

.hidden-lg-down.landing {
  text-align: right
}

.offer-board {
  position: relative;
  flex-flow: column nowrap;
  align-items: center;
  background: url(/images/graphs/cpp-offerboard-background.svg) no-repeat 50%
}

.offer-board .offer-board-inner {
  box-shadow: 0 6px 12px 0 rgba(137, 157, 181, .16);
  border-top: 5px solid #03a9f4;
  position: relative;
  width: 580px;
  margin: 0 auto;
  background-color: #fff;
  z-index: 99;
  height: 532px;
  overflow: auto
}

.offer-board .offer-board-inner::-webkit-scrollbar {
  width: 8px;
  height: 8px;
  border-radius: 1px
}

.offer-board .offer-board-inner::-webkit-scrollbar-track {
  background-color: #e2e2e2;
  border-radius: 2px
}

.offer-board .offer-board-inner::-webkit-scrollbar-thumb {
  background-color: #bbc9d6;
  outline: 1px solid #708090;
  border-radius: 2px
}

.offer-board .offer-board-inner .offer-list-inner {
  width: 100%;
  margin-bottom: 24px;
  overflow: hidden;
  max-height: 99999px;
  -webkit-transition: max-height 1.5s ease;
  transition: max-height 1.5s ease
}

.offer-board .offer-board-inner .offer-list-inner.collapse {
  max-height: 1860px
}

.offer-board .offer-board-inner .offer-list-inner .list-row {
  padding-bottom: 12px
}

.offer-board .offer-board-inner .offer-list-inner .list-row:first-child .list-week-col .dot {
  box-shadow: 3px -3px 0 0 #fff
}

.offer-board .offer-board-inner .offer-list-inner .list-row:last-child {
  padding-bottom: 0
}

.offer-board .offer-board-inner .offer-list-inner .list-row:last-child .list-week-col {
  margin-bottom: 0
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer {
  box-shadow: inset -2px 0 0 #d9d9d9;
  margin: 6px 0 -18px;
  padding: 0 30px 0 5px;
  display: flex;
  flex-flow: column nowrap;
  align-items: flex-end;
  position: relative
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer h3 {
  color: #03a9f4;
  font-size: 16px;
  line-height: 24px
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer .dot {
  width: 18px;
  height: 18px;
  border-radius: 50%;
  border: 3px solid #03a9f4;
  background: #fff;
  position: absolute;
  top: 3px;
  right: -8px
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-week-col-offer .badge {
  height: 72px;
  margin: -18px 0 -12px
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] {
  line-height: 36px;
  height: 36px;
  padding: 0 24px;
  font-size: 14px;
  display: flex;
  align-items: center;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.offer-board .offer-board-inner .offer-list-inner .list-row .list-row-inner div[class*=ant-col-] img {
  max-width: 96px;
  max-height: 24px;
  width: unset
}

.offer-board .offer-board-inner .add-on-container {
  background-color: #fafafa;
  width: 100%;
  text-align: center;
  margin-top: 6px;
  padding: 12px 0
}

.offer-board .offer-board-inner .add-on-container h2 {
  padding: 12px;
  font-size: 14px;
  color: rgba(0, 0, 0, .65)
}

.offer-board .offer-board-inner .add-on-container img {
  padding: 12px
}

.offer-board .offer-board-inner .list-header {
  width: 100%
}

.offer-board .offer-board-inner .list-header div[class*=ant-col-] {
  line-height: 48px;
  height: 48px;
  padding: 0 24px;
  font-size: 18px;
  font-weight: 500;
  text-align: left;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis
}

.landing-page-mobile {
  padding-top: 56px;
  box-shadow: 0 0 6px #f4f6fa;
  background-image: none !important
}

.landing-page-mobile h1,
.landing-page-mobile h2,
.landing-page-mobile h3,
.landing-page-mobile h4 {
  color: #00274b
}

.landing-page-mobile .arrow-container,
.landing-page-mobile .right-qr-code {
  display: none
}

.landing-page-mobile .landing-middle {
  background-image: none !important
}

.landing-page-mobile .landing-form {
  height: 60vh;
  padding: 16px;
  margin: 28px 28px 270px;
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa;
  background-color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: space-between
}

.landing-page-mobile .landing-form .title {
  border-bottom: 4px solid #03a9f4;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page-mobile .landing-form .sub-title {
  box-shadow: inset 0 -12px #c9eeff;
  color: #758293;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page-mobile .landing-form .input {
  height: 40px;
  border-radius: 2px
}

.landing-page-mobile .landing-form .trial-btn .ant-btn {
  background-color: #03a9f4;
  color: #fff;
  border-radius: 0;
  border: none;
  margin-bottom: 16px;
  width: 100%
}

.landing-page-mobile .landing-form .trial-btn .ant-btn:disabled {
  background-color: #8bdbff
}

.landing-page-mobile .landing-form .lower {
  display: grid;
  grid-template-columns: auto 120px;
  grid-column-gap: 4px;
  justify-content: space-between;
  padding-top: 16px;
  border-top: 1px solid #e9ecf0
}

.landing-page-mobile .landing-form .lower .left span {
  margin-top: 8px;
  display: flex;
  position: relative
}

.landing-page-mobile .landing-form .lower .left i {
  color: #03a9f4;
  position: absolute;
  right: 0;
  bottom: 0
}

.landing-page-mobile .landing-form .lower .qr-code-container img {
  border: 4px solid #c9eeff;
  width: 120px
}

.landing-page-mobile .mask .content {
  display: flex;
  justify-content: flex-end;
  padding: 28px;
  position: relative
}

.landing-page-mobile .mask .content .text {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly
}

.landing-page-mobile .mask .content .text h2 {
  box-shadow: inset 0 -12px #c6eee2;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page-mobile .mask .content .text .orange {
  color: #ff8a18;
  font-size: 16px;
  width: calc(100% - 120px)
}

.landing-page-mobile .mask .content .draw {
  height: 100px;
  width: 100px;
  border-radius: 50%;
  background-color: rgba(24, 193, 132, .2);
  position: absolute;
  bottom: 48px;
  cursor: pointer
}

.landing-page-mobile .mask .content .draw.i {
  background-color: rgba(24, 193, 132, .5);
  -webkit-transform: scale(.85);
  transform: scale(.85);
  position: absolute;
  top: 0
}

.landing-page-mobile .mask .content .draw.ii {
  background-color: #18c184;
  -webkit-transform: scale(.8);
  transform: scale(.8);
  position: absolute;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: #fff;
  font-size: 20px
}

.landing-page-mobile .mask .content .draw.ii span {
  font-size: 24px
}

.landing-page-mobile .mask .content .draw:hover .draw.ii {
  -webkit-transform: scale(1);
  transform: scale(1);
  -webkit-transition: all .5s ease;
  transition: all .5s ease
}

.landing-page-mobile .landing-background-video {
  width: 100vw;
  height: auto
}

.landing-page-mobile .landing-background-video:focus {
  outline: none
}

.landing-page-mobile .middle-cards .header {
  display: flex;
  justify-content: center;
  position: relative;
  align-items: center;
  margin-bottom: 24px
}

.landing-page-mobile .middle-cards .header a {
  display: none
}

.landing-page-mobile .middle-cards .header h2 {
  margin: 0;
  line-height: 48px
}

.landing-page-mobile .middle-cards .header .blue {
  height: 3px;
  background-color: #3bbdf8;
  width: 56px;
  position: absolute;
  bottom: 0
}

.landing-page-mobile .left .offer-card {
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa;
  padding: 32px 16px 24px;
  display: flex;
  flex-direction: column;
  width: 70%;
  height: 240px;
  background-color: #fff
}

.landing-page-mobile .left .offer-card .logo {
  display: flex;
  justify-content: flex-end
}

.landing-page-mobile .left .offer-card .logo img {
  height: 24px;
  margin-bottom: 8px
}

.landing-page-mobile .left .offer-card .title {
  font-weight: 500;
  margin-bottom: 8px
}

.landing-page-mobile .left .offer-card .content {
  display: flex;
  flex-direction: column;
  font-size: 12px;
  color: #98a3b1
}

.landing-page-mobile .left .offer-card .content .name {
  color: #576374
}

.landing-page-mobile .left .offer-card .content .content {
  display: flex;
  flex-direction: column
}

.landing-page-mobile .right .course-card {
  display: flex;
  background: #fff;
  margin-bottom: 30px;
  border: 1px solid #e9ecf0;
  box-shadow: 0 0 10px #f4f6fa
}

.landing-page-mobile .right .course-card img {
  height: 108px;
  width: 108px;
  -o-object-fit: cover;
  object-fit: cover
}

.landing-page-mobile .right .course-card .right {
  height: 108px;
  padding: 14px;
  width: calc(100% - 108px);
  position: relative
}

.landing-page-mobile .right .course-card .right .subtitle {
  display: flex;
  align-items: center;
  justify-content: space-between
}

.landing-page-mobile .right .course-card .right .subtitle span {
  color: #3bbdf8;
  width: 75%
}

.landing-page-mobile .right .course-card .right .ant-btn {
  border: 0;
  border-radius: 0;
  background-color: #03a9f4;
  margin-left: 8px;
  display: flex;
  position: absolute;
  right: 14px;
  bottom: 14px
}

.landing-page-mobile .right .course-card .right .ant-btn span {
  color: #fff
}

.landing-page-mobile .right .course-card .right .ant-btn:hover {
  background-color: #3bbdf8
}

.landing-page-mobile .right .course-card.course {
  height: 240px
}

.landing-page-mobile .right .course-card.course img {
  width: 100%;
  height: 48px
}

.landing-page-mobile .right .course-card.course .right {
  width: 100%;
  height: calc(100% - 48px);
  display: flex;
  flex-direction: column;
  justify-content: space-between
}

.landing-page-mobile .right .course-card.course .right .title-container {
  border-bottom: 1px solid #98a3b1
}

.landing-page-mobile .right .course-card.course .right .ant-btn {
  position: unset;
  width: -webkit-fit-content;
  width: fit-content;
  align-self: flex-end
}

.landing-page-mobile .banner {
  margin: 16px 0;
  font-size: 20px;
  color: #fff;
  padding: 8px 0;
  text-align: center;
  background-size: cover
}

.landing-page-mobile .course-card-container.news {
  padding: 0 24px
}

.landing-page-mobile .qr-code-panel {
  margin: 24px;
  padding: 24px;
  background-color: #fff;
  box-shadow: 0 0 10px #f4f6fa;
  border: 1px solid #e9ecf0;
  border-top: 3px solid #03a9f4;
  display: flex;
  flex-direction: column;
  align-items: center
}

.landing-page-mobile .qr-code-panel .code-container {
  padding: 16px 0 70px;
  position: relative;
  width: -webkit-fit-content;
  width: fit-content
}

.landing-page-mobile .qr-code-panel .code-container i {
  color: #03a9f4;
  position: absolute;
  bottom: 22px;
  right: 0;
  -webkit-transform: rotate(-90deg);
  transform: rotate(-90deg);
  font-size: 20px
}

.landing-page-mobile .qr-code-panel .code-container img {
  height: 200px;
  width: 200px;
  border: 4px solid #c9eeff
}

.landing-page-mobile .qr-code-panel .code-container span {
  font-weight: 600;
  position: absolute;
  bottom: 0
}

.landing-page-mobile .qr-code-panel .code-container.first {
  padding-bottom: 48px
}

.landing-page-mobile .ant-carousel {
  margin-bottom: 16px
}

.landing-page-mobile .ant-carousel .slick-list {
  height: 40vh
}

.landing-page-mobile .ant-carousel .slick-list .slick-slide {
  width: 71vw !important;
  margin: 0 4vw
}

.landing-page-mobile .ant-carousel .slick-dots-bottom button {
  width: 12px !important;
  height: 12px;
  border-radius: 50%;
  background-color: #435060
}

.landing-page-mobile .ant-carousel .slick-dots-bottom .slick-active button {
  background-color: #03a9f4
}

.landing-page-draw-modal.mobile .mobile {
  display: flex;
  font-size: 20px;
  flex-direction: column;
  color: #00274b;
  align-items: center;
  -webkit-transition: opacity .5s ease;
  transition: opacity .5s ease
}

.landing-page-draw-modal.mobile .mobile.inVisible {
  opacity: 0
}

.landing-page-draw-modal.mobile .ant-modal-header {
  border: 0;
  padding: 32px 24px 0
}

.landing-page-draw-modal.mobile .ant-modal-title {
  text-align: center;
  font-weight: 700;
  font-size: 30px;
  color: #00274b
}

.landing-page-draw-modal.mobile .lower-decor {
  display: none
}

.landing-page-draw-modal.mobile img {
  width: 84px
}

.landing-page-draw-modal.mobile .draw-content {
  display: flex;
  justify-content: center
}

.landing-page-draw-modal.mobile .cards-container {
  display: flex;
  align-items: center;
  padding: 0;
  width: 308px;
  height: 220px;
  position: relative
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper {
  width: 84px;
  height: 120.3px;
  position: absolute;
  -webkit-perspective: 800px;
  perspective: 800px;
  z-index: 1
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper:hover {
  -webkit-transform: translateY(-4px);
  transform: translateY(-4px)
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.hidden {
  display: none
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.c1 {
  margin-left: 0
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.c2 {
  margin-left: 112px
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.c3 {
  margin-left: 224px
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.chosen {
  opacity: 0;
  -webkit-transition: opacity .5s ease;
  transition: opacity .5s ease
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper.chosen.chosen-card {
  opacity: 1;
  -webkit-transition: all 1s ease;
  transition: all 1s ease;
  margin-left: 112px;
  -webkit-transform: scale(1.5);
  transform: scale(1.5)
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper .card-container {
  position: relative;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  cursor: pointer;
  width: 100%;
  height: 100%;
  -webkit-transition: all 4s ease;
  transition: all 4s ease
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper .card-container .card__face {
  position: absolute;
  height: 100%;
  width: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper .card-container .card__face--back {
  -webkit-transform: rotateY(180deg);
  transform: rotateY(180deg)
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper .card-container.show-front {
  -webkit-transform: rotateY(0deg);
  transform: rotateY(0deg)
}

.landing-page-draw-modal.mobile .cards-container .card-wrapper .card-container.show-back {
  -webkit-transform: rotateY(1260deg);
  transform: rotateY(1260deg)
}

.landing-page-draw-modal.mobile .cards-container.chosen {
  display: flex;
  justify-content: space-between;
  align-items: center
}

.landing-page-draw-modal.mobile .cards-container .circle {
  opacity: 0;
  -webkit-transition: opacity .5s;
  transition: opacity .5s
}

.landing-page-draw-modal.mobile .cards-container .circle.visible {
  opacity: 1
}

.landing-page-draw-modal.mobile .cards-container .circle.left {
  margin-bottom: 80px;
  margin-left: 0
}

.landing-page-draw-modal.mobile .cards-container .circle.right {
  margin-right: 0;
  margin-top: 96px
}

.landing-page-draw-modal.mobile .cards-container .square {
  opacity: 0;
  -webkit-transition: opacity .5s;
  transition: opacity .5s
}

.landing-page-draw-modal.mobile .cards-container .square.visible {
  opacity: 1
}

.landing-page-draw-modal.mobile .cards-container .square.right {
  position: absolute;
  right: 0
}

.course-detail.uk.new .course-summary {
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  padding: 0;
  width: -webkit-max-content;
  width: max-content;
  margin: -36px auto auto
}

.course-detail.uk.new .course-summary .nav-item {
  padding: 32px 40px;
  font-size: 18px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #06294a;
  width: 270px;
  border-right: 1px solid #e9edf1
}

.course-detail.uk.new .course-summary .nav-item i {
  color: #ff6c00;
  margin-right: 8px
}

.course-detail.uk.new .course-summary .try-for-free-btn {
  padding: 32px 48px;
  background-color: #ff6c00;
  color: #fff;
  font-size: 18px
}

.course-detail.uk.new .companies {
  margin-top: 48px;
  margin-left: 64px;
  display: flex;
  align-items: center;
  justify-content: center
}

.course-detail.uk.new .companies .company-item {
  margin-right: 72px
}

.course-detail.uk.new .course-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 6% 6% 0
}

.course-detail.uk.new .course-container h1 {
  font-size: 28px
}

.course-detail.uk.new .course-container .card-container {
  display: flex;
  justify-content: center;
  margin: 3% 0
}

.course-detail.uk.new .course-container .card-container .ai-and-data h3 {
  text-align: center;
  margin-bottom: 2%;
  font-size: 20px
}

.course-detail.uk.new .course-container .card-container .sde {
  margin-right: 6%
}

.course-detail.uk.new .course-container .card-container .sde h3 {
  text-align: center;
  margin-bottom: 2%;
  font-size: 20px
}

.course-detail.uk.new .course-container .card-container .courses {
  display: flex;
  justify-content: space-between
}

.course-detail.uk.new .course-container .card-container .courses .course-card {
  width: 380px;
  height: 600px;
  background-color: #fff;
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06)
}

.course-detail.uk.new .course-container .card-container .courses .course-card.data {
  margin-right: 4%
}

.course-detail.uk.new .course-container .card-container .courses .course-card img {
  margin-bottom: 12px
}

.course-detail.uk.new .course-container .card-container .courses .course-card h3 {
  height: 60px !important
}

.course-detail.uk.new .course-container .card-container .courses .course-card .frequency {
  height: 24px;
  color: #ff6c00;
  margin-bottom: 2%
}

.course-detail.uk.new .course-container .card-container .courses .course-card .desc {
  color: #8795a8;
  height: 90px
}

.course-detail.uk.new .course-container .card-container .courses .course-card .tag-container {
  margin: 12px 0;
  height: 120px
}

.course-detail.uk.new .course-container .card-container .courses .course-card .tag-container .tag-item {
  background-color: rgba(255, 108, 0, .1);
  color: #ff6c00;
  padding: 6px 10px;
  margin-right: 8px;
  margin-bottom: 8px;
  border-radius: 6px;
  height: 32px
}

.course-detail.uk.new .course-container .card-container .courses .course-card .status {
  color: #8795a8
}

.course-detail.uk.new .banner-container {
  height: 350px
}

.course-detail.uk.new .banner-container h2 {
  color: #fff;
  font-size: 32px
}

.course-detail.uk.new .banner-container div {
  width: 49%;
  text-align: center;
  color: #fff;
  font-size: 16px
}

.course-detail.uk.new .banner-container a {
  margin-top: 24px;
  padding: 12px 28px;
  color: #fff;
  background-color: #ff6c00
}

.course-detail.uk.new .uk-instructor-container {
  display: flex;
  flex-direction: column;
  align-items: center
}

.course-detail.uk.new .uk-instructor-container .instructor-container {
  padding: 0 8%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  background: -webkit-gradient(linear, left top, left bottom, from(#fcfcfc), to(#eff2f7));
  background: linear-gradient(#fcfcfc, #eff2f7)
}

.course-detail.uk.new .uk-instructor-container .instructor-container .instructor-item {
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  width: 320px;
  height: 300px;
  position: relative;
  border-bottom: 8px solid #06294a;
  margin-right: 24px;
  margin-bottom: 120px;
  background-color: #fff
}

.course-detail.uk.new .uk-instructor-container .instructor-container .instructor-item img {
  position: absolute;
  left: 30%;
  top: -20%
}

.course-detail.uk.new .uk-instructor-container .instructor-container .instructor-item .name {
  margin-top: 80px;
  font-size: 20px;
  text-align: center;
  padding-bottom: 24px
}

.course-detail.uk.new .uk-instructor-container .instructor-container .instructor-item .experience {
  padding: 0 12px;
  text-align: center
}

.course-detail.uk.new .uk-fag-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 6%
}

.course-detail.uk.new .uk-fag-container h1 {
  font-size: 32px;
  margin-bottom: 4%
}

.course-detail.uk.new .uk-fag-container .faq-container {
  display: flex;
  align-items: center
}

.course-detail.uk.new .uk-fag-container .faq-container .left {
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  border-top: 8px solid #ff6c00;
  padding: 20px;
  margin-right: 10%;
  height: 600px;
  width: 420px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff
}

.course-detail.uk.new .uk-fag-container .faq-container .left h3 {
  font-size: 24px
}

.course-detail.uk.new .uk-fag-container .faq-container .left .question-item {
  margin-bottom: 20px
}

.course-detail.uk.new .uk-fag-container .faq-container .left .question-item .title {
  font-size: 18px;
  color: #ff6c00;
  border-left: 2px solid #ff6c00;
  padding-left: 12px
}

.course-detail.uk.new .uk-fag-container .faq-container .left .question-item .desc {
  padding-left: 12px;
  color: rgba(6, 41, 74, .6)
}

.course-detail.uk.new .uk-fag-container .faq-container i {
  color: #e9ebf0;
  font-size: 32px
}

.course-detail.uk.new .uk-fag-container .faq-container .right {
  box-shadow: 0 2px 12px rgba(0, 0, 0, .06);
  border-top: 8px solid #2dc68f;
  padding: 20px;
  margin-left: 10%;
  height: 600px;
  width: 420px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff
}

.course-detail.uk.new .uk-fag-container .faq-container .right h3 {
  font-size: 24px
}

.course-detail.uk.new .uk-fag-container .faq-container .right .answer-item {
  margin-bottom: 20px
}

.course-detail.uk.new .uk-fag-container .faq-container .right .answer-item .title {
  font-size: 18px;
  color: #2dc68f;
  border-left: 2px solid #2dc68f;
  padding-left: 12px
}

.course-detail.uk.new .uk-fag-container .faq-container .right .answer-item .desc {
  padding-left: 12px;
  color: rgba(6, 41, 74, .6)
}

.course-detail.uk.new .uk-feature-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 5% 12% 0
}

.course-detail.uk.new .uk-feature-container .desc {
  margin-bottom: 3%;
  color: #8795a8
}

.course-detail.uk.new .uk-feature-container .feature-item-container {
  display: flex;
  justify-content: space-between;
  width: 100%
}

.course-detail.uk.new .uk-feature-container .feature-item-container .feature-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 250px
}

.course-detail.uk.new .uk-feature-container .feature-item-container .feature-item img {
  height: 80px;
  width: 80px
}

.course-detail.uk.new .uk-feature-container .feature-item-container .feature-item h4 {
  margin: 5% 0;
  color: #ff6c00
}

.course-detail.uk.new .uk-feature-container .feature-item-container .feature-item .item-desc {
  text-align: center
}

.course-detail.uk.new .uk-feature-container .feature-item-container .feature-item .item-special {
  margin-top: 4%;
  color: #ff6c00
}

</style>

<style scope>

.el-dropdown-menu{
  background-color: white;
}

</style>


