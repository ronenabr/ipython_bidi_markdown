ipython_bidi_markdown
=====================

Add Right-to-left (RTL) support to Ipython's markdown cells. 
Currently support IPython  1.0 only. 

Using [bidiweb](https://github.com/hasenj/bidiweb) to to add Right-To-Left 
properties to paragraphs that starts with Right-To-Left text (Arabic, Hebrew, Farsi, etc.).






Install
=======

Clone this repo into  `~/.ipython_/profile_xxx/static/` (or `~/.config/ipython_/profile_xxx/static/` )

```bash
git clone https://github.com/ronenabr/ipython_bidi_markdown.git ~/.ipython/profile_default/static/custom
```



Restart your notebook server. You may also need to empty your browser cache.


Thanks 
=======
* [Arieh](https://github.com/arieh), for the javascript support
* Kyle Kelley and Matthias BUSSONNIER for help on the mailing list. See discussion at [IPython's mailing list](http://mail.scipy.org/pipermail/ipython-dev/2013-August/012218.html).
