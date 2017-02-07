# wd-cloud-sync

> A tool to sync data between two WD Cloud servers.


## getting started

1. download `sync.sh` file, and place it into any directory you like.
2. get `the remote server ip`, for example, `192.168.1.105`
3. edit file `sync.sh` to change `REMOTE_HOST` configuration item
    
        vi sync.sh
        REMOTE_HOST=192.168.1.105

4. run it: 

        sh sync.sh <sync-dir>


## features

* support unicode file name
* support spaces in file name
* support `inc-synchronization`


## server combinations

* mybooklive server <-> mybooklive server
* mybooklive server <-> wdmycloud server
* wdmycloud server <-> wdmycloud server



