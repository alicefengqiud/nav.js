# nav.js
nav
function navText(text){
    $(".nav>ul>li").each(function(){
        var thisText=$(this).children("a").text();
            if(thisText==text){
            $("nav li").removeClass("cur");
            $(this).addClass("cur");
        }
    });
