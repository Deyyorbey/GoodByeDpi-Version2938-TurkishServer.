# GoodbyeDPI — Deep Packet Inspection circumvention utility
This software designed to bypass Deep Packet Inspection systems found in many Internet Service Providers which block access to certain websites.

It handles DPI connected using optical splitter or port mirroring (Passive DPI) which do not block any data but just replying faster than requested destination, and Active DPI connected in sequence.

$ Windows 7, 8, 8.1, 10 or 11 with administrator privileges required.

Quick start For Russia: Download latest version from Releases page, unpack the file and run 1_russia_blacklist_dnsredir.cmd script. For other countries: Download latest version from Releases page, unpack the file and run 2_any_country_dnsredir.cmd. These scripts launch GoodbyeDPI in recommended mode with DNS resolver redirection to Yandex DNS on non-standard port (to prevent DNS poisoning). If it works — congratulations! You can use it as-is or configure further.

How to use Download latest version from Releases page and run.

Supported arguments To get relevant information about your version of the program, use the -h (--help) argument at startup.

## Turn off windows defender before using
