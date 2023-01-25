# sophos-speedtest
Make a speedtest with sophos XG Firewall using the CLI

You can use this script to run a remote speedtest using speedtest.net CLI on a SOPHOS XG Firewall

Connect to your sophos XG using SSH 

Choose option 5 "DEVICE MANAGEMENT" after choose option 3 " Advanced shell" 

and run this command " curl -s https://raw.githubusercontent.com/WAN4YOU/sophos-speedtest/main/speedtest.py | python3 - "
