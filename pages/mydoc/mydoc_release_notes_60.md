---
title: Servicio Tipo de Cambio 
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 16, 2016
summary: "Servicio Web creado por el Banco de Guatemala que devuelve el Tipo de cambio en moneda extranjera"
sidebar: mydoc_sidebar
permalink: mydoc_release_notes_60.html
folder: mydoc
---

## Nombre de operación

TipoCambioDia

## Descripción

Devuelve el cambio del día en dólares.

## URL

https://www.banguat.gob.gt/variables/ws/TipoCambio.asmx

## Response

```yamll
<string xmlns="http://tempuri.org/">
<?xml version="1.0" encoding="utf-8"?> <InfoVariable> <CambioDolar> <VarDolar> <fecha>05/10/2017</fecha> <referencia>7.34192</referencia> </VarDolar> </CambioDolar> <TotalItems>1</TotalItems> </InfoVariable>
</string>
```

