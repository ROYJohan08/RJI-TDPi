## Before print job starts

```
M117 Calibration...
G90 ; Coordonnées absolues
M82 ; Extrudeur en mode absolu
G28 ; Home tous les axes
M117 Prechauffage de l imprimante
M140 S60 ; Définit la température du plateau à 60°C (sans attendre)
M104 S200 ; Définit la température de la buse à 200°C (sans attendre)
M190 S60 ; Attend que le plateau atteigne 60°C avant de continuer
M109 S200 ; Attend que la buse atteigne 200°C avant de continuer
M117 Nettoyage tete d'impression
G1 X236.0 Y50.0 Z0.0 F5000.0 ; Position Nozzle in Clean start position
G1 X236.0 Y45.0 Z0.0 F5000.0 ; Move into Brass Brush in Cleaning height Z=0
G1 X243.0 Y45.0 Z0.0 F5000.0 ; Move X +7mm
G1 X243.0 Y40.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X236.0 Y40.0 Z0.0 F5000.0 ; Move X -7mm
G1 X236.0 Y35.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X243.0 Y35.0 Z0.0 F5000.0 ; Move X +7mm
G1 X243.0 Y30.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X236.0 Y30.0 Z0.0 F5000.0 ; Move X +7mm
G1 X236.0 Y25.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X243.0 Y25.0 Z0.0 F5000.0 ; Move X +7mm
G1 X243.0 Y20.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X236.0 Y20.0 Z0.0 F5000.0 ; Move X +7mm
G1 X236.0 Y15.0 Z0.0 F5000.0 ; Move Y -5mm
G1 X243.0 Y15.0 Z0.0 F5000.0 ; Move X +7mm
G1 X243.0 Y10.0 Z5.0 F5000.0 ; Move Y -5mm and X +5mm To get free of Brass Brush
M117 Ligne de purge
G92 E0 ; Réinitialise la distance d'extrusion
G1 Z2.0 F3000 ; Soulève la buse pour éviter de rayer le plateau
G1 X220.0 Y20 Z0.3 F5000.0 ; Se déplace à la position de départ (X5, Y20)
G1 X220.0 Y220.0 Z0.3 F1500.0 E20 ; Trace la première ligne vers le fond
G92 E0 ; Réinitialise encore l'extrudeuse
G1 Z2.0 F3000 ; Soulève la buse
G1 X220.0 Y20 Z0.3 F5000.0 ; Petit mouvement rapide pour "couper" le fil
M117 Impression en cours...
```

## After print job completes
```
M104 S0 ; Éteindre buse
M140 S0 ; Éteindre plateau
M107 ; Éteindre ventilos
G91 ; Relatif
G1 Z5 F3000 ; Lever la tête
G90 ; Absolu
G1 X0 Y230 F6000 ; Avancer le plateau (ajuster Y selon votre imprimante)
M84 ; Désactiver moteurs
M117 Impression terminee
OCTOLIGHT OFF
```
