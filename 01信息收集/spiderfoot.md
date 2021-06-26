# spiderfoot

```shell
┌──(root💀kali)-[/home/kali]
└─# spiderfoot --help                     
usage: sf.py [-h] [-d] [-l IP:port] [-m mod1,mod2,...] [-M] [-s TARGET] [-t type1,type2,...] [-T] [-o tab|csv|json] [-H] [-n] [-r]
             [-S LENGTH] [-D DELIMITER] [-f] [-F type1,type2,...] [-x] [-q]

SpiderFoot 3.0: Open Source Intelligence Automation.

optional arguments:
  -h, --help          show this help message and exit
  -d, --debug         Enable debug output.
  -l IP:port          IP and port to listen on.
  -m mod1,mod2,...    Modules to enable.
  -M, --modules       List available modules.
  -s TARGET           Target for the scan.
  -t type1,type2,...  Event types to collect (modules selected automatically).
  -T, --types         List available event types.
  -o tab|csv|json     Output format. Tab is default. If using json, -q is enforced.
  -H                  Don't print field headers, just data.
  -n                  Strip newlines from data.
  -r                  Include the source data field in tab/csv output.
  -S LENGTH           Maximum data length to display. By default, all data is shown.
  -D DELIMITER        Delimiter to use for CSV output. Default is ,.
  -f                  Filter out other event types that weren't requested with -t.
  -F type1,type2,...  Show only a set of event types, comma-separated.
  -x                  STRICT MODE. Will only enable modules that can directly consume your target, and if -t was specified only
                      those events will be consumed by modules. This overrides -t and -m options.
  -q                  Disable logging. This will also hide errors!
                                                                            
```

