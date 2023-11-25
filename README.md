# firmware-i915

Firmware-i915
Fix-Firmware-i915
Ce dépôt propose une solution pour corriger l'erreur "Possible firmware manquant /lib/firmware/i915" sur diverses distributions Linux, notamment Debian, SysLinuxOS et d'autres utilisant le noyau Linux.

Tous les avertissements affichés sont liés au micrologiciel manquant pour les microarchitectures Intel suivantes :

Lac Sky
Broxton
Lac Kaby
Lac Comet
Lac Ice
Lac Elkhart
Lac Tiger
Lac Gemini
Lac Alder
Arc Alchemist
Instructions
Pour utiliser ces fichiers de firmware :

Clonez ce dépôt sur votre machine :

bash

$ git clone https://github.com/Wharkly47/firmware-i915.git

Accédez au répertoire "fix-firmware-i915/" :

bash

$ cd fix-firmware-i915/

Assurez-vous que le script est exécutable :

bash

$ chmod +x fixi915.sh

Exécutez le script pour corriger les firmwares manquants :

bash

$ ./fixi915.sh

---

![W2P](./iWGNU/WGNU.png)

Wharkly-47

