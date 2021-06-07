# Zusammenfassung - Beginning STM32

## Kapitel 3 - Entwicklungsumgebung

### Benötigte Bibliotheken/Software
- libopencm3
- FreeRTOS
- ST-link Tools

### ST-link Tools
Nützliche Kommandos fürs schreiben und lesen von STM32 Controllern.
- `st-info --probe`
- `st-flash read ./file.img 0x8000000 0x1000`
- `st-flash write ./file.img 0x8000000`
- `st-flash erase`

## Kapitel 4 - GPIO

### Benötigte Bibliotheken aus libopencm3

- libopencm3/stm32/rcc.h <- Clock für GPIO Peripherie aktivieren
- libopencm3/stm32/gpio.h
