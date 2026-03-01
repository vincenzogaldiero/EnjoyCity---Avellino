🌍 EnjoyCity

Piattaforma web per la gestione e promozione di eventi locali.

EnjoyCity è un sistema web full-stack sviluppato in PHP e PostgreSQL che consente la consultazione, prenotazione e moderazione di eventi locali attraverso un’architettura multi-ruolo (utente anonimo, utente registrato, amministratore).

🎥 Demo

(Inserire qui eventuale link video o screenshot del progetto)

🚀 Funzionalità Principali
🔎 Consultazione eventi

Visualizzazione eventi con filtri per categoria

Ordinamento per data

Badge dinamici (annullato, archiviato)

Geolocalizzazione “Eventi vicino a me”

👤 Area Utente Registrato

Prenotazione eventi

Visualizzazione eventi prenotati con countdown

Gestione preferenze categorie tramite drag & drop

Proposta nuovi eventi (stato: in_attesa)

🛠 Area Amministratore

Dashboard di controllo

Moderazione eventi:

Approva

Rifiuta

Archivia

Annulla

Ripristina

Gestione completa del ciclo di vita dell’evento (LIVE, PENDING, DONE, CANCELLED, ARCHIVED)

🏗 Architettura del Sistema

L’applicazione è strutturata in modo modulare:

Logica Server-Side (PHP)

Separazione ruoli con controlli di sessione

Pattern PRG (Post-Redirect-Get)

Validazioni lato server

Prepared statements (pg_query_params)

Database (PostgreSQL)

Tabelle relazionali: utenti, eventi, categorie, prenotazioni, preferenze

Password hashate

Vincoli di integrità referenziale

Frontend

HTML5 / CSS3

JavaScript per:

Drag & Drop preferenze

Countdown eventi

Geolocalizzazione browser

Gestione dinamica UI

🔐 Sicurezza

Controllo accessi per ruolo

Protezione SQL Injection

Escape output per prevenzione XSS

Gestione sicura delle sessioni

Validazioni lato client e server

🖥 Tecnologie Utilizzate

PHP

PostgreSQL

HTML5 / CSS3

JavaScript

Apache (XAMPP)

Git & GitHub

👥 Team

Progetto sviluppato dal Gruppo 22:

Vincenzo Galdiero

Dana Iannaccone

Andrea Purcaro ()

🎓 Contesto Accademico

Progetto realizzato per il corso di Tecnologie Web
Università degli Studi di Salerno – DIEM
A.A. 2025/2026
