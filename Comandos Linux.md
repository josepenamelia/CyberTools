# Comandos Linux

## Comandos Para CiberSeguridad

### Fallos en el login

Indica los intentos fallidos de autentificación  en tu sistema, con marca de tiempo.

```bash
grep "Failed password" /var/log/auth.log
```

### Cuentas autentificadas

Quien esta dentro del sistema:

```bash
last
```

### Cuentas autentificadas en tiempo real

Quien esta entrado en el sistema, por ejemplo durante un ataque para ver la cantidad de intentos en tiempo real:

```bash
tail -f /var/log/auth.log
```

### Escucha de puertos

Para ver cada puerto abierto en tu sistema y que proceso lo ha abierto.

```bash
ss -tulnp
```

### Archivos con sticktybit

Encuentra todos los binarios con stickybit y quien puede ejecutarlos.

```bash
find / -perm -4000 2>/dev/null
```

### Procesos por cpu

Listar todos los procesos por uso de cpu. Comando pensado para ver que se esta comiendo la cpu como un cryptominer por ejemplo.

```bash
ps aux --sort=-%cpu
```

###

## Repositorios de Github

[Wpair Aplicativo para explorar, analizar y gestionar Bluetooth](https://github.com/zalexdev/wpair-app)

[MegaRepositorio de Herramientas y OSINT](https://github.com/rawfilejson/awesome-osint-arsenal)

[Osint UI](https://osint-ui.com/)

[90-day-cybersecurity](https://github.com/farhanashrafdev/90DaysOfCyberSecurity)

[Framework IA Obra superpowers](https://github.com/obra/superpowers)

## Bibliografía

[Comandos de Ciberseguridad by Tiktok - 1](https://www.tiktok.com/@haruna_adoga/photo/7648595326013574422)

[]()