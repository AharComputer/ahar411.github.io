---
layout: post
title:  "fixing a grandstream telephone thing"
date:   2014-07-13 13:07:29
---

what we did today is configure a grand stream telephone system which will let you forward calls and even recored voice mail and forward it to an email
here is what we did


1.  fixed ip address we went into its configuration and made it request the ip `10.10.10.10` so now it has a static ip 

1.  then we made it work with ntp time

1.  then configured the email so it can send the voice mail

1. change range for extensions to fit your need

1. make you extensions and make sure it's type is SIP

1. connect your telephone if there also from grandstream it can auto connect

1. connect them to the extensions 

1. configure your anolag trunk

1. configure outbound routes

1. configure inbound routes