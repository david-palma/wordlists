# Most common wordlists

Generally, the best lists are based on pwned password (real world passwords previously exposed in data breaches), such as the infamous `rockyou.txt`. Others, are cultivated from larger dumps of millions of passwords and boiled down to the most commonly reoccurring items.
Here is a (non-exhaustive) collection of the more important wordlists for discovery, enumeration, fuzzing, and exploitation.

Note: Kali Linux provides some password dictionary files as part of its standard installation. One of this files is located in the following location: `/usr/share/wordlists/rockyou.txt.gz`.

## Leaked passwords

- [RockYou](leaked-passwords/rockyou.txt) (*14,344,392 lines*)
- [Nmap](leaked-passwords/nmap.txt) (*4,999 lines*)
- [Dark web 2017](leaked-passwords/darkweb2017.txt) (*9,999 lines*)
- [Facebook phished](leaked-passwords/facebook_phished.txt) (*2,441 lines*)
- [Ashley Madison data breach](leaked-passwords/Ashley-Madison.txt) (*375,853 lines*)

## Password dictionaries

- [Default passwords for services](password-dictionaries/default_passwords_for_services.txt) (*1,243 lines*)
- [John the Ripper](password-dictionaries/john-the-ripper.txt) (*3,106 lines*)
- [Cain and Abel](password-dictionaries/cain-and-abel.txt) (*306,706 lines*)
- [Conficker worm](password-dictionaries/conficker.txt) (*181 lines*)
- [Dates 1900-2030](1900-2030.txt) (*48,664 lines*)
- [Days](days.txt) (*6,240 lines*)
- [Months](months.txt) (*13,431 lines*)
- [Seasons](seasons.txt) (*5,390 lines*)

## Passwords with WPA length

- [WPA - over 200k](passwords-WPA/wpa-over200k.txt) (*203,806 lines*)
- [WPA - top 4,8k](passwords-WPA/wpa-top4800.txt) (*4,800 lines*)
- [WPA - top 447](passwords-WPA/wpa-top447.txt) (*447 lines*)

## Discovery

- [Backup files w/ path](discovery/backup_files_with_path.txt) (*1,286 lines*)
- [Backup files only](discovery/backup_files_only.txt) (*1,015 lines*)
- [Common](discovery/common.txt) (*4,613 lines*)
- [Directory (only one)](discovery/directory_only_one.txt) (*1,993 lines*)
- [Domain names to scan](discovery/dnsmap.txt) (*17,576 lines*)
- [Sensitive files - unix](discovery/sensitive_files_unix.txt) (*16 lines*)
- [Sensitive files - windows](discovery/sensitive_files_win.txt) (*7 lines*)
- [Subdomains](discovery/subdomains.txt) (*114,532 lines*)

## Misc

- [Italian wordlist (single)](other/lower_it.txt) (*344,074 lines*)
- [Italian wordlist (mixed)](other/mixed_it.txt) (*419 lines*)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tutorial has been made for educational purposes only, I don't promote malicious practices and I will not be responsible for any illegal activities.
