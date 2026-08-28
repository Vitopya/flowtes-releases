# Flowtes - telechargements

Depot de distribution : il ne contient que les binaires publies et les
artefacts de mise a jour signes de [Flowtes](https://github.com/Vitopya/perso_app_flowtes)
(notes en blocs + Kanban intelligent, local-first).

## Installer

Derniere version : [Releases](https://github.com/Vitopya/flowtes-releases/releases/latest)

- **Windows** : `Flowtes_x.y.z_x64-setup.exe`
- **macOS Apple Silicon** : `Flowtes_x.y.z_aarch64.dmg`
- **macOS Intel** : `Flowtes_x.y.z_x64.dmg`

Les binaires ne sont pas signes par un certificat editeur : Windows SmartScreen
et Gatekeeper affichent un avertissement au premier lancement.

## Mises a jour

L'application verifie `latest.json` a chaque demarrage. Chaque artefact est signe
avec la cle minisign du projet ; l'app refuse d'installer une mise a jour dont la
signature ne correspond pas.
