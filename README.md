# NORTONCOMMANDER-0
Clone du Norton Commander écrit en Pascal (Turbo Pascal ou Free Pascal)

![image](https://github.com/gladir/NORTONCOMMANDER-0/assets/11842176/79e3db12-9fbf-4989-91a8-0bdab195dda8)

![image](https://github.com/gladir/NORTONCOMMANDER-0/assets/11842176/7bbbbb42-094c-45f7-a794-120b831b8798)

<h2>Quoi de neuf</h2>

<h4>Version 1.0.9</h4>
<ul>
  <li>Ajout de traduction pour la langue danois et suédois.</li>
  <li>Ajout d'un visulisateur hexadécimal avec <kbd>F4</kbd> dans le visualisateur de fichier <kbd>F3</kbd></li>
  <li>Ajout du support du <kbd>PgUp</kbd> ou <kbd>PgDn</kbd> pour se déplacer dans le panneau de fichier courant.</li>
  <li>Ajout du paramètre «/LINES:» pour forcer un nombre de lignes d'affichage spécifique.</li>
</ul>

<h4>Version 1.0.8</h4>
<ul>
  <li>Ajout de traduction pour la langue espagnol.</li>
  <li>Support du <kbd>Ctrl</kbd>+<kbd>\</kbd> pour retourner au répertoire racine.</li>
  <li>Support du <kbd>Ctrl</kbd>+<kbd>\</kbd> pour retrourner au dossier parent dans la panneau de fichiers courant.</li>
</ul>

<h4>Version 1.0.7</h4>
<ul>
  <li>Ajout de traduction pour la langue italienne.</li>
  <li>Support du <kbd>Alt</kbd>+<kbd>F9</kbd> pour le passage en mode EGA avec 43 plutôt que 25 lignes de texte.</li>
  <li>Ajout du support de renommer ou déplacer avec la touche <kbd>F6</kbd></li>
</ul>

<h4>Version 1.0.6</h4>
<ul>
  <li>Ajout de la boite de dialogue d'historique de commande accessible via le raccourci clavier <kbd>Alt</kbd>+<kbd>F8</kbd>.</li>
  <li>Ajout des quelques traductions de langue allemande.</li>
</ul>


<h4>Version 1.0.5</h4>
<ul>
  <li>Restructuration du "Crée un répertoire" pour être plus conforme au Norton Commander (avec des messages francais ou anglais).</li>
</ul>

<h4>Version 1.0.4</h4>
<ul>
  <li>Restructuration des suppressions pour être plus conforme au Norton Commander.</li>
  <li>Transforme la boite de quitter le Norton Commander plus conviviale avec les boutons.</li>
  <li>Intégration du cadre d'application <a href="https://github.com/gladir/FRAMTEXT" target="_blank">FRAMTEXT</a> pour les boites de dialogues.</li>
</ul>

<h4>Version 1.0.3</h4>
<ul>
  <li>Ajout d'un historique de commande accessible avec les combinaisons de touche <kbd>Ctrl</kbd>+<kbd>E</kbd> et <kbd>Ctrl</kbd>+<kbd>X</kbd></li>
  <li>Correctif du <kbd>ESC</kbd> pour qu'il efface la commande plutot que de quitter le programme.</li>
  <li>Ajout du support du raccourci clavier <kbd>Ctrl</kbd>+<kbd>Y</kbd>.</li>
</ul>


<h4>Version 1.0.2</h4>
<ul>
  <li>Ajout du support des extensions contenu dans le fichier NC.EXT.</li>
  <li>Support du raccourci clavier <kbd>Ctrl</kbd>+<kbd>R</kbd> pour recharger le répertoire.</li>
</ul>

<h4>Version 1.0.1</h4>
<ul>
  <li>Ajout du support de menu (<kbd>F2</kbd>) contenu dans le fichier NC.MNU.</li>
</ul>

<h2>Langage humain</h3>

Pour changer la langue des commandes, vous devez fixer la valeur de la variable d'environnement LANGUAGE, par exemple, pour passer à l'allemand :

SET LANGUAGE=GR	
	
Sinon par l'italien :

SET LANGUAGE=IT

Egalement pour l'espagnol :

SET LANGUAGE=SP

Aussi pour le danois :

SET LANGUAGE=DK

Ou le suédois :

SET LANGUAGE=SE

Pour l'anglais :
	
SET LANGUAGE=EN

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler NC.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> NC.PAS</pre>

<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/NORTONCOMMANDER-0/blob/main/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/NORTONCOMMANDER-0/blob/main/LICENSE">MIT</a>.</li>
</ul>
