# tweetvps
Service for vps which listens for encypted commands to execute, from your twitter account


## How to use
1. Create twitter account
1. clone
1. run `sudo crontab -e` and insert 
`cd /opt/rebootclient/;
sudo ./rebootclient daemon --user=$twitteruser --expire=3500 --secret=$secretcode --mydomain=$target --period=$seconds`
