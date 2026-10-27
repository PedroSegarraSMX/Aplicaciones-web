# Guía configuración ubuntu server en virtualbox(NAT+Host-only)
## 1. Crear la red Host-only
### En el gestor de redes le damos a crear para hacer un adaptador nuevo adaptador nuevo(vboxnet0) añadimos los parametros necesarios (ip:192.168.56.1, máscara:255.255.255.0):

<img width="508" height="986" alt="Captura de 2026-10-22 17-23-42" src="https://github.com/user-attachments/assets/7838978a-2057-4b00-b571-ae18a7a45f90" />

### y desactivamos el dhcp:

<img width="582" height="199" alt="Captura de 2026-10-22 17-32-32" src="https://github.com/user-attachments/assets/c5042ccf-49bd-4a86-be18-50a15ce30be5" />

## 2. Crear la máquina virtual
### En la pantalla de inicio le damos a nueva:

<img width="190" height="82" alt="Captura de 2026-10-22 18-15-06" src="https://github.com/user-attachments/assets/0bf5c966-3bcf-4b4f-8bdf-ec6f2a10c7ee" />

### Le ponemos el nombre que queramos con el SO linux, OS distribution ubuntu y OS version ubuntu (64-bit):

<img width="1012" height="301" alt="Captura de 2026-10-22 18-34-29" src="https://github.com/user-attachments/assets/dbdac746-f845-4faa-900d-3dc24bc544d5" />

### Le asignamos un minimo de 2048 MB de memoria base(RAM) y minimo 1 CPU:

<img width="853" height="201" alt="Captura de 2026-10-22 18-40-23" src="https://github.com/user-attachments/assets/915e45ea-c950-4aab-a091-be6d3029e831" />

### Le asignamos un minimo de 20 GB de espacio de disco y le damos a terminar:

<img width="864" height="432" alt="Captura de 2026-10-22 18-53-01" src="https://github.com/user-attachments/assets/ba1d0c73-978f-494d-91dd-b6a1715760bb" />

## 3. Configurar los dos adaptadores de red
### Le damos a configuración en nuestra maquina:

<img width="338" height="81" alt="Captura de 2026-10-22 18-55-17" src="https://github.com/user-attachments/assets/6fd204b9-6463-4e94-8a2f-d601c40310bf" />

### Le damos a red y en adaptador 1 lo habilitamos y lo ponemos en NAT:

<img width="956" height="342" alt="Captura de 2026-10-22 18-59-13" src="https://github.com/user-attachments/assets/9482de5e-8f52-4a88-95f7-73481ed7225d" />

### Habilitamos el adaptador 2 y lo ponemos en adaptador solo-anfitrióny seleccionamos el host-only creado anteriormente(vboxnet):

<img width="692" height="280" alt="Captura de 2026-10-27 15-19-47" src="https://github.com/user-attachments/assets/d1f0fd16-2df7-43bf-9794-99f17ba1195d" />

### Guardar dandole a aceptar:

<img width="319" height="141" alt="Captura de 2026-10-27 15-28-20" src="https://github.com/user-attachments/assets/be6358b2-d927-44e1-ac51-5a4492a48d2d" />

## 4. Montar la ISO y arrancar

### Añadir ISO dandole a configuración en nuestra máquina y seleccionando el archivo de la ISO(ubuntu-24.04-live-server-amd64.iso) en la unidad óptica vacía en almacenamiento:

<img width="954" height="279" alt="Captura de 2026-10-27 15-38-12" src="https://github.com/user-attachments/assets/fa3e8baa-ad27-421e-97b7-2a478d8545d9" />

### Iniciar máquina virtual:

<img width="482" height="91" alt="Captura de 2026-10-27 15-46-18" src="https://github.com/user-attachments/assets/992f1915-59c9-4dbf-9c85-1fcbfe0cb657" />

## 5. Instalar Ubuntu Server 24.04

### Seleccionar idioma:

### Seleccionar distribución de teclado:

### Seleccionar tipo de instalación, en nuestro caso sin minimized:

### Seleccionar proxy, en nuestro caso no:

### Seleccionar mirror, en nuestro caso no:

### Seleccionar el disco completo en almacenamiento(por defecto):

### 
