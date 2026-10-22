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

###
