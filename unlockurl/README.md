# 解封禁闻直连网址


<h2>获得一个直连网址的域名</h2>

<ul type=disc>
<li >点<a href="https://github.com/bannedbook/fanqiang/wiki#jwurl">禁闻代理在线-镜像</a>, 然后点“禁闻代理在线-镜像1” ，即可打开一个禁闻代理网址，把这个网址拷贝下来，比如得到网址：https://ya.dnstogo.xyz/ ，然后我们把前面的https:// 和 后面的一个斜杠去掉，就得到了一个域名：ya.dnstogo.xyz</li>

</ul>

<p >&nbsp;</p>

<h2>一、下载和替换proxy.py文件</h2>

<p   >下载(右键点击，另存为即可下载) <a
href="https://raw.githubusercontent.com/kgfw/fg/master/wstp/proxy.py">proxy.py文件</a>，用其覆盖替换Agent文件夹里的同名文件。替换proxy.py文件后，GoAgent将不会自动更新ip了，从此你需要自己定期扫描和更新ip。</p>

<h2>二、GoAgent扫描IP</h2>

<p >你可以直接用Agent文件夹下的gsan目录里的工具即可扫描了，已经内置了可用ip列表大约1.6w ip。</p>

<p >若你有自己有扫描工具，可以下载<a
href="https://raw.githubusercontent.com/kgfw/fg/master/wstp/googleip.txt">
googleip.txt文件</a>，其为为可用谷歌ip的地址列表，大约2w个ip，来源为vpn扫描全部谷歌地址域得到，可靠性有保障，大家可以下载来自己用<a
href="https://code.google.com/archive/p/gogo-tester/">GoGoTest</a>、GScan进行扫描！</p>


<h2>三、将扫描到的可用IP添加到GoAgent的配置文件中</h2>

<p   ><b>1.&nbsp; </b>如果你正在用我分享的<a
href="https://github.com/bannedbook/fanqiang/wiki/Chrome%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">ChromeGo</a>和<a
href="https://github.com/bannedbook/fanqiang/wiki/%E7%81%AB%E7%8B%90firefox%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">FirefoxFQ</a>两个软件，里面有一个<b>Agent</b>文件夹，Agent文件夹内有个<b>proxy.ini</b>文件，这个就是配置文件（<b>注：</b>如果你的系统隐藏了已知文件类型的扩展名，那你需要在文件夹选项里取消这一项，不然可能会看不到.ini扩展名），注意，请不要修改<b>proxy.ini</b>文件。把<b>proxy.ini</b>文件拷贝粘贴成另一个文件，把拷贝的新文件改名为：proxy.user.ini
，然后编辑这个proxy.user.ini文件<b>（最好是用文本编辑器</b><b>EmEditor</b><b>或者</b><b>notepad++</b><b>打开，用记事本有时会出现乱码）</b>，把文件中的[iplist]小节的google_cn
= 、google_hk
= 后面的值替换为你扫描到的可用ip，多个ip用|隔开，比如：202.86.162.148|59.18.46.11|59.18.46.19|59.18.45.41<br>
替换后大概是这个样子：<br>
google_cn = 202.86.162.148|59.18.46.11|59.18.46.19|59.18.45.41|59.18.45.35<br>
google_hk = 202.86.162.148|59.18.46.11|59.18.46.19|59.18.45.41|59.18.45.35</p>

<p   ><b>2.&nbsp;</b>google_cn和google_hk的ip是否需要换成一样的ip？&nbsp;<br>
&nbsp;这个随你便，只要ip未被干扰，是否一样没要求。&nbsp;</p>

<p   ><b>3.&nbsp; </b>上一步确认无误后，点记事本或文本编辑器左上方菜单栏的“<b>文件</b>”，弹出菜单中点“<b>保存</b>”，然后关闭这个proxy.user.ini
的文件窗口。</p>

<p ><b>四、重新启动软件测试是否可以正常使用</b></p>

<p   >打开一个墙外网站看看，能打开一般来说就没问题。</p>

<p ><b>五、反馈交流</b></p>

<p>GoAgent扫描和更新IP的过程到这里基本也就结束了，如果哪一步还有疑问，请点下面的翻墙交流链接发帖交流。</p>
