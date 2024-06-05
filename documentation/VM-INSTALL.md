# Installation Kali Linux

Si vous êtes sur Windows et que vous voulez vous lancez dans la cybersécurité vous serez pratiquement obligé de passé par linux !

Nous allons voir comment installer un environnement de travail pour faire des tests de sécurité.

Ici, la distribution que nous allons intaller est **Kali Linux**. C'est une distribution basé sur debian qui a déjà énormément d'outils préinstaller sur le système ! C'est un système léger et facile à déployer !

### Téléchargement et installation

Pour ce faire rendez-vous sur le site de [Kali Linux :](https://www.kali.org/)

<img src="images/telechargement2.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Vous pouvez cliquez sur le bouton **Download** qui vous amenera sur la page suivante :

<img src="images/telechargement3.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Vous pouvez constatez qu'il existe de nombreuse adaptation de Kali linux en fonction des différents sytemes mais celle qui va nous intéresser ici c'est la section **Virtual Machine**.

<img src="images/telechargement4.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

On peut ensuite selectionné la version classique et la télécharger !

Vous pouvez ensuite vous rendre sur le site de [VirtualBox](https://www.virtualbox.org/wiki/Downloads) le télécharger et l'installer.

Une fois lancé, voici ce que vous devriez obtenir :

<img src="images/telechargement5.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Cliquez ensuite sur "Ajouter".

<img src="images/telechargement6.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Selectionner l'image que vous venez de télécharger, puis sur ouvrir !

<img src="images/telechargement7.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Rendez-vous ensuite dans l'onglet configuration avant de lancer la machine virtuelle !

<img src="images/telechargement8.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

<img src="images/telechargement9.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Ajustez la la ram et le nombre de processeur que vous souhaitez allouez à votre machine virtuelle.

Vous pouvez ensuite démarer la machine virtuelle et si tout fonctionne bien vous devriez arrivé sur la page suivante :

<img src="images/telechargement10.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

> Attention : Le clavier est en qwerty il faut donc taper sur votre clavier "kqli" pour que cela marque "kali"

**User : kali**
**password : kali**

### Mettre le clavier en AZERTY

Tout d'abord pour corriger le problème de manière temporaire vous pouvez simplement tapez :

```bash
setxkbmap fr
```

<img src="images/telechargement11.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

> Comment faire pour le changer de manière permanente ?

On va reconfigurer le clavier avec :

```bash
dpkg-reconfigure keyboard-configuration
```

Vous devriez arriver sur cette interface :

<img src="images/telechargement12.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Selectionnez "Generic 105-key PC"

<img src="images/telechargement13.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Selectionnez "Other"

<img src="images/telechargement14.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Puis cherchez "French" dans la liste

<img src="images/telechargement15.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

Puis selectionnez "French (AZERTY)" et ensuite vous pouvez simplement suivre les screens !

<img src="images/telechargement16.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

<img src="images/telechargement17.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

<img src="images/telechargement18.png" style="border-radius:5px; box-shadow: 5px 5px 5px #888888;">

**Et voilà maintenant le clavier sera tout le temps en AZERTY ! Vous pouvez maintenant hacker votre première machine !**
