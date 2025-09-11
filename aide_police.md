# Aide Police

## Documentation officiel

Ci-dessous une grosse exeplication de tout le fonctionnement de la tablette
  [https://docs.origennetwork.store/origen-police/guide-of-use](https://docs.origennetwork.store/origen-police/guide-of-use/police-cad)
  
## Les commandes

  *En général si vous avez "non" dans la colonne des raccourcis clavier c'est que cela est configurable dans votre jeux au niveau des touche dans la section FiveM*

  - [   Libéllé   ]         =>  [cmd dans le T]   =>    [raccourci clavier]   =>   [item utilisable]

### Radar
    
  - Radar de véhicules              => /alpr           =>    NUMPAD5       =>    none
  - Verrouiller le radar            => /balpr          =>    NUMPAD8       =>    none
  - Déplacer le radar               => /moveralpr      =>    NUMPAD4       =>    none
    
### Dispatch
  
  - Alerte de dispatch suivante     => /nxtalert       =>    RIGHT         =>    none
  - Alerte de dispatch précédente   => /prvalert       =>    LEFT          =>    none
  - Accepter alerte mini dispatch   => none            =>    O             =>    none
  - Refuser alerte mini dispatch    => none            =>    I             =>    none
  - Ouvrir mini dispatch            => none            =>    U             =>    none


### Autre

  - Ouvrir cad policier             => /pcad           =>    none          =>    police_cad
  - Police: Menotter / Déménotter   => none            =>    none          =>    none
  - Police: QRR                     => none            =>    none          =>    none
  - Police: 10-20                   => none            =>    none          =>    none
  - Police: Faire une charge        => none            =>    none          =>    none
  - Mettre le prévenu dans véhicule => none            =>    none          =>    none
  - Force véhicule + alerte         => /force          =>    none          =>    none
  - Ouvrir le menu accès rapide     => /quickaccess    =>    F7            =>    none
  - Mode minimap                    => /policeminmap   =>    none          =>    none
  - Parler à la radio               => none            =>    LMENU         =>    none
  - Changer animation radio         => /animradio      =>    none          =>    none
  - Parler mégaphone                => none            =>    Y             =>    none
  - Caméra Helico (conducteur)      => none            =>    E             =>    none

### Fonctionnement du Radars (attention reste après une tempête)

  - Command : /radars

### Fonctionnement du tazer

*Le tazer est modifié pour fonctionner avec des cartouches, il permet de faire 2 tires*
Nom des items
  - Arme : WEAPON_STUNGUN
  - Cartouche : taser_cartridge

### K9 (autre script ajouté)

Utiliser le 3eme oeil sur les personnes ou véhicule pour le fouiller

  - Ouvrir le menu                  => /k9menu         =>    F10           =>    none
  - Pour vous suivre                => none            =>    F    

  *Lorsque vous visez une personne pour les actions ci-dessous*
  - recherche sur individue         => none            =>    E    
  - attaquer                        => none            =>    G    
  
  *Pour la recherche vous pouvez aussi utiliser le 3eme oeil sur les individues et les véhicules
  ***ATTENTION:*** Pour qu'il puisse trouver les drogs ou autres qui sont des items il faut les référencer dans le fichier de config au niveau de *SearchableItems*

### Alert

**Police alert**
```lua
/911 [mon message]
```

**Ambulance Alert**
```lua
/911ems [mon message]
```

## Autre système ajouté pour plus de sérious RP

J'ai ajouté d'autre mode essentiel qui sont :
- [job-center]/[police_ems]/lib_police (permet d'avoir un vrai système de tazer avec des cartouches qui sont l'item "taser_cartridge" donc à avoir sur soit maxi 2 dans la config chaque cartouche fait 2 coups)
- [job-center]/[police_ems]/lvc (permet d'avoir un vrai système 2 tons mutli qui est configurable directement en jeux dans les config de touche FiveM, permet plein de solution)
- [others]/[mecaniquedejeux]/[imprimante_document]/nkt-printer/ (permet si vous avez l'item "paper" d'imprimer n'importe quel image que cela créé un item de cette image ouvrable en l'utilisant par exemple créer un papier officiel de licence de transport et l'imprimer pour le donner au joueur)
- [others]/[mecaniquedejeux]/[divers]/randol_notes/ (permet en achetant l'item "notepad" d'avoir un carnet de note utilisable aussi en jeux les note peuvent être détaché à la mode post it, ils peuvent être officiellement signé et donc identifier pour connaitre l'identité du créateur de la note ou pas)
- [others]/[mecaniquedejeux]/ts_Trafficlights (permet d'avoir de vrai feux rouge synchronisé, je l'es ai configuré à 3 à 5s max donc les feux peuvent être réellement respecté par les joueurs et donc ammendable si pas respecté car synchronisé entre joueur)
- [others]/[com]/sf_camerasecurity (permet d'avoir par un vendeur différents type de caméra, possible caméra espion à poser, les possibilités son différentes si Police, EMS, Civil. Elle peuvent être utilisé RP parlant car en cas de record de joueur ont voit la date et info divers sur les images de la tablette associé)

### Imprimante utilisation

  1. Avoir l'item "paper"
  2. Aller sur une imprimante en regardant avec le 3eme oeil
  3. Remplir les champs, le dernier champs est l'url de l'image qui est hebergé quelques part
  4. L'item "paper" ce supprime et vous donne un item "doc" avec tout renseigné dessus
  5. Utilise ce doc pour ouvrir l'image en jeux, cette item est transférable entre joueur




