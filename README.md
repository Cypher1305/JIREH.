# JIREH.

Créer un espace numérique de dons et d’acquisitions d’articles à vocation caritative

---

## 🤝 Notre méthode de travail

- **Les tâches sont créées sous forme d’issues** (par le scrum master [Cypher1305](https://github.com/Cypher1305))
- Chaque Contributeur **s’attribue une issue** ou en reçoit une
- Une branche est **créée à partir de `dev`** pour chaque issue
- Les messages de commit doivent référencer l’ID de l’issue
- Une **pull request** (PR) est faite vers `dev`
- Une fois la PR acceptée, **la branche est supprimée**

---

## 🗂️ Branches principales

| Branche | Usage |
|---------|-------|
| `main` | Version stable, prête pour production |
| `dev` | Base de développement (toutes les fonctionnalités convergent ici) |

---

## 🌱 Nomenclature des branches

```bash
Type/XX/#num-titre-en-kebab-case
```
| Préfixe     | Quand l’utiliser                    |
| ----------- | ----------------------------------- |
| `Feature/`  | Nouvelle fonctionnalité             |
| `Hotfix/`   | Correction de bug                   |
| `Refactor/` | Nettoyage ou réorganisation du code |

- XX = initiales du contributeur
- #num = numéro de l’issue GitHub

Exemples :

    Feature/BY/#12-ajout-formulaire-orientation

    Hotfix/KY/#16-fix-bug-scroll

    Refactor/GY/#20-clean-user-model
---

#### 🛠 Étapes de contribution

1. Cloner le repo sur `dev`
```bash
git clone https://github.com/Cypher1305/.git
cd votre-projet

```
2. 
3. 
