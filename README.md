# 🏢 Caso de Estudio: Infraestructura Tecnológica de Universidad Privada

## 📋 Descripción

Este repositorio documenta un caso real de cómo una universidad privada resolvió sus problemas críticos de infraestructura tecnológica.

## ⚠️ Problema Original

Una universidad privada enfrentaba:
- 📉 Disponibilidad del 85% (muchas caídas)
- 🐢 Tiempo de respuesta de 8-10 segundos
- 👥 Capacidad para solo 200 usuarios simultáneos
- 💾 200 GB de almacenamiento (casi lleno)
- 🔴 15-20 fallos por mes

## ✅ Solución Implementada

Se implementó una arquitectura escalable con:
- 4 Servidores Web con Load Balancer
- Base de Datos MySQL con replicación
- Almacenamiento Centralizado NAS
- Sistema de Backup 3-2-1
- Seguridad multicapa

## 📊 Resultados Conseguidos

| Métrica | Antes | Después |
|---------|-------|---------|
| **Disponibilidad** | 85% | 99.92% ↑ |
| **Usuarios** | 200 | 1,200 ↑ |
| **Tiempo Respuesta** | 8-10 seg | 1.8 seg ↓ |
| **Almacenamiento** | 200 GB | 1 TB ↑ |
| **Fallos/mes** | 15-20 | <1 ↓ |

## 📁 Estructura del Repositorio
