# Simulação de Ecossistema em 3D

Este projeto é uma simulação 3D de um ecossistema que utiliza a biblioteca Three.js para renderização gráfica em WebGL e programação em JavaScript. Ele apresenta interações realistas entre diferentes elementos, incluindo árvores e coelhos.

## Configuração do Projeto

Antes de executar a simulação, certifique-se de ter as seguintes dependências instaladas:

- [Three.js](https://threejs.org/): A biblioteca que fornece funcionalidades para criar gráficos 3D.

## Inicialização do Projeto

1. **Clone este repositório para o seu ambiente local:**

    ```bash
    git clone https://github.com/MiguelPereiraDantas/Simula-o-de-Ecossistema-em-3Dgit
    ```

2. **Navegue até o diretório do projeto:**

    ```bash
    cd simulacao-ecossistema-3d
    ```

3. **Execute um servidor web local para servir os arquivos.**

    - Você pode usar o [http-server](https://www.npmjs.com/package/http-server) como exemplo:

        ```bash
        npm install -g http-server
        http-server
        ```

    - Ou use a extensão Live Server do VS Code, se estiver utilizando o Visual Studio Code.

4. **Abra o navegador e acesse o endereço fornecido pelo servidor local (geralmente [http://localhost:8080](http://localhost:8080)).**

## Estrutura do Projeto

- **index.html**: O arquivo HTML principal que contém a estrutura da página e os scripts necessários.
- **GLTFLoader.js**: O script para carregar modelos GLTF usando a biblioteca Three.js.
- **tree/scene.gltf**: Modelo 3D de uma árvore no formato GLTF.
- **bunny_character/bunny.gltf**: Modelo 3D de um coelho no formato GLTF.

## Funcionalidades

- **Árvore 3D**: Uma árvore é renderizada na simulação com posição inicial configurada.
- **Coelho 3D**: Um modelo de coelho é renderizado com uma posição inicial definida.
- **Animação Simples**: A simulação apresenta uma animação básica, movendo o coelho para a direita e permitindo o crescimento vertical e horizontal da árvore.

## Contribuição

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou adição de novos recursos. Basta seguir as diretrizes de contribuição e enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
