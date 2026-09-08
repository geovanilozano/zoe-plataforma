<h1 align="center">🗂️ ZOE — Núcleo de gestión</h1>

<p align="center">
  <a href="https://geovanilozano.github.io/zoe-plataforma/"><img src="https://img.shields.io/badge/leer-geovanilozano.github.io%2Fzoe--plataforma-1f6feb?style=flat-square&logo=github"/></a>
  <img src="https://img.shields.io/badge/deploy-GitHub%20Pages-222?style=flat-square&logo=githubpages"/>
  <img src="https://img.shields.io/badge/licencia-propietaria-b45309?style=flat-square"/>
</p>

> Documento técnico del **núcleo de gestión** de ZOE: cómo se aísla la
> información de cada organización, cómo viaja un trabajo desde el prospecto
> hasta el cobro, y con qué reglas se calculan las retenciones colombianas, el
> costo real de un proyecto y el reparto entre socios.

## 📖 Leer el documento

**[geovanilozano.github.io/zoe-plataforma](https://geovanilozano.github.io/zoe-plataforma/)**

Una sola página autocontenida: sin dependencias, sin build y sin JavaScript de
terceros. Se abre igual desde el navegador que desde un `file://` local.

## 🗂️ Qué contiene

| Sección | De qué trata |
|---|---|
| **Qué cubre este documento** | El alcance, dicho de frente |
| **Multi-tenant y unidades de negocio** | Aislamiento por organización y división interna |
| **Del prospecto al cobro** | Cliente, interacciones, cotización y conversión a proyecto |
| **Fases, entregables y tareas** | Tres niveles con estados propios, y por qué |
| **El dinero y su imputación** | Cobros, gastos, traspasos y a qué factura va cada giro |
| **Motor tributario** | Retefuente, ICA e IVA: tarifas por condición del tercero y UVT por año |
| **Presupuesto y costo real** | Cómo se calcula la utilidad de un proyecto en curso sin mentir |
| **Reparto entre socios** | Participaciones, tolerancias y el asiento que genera |
| **Auditoría y borrado** | Rastro de cambios y borrado que no destruye |
| **Decisiones que costaron caro** | Los errores que dejaron una regla escrita en el esquema |
| **Arquitectura y ejecución** | Monorepo, stack y cobertura de pruebas |

## ⚖️ Alcance

La plataforma tiene más módulos de los que este documento describe. Cubre el
núcleo de gestión —organizaciones, proyectos, dinero, tributario, costos y
reparto— y deja fuera de forma deliberada los módulos de producción de
contenido. Se dice en la primera sección del propio documento, para que nadie
lo lea como el inventario completo del sistema.

## 🏗️ Estructura

```
index.html    Documento completo (HTML + CSS embebidos)
robots.txt    Reglas de indexación
.nojekyll     Publica el HTML tal cual, sin procesar con Jekyll
```

## 📄 Licencia

**Material propietario. Todos los derechos reservados.**

Este documento describe la arquitectura de una plataforma privada. No se
concede licencia de uso, copia, modificación ni redistribución.

---

<p align="center">
  <sub>Escrito por <a href="https://github.com/geovanilozano">Geovani Lozano</a></sub>
</p>
