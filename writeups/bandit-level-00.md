Pega exactamente todo el siguiente bloque en el editor de GitHub (reemplazando el contenido actual). Está con el formato Markdown y con bloques de código para que se vea bien en GitHub.

# Bandit — Level 00 (Plantilla/Writeup)
**Fecha:** 2025-10-15  
**Autor:** DanielCRincon  
**Tags:** bandit, linux, beginners, ssh  
**Dificultad:** Muy fácil

## Objetivo
Acceder al reto / archivo objetivo del nivel 0 y obtener la contraseña para avanzar al siguiente nivel.

## Entorno
- OverTheWire — Bandit  
- Host: `bandit.labs.overthewire.org`  
- Puerto: `2220`  
- Usuario inicial: `bandit0`

## Conexión
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220

Pasos y Comandos

Conectar por SSH:

ssh bandit0@bandit.labs.overthewire.org -p 2220


Listar archivos del directorio:

ls -la


Salida observada (ejemplo):

-rw-r-----   1 bandit1 bandit0  438 Oct 14 09:25 readme


Leer el archivo readme:

cat readme

Resultado / Evidencia

Contraseña / flag obtenida: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

Observaciones

Qué aprendí: uso básico de ls y cat, permisos de archivos (nota que readme pertenece a bandit1 y tiene permisos -rw-r-----), y acceso SSH a la máquina de Bandit.

Problemas encontrados: ninguno relevante en este nivel.

Mitigación / Buenas prácticas (si aplica)

En entornos reales: no dejar archivos con contraseñas en texto plano; auditar permisos y monitorear accesos.
