🏷️ Modèle de nommage : TYPE_Fonction-Principale
L'idée est d'utiliser des préfixes simples pour regrouper les fonctions par nature :

COM_ (Communication) :

COM_EthernetIP-Scanner (contient tes libs pour XNE-GWBR-2ETH-IP)

COM_ModbusTCP-Master

COM_CanOpen-Manager

DRV_ (Drives & Moteurs) :

DRV_Variateur-DG1

DRV_Demarreur-DM1

DRV_Moteur-Pas-a-Pas

MATH_ (Calculs & Traitement) :

MATH_Mise-Echelle-Analogique

MATH_Statistiques-Production

MATH_Trigonométrie-Avancée

CTRL_ (Contrôle & Régulation) :

CTRL_Regulateur-PID

CTRL_Gestion-Pompes-Alternées

CTRL_Rampe-Accélération

SYS_ (Système & Hard) :

SYS_Gestion-RTC-Horloge

SYS_Diagnostic-CPU-XC

SYS_Gestion-Fichiers-SD

HMI_ (Interface Homme-Machine) :

HMI_Gestion-Alarmes

HMI_Textes-Dynamiques (pour ton template actuel !)

02_LIBRARIES/
└── CODESYS_V2/
    └── CUSTOM_BRUNO/
        ├── COM_EIP-Client-Eaton/
        │   └── Eaton_EIP_V12.lib  <-- (Nom original préservé)
        ├── CTRL_Piscine-Niveau/
        │   └── Filter_Level_Old.lib
        └── MATH_Scaling-Analog/
            └── Scale_4_20.lib
            
            
