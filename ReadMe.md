# What does this do?
This plugin creates an infinite animation loop with three parameters:  
-animation type (in this case 'opacity')  
-duration of animation  
-duration of interval

## How do I use it?
For each element you want to run the plugin on, give it a class of "intThis":

`<span class="intThis"></span>`  
  
Then create the function call at the very bottom of the code:
  
`$('.intThis').intThis();`  

Check out the [demo](http://jsfiddle.net/ZICKONEZERO/ENqpj/22/).

### Requirements:
jQuery 1.7.2

### Supported Browsers:
Chrome  
Safari  
Firefox  
Opera  
IE 7 - 9