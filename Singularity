Bootstrap:docker
From:ubuntu:18.04

%help
    Container for a VNC server

%labels
    MAINTAINER Colin Sauze

%environment
    #define environment variables here
    
%post  
    apt-get update
    apt-get -y install vnc4server jwm ssh
    apt-get update

%runscript
    vncserver
