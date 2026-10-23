# Informe de cobertura — IoT y ESP32

Banco 2026.10.23.2. 322 preguntas: 47 originales o variantes y 275 nuevas. 318 evaluables y 4 de consulta sin puntaje.

## Conciliación de fuentes

Se recuperaron las trece fuentes. Los seis parciales contienen diez preguntas cada uno y los dos HTML contienen 45 y 32, respectivamente: 137 apariciones antes de unificar duplicados. La comparación usa enunciado y conjunto de opciones, conservando las referencias y las variantes con opciones diferentes. No se ejecutaron scripts de los HTML originales.

Los PDF de apuntes tienen 51, 35, 9 y 13 páginas; el resumen se exportó a PDF de 40 páginas para revisión visual. Se generaron vistas de todas las páginas y ampliaciones de diagramas/tablas relevantes. Las claves de parciales se tomaron del texto de solución de Moodle, no de las opciones seleccionadas por el alumno.

| Fuente | Apariciones originales | Preguntas vinculadas |
|---|---:|---:|
| [Copia de Resumen IoT](https://docs.google.com/document/d/1gKJEANf_dM5VozkMCgg-LsZI7aPdlWKvmUt9BOjrC54/edit?usp=drivesdk) | Apunte | 275 |
| [TA.html](https://drive.google.com/file/d/1dJknqI0a1JCqUuXK935zz0xWGcgIj2yR/view?usp=drivesdk) | 45 | 45 |
| [quiz_parcial_iot.html](https://drive.google.com/file/d/1Mct5frisVvpW2ykybsBS2mxbpWWVReOC/view?usp=drivesdk) | 32 | 32 |
| [Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT - 5 de JUNIO_ Revi (1).pdf](https://drive.google.com/file/d/1kiWJYdJSedVSP2UxH3eN9QSzI70sN7yO/view?usp=drivesdk) | 10 | 10 |
| [Recuperatorio Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT_ Rev (1).pdf](https://drive.google.com/file/d/1LG-T6ABAN8thfuxAbxJr1LEs2VH6_g9t/view?usp=drivesdk) | 10 | 10 |
| [2do Parcial TA- IOT.pdf](https://drive.google.com/file/d/1Y4aSMk1Siw6WflotTwoGPILdIq-j4yY0/view?usp=drivesdk) | 10 | 10 |
| [Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT - 5 de JUNIO_ Revi.pdf](https://drive.google.com/file/d/1DF1QZKzp6bOP3kt2Y2n9FuUYXhISD7b0/view?usp=drivesdk) | 10 | 10 |
| [Recuperatorio Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT_ Rev.pdf](https://drive.google.com/file/d/12g_CS2GiaC9BVPZqvo4_GWUP9bT06LvN/view?usp=drivesdk) | 10 | 10 |
| [Parcial ESP32 teo.pdf](https://drive.google.com/file/d/14AkJCjKRRcehFp-Ly1FrN_jzXWHKu7bb/view?usp=drivesdk) | 10 | 10 |
| [Tpa - Apunte IoT 2026.pdf](https://drive.google.com/file/d/1OG4QDM98MbPWfgiJDZA06jeeH5pU5jno/view?usp=drivesdk) | Apunte | 275 |
| [Esp32_2.pdf](https://drive.google.com/file/d/1mK-9GQrba2frIOMNnNiYFcQAHxfxtM26/view?usp=drivesdk) | Apunte | 62 |
| [IOT CLASE 02.pdf](https://drive.google.com/file/d/1itqGCd9ZtHwPbHmszwy9Khty0-qlxqJj/view?usp=drivesdk) | Apunte | 82 |
| [IOT CLASE 01.pdf](https://drive.google.com/file/d/1l0VlGT2GKk1D3wnH6ZwDsVN9LvNGOcOh/view?usp=drivesdk) | Apunte | 39 |

## Duplicados comprobados

Se comprobaron por SHA-256 los siguientes pares idénticos de PDF:
- Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT - 5 de JUNIO_ Revi (1).pdf / Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT - 5 de JUNIO_ Revi.pdf
- Recuperatorio Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT_ Rev (1).pdf / Recuperatorio Segundo Parcial de Tecnologías para la Automatización - Internet de las Cosas - IoT_ Rev.pdf

Los archivos originales se mantienen en el área de trabajo; no se incluyen en la carpeta pública del proyecto.

## Matriz de conceptos

La tabla relaciona los conceptos cubiertos con sus preguntas y referencias. Las nuevas son ejercicios elaborados, no transcripciones atribuidas al docente. Las referencias de nuevas se dan por sección/páginas; las originales incluyen número de pregunta y página cuando se detectó.

| Tema | Originales/variantes | Nuevas |
|---|---:|---:|
| ADC, DAC y PWM | 7 | 22 |
| Arquitectura y pines | 8 | 20 |
| Electricidad y GPIO | 11 | 20 |
| Entorno y herramientas | 5 | 7 |
| Fundamentos de IoT | 1 | 10 |
| HTTP y APIs | 0 | 20 |
| MQTT | 0 | 25 |
| Memoria y seguridad | 2 | 19 |
| Plataformas IoT | 0 | 18 |
| Programación C++ | 2 | 33 |
| SPI e I2C | 2 | 14 |
| Sensores y actuadores | 4 | 23 |
| Telegram y servicios | 0 | 6 |
| Temporización | 2 | 9 |
| UART y serie | 3 | 12 |
| Wi-Fi y redes | 0 | 17 |

La matriz detallada está en `cobertura.csv`: una fila por pregunta, con identificador estable, concepto, tipo, fuente, ubicación y situación de la clave.

## Discrepancias y ambigüedades

### ¿Qué afirmaciones son ciertas sobre delay() en código de ESP32?

La opción “detiene completamente” es excesiva para ESP32 con FreeRTOS.

- Clave original: Detiene completamente la ejecución del programa por ese tiempo; Su uso excesivo puede afectar el rendimiento
- Criterio técnico: Su uso excesivo puede afectar el rendimiento
- Estado: Evaluable con corrección visible
- ID: o-df5cd6bcf876

### ¿Qué ventajas tiene usar sensores digitales frente a analógicos en ESP32?

No todos los sensores digitales se leen con una sola llamada digitalRead().

- Clave original: Se leen con digitalRead(); No requieren conversión ADC
- Criterio técnico: No requieren conversión ADC
- Estado: Evaluable con corrección visible
- ID: o-0944c5c54926

### ¿Qué afirmaciones sobre la señal digital 'LOW' son correctas?

LOW no garantiza apagar una carga activa en bajo.

- Clave original: Equivale a voltaje cercano a 0V; Apaga una salida digital
- Criterio técnico: Equivale a voltaje cercano a 0V
- Estado: Evaluable con corrección visible
- ID: o-096838b0caae

### ¿Qué afirmaciones sobre la arquitectura de la ESP32 son verdaderas?

Redacción ambigua: La clave destaca coprocesadores, ADC/DAC y 16 canales LEDC del ESP32 clásico. La afirmación sobre USB necesita especificar el chip: el ESP32 clásico usa habitualmente un puente USB–UART en la DevKit, mientras otras familias sí incorporan USB. Se conserva para consulta sin afectar el puntaje.

- Clave original: Puede manejar hasta 16 canales PWM; Posee coprocesadores para ciertas tareas; Tiene soporte para múltiples ADC y DAC
- Criterio técnico: Puede manejar hasta 16 canales PWM; Posee coprocesadores para ciertas tareas; Tiene soporte para múltiples ADC y DAC
- Estado: Consulta sin puntaje
- ID: o-0a9f356eba26

### ¿Qué componentes se pueden controlar mediante salidas digitales de la ESP32?

Redacción ambigua: La clave enumera LEDs, relés y pantallas LCD como dispositivos controlables. Controlar no equivale a alimentar: relés y motores requieren la etapa de potencia apropiada, y las pantallas una interfaz compatible. Se conserva para consulta sin afectar el puntaje.

- Clave original: Pantallas LCD; Leds; Relés
- Criterio técnico: Pantallas LCD; Leds; Relés
- Estado: Consulta sin puntaje
- ID: o-7a95eb05facd

### ¿Cuál es la función principal del regulador de tensión en la ESP32 DevKit V1?

Un regulador no constituye protección general contra sobretensiones.

- Clave original: Adaptar el voltaje de entrada a niveles seguros para el microcontrolador; Proteger la placa de sobrevoltajes
- Criterio técnico: Adaptar el voltaje de entrada a niveles seguros para el microcontrolador
- Estado: Evaluable con corrección visible
- ID: o-3d13f0f73985

### ¿Qué dispositivos utilizan modulación por ancho de pulso (PWM)?

Redacción ambigua: PWM se utiliza para LEDs, velocidad de motores con su driver y control de servos. Un transistor también puede ser el interruptor de una etapa PWM; la clave usa “dispositivos” en sentido de aplicaciones finales. Se conserva para consulta sin afectar el puntaje.

- Clave original: Servos; Leds; Motores DC
- Criterio técnico: Servos; Leds; Motores DC
- Estado: Consulta sin puntaje
- ID: o-5ca60e49749d

### ¿Qué hace la función digitalRead(pin) en ESP32?

El retorno documentado de digitalRead() es int, no bool.

- Clave original: Devuelve un valor booleano; Lee si hay una señal HIGH o LOW en un pin digital
- Criterio técnico: Lee si hay una señal HIGH o LOW en un pin digital
- Estado: Evaluable con corrección visible
- ID: o-844e3c4747c6

### ¿Qué características definen la comunicación I²C?

El protocolo I2C sí admite múltiples maestros mediante arbitraje.

- Clave original: Permite un maestro y varios esclavos; Cada dispositivo tiene una dirección única; Usa líneas SDA y SCL
- Criterio técnico: Permite un maestro y varios esclavos; Cada dispositivo tiene una dirección única; Permite varios maestros simultáneos; Usa líneas SDA y SCL
- Estado: Evaluable con corrección visible
- ID: o-ff080cccc7c0

### ¿Qué afirmaciones sobre setup() y loop() en Arduino/ESP32 son correctas?

El framework Arduino es quien invoca loop().

- Clave original: setup() se ejecuta solo una vez al inicio; loop() se repite continuamente mientras la placa esté encendida
- Criterio técnico: loop() es llamado desde el firmware; setup() se ejecuta solo una vez al inicio; loop() se repite continuamente mientras la placa esté encendida
- Estado: Evaluable con corrección visible
- ID: o-10456c51ec62

### ¿Qué lenguajes y entornos se pueden usar para programar una ESP32 DevKit V1?

Redacción ambigua: C++ con Arduino IDE y PlatformIO son opciones válidas. Python requiere un firmware como MicroPython; VS Code por sí solo no agrega un intérprete al chip. La clave original no pretende enumerar todas las herramientas posibles. Se conserva para consulta sin afectar el puntaje.

- Clave original: C++ en Arduino IDE; C++ en PlatformIO
- Criterio técnico: C++ en Arduino IDE; C++ en PlatformIO
- Estado: Consulta sin puntaje
- ID: o-5cb1ce598a04

### ¿Qué herramientas del IDE ayudan a depurar programas en ESP32?

El LED ayuda a depurar, pero no forma parte del IDE.

- Clave original: Monitor serial; LED integrado
- Criterio técnico: Monitor serial
- Estado: Evaluable con corrección visible
- ID: o-6f5b6094e2dc

## Erratas de los apuntes contempladas

- ESP32 clásico: ADC de 12 bits implica 4096 códigos (0–4095), no 2075. Una entrada de 12 bits no se convierte a voltios dividiendo por 256.
- El DAC interno clásico es de 8 bits; Esp32_2 incluye también una línea contradictoria de 16 bits.
- Las tablas AVR de tipos no se trasladan sin contexto al ESP32: int es habitualmente de 32 bits.
- I2C y SPI son síncronos aunque algunos encabezados del resumen los llamen asíncronos.
- Una resistencia pull no elimina por sí sola el rebote mecánico ni reemplaza la resistencia serie de un LED.
- Alimentación USB de 5 V no significa GPIO tolerantes a 5 V. No se usa como regla general la cifra aislada de corriente por pin de las diapositivas.
- Ni todos los Arduino usan 16 MHz ni un ciclo de reloj equivale necesariamente a una instrucción.
- PWM es una señal pulsada; no equivale a una salida continua DAC. El rango útil ADC depende de atenuación/calibración.
- El ESP32 de este curso no se considera un sistema Linux. El resumen contiene anotaciones contradictorias al respecto.
- El host formal del práctico es test.mosquitto.org, frente a .com en algunos fragmentos del resumen.
- loop() pertenece al framework Arduino. PubSubClient.loop() es otro método.
- C++ sí dispone de abstracciones de cadenas; el uso de const char* no demuestra su inexistencia.
- Las prácticas HTTP se analizan críticamente: fragmentación TCP, línea vacía de cabeceras, rutas exactas y semántica de GET.
- Los fragmentos con erratas o marcadores incompletos del resumen no se presentan como código listo para compilar.
- Los límites comerciales y referencias históricas de plataformas cloud no se convierten en propiedades permanentes del protocolo.

## Alcance y límites

La cobertura incluye los temas, tablas, diagramas y consignas presentes: arquitectura, memoria, electricidad, GPIO, conversión, temporización, programación, buses, sensores, control, herramientas, redes, HTTP, Telegram, MQTT y plataformas. Las preguntas de diagnóstico derivadas (por ejemplo, histéresis) están identificadas como nuevas.

Los enlaces de los apuntes a carpetas de prácticos, videos y tutoriales no forman parte de las trece fuentes. No se descargó ni se inventó el contenido de esas soluciones externas. Algunas capturas pequeñas tienen legibilidad limitada; no se transcribieron como código íntegro cuando no resultaba verificable. Se cubre el concepto y se conserva el enlace a la fuente. No se afirma que se hayan recuperado archivos que no estaban en la carpeta.

No hay un temario oficial separado que permita garantizar todo lo que podría evaluar la cátedra. El banco amplía y cubre el material reunido; no promete exhaustividad respecto de exámenes futuros.

## Referencias técnicas complementarias

- [ADC Arduino-ESP32](https://docs.espressif.com/projects/arduino-esp32/en/latest/api/adc.html)
- [LEDC Arduino-ESP32](https://docs.espressif.com/projects/arduino-esp32/en/latest/api/ledc.html)
- [DAC ESP32](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/peripherals/dac.html)
- [GPIO Arduino-ESP32](https://docs.espressif.com/projects/arduino-esp32/en/latest/api/gpio.html)
- [Preferences](https://docs.espressif.com/projects/arduino-esp32/en/latest/api/preferences.html)
- [FreeRTOS ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-reference/system/freertos_idf.html)
- [Especificación I2C de NXP](https://www.nxp.com/docs/en/user-guide/UM10204.pdf)

## Diseño

Se instaló y leyó Impeccable 4.7.0 en work/skills/impeccable. La dirección visual fue la aprobada por el usuario: herramienta de estudio clara, sobria y con acento azul. El generador de conceptos se ejecutó con servicio remoto no disponible; no se usó ese resultado para reemplazar la dirección aprobada. La revisión final y sus pruebas se registran en VERIFICACION.md.