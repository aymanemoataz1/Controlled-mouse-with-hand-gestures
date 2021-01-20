# Controlled-mouse-with-hand-gestures
Curseur de souris contrôlé par le geste de la main avec webcam.

Cette approche de la reconnaissance des gestes de la main est basée sur la vision, qui utilise des techniques de traitement de l'image et des entrées provenant d'une webcam informatique. La trame d'entrée capturée par la webcam est traitée en trois parties

--détection de la peau (à l'aide d'un modèle d'histogramme)

--détection des gestes de la main (par extraction des contours, détection de la coque convexe)

--Intégrer la fonction souris (en utilisant la bibliothèque Pyautogui)

