# Naruto Chronicles – Base de données

Bienvenue sur le dépôt **Naruto Chronicles – Base de données**, qui contient toutes les images et fichiers JSON utilisés par le site :  
[https://naruto-chronicles.web.app](https://naruto-chronicles.web.app)

---

## Présentation

Ce dépôt sert de **bibliothèque centralisée** pour le site Naruto Chronicles.  
Il contient :  

- Des images pour les **personnages**, les **démons** et les **innovations**.  
- Des fichiers **JSON** référençant ces images pour être utilisés directement dans le site.

Ainsi, le site peut charger les images dynamiquement via les liens vers ce dépôt, sans stocker les fichiers en local.

---

## Exemple d'utilisation

Lien brut vers une image :  

https://raw.githubusercontent.com/TON-USER/nom-du-repo/main/images/personnages/naruto.png

Exemple JSON utilisable directement :  

```json
{
  "nom": "Naruto Uzumaki",
  "image": "https://raw.githubusercontent.com/TON-USER/nom-du-repo/main/images/personnages/naruto.png",
}
```

## Auteur

Développé et maintenu par **Emilien Olivarez** – Étudiant en Bac Pro CIEL (ex-SN)  
Lycée Louis de Cormontaigne, Metz

---

## Licence

Ce projet est sous licence **Apache 2.0**.  
Tu peux :  
- utiliser les images et données librement,  
- les modifier,  
- les distribuer,  
- même à usage commercial,  
tant que tu respectes les conditions de la [licence Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

