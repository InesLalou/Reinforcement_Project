# Apprentissage par Renforcement pour la Manipulation Robotique

Ce projet explore l'utilisation de l'apprentissage par renforcement pour contrôler un bras robotique interagissant avec des cubes dans un environnement dynamique basé sur des événements. L'objectif est que le robot apprenne à reconnaître des séquences d'événements et à prendre des décisions pour agir efficacement dans son environnement.

## Objectif

Développer un système d'apprentissage par renforcement permettant à un bras robotique KUKA de :

- Identifier des situations dynamiques complexes dans un environnement piloté par des événements.
- Prendre des décisions séquentielles en réponse à ces événements.
- Atteindre et interagir avec la boîte cible parmi trois positionnées sur une table.

## Technologies utilisées

- **PyBullet** : Simulation physique du bras robotique.
- **Open the Chests (OtC)** : Environnement événementiel pour l'entraînement du robot. Créé par nos professeures Sao Mai Nguyen et Ivelina Stoyanova.
- **Stable-Baselines3 (SB3)**

  ## Modèles utilisés
- **PPO** (Proximal Policy Optimization) – Apprentissage bras robotique. 
- **DQN** (Deep Q-Network)
- **GRU** (Gated Recurrent Unit)

## Technologies utilisées

## Composants

- Environnement de simulation : bras KUKA + 3 coffres.
- Espace d'action : translation 3D limitée pour stabilité.
- Contrôle moteur : cinématique inverse.
- Récompense : basée sur la distance et le contact avec la cible.

## Instructions pour exécuter

1. **Installer les dépendances** :

```bash
pip install pybullet stable-baselines3 gym numpy matplotlib
```


## Equipe

Lily Daganaud, Candice Bouqin-Renoux, Sarah Garcia, Ines Lalou
