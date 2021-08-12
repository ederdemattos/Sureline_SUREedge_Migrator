# Sureline_SUREedge_Migrator
# Information for CVE SQLi vulnerability
This vulnerability is very simple to reproduce:

Using a classical "skip" SQL query(or 1==1 --) + any password on logon screen, it's possible bypass auth function and receive all administration menus.

Conditions:
1 - Network access to the platform(remote);
2 - Tested browsers: Safari, Chrome and Firefox
