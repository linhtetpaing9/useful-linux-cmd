# Useful Linux Cmd

<name> = mongo (eg. something like that)

dkpg -l | grep <name> => to find <name> running process
  
sudo find /etc/ -name "*<name>*" => to find specific folder with file <name>
  
cut -d: -f1 /etc/passwd | grep <name> => check exist password for name
  
cut -d: -f1 /etc/group | grep <name> => check exist password for name
