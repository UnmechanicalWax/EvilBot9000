# EvilBot9000
Kicks certain users from certain rooms to certain rooms in a certain slack page

1. Upload to a callback server of your choice
2. Create inconspicuout bot account in Slack
3. Add inconspicuous bot to slack channels
4. Get OAuth Token with channels:manage  groups:write  im:write  mpim:write privileges
5. On the callback server open port 5000
6. Run these commands on the callback server:

$ export SLACK_BOT_TOKEN=[the OAuth token]
$ export FLASK_APP=EvilBot9000.py
$ flask run host=0.0.0.0 &

7. Set callback server in the inconspicuous bot account in slack to [your server]:5000/handleevent
8. Have some lulz at the expense of others
