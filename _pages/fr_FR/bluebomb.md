---
title: "Bluebomb"
---
{% include toc title="Sommaire" %}

![BlueBomb](/images/bluebomb.png)

Bluebomb est un exploit fait par [FullMetal5] (https://github.com/Fullmetal5/bluebomb/releases) destiné à la Wii Mini Modding qui tire parti d'un exploit de la pile Bluetooth Broadcom à l'intérieur de la console. C'est le seul exploit qui fonctionne sur la Wii Mini, mais il peut également être utilisé sur la Wii d'origine. Il peut également être utilisé comme récupération de brique au cas où vous n'auriez pas installé Priiloader et / ou BootMii.

Pour la vWii et la Wii d'origine de la Wii U, nous vous recommandons d'utiliser [un autre exploit] (/ get-started) à la place si vous avez l'intention d'installer Homebrew Launcher et / ou BootMii
{: .notice-info}

RiiConnect24 n'est pas encore disponible sur la Wii Mini.
{: .notice-info}

BootMii ne peut pas encore être installé sur la Wii Mini. N'essayez pas de l'installer. Nous ne prenons aucune responsabilité si vous briquez votre console.
{: .notice-warning}

Cet exploit ne fonctionnera pas sur le vWii d'une Wii U. Veuillez utiliser [un autre exploit] (/get-started).
{: .notice-warning}

#### Ce dont vous aurez besoin
- Une machine Linux avec un adaptateur bluetooth (une intégrée fonctionnera)
   - Si vous utilisez un Chromebook, vous n'avez pas besoin d'installer un autre système d'exploitation. Vous pouvez activer [Linux dans ChromeOS] (https://support.google.com/chromebook/answer/9145439?hl=en)
   - L'utilisation du sous-système Windows pour Linux ne fonctionnera pas, en raison de l'impossibilité d'accéder à `bluetoothctl`.
   - Si vous n'avez pas Linux, Ubuntu est l'option la plus conviviale
     - Les appareils 32 bits nécessiteront [Ubuntu 16.04] (http://releases.ubuntu.com/16.04/)
     - Les appareils 64 bits peuvent utiliser la [version 18.04 LTS] (http://releases.ubuntu.com/bionic/), mais la [dernière version] (https://ubuntu.com/download/desktop) fonctionnera comme bien
- Une clé USB
- Une console Wii ou Wii Mini (évidemment)

#### Que savoir en premier
Si tu acheter ton Wii dans les location en Canada, États Unis, Japon, et Corée ton Wii Region est NTSC
Si tu acheter ton Wii dans les pays Européen 
Si vous n'êtes pas sûr, accédez aux paramètres Wii
![Paramètres de wii](/images/Wii/Wii-Version-FR.png)
En haut à gauche, notez que votre numéro de version se termine par une lettre: U pour les consoles américaines, E pour les européennes, J pour les consoles japonaises et K pour les coréennes.

𝗟𝗮 𝘀𝗶𝗴𝗻𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻 𝗱𝗲𝘀 𝗹𝗲𝘁𝘁𝗿𝗲𝘀
U, J, K sont les consoles NTSC. 
E sont les consoles européennes
#### Instructions

1. Telecharge les fichiers de (BootMii)[https://bootmii.org/download/]
2. Mettez tous les fichiers du dossier dans l'archive que vous avez téléchargée sur votre clé USB.
3. Ouvrez le site depuis les favoris. Cela va commencer le téléchargement de HackMii Installer. Cela devrait prendre un peu de temps.

Si le HackMii Installer ne s'ouvre pas et la Wii se bloque (vous ne pouvez plus bouger votre curseur), Redémarrez la Wii et recommencez.

[Continuer avec l'installation de la Chaîne Homebrew](hbc)
{: .notice--info}

####Installation de cIOS
cIOS est important si tu veux jouer les jeux dans
