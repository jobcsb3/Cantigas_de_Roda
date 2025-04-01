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

