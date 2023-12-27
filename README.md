# Node16-Source
Open Source Old ROBLOX Revival (also includes kewl clients and launcher source)
Once a revival, now a dead one.

uhhh, use this source at your free will.
you can localhost this with xampp or wamp. a simple php revival
please **do not use this as your revival source like goodblox. this is may be insecure as fuck.**

## Requirements
 - Minimum of 1GB of ram for the gameserver and the webserver.
 - Have cPanel on your webserver.
Juan recommends https://ifastnet.com for hosting as it supports asp.net and PHP.
## How to setup our shitty revival
You need these things:
 - A PHP 7x-8x supported hoster
 - MySQL support
 - A brain of  a non-skidder
 - Windows for the client (or just use wine for linux)
 - A hosting provider (localhost or public domain)
 - .ashx/.aspx support (if you don't have this, just import the files of the non-asp.net mix version)
 - And the source (duh)
 
Extract all your files in WinRAR (windows zip is good but combos the Game and game folder together :\)
Then import the website source contents to the site's source code part (/htdocs for self hosters, /public_html for ifastnet users).
Then create a user named nodexyz_dbadmin and with the password phpadmin123lulz (bad password ik). Then create a db named nodexyz_db. Or just change the connection code to your liking.
In nodexyz_db, import the SQL code given.

Volia! Your site is done! It's that easy :D!!!!!! Just create an account with the admin key (it's in the other read me file) and your good to go.

## oH sImPlE, wHaT aBoUt ClIeNtS
Just extract the clients like you downloaded it from https://node16.xyz and run the local launcher (the hacky one). Should install the URI and client data, and you're ready to go. 

If you want to host the site with the clients (dumbass skid), go to HxD and replace the launcher domain(not the hacky one with the cmd shit) to your site. (do Ctrl+R and the first prompt, do node16.xyz, the second prompt do your website (eg. mysite.kewl) and click on Replace All). The launcher is patched, save it.

Create two subdomains, api and setup. In setup, extract the api contents (in extras) and put it in the api subdomain source. Same thing for setup.

Then run the Cleaner if you ran the local launcher (the hacky one) then run the site launcher, if not just run the site launcher.

#### hOw Do I uPdAtE "mY" cLiEnT?!?!?! 
Get your cool new patched client, put it in setup, and change the version text to your version number (eg. version-6sg7w9eb) idfk.
