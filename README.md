## How to resolve libv8/therubyracer issue

$ gem install libv8 -v '3.16.14.3' -- --with-system-v8

$ bundle install
-- see error installing therubyracer --
$ gem uninstall libv8

$ brew install v8

$ gem install therubyracer

$ bundle install
-- see error installing libv8 --
$ gem install libv8 -v '3.16.14.3' -- --with-system-v8


## js 判断是否微信打开页面
<script type="text/javascript">
    $(window).on("load",function(){
        var winHeight = $(window).height();
        function is_weixin() {
            var ua = navigator.userAgent.toLowerCase();
            if (ua.match(/MicroMessenger/i) == "micromessenger") {
                return true;
            } else {
                return false;
            }
        }
        var isWeixin = is_weixin();
        if(isWeixin){
            $(".weixin-tip").css("height",winHeight);
            $(".weixin-tip").show();
        }
    })
</script>
