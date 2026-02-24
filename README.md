# 01 - Lista Simplesmente Encadeada (Linked List)

## Descrição
Exercício com Lista Simplesmente Encadeada (Linked List).

## Funcionalidades
- [x] Criação/Inicialização: Criar uma lista vazia
- [ ] Inserção (início, fim ou posição específica)
- [ ] Remoção (início, fim ou posição específica)
- [ ] Busca: Encontrar um elemento específico na lista.
- [ ] Percorrimento (Traverse): Acessar todos os elementos
- [ ] Tamanho: Obter o número de elementos
- [ ] Destruição: Liberar a memória da lista

## Pré-requisitos

## Ferramentas de Desenvolvimento
1. **Compilador C++**:
    - Windows: MinGW-w64 (gcc) ou MSVC (Visual Studio)
    - Linux: g++
2. **CMake** para build automatizado

## Instalação

1. **Clone o repositório:**
   `git clone https://github.com/<NOME_REPOSITORIO_CRIADO>`

2. **Build do projeto:**

    * Linux:
        ```bash
        mkdir build && cd build
        cmake ..
        make
        ```

    * Windows (executando a partir de Windows):
        ```bash
        mkdir build && cd build

        # Gera os arquivos de build (usando MinGW)
        cmake .. -G "MinGW Makefiles"

        # Ou usando MSVC (se tiver Visual Studio instalado)
        cmake .. -G "Visual Studio 17 2022"

        # Compila
        cmake --build .
        ```

# Execução

## Fluxo de Execução
Após o build do projeto, executar via CLI:

```bash
./build/linked_list
```

O CLI irá mostrar algo como:

```bash
Exercício de Linked List
Cardinalidade da Lista: 0
```

## Fluxo de Testes

A fazer.
