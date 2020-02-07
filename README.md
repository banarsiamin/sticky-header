# sticky-header
#add code in your header file 
#and replace your header sticky id(#main-header')
#<b>
#<style>
  
#.stickyNtier {position: fixed !important;top: 0!important;}

#</style></b>


#<b><script>
  <br>
jQuery(window).scroll(function(){<br>

  var sticky = jQuery('#main-header'),<br>
  
      scroll = jQuery(window).scrollTop();<br>
      
  if (scroll >= 100) sticky.addClass('stickyNtier');<br>
  
  else sticky.removeClass('stickyNtier');<br>
  
});</script><br>
</b>
