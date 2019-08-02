# wazo-plugind-voipbl
clone of @sboily -> https://github.com/sboily/wazo-plugind-voipbl-scopserv

Add Actual parameters VOIPBL

Please Add to Crontab :

crontab -e

0 */4 * * * /usr/local/bin/voipbl.sh > /var/log/voipbl.log 2>&1 
