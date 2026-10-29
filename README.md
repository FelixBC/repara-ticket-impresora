# Repara ticket & impresora

Programa para Windows que revisa y repara la impresora de tickets para que imprima bien desde Google Chrome.

## Descargar

### 👉 **[is.gd/reparaticket](https://is.gd/reparaticket)**

Baja el programa directo (un solo archivo, sin descomprimir). El link siempre da la última versión.

## Cómo se usa

1. Abra el archivo que bajó (**Repara-ticket-e-impresora.exe**) con doble clic, sin «Ejecutar como administrador». Si Chrome dice que el archivo «no se descarga con frecuencia», toque **«Conservar»**.
2. Si Windows muestra un aviso azul («Windows protegió su PC»), toque **«Más información»** y después **«Ejecutar de todas formas»**. El aviso sale porque el programa es nuevo y no tiene firma digital.
3. Toque **«Reparar la impresora»** y siga lo que diga la ventana.
4. Cuando salga el ticket de prueba, mírelo y conteste si salió bien. Si salió cortado, en blanco, torcido o con letras raras, elija lo que pasó: el programa prueba otra vez o dice qué hacer.
5. Al terminar dice **«Listo, la impresora quedó bien»**, o **«Falta algo»** con un código para soporte.

## Qué revisa y arregla

- Que la impresora de tickets esté instalada (Epson TM-T20, TM-T20II, TM-T20III, TM-T88V y las compatibles con el driver genérico).
- Que esté conectada y sin tickets trabados.
- Que sea la impresora predeterminada.
- La configuración de impresión de Chrome (impresora, papel de 80 mm, márgenes, escala).
- El ícono de Chrome con impresión rápida (se puede apagar con la casilla de la ventana).
- Un ticket de prueba igual al de la banca.

## Para soporte («Ver más», abajo en la ventana)

- **Informe para soporte**: guarda un .txt en `Documentos\Repara ticket & impresora`. Cuando algo queda sin arreglar, se guarda solo.
- **Deshacer el arreglo**: devuelve lo que cambió el último arreglo como estaba antes.
- **Impresoras que encontré**: lo que hay conectado, con «Intentar driver genérico» para una impresora que no reconoce.

Cada versión publica su SHA-256 en la página de la versión, para comprobar que el archivo no fue cambiado.
