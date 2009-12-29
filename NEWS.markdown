### Passerd 0.0.4.2 - 28 Dec 2009

* Updated twitty-twister version. On 0.0.4, I forgot to update the
  twitty-twister git commit reference, and broke twitter posting.


### Passerd 0.0.4.1 - 28 Dec 2009

* Fix a problem on the OAuth access token request method. A POST
  request with no Content-Length may case a 411 Length Required
  error (probably on some proxy servers).
  * Thanks to Bogdano Arendartchuk for the fix.


### Passerd 0.0.4 - 27 Dec 2009

* Ability to follow lists using `#@username/list` channels
* Ability to get updates from a single user using `#@username` channels
* Implement #mentions channel, for mentions of `@username`
* OAuth support! Now you don't need to give your Twitter password to
  Passerd (and you'll get a nice "from Passerd" note on your Twits.  :)
* Optional nickserv-style authentication support
* Better error messages (using a `passerd-bot` IRC user)
* Now with a real (but still a bit ugly) web page at [passerd.raisama.net](http://passerd.raisama.net/)


### Passerd 0.0.3 - 18 Dec 2009

* Ability to send updates to Twitter
* Fetch detailed user info from Twitter on-demand, only if necessary
* Basic command-line option support
* Implement Twitter follow/unfollow as IRCK KICK/INVITE

### Passerd 0.0.2 - 15 Dec 2009

* List Twitter friends as IRC contacts


### Passerd 0.0.1 - 14 Dec 2009

* Basic Twitter reading ability