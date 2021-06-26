# spiderfoot-cli

```shell
┌──(root💀kali)-[/home/kali]
└─# spiderfoot-cli --help                                                                                                     130 ⨯
usage: sfcli.py [-h] [-d] [-s URL] [-u USER] [-p PASS] [-P PASSFILE] [-e FILE] [-l FILE] [-n] [-o FILE] [-q] [-k] [-b]

SpiderFoot: Open Source Intelligence Automation.

optional arguments:
  -h, --help   show this help message and exit
  -d, --debug  Enable debug output.
  -s URL       Connect to SpiderFoot server on URL. By default, a connection to http://127.0.0.1:5001 will be attempted.
  -u USER      Username to authenticate to SpiderFoot server.
  -p PASS      Password to authenticate to SpiderFoot server. Consider using -P PASSFILE instead so that your password isn't
               visible in your shell history or in process lists!
  -P PASSFILE  File containing password to authenticate to SpiderFoot server. Ensure permissions on the file are set
               appropriately!
  -e FILE      Execute commands from FILE.
  -l FILE      Log command history to FILE. By default, history is stored to ~/.spiderfoot_history unless disabled with -n.
  -n           Disable history logging.
  -o FILE      Spool commands and output to FILE.
  -q           Silent output, only errors reported.
  -k           Turn off color-coded output.
  -b, -v       Print the banner w/ version and exit.

```

