Styleguide
==========

This guide has two humble goals: 

- Help newbies quickly figure out preferred project style
- Saves time for older peers about talking their brilliant preferred style ;-)


The very first rule
-------------------

The very first rule of all rules: Follow project style guide ;-)


Views
-----

1) Honor css classic style for class names, preferred example:

    %h1.main-menu

Not prefered: main_menu nor mainMenu
Sometimes Rails devs would prefer main_menu, but then you will forever
mix up with designers and other css class names and you just cannot remember
when you were using ruby style or css stlye. Therefore it's better always to honor css
style for html class names.

2) Add js- prefix for classes/id when you use those with javascript, example:
 
    %h1.js-foldable

When following js- prefix style, it's later way easier to figure
out what classes/id's are pure style related and what are javascript related.

