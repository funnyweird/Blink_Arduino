# Exercício Arduino - LED Blink

## Código Implementado

### Arquivo: `blink.c`

```c
#include <Arduino.h>

void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```

### Explicação do Código

1. **`#include <Arduino.h>`**: Inclui as bibliotecas básicas do Arduino
2. **`void setup()`**: Função executada uma única vez na inicialização
   - `pinMode(LED_BUILTIN, OUTPUT)`: Configura o pino do LED como saída
3. **`void loop()`**: Função executada continuamente
   - `digitalWrite(LED_BUILTIN, HIGH)`: Liga o LED
   - `delay(1000)`: Aguarda 1000ms (1 segundo)
   - `digitalWrite(LED_BUILTIN, LOW)`: Desliga o LED
   - `delay(1000)`: Aguarda mais 1 segundo

## Evidências da Implementação

### Vídeo Demonstrativo

Aqui está um vídeo demonstrando o funcionamento do LED piscando:

[![Vídeo do LED Piscando](blink_video.mp4)](blink_video.mp4)


> **Nota**: O vídeo também está disponível como arquivo separado: [`blink_video.mp4`](blink_video.mp4)