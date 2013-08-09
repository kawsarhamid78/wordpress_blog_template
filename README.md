Wordpress Blog Templates
===========================
I have 2 web repositories to store my wordpress blogs:

> [http://williamjxj.com](http://williamjxj.com)

> [http://williamjxj.wordpress.com/](http://williamjxj.wordpress.com/)

Sometimes I am boring to post the same content twice, especially when the content is longer.
Login to admin panel -> post new -> submit, not quite efficient.

Solution
--------

I plan to use 3 steps to make it more automatic in my spare-time:

1. use templates (Here I use Dreamweaver's .lbi and .tpl template).
By put the templates in github, I can git clone or git pull anywhere whenever I want to write something.

2. write perl script to directly interact wordpress database instead of screen, which cover tag, publish date, category etc.

3. everytime when post, keep a copy in a mongo-based repository for integrate with other apps, since wordpress is hard to interact with others. 

Probably Gist can be used to do some storages.
