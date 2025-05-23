# HITO 1:

## ✅ 1. Crear y configurar la máquina virtual (VirtualBox)

Se creó la VM llamada **hola2** con Debian 64 bits y 8 GB de RAM. 

* **Sistema > Procesador** → asignar 3 CPUs si tienes 4 reales.
* **Pantalla > Video RAM** → subir a 64 MB mínimo.
* **Red**: NAT 
* **Almacenamiento**: Se puede agregar una ISO de Debian



---

## ✅ 2. Instalar paquetes base (build-essential, wget, etc.)

Desde tu terminal en Debian:

```bash
sudo apt update
sudo apt install build-essential wget curl vim git bison gawk texinfo
```

También útiles:

```bash
sudo apt install zlib1g-dev libgmp-dev libmpfr-dev libmpc-dev
```

---

## ✅ 3. Crear estructura de directorios `/mnt/lfs`, `/sources`, `/tools`

```bash
sudo mkdir -pv /mnt/lfs
sudo mkdir -v /mnt/lfs/sources
sudo mkdir -v /mnt/lfs/tools
```





---

## ✅ 4. Verificar conectividad y entorno limpio

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



