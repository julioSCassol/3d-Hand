# Modelo 3D com OpenGL e Assimp

Este projeto demonstra como carregar e renderizar modelos 3D em OpenGL utilizando as bibliotecas **GLEW**, **GLFW**, **GLM** e **Assimp**. Ele também implementa uma câmera interativa controlada por teclado e mouse.

## Funcionalidades

- **Carregamento de modelos 3D**:
  - Utiliza a biblioteca **Assimp** para importar modelos no formato `.obj`.
- **Câmera interativa**:
  - **Teclado**:
    - `W` e `S`: Movem a câmera para frente e para trás.
    - `A` e `D`: Movem a câmera para os lados.
  - **Mouse**:
    - Controla a direção para onde a câmera está olhando.
- **Renderização 3D**:
  - Utiliza **shaders** para configurar e renderizar modelos 3D com transformações como translação e perspectiva.

## Requisitos

Certifique-se de ter as seguintes dependências instaladas no seu ambiente de desenvolvimento:

1. **Bibliotecas**:
   - [GLEW](http://glew.sourceforge.net/)
   - [GLFW](https://www.glfw.org/)
   - [GLM](https://glm.g-truc.net/0.9.9/index.html)
   - [Assimp](https://github.com/assimp/assimp)

2. **Compilador**:
   - Um compilador compatível com **C++11** ou superior.
   - **OpenGL 3.3** ou superior.

3. **Modelo 3D**:
   - Certifique-se de ter um modelo 3D em formato `.obj` disponível no diretório do projeto. Exemplo: `plant.obj`.

## Como Compilar e Executar

1. Clone o repositório ou copie os arquivos para o seu diretório de trabalho:
   ```bash
   git clone https://github.com/julioSCassol/3d-Hand.git
   cd repositorio
   ```

## Projeto Compilado:

![image](https://github.com/user-attachments/assets/18036703-8e4d-44a6-9cda-241e52f151be)

