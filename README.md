Decode-pelican
==============

Port of the [http://scotthsmith.com/projects/decode/](Decode) theme to [http://blog.getpelican.com/](Pelican) blog engine.

This is still work in progress theme. It requires Pelican version 3.0 or greater.

At the moment it does not have a sidebar, tag cloud and lacks social buttons. I have also removed Google Analitics and Disqus integration.
The last two was the conscious choice: I do not think such a secondary features should require JavaScript.

EDIT : Added Disqus comments, Google analytics. Some People do use them, don't use the relevant settings in pelicanconf.py if you do not need them.

I am going to address the sidebar and social buttons issues first.

License: GPL v3

This supports all of these settings (which you would add to the pelicanconf.py file).

```
DISQUS_SITENAME	Pelican can handle disqus comments, specify the sitename you’ve filled in on disqus
```
```
GITHUB_URL	Your github URL (if you have one), it will then use it to create a github ribbon.
```
```
MENUITEMS	A list of tuples (Title, Url) for additional menu items to appear at the beginning of the main menu.
```
```
GOOGLE_ANALYTICS	‘UA-XXXX-YYYY’ to activate google analytics.
```