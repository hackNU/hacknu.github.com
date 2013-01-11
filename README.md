# HackNU
This is HackNU's main website.


## Usage
Of course, you should be familiar with how Jekyll-Bootstrap works.

### Creating a new hack night
Creating a new hack night is a simple process, simply go to the root directory of the project and enter:
```
$ rake post category='hack-night' title='Hack Night qyyyy-n' date='yyyy-mm-dd' link='[url to facebook event]'
```
This new "event" (it's really a post) will then be automagically be updated to the hack-nights page and, if the date hasn't passed yet, the front page.


## Notes
- I modified rakefile so that it accepts additional and custom arguments to create the new hack-night posts

--

[Built with Jekyll-Bootstrap](http://jekyllbootstrap.com/)
