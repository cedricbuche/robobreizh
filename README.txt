------ RoboBreizh ------

Site web de l'équipe RoboBreizh pour la compétition Robocup@Home 2020.


Installation

Etapes
- Copier tout les fichiers du site (dossier RoboBreizh) sur le serveur
- Configurer la racine du site sur le fichier "src/en/index_en.html" (version anglaise) 
ou "src/fr/index_fr.html" (version française)
C'est bon votre site est prêt à être utilisé !


Utilisation 

Pour modifier un fichier rendez-vous dans le dossier src/ puis choisissez la langue de
la page que vous souhaitez modifier (il est conseillé de modifier à chaque fois les 2
langues en même temps) puis ouvrez le fichier correspondant à la page avec un éditeur 
de texte.

Quelques modifications simples :

- Ajout d'une image :
<figure>
	<img src="../../img/NomDeMonImage.jpg" style="max-width: 70%; height: auto;"> 
        <figcaption>  <!-- Légende si necessaire --> </figcaption>
</figure> 
/!\ Ne pas oublier de copier votre fichier .jpg dans le dossier /img/ du répertoire source

- Ajout d'une publication (fichier publications_*.html) :
<li>
        <h6> <Titre de la publication> </h6>
        <p>Authors : <!--Auteurs--> </p>
        <p><cite> <!--Ouvrage--> </cite></p>
        <p>Bibtex : <a href="../../publi/LienBibtexDeLaPublication.bib" class="text-white">.bib
	</a>  PDF : <a href="../../publi/LienPDFDeLaPublication" class="text-white">.pdf</a></p>
</li>
/!\ Ne pas oublier de copier ses fichiers .bib et .pdf dans le dossier /publi/ du répertoire source

- Ajout d'un texte : 
<p class="text-justify"> <!-- Votre texte ici --> </p>

- Ajout d'un lien :
<h5>Robocup@home : <a href="http://AdresseDuLien.com"> <!-- Nom du lien --> </a> </h5>


Pour plus d'informations :

Documentation Bootstrap : https://getbootstrap.com/docs/4.3/getting-started/introduction/
Dépot du template utilisé : https://github.com/BlackrockDigital/startbootstrap-freelancer
Licence du template : Licence MIT, Copyright 2013-2019 Blackrock Digital LLC