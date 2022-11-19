const { time } = hamibot.env;//time:刷视频次数
auto.waitFor();
console.show();
console.log("按音量下键终止脚本运行");
threads.start(function(){
events.observeKey();
events.on("key", function(volume_down, event){
  console.hide();
  home();
  engines.stopAllAndToast();
});
});
log("打开快手");
launchApp("快手");
log("等待5S");
sleep(5000); 
click('精选');
console.log("2S后开始刷视频");
sleep(2000);
for(var i=1;i<time;i++) 
{swipe(700,2200,800,200,1000);
var l = Math.floor((Math.random()*5000) + 2000);
  sleep(l);
  console.log("第"+i+"次刷视频");
  console.log("视频停留"+l/1000+"秒钟");
 	if(text("请完成安全验证").exists())
  {
  log("2S后跳过验证");
 	sleep(2000);
  back()
	}
}
log("5S后返回桌面");
sleep(5000);
home();
console.hide();
engines.stopAllAndToast();
