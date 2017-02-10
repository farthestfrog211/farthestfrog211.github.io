# jpopovich07.github.io
<!--
Instructions on How To Use this HTML:
1. The current setup is for a party of three streamers.  I have generically named the channels: user1, user2, and user3.
2. You will need to do a find and replace to substitute in actual channel names.  (i.e.- Find/Replace user1 with farthestfrog211.
3. Once replaced, you can now open this HTML in your browser @ http://farthestfrog211.github.io/Stream_Chat.html
4. Enjoy!!
-->

<!DOCTYPE html>
<html lang="en-US">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Twitch.tv Multiple Streams</title>
  
<style>
body{font-family:Arial;font-size:.9em;background-color:#000;margin:0;padding:0;}
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script type="text/javascript">function FluidVideo(){var e=$("iframe[src^='https://player.twitch.tv'], iframe[src^='https://twitch.tv'], iframe[src^='https://twitch.tv'], object, embed"),t=$("div.autoresize");e.each(function(){$(this).attr("data-aspectRatio",this.height/this.width).removeAttr("height").removeAttr("width")});$(window).resize(function(){var n=t.width();e.each(function(){var e=$(this);e.width(n).height(n*e.attr("data-aspectRatio"))})}).resize()}}</script>
</head>
<body>
<style>     
      .frame{
      float:left;
      margin:10px;
      }
</style>
<div class="frame"><iframe src="https://player.twitch.tv/?quality=source&channel=user1" frameborder="0" scrolling="no" height="500" width="420" auto></iframe></div>
<div class="frame"><iframe src="https://player.twitch.tv/?quality=source&channel=user2" frameborder="0" scrolling="no" height="500" width="420" auto></iframe></div>
<div class="frame"><iframe src="https://player.twitch.tv/?quality=source&channel=user3" frameborder="0" scrolling="no" height="500" width="420" auto></iframe></div>
</div>
<div class="clear"></div>
<div class="wrapper">


<style>     
      .frame{
      float:left;
      margin:10px;
      }
</style>
<div class="frame"><iframe frameborder="0" scrolling="no" id="chat_embed1" src="https://twitch.tv/chat/embed?channel=user1&amp;popout_chat=true" height="500" width="420" auto></iframe></div>
<div class="frame"><iframe frameborder="0" scrolling="no" id="chat_embed2" src="https://twitch.tv/chat/embed?channel=user2&amp;popout_chat=true" height="500" width="420" auto></iframe></div>
<div class="frame"><iframe frameborder="0" scrolling="no" id="chat_embed3" src="https://twitch.tv/chat/embed?channel=user3&amp;popout_chat=true" height="500" width="420" auto></iframe></div>
</div>

</div>
</div>
</div>
</form>
</body>
</html> 
