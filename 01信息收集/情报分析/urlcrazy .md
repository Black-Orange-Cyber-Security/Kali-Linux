# urlcrazy

```shell
┌──(root💀kali)-[/home/kali]
└─# urlcrazy -h
Warning. Ulimit may be too low. Check with `ulimit -a` and change with `ulimit -n 10000`

_______ ______ _____   ______                         
|   |   |   __ \     |_|      |.----.---.-.-----.--.--.
|   |   |      <       |   ---||   _|  _  |-- __|  |  |
|_______|___|__|_______|______||__| |___._|_____|___  |
                                                |_____|

URLCrazy version 0.7.1 by Andrew Horton (urbanadventurer)
Visit http://www.morningstarsecurity.com/research/urlcrazy

Generate and test domain typos and variations to detect and perform typo squatting, URL hijacking,
phishing, and corporate espionage.

Supports the following domain variations:
Character omission, character repeat, adjacent character swap, adjacent character replacement, double 
character replacement, adjacent character insertion, missing dot, strip dashes, insert dash,
singular or pluralise, common misspellings, vowel swaps, homophones, bit flipping (cosmic rays),
homoglyphs, wrong top level domain, and wrong second level domain.

Usage: ./urlcrazy [options] domain

Options
-k, --keyboard=LAYOUT  Options are: qwerty, azerty, qwertz, dvorak (default: qwerty)
-p, --popularity       Check domain popularity with Google
-r, --no-resolve       Do not resolve DNS
-i, --show-invalid     Show invalid domain names
-f, --format=TYPE      Human readable, JSON, or CSV (default: human readable)
-o, --output=FILE      Output file
-n, --nocolor          Disable colour
-d, --debug            Enable debugging output for development
-h, --help             This help
-v, --version          Print version information. This version is 0.7.1

```

