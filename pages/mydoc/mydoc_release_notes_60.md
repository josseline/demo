---
title: Servicio: Tipo de Cambio 
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

## Automated links using Markdown formatting

Instead of using YAML references to handle links, I've switched to a Markdown reference style approach. A links.html file iterates through the sidebar files and formats the content in the Markdown reference. You then just use Markdown syntax for the links. See [Links][mydoc_hyperlinks] for more details.

## Workflow maps

If you want to display a workflow map for a process, you can do so by adding some properties in your frontmatter. The workflow map helps guide users through a process. Both simple and complex workflow maps are available. For more details, see [Workflow maps][mydoc_workflow_maps].

## Upgrading

If you want to upgrade from an earlier version of the theme, I recommend that you download the new theme and copy of your Markdown files into the new theme. You'll then need to make adjustments to your page frontmatter, to the sidebar table of contents, links, image references, and alert references. In short, there's no easy upgrade path. But all of this won't take too long if you don't have mountains of content.

{% include links.html %}
