+++
title = "Javascript Web Storage Api"
date = 2018-08-08T18:18:18+02:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Web Storage API"]
categories = ["Javascript"]

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = "js.png"
caption = "Javascript Web Storage API: uso del localStorage per salvare i dati da una pagina web in modo persistente sul client"
preview = true

+++

In questo video vediamo come utilizzare l'API Javascript Web Storage che tutti i browser mettono a disposizione del programmatore. La caratteristica fondamentale di questa API è quella di fornire un modo per salvare dei dati in un archivio del tipo chiave-valore. Esistono due tipi di storage (entrambi del tipo chiave-valore) a cui si può accedere con la Web Storage API:

- sessionStorage: i dati salvati permangono solo per la sessione di navigazione corrente.
- localStorage: i dati salvati non hanno un expire time associato e permangono anche nel caso di chiusura e riapertura del browser.

l'oggetto localStorage della Web Storage API consente quindi di accedere a un oggetto Storage che è un archivio chiave-valore (simile a un oggetto javascript ma con la particolarità che chiavi e valori possono essere solo stringhe).

Sarà importante quindi nel caso si voglia salvare un oggetto Javascript, convertirlo preventivamente in JSON utilizzando JSON.stringify e al momento del caricamento dallo storage ripristinare l'oggetto utilizzando JSON.parse.

## RIFERIMENTI

🌐 - Mozilla MDN Web Storage API Documentation- https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API

{{< youtube Srcl4MX3uCM >}}
