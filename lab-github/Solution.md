
##  les commandes  utiliser  pour faire le travail 

1. **Création d'une branche à partir d'une branche principale(master):**

    ```bash
    git branch BlogVersion2
    ```

2. **Passer à notre nouvelle branche:**

    ```bash
    git checkout BlogVersion2
    ```

3. **Après avoir apporté des modifications dans une nouvelle branche (BlogVersion2), puis push ces modifications:**

    ```bash
    git commit -m 'Blog Edited'

    git push origin BlogVersion2
    ```

4. **Après avoir appliqué ces modifications, nous passons à la branche principale et "merge" la nouvelle branche avec la branche principale.**

    ```bash
    git merge BlogVersion2

    ```
