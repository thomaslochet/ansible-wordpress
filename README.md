# Guide rapide : Mise en route du projet

1. **Configurer l'inventaire**
   - Ouvrir le fichier `hosts.ini` et ajouter l'adresse IP ou le nom des serveurs cibles.

2. **Adapter les variables si besoin**
   - Modifier les fichiers dans `defaults/` pour personnaliser les mots de passe, le nom de la base de données, etc.

3. **Lancer le déploiement**
   ```bash
   ansible-playbook -i hosts.ini playbook.yaml
   ```
   
4. **Accéder à WordPress**
   - Ouvrir un navigateur et se rendre à l'adresse du serveur.
