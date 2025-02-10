# 🚀 Projeto TAREFA U4C6 - Display OLED e Matriz LED

Este projeto faz parte da **Residência do CEPEDI de Sistemas Embarcados** e demonstra a integração de múltiplos componentes e protocolos de comunicação utilizando a **Raspberry Pi Pico**. O sistema inclui um **display OLED SSD1306, matriz LED WS2812, botões físicos e comunicação serial via UART**.

## 📜 **Sobre o Projeto**
O projeto **TAREFA U4C6** implementa um sistema interativo que permite:
- **Entrada de caracteres via Serial Monitor**
- **Controle de LEDs RGB com botões**
- **Exibição de caracteres no display OLED SSD1306**
- **Representação de números na matriz LED WS2812 5x5**

---

## 🎥 **Demonstração em Vídeo**
🔗 https://youtube.com/shorts/EwSZflzCO50?feature=share  


---

## ⚡ **Funcionalidades Principais**
### 🔠 **Entrada de Caracteres via PC**
✅ Recebe caracteres individuais pelo **Serial Monitor**  
✅ Exibe os caracteres no **display OLED SSD1306**  
✅ Quando números (0-9) são digitados, exibe padrões correspondentes na **matriz LED WS2812**

### 🎛 **Controle via Botões**
✅ **Botão A:** Liga/desliga o **LED RGB Verde**  
✅ **Botão B:** Liga/desliga o **LED RGB Azul**  
✅ Feedback visual no **display OLED** e mensagens no **Serial Monitor**  
✅ **Debouncing** implementado via software

### 📟 **Display OLED SSD1306**
✅ Suporte a **caracteres maiúsculos e minúsculos**  
✅ Exibição de **mensagens de status**  
✅ Comunicação via **I2C**

### 🔳 **Matriz LED WS2818**
✅ Padrões **5x5** para representação de números  
✅ Controle **individual** de cada LED RGB  
✅ Comunicação eficiente via **PIO**


## 🔧 **Requisitos de Hardware**
🔹 **Placa**: BitDogLab com RP2040 (Raspberry Pi Pico)  
🔹 **Display**: OLED SSD1306 **128x64**  
🔹 **Matriz LED**: **WS2812 5x5**  
🔹 **Botões físicos**: 2 (A e B)  
🔹 **LEDs RGB**  
🔹 **Computador** com porta **USB**  

---

## 🚀 **Como Usar**
1️⃣ **Clone o repositório**  
```sh
git clone https://github.com/Vivian-RC/Embarca_03_02.git
cd Embarca_03_02
