# 👻 Agenda telefônica

> [!NOTE]
> O projeto é um programa feito em `C` de uma **agenda telefônica**, contando com `read`, `create` e `delete`  da **lista local**. Funcionando somente enquanto o programa estiver rodando, _não salvando nada em arquivos_, mas podendo ser facilmente implementado desta forma. O trabalho foi feito para a matéria de programação I na faculdade [^1]

**Ela possui 4 "estados":**

1. Visualizar Lista **(read)**
2. Inserir um telefone **(create)**
3. Remover um telefone **(delete)**
4. `Sair`

## ☕ Info

- **Matéria**: Programação I [^1]
- **Linguagem**: `C`
- **Data**: 12/10/2023

## 🐛 Comandos

### Setup
```bash
# Compilar o programa em um arquivo ./programa
make

# Rodar o programa
./programa
```

### Debug
```bash
# Verifica vazamentos de memoria
valgrind --leak-check=full --track-origins=yes -s ./theboys
```

### Limpeza
```bash
# Remove arquivos .o e executaveis
make clean
```

## 🚀 Arquivos

    .
    ├── biblioteca                   # Todas as funções do programa e defines
    ├── programa                     # Contém o MAIN() e o loop de estados
    ├── makefile                     # Arquivo MAKE para compilação
    |
    └── README.md                   

[^1]: Faculdade de **Informática Biomédica** na Universidade Federal do Paraná no ano de 2023 (segundo semestre), o curso se consiste em uma matriz de ciência da computação com matérias focadas as áreas biomédicas e aplicações da computação em áreas médicas, como genética.
