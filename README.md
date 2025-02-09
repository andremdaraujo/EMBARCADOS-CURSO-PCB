# PROJETO DE PCB PARA SISTEMAS EMBARCADOS
  
Esta é uma placa de desenvolvimento educacional concebida como parte curso 
[**Projeto e PCB para Sistemas Embarcados**]( https://cursos.embarcados.com.br/cursos/projeto-de-pcb-para-sistemas-embarcados/). 
O curso é oferecido em parceria com o [**Portal Embarcados**](https://embarcados.com.br/).
Durante o curso, todas as etapas de projeto e desenvolvimento desta placa são mostradas, passo a passo. 
Neste repositório, é possível acessar a todos os arquivos de projeto e fabricação.

## Licença
Este é um projeto Open Source, licenciado sob a CERN-OHL-P. Mais detalhes em [LICENSE.md](./LICENSE.md).  
A placa desenvolvida durante o curso foi baseada no projeto [**STM32 Explorer Board - STM32XP**](https://github.com/MechatronixLab/STM32XP), 
que também é licenciado conforme a CERN-OHL-P e certificado pela OSWHA ([OSHW BR000018](https://certification.oshwa.org/br000018.html)).

## Especificações da placa

A placa é baseado no [**STM32F411**](https://www.st.com/en/microcontrollers-microprocessors/stm32f411.html), mais especificamente, o [**STM32F411RET6**](https://www.st.com/en/microcontrollers-microprocessors/stm32f411re.html).
Além disso, a placa apresenta alguns componentes comumente usados em sistemas embarcados, como:
- Conversores DC-DC
- Display OLED, conectado ao MCU via I²C
- LEDs RGB
- Áudio (Buzer Piezoelérico), controlada via PWM
- ADC externo com filtros antialiasing analógicos
- USB 1.1 Full Speed via conector Tipo C
- Cartão Micro SD para fácil armazenamento de dados, conectado ao MCU via SPI
- Botões conectados a pinos de entrada do MCU, além de botões para RESET e BOOT
- Vários pinos de GPIO roteados para conectores/pinos de breakout
- Bateria CR2032 para operação RTC

A placa pode ser utilizada em modo Standalone ou conectada a uma protoboard, dependendo da escolha de conectores:

![Top](./DOC/IMAGES/PCB_CURSO_EMBARCADOS_TOP.png)

![Bottom](./DOC/IMAGES/PCB_CURSO_EMBARCADOS_BOTTOM.png)

![Protoboard](./DOC/IMAGES/PCB_CURSO_EMBARCADOS_PROTO.png)
  
## Firmware

Esta placa pode executar a aplicação de demonstração desenvolvida no projeto [STM32 Explorer Board - STM32XP](https://github.com/MechatronixLab/STM32XP).
