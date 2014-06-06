easyListSplitter
================

jQuery plugin: Easy List Splitter


Features

  Split any ordered (OL) or unordered (UL) list
  Define the number of columns in which you want your lists to be split
  Target more than one list on the same page and set different number of columns for each of them
  CSS is completely separated from the javascript. You can either modify the default one or create your own
  A class “last” will be added to each last UL or OL so that you can easily remove side padding or margin
  NEW: Easy List Splitter Plugin preserves nested lists now!
  NEW: You can now choose whether to order your list items vertically or horizontally
  There is no need to modify your HTML. Just target your list element using any of the JQuery-selectors.
  No dependencies at all!
  Plugin size 4KB!
  
Usage

  $('.my-list').easyListSplitter({ colNumber: 3 });
  
What you have to do is simply specify the direction:’horizontal’ parameter when you call the plugin:
  $('.my-list').easyListSplitter({
     colNumber: 3,
     direction: 'horizontal'
  });
