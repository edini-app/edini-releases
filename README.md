# EDINI

Sistema de gestión para comercios y PyMEs argentinas: ventas, stock, caja, facturación electrónica (ARCA), clientes y finanzas en un solo lugar. Corre instalado en tu propia PC — no depende de un servidor externo para operar.

## Instalación

**Requisitos:** Windows 10 u 11 de 64 bits, permisos de administrador.

1. Descargá el instalador (`EdiniSetup.exe`) desde la sección [Releases](../../releases) de este repositorio.
2. Ejecutalo. Windows puede pedirte confirmación de administrador — es normal, el instalador necesita crear el servicio de la base de datos.
3. Seguí el asistente hasta el final.

### ¿Qué se descarga?

| Componente | Tamaño aprox. | ¿Cuándo? |
|---|---|---|
| EDINI (el instalador) | ~40 MB | Siempre |
| PostgreSQL (base de datos) | ~300 MB | Solo si tu PC no lo tiene ya instalado |

**Este es el único momento en que EDINI necesita internet.** Si tu PC no tiene PostgreSQL, el instalador lo descarga automáticamente durante la instalación — por eso ese paso requiere conexión. Una vez instalado, el sistema opera sin conexión (ver más abajo).

Si la descarga de PostgreSQL falla (por ejemplo, sin internet en ese momento), podés instalarlo manualmente desde [postgresql.org/download/windows](https://www.postgresql.org/download/windows/) (versión 14 o superior) y volver a correr el instalador.

## Primer uso

Al abrir EDINI por primera vez:

1. **Activación**: ingresá el código de activación que recibiste (por email, si probaste el Trial gratuito, o de parte del administrador si contrataste un plan pago). El código queda atado a esa PC.
2. **Asistente de configuración**: te guía para cargar los datos fiscales de tu negocio y lo mínimo para empezar a operar.
3. Ya podés abrir la caja, cargar artículos y empezar a vender.

## ¿Funciona sin internet?

Sí. Una vez instalado, tu negocio sigue operando con normalidad sin conexión: vender, facturar localmente, controlar stock y caja no dependen de internet. Las únicas excepciones son:

- **Emitir el comprobante electrónico ante ARCA** (necesita conexión con el organismo).
- **Cobrar con Mercado Pago** (QR / Point, plan Premium).

## Soporte

Dudas de uso, errores o problemas de funcionamiento de EDINI:

- **Email:** soporte@edini.ar
- **WhatsApp:** +54 2302 629252
- **Horario:** 7 a 13 hs, de lunes a viernes hábiles

No incluye soporte de Windows, impresoras, redes u otro hardware de tu PC, ni tramitar o renovar tu certificado ante ARCA (es un trámite con tu clave fiscal — corresponde a vos o a tu contador).
