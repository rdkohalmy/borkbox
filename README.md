# My Website build for HTL&S (My family's business)

#### This is all built off Docker and Docker-Compose hosted at my home on an R.Pi 4.

For simplicty in my mind and helping trouble shoot what may be going wrong I put everything in it's own Docker-Compose file. A lot of this is pulled from other sources that will be cited on this README eventually.

## What's inside

### Portainer
Portianer is great for looking at logs, getting my hands inside the docker container and orginization. You can use it for templates that I will likely try in the future. For now I really just use it for the logs.

### Traefik
It's a love hate thing. Traefik makes things very simple but it has drivien me crazy. Every time I feel like I understand it they change it. Oh well. It's great and I like using it. I use it with CloudFlare and that helps because I do not need to worry about using Lets Encrypt.

### Caddy
Caddy may replace Traefik but unlikely.

### Wordpress - Mariadb - Redis?

Wordpress is going to be the CMS for the site.

Mariadb because MySQL doesn't work on arm yet for Docker.

Redis (maybe) for site chacing.

## More to come

Eventually there will be more and I will hopefully update this as that happens. I would really like to get Bitwarden up and running maybey LDAP (I tink that's what it's called, look up JumpCloud) set up but unlikely.
