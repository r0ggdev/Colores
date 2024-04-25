# Librería de Colores C++ 🎨
Ahora podras usar los colores en consola mucho más facil.

## Instalar ⚠
1. Descarga el archivo [Colors.h](Colors.h)
2. Inclúyelo en tu carpeta de trabajo
3. Importa el encabezado en el archivo donde desees usarlo `#include "Colors.h"`

## Uso

Para poder cambiar el color de fondo del texto utiliza el comando `color::setBackgroundColor(color::BG_backgrundcolor);`
 
Para poder cambiar el color de texto utiliza el comando `color::setTextColor(color::textcolor);`

Para cambiar el color del fondo y al mismo tiempo del texto se utiliza el comando `color::setTxtBgColor(color::textcolor, color::BG_backgrundcolor);`

Por ultimo si desea volver al color por defecto debe usar el comando `color::reset();` 

### Colores disponibles
![alt text](<sources/Recurso 1@2x.png>)