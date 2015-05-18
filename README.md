# myrepo
My Repo
$ docker ps -l
CONTAINER ID        IMAGE               COMMAND             CREATED
STATUS                      PORTS               NAMES
2b3d85989829        ubuntu:latest       "/bin/bash"         8 minutes ago
Exited (0) 18 seconds ago                       kickass_swartz

arun.b.nair@MW7N259CK5PQ3P ~
$ docker run -i -t ubuntu
root@2da3da6f4c01:/# sudo apt-get update
Ign http://archive.ubuntu.com trusty InRelease
Ign http://archive.ubuntu.com trusty-updates InRelease
Ign http://archive.ubuntu.com trusty-security InRelease
Get:1 http://archive.ubuntu.com trusty Release.gpg [933 B]
Get:2 http://archive.ubuntu.com trusty-updates Release.gpg [933 B]
Get:3 http://archive.ubuntu.com trusty-security Release.gpg [933 B]
Get:4 http://archive.ubuntu.com trusty Release [58.5 kB]
Get:5 http://archive.ubuntu.com trusty-updates Release [63.5 kB]
Get:6 http://archive.ubuntu.com trusty-security Release [63.5 kB]
Get:7 http://archive.ubuntu.com trusty/main Sources [1335 kB]
Get:8 http://archive.ubuntu.com trusty/restricted Sources [5335 B]
Get:9 http://archive.ubuntu.com trusty/universe Sources [7926 kB]
Get:10 http://archive.ubuntu.com trusty/main amd64 Packages [1743 kB]
Get:11 http://archive.ubuntu.com trusty/restricted amd64 Packages [16.0 kB]
Get:12 http://archive.ubuntu.com trusty/universe amd64 Packages [7589 kB]
Get:13 http://archive.ubuntu.com trusty-updates/main Sources [257 kB]
Get:14 http://archive.ubuntu.com trusty-updates/restricted Sources [2310 B]
Get:15 http://archive.ubuntu.com trusty-updates/universe Sources [146 kB]
Get:16 http://archive.ubuntu.com trusty-updates/main amd64 Packages [654 kB]
Get:17 http://archive.ubuntu.com trusty-updates/restricted amd64 Packages [15.1
kB]
Get:18 http://archive.ubuntu.com trusty-updates/universe amd64 Packages [365 kB

Get:19 http://archive.ubuntu.com trusty-security/main Sources [100 kB]
Get:20 http://archive.ubuntu.com trusty-security/restricted Sources [1874 B]
Get:21 http://archive.ubuntu.com trusty-security/universe Sources [28.0 kB]
Get:22 http://archive.ubuntu.com trusty-security/main amd64 Packages [341 kB]
Get:23 http://archive.ubuntu.com trusty-security/restricted amd64 Packages [14.
 kB]
Get:24 http://archive.ubuntu.com trusty-security/universe amd64 Packages [133 k
]
Fetched 20.9 MB in 2min 57s (117 kB/s)
Reading package lists... Done

