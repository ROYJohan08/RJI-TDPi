# RJI-TDPi
Code pour une Raspberry pi connecté a une Creality Ender 3

## Matériel.

- [X] [Créality Ender 3](https://www.amazon.fr/-/en/Creality-Ender-3D-Printer-Protection/dp/B07BR3F9N6/ref=sr_1_5?crid=1WM17GQCQ67FD&dib=eyJ2IjoiMSJ9.v45COX6V5taYQ7JDcvZPmDBgmwQxch36BmS0jhXZOpEQ85bI0XMGHBvp3n5nBMgKnNNHQltp6F0HPjwuMCjnKiU0vPuBFy_WZ6diBRRtb1JMPS6PezU-PtOBVdoCU9w2CGN37LqBfRYtyEiudCk2mfeb6A4OYy4SYNN6HSa2XpPQntdoFlzG0sILgr2MPCiFRois9fDgUualCWKNkKleVyx4bohaGY1BK7XDA36f5dZbyAfb6EvIFqdbaq8otxEZMiT3iwUOxt3ryvGM8wpkz6hg0gZwF6cFXawyT3aFxck.tv2Ow8JJKpE4Ni_XpqRp-SFUWSy83X6O1y_mZkWQvcc&dib_tag=se&keywords=creality+ender+3&qid=1774355655&sprefix=creality+ender%2Caps%2C1321&sr=8-5).
- [X] [Raspberry pi 2](https://www.amazon.fr/-/en/Raspberry-Pi-Model-Desktop-Linux/dp/B00T2U7R7I/ref=sr_1_4?dib=eyJ2IjoiMSJ9._PONHtvgCeuUGHwdKumpftsdpmljx4rmJaD_gijw8iW5plCm7f-BErsxjD3II-Gwv-JwzgV-LobaUblR7zwXkunnGYLWmkW3wBNib81k71BO2R8VBuT3zyK0Jq-_4AnoItIIAnR_pI1ytUf5qVnelhwaCypxiwVB1VAMO8ouTu-5zwsXa9uAcd_QqdVQ8B3YrOzYJCAgNxsJ4QNY55Cn3d2IfWefPOVxHHsLa3QdaNGVdSWSjcTiRPk8Omdo_CASPS-Q1ZQxfd4CmTlI4UGodO9r66qq2HNy05G0lpkbqd8.IHo7fFokIVqufRIot62RXSi4dJ6TPXJXBLvsIBNdBQw&dib_tag=se&keywords=pi+2&qid=1774355683&sr=8-4).
- [X] [Camera pi](https://fr.aliexpress.com/item/1005009359009033.html?spm=a2g0o.productlist.main.2.c392COMsCOMs6s&algo_pvid=7c342357-a3c3-43b6-9d91-11d36dac5032&algo_exp_id=7c342357-a3c3-43b6-9d91-11d36dac5032-1&pdp_ext_f=%7B%22order%22%3A%2243%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%217.25%214.29%21%21%2156.58%2133.46%21%402103890117743557096997655ec84b%2112000055983659891%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A3dd36dd8%3Bm03_new_user%3A-29895%3BpisId%3A5000000197682667&curPageLogUid=cynOwBFQrrc7&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009359009033%7C_p_origin_prod%3A).
- [X] [Rallonge cable 22 pin](https://fr.aliexpress.com/item/1005004285888200.html?spm=a2g0o.productlist.main.11.53d8566ae2TKwS&algo_pvid=fadd7adf-22b3-437d-b14c-e596e176b3d3&algo_exp_id=fadd7adf-22b3-437d-b14c-e596e176b3d3-8&pdp_ext_f=%7B%22order%22%3A%22772%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%210.86%210.86%21%21%210.97%210.97%21%40210385db17743557407941880e43da%2112000028630582402%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A3dd36dd8%3Bm03_new_user%3A-29895&curPageLogUid=mk9gDYcGKICz&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004285888200%7C_p_origin_prod%3A).
- [X] [Carte micro-SD](https://fr.aliexpress.com/item/1005009550817879.html?algo_pvid=d6d4a73d-7b88-4096-a3a5-c67879c4a4b8&algo_exp_id=d6d4a73d-7b88-4096-a3a5-c67879c4a4b8-9&pdp_ext_f=%7B%22order%22%3A%2220660%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%213.49%213.49%21%21%2127.22%2127.22%21%40211b680e17743558278828537e7be7%2112000049441219340%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A3dd36dd8%3Bm03_new_user%3A-29895&curPageLogUid=HVtX9EpRYMt2&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009550817879%7C_p_origin_prod%3A).
- [X] [3D Touch](https://fr.aliexpress.com/item/1005006719560635.html?spm=a2g0o.productlist.main.30.1b9dIiFHIiFHlZ&algo_pvid=65268069-b382-4d04-91e4-55e7d1d35c79&algo_exp_id=65268069-b382-4d04-91e4-55e7d1d35c79-29&pdp_ext_f=%7B%22order%22%3A%22227%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%215.88%212.31%21%21%2145.84%2118.01%21%40210385db17743557891053408e43da%2112000038087014466%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A3dd36dd8%3Bm03_new_user%3A-29895%3BpisId%3A5000000197682667&curPageLogUid=ys3KZAIAOXVt&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006719560635%7C_p_origin_prod%3A).
- [X] [Roulements 608](https://fr.aliexpress.com/item/1005006087537541.html?spm=a2g0o.productlist.main.5.76284bf9UML6cb&algo_pvid=a5c3982f-1bfb-47d5-b584-19f2b9d6ca2a&algo_exp_id=a5c3982f-1bfb-47d5-b584-19f2b9d6ca2a-4&pdp_ext_f=%7B%22order%22%3A%22756%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%213.21%210.99%21%21%2125.07%217.73%21%40211b804117743559617342000ecc6d%2112000035671138014%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A3dd36dd8%3Bm03_new_user%3A-29895%3BpisId%3A5000000197682715&curPageLogUid=ghPafFwWZZdv&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006087537541%7C_p_origin_prod%3A).
- [X] [PLA](https://www.amazon.fr/ELEGOO-Filament-Dimensional-Accuracy-Compatible/dp/B0F4871GP4/ref=sr_1_4_sspa?dib=eyJ2IjoiMSJ9.EUKdJhH8N5kMm-71FTptkxWOi6-Ke-pfjUPL8nlOxs6Bza2N8vPjbTCHHgX4zxrPYk3FHUluvWEsjPYghqBPyUbgCOxzjZ6uOBl27RFudAVFh8Jkhhff_0XKhb-Rhcr4Hmz8cs7NRZC3kaQFpRWyiBVrQ0rMwXfit46eQV1ftBOmG10zK9ENGsM2YQ5mWaYU_4U4CtG4Bk6aWdhkNJHaVPiGYitb8r6t_vAF8rLV4-4pi2TcTUuxQqQwJdKxhWyGJd-hvz64adsdW5_g7URnCSeVtF18fNkNXEiralwgSX8.tmTz7LD2ifngWGTYtosgB7Mv661MZ_SXZVsAwTPwQyY&dib_tag=se&keywords=PLA&qid=1774356015&sr=8-4-spons&aref=kQnNZl9jIx&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1).
- [X] [Visserie M3](https://www.aliexpress.com/ssr/300000512/BundleDeals2?spm=a2g0o.productlist.main.2.70a3ruWkruWkJ6&productIds=1005009877872391:12000050454712739&pha_manifest=ssr&_immersiveMode=true&disableNav=YES&sourceName=SEARCHProduct&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009877872391%7C_p_origin_prod%3A&pvid=696283ab-6ddb-4792-877c-75eece452125).

## Partie 1 : Premiers pas.

- [X] Montez la Créality Ender 3 selons le manuel.
- [X] Branchez l'imprimante.
- [X] Récuperez la carte micro-SD et installez la sur un ordinateur.
- [X] Téléchargez le pack de GCodes et décompressez le dans la carte SD.
- [X] Mettez la carte Micro-SD dans l'imprimante et lancez un a un les impression.

## Partie 2 : Level up.

- [X] Installez un roulement 608 dans [ZAxisGuide](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/ZAxisGuide.gcode).
- [X] Installez un roulement 608 dans [FilamentHolder](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/FilamentHolder.gcode).
- [X] Installez le [ZAxisGuide](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/ZAxisGuide.gcode) dans la fente 2040 du haut du chassis.
- [X] Installez et vissez le [FilamentHolder](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/FilamentHolder.gcode) au bout de l'extruder.
- [X] Installez et vissez les [FanCover](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/FanCover.gcode) sur les ventilateurs.
- [X] Installez et vissez la Raspberry pi dans le [RPI2Case](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/RPI2Case.gcode).
- [X] Connectez les cables aux différents relais et capteurs.
- [X] Installez la camera dans le [RPI2CameraHolder](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/RPI2CameraHolder.gcode).
 - [X] Fixez la camera a la colle a chaud.
- [X] Installez et vissez le bras de la camera.
- [X] Connectez la caméra a la RPI.
- [X] Installez et vissez le [RPI2Case](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/RPI2Case.gcode).
- [X] Vissez le tout sur le chassis gauche.
- [X] Installer et vissez le 3DTouch sur le [3DTouchSupport](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/3DTouch.gcode).
- [X] Installez le [3DTouchSupport](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/GCodes/3DTouch.gcode) sur la tete d'impression.
- [X] Connectez le 3DTouch a la carte mère.
- [X] Branchez l'alimentation de l'imprimante sur le relais de la RPI.
- [ ] Branchez les mumières sur le second relais de la RPI.

## Partie 3 : Configuration.

- [X] Récuperez la carte microSD de la RPI.
- [X] Installez Octoprint via [RaspberryPiImager](https://www.raspberrypi.com/software/).
- [X] Initialisez octoprint puis Connectez-vous.
- [X] Téléchargez et envoyer le [fichier Backup](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/backups/20260324-134532.zip) dans "Paramètres>Backup&Restore".
- [X] Redémarrez la raspberry.
- [X] Dans firmware updater ajouter le [nouveau Firmware](https://github.com/ROYJohan08/RJI-TDPi/raw/refs/heads/main/sources/Ender3-BLTouchFirmware.bin).
- [X] Redémarrez l'imprimante.

## Partie 4 : Calibration.

- [X] Extrudeur :
  - [X] Extrudez 100mm
  - [X] Mesurez la quantitée réellement extrudé.
  - [X] Dans Controle>Step>Extruder, prenez la actuelle/100*La quantité réellement extrudé et saisissez cette valeur.
  - [X] Sauvegardez la configuration.
- [ ] Axe X et Y :
- [ ] Axe Z :

## Partie 5 : Direct drive

## Partie 6 : PETG, TPU et ABS
