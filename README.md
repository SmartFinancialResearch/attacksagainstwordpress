# Attacks Against Wordpress

A list of attempted attacks against wordpress sites (from server logs).

Check the requests text files for requests that attempted hackers make against WP sites. 

Some of the requests are blocked by WAFs because of being malicious, while others are blocked because of the IPs that sent the requests.

If you have a WordPress site, you should check through traffic logs and see if there are any requests similar to these. Obviously, some things can be legitimate, like wp-login.php, but they can also be misused by bad people. Additionally, some of these requests are always bad. 

These attempted attacks don't even apply to every WP site they attempt to hack. They sometimes make requests to assets that don't even exist on a server. But what they're doing is finding WordPress or WordPress plugin vulnerabilities and then testing lots of WP sites to find ones with the vulnerable software.

I've even seen some bots that attempt Joomla exploits... against Wordpress servers. I guess they just cast a wide enough net that they don't care if many of their attempts fail. You think they'd at least check if the CMS they have an exploit for is even installed on a web server, but I guess not.

By sharing this information, I hope to help others more aware of current attacks made against WordPress sites... and other CMSs, I guess.

