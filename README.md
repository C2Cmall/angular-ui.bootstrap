### zh-CN  机器翻译中文,请参阅下面EN原版理解
<article class="markdown-body entry-content" itemprop="text"><h3><a id="user-content-ui-bootstrap---angularjs-directives-specific-to-bootstrap" class="anchor" href="#ui-bootstrap---angularjs-directives-specific-to-bootstrap" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="UI Bootstrap - " data-dst="用户界面引导—" style="background: transparent;">用户界面引导—</trans><a href="http://angularjs.org/"><trans data-src="AngularJS" data-dst="AngularJS"><trans data-src="AngularJS" data-dst="AngularJS" style="background: transparent;">AngularJS</trans></trans></a><trans data-src=" directives specific to " data-dst="指令的具体">指令的具体</trans><a href="http://getbootstrap.com"><trans data-src="Bootstrap" data-dst="自举">自举</trans></a></h3>

<p><a href="https://gitter.im/angular-ui/bootstrap?utm_source=badge&amp;utm_medium=badge&amp;utm_campaign=pr-badge&amp;utm_content=badge"><img src="https://camo.githubusercontent.com/da2edb525cde1455a622c58c0effc3a90b9a181c/68747470733a2f2f6261646765732e6769747465722e696d2f4a6f696e253230436861742e737667" alt="Gitter" data-canonical-src="https://badges.gitter.im/Join%20Chat.svg" style="max-width:100%;"></a>
<a href="http://travis-ci.org/angular-ui/bootstrap"><img src="https://camo.githubusercontent.com/c9adebb9662c64b3d4129208c7e5514cb0802a4d/68747470733a2f2f7365637572652e7472617669732d63692e6f72672f616e67756c61722d75692f626f6f7473747261702e737667" alt="Build Status" data-canonical-src="https://secure.travis-ci.org/angular-ui/bootstrap.svg" style="max-width:100%;"></a>
<a href="https://david-dm.org/angular-ui/bootstrap#info=devDependencies"><img src="https://camo.githubusercontent.com/fc8d0d8abf735b19162117c3b01cd7be09109a1a/68747470733a2f2f64617669642d646d2e6f72672f616e67756c61722d75692f626f6f7473747261702f6465762d7374617475732e7376673f6272616e63683d6d6173746572" alt="devDependency Status" data-canonical-src="https://david-dm.org/angular-ui/bootstrap/dev-status.svg?branch=master" style="max-width:100%;"></a></p>

<h3><a id="user-content-quick-links" class="anchor" href="#quick-links" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Quick links" data-dst="快速链接">快速链接</trans></h3>

<ul>
<li><a href="#demo"><trans data-src="Demo" data-dst="演示">演示</trans></a></li>
<li><a href="#angular-2"><trans data-src="Angular 2" data-dst="角2">角2</trans></a></li>
<li><a href="#installation"><trans data-src="Installation" data-dst="安装">安装</trans></a>

<ul>
<li><a href="#install-with-npm"><trans data-src="NPM" data-dst="新公共管理">新公共管理</trans></a></li>
<li><a href="#install-with-bower"><trans data-src="Bower" data-dst="鲍尔">鲍尔</trans></a></li>
<li><a href="#install-with-nuget"><trans data-src="NuGet" data-dst="NuGet"><trans data-src="NuGet" data-dst="NuGet">NuGet</trans></trans></a></li>
<li><a href="#custom-build"><trans data-src="Custom" data-dst="自定义">自定义</trans></a></li>
<li><a href="#manual-download"><trans data-src="Manual" data-dst="手动">手动</trans></a></li>
</ul></li>
<li><a href="#webpack"><trans data-src="Webpack" data-dst="WebPACK">WebPACK</trans></a></li>
<li><a href="#support"><trans data-src="Support" data-dst="支持">支持</trans></a>

<ul>
<li><a href="#faq"><trans data-src="FAQ" data-dst="常见问题">常见问题</trans></a></li>
<li><a href="#code-of-conduct"><trans data-src="Code of Conduct" data-dst="行为准则">行为准则</trans></a></li>
<li><a href="#prefix-migration-guide"><trans data-src="PREFIX MIGRATION GUIDE" data-dst="前缀迁移指南">前缀迁移指南</trans></a></li>
<li><a href="#supported-browsers"><trans data-src="Supported browsers" data-dst="支持的浏览器">支持的浏览器</trans></a></li>
<li><a href="#need-help"><trans data-src="Need help?" data-dst="需要帮助">需要帮助</trans></a></li>
<li><a href="#found-a-bug"><trans data-src="Found a bug?" data-dst="发现了一个bug？">发现了一个bug？</trans></a></li>
</ul></li>
<li><a href="#contributing-to-the-project"><trans data-src="Contributing to the project" data-dst="有助于项目">有助于项目</trans></a></li>
<li><a href="#development-meeting-minutes-roadmap-and-more"><trans data-src="Development, meeting minutes, roadmap and more." data-dst="发展，会议纪要，路线图和更多。">发展，会议纪要，路线图和更多。</trans></a></li>
</ul>

<h1><a id="user-content-demo" class="anchor" href="#demo" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Demo" data-dst="演示">演示</trans></h1>

<p><trans data-src="Do you want to see directives in action? Visit " data-dst="你想看到指示行动吗？访问">你想看到指示行动吗？访问</trans><a href="http://angular-ui.github.io/bootstrap/"><trans data-src="http://angular-ui.github.io/bootstrap/" data-dst="http://angular-ui.github.io/bootstrap/"><trans data-src="http://angular-ui.github.io/bootstrap/" data-dst="http://angular-ui.github.io/bootstrap/">http://angular-ui.github.io/bootstrap/</trans></trans></a><trans data-src="!" data-dst="！">！</trans></p>

<h1><a id="user-content-angular-2" class="anchor" href="#angular-2" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Angular 2" data-dst="角2">角2</trans></h1>

<p><trans data-src="Are you interested in Angular 2? We are on our way! Check out " data-dst="你在角2感兴趣吗？我们对我们的方式！退房">你在角2感兴趣吗？我们对我们的方式！退房</trans><a href="https://github.com/ui-bootstrap/core"><trans data-src="ng-bootstrap" data-dst="伍举">伍举</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h1><a id="user-content-installation" class="anchor" href="#installation" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Installation" data-dst="安装">安装</trans></h1>

<p><trans data-src="Installation is easy as UI Bootstrap has minimal dependencies - only the AngularJS and Twitter Bootstrap's CSS are required.
" data-dst="安装简单界面引导具有最小的依赖只有AngularJS和推特Bootstrap的CSS是必需的。">安装简单界面引导具有最小的依赖只有AngularJS和推特Bootstrap的CSS是必需的。</trans><em><trans data-src="Notes:" data-dst="笔记">笔记</trans></em></p>

<ul>
<li><trans data-src="Since version 0.13.0, UI Bootstrap depends on " data-dst="自从版本0.1~3.0，UI引导取决于">自从版本0.1~3.0，UI引导取决于</trans><a href="https://docs.angularjs.org/api/ngAnimate"><trans data-src="ngAnimate" data-dst="nganimate">nganimate</trans></a><trans data-src=" for transitions and animations, such as the accordion, carousel, etc. Include " data-dst="对于过渡和动画，如旋转木马，包括手风琴，等。">对于过渡和动画，如旋转木马，包括手风琴，等。</trans><code><trans data-src="ngAnimate" data-dst="nganimate">nganimate</trans></code><trans data-src=" in the module dependencies for your app in order to enable animation." data-dst="为你的应用程序以使动画模块依赖。">为你的应用程序以使动画模块依赖。</trans></li>
<li><trans data-src="UI Bootstrap depends on " data-dst="UI引导取决于">UI引导取决于</trans><a href="https://docs.angularjs.org/api/ngTouch"><trans data-src="ngTouch" data-dst="ngtouch">ngtouch</trans></a><trans data-src=" for swipe actions. Include " data-dst="对于滑动的动作。包括">对于滑动的动作。包括</trans><code><trans data-src="ngTouch" data-dst="ngtouch">ngtouch</trans></code><trans data-src=" in the module dependencies for your app in order to enable swiping." data-dst="为你的应用程序以使刷卡模块依赖。">为你的应用程序以使刷卡模块依赖。</trans></li>
</ul>

<h2><a id="user-content-angular-requirements" class="anchor" href="#angular-requirements" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Angular Requirements" data-dst="角的要求">角的要求</trans></h2>

<ul>
<li><trans data-src="UI Bootstrap 1.0 and higher " data-dst="UI Bootstrap 1和更高">UI Bootstrap 1和更高</trans><em><trans data-src="requires" data-dst="要求">要求</trans></em><trans data-src=" Angular 1.4.x or higher and it has been tested with Angular 1.4.8." data-dst="角1.4。x或更高，它已与角1.4.8测试。">角1.4。x或更高，它已与角1.4.8测试。</trans></li>
<li><trans data-src="UI Bootstrap 0.14.3 is the " data-dst="引导0.14.3是UI">引导0.14.3是UI</trans><em><trans data-src="last" data-dst="最后的">最后的</trans></em><trans data-src=" version that supports Angular 1.3.x." data-dst="版本支持角1.3。X。">版本支持角1.3。X。</trans></li>
<li><trans data-src="UI Bootstrap 0.12.0 is the " data-dst="引导0.12.0是UI">引导0.12.0是UI</trans><em><trans data-src="last" data-dst="最后的">最后的</trans></em><trans data-src=" version that supports Angular 1.2.x." data-dst="版本支持角1.2。X。">版本支持角1.2。X。</trans></li>
</ul>

<h2><a id="user-content-bootstrap-requirements" class="anchor" href="#bootstrap-requirements" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Bootstrap Requirements" data-dst="引导需求">引导需求</trans></h2>

<ul>
<li><trans data-src="UI Bootstrap requires Bootstrap CSS version 3.x or higher and it has been tested with Bootstrap CSS 3.3.6." data-dst="UI引导需要引导的CSS版本3。x或更高，它已与Bootstrap CSS 3.3.6测试。">UI引导需要引导的CSS版本3。x或更高，它已与Bootstrap CSS 3.3.6测试。</trans></li>
<li><trans data-src="UI Bootstrap 0.8 is the " data-dst="0.8是用户界面引导">0.8是用户界面引导</trans><em><trans data-src="last" data-dst="最后的">最后的</trans></em><trans data-src=" version that supports Bootstrap CSS 2.3.x." data-dst="版本支持Bootstrap CSS 2.3。X。">版本支持Bootstrap CSS 2.3。X。</trans></li>
</ul>

<h4><a id="user-content-install-with-npm" class="anchor" href="#install-with-npm" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Install with NPM" data-dst="安装新公共管理">安装新公共管理</trans></h4>

<div class="highlight highlight-source-shell"><pre><trans data-src="$ npm install angular-ui-bootstrap" data-dst="NPM安装角UI引导美元">NPM安装角UI引导美元</trans></pre></div>

<p><trans data-src="This will install AngularJS and Bootstrap NPM packages." data-dst="这将安装AngularJS和Bootstrap NPM包。">这将安装AngularJS和Bootstrap NPM包。</trans></p>

<h4><a id="user-content-install-with-bower" class="anchor" href="#install-with-bower" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Install with Bower" data-dst="安装凉亭">安装凉亭</trans></h4>

<div class="highlight highlight-source-shell"><pre><trans data-src="$ bower install angular-bootstrap" data-dst="鲍尔美元安装角的引导">鲍尔美元安装角的引导</trans></pre></div>

<p><trans data-src="Note: do not install 'angular-ui-bootstrap'.  A separate repository - " data-dst="注意：不要安装“角UI引导”。一个分离的库—">注意：不要安装“角UI引导”。一个分离的库—</trans><a href="https://github.com/angular-ui/bootstrap-bower"><trans data-src="bootstrap-bower" data-dst="自举的凉亭">自举的凉亭</trans></a><trans data-src=" - hosts the compiled javascript file and bower.json." data-dst="东道主编译JavaScript文件和bower.json。">东道主编译JavaScript文件和bower.json。</trans></p>

<h4><a id="user-content-install-with-nuget" class="anchor" href="#install-with-nuget" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Install with NuGet" data-dst="安装NuGet">安装NuGet</trans></h4>

<p><trans data-src="To install AngularJS UI Bootstrap, run the following command in the Package Manager Console" data-dst="安装AngularJS UI引导，运行下面的软件包管理器控制台命令">安装AngularJS UI引导，运行下面的软件包管理器控制台命令</trans></p>

<div class="highlight highlight-source-shell"><pre><trans data-src="PM" data-dst="颗粒物">颗粒物</trans><span class="pl-k"><trans data-src=">" data-dst=">">&gt;</trans></span><trans data-src=" Install-Package Angular.UI.Bootstrap" data-dst="安装包angular.ui.bootstrap">安装包angular.ui.bootstrap</trans></pre></div>

<h4><a id="user-content-custom-build" class="anchor" href="#custom-build" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Custom build" data-dst="自定义生成">自定义生成</trans></h4>

<p><trans data-src="Head over to " data-dst="头向">头向</trans><a href="http://angular-ui.github.io/bootstrap/"><trans data-src="http://angular-ui.github.io/bootstrap/" data-dst="http://angular-ui.github.io/bootstrap/"><trans data-src="http://angular-ui.github.io/bootstrap/" data-dst="http://angular-ui.github.io/bootstrap/">http://angular-ui.github.io/bootstrap/</trans></trans></a><trans data-src=" and hit the " data-dst="和打">和打</trans><em><trans data-src="Custom build" data-dst="自定义生成">自定义生成</trans></em><trans data-src=" button to create your own custom UI Bootstrap build, just the way you like it." data-dst="按钮来创建您自己的自定义用户界面引导建立，只是你喜欢的方式。">按钮来创建您自己的自定义用户界面引导建立，只是你喜欢的方式。</trans></p>

<h4><a id="user-content-manual-download" class="anchor" href="#manual-download" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Manual download" data-dst="手动下载">手动下载</trans></h4>

<p><trans data-src="After downloading dependencies (or better yet, referencing them from your favorite CDN) you need to download build version of this project. All the files and their purposes are described here:
" data-dst="下载后的依赖（或者更好的是，引用他们从您最喜爱的CDN）你需要下载这个版本的构建。所有的文件，其目的是描述在这里：">下载后的依赖（或者更好的是，引用他们从您最喜爱的CDN）你需要下载这个版本的构建。所有的文件，其目的是描述在这里：</trans><a href="https://github.com/angular-ui/bootstrap/tree/gh-pages#build-files"><trans data-src="https://github.com/angular-ui/bootstrap/tree/gh-pages#build-files" data-dst="http：/ / GitHub。COM /角UI /引导/树/ GH页#构建文件">http：/ / GitHub。COM /角UI /引导/树/ GH页#构建文件</trans></a><trans data-src="
Don't worry, if you are not sure which file to take, opt for " data-dst="别担心，如果你不确定哪个文件，选择">别担心，如果你不确定哪个文件，选择</trans><code><trans data-src="ui-bootstrap-tpls-[version].min.js" data-dst="UI引导企业- [版版]。">UI引导企业- [版版]。</trans></code><trans data-src="." data-dst="。">。</trans></p>

<h3><a id="user-content-adding-dependency-to-your-project" class="anchor" href="#adding-dependency-to-your-project" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Adding dependency to your project" data-dst="添加依赖你的项目">添加依赖你的项目</trans></h3>

<p><trans data-src="When you are done downloading all the dependencies and project files the only remaining part is to add dependencies on the " data-dst="当您完成下载所有依赖关系和项目文件，剩下的部分是在添加依赖关系">当您完成下载所有依赖关系和项目文件，剩下的部分是在添加依赖关系</trans><code><trans data-src="ui.bootstrap" data-dst="ui.bootstrap"><trans data-src="ui.bootstrap" data-dst="ui.bootstrap">ui.bootstrap</trans></trans></code><trans data-src=" AngularJS module:" data-dst="AngularJS模块：">AngularJS模块：</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="myModule" data-dst="mymodule">mymodule</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=", [" data-dst="，[">，[</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="ui.bootstrap" data-dst="ui.bootstrap">ui.bootstrap</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src="]);" data-dst="]）；">]）；</trans></pre></div>

<h1><a id="user-content-webpack--jspm" class="anchor" href="#webpack--jspm" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Webpack / JSPM" data-dst="jspm WebPACK /">jspm WebPACK /</trans></h1>

<p><trans data-src="To use this project with webpack, follow the " data-dst="使用该项目遵循WebPACK，">使用该项目遵循WebPACK，</trans><a href="#install-with-npm"><trans data-src="NPM" data-dst="新公共管理">新公共管理</trans></a><trans data-src=" instructions.
Now, if you want to use only the accordion, you can do:" data-dst="
指令。现在，如果你想使用的手风琴，你可以：">
指令。现在，如果你想使用的手风琴，你可以：</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="import" data-dst="进口">进口</trans></span> <span class="pl-smi"><trans data-src="accordion" data-dst="手风琴">手风琴</trans></span> <span class="pl-k"><trans data-src="from" data-dst="从">从</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="angular-ui-bootstrap/src/accordion" data-dst="角UI引导/ SRC /手风琴">角UI引导/ SRC /手风琴</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=";

" data-dst="；">；</trans><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="myModule" data-dst="mymodule">mymodule</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=", [accordion]);" data-dst="[手风琴]）；">[手风琴]）；</trans></pre></div>

<p><trans data-src="You can import all the pieces you need in the same way:" data-dst="你可以导入所有的作品以同样的方式，你需要：">你可以导入所有的作品以同样的方式，你需要：</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="import" data-dst="进口">进口</trans></span> <span class="pl-smi"><trans data-src="accordion" data-dst="手风琴">手风琴</trans></span> <span class="pl-k"><trans data-src="from" data-dst="从">从</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="angular-ui-bootstrap/src/accordion" data-dst="角UI引导/ SRC /手风琴">角UI引导/ SRC /手风琴</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=";
" data-dst="；">；</trans><span class="pl-k"><trans data-src="import" data-dst="进口">进口</trans></span> <span class="pl-smi"><trans data-src="datepicker" data-dst="DatePicker">DatePicker</trans></span> <span class="pl-k"><trans data-src="from" data-dst="从">从</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="angular-ui-bootstrap/src/datepicker" data-dst="角UI引导/ SRC / DatePicker">角UI引导/ SRC / DatePicker</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=";

" data-dst="；">；</trans><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="myModule" data-dst="mymodule">mymodule</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=", [accordion, datepicker]);" data-dst="accordion DataPicker的[，]）；">accordion DataPicker的[，]）；</trans></pre></div>

<p><trans data-src="This will load all the dependencies (if any) and also the templates (if any)." data-dst="这将加载所有的依赖关系（如果有）和模板（如果有）。">这将加载所有的依赖关系（如果有）和模板（如果有）。</trans></p>

<p><trans data-src="Be sure to have a loader able to process " data-dst="一定要有一个程序能够处理">一定要有一个程序能够处理</trans><code><trans data-src="css" data-dst="CSS"><trans data-src="CSS" data-dst="CSS">CSS</trans></trans></code><trans data-src=" files like " data-dst="文件一样">文件一样</trans><code><trans data-src="css-loader" data-dst="CSS的装载机">CSS的装载机</trans></code><trans data-src="." data-dst="。">。</trans></p>

<p><trans data-src="If you would prefer not to load your css through your JavaScript file loader/bundler, you can choose to import the " data-dst="如果你不想通过你的JavaScript文件装载机/捆扎机负载你的CSS，你可以选择进口的">如果你不想通过你的JavaScript文件装载机/捆扎机负载你的CSS，你可以选择进口的</trans><code><trans data-src="index-nocss.js" data-dst="index-nocss.js"><trans data-src="index-nocss.js" data-dst="index-nocss.js">index-nocss.js</trans></trans></code><trans data-src=" file instead, which is available for the modules:" data-dst="文件，以供模块：">文件，以供模块：</trans></p>

<ul>
<li><trans data-src="carousel" data-dst="旋转木马">旋转木马</trans></li>
<li><trans data-src="datepicker" data-dst="DatePicker">DatePicker</trans></li>
<li><trans data-src="datepickerPopup" data-dst="datepickerpopup">datepickerpopup</trans></li>
<li><trans data-src="dropdown" data-dst="下拉">下拉</trans></li>
<li><trans data-src="popover" data-dst="弹出">弹出</trans></li>
<li><trans data-src="position" data-dst="位置">位置</trans></li>
<li><trans data-src="timepicker" data-dst="时间选择">时间选择</trans></li>
<li><trans data-src="tooltip" data-dst="工具提示">工具提示</trans></li>
<li><trans data-src="typeahead" data-dst="typeahead"><trans data-src="typeahead" data-dst="typeahead">typeahead</trans></trans></li>
</ul>

<p><trans data-src="The other modules, such as " data-dst="其他模块，如">其他模块，如</trans><code><trans data-src="accordion" data-dst="手风琴">手风琴</trans></code><trans data-src=" in the example below, do not have CSS resources to load, so you should continue to import them as normal:" data-dst="在下面的例子中，没有CSS资源加载，所以你应该继续他们的正常进口：">在下面的例子中，没有CSS资源加载，所以你应该继续他们的正常进口：</trans></p>

<div class="highlight highlight-source-js"><pre><span class="pl-k"><trans data-src="import" data-dst="进口">进口</trans></span> <span class="pl-smi"><trans data-src="accordion" data-dst="手风琴">手风琴</trans></span> <span class="pl-k"><trans data-src="from" data-dst="从">从</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="angular-ui-bootstrap/src/accordion" data-dst="角UI引导/ SRC /手风琴">角UI引导/ SRC /手风琴</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=";
" data-dst="；">；</trans><span class="pl-k"><trans data-src="import" data-dst="进口">进口</trans></span> <span class="pl-smi"><trans data-src="typeahead" data-dst="typeahead"><trans data-src="typeahead" data-dst="typeahead">typeahead</trans></trans></span> <span class="pl-k"><trans data-src="from" data-dst="从">从</trans></span> <span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="angular-ui-bootstrap/src/typeahead/index-nocss.js" data-dst="角UI引导/ SRC / typeahead / index-nocss.js">角UI引导/ SRC / typeahead / index-nocss.js</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=";

" data-dst="；">；</trans><span class="pl-smi"><trans data-src="angular" data-dst="角">角</trans></span><trans data-src="." data-dst="。">。</trans><span class="pl-en"><trans data-src="module" data-dst="模块">模块</trans></span><trans data-src="(" data-dst="（">（</trans><span class="pl-s"><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span><trans data-src="myModule" data-dst="mymodule">mymodule</trans><span class="pl-pds"><trans data-src="'" data-dst="'"><trans data-src="'" data-dst="&amp;#39;">&amp;#39;</trans></trans></span></span><trans data-src=", [accordion, datepicker]);" data-dst="accordion DataPicker的[，]）；">accordion DataPicker的[，]）；</trans></pre></div>

<h1><a id="user-content-support" class="anchor" href="#support" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Support" data-dst="支持">支持</trans></h1>

<h2><a id="user-content-faq" class="anchor" href="#faq" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="FAQ" data-dst="常见问题">常见问题</trans></h2>

<p><a href="https://github.com/angular-ui/bootstrap/wiki/FAQ"><trans data-src="https://github.com/angular-ui/bootstrap/wiki/FAQ" data-dst="https://github.com/angular-ui/bootstrap/wiki/faq">https://github.com/angular-ui/bootstrap/wiki/faq</trans></a></p>

<h1><a id="user-content-code-of-conduct" class="anchor" href="#code-of-conduct" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Code of Conduct" data-dst="行为准则">行为准则</trans></h1>

<p><trans data-src="Take a moment to read our " data-dst="花一点时间来阅读我们的">花一点时间来阅读我们的</trans><a href="/2947721120/bootstrap-1/blob/master/CODE_OF_CONDUCT.md"><trans data-src="Code of Conduct" data-dst="行为准则">行为准则</trans></a></p>

<h2><a id="user-content-prefix-migration-guide" class="anchor" href="#prefix-migration-guide" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="PREFIX MIGRATION GUIDE" data-dst="前缀迁移指南">前缀迁移指南</trans></h2>

<p><trans data-src="If you're updating your application to use prefixes, please check the " data-dst="如果你更新你的应用程序使用的前缀，请检查">如果你更新你的应用程序使用的前缀，请检查</trans><a href="https://github.com/angular-ui/bootstrap/wiki/Migration-guide-for-prefixes"><trans data-src="migration guide" data-dst="迁移指南">迁移指南</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h2><a id="user-content-supported-browsers" class="anchor" href="#supported-browsers" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Supported browsers" data-dst="支持的浏览器">支持的浏览器</trans></h2>

<p><trans data-src="Directives from this repository are automatically tested with the following browsers:" data-dst="指令从这个库自动测试以下浏览器：">指令从这个库自动测试以下浏览器：</trans></p>

<ul>
<li><trans data-src="Chrome (stable and canary channel)" data-dst="铬（稳定和金丝雀）">铬（稳定和金丝雀）</trans></li>
<li><trans data-src="Firefox" data-dst="火狐">火狐</trans></li>
<li><trans data-src="IE 9 and 10" data-dst="在9和10">在9和10</trans></li>
<li><trans data-src="Opera" data-dst="歌剧">歌剧</trans></li>
<li><trans data-src="Safari" data-dst="Safari"><trans data-src="Safari" data-dst="Safari">Safari</trans></trans></li>
</ul>

<p><trans data-src="Modern mobile browsers should work without problems." data-dst="现代移动浏览器应该没有问题。">现代移动浏览器应该没有问题。</trans></p>

<h2><a id="user-content-need-help" class="anchor" href="#need-help" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Need help?" data-dst="需要帮助">需要帮助</trans></h2>

<p><trans data-src="Need help using UI Bootstrap?" data-dst="需要帮助的使用界面引导？">需要帮助的使用界面引导？</trans></p>

<ul>
<li><trans data-src="Live help in the IRC (" data-dst="生活帮在IRC（">生活帮在IRC（</trans><code><trans data-src="#angularjs" data-dst="# angularjs"># angularjs</trans></code><trans data-src=" channel at the " data-dst="在频道">在频道</trans><code><trans data-src="freenode" data-dst="其中">其中</trans></code><trans data-src=" network). Use this " data-dst="网络）。使用本">网络）。使用本</trans><a href="https://webchat.freenode.net/"><trans data-src="webchat" data-dst="聊天">聊天</trans></a><trans data-src=" or your own IRC client." data-dst="或你自己的IRC客户端。">或你自己的IRC客户端。</trans></li>
<li><trans data-src="Ask a question in " data-dst="问一个问题">问一个问题</trans><a href="http://stackoverflow.com/"><trans data-src="StackOverflow" data-dst="计算器">计算器</trans></a><trans data-src=" under the " data-dst="下">下</trans><a href="http://stackoverflow.com/questions/tagged/angular-ui-bootstrap"><trans data-src="angular-ui-bootstrap" data-dst="角的界面引导">角的界面引导</trans></a><trans data-src=" tag." data-dst="标签">标签</trans></li>
</ul>

<p><strong><trans data-src="Please do not create new issues in this repository to ask questions about using UI Bootstrap" data-dst="请不要在这个库中创建新的问题来问关于使用UI的引导问题">请不要在这个库中创建新的问题来问关于使用UI的引导问题</trans></strong></p>

<h2><a id="user-content-found-a-bug" class="anchor" href="#found-a-bug" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Found a bug?" data-dst="发现了一个bug？">发现了一个bug？</trans></h2>

<p><trans data-src="Please take a look at " data-dst="请看一看">请看一看</trans><a href="/2947721120/bootstrap-1/blob/master/CONTRIBUTING.md#you-think-youve-found-a-bug"><trans data-src="CONTRIBUTING.md" data-dst="contributing.md">contributing.md</trans></a><trans data-src=" and submit your issue " data-dst="提交您的问题">提交您的问题</trans><a href="https://github.com/angular-ui/bootstrap/issues/new"><trans data-src="here" data-dst="在这里">在这里</trans></a><trans data-src="." data-dst="。">。</trans></p>

<hr>

<h1><a id="user-content-contributing-to-the-project" class="anchor" href="#contributing-to-the-project" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Contributing to the project" data-dst="有助于项目">有助于项目</trans></h1>

<p><trans data-src="We are always looking for the quality contributions! Please check the " data-dst="我们一直在寻找质量的贡献！请检查">我们一直在寻找质量的贡献！请检查</trans><a href="/2947721120/bootstrap-1/blob/master/CONTRIBUTING.md"><trans data-src="CONTRIBUTING.md" data-dst="contributing.md">contributing.md</trans></a><trans data-src=" for the contribution guidelines." data-dst="的贡献的准则。">的贡献的准则。</trans></p>

<h1><a id="user-content-development-meeting-minutes-roadmap-and-more" class="anchor" href="#development-meeting-minutes-roadmap-and-more" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Development, meeting minutes, roadmap and more." data-dst="发展，会议纪要，路线图和更多。">发展，会议纪要，路线图和更多。</trans></h1>

<p><trans data-src="Head over to the " data-dst="去">去</trans><a href="https://github.com/angular-ui/bootstrap/wiki"><trans data-src="Wiki" data-dst="维基">维基</trans></a><trans data-src=" for notes on development for UI Bootstrap, meeting minutes from the UI Bootstrap team, roadmap plans, project philosophy and more." data-dst="笔记在UI引导发展，会议纪要从UI引导团队，路线图计划，工程哲学和更多。">笔记在UI引导发展，会议纪要从UI引导团队，路线图计划，工程哲学和更多。</trans></p>
</article>
### EN
### UI Bootstrap - [AngularJS](http://angularjs.org/) directives specific to [Bootstrap](http://getbootstrap.com)

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/angular-ui/bootstrap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://secure.travis-ci.org/angular-ui/bootstrap.svg)](http://travis-ci.org/angular-ui/bootstrap)
[![devDependency Status](https://david-dm.org/angular-ui/bootstrap/dev-status.svg?branch=master)](https://david-dm.org/angular-ui/bootstrap#info=devDependencies)

### Quick links
- [Demo](#demo)
- [Angular 2](#angular-2)
- [Installation](#installation)
    - [NPM](#install-with-npm)
    - [Bower](#install-with-bower)
    - [NuGet](#install-with-nuget)
    - [Custom](#custom-build)
    - [Manual](#manual-download)
- [Webpack](#webpack)
- [Support](#support)
    - [FAQ](#faq)
    - [Code of Conduct](#code-of-conduct)
    - [PREFIX MIGRATION GUIDE](#prefix-migration-guide)
    - [Supported browsers](#supported-browsers)
    - [Need help?](#need-help)
    - [Found a bug?](#found-a-bug)
- [Contributing to the project](#contributing-to-the-project)
- [Development, meeting minutes, roadmap and more.](#development-meeting-minutes-roadmap-and-more)


# Demo

Do you want to see directives in action? Visit http://angular-ui.github.io/bootstrap/!

# Angular 2

Are you interested in Angular 2? We are on our way! Check out [ng-bootstrap](https://github.com/ui-bootstrap/core).

# Installation

Installation is easy as UI Bootstrap has minimal dependencies - only the AngularJS and Twitter Bootstrap's CSS are required.
*Notes:*
* Since version 0.13.0, UI Bootstrap depends on [ngAnimate](https://docs.angularjs.org/api/ngAnimate) for transitions and animations, such as the accordion, carousel, etc. Include `ngAnimate` in the module dependencies for your app in order to enable animation.
* UI Bootstrap depends on [ngTouch](https://docs.angularjs.org/api/ngTouch) for swipe actions. Include `ngTouch` in the module dependencies for your app in order to enable swiping.

## Angular Requirements
* UI Bootstrap 1.0 and higher _requires_ Angular 1.4.x or higher and it has been tested with Angular 1.4.8.
* UI Bootstrap 0.14.3 is the _last_ version that supports Angular 1.3.x.
* UI Bootstrap 0.12.0 is the _last_ version that supports Angular 1.2.x.

## Bootstrap Requirements
* UI Bootstrap requires Bootstrap CSS version 3.x or higher and it has been tested with Bootstrap CSS 3.3.6.
* UI Bootstrap 0.8 is the _last_ version that supports Bootstrap CSS 2.3.x.

#### Install with NPM

```sh
$ npm install angular-ui-bootstrap
```

This will install AngularJS and Bootstrap NPM packages.

#### Install with Bower
```sh
$ bower install angular-bootstrap
```

Note: do not install 'angular-ui-bootstrap'.  A separate repository - [bootstrap-bower](https://github.com/angular-ui/bootstrap-bower) - hosts the compiled javascript file and bower.json.

#### Install with NuGet
To install AngularJS UI Bootstrap, run the following command in the Package Manager Console

```sh
PM> Install-Package Angular.UI.Bootstrap
```

#### Custom build

Head over to http://angular-ui.github.io/bootstrap/ and hit the *Custom build* button to create your own custom UI Bootstrap build, just the way you like it.

#### Manual download

After downloading dependencies (or better yet, referencing them from your favorite CDN) you need to download build version of this project. All the files and their purposes are described here:
https://github.com/angular-ui/bootstrap/tree/gh-pages#build-files
Don't worry, if you are not sure which file to take, opt for `ui-bootstrap-tpls-[version].min.js`.

### Adding dependency to your project

When you are done downloading all the dependencies and project files the only remaining part is to add dependencies on the `ui.bootstrap` AngularJS module:

```js
angular.module('myModule', ['ui.bootstrap']);
```

# Webpack / JSPM

To use this project with webpack, follow the [NPM](#install-with-npm) instructions.
Now, if you want to use only the accordion, you can do:

```js
import accordion from 'angular-ui-bootstrap/src/accordion';

angular.module('myModule', [accordion]);
```

You can import all the pieces you need in the same way:

```js
import accordion from 'angular-ui-bootstrap/src/accordion';
import datepicker from 'angular-ui-bootstrap/src/datepicker';

angular.module('myModule', [accordion, datepicker]);
```

This will load all the dependencies (if any) and also the templates (if any).

Be sure to have a loader able to process `css` files like `css-loader`.

If you would prefer not to load your css through your JavaScript file loader/bundler, you can choose to import the `index-nocss.js` file instead, which is available for the modules:
* carousel
* datepicker
* datepickerPopup
* dropdown
* popover
* position
* timepicker
* tooltip
* typeahead

The other modules, such as `accordion` in the example below, do not have CSS resources to load, so you should continue to import them as normal:

```js
import accordion from 'angular-ui-bootstrap/src/accordion';
import typeahead from 'angular-ui-bootstrap/src/typeahead/index-nocss.js';

angular.module('myModule', [accordion, datepicker]);
```

# Support

## FAQ

https://github.com/angular-ui/bootstrap/wiki/FAQ

# Code of Conduct

Take a moment to read our [Code of Conduct](CODE_OF_CONDUCT.md)

## PREFIX MIGRATION GUIDE

If you're updating your application to use prefixes, please check the [migration guide](https://github.com/angular-ui/bootstrap/wiki/Migration-guide-for-prefixes).

## Supported browsers

Directives from this repository are automatically tested with the following browsers:
* Chrome (stable and canary channel)
* Firefox
* IE 9 and 10
* Opera
* Safari

Modern mobile browsers should work without problems.

## Need help?
Need help using UI Bootstrap?

* Live help in the IRC (`#angularjs` channel at the `freenode` network). Use this [webchat](https://webchat.freenode.net/) or your own IRC client.
* Ask a question in [StackOverflow](http://stackoverflow.com/) under the [angular-ui-bootstrap](http://stackoverflow.com/questions/tagged/angular-ui-bootstrap) tag.

**Please do not create new issues in this repository to ask questions about using UI Bootstrap**

## Found a bug?
Please take a look at [CONTRIBUTING.md](CONTRIBUTING.md#you-think-youve-found-a-bug) and submit your issue [here](https://github.com/angular-ui/bootstrap/issues/new).


----


# Contributing to the project

We are always looking for the quality contributions! Please check the [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution guidelines.

# Development, meeting minutes, roadmap and more.

Head over to the [Wiki](https://github.com/angular-ui/bootstrap/wiki) for notes on development for UI Bootstrap, meeting minutes from the UI Bootstrap team, roadmap plans, project philosophy and more.
