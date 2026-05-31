# Instalación de BalenaEtcher en Debian y derivadas

Herramienta de creación de medios USB booteables.

BalenaEtcher permite grabar imágenes ISO/IMG en dispositivos USB de forma segura y sencilla.

---

## 📌 Características

* Interfaz gráfica simple
* Verificación automática de escritura
* Soporte para ISO, IMG y ZIP
* Multiplataforma (Linux, Windows, macOS)

---

## ⚙️ Requisitos

* Debian 12/13 o derivados
* Acceso a internet
* Permisos de administrador (`sudo`)

---

## 📥 Instalación

### 1. Descargar BalenaEtcher

```bash
wget https://github.com/balena-io/etcher/releases/latest/download/balena-etcher_amd64.deb
```

---

### 2. Instalar el paquete

```bash
sudo dpkg -i balena-etcher_amd64.deb
```

Si aparecen errores de dependencias:

```bash
sudo apt --fix-broken install -y
```

---

### 3. Verificación de instalación

```bash
balena-etcher --version
```

---

## 🚀 Ejecución

Para abrir la aplicación:

```bash
balena-etcher
```

---

## 🧹 Limpieza (opcional)

Eliminar el instalador descargado:

```bash
rm balena-etcher_amd64.deb
```

---

## 🧠 Notas técnicas

* Se recomienda ejecutar como usuario normal.
* Evitar usar `sudo` salvo en casos necesarios.
* Verificar siempre la ISO antes de flashear.

---

## 📦 Estado del proyecto

✔ Estable
✔ Compatible con Debian
✔ Mantenido por Balena

---
