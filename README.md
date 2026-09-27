# CellOS — App de escritorio

Aquí viven los **instaladores** de la app de escritorio de CellOS. No hay código:
el código vive aparte, esto es solo el lugar de donde se bajan los archivos.

## Descargar

Siempre la última versión, desde **[Releases](../../releases/latest)**:

| Tu computadora | Archivo |
|---|---|
| Mac con chip Apple (M1 en adelante) | `CellOS-mac-arm64.dmg` |
| Mac Intel | `CellOS-mac-x64.dmg` |
| Windows | `CellOS-win-x64.exe` |

¿No sabes cuál? En Mac: menú  → *Acerca de esta Mac*. Si dice **Apple M1/M2/M3/M4**,
es la primera; si dice **Intel**, la segunda.

## La primera vez dirá que no se puede abrir

Es normal: la app todavía no está firmada con Apple ni con Microsoft. Se autoriza
una sola vez.

- **Mac** — abre el `.dmg` y arrastra CellOS a Aplicaciones. Al abrirla dirá que
  Apple no pudo verificarla, y te va a ofrecer **Mover a la papelera**: no le des
  ahí, dale **Listo**. Luego ve a **Ajustes del sistema → Privacidad y seguridad**,
  baja hasta el final (sección *Seguridad*) y dale **Abrir de todos modos** — ese
  botón aparece solo después de ese primer intento, y pide tu huella o contraseña.
- **Windows** — al abrir el instalador sale *"Windows protegió tu PC"*. Dale
  **Más información → Ejecutar de todas formas**.

## Al abrirla te pide 2 datos

La dirección de tu panel y tu clave del checker. Los dos están en tu propio panel,
en **Config → App de escritorio**. Se ponen una sola vez.

Bajar el instalador no le da a nadie acceso a ningún negocio: sin esos dos datos
la app no se conecta a nada.
