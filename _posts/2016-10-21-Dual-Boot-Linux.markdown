---
layout: post
title: "Dual Boot Linux(en cours de rédaction)"
date : 2016-10-21 08:57:30 -0700
categories: tutorial
summary: Pour tous ceux qui veulent coder avec un vrai OS, voici un petit tuto pour installer une distribution Linux en dual boot.
---
# Dual Boot Linux

## Qu'est ce que c'est ?

Le dual boot c'est simplement le fait d'avoir 2 systèmes d'exploitation sur sa machine, dans notre cas ce sera un dual boot Windows-Linux.

## Les prérequis
Pour le dual boot quelques prérequis sont nécessaire :

* Votre Pc avec Windows 7/8/10 installé
* Un iso Linux 
* Une clé usb formaté

Dans un souci de sécurité, pensez à bien sauvegarder vos données sensible au préalable.

## La clé bootable
Pour pouvoir installer Linux, nous allons avoir besoin d'une clé bootable.
Pour ce faire télécharger le logiciel [Unetbootin](http://www.commentcamarche.net/download/telecharger-34061449-unetbootin) et installer le.

Si vous ne savez pas quel distribution linux prendre, je vous propose [Linux mint](http://ftp.crifo.org/mint-cd//stable/18/linuxmint-18-cinnamon-64bit.iso) une distribution très *user friendly* avec l'environnement de bureau Cinnamon qui est très proche de celui de windows.

Une fois l'iso téléchargé, lancer Windows 7 USB/DVD Tool. Cela vous ouvre une fenêtre avec plusieurs possibilité.
Selectionner l'option **DisqueImage** puis cliqué sur **...** et selectionner votre iso.
Dans la liste déroulante à coté de **Lecteur** choisiser votre clé usb et appuyer sur ok.
Il ne reste plus qu'à attendre la fin de la copie.
