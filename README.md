# dark-mode toggle

**Navigateurs pris en charge chromium/chrome/edge & firefox**

(https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/light-dark)

Exemple d'inputs HTML de type radio permettant de forcer le mode d'affichage (automatique, sombre ou clair)

Dans l'exemple suivant, la couleur d'arrière-plan utilisée est #333 en mode sombre, ou #ccc en mode clair (ou en mode inconnu).

:root {

  color-scheme: light dark;
  
}

body {

  background-color: light-dark(#ccc, #333);
  
}
