# sticky-header
#add code in your header file 
#and replace your header sticky id(#main-header')
#<b>
#<style>
#.stickyNtier {position: fixed !important;top: 0!important;}
#</style></b>
#<script>
jQuery(window).scroll(function(){
  var sticky = jQuery('#main-header'),
      scroll = jQuery(window).scrollTop();
  if (scroll >= 100) sticky.addClass('stickyNtier');
  else sticky.removeClass('stickyNtier');
});</script>
