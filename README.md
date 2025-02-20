# Recyclarr & Radarr - Configuration pour les Films 4K (Français Québécois)

Ce dépôt contient une configuration pour [Recyclarr](https://github.com/recyclarr/recyclarr) et [Radarr](https://radarr.video/), visant spécifiquement les films en 4K et en français québécois.

## 📜 Description

Cette configuration `.yml` permet d'améliorer la gestion et l'organisation des films 4K en langue française (Québec) dans Radarr. Elle est optimisée pour :

- **Une qualité vidéo 4K** avec les meilleures sources disponibles.
- **Des pistes audio en français québécois** en priorité.
- **Un tri et un filtrage efficace** pour éviter les doublons et garantir la meilleure version.
- **Une gestion automatique via Recyclarr**, synchronisant Radarr avec des listes de qualité prédéfinies.

## 📂 Contenu du Dépôt

- `recyclarr.yml` : Configuration principale pour Recyclarr et Radarr.
- `README.md` : Ce document expliquant le projet et son utilisation.
- `LICENSE` : Licence sous laquelle le projet est distribué.
- `prowlarr_indexer_config.jpg` : Image illustrative de la configuration de Prowlarr pour Radarr.
- `radarr_file_management_config.jpg` : Image illustrative de la configuration de Radarr.
- `radarr_indexer_config.jpg` : Image illustrative de la configuration de Radarr.

## 🔧 Installation & Utilisation

### Prérequis

- **Radarr** installé et configuré ([voir la documentation officielle](https://wiki.servarr.com/radarr))
- **Recyclarr** installé ([voir la documentation officielle](https://recyclarr.dev/))

### Configuration

1. **Télécharge et place le fichier `recyclarr.yml`** dans le répertoire de configuration de Recyclarr (ex. `~/.config/recyclarr/` sur Linux).
2. **Modifie les chemins et préférences** si nécessaire pour correspondre à ton installation.
3. **Lance une synchronisation** avec la commande :
   ```sh
   recyclarr sync
   ```
4. **Vérifie les logs** pour t'assurer que tout fonctionne correctement.

## 🚀 Fonctionnalités

- Sélection automatique des meilleures versions 4K
- Priorisation des versions avec audio FR-CA
- Exclusion des versions inutiles ou de qualité inférieure
- Mise à jour automatique des profils Radarr via Recyclarr

## 🤝 Contribution

Si tu souhaites améliorer cette configuration, n'hésite pas à forker le projet et proposer des améliorations via des pull requests !

## 📜 Licence

Ce projet est distribué sous la licence MIT. Tu peux l'utiliser et le modifier librement.

---

🔗 **Liens utiles** :

- [Recyclarr Documentation](https://recyclarr.dev/)
- [Trash Guides](https://trash-guides.info/)
- [Radarr Documentation](https://wiki.servarr.com/radarr)
