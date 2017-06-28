
  // jQuery(".special").slide({mainCell:".bd ul",autoPage:true,effect:"left",autoPlay:false,vis:8});
  jQuery(".banner").slide({ titCell:".hd ul", mainCell:".bd ul", effect:"fold",  autoPlay:true, autoPage:true, interTime:6000, trigger:"click" ,delayTime:1000 }); 
  //波浪动画
  $(function () {
    var marqueeScroll = function (id1, id2, id3, timer) {
      var $parent = $("#" + id1);
      var $goal = $("#" + id2);
      var $closegoal = $("#" + id3);
      $closegoal.html($goal.html());
      function Marquee() {
        if (parseInt($parent.scrollLeft()) - $closegoal.width() >= 0) {
          $parent.scrollLeft(parseInt($parent.scrollLeft()) - $goal.width());
        }
        else {
          $parent.scrollLeft($parent.scrollLeft() + 1);
        }
      }

      setInterval(Marquee, timer);
    }
    var marqueeScroll1 = new marqueeScroll("marquee-box", "wave-list-box1", "wave-list-box2", 20);
    var marqueeScroll2 = new marqueeScroll("marquee-box3", "wave-list-box4", "wave-list-box5", 40);
  });

  // nav
  $(".nav ul>li").mouseenter(function(){
    $(this).find('ol').slideDown(400);
    $(this).siblings('li').find('ol').slideUp(400);
    console.log('kk');
  })
   $(".nav ul>li").mouseleave(function(){
    $(this).find('ol').slideUp(400);
  })