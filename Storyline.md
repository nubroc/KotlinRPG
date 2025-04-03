```
Début : Tu te réveilles au pied des marches du Sanctuaire.
│
├── [1] Monter les premières marches
│   ├── Combat contre un garde du Sanctuaire
│   │   ├── Gagner → suite : Accès aux chemins Est/Ouest
│   │   └── Perdre → Fin du jeu ou recommencer
│
├── [2] Fouiller les alentours
│   ├── Trouve une potion de soin (+20 PV)
│   └── Retour au début avec potion en inventaire
│
└── [3] Parler à Shun
    ├── Il te dit de prendre le chemin de gauche (le droit est piégé)
    └── Retour avec info stratégique

Après victoire contre le garde :
Choix : Quel chemin prendre ?
│
├── [1] Prendre à droite
│   └── Tu tombes dans un piège (perte de 30 PV)
│       └── Si PV > 0 → Continue jusqu’au Temple du Bélier
│       └── Sinon → Fin
│
└── [2] Prendre à gauche
    └── Tu évites le piège grâce à l’indice de Shun
        └── Accès direct au Temple du Bélier (bonus : +10 PV)

Temple du Bélier (Mu)
│
├── Énigme : "Je suis né dans le sang, frère du tonnerre. Qui suis-je ?"
│   ├── Réponse : Dragon → Faux
│   ├── Réponse : Phénix → Faux
│   └── Réponse : Pégase → Vrai → + Armure réparée
│
└── Passage accordé vers les maisons du Zodiaque

Traversée des Maisons
│
├── Maison du Taureau → Aldébaran
│   ├── Combat : attaque puissante lente
│   └── Si victoire → possibilité de récupérer l’Écu d’Or (bonus défense)
│
├── Maison du Cancer → Deathmask
│   ├── Combat mental : illusions (test de volonté)
│   └── Si échec → retour 1 maison en arrière
│
└── Maison du Lion → Aiolia
    ├── Combat éclair (rapide et intense)
    ├── Si tu as l’armure réparée → + chances
    └── Si victoire → accès à la maison de la Vierge

Maison de la Vierge → Shaka
│
├── Combat impossible à gagner de front
├── Choix : méditer ou attaquer ?
│   ├── Attaquer → échec immédiat
│   └── Méditer → éveil du 7e sens → victoire par sagesse

Temple du Scorpion → Milo
│
├── Si PV bas, Milo te laisse passer
└── Sinon combat test de courage

Fin du sanctuaire :
│
└── Statue d’Athéna
    ├── Tu arrives juste avant que Saga (le faux Pope) ne frappe Saori
    ├── Choix : Attaquer Saga / Protéger Saori / Appeler les autres chevaliers
    └── Plusieurs fins possibles :
        ├── Seiya seul → échec ou sacrifice héroïque
        ├── Avec armure + objets + alliés → victoire, Saori sauvée
        └── Tous les bronzes réunis → Fin parfaite
```