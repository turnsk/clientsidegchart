Client-side GChart is a GWT chart library that supports line, pie,
bar, area, and combination charts, popups, mouse events, and more.
<ul>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/live-demo/v2_7/com.googlecode.gchart.gchartdemoapp.GChartDemoApp/GChartDemoApp.html'>The<br>
live demo</a> has advanced examples to illustrate what's possible.</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/javadoc/com/googlecode/gchart/client/package-summary.html#ChartGallery'>The<br>
Chart Gallery</a> has simpler examples to help get you started.</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/javadoc/com/googlecode/gchart/client/package-summary.html#InstallingGChart'>Installing gchart</a> explains how to plug the GChart library into your application.</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/javadoc/com/googlecode/gchart/client/GChart.html'>The javadocs</a> are so complete, you won't need a<br>
Wiki or a User's Guide</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/javadoc/com/googlecode/gchart/client/doc-files/externalgchartresources.html'>The external resources page</a> has links to applications, tutorials, and blog posts.</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/live-demo/v2_7/com.googlecode.gchart.gcharttestapp.GChartTestApp/GChartTestApp.html'>The<br>
GChart Paint Test</a> contains over 200 charts. Think<br>
of it as bug insurance.</li>
<li><a href='http://clientsidegchart.googlecode.com/svn/trunk/javadoc/com/googlecode/gchart/client/doc-files/releasenotes.html'>The release notes</a> explain the most recent<br>
changes.</li>
</ul><p>

<p>GChart is layered on top of GWT's standard widget set.<br>
Specifically,<br>
<tt>Image</tt> widgets (for curves) and <tt>Grid</tt> widgets (for<br>
aligned text) are placed onto <tt>AbsolutePanels</tt> to render each<br>
chart. Thus,<br>
it works reliably cross-browser, fully exploits GWT's compiler<br>
technology, and does not require proprietary<br>
browser plug-ins, complex external Javascript libraries, or a server<br>
hit each time the chart changes.<p>
<p>

Though this approach has many advantages, high visual quality for<br>
non-rectangular curve types isn't one of them. To fix this, GChart<br>
lets you optionally bolt on an external GWT vector graphics library.<br>
<br>
<p>
<i>Where's the forum?</i> Just use the GChart issue tracker, which doubles as the GChart forum.<br>
<p>

As of version 2.7, GChart releases are signed with the following PGP key:<br>
<p>

<pre><code>-----BEGIN PGP PUBLIC KEY BLOCK-----<br>
Version: GnuPG v1.4.9 (GNU/Linux)<br>
<br>
mQINBEwEHX8BEADmw2om4OHePyIRSCol5416POEIz7j5V7z1K/0ysMyXt0Jt7QYC<br>
Dfk50Uv6/5QXWUtRyy4LCW+1K2SzOnrpBQuTwv5gG99i7BBBuu+pUnmxFMLDtG1y<br>
ntmXj5tCDShuhncfnYXi3YhNDWph0GP5q/+iH605YPVsRGN/goCGJqkb2Mmy8htJ<br>
X5rlMokREqkHu2EFo5XSrdDZ5jo8w4cqgVS/l1mOCGMrZZSit2zIpsvnvZ/LvdT0<br>
EVN25Oj4mccveJ1CzN/kXj046MeygaEEC6gmnMZTmDo4lvabWMSOBVGpF9qSc9ZK<br>
y7jdeVEKIVk4Ss6HniCfTSFiLABYWY9rAKSrY040olBGyoOyr4249nzcvC7Uk1IS<br>
GQt7frBEaZmu+DmiXipAAfASQhSsnzapnLyutgkessjbKHTP6kMgaoCssTO/0jnd<br>
EpB588tFrCHl4SJOcFEzEYeZqns1+DtfsrzLVQNaTKERpWZx4pQNlSKsDHYPjs2j<br>
uLQSdQOGsZSJbjynP1na7x09kn0YX22MXK6RxFg7ZgNG4xuOSW+FwIm8cAQVj9il<br>
CBmu7Xh/2dc2G0TKikk3MUW4bd02BtjLglAhm+vGWuDWMeBxcW+0KNXUUmSamGxR<br>
JTN8lEe/K6hqA4am70DQzQ8Nj1GBCSditUGkV1XCQCRIHc7RckhSggVHJQARAQAB<br>
tFZKb2huIEMuIEd1bnRoZXIgKGZvciBDT0RFIFNJR05JTkcgT05MWSkgPFRoaXNL<br>
ZXlJc05vdFJlbGF0ZWRUb0FuRW1haWxAbm9zdWNoZW1haWwuY29tPokCNgQTAQIA<br>
IAUCTAQdfwIbAwYLCQgHAwIEFQIIAwQWAgMBAh4BAheAAAoJENWr0UrHqSwVlPUQ<br>
ANWpdHHw3Iu+XyUL34O1T2TJYVIW5hDM97zLSesmqccH8YxuBMPZtZmnr9RQ6xgd<br>
zJgkaTyEY+CLFIkBnikQA+1k29FviU2vTk7VrsLuB0YnYEBhWbPzlCBFz2yEYrLH<br>
wVCgd+mv9Kx6z4khQ/jAB0ehIpSq9Waux76+jE6rM55hLfnLbZt8FCjp2HU+YMCP<br>
zRQWj8OpPu/z2wH3x6MNA//SXw0xFDZwoVNSCZ+b9gYU7MRzC0ItaengnlNOHkx6<br>
zn6ejWMbm52ZAGzLGvCz20DBvAa6F3/lZZI9SyMqo1Zso2oWIy1LL8s4k+IJxPM+<br>
9WdTSAR+OGFF4XBElUZGNHxirxv7ddEgUexeqr/ZMeMBknm/6zAeRN3fup94qpbw<br>
klFq/5arL3+5RQXiY4RYFjoYgtY5aVy1mRbQe/0924KT6bqGgXdXe1G0PwhAtC0+<br>
QyUnIMj0uWZ9rcJmY0zaTp6wex9oOPqbQJ8+/H3C3AJEiv1nGlI1y7tNTqF2qjSc<br>
ToDv+h9SLWONSQlksimaPy2KxI5stjRC5nBsRnE7AsEVr8ROknziPknmt0HUgKjz<br>
1UnOTGezgYtXgc8n4jXD6ANWutedTKp/z09iOLp+IiploUSJ1cn5U0HfMCEP8O0Q<br>
pLKGzTgX2nF47Jjc/BDKDKKHGLgB17YOFvVb4SaaLtdK<br>
=yZtx<br>
-----END PGP PUBLIC KEY BLOCK-----<br>
</code></pre>

<p>
I'm told there are people who can read these things like tea leaves.<br>
<p>

- John C. Gunther<br>
