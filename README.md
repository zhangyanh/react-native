# react-native
<h1>一、环境配置(以mac系统为例)</h1>
<p>1、大环境：用xcod安装git,然后安装node.js，node自带npm，然后用npm安装watchman等其它所需要的。</p>
<p>2、ios环境：xcode直接用即可。android环境：下载android-sdk并且安装，参考：<a href="http://reactnative.cn/docs/0.23/android-setup.html#content" target="_blank">mac系统下安卓环境配置</a></p>
<h1>二、应用</h1>
<p>项目创建：</p>
<pre>
<code>$ npm install -g react-native-cli(只需安装一次)
    $ react-native init nativePro(创建react-native项目)</code>
</pre>
<p>应用：</p>
<p>运行iOS应用:</p>
<p>1、$ cd nativePro</p>
<p>2､用XCode打开ios/nativePro.xcodeproj并点击Run按钮。</p>
<p>3､使用你喜欢的文本编辑器打开index.ios.js并随便改上几行。xcode界面点运行即可。</p>
<p>运行Android应用:</p>
<p>1、$ cd nativePro（进入项目目录）</p>
<p>2、在android sdk中打开avd安卓模拟系统界面（终端里执行命令：android avd）</p>
<p>3、终端里运行react-native run-android即可看到项目效果</p>
