---
title: "AutoTicketLinkName"
date: 2025-11-27T21:47:12+09:00
lastmod: 2025-11-27T21:47:12+09:00
slug: "AutoTicketLinkName"
draft: false
---

#author("2025-11-24T17:33:15+09:00","default:massy","massy")
#freeze
# AutoTicketLink definition

Reference: https://pukiwiki.osdn.jp/?AutoTicketLink

- jira https://site1.example.com/jira/browse/
  - AAA Project title $1
  - BBB Project title $1
- jira https://site2.example.com/jira/browse/
  - PROJECTA Site2 $1


 (Default definition) pukiwiki.ini.php
  = array(
   'title' => 'My JIRA - $1',
   'base_url' => 'https://issues.example.com/jira/browse/',
 );
