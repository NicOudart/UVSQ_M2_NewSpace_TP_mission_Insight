# Etape 5 : Réponses aux questions

* **Question 1 :** L'instrument SEIS fait partie de la mission Insight de la NASA.

* **Question 2 :** L'objectif scientifique de la mission est d'étudier la structure interne de Mars à travers des mesures géophysiques, notamment sismiques, afin de mieux comprendre sa formation et son évolution.

* **Question 3 :** La plateforme est un atterrisseur à la surface de Mars.

* **Question 4 :** La plateforme contient les instruments SEIS (sismomètre, direct-sensing, passif), HP3 (thermomètre, direct-sensing, potentiellement actif ou passif), RISE (mesure de la rotation grâce au canal de communication X-band, remote-sensing, passif si purement récepteur).

* **Question 5 :** SEIS contient un sismomètre Very Broad Band (VBB) et un sismomètre Short Period (SP).

* **Question 6 :** L'institut responsable de développement de SEIS est le CNES. P. Lognonné est le Principal Investigator (PI) de l'instrument.

* **Question 7 :** Pour couvrir les gammes de fréquence des 3 types de séismes mentionnés, la plage de fréquence de SEIS doit être 0.01-5 Hz.

* **Question 8 :** Il faut au moins 10 échantillons par seconde pour respecter le théorème de Shannon-Nyquist.

* **Question 9 :** 1 bit représente environ 3 µV.

* **Question 10 :** 111100001011110111000000

* **Question 11 :** La puissance reçue est de -128.62 dB, d'où un SNR = 41.38 dB. Ceci veut dire que la puissance du signal est plus de 10000X plus haute que celle du bruit. C'est donc un très bon SNR !

* **Question 12 :** Pour un débit de 63 bits/s, il faut une bande de fréquences de 4.58 Hz, ce qui est relativement faible comparé à la fréquence centrale du signal. Ceci parait donc plausible.

* **Question 14 :** Le signal est causal, il est aléatoire car visiblement bruité, et il est non stationnaire.

* **Question 15 :** La plage de fréquence après FFT sera de 0-10 Hz. La résolution du spectre sera de 1/1500 Hz.

* **Question 16 :** Il faut 256 échantillons pour la fenêtre glissante.

* **Question 17 :** L'overlap est de 128 échantillons.

* **Question 18 :** Il s'agit de lobes secondaires, un artéfact lié au fait que nous n'avons pas fenêtré ce signal avant STFT.

* **Question 19 :** Pour favoriser la résolution, il vaut mieux choisir la fenêtre de Hamming.

* **Questions 20 et 21 :** Pour isoler les ondes de surface, il faut utiliser un filtre passe-bande de fréquences de coupure 0.01 et 0.1 Hz.