# Ordre_execution_des_Hooks_in_Cucumber

- Ordonner les Hooks à exécuter dans une séquence particulière est facile à faire
- @Before(order = int) : Ceci s’exécute dans l’ordre incrémentiel, signifie que la valeur 0 s’exécuterait en premier et 1 serait après 0.
- @After(order = int) : Ceci fonctionne dans l’ordre décrémentiel, signifie apposite de @Before. La valeur 1 s’exécuterait en premier et 0 après 1.

## l'architecture de notre exemple:
![image](https://user-images.githubusercontent.com/7100940/213881797-fb812a22-f554-41a1-bdaa-b8b90310998d.png)

## le ficher Hooks.java
![image](https://user-images.githubusercontent.com/7100940/213882081-a5adc69e-99ba-4a3a-8436-bbe5b8cf2ed5.png)

## le Résultat
![image](https://user-images.githubusercontent.com/7100940/213882133-0317ed40-fc9e-4aae-827c-a2c608bee645.png)
