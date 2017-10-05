---
title: Servicio Clientes
tags: [getting_started]
keywords: release notes, announcements, what's new, new features
last_updated: July 3, 2016
summary: "Test"
sidebar: mydoc_sidebar
permalink: mydoc_rest.html
folder: mydoc
---

## GET

Devuelve la lista de todos los clientes

### Request

```yamll
GET /api/Clientes
```

### Responses
```yamll
<table>
<tr>
<td><strong>Código</strong></td>
<td><strong>Descripción</strong></td>
</tr>
<tr>
<td>200</td>
<td>OK</td>
</tr>
</table>
```

## POST
Crea un nuevo cliente

### Request
```yamll
POST /api/Clientes
```

### Parámetros
Se debe especificar un objeto de tipo Cliente con la siguiente estructura:
```yamll
{
  "Nombre": "Cliente 1",
  "Dirección": "zona 4",
  "NIT": "7366489-7"
}
```

### Responses
```yamll
Código Descripción
-------- ------
200 OK
400 Bad Request
```

## GET
Devuelve un cliente específico

###Request
```yamll
GET /api/Clientes/{id}
```

### Parámetros
Se debe especificar el ID del cliente que se desea consultar

```yamll
Nombre | Tipo | 
-- | --
*id| integer | 
```
### Responses
```yamll
Codigo | Descripción | 
-- | --
200| OK | 
404| Not Found |
```

## PUT
Permite modificar un cliente específico.

###Request
```yamll
PUT /api/Clientes/{id}
```

### Parámetros
Se debe especificar el ID del cliente que se desea consultar

```yamll
Nombre | Tipo | 
-- | --
*id| integer | 
cliente| cliente
```
### Responses
```yamll
Codigo | Descripción | 
-- | --
200| OK | 
400| Bad Request |
404| Not Found |
```

## DELETE
Permite eliminar un cliente específico.

###Request
```yamll
DELETE /api/Clientes/{id}
```

### Parámetros
Se debe especificar el ID del cliente que se desea eliminar

```yamll
Nombre | Tipo | 
-- | --
*id| integer | 
```

### Responses
```yamll
Codigo | Descripción | 
-- | --
204| No Content | 
404| Not Found |
```
