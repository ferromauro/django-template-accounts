# Progetto: django-template-accounts
Questo progetto è parte integrante del sito django-template.net.

Potete trovare la pagina relativa a questo progetto al seguente indirizzo: 

Se volete accedere al pannello di controllo dell'admin interface di Django dovete creare un utente 

amministratore con il comando di django:  `python manage.py createsuperuser`

## Requisiti
- Python 3.x
- DJango
- Crispy-Forms

## Sezioni: 
Le sezioni del sito principali presenti in questo progetto sono le seguenti:
- **signup**: permette la creazione di un nuovo utente
- **login**: permette all'utene di loggarsi
- **logout**: permette all'utente di disconnettersi
- **reset password**: permette di avviare il processo per il recupero della password

## Email Backend
Il progetto prevede di utilizzare il servizio di email backend offerto da Django per la fase di sviluppo:

EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'        

Per la fase di produzione sara necessario impostare un server SMTP.
