$(document).ready (function () {
   var scroll_start = 0;
   var startchange = $('#startchange');
   var offset = startchange.offset();
    if (startchange.length){
 $(window).scroll (function () {
    scroll_start = $(this).scrollTop();
        if (scroll_start > offset.top)  {
            $('.navbar-inverse').addClass('navbar-color')
            $('.hide-this').addClass('hidden')
            $('.show-this').removeClass('hidden')
        }else {
            $('.navbar-inverse').removeClass('navbar-color')
            $('.hide-this').removeClass('hidden')
            $('.show-this').addClass('hidden')
        }
  });
  }
})


