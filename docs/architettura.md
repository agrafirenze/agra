# ARCHITETTURA DEL PROGETTO - AGRA

## Obiettivo

Realizzare una piattaforma semplice, elegante e scalabile per la scoperta e la prenotazione di esperienze autentiche nel mondo rurale.

L'architettura del progetto deve permettere di aggiungere nuove funzionalità senza dover ricostruire il sito.

---

# Struttura generale del sito

Home

↓

Esperienze

↓

Pagina esperienza

↓

Prenotazione

↓

Conferma

---

# Pagine del sito

## Home

La homepage rappresenta il punto di ingresso principale.

Obiettivi:

- raccontare il brand
- trasmettere fiducia
- mostrare le esperienze in evidenza
- guidare l'utente verso la scoperta delle esperienze

---

## Esperienze

Pagina che raccoglie tutte le esperienze disponibili.

Ogni esperienza è rappresentata da una card.

Ogni card contiene:

- immagine
- titolo
- data
- luogo
- breve descrizione
- prezzo
- pulsante "Scopri"

---

## Pagina esperienza

Ogni esperienza possiede una pagina dedicata.

La pagina contiene:

- copertina
- galleria immagini
- descrizione completa
- programma
- informazioni utili
- luogo
- azienda ospitante
- prezzo
- posti disponibili
- FAQ
- pulsante di prenotazione

---

## Prenotazione

Il pulsante "Prenota" reindirizza al modulo Tally dedicato a quella specifica esperienza.

Tally raccoglie automaticamente i dati dell'utente.

---

## Conferma

Dopo la compilazione del modulo, l'utente visualizza una pagina di conferma e riceve le comunicazioni previste.

---

# Gestione delle esperienze

Le esperienze dovranno essere facilmente aggiornabili.

L'obiettivo è evitare modifiche manuali al codice ogni volta che viene aggiunto un nuovo evento.

In futuro le informazioni saranno recuperate automaticamente da Google Sheets o da un database dedicato.

---

# Gestione delle prenotazioni

Le prenotazioni saranno raccolte tramite Tally.

I dati confluiranno automaticamente in Google Sheets.

Successivamente potranno essere integrati con automazioni aggiuntive.

---

# Scalabilità

Il progetto deve essere progettato per consentire in futuro l'aggiunta di:

- ricerca esperienze
- filtri
- categorie
- area partner
- dashboard amministrativa
- pagamenti online
- recensioni
- newsletter
- autenticazione utenti
- autenticazione aziende

senza modificare la struttura principale del sito.

---

# Principi di sviluppo

Il progetto deve essere:

- modulare
- facilmente manutenibile
- responsive
- veloce
- accessibile
- SEO friendly

---

# Filosofia

Il sito non deve essere progettato come un semplice catalogo eventi.

Ogni esperienza deve raccontare una storia.

La navigazione deve trasmettere la sensazione di esplorare una collezione curata di esperienze autentiche.

L'obiettivo principale è ispirare l'utente prima ancora di portarlo alla prenotazione.
