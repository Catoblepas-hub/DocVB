---
id: carte-5V.md
title: Carte 5V 25-26
description: Carte d'alimentation 5V pour le rail logique — schéma électrique et PCB
sidebar_label: Carte 5V
sidebar_position: 4
tags: [cdr, nantes, robotique, electronique, pcb]

---

Cette carte sert à abaisser le niveau de tension initiallement à 15V pour obtenir du 5V comptable avec les Teensy, le Lidar et l'ensemble des capteurs

## Schéma électrique 
<img width="642" height="207" alt="image" src="https://github.com/user-attachments/assets/33b76af5-6948-4183-987c-ac70925f0db6" />
## Schéma PCB
<img width="913" height="582" alt="image" src="https://github.com/user-attachments/assets/9ed1ae7a-e93d-462f-b98d-db77b78d1d64" />

Ce PCB branché sur une sortie 5V du PCB d'alimentation principale en passant par un Buck Convertor est protégé par un condensateur et un fusible pour 
protéger des pics de courants et de voltages. Des protections suplémentaires sont placées au niveau de la prise usb destinée au LIDAR car celui ci 
comprend un moteur qui est succeptible de génerer des pics de voltages.
