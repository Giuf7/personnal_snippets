# Mes Snippets personnels (VS Code)

Ce dépôt contient ma collection personnelle de snippets (extraits de code) pour **VS Code**. Ils sont optimisés pour le développement Full Stack avec **Python**, **Flask**, **FastAPI** et **SQLAlchemy** (architecture découplée Routes/Controllers).

---

## Comment les installer ?

L'installation prend moins de 2 minutes. Suis ces étapes :

### 1. Ouvrir la configuration des snippets dans VS Code
* Ouvre ton éditeur VS Code.
* Utilise le raccourci clavier :
  * **Windows / Linux :** `Ctrl + Shift + P`
  * **Mac :** `Cmd + Shift + P`
* Dans la barre de recherche qui apparaît, tape : **`Snippets: Configure Snippets`** (ou *Configurer les extraits de code utilisateur*) et appuie sur `Entrée`.

### 2. Choisir le bon fichier
* **Pour les snippets Python (`tryex`, `flaskroute`, `flaskcontrol`, `sqlbase`) :** Tape `python` dans la liste et sélectionne `python.json`.
* **Pour les snippets globaux (`envsql`) :** Sélectionne `dotenv`.

### 3. Copier le code
* Remplace le contenu fichier qui vient de s'ouvrir.
* Copie et colle les blocs JSON de ce dépôt à l'intérieur des accolades.
* Sauvegarde le fichier (`Ctrl + S` ou `Cmd + S`).

---

## Comment les utiliser en codant ?

Ouvre n'importe quel fichier de code dans VS Code, tape l'un des préfixes ci-dessous et appuie sur **`Tab`** ou **`Entrée`** :

| Préfixe        | Description | Utilisation                      |
| :--------------| :----------------------------------------------| :----------------------------- |
| `tryex`        | Bloc `try / except` robuste                    | Gestion des erreurs en Python  |
| `main`         | Structure standard `if __name__ == '__main__'` | Lancement de script            |
| `sqlbase`      | Classe `DeclarativeBase`                       | Initialisation SQLAlchemy      |
| `flaskroute`   | Route Flask découplée                          | Dans le dossier `/routes`      |
| `flaskcontrol` | Controller pur avec session DB                 | Dans le dossier `/controllers` |
| `envsql`       | Chaîne de connexion MSSQL (SQL Server)         | Dans le fichier `.env`         |

> **Astuce :** Utilise la touche `Tab` pour naviguer instantanément entre les variables de chaque snippet pendant que tu écris !
