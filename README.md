# Proyecto de Seguridad y Monitoreo de Red

Este proyecto realiza un sistema de monitoreo y seguridad de red utilizando Debian 12, Zabbix, pfSense, Suricata y Wireshark, con pruebas realizadas desde Kali Linux.

## Objetivos

- Monitorear el tráfico de red en tiempo real.
- Detectar intrusiones mediante un IDS (Suricata).
- Visualizar alertas y métricas en Zabbix.
- Realizar pruebas de penetración y generación de tráfico.

## Herramientas Utilizadas

- Debian 12 (servidor base)
- Zabbix (monitoreo)
- pfSense (firewall/router)
- Suricata (IDS)
- Wireshark (análisis de paquetes)
- Kali Linux (pruebas y generación de tráfico)

## Requisitos

- Máquina física con Debian 12 instalado.
- Máquina virtual con pfSense.
- maquina virtual con KaliLinux.
- Acceso root o sudo.

## Instalación y Configuración

Se recomienda revisar el documento `docs/manual_instalacion.md` para los pasos detallados.

## Uso

- Ejecutar los scripts de integración en `scripts/`.
- Consultar los reportes en `docs/pruebas_y_resultados.md`.
- Visualizar alertas y métricas en la interfaz web de Zabbix.

## Licencia

Este proyecto está bajo licencia MIT. Ver archivo `LICENSE`.

---

## Contacto

Emmanuel Isaí Núñez Cuenca - al222310388@gmail.com
