# PROJETO INTEGRADO DE COMPUTAÇÃO I: 
## _Robô que desvia de obstáculos_

Projeto final apresentado à disciplina de Projeto Integrado de Computação 1, da Universidade Federal do Espírito Santo.

## Descrição

O projeto consite em um robô que desvia de obstáculos. Inicialmente, o robô percorre em linha reta até que encontre algum obstáculo. Quando isto acontece, os arredores do robô são analisados, por um sensor ultrassom, que determina a distância à cada um dos lados. O robô então escolhe a melhor rota que se deve tomar para evitar o obstáculo. Quando o robô se encontra encurralado, ou seja, quando as distâncias da direita, da esquerda e da frente são pequenas, ele se move para trás até que se livre do obstáculo.

## Instruções

O código do robô utiliza duas bibliotecas que precisam ser instaladas, a bilioteca  [_Servo.h_](https://github.com/arduino-libraries/Servo) e [_Ultrassonic.h_](https://www.arduino.cc/reference/en/libraries/ultrasonic/). Ambas podem ser encontradas nos links disponibilizados. Instaladas as bibliotecas, basta realizar o upload do código através do arduino IDE.

## Componentes

- Quatro rodas
- Quatro motores
- Ponte H L298N
- Sensor ultrassom HC­SR04
- Servo motor TowerPro SG90
- Jumpers
- Arduino Uno
- Bateria de 9V
- Power Bank

## Video do projeto
[![Robô que desvia de obstáculos](https://i9.ytimg.com/vi_webp/QRAf1Roo5vg/mq1.webp?sqp=CMSM5J4G-oaymwEmCMACELQB8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGBMgRCh_MA8=&rs=AOn4CLAeFeMmTCtIopGS5Vy4BOB8iBi0sw)](https://youtu.be/QRAf1Roo5vg)
