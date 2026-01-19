# better-ping
My own customized version of the ping command included with iputils.

This script will ping the supplied IP address and echo the results in your command-line interface. The script is written in bash, but can be refactored rather easily - as necessary.

This script also assumes you keep your ping logs under $HOME/logs/ping/lesser-pings. Adjust the code to fit your use-case. If you want to use the default convention, then create the necessary directories and off you go!

Personally, I set up an alias to run the script whenever I need to. I use 'pg' as my shorthand, do as you wish.

Syntax (no alias):
./path/to/script IP

Syntax (alias):
pg IP
