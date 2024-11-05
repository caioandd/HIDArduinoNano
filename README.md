# Virtualização de HID para Arduino Nano

Este repositório foi criado para facilitar o acesso às informações sobre como virtualizar o HID (Human Interface Device) para o Arduino Nano e microcontroladores compatíveis. O Arduino Nano não possui suporte nativo para essa funcionalidade, sendo necessária a utilização de softwares de terceiros para implementar a virtualização HID. Outros microcontroladores que não possuem suporte nativo também podem se beneficiar desta solução.

## Pré-requisitos

- Arduino Nano (ou outro microcontrolador compatível sem suporte nativo para HID)
- Software de virtualização HID

## Ferramentas Utilizadas

- **vJoy**: Um driver de joystick virtual que permite a criação de dispositivos HID customizados.
  - [Download do vJoy](https://sourceforge.net/projects/vjoystick/)
- **vJoySerialFeeder**: Ferramenta que facilita a comunicação entre o Arduino e o vJoy.
  - [Repositório GitHub do vJoySerialFeeder](https://github.com/Cleric-K/vJoySerialFeeder/tree/master)
  - [Download do vJoySerialFeeder](https://github.com/Cleric-K/vJoySerialFeeder/releases)

## Instalação

1. Baixe e instale o **vJoy** no seu sistema.
2. Faça o download do **vJoySerialFeeder** a partir do repositório GitHub e siga as instruções para instalação e configuração.

## Uso

1. Conecte o Arduino Nano ao computador.
2. Faça upload do código escolhido no microcontrolador.
3. Abra o **vJoySerialFeeder**, conecte a porta COM desejada e configure-o conforme as instruções do projeto.

## Tutorial em Vídeo

Para um guia passo a passo, assista ao nosso [vídeo tutorial](#).

## Referências

- Repositório vJoySerialFeeder: [GitHub](https://github.com/Cleric-K/vJoySerialFeeder/tree/master)
