# 💈 SalonApp — Application de Gestion de Salon de Coiffure pour Hommes

> Application mobile & web full-stack de gestion complète d'un salon de coiffure masculin.  
> Développée avec **Flutter · Laravel 11 · MySQL · REST API**

---

## 📱 Aperçu du projet

SalonApp est une solution digitale complète destinée aux salons de coiffure pour hommes.  
Elle permet la gestion des réservations, des coiffeurs, de la caisse et de l'administration — le tout depuis une interface mobile intuitive.

---

## 🎯 Fonctionnalités principales

### 👤 Client
- Inscription et connexion sécurisée
- Réservation en ligne avec choix du créneau horaire et du coiffeur
- Suivi de l'état de ses rendez-vous
- Historique des visites

### ✂️ Coiffeur
- Consultation de son planning du jour
- Gestion de ses disponibilités
- Suivi de ses rendez-vous assignés

### 🧾 Gérant
- Tableau de bord de l'activité du salon
- Gestion des coiffeurs (ajout, modification, désactivation)
- Suivi des rendez-vous de tous les clients
- Gestion de la caisse et des paiements

### 🔐 Administrateur
- Accès complet à toutes les fonctionnalités
- Gestion des comptes utilisateurs et des rôles
- Configuration générale de l'application

---

## 🛠️ Stack technique

| Couche | Technologie |
|---|---|
| Mobile | Flutter (Dart) |
| Backend | Laravel 11 (PHP) |
| Base de données | MySQL |
| Communication | REST API (JSON) |
| Authentification | Laravel Sanctum |
| Gestion de versions | Git & GitHub |

---

## 🗂️ Architecture du projet

```
salonapp/
├── mobile/          # Application Flutter
│   ├── lib/
│   │   ├── screens/ # Écrans par rôle
│   │   ├── models/  # Modèles de données
│   │   └── services/# Appels API
├── backend/         # API Laravel 11
│   ├── app/
│   │   ├── Http/Controllers/
│   │   ├── Models/
│   │   └── Middleware/
│   ├── routes/api.php
│   └── database/migrations/
```

---

## 🚀 Installation & lancement

### Prérequis
- Flutter SDK ≥ 3.x
- PHP ≥ 8.2
- Composer
- MySQL
- Git

### Backend (Laravel)

```bash
git clone https://github.com/TON_USERNAME/salonapp.git
cd salonapp/backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

### Mobile (Flutter)

```bash
cd salonapp/mobile
flutter pub get
flutter run
```

---

## 🔑 Comptes de démonstration

| Rôle | Email | Mot de passe |
|---|---|---|
| Admin | admin@salonapp.com | password |
| Gérant | gerant@salonapp.com | password |
| Coiffeur | coiffeur@salonapp.com | password |
| Client | client@salonapp.com | password |

---

## 📋 Statut du projet

| Module | Statut |
|---|---|
| Authentification & rôles | ✅ Terminé |
| Gestion des coiffeurs | ✅ Terminé |
| Réservations (RendezVous) | 🔄 En cours |
| Caisse & paiements | 🔄 En cours |
| Intégration Mobile Money | 🔜 Prévu (Wave, Orange Money, MTN MoMo) |
| Déploiement production | 🔜 Prévu |

---

## 👨‍💻 Développeur

**Non Joseph Junior**  
Développeur Full-Stack Flutter & Laravel  
📍 Douala, Cameroun  
📧 jnon200@yahoo.com  
📱 +237 699 831 392

---

## 📄 Licence

Ce projet est développé à des fins professionnelles et de démonstration.  
© 2025 Non Joseph Junior — Tous droits réservés.