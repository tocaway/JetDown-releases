# Instalar y actualizar JetDown

JetDown descarga vídeo y audio en tu Mac o tu PC con Windows. **Solo necesitas el instalador de la app:** la extensión para Chrome, Edge y Brave va dentro. La app y la extensión se actualizan desde aquí: solo descargan el número de la última versión y, si aceptas, el paquete. Nunca envían datos tuyos.

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

## Extensión para Chrome, Edge y Brave (va dentro de la app)

No hay que descargar nada más. La primera vez que abres JetDown te pregunta si quieres instalar la extensión (también en **Ajustes → Motor → Instalar extensión**):

1. Elige el navegador. JetDown prepara la extensión, abre la página de extensiones y te muestra la carpeta.
2. Una ventanita con los pasos se queda a la vista: activa **Modo de desarrollador** y **arrastra la carpeta JetDownExtension** a esa página.

Solo se hace una vez; después se actualiza sola junto con la app. Chrome y Edge no dejan que un programa instale extensiones por su cuenta fuera de su tienda: por eso queda ese único paso. Si ya la tenías cargada, JetDown la reconoce y no vuelve a preguntar.

(El ZIP «JetDown Extension» de Releases es el paquete firmado que usan las actualizaciones; no hace falta descargarlo.)

## Actualizaciones

- **Juntas:** la app y la extensión se actualizan a la vez. Busques donde busques (en la app o en la extensión), un solo **Actualizar** instala todo lo pendiente.
- **App:** al abrirse avisa si hay versión nueva y muestra los cambios. Pulsa **Actualizar**: descarga la versión, comprueba su firma, se cierra y se vuelve a abrir actualizada (en Windows el instalador nuevo se ejecuta solo, sin preguntas). También en el menú **JetDown → Buscar actualizaciones…** (Mac) y en **Ajustes → Actualizaciones**, donde puedes desactivar el aviso al abrir y **volver a la versión anterior**.
- **Extensión:** cuando hay versión nueva (de ella o de la app), su icono muestra cuántas hay y el botón **Actualizar** del panel lo indica. Al pulsarlo, JetDown descarga la versión, comprueba su firma y sustituye la carpeta guardando una copia de la anterior; la extensión se recarga sola.

Nunca se instala nada sin que lo pulses.
