
# UNIT PAM8403 Amplificador de Audio 3W

![UNIT PAM8403](ruta_a_la_imagen_principal.jpg) 

El **UNIT PAM8403 Amplificador de Audio 3W** es un módulo de amplificación de audio en clase D diseñado para ofrecer una salida estéreo de hasta 3W por canal con alta eficiencia. Ideal para aplicaciones de audio portátiles y proyectos con dispositivos de bajo consumo, como reproductores de música, altavoces portátiles y sistemas alimentados por baterías.

## Características del Módulo

![Pinout del UNIT PAM8403](ruta_a_la_imagen_pinout.jpg) 
<img src="Docs/Pinout_EN.jpg?raw=false" width="800px"><br/>


- **Voltaje de operación:** 2.5V a 5.5V, compatible con fuentes USB y baterías de litio.
- **Potencia de salida:** 3W por canal (4Ω, 5V).
- **Consumo de corriente:** 5V/40mA en reposo y 5V/500mA a carga máxima.
- **Eficiencia:** Hasta 90%, minimizando el consumo de energía.
- **Distorsión armónica total (THD):** Menos del 0.1%, asegurando una excelente calidad de sonido.
- **Tamaño compacto:** 19 mm x 22 mm, ideal para proyectos con espacio limitado.
- **Rango de impedancia:** Soporta altavoces con una impedancia de 4Ω a 8Ω.
- **Protección:** Incluye protección contra sobrecalentamiento y cortocircuitos.
- **Temperatura de operación:** -40°C a 85°C, adecuado para aplicaciones industriales y ambientes extremos.

# Datasheet

Para más información técnica detallada sobre el módulo PAM8403, consulta el siguiente documento:

👉 [Descargar el Datasheet del PAM8403](https://www.mouser.com/ds/2/115/PAM8403-247318.pdf?srsltid=AfmBOorzunVHYR1wIITzAZVypkFj5LkC2lR0cZLh1zfklQpAhanR1Qrl)


## Tabla de Pinout

La siguiente tabla detalla las conexiones principales del módulo amplificador **UNIT PAM8403**:

| PIN  | Descripción             | Conexión Sugerida con RP2040/ESP32 |
| ---- | ----------------------- | ---------------------------------- |
| VCC  | Alimentación (+)         | 3.3V                              |
| GND  | Tierra (-)               | GND                               |
| INL  | Entrada de audio izquierdo | Pin específico para señal de audio |
| INR  | Entrada de audio derecho  | Pin específico para señal de audio |
| OUTL | Salida de audio izquierdo | Altavoz                           |
| OUTR | Salida de audio derecho   | Altavoz                           |

Para un ejemplo detallado de cómo utilizar el **UNIT PAM8403** con el microcontrolador **ESP32**, consulta la guía de uso en el siguiente enlace:

👉 [Guía de Uso del UNIT PAM8403 con DualMCU ESP32](https://github.com/UNIT-Electronics/VoiceAmp_Synth_ESP32)

## Links de compra

Puedes adquirir el módulo **UNIT PAM8403 Amplificador de Audio 3W** directamente en [UNIT Electronics](https://www.uelectronics.com).

### Ventajas técnicas:

- **Amplificador de Clase D**: Tecnología de amplificación eficiente que reduce el consumo de energía.
- **Consumo ultrabajo**: Perfecto para dispositivos móviles y alimentados por batería.
- **Sin necesidad de disipador de calor**: Gracias a su eficiencia energética, se mantiene frío incluso en uso prolongado.
- **Diseño sin filtro**: Menor cantidad de componentes externos requeridos.
- **Tamaño compacto**: Fácil de integrar en cualquier proyecto, con un tamaño reducido que ahorra espacio.

## Aplicaciones típicas

Este amplificador es ideal para:

- Altavoces portátiles.
- Sistemas de audio USB o alimentados por batería.
- Proyectos DIY y educativos.
- Cualquier sistema que necesite amplificación de audio eficiente.

---

¡Comienza tu proyecto de amplificación de audio con el **UNIT PAM8403** hoy mismo!
