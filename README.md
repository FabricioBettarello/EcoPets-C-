# Projeto Sensor de Temperatura, Umidade e Altura da Água
O Projeto EcoPets é uma iniciativa dedicada à preservação do meio ambiente, com foco especial nos oceanos. Por meio da criação de robôs para a limpeza dos mares, utilizamos uma combinação de tecnologias avançadas para enfrentar os desafios ambientais.

## Descrição
Este projeto consiste em dois componentes principais: o **Robô Tartaruga**, que monitora temperatura e umidade, e o **Robô Golfinho**, que mede a altura da água. Ambos são projetados para fornecer dados ambientais precisos e alertas em tempo real.

## Funcionalidades
- **Robô Tartaruga**: Sensor de temperatura e umidade.
- **Robô Golfinho**: Sensor de altura da água com alertas visuais e sonoros.

## Componentes
- Arduino
- Sensor de Temperatura e Umidade (DHT11/DHT22)
- Sensor Ultrassônico (HC-SR04)
- Servo Motor
- LEDs (Vermelho, Amarelo, Verde)
- Buzzer
- LCD I2C
- Resistores

## Instruções de Uso
1. Conecte os componentes conforme o esquemático fornecido.
2. Carregue o código no Arduino.
3. Posicione o Robô Tartaruga e o Robô Golfinho nos locais desejados.
4. Monitore as leituras de temperatura, umidade e altura da água no display LCD.

## Requisitos
- Arduino IDE
- Bibliotecas: `LiquidCrystal_I2C`, `Servo`

## Dependências
Instale as bibliotecas necessárias usando o Gerenciador de Bibliotecas na Arduino IDE:
```cpp
#include <LiquidCrystal_I2C.h>
#include <Servo.h>
```

## Código de Exemplo
O código a seguir é responsável pelo funcionamento do Robô Golfinho:
```cpp
#include <LiquidCrystal_I2C.h>
#include <Servo.h>
// Definições de pinos e inicializações
// ...
void setup() {
  // Configurações iniciais
}
void loop() {
  // Lógica principal
}
```

## Alertas
- **Verde**: Nível de água seguro.
- **Amarelo**: Nível de água moderado.
- **Vermelho**: Nível de água crítico, aciona o alarme e abre o portão.

## Contribuições
Fabricio Bettarello RM 554638 e Eric Yuji RM 554869
