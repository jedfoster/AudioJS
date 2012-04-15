AudioJS
--------
Fork of VideoJS, for audio tags with support for themes.

View demo.html for an example of how to use it.

Based on [VideoJS.com](http://videojs.com) 


Example jQuery plugin:

    if (window.jQuery) {
      (function($) {
        $.fn.AudioJS = function(options) {
          this.each(function() {
            AudioJS.setup(this, options);
          });
          return this;
        };
        $.fn.player = function() {
          return this[0].player;
        };
      })(jQuery);
    }


Audio sample is ["Crookshanks" by Palace Cat](http://palacecat.bandcamp.com/track/crookshanks), via [duplokat](http://duplokat.tumblr.com/post/12695092003/geek-friday-ringtone)