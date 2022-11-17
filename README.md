# Most common wordlists

Generally, the best lists are based on pwned password (real world passwords previously exposed in data breaches), such as the infamous `rockyou.txt`. Others, are cultivated from larger dumps of millions of passwords and boiled down to the most commonly reoccurring items.
Here is a (non-exhaustive) collection of the more important wordlists for discovery, enumeration, fuzzing, and exploitation.

Note: Kali Linux provides some password dictionary files as part of its standard installation. One of this files is located in the following location: `/usr/share/wordlists/rockyou.txt.gz`.

## Leaked passwords

- [RockYou](lists/leaked-passwords/rockyou.txt) (*14,344,392 lines*)
- [Nmap](lists/leaked-passwords/nmap.txt) (*4,999 lines*)
- [Dark web 2017](lists/leaked-passwords/darkweb2017.txt) (*9,999 lines*)
- [Facebook phished](lists/leaked-passwords/facebook_phished.txt) (*2,441 lines*)
- [Ashley Madison data breach](lists/leaked-passwords/Ashley-Madison.txt) (*375,853 lines*)

## Password dictionaries

- [Default passwords for services](lists/password-dictionaries/default_passwords_for_services.txt) (*1,243 lines*)
- [John the Ripper](lists/password-dictionaries/john-the-ripper.txt) (*3,106 lines*)
- [Cain and Abel](lists/password-dictionaries/cain-and-abel.txt) (*306,706 lines*)
- [Conficker worm](lists/password-dictionaries/conficker.txt) (*181 lines*)
- [Dates 1900-2030](lists/1900-2030.txt) (*48,664 lines*)
- [Days](lists/days.txt) (*6,240 lines*)
- [Months](lists/months.txt) (*13,431 lines*)
- [Seasons](lists/seasons.txt) (*5,390 lines*)

## Passwords with WPA length

- [WPA - over 200k](lists/passwords-WPA/wpa-over200k.txt) (*203,806 lines*)
- [WPA - top 4,8k](lists/passwords-WPA/wpa-top4800.txt) (*4,800 lines*)
- [WPA - top 447](lists/passwords-WPA/wpa-top447.txt) (*447 lines*)

## Discovery

- [Backup files w/ path](lists/discovery/backup_files_with_path.txt) (*1,286 lines*)
- [Backup files only](lists/discovery/backup_files_only.txt) (*1,015 lines*)
- [Common](lists/discovery/common.txt) (*4,613 lines*)
- [Directory (only one)](lists/discovery/directory_only_one.txt) (*1,993 lines*)
- [Domain names to scan](lists/discovery/dnsmap.txt) (*17,576 lines*)
- [Sensitive files - unix](lists/discovery/sensitive_files_unix.txt) (*16 lines*)
- [Sensitive files - windows](lists/discovery/sensitive_files_win.txt) (*7 lines*)
- [Subdomains](lists/discovery/subdomains.txt) (*114,532 lines*)

## Misc

- [Italian wordlist (single)](lists/other/lower_it.txt) (*344,074 lines*)
- [Italian wordlist (mixed)](lists/other/mixed_it.txt) (*419 lines*)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tutorial has been made for educational purposes only, I don't promote malicious practices and I will not be responsible for any illegal activities.
