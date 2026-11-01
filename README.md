# Metrónomo configurable

Metrónomo que funciona en el navegador, sin instalar nada.

## Funciones

- Tempo de 30 a 260 BPM, botones +/− y “Marcar tempo” (tap tempo)
- De 1 a 12 pulsos por compás, con acento opcional en el primero
- Subdivisiones: corcheas, tresillos y semicorcheas, con volumen propio
- Volumen, tono del pulso y del acento (Hz), duración del golpe
- Cinco timbres: suave, redondo, hueco, brillante y madera
- Presets con nombre, guardados en el navegador
- Exportar e importar presets como archivo `.json` para compartirlos
- Botón para restaurar los valores por defecto
- Atajo: barra espaciadora para iniciar o detener

## Uso local

Abre `index.html` en cualquier navegador moderno. No necesita servidor ni dependencias.

## Notas

- Los ajustes y presets se guardan en el `localStorage` de cada navegador. Si alguien borra los datos del navegador o cambia de dispositivo, los pierde; por eso existe la opción de exportar.
- En iPhone, el sonido no sale si el interruptor de silencio está activado.
