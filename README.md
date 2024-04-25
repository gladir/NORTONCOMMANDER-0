# NORTONCOMMANDER-0
Clone du Norton Commander écrit en Pascal (Turbo Pascal ou Free Pascal)

![image](https://github.com/gladir/NORTONCOMMANDER-0/assets/11842176/79e3db12-9fbf-4989-91a8-0bdab195dda8)

<h2>Quoi de neuf</h2>

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
