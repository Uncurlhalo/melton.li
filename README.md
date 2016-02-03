# melton.li
This is the HTML/CSS source for my personal website, as well as the server configs for it. Additionally I've included configs and scripts that I use for the 2 small utility pages I run on my domain (ntopng and vnstat). This README outlines the required software needed to duplicate my website running at htpp://melton.li or http://uncurlhalo.in

## Future Plans
* I plan on adding a Let's Encrypt cert to my actual site, so I'll likely add configuration info about that here as well.
* Adding additional web utilities or monitoring.
* I might eventually transform this into an ansible playbook to make it possible for me to automatically redeploy my website wherever and whenever I want.
* I may also add my mail configuration stuff here as well since thats something else I'd want to have easily reporoducable if I ever migrate hosting.

## Requirements
### Vnstat
vnstat, vnstati, cron, bash

### ntopng
(TODO): Need to setup on my actual server to see how it goes then add configs and info here

### Webserver
nginx, fastcgi

## Deployment
(TODO): Actually give detailed instructions on where to place the config files
At the moment you just have to place all the files in the right places manually, if you know how nginx works then you can figure out what to do on your own from the configs. Also you might have to change the user in nginx.conf to match the default on your distrobution.
