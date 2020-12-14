+++
title = "Servlet Java: Autenticazione Utente"
date = 2018-03-27T15:30:28+02:00
draft = false

summary="Gestire l'autenticazione utente è fondamentale in una vasta gamma di applicazioni. In questo post (con video) vedremo come affrontare la problematica utilizzando JSP e le Servlet."

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

## Il problema dell'autenticazione utente

Quando si realizza una applicazione dove saranno gestiti i dati privati degli utenti (o in ogni caso sarà necessario avere delle risorse riservate ai singoli utenti, come ad esempio i profili di un social network) risultarà fondamentale associare all'utente che si collega all'applicazione un utente "informatico" ovvero una entità logica presente nell'applicazione e a cui saranno associati alcuni dati presenti in essa.

Il processo di autenticazione fa proprio questo, mappa una persona su di una entità logica che lo rappresenterà poi mentre utilizza il sistema.

### SERIE: Gestione dell'autenticazione con Servlet e JSP

- [PARTE 1]({{< relref "/post/servlet-jsp-java-autenticazione-utente/index.md" >}})
- [PARTE 2]({{< relref "/post/servlet-jsp-java-autenticazione-utente-2/index.md" >}})

{{< youtube FMCkS3sAVmM >}}
