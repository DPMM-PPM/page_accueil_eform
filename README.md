# Page accueil EFORM Intradef

Ce dépôt contient les éléménts constituant la page d'accueil de la plateforme d'enseignement à distance EFORM.

## Instructions d'utilisation

Cloner ou télécharger le dépôt

```bash
git clone https://github.com/vincent-sayah/accueil_eform.git
cd accueil_eform
```

## Visualiser la page d'accueil

cliquer sur le fichier index.html


## Ajouter une tuile d'accès à un centre ou école de formation

Pour ajouter une tuile, suivez ces étapes :

- Ajoutez une nouvelle div avec la classe tile dans la section main-content.
- Ajoutez une div avec la classe card dans la div tile.
- Ajouter une balise href vers le lien du lms de formation.
- Ajoutez une image avec la classe card-img-top dans la div card. L'image doit être au format PNG et de dimension 500x500 px. Elle doit être placée dans le répertoire "images".
- Ajoutez une div avec la classe card-body dans la div card.
- Ajoutez un titre avec la classe card-title dans la div card-body.

Exemple de code pour l'ajout d'une tuile :

```bash
 <!-- Tuile  -->
<div class="col-lg-3 col-md-6 col-12 tile">
   <div class="card">
       <a href="https://<lien vers le centre de formation>" target="_blank">
           <img src="images/example.png" class="card-img-top" alt="Example">
           <div class="card-body">
               <h5 class="card-title">Example</h5>
           </div>
       </a>
   </div>
</div>
```

## Ajouter une tuile d'accès à un outil ou service de l'intradef

Pour ajouter une tuile, suivez ces étapes :

- Ajoutez une nouvelle div avec la classe card-laterale dans la section sidebar.
- Ajouter une balise href vers le lien du service.
- Ajoutez une image avec la classe card-img-top dans la div card-laterale. L'image doit être au format PNG et de dimension 500x500 px. Elle doit être placée dans le répertoire "images".
- Ajoutez une div avec la classe card-body dans la div card-laterale.
- Ajoutez un titre avec la classe card-title dans la div card-body.

Exemple de code pour l'ajout d'une tuile :

```bash
<!-- Carte -->
<div class="col-lg-6 col-md-12 col-12">
   <div class="card-laterale">
       <a href="https://<lien vers outil>" target="_blank">
           <img src="images/example.png" class="card-img-top" alt="Example">
           <div class="card-body">
               <h5 class="card-title">Example</h5>
           </div>
       </a>
   </div>
</div>
```

## Envoyer ou uploader votre nouvelle page d'accueil à votre hébergeur ou centre d'infogérence.
