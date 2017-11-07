# jQuery.scroll
jQuery扩展scroll时间，监听滚动 停止事件

eg: 

(function(){
    jQuery(window).bind('scrollstart', function(){
        console.log("start");
    });
 
    jQuery(window).bind('scrollstop', function(e){
        console.log("end");
    });
 
})();
