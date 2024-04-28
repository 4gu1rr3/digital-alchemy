# Alquimia Digital 🧙🏻‍♀️✨🖼️
O problema envolve a otimização de uma imagem, onde pixels são trocados de posição para se aproximar de uma imagem desejada. Este algoritmo implementa essa otimização utilizando a técnica de troca de pixels de forma iterativa.

> O algoritmo implementado funciona da seguinte forma:

1. Carrega as imagens origem e desejada.
2. Inicializa a interface gráfica e OpenGL para visualização.
3. Copia a imagem de origem para a imagem de saída.
4. Realiza trocas iterativas de pixels entre a imagem de saída e a imagem desejada.
5. Calcula a diferença de cor entre pixels utilizando a métrica de distância de Manhattan.
6. Se a troca resultar em uma melhoria na diferença de cor, a troca é realizada.
7. Repete o processo até atingir a condição de parada.

## Como executar
Para executar o programa, é necessário ter o ambiente de desenvolvimento configurado para C/C++.
1. Baixe ou clone este repositório.
2. Abra a pasta `alchemy`.
3. Compile o programa utilizando um compilador C/C++.
4. Execute o programa gerado pelo terminal, normalmente com o comando `./alchemy.exe .\img\[imagem_origem] .\img\[imagem_desejada]`.

## Operação do programa
Durante a execução da aplicação, as seguintes teclas estão disponíveis para interação:
- **1**: Exibe a imagem original.
- **2**: Exibe a imagem desejada.
- **3**: Exibe a imagem resultante após a aplicação do algoritmo.
- **v**: Verifica se todos os pixels da imagem desejada foram utilizados na imagem resultante.
- **ESC**: Encerra a execução da aplicação.

## Autores
[Eduarda dos Santos Patricio](https://github.com/e-patricio)

[Yasmin Cardozo Aguirre](https://github.com/4gu1rr3)
