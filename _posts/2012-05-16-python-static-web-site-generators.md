---
layout: post
title: "Python Static Web Site Generators"
tagline: "Who Needs a Dynamic Web Site with JavaScript"
description: "Who Needs a Dynamic Web Site with JavaScript"
category: python
tags: [python, static web site generator]
---
{% include JB/setup %}
## Python Static Site Generators ##

While git is great and all, on windows it is huge. I wanted to find other ways of actually posting remotely without using git. It would seem that FTP would be obvious, but so far no luck. I might have to find one with a publishing hook and write a python function to upload via ftp.

## Features I Currently Like ##
    - Python rather than Ruby
    - Dropbox syncing although ftp would work just as well for me.
    - YAML post configuration
    - Markdown default with the options of other formats
    - Hookable
    - Jinja2 templating
    - Importing from Wordpress and other blogs
    
## Possible Candidates ##

- [https://github.com/borismus/lightning](https://github.com/borismus/lightning) - uses dropbox for syncing posts
- [https://github.com/piranha/cyrax](https://github.com/borismus/lightning) - Based on jekyll. Uses Jinja2. Markdown, reST or textile.
- [https://github.com/xfire/growl/](https://github.com/xfire/growl/) - Based on jekyll. Is extendable and has hooks. Multiple templating or formatting options.
- [https://github.com/ametaireau/pelican](https://github.com/ametaireau/pelican) - Lots of features. Web hooks and DVCSes
- [https://github.com/Anomareh/mynt](https://github.com/Anomareh/mynt) - Worth looking at again
- [http://www.blogofile.com/](https://github.com/Anomareh/mynt) - Lots of docs. Lots of configuration. I see a post_build hook which may be the oppurtunity for FTP upload or git. Uses Mako. MVC and extendable. YAML post format. Migration from wordpress. Ended development
- [https://github.com/bow/volt/](https://github.com/bow/volt/) - Based on blogofile
- [https://github.com/amirouche/nikola](https://github.com/amirouche/nikola) - Lots of features. Suggests multiple deployment methods including dropbx and ftp.
- jekll plus [https://github.com/teiko/glynn](https://github.com/teiko/glynn) which will upload via ftp
- [http://packages.python.org/Frozen-Flask/](http://packages.python.org/Frozen-Flask/) - Freeze Flask
- [https://github.com/Iodine/lynki](https://github.com/Iodine/lynki) - wiki generator
- [http://wok.mythmon.com/](http://wok.mythmon.com/)
- [https://github.com/honza/socrates](https://github.com/honza/socrates)
- [http://posativ.org/acrylamid/](http://posativ.org/acrylamid/) - Parses a lot of markup syntaxes. Extentable
- [http://pyblosxom.bluesock.org/](http://pyblosxom.bluesock.org/) - Blogging software that can do static
- [https://github.com/nikcub/floyd](https://github.com/nikcub/floyd)
- [https://github.com/colinta/StrangeCase](https://github.com/colinta/StrangeCase) - Lots of docs worth reading
- [https://github.com/lejonet/Cipherpress](https://github.com/lejonet/Cipherpress) - Interesting
- [https://github.com/tylerbutler/engineer](https://github.com/tylerbutler/engineer) - Research
- [https://github.com/galvez/fab-publish](https://github.com/galvez/fab-publish) - Maybe use for remote deployment other than git. Brings up the possibility of using fab, waf or doit along with an ftp python class.
    
## With a GUI ##

- [Thingamablog](http://www.thingamablog.com/)
- [Fire Drop](http://www.voidspace.org.uk/python/firedrop2/)