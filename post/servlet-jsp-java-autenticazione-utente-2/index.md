+++
title = "Servlet Java: Autenticazione Utente: Parte 2"
date = 2018-03-27T15:30:28+02:00
draft = false

summary="Gestire l'autenticazione utente è fondamentale in una vasta gamma di applicazioni. In questo secondo post della serie(con video), riprenderemo quanto visto nella seconda parte, aggiungendo la persistenza dei dati di autenticazione degli utenti su di un database Derby e implementeremo anche la gestione del processo di registrazione di un nuovo utente."

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['Java','Servlet','Web Applications']
categories = ['Programmazione Java']

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "java-auth.jpg"
caption = "Programmazione Java"


+++

## Gestione della registrazione utente

In questa lezione vediamo come implementare una servlet che effettui la registrazione utente ed una pagina JSP con
il form di registrazione. I controlli effettuati sono basici.

## Persistenza dei dati di login

I dati vengono salvati su di un database [Derby](https://db.apache.org/derby/).

### ESERCIZI PROPOSTI

- Fare in modo che i form di login e di registrazione tornino i messaggi di errore all'utente.

### SERIE: Gestione dell'autenticazione con Servlet e JSP

- [PARTE 1]({{< relref "/post/servlet-jsp-java-autenticazione-utente/index.md" >}})
- [PARTE 2]({{< relref "/post/servlet-jsp-java-autenticazione-utente-2/index.md" >}})

{{< youtube J6BDLfIPvLU >}}
