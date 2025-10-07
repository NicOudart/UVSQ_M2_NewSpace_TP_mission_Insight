# Etape 2 : Acquisition des mesures par l'instrument

Dans la suite de l’article, P. Lognonné décrit les différents types de séismes qui étaient attendus sur Mars en 2019 :

|Extrait 4|
|:-|
|"[…] the most reliable seismological secondary data that could be extracted should be:|
|– travel times of body waves (in the short period range, 0.1–5 Hz)|
|– group and phase velocities of Rayleigh surface waves (in the long period range, 0.01–0.1 Hz)|
|– eigenfrequencies of spheroidal fundamental normal modes in the frequency range of 0.01–0.02 Hz."|

A partir de cet extrait, répondez aux questions suivantes :

* **Quelle doit être la plage de fréquences des capteurs de SEIS afin de pouvoir mesurer les 3 types séismes ?**

* **Quel doit être le nombre minimum d’échantillons acquis par seconde pour éviter le repliement de spectre ? **

Pour information : la valeur choisie par l’équipe SEIS est de 20 échantillons par seconde.

Dans son article, P. Lognonné décrit ensuite la conversion analogique-numérique des signaux mesurés par VBB (ADC = CAN en anglais) :

|Extrait 5|
|:-|
|"For the acquisition of the science channels a 24 bit sigma-delta ADC (AD7712) has been chosen […]|
|Full scale range are ±25 Volt for the VBBs (for both velocity and position outputs)."|

En vous basant sur cet extrait, répondez aux questions suivantes :

* **Que représente ici 1 bit en termes de tension (arrondi au µV) ?**

* **Avec la convention du complément à 2, comment serait représenté en binaire une tension de -3V ?**

Pour répondre à cette dernière question, écrivez une fonction Python qui convertisse une tension entre -25 et 25 V en un binaire de 24 bits en respectant la convention du complément à 2.
Le nombre binaire pourra être retourné sous la forme d'un string.