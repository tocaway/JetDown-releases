# Instalar y actualizar JetDown

JetDown descarga vídeo y audio en tu Mac o tu PC con Windows. La app y su extensión para Chrome y Edge se actualizan desde aquí: solo descargan el número de la última versión y, si aceptas, el paquete. Nunca envían datos tuyos.

Las versiones están en [Releases](https://github.com/tocaway/JetDown-releases/releases). Cada una va firmada: JetDown comprueba la firma antes de instalar y rechaza cualquier paquete alterado.

## App para Mac (Apple Silicon, macOS 13 o posterior)

1. Descarga `JetDown-X.Y.Z-arm64.dmg` de la última versión «JetDown Mac».
2. Ábrelo y arrastra **JetDown** a **Aplicaciones**.
3. La primera vez: clic derecho sobre JetDown → **Abrir** → **Abrir**. Si el Mac dice que no puede comprobarla, ve a **Ajustes del Sistema → Privacidad y seguridad** y pulsa **Abrir igualmente**.

Para actualizar, JetDown debe estar en **Aplicaciones** (no abierta desde el DMG).

## App para Windows (Windows 10 u 11 de 64 bits)

1. Descarga `JetDown-X.Y.Z-Setup.exe` de la última versión «JetDown Windows».
2. Ejecútalo y sigue los pasos. Se instala solo para tu usuario, sin permisos de administrador.
3. Si aparece **«Windows protegió su PC»** (el instalador no lleva certificado de Microsoft): **Más información → Ejecutar de todas formas**. El archivo `SHA256SUMS-X.Y.Z.txt` de la versión permite comprobar que el instalador es el publicado.

## Extensión para Chrome y Edge

1. Descarga `JetDownExtension-X.Y.Z.zip` de la última versión «JetDown Extension» y descomprímelo en una carpeta que no vayas a mover.
2. En `chrome://extensions` (o `edge://extensions`) activa **Modo de desarrollador**, pulsa **Cargar descomprimida** y elige esa carpeta.
3. En JetDown: **Ajustes → Motor → Configurar conexión** y elige la misma carpeta.

## Actualizaciones

- **App:** al abrirse avisa si hay versión nueva y muestra los cambios. Pulsa **Actualizar**: descarga la versión, comprueba su firma, se cierra y se vuelve a abrir actualizada (en Windows el instalador nuevo se ejecuta solo, sin preguntas). También en el menú **JetDown → Buscar actualizaciones…** (Mac) y en **Ajustes → Actualizaciones**, donde puedes desactivar el aviso al abrir y **volver a la versión anterior**.
- **Extensión:** cuando hay versión nueva, el botón **Actualizar** del panel lo indica. Al pulsarlo, JetDown descarga la versión, comprueba su firma y sustituye la carpeta guardando una copia de la anterior; la extensión se recarga sola.

Nunca se instala nada sin que lo pulses.
