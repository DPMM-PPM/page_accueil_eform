# accueil_eform
Page d'accueil EFORM
EFORM Intradef

Ce dépôt contient les éléménts constiuant la page d'accueil de la plateforme d'enseignement à distance du Ministère des Armées.
Comment utiliser ce dépôt

    Téléchargez ou clonez ce dépôt sur votre ordinateur.
	https://github.com/vincent-sayah/accueil_eform.git
    Ouvrez le fichier index.html dans votre navigateur web préféré.


Comment ajouter une tuile

Pour ajouter une tuile, suivez ces étapes :

    Ajoutez une nouvelle div avec la classe tile dans la section main-content.
    Ajoutez une div avec la classe card dans la div tile.
    Ajoutez une image avec la classe card-img-top dans la div card. L'image doit être au format PNG et de dimension 500x500 px. Elle doit être placée dans le répertoire images.
    Ajoutez une div avec la classe card-body dans la div card.
    Ajoutez un lien avec la classe card-title dans la div card-body.

Exemple de code pour l'ajout d'une tuile :

 <!-- Tuile  -->
<div class="col-lg-3 col-md-6 col-12 tile">
   <div class="card">
       <a href="https://example.com" target="_blank">
           <img src="images/example.png" class="card-img-top" alt="Example">
           <div class="card-body">
               <h5 class="card-title">Example</h5>
           </div>
       </a>
   </div>
</div>

Comment ajouter une carte

Pour ajouter une carte, suivez ces étapes :

    Ajoutez une nouvelle div avec la classe card-laterale dans la section sidebar.
    Ajoutez une image avec la classe card-img-top dans la div card-laterale. L'image doit être au format PNG et de dimension 500x500 px. Elle doit être placée dans le répertoire images.
    Ajoutez une div avec la classe card-body dans la div card-laterale.
    Ajoutez un lien avec la classe card-title dans la div card-body.

Exemple de code pour l'ajout d'une carte :

<!-- Carte -->
<div class="col-lg-6 col-md-12 col-12">
   <div class="card-laterale">
       <a href="https://example.com" target="_blank">
           <img src="images/example.png" class="card-img-top" alt="Example">
           <div class="card-body">
               <h5 class="card-title">Example</h5>
           </div>
       </a>
   </div>
</div>

