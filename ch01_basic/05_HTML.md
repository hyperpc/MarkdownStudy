# HTML #

## Font ##

<span style="color:green;font-family:Microsoft Sans Serif;">Green</span><span style="color:#fa0;font-size:20px;font-family:Microsoft YaHei;">Yellow</span><span style="color:red;font-size:30px;font-family:YouYuan;font-weight:bold;">Red</span>

## iframe ##

<iframe height='265' scrolling='yes' title='微软必应' src='https://www.bing.com/' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width:100%;'></iframe>

> the iframe content cannot be exported.

## Image ##

<img src='../img/firefox.png'/>
<img src='../img/firefox.png' style="width:110px;height:55px;"/>
<img src='../img/firefox.png' style="zoom:50%;"/>

## Sound ##

> the nested sound file cannot be exported.

<!--not useful-->
![](../sound/WinNotify.mp3)
![](D:/Workspace/github/MarkdownStudy/sound/WinNotify.mp3)

<audio controls="controls">
  <source type="audio/mp3" src="../sound/WinNotify.mp3"></source>
  <source type="audio/ogg" src="../sound/WinNotify.ogg"></source>
  <p>Your browser does not support the audio element.</p>
</audio>

## Video ##

> the nested video file cannot be exported.

<!--not useful-->
![](D:/Workspace/github/MarkdownStudy/video/SampleVideo_1280x720_5mb.mp4)


[![Loading a video...](../img/firefox.png)](../video/SampleVideo_1280x720_5mb.mp4 "Sample Video")

<a href='../video/SampleVideo_1280x720_5mb.mp4' title='Sample Video'><img src='../img/firefox.png' alt='Loading a video...'/></a>

<p>
<video width='640' height='360' class='audioplayer' controls>
<source type='video/mp4' src='../video/SampleVideo_1280x720_5mb.mp4'></source>
Your browser does not support playing HTML5 video. You can <a href='../video/SampleVideo_1280x720_5mb.mp4'>download</a> a copy of the video file instead.
</video>
</p>