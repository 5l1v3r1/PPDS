# PPDS
A tool to overwrite devices with trash data on Linux

# Compile
$ cd PPDS/
$ make

# Execute
[ra_horakhty][Dev][PPDS]
-> sudo ./PPDS
[sudo] password for ra_horakhty: 
[-] Insufficient args
[Usage] ./PPDS <Buffer write size in bytes Ex. 1048576 (1MB)> <Device Ex. /dev/sdb>

# Example output of erasing my 8GB USB drive with a 1MB write

[ra_horakhty][Dev][PPDS]
-> sudo ./PPDS 1048576 /dev/sdb
[INFO] Bytes Out: 1073741824 -> Device: /dev/sdb
[INFO] Bytes Out: 2147483648 -> Device: /dev/sdb
[INFO] Bytes Out: 3221225472 -> Device: /dev/sdb
[INFO] Bytes Out: 4294967296 -> Device: /dev/sdb
[INFO] Bytes Out: 5368709120 -> Device: /dev/sdb
[INFO] Bytes Out: 6442450944 -> Device: /dev/sdb
[INFO] Bytes Out: 7516192768 -> Device: /dev/sdb
[INFO] Finishing up. This could take a while..
[INFO] Device overwritten: /dev/sdb
[INFO] Total bytes written: 8006926335
