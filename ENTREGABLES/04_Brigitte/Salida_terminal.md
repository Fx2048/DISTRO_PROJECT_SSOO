brigitte@vbox:~$ sudo apt update
[sudo] contraseña para brigitte: 
Obj:1 http://deb.debian.org/debian bookworm InRelease
Obj:2 http://security.debian.org/debian-security bookworm-security InRelease
Obj:3 http://deb.debian.org/debian bookworm-updates InRelease
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
Todos los paquetes están actualizados.
brigitte@vbox:~$ sudo apt install build-essential wget curl vim git bison gawk texinfo
Leyendo lista de paquetes... Hecho
Creando árbol de dependencias... Hecho
Leyendo la información de estado... Hecho
wget ya está en su versión más reciente (1.21.3-1+deb12u1).
Se instalarán los siguientes paquetes adicionales:
  binutils binutils-common binutils-x86-64-linux-gnu dpkg-dev fakeroot g++
  g++-12 gcc gcc-12 git-man libalgorithm-diff-perl libalgorithm-diff-xs-perl
  libalgorithm-merge-perl libasan8 libbinutils libc-dev-bin libc-devtools
  libc6-dev libcc1-0 libcrypt-dev libctf-nobfd0 libctf0 libdpkg-perl
  liberror-perl libfakeroot libfile-fcntllock-perl libgcc-12-dev libgprofng0
  libitm1 liblsan0 libnsl-dev libsigsegv2 libstdc++-12-dev
  libtext-unidecode-perl libtirpc-dev libtsan2 libubsan1 libxml-libxml-perl
  libxml-namespacesupport-perl libxml-sax-base-perl libxml-sax-expat-perl
  libxml-sax-perl linux-libc-dev m4 make manpages-dev patch rpcsvc-proto
  tex-common vim-runtime
Paquetes sugeridos:
  binutils-doc bison-doc debian-keyring g++-multilib g++-12-multilib
  gcc-12-doc gawk-doc gcc-multilib autoconf automake libtool flex gdb gcc-doc
  gcc-12-multilib gcc-12-locales git-daemon-run | git-daemon-sysvinit git-doc
  git-email git-gui gitk gitweb git-cvs git-mediawiki git-svn glibc-doc bzr
  libstdc++-12-doc libxml-sax-expatxs-perl m4-doc make-doc ed diffutils-doc
  debhelper texlive-base texlive-latex-base texlive-plain-generic
  texlive-fonts-recommended ctags vim-doc vim-scripts
Se instalarán los siguientes paquetes NUEVOS:
  binutils binutils-common binutils-x86-64-linux-gnu bison build-essential
  curl dpkg-dev fakeroot g++ g++-12 gawk gcc gcc-12 git git-man
  libalgorithm-diff-perl libalgorithm-diff-xs-perl libalgorithm-merge-perl
  libasan8 libbinutils libc-dev-bin libc-devtools libc6-dev libcc1-0
  libcrypt-dev libctf-nobfd0 libctf0 libdpkg-perl liberror-perl libfakeroot
  libfile-fcntllock-perl libgcc-12-dev libgprofng0 libitm1 liblsan0 libnsl-dev
  libsigsegv2 libstdc++-12-dev libtext-unidecode-perl libtirpc-dev libtsan2
  libubsan1 libxml-libxml-perl libxml-namespacesupport-perl
  libxml-sax-base-perl libxml-sax-expat-perl libxml-sax-perl linux-libc-dev m4
  make manpages-dev patch rpcsvc-proto tex-common texinfo vim vim-runtime
0 actualizados, 57 nuevos se instalarán, 0 para eliminar y 0 no actualizados.
Se necesita descargar 79,3 MB de archivos.
Se utilizarán 341 MB de espacio de disco adicional después de esta operación.
¿Desea continuar? [S/n] S
Des:1 http://deb.debian.org/debian bookworm/main amd64 libsigsegv2 amd64 2.14-1 [37,2 kB]
Des:2 http://deb.debian.org/debian bookworm/main amd64 gawk amd64 1:5.2.1-2 [673 kB]
Des:3 http://deb.debian.org/debian bookworm/main amd64 binutils-common amd64 2.40-2 [2.487 kB]
Des:4 http://deb.debian.org/debian bookworm/main amd64 libbinutils amd64 2.40-2 [572 kB]
Des:5 http://deb.debian.org/debian bookworm/main amd64 libctf-nobfd0 amd64 2.40-2 [153 kB]
Des:6 http://deb.debian.org/debian bookworm/main amd64 libctf0 amd64 2.40-2 [89,8 kB]
Des:7 http://deb.debian.org/debian bookworm/main amd64 libgprofng0 amd64 2.40-2 [812 kB]
Des:8 http://deb.debian.org/debian bookworm/main amd64 binutils-x86-64-linux-gnu amd64 2.40-2 [2.246 kB]
Des:9 http://deb.debian.org/debian bookworm/main amd64 binutils amd64 2.40-2 [65,0 kB]
Des:10 http://deb.debian.org/debian bookworm/main amd64 m4 amd64 1.4.19-3 [287 kB]
Des:11 http://deb.debian.org/debian bookworm/main amd64 bison amd64 2:3.8.2+dfsg-1+b1 [1.175 kB]
Des:12 http://deb.debian.org/debian bookworm/main amd64 libc-dev-bin amd64 2.36-9+deb12u10 [47,1 kB]
Des:13 http://deb.debian.org/debian bookworm/main amd64 linux-libc-dev amd64 6.1.137-1 [2.139 kB]
Des:14 http://deb.debian.org/debian bookworm/main amd64 libcrypt-dev amd64 1:4.4.33-2 [118 kB]
Des:15 http://deb.debian.org/debian bookworm/main amd64 libtirpc-dev amd64 1.3.3+ds-1 [191 kB]
Des:16 http://deb.debian.org/debian bookworm/main amd64 libnsl-dev amd64 1.3.0-2 [66,4 kB]
Des:17 http://deb.debian.org/debian bookworm/main amd64 rpcsvc-proto amd64 1.4.3-1 [63,3 kB]
Des:18 http://deb.debian.org/debian bookworm/main amd64 libc6-dev amd64 2.36-9+deb12u10 [1.903 kB]
Des:19 http://deb.debian.org/debian bookworm/main amd64 libcc1-0 amd64 12.2.0-14+deb12u1 [41,7 kB]
Des:20 http://deb.debian.org/debian bookworm/main amd64 libitm1 amd64 12.2.0-14+deb12u1 [26,1 kB]
Des:21 http://deb.debian.org/debian bookworm/main amd64 libasan8 amd64 12.2.0-14+deb12u1 [2.193 kB]
Des:22 http://deb.debian.org/debian bookworm/main amd64 liblsan0 amd64 12.2.0-14+deb12u1 [969 kB]
Des:23 http://deb.debian.org/debian bookworm/main amd64 libtsan2 amd64 12.2.0-14+deb12u1 [2.197 kB]
Des:24 http://deb.debian.org/debian bookworm/main amd64 libubsan1 amd64 12.2.0-14+deb12u1 [883 kB]
Des:25 http://deb.debian.org/debian bookworm/main amd64 libgcc-12-dev amd64 12.2.0-14+deb12u1 [2.437 kB]
Des:26 http://deb.debian.org/debian bookworm/main amd64 gcc-12 amd64 12.2.0-14+deb12u1 [19,3 MB]
Des:27 http://deb.debian.org/debian bookworm/main amd64 gcc amd64 4:12.2.0-3 [5.216 B]
Des:28 http://deb.debian.org/debian bookworm/main amd64 libstdc++-12-dev amd64 12.2.0-14+deb12u1 [2.047 kB]
Des:29 http://deb.debian.org/debian bookworm/main amd64 g++-12 amd64 12.2.0-14+deb12u1 [10,7 MB]
Des:30 http://deb.debian.org/debian bookworm/main amd64 g++ amd64 4:12.2.0-3 [1.356 B]
Des:31 http://deb.debian.org/debian bookworm/main amd64 make amd64 4.3-4.1 [396 kB]
Des:32 http://deb.debian.org/debian bookworm/main amd64 libdpkg-perl all 1.21.22 [603 kB]
Des:33 http://deb.debian.org/debian bookworm/main amd64 patch amd64 2.7.6-7 [128 kB]
Des:34 http://deb.debian.org/debian bookworm/main amd64 dpkg-dev all 1.21.22 [1.353 kB]
Des:35 http://deb.debian.org/debian bookworm/main amd64 build-essential amd64 12.9 [7.704 B]
Des:36 http://deb.debian.org/debian bookworm/main amd64 curl amd64 7.88.1-10+deb12u12 [315 kB]
Des:37 http://deb.debian.org/debian bookworm/main amd64 libfakeroot amd64 1.31-1.2 [28,3 kB]
Des:38 http://deb.debian.org/debian bookworm/main amd64 fakeroot amd64 1.31-1.2 [66,9 kB]
Des:39 http://deb.debian.org/debian bookworm/main amd64 liberror-perl all 0.17029-2 [29,0 kB]
Des:40 http://deb.debian.org/debian bookworm/main amd64 git-man all 1:2.39.5-0+deb12u2 [2.053 kB]
Des:41 http://deb.debian.org/debian bookworm/main amd64 git amd64 1:2.39.5-0+deb12u2 [7.260 kB]
Des:42 http://deb.debian.org/debian bookworm/main amd64 libalgorithm-diff-perl all 1.201-1 [43,3 kB]
Des:43 http://deb.debian.org/debian bookworm/main amd64 libalgorithm-diff-xs-perl amd64 0.04-8+b1 [11,4 kB]
Des:44 http://deb.debian.org/debian bookworm/main amd64 libalgorithm-merge-perl all 0.08-5 [11,8 kB]
Des:45 http://deb.debian.org/debian bookworm/main amd64 libc-devtools amd64 2.36-9+deb12u10 [54,7 kB]
Des:46 http://deb.debian.org/debian bookworm/main amd64 libfile-fcntllock-perl amd64 0.22-4+b1 [34,8 kB]
Des:47 http://deb.debian.org/debian bookworm/main amd64 libtext-unidecode-perl all 1.30-3 [101 kB]
Des:48 http://deb.debian.org/debian bookworm/main amd64 libxml-namespacesupport-perl all 1.12-2 [15,1 kB]
Des:49 http://deb.debian.org/debian bookworm/main amd64 libxml-sax-base-perl all 1.09-3 [20,6 kB]
Des:50 http://deb.debian.org/debian bookworm/main amd64 libxml-sax-perl all 1.02+dfsg-3 [59,4 kB]
Des:51 http://deb.debian.org/debian bookworm/main amd64 libxml-libxml-perl amd64 2.0207+dfsg+really+2.0134-1+b1 [322 kB]
Des:52 http://deb.debian.org/debian bookworm/main amd64 libxml-sax-expat-perl all 0.51-2 [11,1 kB]
Des:53 http://deb.debian.org/debian bookworm/main amd64 manpages-dev all 6.03-2 [2.030 kB]
Des:54 http://deb.debian.org/debian bookworm/main amd64 tex-common all 6.18 [32,5 kB]
Des:55 http://deb.debian.org/debian bookworm/main amd64 texinfo amd64 6.8-6+b1 [1.816 kB]
Des:56 http://deb.debian.org/debian bookworm/main amd64 vim-runtime all 2:9.0.1378-2+deb12u2 [7.027 kB]
Des:57 http://deb.debian.org/debian bookworm/main amd64 vim amd64 2:9.0.1378-2+deb12u2 [1.568 kB]
Descargados 79,3 MB en 9s (8.459 kB/s)                                         
Extrayendo plantillas para los paquetes: 100%
Seleccionando el paquete libsigsegv2:amd64 previamente no seleccionado.
(Leyendo la base de datos ... 149747 ficheros o directorios instalados actualmen
te.)
Preparando para desempaquetar .../libsigsegv2_2.14-1_amd64.deb ...
Desempaquetando libsigsegv2:amd64 (2.14-1) ...
Configurando libsigsegv2:amd64 (2.14-1) ...
Seleccionando el paquete gawk previamente no seleccionado.
(Leyendo la base de datos ... 149756 ficheros o directorios instalados actualmen
te.)
Preparando para desempaquetar .../00-gawk_1%3a5.2.1-2_amd64.deb ...
Desempaquetando gawk (1:5.2.1-2) ...
Seleccionando el paquete binutils-common:amd64 previamente no seleccionado.
Preparando para desempaquetar .../01-binutils-common_2.40-2_amd64.deb ...
Desempaquetando binutils-common:amd64 (2.40-2) ...
Seleccionando el paquete libbinutils:amd64 previamente no seleccionado.
Preparando para desempaquetar .../02-libbinutils_2.40-2_amd64.deb ...
Desempaquetando libbinutils:amd64 (2.40-2) ...
Seleccionando el paquete libctf-nobfd0:amd64 previamente no seleccionado.
Preparando para desempaquetar .../03-libctf-nobfd0_2.40-2_amd64.deb ...
Desempaquetando libctf-nobfd0:amd64 (2.40-2) ...
Seleccionando el paquete libctf0:amd64 previamente no seleccionado.
Preparando para desempaquetar .../04-libctf0_2.40-2_amd64.deb ...
Desempaquetando libctf0:amd64 (2.40-2) ...
Seleccionando el paquete libgprofng0:amd64 previamente no seleccionado.
Preparando para desempaquetar .../05-libgprofng0_2.40-2_amd64.deb ...
Desempaquetando libgprofng0:amd64 (2.40-2) ...
Seleccionando el paquete binutils-x86-64-linux-gnu previamente no seleccionado.
Preparando para desempaquetar .../06-binutils-x86-64-linux-gnu_2.40-2_amd64.deb 
...
Desempaquetando binutils-x86-64-linux-gnu (2.40-2) ...
Seleccionando el paquete binutils previamente no seleccionado.
Preparando para desempaquetar .../07-binutils_2.40-2_amd64.deb ...
Desempaquetando binutils (2.40-2) ...
Seleccionando el paquete m4 previamente no seleccionado.
Preparando para desempaquetar .../08-m4_1.4.19-3_amd64.deb ...
Desempaquetando m4 (1.4.19-3) ...
Seleccionando el paquete bison previamente no seleccionado.
Preparando para desempaquetar .../09-bison_2%3a3.8.2+dfsg-1+b1_amd64.deb ...
Desempaquetando bison (2:3.8.2+dfsg-1+b1) ...
Seleccionando el paquete libc-dev-bin previamente no seleccionado.
Preparando para desempaquetar .../10-libc-dev-bin_2.36-9+deb12u10_amd64.deb ...
Desempaquetando libc-dev-bin (2.36-9+deb12u10) ...
Seleccionando el paquete linux-libc-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../11-linux-libc-dev_6.1.137-1_amd64.deb ...
Desempaquetando linux-libc-dev:amd64 (6.1.137-1) ...
Seleccionando el paquete libcrypt-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../12-libcrypt-dev_1%3a4.4.33-2_amd64.deb ...
Desempaquetando libcrypt-dev:amd64 (1:4.4.33-2) ...
Seleccionando el paquete libtirpc-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../13-libtirpc-dev_1.3.3+ds-1_amd64.deb ...
Desempaquetando libtirpc-dev:amd64 (1.3.3+ds-1) ...
Seleccionando el paquete libnsl-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../14-libnsl-dev_1.3.0-2_amd64.deb ...
Desempaquetando libnsl-dev:amd64 (1.3.0-2) ...
Seleccionando el paquete rpcsvc-proto previamente no seleccionado.
Preparando para desempaquetar .../15-rpcsvc-proto_1.4.3-1_amd64.deb ...
Desempaquetando rpcsvc-proto (1.4.3-1) ...
Seleccionando el paquete libc6-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../16-libc6-dev_2.36-9+deb12u10_amd64.deb ...
Desempaquetando libc6-dev:amd64 (2.36-9+deb12u10) ...
Seleccionando el paquete libcc1-0:amd64 previamente no seleccionado.
Preparando para desempaquetar .../17-libcc1-0_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando libcc1-0:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete libitm1:amd64 previamente no seleccionado.
Preparando para desempaquetar .../18-libitm1_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando libitm1:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete libasan8:amd64 previamente no seleccionado.
Preparando para desempaquetar .../19-libasan8_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando libasan8:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete liblsan0:amd64 previamente no seleccionado.
Preparando para desempaquetar .../20-liblsan0_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando liblsan0:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete libtsan2:amd64 previamente no seleccionado.
Preparando para desempaquetar .../21-libtsan2_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando libtsan2:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete libubsan1:amd64 previamente no seleccionado.
Preparando para desempaquetar .../22-libubsan1_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando libubsan1:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete libgcc-12-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../23-libgcc-12-dev_12.2.0-14+deb12u1_amd64.deb .
..
Desempaquetando libgcc-12-dev:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete gcc-12 previamente no seleccionado.
Preparando para desempaquetar .../24-gcc-12_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando gcc-12 (12.2.0-14+deb12u1) ...
Seleccionando el paquete gcc previamente no seleccionado.
Preparando para desempaquetar .../25-gcc_4%3a12.2.0-3_amd64.deb ...
Desempaquetando gcc (4:12.2.0-3) ...
Seleccionando el paquete libstdc++-12-dev:amd64 previamente no seleccionado.
Preparando para desempaquetar .../26-libstdc++-12-dev_12.2.0-14+deb12u1_amd64.de
b ...
Desempaquetando libstdc++-12-dev:amd64 (12.2.0-14+deb12u1) ...
Seleccionando el paquete g++-12 previamente no seleccionado.
Preparando para desempaquetar .../27-g++-12_12.2.0-14+deb12u1_amd64.deb ...
Desempaquetando g++-12 (12.2.0-14+deb12u1) ...
Seleccionando el paquete g++ previamente no seleccionado.
Preparando para desempaquetar .../28-g++_4%3a12.2.0-3_amd64.deb ...
Desempaquetando g++ (4:12.2.0-3) ...
Seleccionando el paquete make previamente no seleccionado.
Preparando para desempaquetar .../29-make_4.3-4.1_amd64.deb ...
Desempaquetando make (4.3-4.1) ...
Seleccionando el paquete libdpkg-perl previamente no seleccionado.
Preparando para desempaquetar .../30-libdpkg-perl_1.21.22_all.deb ...
Desempaquetando libdpkg-perl (1.21.22) ...
Seleccionando el paquete patch previamente no seleccionado.
Preparando para desempaquetar .../31-patch_2.7.6-7_amd64.deb ...
Desempaquetando patch (2.7.6-7) ...
Seleccionando el paquete dpkg-dev previamente no seleccionado.
Preparando para desempaquetar .../32-dpkg-dev_1.21.22_all.deb ...
Desempaquetando dpkg-dev (1.21.22) ...
Seleccionando el paquete build-essential previamente no seleccionado.
Preparando para desempaquetar .../33-build-essential_12.9_amd64.deb ...
Desempaquetando build-essential (12.9) ...
Seleccionando el paquete curl previamente no seleccionado.
Preparando para desempaquetar .../34-curl_7.88.1-10+deb12u12_amd64.deb ...
Desempaquetando curl (7.88.1-10+deb12u12) ...
Seleccionando el paquete libfakeroot:amd64 previamente no seleccionado.
Preparando para desempaquetar .../35-libfakeroot_1.31-1.2_amd64.deb ...
Desempaquetando libfakeroot:amd64 (1.31-1.2) ...
Seleccionando el paquete fakeroot previamente no seleccionado.
Preparando para desempaquetar .../36-fakeroot_1.31-1.2_amd64.deb ...
Desempaquetando fakeroot (1.31-1.2) ...
Seleccionando el paquete liberror-perl previamente no seleccionado.
Preparando para desempaquetar .../37-liberror-perl_0.17029-2_all.deb ...
Desempaquetando liberror-perl (0.17029-2) ...
Seleccionando el paquete git-man previamente no seleccionado.
Preparando para desempaquetar .../38-git-man_1%3a2.39.5-0+deb12u2_all.deb ...
Desempaquetando git-man (1:2.39.5-0+deb12u2) ...
Seleccionando el paquete git previamente no seleccionado.
Preparando para desempaquetar .../39-git_1%3a2.39.5-0+deb12u2_amd64.deb ...
Desempaquetando git (1:2.39.5-0+deb12u2) ...
Seleccionando el paquete libalgorithm-diff-perl previamente no seleccionado.
Preparando para desempaquetar .../40-libalgorithm-diff-perl_1.201-1_all.deb ...
Desempaquetando libalgorithm-diff-perl (1.201-1) ...
Seleccionando el paquete libalgorithm-diff-xs-perl:amd64 previamente no seleccio
nado.
Preparando para desempaquetar .../41-libalgorithm-diff-xs-perl_0.04-8+b1_amd64.d
eb ...
Desempaquetando libalgorithm-diff-xs-perl:amd64 (0.04-8+b1) ...
Seleccionando el paquete libalgorithm-merge-perl previamente no seleccionado.
Preparando para desempaquetar .../42-libalgorithm-merge-perl_0.08-5_all.deb ...
Desempaquetando libalgorithm-merge-perl (0.08-5) ...
Seleccionando el paquete libc-devtools previamente no seleccionado.
Preparando para desempaquetar .../43-libc-devtools_2.36-9+deb12u10_amd64.deb ...
Desempaquetando libc-devtools (2.36-9+deb12u10) ...
Seleccionando el paquete libfile-fcntllock-perl previamente no seleccionado.
Preparando para desempaquetar .../44-libfile-fcntllock-perl_0.22-4+b1_amd64.deb 
...
Desempaquetando libfile-fcntllock-perl (0.22-4+b1) ...
Seleccionando el paquete libtext-unidecode-perl previamente no seleccionado.
Preparando para desempaquetar .../45-libtext-unidecode-perl_1.30-3_all.deb ...
Desempaquetando libtext-unidecode-perl (1.30-3) ...
Seleccionando el paquete libxml-namespacesupport-perl previamente no seleccionad
o.
Preparando para desempaquetar .../46-libxml-namespacesupport-perl_1.12-2_all.deb
 ...
Desempaquetando libxml-namespacesupport-perl (1.12-2) ...
Seleccionando el paquete libxml-sax-base-perl previamente no seleccionado.
Preparando para desempaquetar .../47-libxml-sax-base-perl_1.09-3_all.deb ...
Desempaquetando libxml-sax-base-perl (1.09-3) ...
Seleccionando el paquete libxml-sax-perl previamente no seleccionado.
Preparando para desempaquetar .../48-libxml-sax-perl_1.02+dfsg-3_all.deb ...
Desempaquetando libxml-sax-perl (1.02+dfsg-3) ...
Seleccionando el paquete libxml-libxml-perl previamente no seleccionado.
Preparando para desempaquetar .../49-libxml-libxml-perl_2.0207+dfsg+really+2.013
4-1+b1_amd64.deb ...
Desempaquetando libxml-libxml-perl (2.0207+dfsg+really+2.0134-1+b1) ...
Seleccionando el paquete libxml-sax-expat-perl previamente no seleccionado.
Preparando para desempaquetar .../50-libxml-sax-expat-perl_0.51-2_all.deb ...
Desempaquetando libxml-sax-expat-perl (0.51-2) ...
Seleccionando el paquete manpages-dev previamente no seleccionado.
Preparando para desempaquetar .../51-manpages-dev_6.03-2_all.deb ...
Desempaquetando manpages-dev (6.03-2) ...
Seleccionando el paquete tex-common previamente no seleccionado.
Preparando para desempaquetar .../52-tex-common_6.18_all.deb ...
Desempaquetando tex-common (6.18) ...
Seleccionando el paquete texinfo previamente no seleccionado.
Preparando para desempaquetar .../53-texinfo_6.8-6+b1_amd64.deb ...
Desempaquetando texinfo (6.8-6+b1) ...
Seleccionando el paquete vim-runtime previamente no seleccionado.
Preparando para desempaquetar .../54-vim-runtime_2%3a9.0.1378-2+deb12u2_all.deb 
...
2025-05-19 14:07:09 install libyuv0:amd64 <none> 0.0~git20230123.b2528b0-1
2025-05-19 14:07:09 install libavif15:amd64 <none> 0.11.1-1
2025-05-19 14:07:10 install libxpm4:amd64 <none> 1:3.5.12-1.1+deb12u1
2025-05-19 14:07:10 install libgd3:amd64 <none> 2.3.3-9
2025-05-19 14:07:10 install libgphoto2-port12:amd64 <none> 2.5.30-1
2025-05-19 14:07:10 install libgphoto2-6:amd64 <none> 2.5.30-1
2025-05-19 14:07:11 install libnspr4:amd64 <none> 2:4.35-1
2025-05-19 14:07:11 install libnss3:amd64 <none> 2:3.87.1-1+deb12u1
2025-05-19 14:07:12 install libpoppler126:amd64 <none> 22.12.0-2+deb12u1
2025-05-19 14:07:12 install libpoppler-glib8:amd64 <none> 22.12.0-2+deb12u1
2025-05-19 14:07:12 install libsensors-config:all <none> 1:3.6.0-7.1
2025-05-19 14:07:13 install libsensors5:amd64 <none> 1:3.6.0-7.1
2025-05-19 14:07:13 install libwrap0:amd64 <none> 7.6.q-32
2025-05-19 14:07:13 install libsnmp-base:all <none> 5.9.3+dfsg-2
2025-05-19 14:07:14 install libsnmp40:amd64 <none> 5.9.3+dfsg-2
2025-05-19 14:07:14 install libsane1:amd64 <none> 1.2.1-2
2025-05-19 14:07:15 install sane-utils:amd64 <none> 1.2.1-2
2025-05-19 14:07:16 install sgml-base:all <none> 1.31
2025-05-19 14:07:16 install sudo:amd64 <none> 1.9.13p3-1+deb12u1
2025-05-19 14:07:17 install python-apt-common:all <none> 2.6.0
2025-05-19 14:07:17 install distro-info-data:all <none> 0.58+deb12u4
2025-05-19 14:07:17 install python3-apt:amd64 <none> 2.6.0
2025-05-19 14:07:17 install python3-debconf:all <none> 1.5.82
2025-05-19 14:07:18 install apt-listchanges:all <none> 3.24
2025-05-19 14:07:18 install bash-completion:all <none> 1:2.11-6
2025-05-19 14:07:19 install libuv1:amd64 <none> 1.44.2-1+deb12u1
2025-05-19 14:07:20 install libfstrm0:amd64 <none> 0.6.1-1
2025-05-19 14:07:20 install libjemalloc2:amd64 <none> 5.3.0-1
2025-05-19 14:07:20 install liblmdb0:amd64 <none> 0.9.24-1
2025-05-19 14:07:20 install libmaxminddb0:amd64 <none> 1.7.1-1
2025-05-19 14:07:21 install libprotobuf-c1:amd64 <none> 1.4.1-1+b1
2025-05-19 14:07:21 install bind9-libs:amd64 <none> 1:9.18.33-1~deb12u2
2025-05-19 14:07:21 install bind9-host:amd64 <none> 1:9.18.33-1~deb12u2
2025-05-19 14:07:21 install bind9-dnsutils:amd64 <none> 1:9.18.33-1~deb12u2
2025-05-19 14:07:22 install bzip2:amd64 <none> 1.0.8-5+b1
2025-05-19 14:07:22 install ca-certificates:all <none> 20230311
2025-05-19 14:07:23 install debian-faq:all <none> 11.1
2025-05-19 14:07:23 install doc-debian:all <none> 11.3+nmu1
2025-05-19 14:07:23 install libmagic-mgc:amd64 <none> 1:5.44-3
2025-05-19 14:07:24 install libmagic1:amd64 <none> 1:5.44-3
2025-05-19 14:07:24 install file:amd64 <none> 1:5.44-3
2025-05-19 14:07:24 install gettext-base:amd64 <none> 0.21-12
2025-05-19 14:07:25 install libuchardet0:amd64 <none> 0.0.7-1
2025-05-19 14:07:25 install groff-base:amd64 <none> 1.22.4-10
2025-05-19 14:07:26 install inetutils-telnet:amd64 <none> 2:2.4-2+deb12u1
2025-05-19 14:07:26 install krb5-locales:all <none> 1.20.1-2+deb12u3
2025-05-19 14:07:26 install liblockfile-bin:amd64 <none> 1.17-1+b1
2025-05-19 14:07:26 install libnss-systemd:amd64 <none> 252.36-1~deb12u1
2025-05-19 14:07:27 install libpam-systemd:amd64 <none> 252.36-1~deb12u1
2025-05-19 14:07:27 install lsof:amd64 <none> 4.95.0-1
2025-05-19 14:07:27 install bsdextrautils:amd64 <none> 2.38.1-5+deb12u3
2025-05-19 14:07:27 install libpipeline1:amd64 <none> 1.5.7-1
2025-05-19 14:07:28 install man-db:amd64 <none> 2.11.2-2
2025-05-19 14:07:29 install manpages:all <none> 6.03-2
2025-05-19 14:07:30 install ncurses-term:all <none> 6.4-4
2025-05-19 14:07:34 install netcat-traditional:amd64 <none> 1.10-47
2025-05-19 14:07:34 install libcbor0.8:amd64 <none> 0.8.0-2+b1
2025-05-19 14:07:35 install libfido2-1:amd64 <none> 1.12.0-2+b1
2025-05-19 14:07:35 install openssh-client:amd64 <none> 1:9.2p1-2+deb12u6
2025-05-19 14:07:36 install python3-pkg-resources:all <none> 66.1.1-1+deb12u1
2025-05-19 14:07:36 install python3-chardet:all <none> 5.1.0+dfsg-2
2025-05-19 14:07:36 install python3-debian:all <none> 0.1.49
2025-05-19 14:07:37 install python3-pyparsing:all <none> 3.0.9-1
2025-05-19 14:07:37 install python3-httplib2:all <none> 0.20.4-3
2025-05-19 14:07:37 install python3-pycurl:amd64 <none> 7.45.2-3
2025-05-19 14:07:38 install python3-pysimplesoap:all <none> 1.16.2-5
2025-05-19 14:07:38 install python3-debianbts:all <none> 4.0.1
2025-05-19 14:07:38 install python3-certifi:all <none> 2022.9.24-1
2025-05-19 14:07:38 install python3-charset-normalizer:all <none> 3.0.1-2
2025-05-19 14:07:39 install python3-idna:all <none> 3.3-1+deb12u1
2025-05-19 14:07:39 install python3-six:all <none> 1.16.0-4
2025-05-19 14:07:39 install python3-urllib3:all <none> 1.26.12-1+deb12u1
2025-05-19 14:07:39 install python3-requests:all <none> 2.28.1+dfsg-1
2025-05-19 14:07:40 install python3-reportbug:all <none> 12.0.0
2025-05-19 14:07:40 install reportbug:all <none> 12.0.0
2025-05-19 14:07:40 install systemd-timesyncd:amd64 <none> 252.36-1~deb12u1
2025-05-19 14:07:40 install traceroute:amd64 <none> 1:2.1.2-1
2025-05-19 14:07:41 install wamerican:all <none> 2020.12.07-2
2025-05-19 14:07:41 install wget:amd64 <none> 1.21.3-1+deb12u1
2025-05-19 14:07:42 install xz-utils:amd64 <none> 5.4.1-1
2025-05-19 14:07:42 install libaccountsservice0:amd64 <none> 22.08.8-6
2025-05-19 14:07:42 install libpolkit-gobject-1-0:amd64 <none> 122-3
2025-05-19 14:07:43 install accountsservice:amd64 <none> 22.08.8-6
2025-05-19 14:07:43 install hicolor-icon-theme:all <none> 0.17-2
2025-05-19 14:07:43 install libgdk-pixbuf2.0-common:all <none> 2.42.10+dfsg-1+deb12u1
2025-05-19 14:07:44 install shared-mime-info:amd64 <none> 2.2-1
2025-05-19 14:07:45 install libgdk-pixbuf-2.0-0:amd64 <none> 2.42.10+dfsg-1+deb12u1
2025-05-19 14:07:45 install gtk-update-icon-cache:amd64 <none> 3.24.38-2~deb12u3
2025-05-19 14:07:45 install adwaita-icon-theme:all <none> 43-1
2025-05-19 14:07:57 install dbus-user-session:amd64 <none> 1.14.10-1~deb12u1
2025-05-19 14:07:57 install libdconf1:amd64 <none> 0.40.0-4
2025-05-19 14:07:57 install dconf-service:amd64 <none> 0.40.0-4
2025-05-19 14:07:58 install dconf-gsettings-backend:amd64 <none> 0.40.0-4
2025-05-19 14:07:58 install libgc1:amd64 <none> 1:8.2.2-3
2025-05-19 14:07:58 install guile-3.0-libs:amd64 <none> 3.0.8-2
2025-05-19 14:08:02 install at-spi2-common:all <none> 2.46.0-5
2025-05-19 14:08:02 install libatk1.0-0:amd64 <none> 2.46.0-5
2025-05-19 14:08:03 install libtdb1:amd64 <none> 1.4.8-2
2025-05-19 14:08:03 install libogg0:amd64 <none> 1.3.5-3
2025-05-19 14:08:03 install libvorbis0a:amd64 <none> 1.3.7-1
2025-05-19 14:08:03 install libvorbisfile3:amd64 <none> 1.3.7-1
2025-05-19 14:08:04 install sound-theme-freedesktop:all <none> 0.8-2
2025-05-19 14:08:04 install libcanberra0:amd64 <none> 0.30-10
2025-05-19 14:08:04 install libxi6:amd64 <none> 2:1.8-1+b1
2025-05-19 14:08:04 install libatspi2.0-0:amd64 <none> 2.46.0-5
2025-05-19 14:08:05 install libatk-bridge2.0-0:amd64 <none> 2.46.0-5
2025-05-19 14:08:05 install libcairo-gobject2:amd64 <none> 1.16.0-7
2025-05-19 14:08:05 install libcolord2:amd64 <none> 1.4.6-2.2
2025-05-19 14:08:05 install libepoxy0:amd64 <none> 1.5.10-1
2025-05-19 14:08:06 install libfribidi0:amd64 <none> 1.0.8-2.1
2025-05-19 14:08:06 install libgraphite2-3:amd64 <none> 1.3.14-1
2025-05-19 14:08:06 install libharfbuzz0b:amd64 <none> 6.0.0+dfsg-3
2025-05-19 14:08:07 install fontconfig:amd64 <none> 2.14.1-4
2025-05-19 14:08:07 install libthai-data:all <none> 0.1.29-1
2025-05-19 14:08:07 install libdatrie1:amd64 <none> 0.2.13-2+b1
2025-05-19 14:08:08 install libthai0:amd64 <none> 0.1.29-1
2025-05-19 14:08:08 install libpango-1.0-0:amd64 <none> 1.50.12+ds-1
2025-05-19 14:08:08 install libpangoft2-1.0-0:amd64 <none> 1.50.12+ds-1
2025-05-19 14:08:08 install libpangocairo-1.0-0:amd64 <none> 1.50.12+ds-1
2025-05-19 14:08:09 install libwayland-client0:amd64 <none> 1.21.0-1
2025-05-19 14:08:09 install libwayland-cursor0:amd64 <none> 1.21.0-1
2025-05-19 14:08:09 install libwayland-egl1:amd64 <none> 1.21.0-1
2025-05-19 14:08:09 install libxcomposite1:amd64 <none> 1:0.4.5-1
2025-05-19 14:08:10 install libxfixes3:amd64 <none> 1:6.0.0-2
2025-05-19 14:08:10 install libxcursor1:amd64 <none> 1:1.2.1-1
2025-05-19 14:08:10 install libxdamage1:amd64 <none> 1:1.1.6-1
2025-05-19 14:08:10 install libxinerama1:amd64 <none> 2:1.1.4-3
2025-05-19 14:08:10 install libxkbcommon0:amd64 <none> 1.5.0-1
2025-05-19 14:08:11 install libxrandr2:amd64 <none> 2:1.5.2-2+b1
2025-05-19 14:08:11 install libgtk-3-common:all <none> 3.24.38-2~deb12u3
2025-05-19 14:08:13 install libgtk-3-0:amd64 <none> 3.24.38-2~deb12u3
2025-05-19 14:08:14 install libcanberra-gtk3-0:amd64 <none> 0.30-10
2025-05-19 14:08:14 install librsvg2-2:amd64 <none> 2.54.7+dfsg-1~deb12u1
2025-05-19 14:08:15 install aisleriot:amd64 <none> 1:3.22.23-1
2025-05-19 14:08:20 install alsa-topology-conf:all <none> 1.2.5.1-2
2025-05-19 14:08:20 install alsa-ucm-conf:all <none> 1.2.8-1
2025-05-19 14:08:21 install libatopology2:amd64 <none> 1.2.8-1+b1
2025-05-19 14:08:21 install libfftw3-single3:amd64 <none> 3.3.10-1
2025-05-19 14:08:21 install libsamplerate0:amd64 <none> 0.2.2-3
2025-05-19 14:08:22 install alsa-utils:amd64 <none> 1.2.8-1
2025-05-19 14:08:22 install anacron:amd64 <none> 2.3-36
2025-05-19 14:08:23 install libapr1:amd64 <none> 1.7.2-3+deb12u1
2025-05-19 14:08:23 install libaprutil1:amd64 <none> 1.6.3-1
2025-05-19 14:08:23 install libaprutil1-dbd-sqlite3:amd64 <none> 1.6.3-1
2025-05-19 14:08:23 install libaprutil1-ldap:amd64 <none> 1.6.3-1
2025-05-19 14:08:23 install liblua5.3-0:amd64 <none> 5.3.6-2
2025-05-19 14:08:24 install apache2-bin:amd64 <none> 2.4.62-1~deb12u2
2025-05-19 14:08:24 install apg:amd64 <none> 2.2.3.dfsg.1-5+b2
2025-05-19 14:08:25 install libstemmer0d:amd64 <none> 2.2.0-2
2025-05-19 14:08:25 install libxmlb2:amd64 <none> 0.3.10-2
2025-05-19 14:08:25 install libyaml-0-2:amd64 <none> 0.2.5-1
2025-05-19 14:08:26 install libappstream4:amd64 <none> 0.16.1-2
2025-05-19 14:08:26 install appstream:amd64 <none> 0.16.1-2
2025-05-19 14:08:26 install apt-config-icons:all <none> 0.16.1-2
2025-05-19 14:08:27 install libaspell15:amd64 <none> 0.60.8-4+b1
2025-05-19 14:08:27 install emacsen-common:all <none> 3.0.5
2025-05-19 14:08:27 install dictionaries-common:all <none> 1.29.5
2025-05-19 14:08:28 install aspell:amd64 <none> 0.60.8-4+b1
2025-05-19 14:08:28 install aspell-en:all <none> 2020.12.07-0-1
2025-05-19 14:08:29 install aspell-es:all <none> 1.11-20
2025-05-19 14:08:29 install libxtst6:amd64 <none> 2:1.2.3-1.1
2025-05-19 14:08:29 install gsettings-desktop-schemas:all <none> 43.0-1
2025-05-19 14:08:30 install at-spi2-core:amd64 <none> 2.46.0-5
2025-05-19 14:08:30 install libdaemon0:amd64 <none> 0.14-7.1
2025-05-19 14:08:30 install avahi-autoipd:amd64 <none> 0.8-10+deb12u1
2025-05-19 14:08:31 install libavahi-core7:amd64 <none> 0.8-10+deb12u1
2025-05-19 14:08:31 install avahi-daemon:amd64 <none> 0.8-10+deb12u1
2025-05-19 14:08:31 install libgraphene-1.0-0:amd64 <none> 1.10.8-1
2025-05-19 14:08:31 install liblzo2-2:amd64 <none> 2.10-2
2025-05-19 14:08:32 install libcairo-script-interpreter2:amd64 <none> 1.16.0-7
2025-05-19 14:08:32 install libcloudproviders0:amd64 <none> 0.3.1-2
2025-05-19 14:08:32 install libgtk-4-common:all <none> 4.8.3+ds-2+deb12u1
2025-05-19 14:08:33 install libgtk-4-1:amd64 <none> 4.8.3+ds-2+deb12u1
2025-05-19 14:08:34 install libadwaita-1-0:amd64 <none> 1.2.2-1
2025-05-19 14:08:34 install baobab:amd64 <none> 43.0-1
2025-05-19 14:08:35 install bluetooth:all <none> 5.66-1+deb12u2
2025-05-19 14:08:36 install libical3:amd64 <none> 3.0.16-1+b1
2025-05-19 14:08:36 install bluez-obexd:amd64 <none> 5.66-1+deb12u2
2025-05-19 14:08:36 install bogofilter-common:amd64 <none> 1.2.5-1+b2
2025-05-19 14:08:37 install libgslcblas0:amd64 <none> 2.7.1+dfsg-5+deb12u1
2025-05-19 14:08:37 install libgsl27:amd64 <none> 2.7.1+dfsg-5+deb12u1
2025-05-19 14:08:37 install bogofilter-bdb:amd64 <none> 1.2.5-1+b2
2025-05-19 14:08:38 install bogofilter:amd64 <none> 1.2.5-1+b2
2025-05-19 14:08:38 install bolt:amd64 <none> 0.9.5-1
2025-05-19 14:08:38 install brasero-common:all <none> 3.12.3-2
2025-05-19 14:08:40 install bubblewrap:amd64 <none> 0.8.0-2+deb12u1
2025-05-19 14:08:40 install libao-common:all <none> 1.2.2+20180113-1.1
2025-05-19 14:08:41 install libao4:amd64 <none> 1.2.2+20180113-1.1
2025-05-19 14:08:41 install cdrdao:amd64 <none> 1:1.2.4-3
2025-05-19 14:08:41 install libglvnd0:amd64 <none> 1.6.0-1
2025-05-19 14:08:41 install libdrm-common:all <none> 2.4.114-1
2025-05-19 14:08:42 install libdrm2:amd64 <none> 2.4.114-1+b1
2025-05-19 14:08:42 install libglapi-mesa:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:08:42 install libx11-xcb1:amd64 <none> 2:1.8.4-2+deb12u2
2025-05-19 14:08:42 install libxcb-dri2-0:amd64 <none> 1.15-1
2025-05-19 14:08:43 install libxcb-dri3-0:amd64 <none> 1.15-1
2025-05-19 14:08:43 install libxcb-glx0:amd64 <none> 1.15-1
2025-05-19 14:08:43 install libxcb-present0:amd64 <none> 1.15-1
2025-05-19 14:08:43 install libxcb-randr0:amd64 <none> 1.15-1
2025-05-19 14:08:44 install libxcb-sync1:amd64 <none> 1.15-1
2025-05-19 14:08:44 install libxcb-xfixes0:amd64 <none> 1.15-1
2025-05-19 14:08:44 install libxshmfence1:amd64 <none> 1.3-1
2025-05-19 14:08:44 install libxxf86vm1:amd64 <none> 1:1.1.4-1+b2
2025-05-19 14:08:44 install libdrm-amdgpu1:amd64 <none> 2.4.114-1+b1
2025-05-19 14:08:45 install libpciaccess0:amd64 <none> 0.17-2
2025-05-19 14:08:45 install libdrm-intel1:amd64 <none> 2.4.114-1+b1
2025-05-19 14:08:45 install libdrm-nouveau2:amd64 <none> 2.4.114-1+b1
2025-05-19 14:08:45 install libdrm-radeon1:amd64 <none> 2.4.114-1+b1
2025-05-19 14:08:46 install libz3-4:amd64 <none> 4.8.12-3.1
2025-05-19 14:08:48 install libllvm15:amd64 <none> 1:15.0.6-4+b1
2025-05-19 14:08:54 install libgl1-mesa-dri:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:08:56 install libglx-mesa0:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:08:56 install libglx0:amd64 <none> 1.6.0-1
2025-05-19 14:08:57 install libgl1:amd64 <none> 1.6.0-1
2025-05-19 14:08:57 install libwayland-server0:amd64 <none> 1.21.0-1
2025-05-19 14:08:57 install libgbm1:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:08:57 install libegl-mesa0:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:08:58 install libegl1:amd64 <none> 1.6.0-1
2025-05-19 14:08:58 install libcogl20:amd64 <none> 1.22.8-3+b1
2025-05-19 14:08:58 install libcogl-pango20:amd64 <none> 1.22.8-3+b1
2025-05-19 14:08:58 install libcogl-path20:amd64 <none> 1.22.8-3+b1
2025-05-19 14:08:59 install libevdev2:amd64 <none> 1.13.0+dfsg-1
2025-05-19 14:08:59 install libmtdev1:amd64 <none> 1.1.6-1
2025-05-19 14:08:59 install libgudev-1.0-0:amd64 <none> 237-2
2025-05-19 14:08:59 install libwacom-common:all <none> 2.6.0-1
2025-05-19 14:09:00 install libwacom9:amd64 <none> 2.6.0-1
2025-05-19 14:09:01 install libinput-bin:amd64 <none> 1.22.1-1
2025-05-19 14:09:01 install libinput10:amd64 <none> 1.22.1-1
2025-05-19 14:09:01 install libjson-glib-1.0-common:all <none> 1.6.6-1
2025-05-19 14:09:02 install libjson-glib-1.0-0:amd64 <none> 1.6.6-1
2025-05-19 14:09:02 install libclutter-1.0-0:amd64 <none> 1.26.4+dfsg-4
2025-05-19 14:09:02 install libunwind8:amd64 <none> 1.6.2-3
2025-05-19 14:09:03 install libgstreamer1.0-0:amd64 <none> 1.22.0-2+deb12u1
2025-05-19 14:09:03 install liborc-0.4-0:amd64 <none> 1:0.4.33-2
2025-05-19 14:09:04 install iso-codes:all <none> 4.15.0-1
2025-05-19 14:09:06 install libgstreamer-plugins-base1.0-0:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:09:07 install libclutter-gst-3.0-0:amd64 <none> 3.0.27-3
2025-05-19 14:09:07 install libass9:amd64 <none> 1:0.17.1-1
2025-05-19 14:09:07 install libbs2b0:amd64 <none> 3.1.0+dfsg-7
2025-05-19 14:09:08 install libva2:amd64 <none> 2.17.0-1
2025-05-19 14:09:08 install libmfx1:amd64 <none> 22.5.4-1
2025-05-19 14:09:10 install libva-drm2:amd64 <none> 2.17.0-1
2025-05-19 14:09:10 install libva-x11-2:amd64 <none> 2.17.0-1
2025-05-19 14:09:10 install libvdpau1:amd64 <none> 1.5-2
2025-05-19 14:09:10 install ocl-icd-libopencl1:amd64 <none> 2.3.1-1
2025-05-19 14:09:11 install libavutil57:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:09:11 install libcodec2-1.0:amd64 <none> 1.0.5-1
2025-05-19 14:09:13 install libgsm1:amd64 <none> 1.0.22-1
2025-05-19 14:09:13 install libhwy1:amd64 <none> 1.0.3-3+deb12u1
2025-05-19 14:09:14 install libjxl0.7:amd64 <none> 0.7.0-10
2025-05-19 14:09:14 install libmp3lame0:amd64 <none> 3.100-6
2025-05-19 14:09:14 install libopus0:amd64 <none> 1.3.1-3
2025-05-19 14:09:15 install libshine3:amd64 <none> 3.1.1-2
2025-05-19 14:09:15 install libsnappy1v5:amd64 <none> 1.1.9-3
2025-05-19 14:09:15 install libspeex1:amd64 <none> 1.2.1-2
2025-05-19 14:09:15 install libsoxr0:amd64 <none> 0.1.3-4
2025-05-19 14:09:16 install libswresample4:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:09:16 install libtheora0:amd64 <none> 1.1.1+dfsg.1-16.1+b1
2025-05-19 14:09:16 install libtwolame0:amd64 <none> 0.4.0-2
2025-05-19 14:09:16 install libvorbisenc2:amd64 <none> 1.3.7-1
2025-05-19 14:09:17 install libvpx7:amd64 <none> 1.12.0-1+deb12u3
2025-05-19 14:09:17 install libx264-164:amd64 <none> 2:0.164.3095+gitbaee400-3
2025-05-19 14:09:18 install libxvidcore4:amd64 <none> 2:1.3.7-1
2025-05-19 14:09:18 install libzvbi-common:all <none> 0.2.41-1
2025-05-19 14:09:18 install libzvbi0:amd64 <none> 0.2.41-1
2025-05-19 14:09:18 install libavcodec59:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:09:20 install libchromaprint1:amd64 <none> 1.5.1-2+b1
2025-05-19 14:09:20 install libraw1394-11:amd64 <none> 2.1.2-2
2025-05-19 14:09:20 install libdc1394-25:amd64 <none> 2.2.6-4
2025-05-19 14:09:21 install libdca0:amd64 <none> 0.0.7-2
2025-05-19 14:09:21 install libgles2:amd64 <none> 1.6.0-1
2025-05-19 14:09:21 install libdirectfb-1.7-7:amd64 <none> 1.7.7-11
2025-05-19 14:09:22 install libdvdread8:amd64 <none> 6.1.3-1
2025-05-19 14:09:22 install libdvdnav4:amd64 <none> 6.1.1-1
2025-05-19 14:09:22 install libfaad2:amd64 <none> 2.10.1-1
2025-05-19 14:09:23 install libflite1:amd64 <none> 2.2-5
2025-05-19 14:09:27 install libflac12:amd64 <none> 1.4.2+ds-2
2025-05-19 14:09:27 install libmpg123-0:amd64 <none> 1.31.2-1+deb12u1
2025-05-19 14:09:27 install libsndfile1:amd64 <none> 1.2.0-1
2025-05-19 14:09:28 install libinstpatch-1.0-2:amd64 <none> 1.1.6-1
2025-05-19 14:09:28 install libjack-jackd2-0:amd64 <none> 1.9.21~dfsg-3
2025-05-19 14:09:28 install libasyncns0:amd64 <none> 0.8-6+b3
2025-05-19 14:09:29 install libpulse0:amd64 <none> 16.1+dfsg1-2+b1
2025-05-19 14:09:29 install libdecor-0-0:amd64 <none> 0.1.1-2
2025-05-19 14:09:29 install libxss1:amd64 <none> 1:1.2.3-1
2025-05-19 14:09:29 install libsdl2-2.0-0:amd64 <none> 2.26.5+dfsg-1
2025-05-19 14:09:30 install timgm6mb-soundfont:all <none> 1.3-5
2025-05-19 14:09:31 install libfluidsynth3:amd64 <none> 2.3.1-2
2025-05-19 14:09:31 install libfreeaptx0:amd64 <none> 0.1.1-2
2025-05-19 14:09:31 install libgme0:amd64 <none> 0.6.3-6
2025-05-19 14:09:32 install libgstreamer-gl1.0-0:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:09:32 install libproxy1v5:amd64 <none> 0.4.18-1.2
2025-05-19 14:09:32 install glib-networking-common:all <none> 2.74.0-4
2025-05-19 14:09:33 install glib-networking-services:amd64 <none> 2.74.0-4
2025-05-19 14:09:33 install glib-networking:amd64 <none> 2.74.0-4
2025-05-19 14:09:33 install libsoup-3.0-common:all <none> 3.2.2-2
2025-05-19 14:09:34 install libsoup-3.0-0:amd64 <none> 3.2.2-2
2025-05-19 14:09:34 install libgssdp-1.6-0:amd64 <none> 1.6.2-2
2025-05-19 14:09:34 install libgupnp-1.6-0:amd64 <none> 1.6.3-1
2025-05-19 14:09:34 install libgupnp-igd-1.0-4:amd64 <none> 1.2.0-3
2025-05-19 14:09:35 install libnice10:amd64 <none> 0.1.21-1
2025-05-19 14:09:35 install libvulkan1:amd64 <none> 1.3.239.0-1
2025-05-19 14:09:35 install libxcb-xkb1:amd64 <none> 1.15-1
2025-05-19 14:09:35 install libxkbcommon-x11-0:amd64 <none> 1.5.0-1
2025-05-19 14:09:36 install libgstreamer-plugins-bad1.0-0:amd64 <none> 1.22.0-4+deb12u5
2025-05-19 14:09:36 install libimath-3-1-29:amd64 <none> 3.1.6-1
2025-05-19 14:09:36 install libkate1:amd64 <none> 0.4.1-11
2025-05-19 14:09:37 install libldacbt-enc2:amd64 <none> 2.0.2.3+git20200429+ed310a0-4
2025-05-19 14:09:37 install libserd-0-0:amd64 <none> 0.30.16-1
2025-05-19 14:09:37 install libsord-0-0:amd64 <none> 0.16.14+git221008-1
2025-05-19 14:09:37 install libsratom-0-0:amd64 <none> 0.6.14-1
2025-05-19 14:09:38 install liblilv-0-0:amd64 <none> 0.24.14-1
2025-05-19 14:09:38 install libxslt1.1:amd64 <none> 1.1.35-1+deb12u1
2025-05-19 14:09:39 install libyajl2:amd64 <none> 2.1.0-3+deb12u2
2025-05-19 14:09:39 install libraptor2-0:amd64 <none> 2.0.15-4
2025-05-19 14:09:39 install liblrdf0:amd64 <none> 0.6.1-4
2025-05-19 14:09:40 install libltc11:amd64 <none> 1.3.2-1
2025-05-19 14:09:40 install libmjpegutils-2.1-0:amd64 <none> 1:2.1.0+debian-7
2025-05-19 14:09:40 install libmodplug1:amd64 <none> 1:0.8.9.0-3
2025-05-19 14:09:41 install libmpcdec6:amd64 <none> 2:0.1~r495-2
2025-05-19 14:09:41 install libmpeg2encpp-2.1-0:amd64 <none> 1:2.1.0+debian-7
2025-05-19 14:09:41 install libmplex2-2.1-0:amd64 <none> 1:2.1.0+debian-7
2025-05-19 14:09:41 install libneon27:amd64 <none> 0.32.5-1
2025-05-19 14:09:42 install libopenal-data:all <none> 1:1.19.1-2
2025-05-19 14:09:42 install libsndio7.0:amd64 <none> 1.9.0-0.3+b2
2025-05-19 14:09:42 install libopenal1:amd64 <none> 1:1.19.1-2
2025-05-19 14:09:43 install libopenexr-3-1-30:amd64 <none> 3.1.5-5
2025-05-19 14:09:43 install libopenh264-7:amd64 <none> 2.3.1+dfsg-3+deb12u2
2025-05-19 14:09:43 install libopenmpt0:amd64 <none> 0.6.9-1
2025-05-19 14:09:44 install libopenni2-0:amd64 <none> 2.2.0.33+dfsg-15+b1
2025-05-19 14:09:44 install libqrencode4:amd64 <none> 4.1.1-1
2025-05-19 14:09:44 install libsbc1:amd64 <none> 2.0-1
2025-05-19 14:09:45 install libsoundtouch1:amd64 <none> 2.3.2+ds1-1
2025-05-19 14:09:45 install libspandsp2:amd64 <none> 0.0.6+dfsg-2+b1
2025-05-19 14:09:45 install libsrt1.5-gnutls:amd64 <none> 1.5.1-1+deb12u1
2025-05-19 14:09:46 install libsrtp2-1:amd64 <none> 2.5.0-3
2025-05-19 14:09:46 install libvo-aacenc0:amd64 <none> 0.1.3-2
2025-05-19 14:09:46 install libvo-amrwbenc0:amd64 <none> 0.1.3-2
2025-05-19 14:09:46 install libwebrtc-audio-processing1:amd64 <none> 0.3-1+b1
2025-05-19 14:09:47 install libwildmidi2:amd64 <none> 0.4.3-1
2025-05-19 14:09:47 install libv4lconvert0:amd64 <none> 1.22.1-5+b2
2025-05-19 14:09:47 install libv4l-0:amd64 <none> 1.22.1-5+b2
2025-05-19 14:09:47 install libzbar0:amd64 <none> 0.23.92-7+deb12u1
2025-05-19 14:09:48 install libzxing2:amd64 <none> 1.4.0-3+b1
2025-05-19 14:09:48 install libcdparanoia0:amd64 <none> 3.10.2+debian-14
2025-05-19 14:09:48 install libvisual-0.4-0:amd64 <none> 0.4.0-19
2025-05-19 14:09:49 install gstreamer1.0-plugins-base:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:09:49 install libgpm2:amd64 <none> 1.20.7-10+b1
2025-05-19 14:09:49 install libncurses6:amd64 <none> 6.4-4
2025-05-19 14:09:50 install libaa1:amd64 <none> 1.4p5-50
2025-05-19 14:09:50 install libavc1394-0:amd64 <none> 0.5.4-5
2025-05-19 14:09:50 install libcaca0:amd64 <none> 0.99.beta20-3
2025-05-19 14:09:50 install libdv4:amd64 <none> 1.0.0-15
2025-05-19 14:09:51 install libiec61883-0:amd64 <none> 1.2.0-6+b1
2025-05-19 14:09:51 install libshout3:amd64 <none> 2.4.6-1+b1
2025-05-19 14:09:51 install libtag1v5-vanilla:amd64 <none> 1.13-2
2025-05-19 14:09:51 install libtag1v5:amd64 <none> 1.13-2
2025-05-19 14:09:52 install libwavpack1:amd64 <none> 5.6.0-1
2025-05-19 14:09:52 install libsoup2.4-common:all <none> 2.74.3-1+deb12u1
2025-05-19 14:09:52 install libsoup2.4-1:amd64 <none> 2.74.3-1+deb12u1
2025-05-19 14:09:53 install gstreamer1.0-plugins-good:amd64 <none> 1.22.0-5+deb12u2
2025-05-19 14:09:54 install gstreamer1.0-plugins-bad:amd64 <none> 1.22.0-4+deb12u5
2025-05-19 14:09:55 install cheese-common:all <none> 43.0-1
2025-05-19 14:09:56 install libxv1:amd64 <none> 2:1.0.11-1.1
2025-05-19 14:09:56 install gstreamer1.0-x:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:09:56 install libcheese8:amd64 <none> 43.0-1
2025-05-19 14:09:57 install libclutter-gtk-1.0-0:amd64 <none> 1.8.4-4+b1
2025-05-19 14:09:57 install gstreamer1.0-clutter-3.0:amd64 <none> 3.0.27-3
2025-05-19 14:09:57 install libcheese-gtk25:amd64 <none> 43.0-1
2025-05-19 14:09:57 install gnome-desktop3-data:all <none> 43.2-2
2025-05-19 14:09:58 install libxkbregistry0:amd64 <none> 1.5.0-1
2025-05-19 14:09:58 install libgnome-desktop-3-20:amd64 <none> 43.2-2
2025-05-19 14:09:59 install gnome-video-effects:all <none> 0.5.0-1
2025-05-19 14:09:59 install cheese:amd64 <none> 43.0-1
2025-05-19 14:09:59 install libgirepository-1.0-1:amd64 <none> 1.74.0-3
2025-05-19 14:09:59 install gir1.2-glib-2.0:amd64 <none> 1.74.0-3
2025-05-19 14:10:00 install gir1.2-accountsservice-1.0:amd64 <none> 22.08.8-6
2025-05-19 14:10:00 install gir1.2-freedesktop:amd64 <none> 1.74.0-3
2025-05-19 14:10:00 install gir1.2-gdkpixbuf-2.0:amd64 <none> 2.42.10+dfsg-1+deb12u1
2025-05-19 14:10:00 install gir1.2-graphene-1.0:amd64 <none> 1.10.8-1
2025-05-19 14:10:01 install gir1.2-harfbuzz-0.0:amd64 <none> 6.0.0+dfsg-3
2025-05-19 14:10:01 install libxft2:amd64 <none> 2.3.6-1
2025-05-19 14:10:01 install libpangoxft-1.0-0:amd64 <none> 1.50.12+ds-1
2025-05-19 14:10:01 install gir1.2-pango-1.0:amd64 <none> 1.50.12+ds-1
2025-05-19 14:10:02 install gir1.2-gtk-4.0:amd64 <none> 4.8.3+ds-2+deb12u1
2025-05-19 14:10:02 install gir1.2-adw-1:amd64 <none> 1.2.2-1
2025-05-19 14:10:02 install gir1.2-atk-1.0:amd64 <none> 2.46.0-5
2025-05-19 14:10:02 install gir1.2-atspi-2.0:amd64 <none> 2.46.0-5
2025-05-19 14:10:03 install libgck-1-0:amd64 <none> 3.41.1-1+b1
2025-05-19 14:10:03 install libgcr-base-3-1:amd64 <none> 3.41.1-1+b1
2025-05-19 14:10:03 install libgcr-ui-3-1:amd64 <none> 3.41.1-1+b1
2025-05-19 14:10:03 install gir1.2-gck-1:amd64 <none> 3.41.1-1+b1
2025-05-19 14:10:04 install gir1.2-gtk-3.0:amd64 <none> 3.24.38-2~deb12u3
2025-05-19 14:10:04 install gir1.2-gcr-3:amd64 <none> 3.41.1-1+b1
2025-05-19 14:10:04 install gir1.2-gdesktopenums-3.0:amd64 <none> 43.0-1
2025-05-19 14:10:04 install libgdm1:amd64 <none> 43.0-3
2025-05-19 14:10:05 install gir1.2-gdm-1.0:amd64 <none> 43.0-3
2025-05-19 14:10:05 install libgeoclue-2-0:amd64 <none> 2.6.0-2+deb12u1
2025-05-19 14:10:05 install gir1.2-geoclue-2.0:amd64 <none> 2.6.0-2+deb12u1
2025-05-19 14:10:05 install libupower-glib3:amd64 <none> 0.99.20-2
2025-05-19 14:10:06 install gnome-bluetooth-3-common:all <none> 42.5-3
2025-05-19 14:10:06 install libgnome-bluetooth-3.0-13:amd64 <none> 42.5-3
2025-05-19 14:10:06 install gir1.2-gnomebluetooth-3.0:amd64 <none> 42.5-3
2025-05-19 14:10:06 install gir1.2-gnomedesktop-3.0:amd64 <none> 43.2-2
2025-05-19 14:10:07 install gir1.2-gstreamer-1.0:amd64 <none> 1.22.0-2+deb12u1
2025-05-19 14:10:07 install geocode-glib-common:all <none> 3.26.3-6
2025-05-19 14:10:07 install libgeocode-glib-2-0:amd64 <none> 3.26.3-6
2025-05-19 14:10:07 install libgweather-4-common:all <none> 4.2.0-2
2025-05-19 14:10:09 install libgweather-4-0:amd64 <none> 4.2.0-2
2025-05-19 14:10:09 install gir1.2-gweather-4.0:amd64 <none> 4.2.0-2
2025-05-19 14:10:10 install libibus-1.0-5:amd64 <none> 1.5.27-5
2025-05-19 14:10:10 install gir1.2-ibus-1.0:amd64 <none> 1.5.27-5
2025-05-19 14:10:10 install mutter-common:all <none> 43.8-0+deb12u1
2025-05-19 14:10:11 install libice6:amd64 <none> 2:1.0.10-1
2025-05-19 14:10:11 install libspa-0.2-modules:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:12 install libpipewire-0.3-0:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:12 install libsm6:amd64 <none> 2:1.2.3-1
2025-05-19 14:10:12 install libxcb-util1:amd64 <none> 0.4.0-1+b1
2025-05-19 14:10:12 install libstartup-notification0:amd64 <none> 0.12-6+b1
2025-05-19 14:10:13 install libxcb-res0:amd64 <none> 1.15-1
2025-05-19 14:10:13 install libxkbfile1:amd64 <none> 1:1.1.0-1
2025-05-19 14:10:13 install libmutter-11-0:amd64 <none> 43.8-0+deb12u1
2025-05-19 14:10:14 install gir1.2-json-1.0:amd64 <none> 1.6.6-1
2025-05-19 14:10:14 install gir1.2-mutter-11:amd64 <none> 43.8-0+deb12u1
2025-05-19 14:10:14 install libnm0:amd64 <none> 1.42.4-1+deb12u1
2025-05-19 14:10:15 install gir1.2-nm-1.0:amd64 <none> 1.42.4-1+deb12u1
2025-05-19 14:10:15 install libnma-common:all <none> 1.10.6-1
2025-05-19 14:10:15 install libnma0:amd64 <none> 1.10.6-1
2025-05-19 14:10:16 install gir1.2-nma-1.0:amd64 <none> 1.10.6-1
2025-05-19 14:10:16 install libpolkit-agent-1-0:amd64 <none> 122-3
2025-05-19 14:10:16 install gir1.2-polkit-1.0:amd64 <none> 122-3
2025-05-19 14:10:16 install gir1.2-rsvg-2.0:amd64 <none> 2.54.7+dfsg-1~deb12u1
2025-05-19 14:10:16 install gir1.2-soup-3.0:amd64 <none> 3.2.2-2
2025-05-19 14:10:17 install gir1.2-upowerglib-1.0:amd64 <none> 0.99.20-2
2025-05-19 14:10:17 install libatomic1:amd64 <none> 12.2.0-14+deb12u1
2025-05-19 14:10:17 install libjavascriptcoregtk-4.1-0:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:10:19 install xdg-dbus-proxy:amd64 <none> 0.1.4-3
2025-05-19 14:10:20 install hunspell-en-us:all <none> 1:2020.12.07-2
2025-05-19 14:10:20 install myspell-es:all <none> 1.11-20
2025-05-19 14:10:20 install ispell:amd64 <none> 3.4.05-1
2025-05-19 14:10:21 install ispanish:all <none> 1.11-20
2025-05-19 14:10:21 install libhunspell-1.7-0:amd64 <none> 1.7.1-1
2025-05-19 14:10:21 install libenchant-2-2:amd64 <none> 2.3.3-2
2025-05-19 14:10:21 install libharfbuzz-icu0:amd64 <none> 6.0.0+dfsg-3
2025-05-19 14:10:22 install libhyphen0:amd64 <none> 2.8.8-7
2025-05-19 14:10:22 install libmanette-0.2-0:amd64 <none> 0.2.6-3+b1
2025-05-19 14:10:22 install libsecret-common:all <none> 0.20.5-3
2025-05-19 14:10:23 install libsecret-1-0:amd64 <none> 0.20.5-3
2025-05-19 14:10:23 install libwoff1:amd64 <none> 1.0.2-2
2025-05-19 14:10:23 install libwebkit2gtk-4.1-0:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:10:29 install gir1.2-javascriptcoregtk-4.1:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:10:29 install gir1.2-webkit2-4.1:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:10:30 install gnome-backgrounds:all <none> 43.1-1
2025-05-19 14:10:31 install gnome-settings-daemon-common:all <none> 43.0-4
2025-05-19 14:10:32 install libbluetooth3:amd64 <none> 5.66-1+deb12u2
2025-05-19 14:10:32 install liblc3-0:amd64 <none> 1.0.1-1+b1
2025-05-19 14:10:33 install libldacbt-abr2:amd64 <none> 2.0.2.3+git20200429+ed310a0-4
2025-05-19 14:10:33 install libspa-0.2-bluetooth:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:33 install libpipewire-0.3-modules:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:34 install pipewire-bin:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:35 install pipewire:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:35 install pipewire-alsa:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:35 install pipewire-pulse:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:35 install libwireplumber-0.4-0:amd64 <none> 0.4.13-1
2025-05-19 14:10:36 install wireplumber:amd64 <none> 0.4.13-1
2025-05-19 14:10:37 install pipewire-audio:all <none> 0.3.65-3+deb12u1
2025-05-19 14:10:37 install libmm-glib0:amd64 <none> 1.20.4-1
2025-05-19 14:10:37 install libnotify4:amd64 <none> 0.8.1-1
2025-05-19 14:10:37 install libpulse-mainloop-glib0:amd64 <none> 16.1+dfsg1-2+b1
2025-05-19 14:10:38 install gnome-settings-daemon:amd64 <none> 43.0-4
2025-05-19 14:10:38 install gnome-shell-common:all <none> 43.9-0+deb12u2
2025-05-19 14:10:39 install gstreamer1.0-pipewire:amd64 <none> 0.3.65-3+deb12u1
2025-05-19 14:10:39 install libglib2.0-data:all <none> 2.74.6-2+deb12u6
2025-05-19 14:10:40 install libglib2.0-bin:amd64 <none> 2.74.6-2+deb12u6
2025-05-19 14:10:40 install libcamel-1.2-64:amd64 <none> 3.46.4-2
2025-05-19 14:10:41 install evolution-data-server-common:all <none> 3.46.4-2
2025-05-19 14:10:42 install libedataserver-1.2-27:amd64 <none> 3.46.4-2
2025-05-19 14:10:42 install libecal-2.0-2:amd64 <none> 3.46.4-2
2025-05-19 14:10:42 install libmozjs-102-0:amd64 <none> 102.15.1-1~deb12u1
2025-05-19 14:10:45 install libgjs0g:amd64 <none> 1.74.2-1+deb12u1
2025-05-19 14:10:45 install libarchive13:amd64 <none> 3.6.2-1+deb12u2
2025-05-19 14:10:46 install libgnome-autoar-0-0:amd64 <none> 0.4.3-1
2025-05-19 14:10:46 install gnome-shell:amd64 <none> 43.9-0+deb12u2
2025-05-19 14:10:46 install python3-gi:amd64 <none> 3.42.2-3+b1
2025-05-19 14:10:47 install gnome-browser-connector:all <none> 42.1-3
2025-05-19 14:10:47 install chrome-gnome-shell:all <none> 42.1-3
2025-05-19 14:10:47 install libblas3:amd64 <none> 3.11.0-2
2025-05-19 14:10:48 install libquadmath0:amd64 <none> 12.2.0-14+deb12u1
2025-05-19 14:10:48 install libgfortran5:amd64 <none> 12.2.0-14+deb12u1
2025-05-19 14:10:48 install liblapack3:amd64 <none> 3.11.0-2
2025-05-19 14:10:49 install coinor-libcoinutils3v5:amd64 <none> 2.11.4+repack1-2
2025-05-19 14:10:50 install coinor-libosi1v5:amd64 <none> 0.108.6+repack1-2
2025-05-19 14:10:50 install coinor-libclp1:amd64 <none> 1.17.6-3
2025-05-19 14:10:50 install coinor-libcgl1:amd64 <none> 0.60.3+repack1-4
2025-05-19 14:10:51 install coinor-libcbc3:amd64 <none> 2.10.8+ds1-1
2025-05-19 14:10:51 install coinor-libcoinmp1v5:amd64 <none> 1.8.3-3
2025-05-19 14:10:51 install colord-data:all <none> 1.4.6-2.2
2025-05-19 14:10:52 install xml-core:all <none> 0.18+nmu1
2025-05-19 14:10:52 install libduktape207:amd64 <none> 2.7.0-2
2025-05-19 14:10:53 install polkitd:amd64 <none> 122-3
2025-05-19 14:10:53 install libgusb2:amd64 <none> 0.3.10-1
2025-05-19 14:10:54 install libcolorhug2:amd64 <none> 1.4.6-2.2
2025-05-19 14:10:54 install colord:amd64 <none> 1.4.6-2.2
2025-05-19 14:10:54 install libisl23:amd64 <none> 0.25-1.1
2025-05-19 14:10:55 install libmpfr6:amd64 <none> 4.2.0-1
2025-05-19 14:10:55 install libmpc3:amd64 <none> 1.3.1-1
2025-05-19 14:10:55 install cpp-12:amd64 <none> 12.2.0-14+deb12u1
2025-05-19 14:10:58 install cpp:amd64 <none> 4:12.2.0-3
2025-05-19 14:10:58 install libcrack2:amd64 <none> 2.9.6-5+b1
2025-05-19 14:10:59 install cracklib-runtime:amd64 <none> 2.9.6-5+b1
2025-05-19 14:10:59 install cups-common:all <none> 2.4.2-3+deb12u8
2025-05-19 14:10:59 install cups-client:amd64 <none> 2.4.2-3+deb12u8
2025-05-19 14:11:00 install cups-ipp-utils:amd64 <none> 2.4.2-3+deb12u8
2025-05-19 14:11:00 install poppler-utils:amd64 <none> 22.12.0-2+deb12u1
2025-05-19 14:11:01 install libpoppler-cpp0v5:amd64 <none> 22.12.0-2+deb12u1
2025-05-19 14:11:01 install libqpdf29:amd64 <none> 11.3.0-1+deb12u1
2025-05-19 14:11:01 install cups-filters-core-drivers:amd64 <none> 1.28.17-3+deb12u1
2025-05-19 14:11:02 install cups-core-drivers:amd64 <none> 2.4.2-3+deb12u8
2025-05-19 14:11:02 install libgs-common:all <none> 10.0.0~dfsg-11+deb12u7
2025-05-19 14:11:02 install libgs10-common:all <none> 10.0.0~dfsg-11+deb12u7
2025-05-19 14:11:03 install libidn12:amd64 <none> 1.41-1
2025-05-19 14:11:03 install libijs-0.35:amd64 <none> 0.35-15
2025-05-19 14:11:04 install libjbig2dec0:amd64 <none> 0.19-3
2025-05-19 14:11:04 install libxt6:amd64 <none> 1:1.2.1-1.1
2025-05-19 14:11:04 install libgs10:amd64 <none> 10.0.0~dfsg-11+deb12u7
2025-05-19 14:11:05 install ghostscript:amd64 <none> 10.0.0~dfsg-11+deb12u7
2025-05-19 14:11:06 install libfontembed1:amd64 <none> 1.28.17-3+deb12u1
2025-05-19 14:11:06 install cups-filters:amd64 <none> 1.28.17-3+deb12u1
2025-05-19 14:11:06 install cups-ppdc:amd64 <none> 2.4.2-3+deb12u8
2025-05-19 14:11:07 install cups-server-common:all <none> 2.4.2-3+deb12u8
2025-05-19 14:11:08 install cups:amd64 <none> 2.4.2-3+deb12u8
2025-05-19 14:11:09 install cups-pk-helper:amd64 <none> 0.2.6-1+b1
2025-05-19 14:11:09 install dconf-cli:amd64 <none> 0.40.0-4
2025-05-19 14:11:09 install debian-reference-common:all <none> 2.100
2025-05-19 14:11:09 install debian-reference-es:all <none> 2.100
2025-05-19 14:11:10 install librsvg2-common:amd64 <none> 2.54.7+dfsg-1~deb12u1
2025-05-19 14:11:10 install fonts-quicksand:all <none> 0.2016-2.1
2025-05-19 14:11:10 install desktop-base:all <none> 12.0.6+nmu1~deb12u1
2025-05-19 14:11:13 install desktop-file-utils:amd64 <none> 0.26-1
2025-05-19 14:11:13 install libassuan0:amd64 <none> 2.5.5-5
2025-05-19 14:11:13 install gpgconf:amd64 <none> 2.2.40-1.1
2025-05-19 14:11:14 install libksba8:amd64 <none> 1.6.3-2
2025-05-19 14:11:14 install libnpth0:amd64 <none> 1.6-3
2025-05-19 14:11:14 install dirmngr:amd64 <none> 2.2.40-1.1
2025-05-19 14:11:15 install dns-root-data:all <none> 2024071801~deb12u1
2025-05-19 14:11:15 install libnfnetlink0:amd64 <none> 1.0.2-2
2025-05-19 14:11:15 install libnetfilter-conntrack3:amd64 <none> 1.0.9-3
2025-05-19 14:11:15 install dnsmasq-base:amd64 <none> 2.90-4~deb12u1
2025-05-19 14:11:16 install sgml-data:all <none> 2.0.11+nmu1
2025-05-19 14:11:16 install docbook-xml:all <none> 4.5-12
2025-05-19 14:11:17 install dosfstools:amd64 <none> 4.2-1
2025-05-19 14:11:17 install enchant-2:amd64 <none> 2.3.3-2
2025-05-19 14:11:17 install libexempi8:amd64 <none> 2.6.3-1
2025-05-19 14:11:18 install libhandy-1-0:amd64 <none> 1.8.1-1
2025-05-19 14:11:18 install libpeas-common:all <none> 1.34.0-1
2025-05-19 14:11:18 install libpython3.11:amd64 <none> 3.11.2-6+deb12u6
2025-05-19 14:11:19 install libpeas-1.0-0:amd64 <none> 1.34.0-1+b1
2025-05-19 14:11:19 install gir1.2-peas-1.0:amd64 <none> 1.34.0-1+b1
2025-05-19 14:11:19 install webp-pixbuf-loader:amd64 <none> 0.2.1-1
2025-05-19 14:11:20 install eog:amd64 <none> 43.2-1
2025-05-19 14:11:22 install espeak-ng-data:amd64 <none> 1.51+dfsg-10+deb12u2
2025-05-19 14:11:24 install evince-common:all <none> 43.1-2
2025-05-19 14:11:29 install libdjvulibre-text:all <none> 3.5.28-2
2025-05-19 14:11:30 install libdjvulibre21:amd64 <none> 3.5.28-2+b1
2025-05-19 14:11:30 install libgxps2:amd64 <none> 0.3.2-2+b1
2025-05-19 14:11:30 install libkpathsea6:amd64 <none> 2022.20220321.62855-5.1+deb12u2
2025-05-19 14:11:30 install libspectre1:amd64 <none> 0.2.12-1
2025-05-19 14:11:31 install libsynctex2:amd64 <none> 2022.20220321.62855-5.1+deb12u2
2025-05-19 14:11:31 install libevdocument3-4:amd64 <none> 43.1-2+b1
2025-05-19 14:11:31 install libgspell-1-common:all <none> 1.12.0-1
2025-05-19 14:11:32 install libgspell-1-2:amd64 <none> 1.12.0-1+b2
2025-05-19 14:11:32 install libevview3-3:amd64 <none> 43.1-2+b1
2025-05-19 14:11:32 install evince:amd64 <none> 43.1-2+b1
2025-05-19 14:11:32 install libcmark0.30.2:amd64 <none> 0.30.2-6
2025-05-19 14:11:33 install libprotobuf32:amd64 <none> 3.21.12-3
2025-05-19 14:11:33 install libphonenumber8:amd64 <none> 8.12.57+ds-3
2025-05-19 14:11:33 install libebook-contacts-1.2-4:amd64 <none> 3.46.4-2
2025-05-19 14:11:34 install libebackend-1.2-11:amd64 <none> 3.46.4-2
2025-05-19 14:11:34 install libedata-book-1.2-27:amd64 <none> 3.46.4-2
2025-05-19 14:11:34 install libebook-1.2-21:amd64 <none> 3.46.4-2
2025-05-19 14:11:34 install libedataserverui-1.2-4:amd64 <none> 3.46.4-2
2025-05-19 14:11:35 install libgail-3-0:amd64 <none> 3.24.38-2~deb12u3
2025-05-19 14:11:35 install libgnome-autoar-gtk-0-0:amd64 <none> 0.4.3-1
2025-05-19 14:11:35 install libytnef0:amd64 <none> 2.0-1+b1
2025-05-19 14:11:35 install evolution-common:all <none> 3.46.4-2
2025-05-19 14:11:48 install libevolution:amd64 <none> 3.46.4-2
2025-05-19 14:11:49 install libedata-cal-2.0-2:amd64 <none> 3.46.4-2
2025-05-19 14:11:49 install libgoa-1.0-common:all <none> 3.46.0-1
2025-05-19 14:11:50 install libgoa-1.0-0b:amd64 <none> 3.46.0-1
2025-05-19 14:11:50 install gcr:amd64 <none> 3.41.1-1+b1
2025-05-19 14:11:50 install p11-kit-modules:amd64 <none> 0.24.1-2
2025-05-19 14:11:51 install p11-kit:amd64 <none> 0.24.1-2
2025-05-19 14:11:51 install pinentry-gnome3:amd64 <none> 1.2.1-1
2025-05-19 14:11:51 install gnome-keyring:amd64 <none> 42.1-1+b2
2025-05-19 14:11:52 install evolution-data-server:amd64 <none> 3.46.4-2
2025-05-19 14:11:52 install psmisc:amd64 <none> 23.6-1
2025-05-19 14:11:53 install evolution:amd64 <none> 3.46.4-2
2025-05-19 14:11:53 install evolution-plugin-bogofilter:amd64 <none> 3.46.4-2
2025-05-19 14:11:53 install libpst4:amd64 <none> 0.6.76-1
2025-05-19 14:11:54 install evolution-plugin-pstimport:amd64 <none> 3.46.4-2
2025-05-19 14:11:54 install libdbusmenu-glib4:amd64 <none> 18.10.20180917~bzr492+repack1-3
2025-05-19 14:11:54 install libdee-1.0-4:amd64 <none> 1.2.7+17.10.20170616-7+b2
2025-05-19 14:11:54 install libunity-protocol-private0:amd64 <none> 7.1.4+19.04.20190319-6+b1
2025-05-19 14:11:55 install libunity-scopes-json-def-desktop:all <none> 7.1.4+19.04.20190319-6
2025-05-19 14:11:55 install libunity9:amd64 <none> 7.1.4+19.04.20190319-6+b1
2025-05-19 14:11:55 install evolution-plugins:amd64 <none> 3.46.4-2
2025-05-19 14:11:55 install exfatprogs:amd64 <none> 1.2.0-1+deb12u1
2025-05-19 14:11:56 install p7zip:amd64 <none> 16.02+dfsg-8
2025-05-19 14:11:56 install p7zip-full:amd64 <none> 16.02+dfsg-8
2025-05-19 14:11:57 install libnautilus-extension4:amd64 <none> 43.2-1
2025-05-19 14:11:57 install file-roller:amd64 <none> 43.0-1
2025-05-19 14:11:58 install libevent-2.1-7:amd64 <none> 2.1.12-stable-8
2025-05-19 14:11:58 install firefox-esr:amd64 <none> 128.10.1esr-1~deb12u1
2025-05-19 14:12:16 install firefox-esr-l10n-es-ar:all <none> 128.10.1esr-1~deb12u1
2025-05-19 14:12:16 install firefox-esr-l10n-es-cl:all <none> 128.10.1esr-1~deb12u1
2025-05-19 14:12:17 install firefox-esr-l10n-es-es:all <none> 128.10.1esr-1~deb12u1
2025-05-19 14:12:17 install firefox-esr-l10n-es-mx:all <none> 128.10.1esr-1~deb12u1
2025-05-19 14:12:17 install libgee-0.8-2:amd64 <none> 0.20.6-1
2025-05-19 14:12:18 install libgnome-games-support-common:all <none> 1.8.2-1
2025-05-19 14:12:18 install libgnome-games-support-1-3:amd64 <none> 1.8.2-1+b1
2025-05-19 14:12:18 install five-or-more:amd64 <none> 1:3.32.3-1
2025-05-19 14:12:20 install folks-common:all <none> 0.15.5-2
2025-05-19 14:12:20 install fonts-cantarell:all <none> 0.303.1-1
2025-05-19 14:12:20 install fonts-dejavu-extra:all <none> 2.37-6
2025-05-19 14:12:21 install fonts-dejavu:all <none> 2.37-6
2025-05-19 14:12:21 install fonts-noto-color-emoji:all <none> 2.042-0+deb12u1
2025-05-19 14:12:24 install fonts-noto-mono:all <none> 20201225-1
2025-05-19 14:12:24 install fonts-opensymbol:all <none> 4:102.12+LibO7.4.7-1+deb12u8
2025-05-19 14:12:24 install fonts-symbola:all <none> 2.60-1.1
2025-05-19 14:12:25 install libgsound0:amd64 <none> 1.0.3-2
2025-05-19 14:12:25 install four-in-a-row:amd64 <none> 1:3.38.1-1+b1
2025-05-19 14:12:26 install libfuse3-3:amd64 <none> 3.14.0-4
2025-05-19 14:12:27 install fuse3:amd64 <none> 3.14.0-4
2025-05-19 14:12:27 install libefivar1:amd64 <none> 37-6
2025-05-19 14:12:27 install libefiboot1:amd64 <none> 37-6
2025-05-19 14:12:27 install libftdi1-2:amd64 <none> 1.5-6+b2
2025-05-19 14:12:28 install libjaylink0:amd64 <none> 0.3.1-1
2025-05-19 14:12:28 install libflashrom1:amd64 <none> 1.3.0-2.1
2025-05-19 14:12:28 install gnupg-l10n:all <none> 2.2.40-1.1
2025-05-19 14:12:29 install gnupg-utils:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:30 install gpg:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:30 install gpg-agent:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:30 install gpg-wks-client:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:31 install gpg-wks-server:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:31 install gpgsm:amd64 <none> 2.2.40-1.1
2025-05-19 14:12:32 install gnupg:all <none> 2.2.40-1.1
2025-05-19 14:12:32 install libgpgme11:amd64 <none> 1.18.0-3+b1
2025-05-19 14:12:32 install libjcat1:amd64 <none> 0.1.9-1
2025-05-19 14:12:33 install libfwupd2:amd64 <none> 1.8.12-2
2025-05-19 14:12:33 install libgcab-1.0-0:amd64 <none> 1.5-1
2025-05-19 14:12:33 install libmbim-glib4:amd64 <none> 1.28.2-1
2025-05-19 14:12:34 install libmbim-proxy:amd64 <none> 1.28.2-1
2025-05-19 14:12:34 install libqrtr-glib0:amd64 <none> 1.2.2-1
2025-05-19 14:12:34 install libqmi-glib5:amd64 <none> 1.32.2-1
2025-05-19 14:12:35 install libqmi-proxy:amd64 <none> 1.32.2-1
2025-05-19 14:12:35 install libsmbios-c2:amd64 <none> 2.4.3-1
2025-05-19 14:12:35 install tpm-udev:all <none> 0.6
2025-05-19 14:12:36 install libtss2-mu0:amd64 <none> 3.2.1-3
2025-05-19 14:12:36 install libtss2-tcti-cmd0:amd64 <none> 3.2.1-3
2025-05-19 14:12:36 install libtss2-tcti-device0:amd64 <none> 3.2.1-3
2025-05-19 14:12:36 install libtss2-tcti-mssim0:amd64 <none> 3.2.1-3
2025-05-19 14:12:37 install libtss2-tcti-swtpm0:amd64 <none> 3.2.1-3
2025-05-19 14:12:37 install libtss2-sys1:amd64 <none> 3.2.1-3
2025-05-19 14:12:37 install libtss2-esys-3.0.2-0:amd64 <none> 3.2.1-3
2025-05-19 14:12:38 install fwupd:amd64 <none> 1.8.12-2
2025-05-19 14:12:39 install fwupd-amd64-signed:amd64 <none> 1:1.4+1
2025-05-19 14:12:39 install gdisk:amd64 <none> 1.0.9-2.1
2025-05-19 14:12:39 install upower:amd64 <none> 0.99.20-2
2025-05-19 14:12:40 install libxmu6:amd64 <none> 2:1.1.3-3
2025-05-19 14:12:40 install libxaw7:amd64 <none> 2:1.0.14-1
2025-05-19 14:12:40 install x11-xkb-utils:amd64 <none> 7.7+7
2025-05-19 14:12:41 install xserver-common:all <none> 2:21.1.7-3+deb12u9
2025-05-19 14:12:41 install libxcvt0:amd64 <none> 0.1.2-1
2025-05-19 14:12:41 install libxfont2:amd64 <none> 1:2.0.6-1
2025-05-19 14:12:41 install xwayland:amd64 <none> 2:22.1.9-1
2025-05-19 14:12:42 install gnome-session-bin:amd64 <none> 43.0-1+deb12u1
2025-05-19 14:12:42 install gnome-session-common:all <none> 43.0-1+deb12u1
2025-05-19 14:12:43 install xdg-desktop-portal:amd64 <none> 1.16.0-2
2025-05-19 14:12:43 install xdg-desktop-portal-gtk:amd64 <none> 1.14.1-1
2025-05-19 14:12:44 install libgnome-desktop-4-2:amd64 <none> 43.2-2
2025-05-19 14:12:44 install libgnome-bg-4-2:amd64 <none> 43.2-2
2025-05-19 14:12:45 install xdg-desktop-portal-gnome:amd64 <none> 43.1-2
2025-05-19 14:12:45 install gnome-session:all <none> 43.0-1+deb12u1
2025-05-19 14:12:45 install xbitmaps:all <none> 1.1.1-2.2
2025-05-19 14:12:46 install libutempter0:amd64 <none> 1.2.1-3
2025-05-19 14:12:46 install xterm:amd64 <none> 379-1
2025-05-19 14:12:47 install gnome-terminal-data:all <none> 3.46.8-1
2025-05-19 14:12:49 install libvte-2.91-common:amd64 <none> 0.70.6-2~deb12u1
2025-05-19 14:12:49 install libvte-2.91-0:amd64 <none> 0.70.6-2~deb12u1
2025-05-19 14:12:50 install gnome-terminal:amd64 <none> 3.46.8-1
2025-05-19 14:12:50 install libxmuu1:amd64 <none> 2:1.1.3-3
2025-05-19 14:12:50 install x11-xserver-utils:amd64 <none> 7.7+9+b1
2025-05-19 14:12:51 install gdm3:amd64 <none> 43.0-3
2025-05-19 14:12:52 install geoclue-2.0:amd64 <none> 2.6.0-2+deb12u1
2025-05-19 14:12:52 install gir1.2-cogl-1.0:amd64 <none> 1.22.8-3+b1
2025-05-19 14:12:52 install gir1.2-coglpango-1.0:amd64 <none> 1.22.8-3+b1
2025-05-19 14:12:53 install gir1.2-clutter-1.0:amd64 <none> 1.26.4+dfsg-4
2025-05-19 14:12:53 install gir1.2-evince-3.0:amd64 <none> 43.1-2+b1
2025-05-19 14:12:53 install gir1.2-geocodeglib-2.0:amd64 <none> 3.26.3-6
2025-05-19 14:12:53 install libgnome-menu-3-0:amd64 <none> 3.36.0-1.1
2025-05-19 14:12:54 install gir1.2-gmenu-3.0:amd64 <none> 3.36.0-1.1
2025-05-19 14:12:54 install gir1.2-gnomedesktop-4.0:amd64 <none> 43.2-2
2025-05-19 14:12:54 install gir1.2-goa-1.0:amd64 <none> 3.46.0-1
2025-05-19 14:12:54 install libsoup-gnome2.4-1:amd64 <none> 2.74.3-1+deb12u1
2025-05-19 14:12:55 install gir1.2-soup-2.4:amd64 <none> 2.74.3-1+deb12u1
2025-05-19 14:12:55 install libtotem-plparser-common:all <none> 3.26.6-1
2025-05-19 14:12:55 install libtotem-plparser18:amd64 <none> 3.26.6-1+b1
2025-05-19 14:12:56 install libgrilo-0.3-0:amd64 <none> 0.3.15-1
2025-05-19 14:12:56 install gir1.2-grilo-0.3:amd64 <none> 0.3.15-1
2025-05-19 14:12:56 install gir1.2-gst-plugins-base-1.0:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:12:57 install gir1.2-gst-plugins-bad-1.0:amd64 <none> 1.22.0-4+deb12u5
2025-05-19 14:12:57 install gir1.2-gtkclutter-1.0:amd64 <none> 1.8.4-4+b1
2025-05-19 14:12:57 install libgtksourceview-4-common:all <none> 4.8.4-4
2025-05-19 14:12:58 install libgtksourceview-4-0:amd64 <none> 4.8.4-4
2025-05-19 14:12:58 install gir1.2-gtksource-4:amd64 <none> 4.8.4-4
2025-05-19 14:12:59 install gir1.2-handy-1:amd64 <none> 1.8.1-1
2025-05-19 14:12:59 install libjavascriptcoregtk-4.0-18:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:13:02 install gir1.2-javascriptcoregtk-4.0:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:13:02 install libmalcontent-0-0:amd64 <none> 0.11.0-4
2025-05-19 14:13:02 install gir1.2-malcontent-0:amd64 <none> 0.11.0-4
2025-05-19 14:13:02 install libmediaart-2.0-0:amd64 <none> 1.9.6-1
2025-05-19 14:13:03 install gir1.2-mediaart-2.0:amd64 <none> 1.9.6-1
2025-05-19 14:13:03 install gir1.2-notify-0.7:amd64 <none> 0.8.1-1
2025-05-19 14:13:03 install libpackagekit-glib2-18:amd64 <none> 1.2.6-5
2025-05-19 14:13:03 install gir1.2-packagekitglib-1.0:amd64 <none> 1.2.6-5
2025-05-19 14:13:04 install librhythmbox-core10:amd64 <none> 3.4.6-2+b1
2025-05-19 14:13:04 install gir1.2-rb-3.0:amd64 <none> 3.4.6-2+b1
2025-05-19 14:13:04 install librest-1.0-0:amd64 <none> 0.9.1-6
2025-05-19 14:13:05 install gir1.2-rest-1.0:amd64 <none> 0.9.1-6
2025-05-19 14:13:05 install gir1.2-secret-1:amd64 <none> 0.20.5-3
2025-05-19 14:13:05 install libshumate-common:all <none> 1.0.3-2
2025-05-19 14:13:05 install libshumate-1.0-1:amd64 <none> 1.0.3-2
2025-05-19 14:13:06 install gir1.2-shumate-1.0:amd64 <none> 1.0.3-2
2025-05-19 14:13:06 install gir1.2-totemplparser-1.0:amd64 <none> 3.26.6-1+b1
2025-05-19 14:13:06 install libtotem0:amd64 <none> 43.0-2
2025-05-19 14:13:06 install gir1.2-totem-1.0:amd64 <none> 43.0-2
2025-05-19 14:13:07 install libtracker-sparql-3.0-0:amd64 <none> 3.4.2-1
2025-05-19 14:13:07 install gir1.2-tracker-3.0:amd64 <none> 3.4.2-1
2025-05-19 14:13:07 install libwebkit2gtk-4.0-37:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:13:14 install gir1.2-webkit2-4.0:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:13:15 install libxres1:amd64 <none> 2:1.2.1-1
2025-05-19 14:13:15 install libwnck-3-common:all <none> 43.0-3
2025-05-19 14:13:16 install libwnck-3-0:amd64 <none> 43.0-3
2025-05-19 14:13:16 install gir1.2-wnck-3.0:amd64 <none> 43.0-3
2025-05-19 14:13:16 install gjs:amd64 <none> 1.74.2-1+deb12u1
2025-05-19 14:13:17 install libgnomekbd-common:all <none> 3.28.1-1
2025-05-19 14:13:17 install libxklavier16:amd64 <none> 5.4-4
2025-05-19 14:13:17 install libgnomekbd8:amd64 <none> 3.28.1-1
2025-05-19 14:13:18 install gkbd-capplet:amd64 <none> 3.28.1-1
2025-05-19 14:13:18 install gnome-bluetooth-sendto:amd64 <none> 42.5-3
2025-05-19 14:13:18 install libgtksourceview-5-common:all <none> 5.6.2-1
2025-05-19 14:13:19 install libgtksourceview-5-0:amd64 <none> 5.6.2-1
2025-05-19 14:13:20 install gnome-calculator:amd64 <none> 1:43.0.1-2
2025-05-19 14:13:22 install gnome-characters:amd64 <none> 43.1-1+deb12u1
2025-05-19 14:13:23 install libfolks26:amd64 <none> 0.15.5-2+b1
2025-05-19 14:13:23 install libfolks-eds26:amd64 <none> 0.15.5-2+b1
2025-05-19 14:13:23 install libportal1:amd64 <none> 0.6-4
2025-05-19 14:13:24 install gnome-contacts:amd64 <none> 43.1-1
2025-05-19 14:13:24 install libcolord-gtk4-1:amd64 <none> 0.3.0-3.1
2025-05-19 14:13:25 install libgnome-bluetooth-ui-3.0-13:amd64 <none> 42.5-3
2025-05-19 14:13:25 install libgnome-rr-4-2:amd64 <none> 43.2-2
2025-05-19 14:13:25 install libgoa-backend-1.0-1:amd64 <none> 3.46.0-1
2025-05-19 14:13:25 install libgtop2-common:all <none> 2.40.0-2
2025-05-19 14:13:26 install libgtop-2.0-11:amd64 <none> 2.40.0-2
2025-05-19 14:13:26 install libnma-gtk4-0:amd64 <none> 1.10.6-1
2025-05-19 14:13:26 install libpwquality-common:all <none> 1.4.5-1
2025-05-19 14:13:27 install libpwquality1:amd64 <none> 1.4.5-1+b1
2025-05-19 14:13:27 install libtalloc2:amd64 <none> 2.4.0-f2
2025-05-19 14:13:27 install libtevent0:amd64 <none> 0.14.1-1
2025-05-19 14:13:28 install libldb2:amd64 <none> 2:2.6.2+samba4.17.12+dfsg-0+deb12u1
2025-05-19 14:13:28 install libwbclient0:amd64 <none> 2:4.17.12+dfsg-0+deb12u1
2025-05-19 14:13:28 install samba-libs:amd64 <none> 2:4.17.12+dfsg-0+deb12u1
2025-05-19 14:13:31 install libsmbclient:amd64 <none> 2:4.17.12+dfsg-0+deb12u1
2025-05-19 14:13:31 install libsnapd-glib-2-1:amd64 <none> 1.63-5
2025-05-19 14:13:31 install libudisks2-0:amd64 <none> 2.9.4-4
2025-05-19 14:13:31 install gnome-control-center-data:all <none> 1:43.6-2~deb12u1
2025-05-19 14:13:33 install gnome-control-center:amd64 <none> 1:43.6-2~deb12u1
2025-05-19 14:13:34 install libblockdev-part-err2:amd64 <none> 2.28-2
2025-05-19 14:13:34 install libblockdev-utils2:amd64 <none> 2.28-2
2025-05-19 14:13:34 install libparted2:amd64 <none> 3.5-3
2025-05-19 14:13:35 install libparted-fs-resize0:amd64 <none> 3.5-3
2025-05-19 14:13:35 install libblockdev-fs2:amd64 <none> 2.28-2
2025-05-19 14:13:35 install libblockdev-loop2:amd64 <none> 2.28-2
2025-05-19 14:13:36 install libblockdev-part2:amd64 <none> 2.28-2
2025-05-19 14:13:36 install libblockdev-swap2:amd64 <none> 2.28-2
2025-05-19 14:13:36 install parted:amd64 <none> 3.5-3
2025-05-19 14:13:36 install libatasmart4:amd64 <none> 0.19-5
2025-05-19 14:13:37 install libblockdev2:amd64 <none> 2.28-2
2025-05-19 14:13:37 install udisks2:amd64 <none> 2.9.4-4
2025-05-19 14:13:38 install gnome-disk-utility:amd64 <none> 43.0-1
2025-05-19 14:13:38 install gnome-font-viewer:amd64 <none> 43.0-1
2025-05-19 14:13:39 install gnome-logs:amd64 <none> 43.0-1
2025-05-19 14:13:40 install gnome-menus:amd64 <none> 3.36.0-1.1
2025-05-19 14:13:40 install gnome-online-accounts:amd64 <none> 3.46.0-1
2025-05-19 14:13:41 install gvfs-common:all <none> 1.50.3-1
2025-05-19 14:13:41 install gvfs-libs:amd64 <none> 1.50.3-1
2025-05-19 14:13:42 install libudfread0:amd64 <none> 1.1.2-1
2025-05-19 14:13:42 install libbluray2:amd64 <none> 1:1.3.4-1
2025-05-19 14:13:42 install gvfs-daemons:amd64 <none> 1.50.3-1
2025-05-19 14:13:42 install gvfs:amd64 <none> 1.50.3-1
2025-05-19 14:13:43 install gnome-shell-extensions:all <none> 43.1-1
2025-05-19 14:13:43 install gnome-software-common:all <none> 43.5-1~deb12u1
2025-05-19 14:13:44 install libcairo-perl:amd64 <none> 1.109-3+b1
2025-05-19 14:13:44 install libextutils-depends-perl:all <none> 0.8001-2
2025-05-19 14:13:45 install libglib-perl:amd64 <none> 3:1.329.3-2+b2
2025-05-19 14:13:45 install libcairo-gobject-perl:amd64 <none> 1.005-4
2025-05-19 14:13:45 install libglib-object-introspection-perl:amd64 <none> 0.049-3
2025-05-19 14:13:46 install libgtk3-perl:all <none> 0.038-3
2025-05-19 14:13:46 install packagekit:amd64 <none> 1.2.6-5
2025-05-19 14:13:47 install python3-dateutil:all <none> 2.8.2-2
2025-05-19 14:13:47 install python3-distro-info:all <none> 1.5+deb12u1
2025-05-19 14:13:48 install lsb-release:all <none> 12.0-1
2025-05-19 14:13:48 install python3-lazr.uri:all <none> 1.0.6-3
2025-05-19 14:13:48 install python3-wadllib:all <none> 1.3.6-4
2025-05-19 14:13:48 install python3-distro:all <none> 1.8.0-1
2025-05-19 14:13:49 install python3-blinker:all <none> 1.5-1
2025-05-19 14:13:49 install python3-cffi-backend:amd64 <none> 1.15.1-5+b1
2025-05-19 14:13:49 install python3-cryptography:amd64 <none> 38.0.4-3+deb12u1
2025-05-19 14:13:50 install python3-jwt:all <none> 2.6.0-1
2025-05-19 14:13:50 install python3-oauthlib:all <none> 3.2.2-1
2025-05-19 14:13:51 install python3-lazr.restfulclient:all <none> 0.14.5-1
2025-05-19 14:13:51 install python3-software-properties:all <none> 0.99.30-4.1~deb12u1
2025-05-19 14:13:51 install python3-dbus:amd64 <none> 1.3.2-4+b1
2025-05-19 14:13:52 install software-properties-common:all <none> 0.99.30-4.1~deb12u1
2025-05-19 14:13:52 install software-properties-gtk:all <none> 0.99.30-4.1~deb12u1
2025-05-19 14:13:52 install gnome-software:amd64 <none> 43.5-1~deb12u1
2025-05-19 14:13:53 install nautilus-data:all <none> 43.2-1
2025-05-19 14:13:54 install tracker:amd64 <none> 3.4.2-1
2025-05-19 14:13:55 install libcue2:amd64 <none> 2.2.1-4+deb12u1
2025-05-19 14:13:55 install libexiv2-27:amd64 <none> 0.27.6-1
2025-05-19 14:13:56 install libgexiv2-2:amd64 <none> 0.14.0-1+b1
2025-05-19 14:13:56 install libgif7:amd64 <none> 5.2.1-2.5
2025-05-19 14:13:56 install libgsf-1-common:all <none> 1.14.50-1+deb12u1
2025-05-19 14:13:57 install libgsf-1-114:amd64 <none> 1.14.50-1+deb12u1
2025-05-19 14:13:57 install libiptcdata0:amd64 <none> 1.0.5-2.3
2025-05-19 14:13:57 install usb.ids:all <none> 2024.07.04-0+deb12u1
2025-05-19 14:13:58 install libosinfo-l10n:all <none> 1.10.0-2
2025-05-19 14:13:58 install osinfo-db:all <none> 0.20221130-2
2025-05-19 14:14:00 install libosinfo-1.0-0:amd64 <none> 1.10.0-2
2025-05-19 14:14:00 install tracker-extract:amd64 <none> 3.4.3-1
2025-05-19 14:14:01 install tracker-miner-fs:amd64 <none> 3.4.3-1
2025-05-19 14:14:02 install libportal-gtk4-1:amd64 <none> 0.6-4
2025-05-19 14:14:02 install nautilus:amd64 <none> 43.2-1
2025-05-19 14:14:02 install gstreamer1.0-gtk3:amd64 <none> 1.22.0-5+deb12u2
2025-05-19 14:14:03 install gnome-sushi:amd64 <none> 43.0-2
2025-05-19 14:14:03 install libsigc++-2.0-0v5:amd64 <none> 2.12.0-1
2025-05-19 14:14:04 install libglibmm-2.4-1v5:amd64 <none> 2.66.5-2
2025-05-19 14:14:04 install libatkmm-1.6-1v5:amd64 <none> 2.28.3-1
2025-05-19 14:14:04 install libcairomm-1.0-1v5:amd64 <none> 1.14.4-2
2025-05-19 14:14:05 install libpangomm-1.4-1v5:amd64 <none> 2.46.3-1
2025-05-19 14:14:05 install libgtkmm-3.0-1v5:amd64 <none> 3.24.7-1
2025-05-19 14:14:05 install gnome-system-monitor:amd64 <none> 42.0-2
2025-05-19 14:14:07 install libeditorconfig0:amd64 <none> 0.12.6-0.1
2025-05-19 14:14:07 install gnome-text-editor:amd64 <none> 43.2-1
2025-05-19 14:14:08 install gnome-themes-extra-data:all <none> 3.28-2
2025-05-19 14:14:09 install gtk2-engines-pixbuf:amd64 <none> 2.24.33-2+deb12u1
2025-05-19 14:14:10 install gnome-themes-extra:amd64 <none> 3.28-2
2025-05-19 14:14:10 install libyelp0:amd64 <none> 42.2-1
2025-05-19 14:14:10 install yelp-xsl:all <none> 42.1-2
2025-05-19 14:14:11 install yelp:amd64 <none> 42.2-1
2025-05-19 14:14:12 install gnome-user-docs:all <none> 43.0-2
2025-05-19 14:16:58 install libapache2-mod-dnssd:amd64 <none> 0.6-4
2025-05-19 14:16:58 install gnome-user-share:amd64 <none> 43.0-1
2025-05-19 14:16:58 install gstreamer1.0-packagekit:amd64 <none> 1.2.6-5
2025-05-19 14:16:59 install libcdio19:amd64 <none> 2.1.0-4
2025-05-19 14:16:59 install libcdio-cdda2:amd64 <none> 10.2+2.0.1-1
2025-05-19 14:16:59 install libcdio-paranoia2:amd64 <none> 10.2+2.0.1-1
2025-05-19 14:16:59 install libgdata-common:all <none> 0.18.1-2
2025-05-19 14:17:00 install libgdata22:amd64 <none> 0.18.1-2
2025-05-19 14:17:00 install libplist3:amd64 <none> 2.2.0-6+b2
2025-05-19 14:17:00 install libusbmuxd6:amd64 <none> 2.0.2-3
2025-05-19 14:17:00 install libimobiledevice6:amd64 <none> 1.3.0-6+b3
2025-05-19 14:17:01 install libmtp-common:all <none> 1.1.20-1
2025-05-19 14:17:01 install libmtp9:amd64 <none> 1.1.20-1
2025-05-19 14:17:01 install libnfs13:amd64 <none> 4.0.0-1
2025-05-19 14:17:01 install gvfs-backends:amd64 <none> 1.50.3-1
2025-05-19 14:17:02 install gvfs-fuse:amd64 <none> 1.50.3-1
2025-05-19 14:17:02 install libatk-adaptor:amd64 <none> 2.46.0-5
2025-05-19 14:17:02 install libcanberra-pulse:amd64 <none> 0.30-10
2025-05-19 14:17:02 install libpam-gnome-keyring:amd64 <none> 42.1-1+b2
2025-05-19 14:17:03 install libproxy1-plugin-gsettings:amd64 <none> 0.4.18-1.2
2025-05-19 14:17:03 install libproxy1-plugin-webkit:amd64 <none> 0.4.18-1.2
2025-05-19 14:17:03 install python3-cairo:amd64 <none> 1.20.1-5+b1
2025-05-19 14:17:03 install python3-cups:amd64 <none> 2.0.1-5+b4
2025-05-19 14:17:03 install python3-cupshelpers:all <none> 1.5.18-1
2025-05-19 14:17:04 install system-config-printer-common:all <none> 1.5.18-1
2025-05-19 14:17:04 install system-config-printer-udev:amd64 <none> 1.5.18-1
2025-05-19 14:17:04 install libdmapsharing-3.0-2:amd64 <none> 2.9.41-3+b1
2025-05-19 14:17:05 install libgom-1.0-0:amd64 <none> 0.4-1
2025-05-19 14:17:05 install liboauth0:amd64 <none> 1.0.3-5
2025-05-19 14:17:05 install grilo-plugins-0.3:amd64 <none> 0.3.15-2
2025-05-19 14:17:06 install totem-common:all <none> 43.0-2
2025-05-19 14:17:07 install gstreamer1.0-gl:amd64 <none> 1.22.0-3+deb12u4
2025-05-19 14:17:07 install totem:amd64 <none> 43.0-2
2025-05-19 14:17:08 install zenity-common:all <none> 3.44.0-1
2025-05-19 14:17:10 install zenity:amd64 <none> 3.44.0-1
2025-05-19 14:17:10 install gnome-core:amd64 <none> 1:43+1
2025-05-19 14:17:10 install libproxy1-plugin-networkmanager:amd64 <none> 0.4.18-1.2
2025-05-19 14:17:10 install libayatana-ido3-0.4-0:amd64 <none> 0.9.3-1
2025-05-19 14:17:11 install libayatana-indicator3-7:amd64 <none> 0.9.3-1
2025-05-19 14:17:11 install libdbusmenu-gtk3-4:amd64 <none> 18.10.20180917~bzr492+repack1-3
2025-05-19 14:17:11 install libayatana-appindicator3-1:amd64 <none> 0.5.92-1
2025-05-19 14:17:11 install libndp0:amd64 <none> 1.8-1+deb12u1
2025-05-19 14:17:12 install libteamdctl0:amd64 <none> 1.31-1
2025-05-19 14:17:12 install network-manager:amd64 <none> 1.42.4-1+deb12u1
2025-05-19 14:17:13 install network-manager-gnome:amd64 <none> 1.30.0-2
2025-05-19 14:17:14 install libjavascriptcoregtk-6.0-1:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:17:15 install libwebkitgtk-6.0-4:amd64 <none> 2.48.1-2~deb12u1
2025-05-19 14:17:20 install libedataserverui4-1.0-0:amd64 <none> 3.46.4-2
2025-05-19 14:17:20 install gnome-calendar:amd64 <none> 43.1-2
2025-05-19 14:17:20 install gnome-clocks:amd64 <none> 43.0-1
2025-05-19 14:17:21 install gnome-color-manager:amd64 <none> 3.36.0-1+b1
2025-05-19 14:17:22 install gnome-maps:amd64 <none> 43.5-2~deb12u1
2025-05-19 14:17:22 install python3-gi-cairo:amd64 <none> 3.42.2-3+b1
2025-05-19 14:17:23 install gnome-music:amd64 <none> 42.1-1
2025-05-19 14:17:24 install libraw20:amd64 <none> 0.20.2-2.1
2025-05-19 14:17:24 install shotwell-common:all <none> 0.30.17-1
2025-05-19 14:17:25 install shotwell:amd64 <none> 0.30.17-1+b1
2025-05-19 14:17:26 install gnome-weather:all <none> 43.0-1
2025-05-19 14:17:26 install libbrlapi0.8:amd64 <none> 6.5-7+deb12u1
2025-05-19 14:17:26 install python3-brlapi:amd64 <none> 6.5-7+deb12u1
2025-05-19 14:17:27 install liblouis-data:all <none> 3.24.0-1
2025-05-19 14:17:28 install liblouis20:amd64 <none> 3.24.0-1
2025-05-19 14:17:28 install python3-louis:all <none> 3.24.0-1
2025-05-19 14:17:29 install python3-pyatspi:all <none> 2.46.0-2
2025-05-19 14:17:29 install python3-xdg:all <none> 0.28-2
2025-05-19 14:17:29 install python3-speechd:all <none> 0.11.4-2
2025-05-19 14:17:29 install libaudio2:amd64 <none> 1.9.4-7
2025-05-19 14:17:30 install speech-dispatcher-audio-plugins:amd64 <none> 0.11.4-2
2025-05-19 14:17:30 install libdotconf0:amd64 <none> 1.3-0.3
2025-05-19 14:17:30 install libspeechd2:amd64 <none> 0.11.4-2
2025-05-19 14:17:30 install speech-dispatcher:amd64 <none> 0.11.4-2
2025-05-19 14:17:32 install xkbset:amd64 <none> 0.6-3
2025-05-19 14:17:32 install orca:all <none> 43.1-1
2025-05-19 14:17:35 install libges-1.0-0:amd64 <none> 1.22.0-2
2025-05-19 14:17:35 install libgupnp-av-1.0-3:amd64 <none> 0.14.1-1
2025-05-19 14:17:35 install libgupnp-dlna-2.0-4:amd64 <none> 0.12.0-3
2025-05-19 14:17:35 install librygel-core-2.8-0:amd64 <none> 0.42.1-1
2025-05-19 14:17:36 install librygel-db-2.8-0:amd64 <none> 0.42.1-1
2025-05-19 14:17:36 install librygel-renderer-2.8-0:amd64 <none> 0.42.1-1
2025-05-19 14:17:36 install librygel-server-2.8-0:amd64 <none> 0.42.1-1
2025-05-19 14:17:36 install rygel:amd64 <none> 0.42.1-1
2025-05-19 14:17:37 install librygel-renderer-gst-2.8-0:amd64 <none> 0.42.1-1
2025-05-19 14:17:37 install rygel-playbin:amd64 <none> 0.42.1-1
2025-05-19 14:17:37 install rygel-tracker:amd64 <none> 0.42.1-1
2025-05-19 14:17:37 install xdg-utils:all <none> 1.1.3-4.1
2025-05-19 14:17:38 install simple-scan:amd64 <none> 42.5-2
2025-05-19 14:17:39 install gnome-sound-recorder:all <none> 43~beta-1
2025-05-19 14:17:39 install gnome-tweaks:all <none> 42~beta-4
2025-05-19 14:17:40 install libgsf-bin:amd64 <none> 1.14.50-1+deb12u1
2025-05-19 14:17:40 install libreoffice-style-colibre:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:41 install libuno-sal3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:42 install libuno-salhelpergcc3-3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:42 install libuno-cppu3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:42 install uno-libs-private:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:42 install liblangtag-common:all <none> 0.6.4-2
2025-05-19 14:17:42 install liblangtag1:amd64 <none> 0.6.4-2
2025-05-19 14:17:43 install libuno-cppuhelpergcc3-3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:43 install libuno-purpenvhelpergcc3-3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:43 install ure:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:44 install libnumbertext-data:all <none> 1.0.11-1
2025-05-19 14:17:44 install libreoffice-common:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:17:50 install libboost-thread1.74.0:amd64 <none> 1.74.0+ds1-21
2025-05-19 14:17:50 install libboost-locale1.74.0:amd64 <none> 1.74.0+ds1-21
2025-05-19 14:17:51 install libclucene-core1v5:amd64 <none> 2.3.3.4+dfsg-1.1
2025-05-19 14:17:51 install libclucene-contribs1v5:amd64 <none> 2.3.3.4+dfsg-1.1
2025-05-19 14:17:51 install libeot0:amd64 <none> 0.01-5+b1
2025-05-19 14:17:51 install libexttextcat-data:all <none> 3.4.5-1
2025-05-19 14:17:52 install libexttextcat-2.0-0:amd64 <none> 3.4.5-1
2025-05-19 14:17:52 install libgpgmepp6:amd64 <none> 1.18.0-3+b1
2025-05-19 14:17:52 install libmythes-1.2-0:amd64 <none> 2:1.2.5-1
2025-05-19 14:17:52 install libnumbertext-1.0-0:amd64 <none> 1.0.11-1
2025-05-19 14:17:53 install libboost-filesystem1.74.0:amd64 <none> 1.74.0+ds1-21
2025-05-19 14:17:53 install libboost-iostreams1.74.0:amd64 <none> 1.74.0+ds1-21
2025-05-19 14:17:53 install liborcus-parser-0.17-0:amd64 <none> 0.17.2-2+b2
2025-05-19 14:17:53 install liborcus-0.17-0:amd64 <none> 0.17.2-2+b2
2025-05-19 14:17:54 install libmhash2:amd64 <none> 0.9.9.9-9
2025-05-19 14:17:54 install librasqal3:amd64 <none> 0.9.33-2
2025-05-19 14:17:54 install librdf0:amd64 <none> 1.0.17-3
2025-05-19 14:17:54 install librevenge-0.0-0:amd64 <none> 0.0.5-3
2025-05-19 14:17:55 install libxmlsec1:amd64 <none> 1.2.37-2
2025-05-19 14:17:55 install libxmlsec1-nss:amd64 <none> 1.2.37-2
2025-05-19 14:17:55 install libreoffice-core:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:02 install libreoffice-gnome:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:02 install libreoffice-base-core:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:03 install libabw-0.1-1:amd64 <none> 0.1.3-1
2025-05-19 14:18:03 install libe-book-0.1-1:amd64 <none> 0.1.3-2+b2
2025-05-19 14:18:03 install libepubgen-0.1-1:amd64 <none> 0.1.1-1
2025-05-19 14:18:03 install libetonyek-0.1-1:amd64 <none> 0.1.10-3+b1
2025-05-19 14:18:04 install libmwaw-0.3-3:amd64 <none> 0.3.21-1
2025-05-19 14:18:04 install libodfgen-0.1-1:amd64 <none> 0.1.8-2
2025-05-19 14:18:05 install libstaroffice-0.0-0:amd64 <none> 0.0.7-1
2025-05-19 14:18:05 install libwpd-0.10-10:amd64 <none> 0.10.3-2+b1
2025-05-19 14:18:05 install libwpg-0.3-3:amd64 <none> 0.3.3-1
2025-05-19 14:18:05 install libwps-0.4-4:amd64 <none> 0.4.13-1
2025-05-19 14:18:06 install libreoffice-writer:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:09 install libsuitesparseconfig5:amd64 <none> 1:5.12.0+dfsg-2
2025-05-19 14:18:09 install libcolamd2:amd64 <none> 1:5.12.0+dfsg-2
2025-05-19 14:18:09 install lp-solve:amd64 <none> 5.5.2.5-2
2025-05-19 14:18:09 install libreoffice-calc:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:11 install libcdr-0.1-1:amd64 <none> 0.1.6-2+b2
2025-05-19 14:18:12 install libfreehand-0.1-1:amd64 <none> 0.1.2-3
2025-05-19 14:18:12 install libmspub-0.1-1:amd64 <none> 0.1.4-3+b3
2025-05-19 14:18:12 install libpagemaker-0.0-0:amd64 <none> 0.0.4-1
2025-05-19 14:18:12 install libqxp-0.0-0:amd64 <none> 0.0.2-1+b3
2025-05-19 14:18:12 install libvisio-0.1-1:amd64 <none> 0.1.7-1+b3
2025-05-19 14:18:13 install libzmf-0.0-0:amd64 <none> 0.0.2-1+b5
2025-05-19 14:18:13 install libreoffice-draw:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:14 install libbox2d2:amd64 <none> 2.4.1-3
2025-05-19 14:18:14 install libreoffice-impress:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:18:15 install rhythmbox-data:all <none> 3.4.6-2
2025-05-19 14:18:16 install media-player-info:all <none> 24-2
2025-05-19 14:18:16 install rhythmbox:amd64 <none> 3.4.6-2+b1
2025-05-19 14:18:17 install seahorse:amd64 <none> 43.0-1
2025-05-19 14:18:18 install xdg-user-dirs:amd64 <none> 0.18-1
2025-05-19 14:18:19 install xdg-user-dirs-gtk:amd64 <none> 0.11-1
2025-05-19 14:18:19 install librabbitmq4:amd64 <none> 0.11.0-1+deb12u1
2025-05-19 14:18:19 install libcjson1:amd64 <none> 1.7.15-1+deb12u2
2025-05-19 14:18:19 install libmbedcrypto7:amd64 <none> 2.28.3-1
2025-05-19 14:18:20 install librist4:amd64 <none> 0.2.7+dfsg-1
2025-05-19 14:18:20 install libssh-gcrypt-4:amd64 <none> 0.10.6-0+deb12u1
2025-05-19 14:18:20 install libnorm1:amd64 <none> 1.5.9+dfsg-2
2025-05-19 14:18:20 install libpgm-5.3-0:amd64 <none> 5.3.128~dfsg-2
2025-05-19 14:18:21 install libsodium23:amd64 <none> 1.0.18-1
2025-05-19 14:18:21 install libzmq5:amd64 <none> 4.3.4-6
2025-05-19 14:18:21 install libavformat59:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:18:22 install libmysofa1:amd64 <none> 1.3.1~dfsg0-1
2025-05-19 14:18:22 install libplacebo208:amd64 <none> 4.208.0-3
2025-05-19 14:18:23 install libsphinxbase3:amd64 <none> 0.8+5prealpha+1-16
2025-05-19 14:18:23 install libpocketsphinx3:amd64 <none> 0.8+5prealpha+1-15
2025-05-19 14:18:23 install libpostproc56:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:18:23 install librubberband2:amd64 <none> 3.1.2+dfsg0-1
2025-05-19 14:18:23 install libswscale6:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:18:24 install libvidstab1.1:amd64 <none> 1.1.0-2+b1
2025-05-19 14:18:24 install libzimg2:amd64 <none> 3.0.4+ds1-1
2025-05-19 14:18:24 install libavfilter8:amd64 <none> 7:5.1.6-0+deb12u1
2025-05-19 14:18:25 install gstreamer1.0-libav:amd64 <none> 1.22.0-2
2025-05-19 14:18:25 install liba52-0.7.4:amd64 <none> 0.7.4-20
2025-05-19 14:18:25 install libmpeg2-4:amd64 <none> 0.5.1-9
2025-05-19 14:18:26 install libopencore-amrnb0:amd64 <none> 0.1.6-1
2025-05-19 14:18:26 install libopencore-amrwb0:amd64 <none> 0.1.6-1
2025-05-19 14:18:26 install libsidplay1v5:amd64 <none> 1.36.60-1
2025-05-19 14:18:26 install gstreamer1.0-plugins-ugly:amd64 <none> 1.22.0-2+deb12u1
2025-05-19 14:18:27 install libgpod4:amd64 <none> 0.8.3-17+b1
2025-05-19 14:18:27 install liblirc-client0:amd64 <none> 0.10.1-7.2
2025-05-19 14:18:27 install python3-markupsafe:amd64 <none> 2.1.2-1+b1
2025-05-19 14:18:27 install python3-mako:all <none> 1.2.4+ds-1
2025-05-19 14:18:28 install rhythmbox-plugins:amd64 <none> 3.4.6-2+b1
2025-05-19 14:18:28 install libburn4:amd64 <none> 1.5.4-1
2025-05-19 14:18:28 install libjte2:amd64 <none> 1.22-3
2025-05-19 14:18:29 install libisofs6:amd64 <none> 1.5.4-1
2025-05-19 14:18:29 install libbrasero-media3-1:amd64 <none> 3.12.3-2
2025-05-19 14:18:29 install rhythmbox-plugin-cdrecorder:amd64 <none> 3.4.6-2+b1
2025-05-19 14:18:29 install libportal-gtk3-1:amd64 <none> 0.6-4
2025-05-19 14:18:30 install totem-plugins:amd64 <none> 43.0-2
2025-05-19 14:18:30 install gnome:amd64 <none> 1:43+1
2025-05-19 14:18:30 install gnome-2048:amd64 <none> 3.38.2-3
2025-05-19 14:18:30 install gnome-accessibility-themes:all <none> 3.28-2
2025-05-19 14:18:36 install hoichess:amd64 <none> 0.22.0-3
2025-05-19 14:18:36 install gnome-chess:amd64 <none> 1:43.1-1
2025-05-19 14:18:37 install gnome-klotski:amd64 <none> 1:3.38.2-1
2025-05-19 14:18:38 install gnome-mahjongg:amd64 <none> 1:3.38.3-2
2025-05-19 14:18:39 install gnome-mines:amd64 <none> 1:40.1-1
2025-05-19 14:18:40 install gnome-nibbles:amd64 <none> 1:3.38.2-2+b1
2025-05-19 14:18:40 install gnome-robots:amd64 <none> 1:40.0-2
2025-05-19 14:18:41 install libqqwing2v5:amd64 <none> 1.3.4-1.1+b1
2025-05-19 14:18:41 install gnome-sudoku:amd64 <none> 1:43.1-1
2025-05-19 14:18:42 install gnome-taquin:amd64 <none> 3.38.1-2+b1
2025-05-19 14:18:43 install gnome-tetravex:amd64 <none> 1:3.38.2-3
2025-05-19 14:18:44 install hitori:amd64 <none> 3.38.4-2
2025-05-19 14:18:45 install iagno:amd64 <none> 1:3.38.1-2
2025-05-19 14:18:46 install lightsoff:amd64 <none> 1:40.0.1-1
2025-05-19 14:18:46 install quadrapassel:amd64 <none> 1:40.2-1
2025-05-19 14:18:47 install swell-foop:amd64 <none> 1:41.1-1
2025-05-19 14:18:48 install tali:amd64 <none> 1:40.9-1
2025-05-19 14:18:48 install gnome-games:all <none> 1:43+1
2025-05-19 14:18:49 install gnome-icon-theme:all <none> 3.12.0-5
2025-05-19 14:18:54 install libostree-1-1:amd64 <none> 2022.7-2+deb12u1
2025-05-19 14:18:55 install libflatpak0:amd64 <none> 1.14.10-1~deb12u1
2025-05-19 14:18:55 install libmalcontent-ui-1-1:amd64 <none> 0.11.0-4
2025-05-19 14:18:55 install pkexec:amd64 <none> 122-3
2025-05-19 14:18:55 install gnome-initial-setup:amd64 <none> 43.2-6
2025-05-19 14:18:56 install gnome-keyring-pkcs11:amd64 <none> 42.1-1+b2
2025-05-19 14:18:56 install libwinpr2-2:amd64 <none> 2.10.0+dfsg1-1
2025-05-19 14:18:56 install libfreerdp2-2:amd64 <none> 2.10.0+dfsg1-1
2025-05-19 14:18:57 install libfreerdp-server2-2:amd64 <none> 2.10.0+dfsg1-1
2025-05-19 14:18:57 install libtss2-rc0:amd64 <none> 3.2.1-3
2025-05-19 14:18:57 install libtss2-tctildr0:amd64 <none> 3.2.1-3
2025-05-19 14:18:57 install gnome-remote-desktop:amd64 <none> 43.3-1
2025-05-19 14:18:58 install gnome-shell-extension-prefs:amd64 <none> 43.9-0+deb12u2
2025-05-19 14:18:58 install gsfonts:all <none> 2:20200910-7
2025-05-19 14:18:58 install hyphen-en-us:all <none> 2.8.8-7
2025-05-19 14:18:58 install i965-va-driver:amd64 <none> 2.4.1+dfsg1-1
2025-05-19 14:18:58 install ibus-data:all <none> 1.5.27-5
2025-05-19 14:19:02 install python3-ibus-1.0:all <none> 1.5.27-5
2025-05-19 14:19:02 install ibus:amd64 <none> 1.5.27-5
2025-05-19 14:19:02 install libgtk2.0-common:all <none> 2.24.33-2+deb12u1
2025-05-19 14:19:04 install libgtk2.0-0:amd64 <none> 2.24.33-2+deb12u1
2025-05-19 14:19:04 install ibus-gtk:amd64 <none> 1.5.27-5
2025-05-19 14:19:04 install ibus-gtk3:amd64 <none> 1.5.27-5
2025-05-19 14:19:05 install ibus-gtk4:amd64 <none> 1.5.27-5
2025-05-19 14:19:05 install iio-sensor-proxy:amd64 <none> 3.0-2
2025-05-19 14:19:05 install im-config:all <none> 0.55-2
2025-05-19 14:19:06 install libigdgmm12:amd64 <none> 22.3.3+ds1-1
2025-05-19 14:19:06 install intel-media-va-driver:amd64 <none> 23.1.1+dfsg1-1
2025-05-19 14:19:07 install ipp-usb:amd64 <none> 0.9.23-1+b4
2025-05-19 14:19:07 install libnl-3-200:amd64 <none> 3.7.0-0.2+b1
2025-05-19 14:19:07 install libnl-genl-3-200:amd64 <none> 3.7.0-0.2+b1
2025-05-19 14:19:08 install iw:amd64 <none> 5.19-1
2025-05-19 14:19:08 install javascript-common:all <none> 11+nmu1
2025-05-19 14:19:08 install libonig5:amd64 <none> 6.9.8-1
2025-05-19 14:19:08 install libjq1:amd64 <none> 1.6-2.1
2025-05-19 14:19:09 install jq:amd64 <none> 1.6-2.1
2025-05-19 14:19:09 install libaacs0:amd64 <none> 0.11.1-2
2025-05-19 14:19:09 install libauthen-sasl-perl:all <none> 2.1600-3
2025-05-19 14:19:09 install libbdplus0:amd64 <none> 0.2.0-3
2025-05-19 14:19:10 install libvolume-key1:amd64 <none> 0.3.12-5+b1
2025-05-19 14:19:10 install libblockdev-crypto2:amd64 <none> 2.28-2
2025-05-19 14:19:10 install libcanberra-gtk3-module:amd64 <none> 0.30-10
2025-05-19 14:19:10 install libclone-perl:amd64 <none> 0.46-1
2025-05-19 14:19:10 install libclutter-1.0-common:all <none> 1.26.4+dfsg-4
2025-05-19 14:19:11 install libcogl-common:all <none> 1.22.8-3
2025-05-19 14:19:11 install libdata-dump-perl:all <none> 1.25-1
2025-05-19 14:19:12 install libdecor-0-plugin-1-cairo:amd64 <none> 0.1.1-2
2025-05-19 14:19:12 install libencode-locale-perl:all <none> 1.05-3
2025-05-19 14:19:12 install libept1.6.0:amd64 <none> 1.2.1
2025-05-19 14:19:12 install libpcaudio0:amd64 <none> 1.2-2
2025-05-19 14:19:13 install libsonic0:amd64 <none> 0.2.0-12
2025-05-19 14:19:13 install libespeak-ng1:amd64 <none> 1.51+dfsg-10+deb12u2
2025-05-19 14:19:13 install libipc-system-simple-perl:all <none> 1.30-2
2025-05-19 14:19:13 install libfile-basedir-perl:all <none> 0.09-2
2025-05-19 14:19:13 install libregexp-ipv6-perl:all <none> 0.03-3
2025-05-19 14:19:14 install liburi-perl:all <none> 5.17-1
2025-05-19 14:19:14 install libfile-desktopentry-perl:all <none> 0.22-3
2025-05-19 14:19:14 install libtimedate-perl:all <none> 2.3300-2
2025-05-19 14:19:14 install libhttp-date-perl:all <none> 6.05-2
2025-05-19 14:19:15 install libfile-listing-perl:all <none> 6.15-1
2025-05-19 14:19:15 install libfile-mimeinfo-perl:all <none> 0.33-1
2025-05-19 14:19:15 install libfont-afm-perl:all <none> 1.20-4
2025-05-19 14:19:15 install libgail18:amd64 <none> 2.24.33-2+deb12u1
2025-05-19 14:19:15 install libgail-common:amd64 <none> 2.24.33-2+deb12u1
2025-05-19 14:19:16 install libgdk-pixbuf2.0-bin:amd64 <none> 2.42.10+dfsg-1+deb12u1
2025-05-19 14:19:16 install libopengl0:amd64 <none> 1.6.0-1
2025-05-19 14:19:16 install libglu1-mesa:amd64 <none> 9.0.2-1.1
2025-05-19 14:19:16 install libgphoto2-l10n:all <none> 2.5.30-1
2025-05-19 14:19:17 install libsgutils2-1.46-2:amd64 <none> 1.46-3
2025-05-19 14:19:17 install libgpod-common:amd64 <none> 0.8.3-17+b1
2025-05-19 14:19:17 install libgtk-3-bin:amd64 <none> 3.24.38-2~deb12u3
2025-05-19 14:19:17 install libgtk-4-bin:amd64 <none> 4.8.3+ds-2+deb12u1
2025-05-19 14:19:18 install libgtk2.0-bin:amd64 <none> 2.24.33-2+deb12u1
2025-05-19 14:19:18 install libhtml-tagset-perl:all <none> 3.20-6
2025-05-19 14:19:18 install libhtml-parser-perl:amd64 <none> 3.81-1
2025-05-19 14:19:19 install libio-html-perl:all <none> 1.004-3
2025-05-19 14:19:19 install liblwp-mediatypes-perl:all <none> 6.04-2
2025-05-19 14:19:19 install libhttp-message-perl:all <none> 6.44-1
2025-05-19 14:19:19 install libhtml-form-perl:all <none> 6.11-1
2025-05-19 14:19:19 install libhtml-tree-perl:all <none> 5.07-3
2025-05-19 14:19:20 install libhtml-format-perl:all <none> 2.16-2
2025-05-19 14:19:20 install libhttp-cookies-perl:all <none> 6.10-1
2025-05-19 14:19:20 install libhttp-daemon-perl:all <none> 6.16-1
2025-05-19 14:19:20 install libhttp-negotiate-perl:all <none> 6.01-2
2025-05-19 14:19:21 install perl-openssl-defaults:amd64 <none> 7+b1
2025-05-19 14:19:21 install libnet-ssleay-perl:amd64 <none> 1.92-2+b1
2025-05-19 14:19:21 install libio-socket-ssl-perl:all <none> 2.081-2
2025-05-19 14:19:21 install libio-stringy-perl:all <none> 2.111-3
2025-05-19 14:19:22 install libiw30:amd64 <none> 30~pre9-14
2025-05-19 14:19:22 install libjim0.81:amd64 <none> 0.81+dfsg0-2
2025-05-19 14:19:22 install libjxr0:amd64 <none> 1.2~git20170615.f752187-5
2025-05-19 14:19:22 install libjxr-tools:amd64 <none> 1.2~git20170615.f752187-5
2025-05-19 14:19:23 install libldap-common:all <none> 2.5.13+dfsg-5
2025-05-19 14:19:23 install liblouisutdml-data:all <none> 2.11.0-2
2025-05-19 14:19:23 install liblouisutdml9:amd64 <none> 2.11.0-2
2025-05-19 14:19:23 install liblouisutdml-bin:amd64 <none> 2.11.0-2
2025-05-19 14:19:23 install libnet-http-perl:all <none> 6.22-1
2025-05-19 14:19:24 install libtry-tiny-perl:all <none> 0.31-2
2025-05-19 14:19:24 install libwww-robotrules-perl:all <none> 6.02-1
2025-05-19 14:19:24 install libwww-perl:all <none> 6.68-1
2025-05-19 14:19:24 install liblwp-protocol-https-perl:all <none> 6.10-1
2025-05-19 14:19:25 install libwmflite-0.2-7:amd64 <none> 0.2.12-5.1
2025-05-19 14:19:25 install libmagickcore-6.q16-6-extra:amd64 <none> 8:6.9.11.60+dfsg-1.6+deb12u3
2025-05-19 14:19:25 install libnet-smtp-ssl-perl:all <none> 1.04-2
2025-05-19 14:19:25 install libmailtools-perl:all <none> 2.21-2
2025-05-19 14:19:25 install libmbim-utils:amd64 <none> 1.28.2-1
2025-05-19 14:19:26 install libminiupnpc17:amd64 <none> 2.2.4-1+b1
2025-05-19 14:19:26 install libmtp-runtime:amd64 <none> 1.1.20-1
2025-05-19 14:19:26 install libnatpmp1:amd64 <none> 20150609-7.1+b2
2025-05-19 14:19:26 install libxml-parser-perl:amd64 <none> 2.46-4
2025-05-19 14:19:27 install libxml-twig-perl:all <none> 1:3.52-2
2025-05-19 14:19:27 install libnet-dbus-perl:amd64 <none> 1.2.0-2
2025-05-19 14:19:27 install libnl-route-3-200:amd64 <none> 3.7.0-0.2+b1
2025-05-19 14:19:28 install libnss-mdns:amd64 <none> 0.15.1-3
2025-05-19 14:19:28 install libnss-myhostname:amd64 <none> 252.36-1~deb12u1
2025-05-19 14:19:28 install libntfs-3g89:amd64 <none> 1:2022.10.3-1+deb12u2
2025-05-19 14:19:28 install libpaper-utils:amd64 <none> 1.1.29
2025-05-19 14:19:28 install libpcap0.8:amd64 <none> 1.10.3-1
2025-05-19 14:19:29 install libpcsclite1:amd64 <none> 1.9.9-2
2025-05-19 14:19:29 install libperl4-corelibs-perl:all <none> 0.004-3
2025-05-19 14:19:29 install libpipewire-0.3-common:all <none> 0.3.65-3+deb12u1
2025-05-19 14:19:29 install libplymouth5:amd64 <none> 22.02.122-3
2025-05-19 14:19:30 install libqmi-utils:amd64 <none> 1.32.2-1
2025-05-19 14:19:30 install libreoffice-gtk3:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:30 install node-normalize.css:all <none> 8.0.1-5
2025-05-19 14:19:30 install node-clipboard:all <none> 2.0.11+ds+~cs9.6.11-1
2025-05-19 14:19:31 install node-prismjs:all <none> 1.29.0+dfsg+~1.26.0-1
2025-05-19 14:19:32 install libreoffice-help-common:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:41 install libreoffice-help-en-us:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:45 install libreoffice-l10n-es:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:46 install libreoffice-help-es:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:51 install libreoffice-math:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:51 install libreoffice-style-elementary:all <none> 4:7.4.7-1+deb12u8
2025-05-19 14:19:53 install libsasl2-modules:amd64 <none> 2.1.28+dfsg-10
2025-05-19 14:19:53 install libtie-ixhash-perl:all <none> 1.23-4
2025-05-19 14:19:53 install libvdpau-va-gl1:amd64 <none> 0.4.2-1+b1
2025-05-19 14:19:54 install libx11-protocol-perl:all <none> 0.56-9
2025-05-19 14:19:54 install libxapian30:amd64 <none> 1.4.22-1
2025-05-19 14:19:54 install libxatracker2:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:19:55 install libxcb-damage0:amd64 <none> 1.15-1
2025-05-19 14:19:55 install libxcb-icccm4:amd64 <none> 0.4.1-1.1
2025-05-19 14:19:55 install libxcb-image0:amd64 <none> 0.4.0-2
2025-05-19 14:19:55 install libxcb-keysyms1:amd64 <none> 0.4.0-1+b2
2025-05-19 14:19:56 install libxcb-render-util0:amd64 <none> 0.3.9-1+b1
2025-05-19 14:19:56 install libxcb-shape0:amd64 <none> 1.15-1
2025-05-19 14:19:56 install libxcb-xv0:amd64 <none> 1.15-1
2025-05-19 14:19:56 install libxml-xpathengine-perl:all <none> 0.14-2
2025-05-19 14:19:57 install libxvmc1:amd64 <none> 2:1.0.12-2
2025-05-19 14:19:57 install libxxf86dga1:amd64 <none> 2:1.1.5-1
2025-05-19 14:19:57 install low-memory-monitor:amd64 <none> 2.1-1
2025-05-19 14:19:57 install lynx-common:all <none> 2.9.0dev.12-1
2025-05-19 14:19:58 install lynx:amd64 <none> 2.9.0dev.12-1
2025-05-19 14:19:58 install malcontent:all <none> 0.11.0-4
2025-05-19 14:19:58 install malcontent-gui:amd64 <none> 0.11.0-4
2025-05-19 14:19:59 install manpages-es:all <none> 4.18.1-1
2025-05-19 14:20:00 install mesa-va-drivers:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:20:01 install mesa-vdpau-drivers:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:20:01 install mesa-vulkan-drivers:amd64 <none> 22.3.6-1+deb12u1
2025-05-19 14:20:03 install mobile-broadband-provider-info:all <none> 20230416-1
2025-05-19 14:20:03 install modemmanager:amd64 <none> 1.20.4-1
2025-05-19 14:20:04 install mythes-en-us:all <none> 1:7.5.0-1
2025-05-19 14:20:05 install nautilus-extension-gnome-terminal:amd64 <none> 3.46.8-1
2025-05-19 14:20:05 install ntfs-3g:amd64 <none> 1:2022.10.3-1+deb12u2
2025-05-19 14:20:05 install packagekit-tools:amd64 <none> 1.2.6-5
2025-05-19 14:20:06 install perl-tk:amd64 <none> 1:804.036-1+b2
2025-05-19 14:20:07 install plymouth:amd64 <none> 22.02.122-3
2025-05-19 14:20:08 install plymouth-label:amd64 <none> 22.02.122-3
2025-05-19 14:20:08 install pocketsphinx-en-us:all <none> 0.8+5prealpha+1-15
2025-05-19 14:20:12 install power-profiles-daemon:amd64 <none> 0.12-1+b1
2025-05-19 14:20:12 install powertop:amd64 <none> 2.14-1+b2
2025-05-19 14:20:13 install ppp:amd64 <none> 2.4.9-1+1.1+b1
2025-05-19 14:20:13 install publicsuffix:all <none> 20230209.2326-1
2025-05-19 14:20:14 install python3-smbc:amd64 <none> 1.0.23-2+b4
2025-05-19 14:20:14 install python3-uno:amd64 <none> 4:7.4.7-1+deb12u8
2025-05-19 14:20:14 install realmd:amd64 <none> 0.17.1-1
2025-05-19 14:20:15 install rtkit:amd64 <none> 0.13-5
2025-05-19 14:20:15 install sane-airscan:amd64 <none> 0.99.27-1+b1
2025-05-19 14:20:15 install sound-icons:all <none> 0.1-8
2025-05-19 14:20:16 install speech-dispatcher-espeak-ng:amd64 <none> 0.11.4-2
2025-05-19 14:20:16 install switcheroo-control:amd64 <none> 2.6-1+b1
2025-05-19 14:20:16 install synaptic:amd64 <none> 0.91.3
2025-05-19 14:20:17 install xserver-xorg-core:amd64 <none> 2:21.1.7-3+deb12u9
2025-05-19 14:20:18 install xserver-xorg-video-amdgpu:amd64 <none> 23.0.0-1
2025-05-19 14:20:18 install xserver-xorg-video-radeon:amd64 <none> 1:19.1.0-3
2025-05-19 14:20:18 install xserver-xorg-video-ati:amd64 <none> 1:19.1.0-3
2025-05-19 14:20:18 install xserver-xorg-video-fbdev:amd64 <none> 1:0.5.0-2
2025-05-19 14:20:19 install xserver-xorg-video-nouveau:amd64 <none> 1:1.0.17-2
2025-05-19 14:20:19 install xserver-xorg-video-vesa:amd64 <none> 1:2.5.0-1+b1
2025-05-19 14:20:19 install xserver-xorg-video-vmware:amd64 <none> 1:13.3.0-3.1+b1
2025-05-19 14:20:19 install xserver-xorg-video-all:amd64 <none> 1:7.7+23
2025-05-19 14:20:20 install xserver-xorg-video-qxl:amd64 <none> 0.1.5+git20200331-3
2025-05-19 14:20:20 install xserver-xorg-video-intel:amd64 <none> 2:2.99.917+git20210115-1
2025-05-19 14:20:20 install xserver-xorg-input-libinput:amd64 <none> 1.2.1-1+b1
2025-05-19 14:20:20 install xserver-xorg-input-all:amd64 <none> 1:7.7+23
2025-05-19 14:20:21 install xserver-xorg-input-wacom:amd64 <none> 1.1.0-1
2025-05-19 14:20:21 install xserver-xorg:amd64 <none> 1:7.7+23
2025-05-19 14:20:21 install xfonts-base:all <none> 1:1.0.5+nmu1
2025-05-19 14:20:23 install xfonts-100dpi:all <none> 1:1.0.5
2025-05-19 14:20:24 install xfonts-75dpi:all <none> 1:1.0.5
2025-05-19 14:20:25 install xfonts-scalable:all <none> 1:1.0.3-1.3
2025-05-19 14:20:26 install x11-apps:amd64 <none> 7.7+9
2025-05-19 14:20:26 install x11-session-utils:amd64 <none> 7.7+5
2025-05-19 14:20:26 install x11-utils:amd64 <none> 7.7+5
2025-05-19 14:20:27 install xauth:amd64 <none> 1:1.1.2-1
2025-05-19 14:20:27 install xinit:amd64 <none> 1.4.0-1
2025-05-19 14:20:27 install xorg-docs-core:all <none> 1:1.7.1-1.2
2025-05-19 14:20:27 install xorg:amd64 <none> 1:7.7+23
2025-05-19 14:20:28 install task-desktop:all <none> 3.73
2025-05-19 14:20:28 install task-gnome-desktop:all <none> 3.73
2025-05-19 14:20:28 install task-laptop:all <none> 3.73
2025-05-19 14:20:28 install task-spanish:all <none> 3.73
2025-05-19 14:20:28 install task-spanish-desktop:all <none> 3.73
2025-05-19 14:20:28 install transmission-common:all <none> 3.00-2.1+deb12u1
2025-05-19 14:20:29 install transmission-gtk:amd64 <none> 3.00-2.1+deb12u1
2025-05-19 14:20:29 install unzip:amd64 <none> 6.0-28
2025-05-19 14:20:30 install usb-modeswitch-data:all <none> 20191128-5
2025-05-19 14:20:30 install usb-modeswitch:amd64 <none> 2.6.1-3+b1
2025-05-19 14:20:30 install usbmuxd:amd64 <none> 1.1.1-2
2025-05-19 14:20:30 install util-linux-locales:all <none> 2.38.1-5+deb12u3
2025-05-19 14:20:31 install va-driver-all:amd64 <none> 2.17.0-1
2025-05-19 14:20:31 install vdpau-driver-all:amd64 <none> 1.5-2
2025-05-19 14:20:31 install wireless-regdb:all <none> 2025.02.20-1~deb12u1
2025-05-19 14:20:32 install wireless-tools:amd64 <none> 30~pre9-14
2025-05-19 14:20:32 install wpasupplicant:amd64 <none> 2:2.10-12+deb12u2
2025-05-19 14:20:32 install wspanish:all <none> 1.0.30
2025-05-19 14:20:33 install xbrlapi:amd64 <none> 6.5-7+deb12u1
2025-05-19 14:20:33 install xcvt:amd64 <none> 0.1.2-1
2025-05-19 14:20:33 install xserver-xephyr:amd64 <none> 2:21.1.7-3+deb12u9
2025-05-19 14:20:34 install xserver-xorg-legacy:amd64 <none> 2:21.1.7-3+deb12u9
2025-05-19 14:26:10 install libfuse2:amd64 <none> 2.9.9-6+b1
2025-05-19 14:26:10 install grub-common:amd64 <none> 2.06-13+deb12u1
2025-05-19 14:26:11 install os-prober:amd64 <none> 1.81
2025-05-19 14:26:23 install grub2-common:amd64 <none> 2.06-13+deb12u1
2025-05-19 14:26:23 install grub-pc-bin:amd64 <none> 2.06-13+deb12u1
2025-05-19 14:26:24 install grub-pc:amd64 <none> 2.06-13+deb12u1
2025-05-19 14:34:12 install amd64-microcode:amd64 <none> 3.20240820.1~deb12u1
2025-05-23 06:30:51 install libsigsegv2:amd64 <none> 2.14-1
2025-05-23 06:30:52 install gawk:amd64 <none> 1:5.2.1-2
2025-05-23 06:30:52 install binutils-common:amd64 <none> 2.40-2
2025-05-23 06:30:53 install libbinutils:amd64 <none> 2.40-2
2025-05-23 06:30:53 install libctf-nobfd0:amd64 <none> 2.40-2
2025-05-23 06:30:54 install libctf0:amd64 <none> 2.40-2
2025-05-23 06:30:54 install libgprofng0:amd64 <none> 2.40-2
2025-05-23 06:30:54 install binutils-x86-64-linux-gnu:amd64 <none> 2.40-2
2025-05-23 06:30:55 install binutils:amd64 <none> 2.40-2
2025-05-23 06:30:55 install m4:amd64 <none> 1.4.19-3
2025-05-23 06:30:55 install bison:amd64 <none> 2:3.8.2+dfsg-1+b1
2025-05-23 06:30:56 install libc-dev-bin:amd64 <none> 2.36-9+deb12u10
2025-05-23 06:30:56 install linux-libc-dev:amd64 <none> 6.1.137-1
2025-05-23 06:30:58 install libcrypt-dev:amd64 <none> 1:4.4.33-2
2025-05-23 06:30:59 install libtirpc-dev:amd64 <none> 1.3.3+ds-1
2025-05-23 06:30:59 install libnsl-dev:amd64 <none> 1.3.0-2
2025-05-23 06:30:59 install rpcsvc-proto:amd64 <none> 1.4.3-1
2025-05-23 06:30:59 install libc6-dev:amd64 <none> 2.36-9+deb12u10
2025-05-23 06:31:01 install libcc1-0:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:01 install libitm1:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:01 install libasan8:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:02 install liblsan0:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:02 install libtsan2:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:02 install libubsan1:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:02 install libgcc-12-dev:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:03 install gcc-12:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:05 install gcc:amd64 <none> 4:12.2.0-3
2025-05-23 06:31:05 install libstdc++-12-dev:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:07 install g++-12:amd64 <none> 12.2.0-14+deb12u1
2025-05-23 06:31:08 install g++:amd64 <none> 4:12.2.0-3
2025-05-23 06:31:08 install make:amd64 <none> 4.3-4.1
2025-05-23 06:31:09 install libdpkg-perl:all <none> 1.21.22
2025-05-23 06:31:09 install patch:amd64 <none> 2.7.6-7
2025-05-23 06:31:09 install dpkg-dev:all <none> 1.21.22
2025-05-23 06:31:10 install build-essential:amd64 <none> 12.9
2025-05-23 06:31:10 install curl:amd64 <none> 7.88.1-10+deb12u12
2025-05-23 06:31:11 install libfakeroot:amd64 <none> 1.31-1.2
2025-05-23 06:31:11 install fakeroot:amd64 <none> 1.31-1.2
2025-05-23 06:31:11 install liberror-perl:all <none> 0.17029-2
2025-05-23 06:31:11 install git-man:all <none> 1:2.39.5-0+deb12u2
2025-05-23 06:31:12 install git:amd64 <none> 1:2.39.5-0+deb12u2
2025-05-23 06:31:14 install libalgorithm-diff-perl:all <none> 1.201-1
2025-05-23 06:31:14 install libalgorithm-diff-xs-perl:amd64 <none> 0.04-8+b1
2025-05-23 06:31:15 install libalgorithm-merge-perl:all <none> 0.08-5
2025-05-23 06:31:15 install libc-devtools:amd64 <none> 2.36-9+deb12u10
2025-05-23 06:31:15 install libfile-fcntllock-perl:amd64 <none> 0.22-4+b1
2025-05-23 06:31:15 install libtext-unidecode-perl:all <none> 1.30-3
2025-05-23 06:31:16 install libxml-namespacesupport-perl:all <none> 1.12-2
2025-05-23 06:31:16 install libxml-sax-base-perl:all <none> 1.09-3
2025-05-23 06:31:16 install libxml-sax-perl:all <none> 1.02+dfsg-3
2025-05-23 06:31:16 install libxml-libxml-perl:amd64 <none> 2.0207+dfsg+really+2.0134-1+b1
2025-05-23 06:31:17 install libxml-sax-expat-perl:all <none> 0.51-2
2025-05-23 06:31:17 install manpages-dev:all <none> 6.03-2
2025-05-23 06:31:20 install tex-common:all <none> 6.18
2025-05-23 06:31:20 install texinfo:amd64 <none> 6.8-6+b1
2025-05-23 06:31:22 install vim-runtime:all <none> 2:9.0.1378-2+deb12u2
2025-05-23 06:31:28 install vim:amd64 <none> 2:9.0.1378-2+deb12u2
2025-05-23 06:37:23 install libgmpxx4ldbl:amd64 <none> 2:6.2.1+dfsg1-1.1
2025-05-23 06:37:23 install libgmp-dev:amd64 <none> 2:6.2.1+dfsg1-1.1
2025-05-23 06:37:24 install libmpfr-dev:amd64 <none> 4.2.0-1
2025-05-23 06:37:24 install libmpc-dev:amd64 <none> 1.3.1-1
2025-05-23 06:37:24 install zlib1g-dev:amd64 <none> 1:1.2.13.dfsg-1

