# 🚀 EmbarcaTech 2025 - Fase II

## 📚 Objetivo
Este repositório apresenta o projeto de **Sistemas Embarcados** desenvolvido na **EmbarcaTech 2025 - Fase II**. 
Aqui você encontrará o código-fonte, documentação e recursos utilizados no desenvolvimento do sistema.

## 📂 Estrutura do Repositório

```
/Cantigas_de_Roda
│── /build         # Diretório de compilação (gerado pelo CMake)
│── /src           # Código-fonte principal (.c, .cpp, .py)
│── /include       # Cabeçalhos (.h, .hpp)
│── /lib           # Bibliotecas externas
│── CMakeLists.txt # Configuração do projeto CMake
│── pico_sdk_import.cmake # Importação do SDK da Raspberry Pi
│── README.md      # Documentação do projeto
```

## 🔗 Projetos
Abaixo está a lista de projetos desenvolvidos. Cada um possui um diretório específico dentro do repositório:

- [Cantigas_de_Roda](./Cantigas_de_Roda)
- [Cantigas_de_Roda](./Leitor de Temperatura Interna (RP2040))
- [Cantigas_de_Roda](./Contador Decrescente Controlado por Interrupção)
- [Cantigas_de_Roda](./Conversor de Valores Digital (Joystick))

## 📚 Descrição do Projeto
Cantigas_de_Roda: Este projeto tem como objetivo principal desenvolver um sistema interativo que utilize a eletrônica para estimular o aprendizado infantil por meio das cantigas de roda. Para isso, foi criado um dispositivo que permite às crianças navegarem e selecionarem cantigas de rodas utilizando um joystick e um display OLED, e reproduzi-las utilizando o botão A e os buzzers A e B. 
Leitor de Temperatura Interna (RP2040): Medidor de temperatura interna do RP2040 que coverte a leitura do ADC em um valor em ºC.
Contador Decrescente Controlado por Interrupção: Implementação de um contador decrescente controlado por interrupção.
Conversor de Valores Digital (Joystick): Leitor de valores convertidos digitalmente do joystick da BitDogLab. Os valores podem ser mostrados no terminal ou então no display OLED.

## 🖼️ Setup do Hardware
BitDogLab (Raspberry Pi Pico W, Display OLED SSD1306, Botão A, Buzzer A e Buzzer B, Joystick, Fonte de Alimentação)

## 🛠️ Requisitos e Configuração
Para compilar e rodar os projetos no **Raspberry Pi Pico W**, siga os passos abaixo:

1. **Instale o SDK do Pico** seguindo as instruções oficiais da Raspberry Pi.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   cd meu_projeto
   ```
3. **Crie o diretório de build e compile:**
   ```bash
   mkdir build
   cd build
   cmake ..
   make
   ```
4. **Carregue o firmware no Raspberry Pi Pico W.**

## 👤 Autor
**João Carlos da Silva Brito - Campinas**

Se tiver dúvidas ou sugestões, fique à vontade para contribuir ou abrir uma _issue_. 🚀

