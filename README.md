# Angular Secure Login (Fullstack Project)

A complete secure login system built with:
- **Frontend:** Angular 17 + Bootstrap
- **Backend:** Laravel 11 + Sanctum (REST API)
- **Auth:** Token-based authentication (Login, Register, Logout)
- **Database:** MySQL

## Structure
# Angular Secure Login (Fullstack Project)

angular-secure-login/
├── backend/   → Laravel API
└── frontend/  → Angular client

## Setup Instructions

**Backend (Laravel)**
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
Runs at http://127.0.0.1:8000

**Frontend (Angular)**
cd ../frontend
npm install
ng serve

Features
	•	Secure user authentication (JWT via Laravel Sanctum)
	•	Register / Login / Logout flow
	•	Auth guard for protected routes
	•	User dashboard with profile info
	•	Token stored securely in localStorage

Tech Stack
	•	Angular 17
	•	Laravel 11
	•	MySQL
	•	Sanctum
	•	Bootstrap 5
