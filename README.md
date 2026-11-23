# TP13 – Sérialisation et Désérialisation en Java

##  Informations générales

- **Module :** Fondamentaux et Concepts Avancés de la Programmation Java
- **TP :** 13 – Sérialisation
- **Étudiant :** Hamza ID EL BAZ
- **Établissement :** ENS Marrakech – Université Cadi Ayyad
- **Année universitaire :** 2025–2026

---

##  Objectifs du TP

Ce TP a pour objectif de comprendre et de pratiquer les mécanismes de sérialisation et de désérialisation en Java.

Les notions étudiées sont :

- Comprendre la sérialisation et la désérialisation des objets.
- Utiliser `Serializable` et `Externalizable`.
- Manipuler `ObjectOutputStream` et `ObjectInputStream`.
- Comprendre le rôle de `serialVersionUID`.
- Utiliser le mot-clé `transient`.
- Implémenter `writeExternal()` et `readExternal()`.
- Gérer les exceptions avec `try-catch`.
- Utiliser le mécanisme `try-with-resources`.

---

##  Exercice 1 : Sérialisation et Désérialisation

### Description

Dans cet exercice, nous avons développé une application permettant de sauvegarder une liste d'employés dans un fichier binaire, puis de récupérer les objets enregistrés.

### Classes utilisées

- **Employee.java :** représente un employé avec son identifiant, son nom, son salaire et son mot de passe.
- **SerializationUtil.java :** contient les méthodes de sauvegarde et de récupération des employés.
- **Main.java :** permet de tester la sérialisation et la désérialisation.


<img width="1920" height="1080" alt="ex1" src="https://github.com/user-attachments/assets/ac3be4c1-9024-4bf3-b52d-e1f3b547678a" />




##  Conclusion

Ce TP m'a permis de comprendre comment sauvegarder des objets Java dans des fichiers et les récupérer ultérieurement.

J'ai également appris à différencier `Serializable` et `Externalizable`, à utiliser `transient` pour exclure certains attributs et à gérer les versions des données sérialisées.

Ces mécanismes sont utiles dans le développement d'applications Java nécessitant la sauvegarde et la restauration des données.

---

**Réalisé par : Hamza ID EL BAZ**

**ENS Marrakech – Université Cadi Ayyad**
