fail2ban-geo
========================
Block any IP who does not match the country code pattern

- Define your own pattern in jail.conf
- Extra logging: ip, country code and iptable command


To install linux
========================

- Install fail2ban and geoip like:
    $ apt-get install fail2ban
    $ apt-get install geoip-database
