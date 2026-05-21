# Supports pédagogiques ENSM

Dépôt public des supports de TP pour les étudiants de l'École Nationale Supérieure Maritime (ENSM).

---

## Structure

```
Etudiants/
├── InstallOff/          — Installation pandapower & OpenFAST (NREL)
├── Logiciels&IDE&WSL/   — Outils & environnement de développement
│   ├── WSL_VSCode/      — Installation WSL + VS Code (Windows)
│   ├── Python/          — Dépendances Python pour le post-traitement
│   └── OpenFOAM/        — Guide d'installation OpenFOAM 2412
├── MecaFlux/            — Mécanique des fluides numérique (OpenFOAM)
├── TenueMer/            — Tenue à la mer : Capytaine & Nemoh V3
└── scripts/             — Scripts utilitaires
```

---

## Modules disponibles

| Module | Description | Documentation |
|--------|-------------|---------------|
| **MecaFlux** | CFD avec OpenFOAM 2412 — TP Poiseuille | [MecaFlux/README.md](MecaFlux/README.md) |
| **TenueMer** | Tenue à la mer — Capytaine & Nemoh V3 | *(en préparation)* |
| **InstallOff** | Éolien offshore — pandapower & OpenFAST | *(en préparation)* |

---

## Mise en place de l'environnement

### 1. WSL + VS Code (Windows)

→ [`Logiciels&IDE&WSL/WSL_VSCode/Install_VSCode_WSL.md`](Logiciels%26IDE%26WSL/WSL_VSCode/Install_VSCode_WSL.md)

### 2. Dépendances Python

```bash
bash Logiciels\&IDE\&WSL/Python/install_python_deps.sh
```

→ [`Logiciels&IDE&WSL/Python/Install_Python_Deps.md`](Logiciels%26IDE%26WSL/Python/Install_Python_Deps.md)

### 3. OpenFOAM 2412

```bash
bash Logiciels\&IDE\&WSL/OpenFOAM/install_openfoam2412.sh
```

→ [`Logiciels&IDE&WSL/OpenFOAM/Install_OpenFoam2412.md`](Logiciels%26IDE%26WSL/OpenFOAM/Install_OpenFoam2412.md)

---

## Démarrage rapide — TP Poiseuille

```bash
git clone https://github.com/ChrisVhk/Etudiants
cd Etudiants/MecaFlux/Poiseuille
bash tp_poiseuille.sh all
```
