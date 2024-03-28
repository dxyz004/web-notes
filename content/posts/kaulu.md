+++
title = 'kaulu: song lyric search engine'
date = 2024-03-27T18:03:54-05:00
draft = false
+++

![logo](/home_half.png)

Kaulu (kah-oo-loo) is a Hawaiian word for a mythological trickster god. The search engine borrows its fun (with less mischief) sounding name.

Demonstration notes:

- The local search functionality is handled using Lucene. The web search functionality is handled using a Google API.
- To run/host the local search component, one may install and set up Apache Tomcat and drag the “jsp” folder into Tomcat’s “webapps” directory and access http://localhost:8080/jsp (8080 by default) in a web browser while Tomcat is running.

