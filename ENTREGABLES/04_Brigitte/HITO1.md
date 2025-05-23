# HITO 1:

## ✅ 1. Crear y configurar la máquina virtual (VirtualBox)

## 🗂 FASE 1 – Bitácora del Hito 1: Entorno Virtual Establecido (Responsable: Matías)

### 📌  *Resumen del hito*



> Se configuró una VM Debian con 8 GB de RAM, 2 CPUs, y 20 GB de disco. Se instalaron paquetes base como build-essential, wget, gawk, bison, etc. Se creó la estructura de directorios /mnt/lfs, /mnt/lfs/sources y /mnt/lfs/tools. Se configuró la variable $LFS en .bashrc.

---



---

bash
# Actualizar sistema
sudo apt update && sudo apt upgrade -y

# Instalar paquetes necesarios
sudo apt install build-essential bison gawk texinfo wget vim -y

# Crear estructura de carpetas
sudo mkdir -pv /mnt/lfs/{sources,tools}
sudo chmod -v a+wt /mnt/lfs/sources

# Crear usuario lfs
sudo groupadd lfs
sudo useradd -s /bin/bash -g lfs -m -k /dev/null lfs
sudo passwd lfs

# Establecer variable $LFS
echo 'export LFS=/mnt/lfs' >> ~/.bashrc
source ~/.bashrc






---

## ✅  Verificar conectividad y entorno limpio

### Verifica variables:

```bash
export LFS=/mnt/lfs
echo $LFS
```

Agregar `~/.bashrc` para persistencia:

```bash
echo 'export LFS=/mnt/lfs' >> ~/.bashrc
source ~/.bashrc
```

### Verificar conexión y entorno limpio:

```bash
ping -c 2 google.com         # Verifica red
df -h /mnt/lfs               # Espacio en /mnt/lfs
ls /mnt/lfs                  # Debe estar vacío o solo /sources y /tools
```

---

## 📸 Entrega esperada:

* Captura de pantalla mostrando:

  * El prompt del sistema con `/mnt/lfs` creado.
  * `df -h` con espacio.
  * `echo $LFS` con resultado correcto.
  * Algún log de `apt install` funcionando : https://github.com/Fx2048/DISTRO_PROJECT_SSOO/new/main/ENTREGABLES/04_Brigitte/Salida_terminal.md

![imagen](https://github.com/user-attachments/assets/e331e9f6-2714-4381-aacd-5463de5a7bc1)

---



---





---

### 🧩  *Errores encontrados y solución*

Este es crucial. Anota errores como:

* ❌ Permisos al crear carpetas → ✔ Solución: chmod -v a+wt /mnt/lfs/sources
* ❌ $LFS no persistía → ✔ Solución: Añadir a .bashrc correctamente y hacer source ~/.bashrc
* ❌ wget fallaba en una URL → ✔ Solución: Revisar conectividad y probar con curl


---



### ✍  *Fecha y responsable*



🗓 Fecha: 23/05/2025  
👤 Responsable: Matías


---

