---
title: "E: Sub-process /usr/bin/dpkg returned an error code"
path: "/SUB-PROCESS /USR/BIN/DPKG RETURNED AN ERROR CODE"
date: "2020-06-19"
---

Lors ce que une commande terminal renvoie:

`dpkg: erreur: erreur de configuration : /etc/dpkg/dpkg.cfg.d/multiarch:1 : option « foreign-architecture » inconnue
E: Sub-process /usr/bin/dpkg returned an error code (2)’`

La solution est de taper:
`sudo rm /etc/dpkg/dpkg.cfg.d/multiarch`
