# Packmol

Packmol é um software gratuito usado para construir configurações iniciais para simulações de dinâmica molecular. Ele garante que as moléculas não se sobreponham, simplificando a preparação inicial de simulações.

## Citação

Se o Packmol for útil em suas publicações, por favor, cite a seguinte referência:

```
L. Martínez, R. Andrade, E. G. Birgin, J. M. Martínez. Packmol: A package for building initial configurations for molecular dynamics simulations. Journal of Computational Chemistry, 30(13):2157-2164, 2009.
```

---

## Como instalar e usar o Packmol

### Método mais fácil: Usando o wrapper Julia para Packmol

O método mais simples para instalar e usar o Packmol em qualquer plataforma (Windows, macOS, Linux) é através do wrapper Julia. Siga os passos abaixo:

1. **Instale o Julia**:
   - Faça o download do Julia a partir do site oficial: [https://julialang.org/downloads/](https://julialang.org/downloads/)

2. **Instale o pacote Packmol.jl no Julia**:
   - Abra o terminal do Julia e execute:
     ```julia
     import Pkg; Pkg.add("Packmol")
     ```

3. **Execute o Packmol**:
   - No REPL do Julia, digite:
     ```julia
     using Packmol; run_packmol()
     ```
   - Isso abrirá uma interface gráfica (GUI) onde você poderá selecionar o arquivo de entrada a ser usado pelo Packmol.

> **Nota:** Os passos 1 e 2 precisam ser feitos apenas uma vez. O passo 3 deve ser executado toda vez que você desejar rodar o Packmol.

### Alternativas avançadas para instalação

1. **Repositório do código-fonte**:
   - Você pode baixar o código-fonte da versão mais recente no repositório oficial (links como `zip` ou `tar.gz`).
   - Após o download, siga as [instruções de instalação](#) contidas no repositório.

2. **Conda**:
   - O Packmol também está disponível no [conda-forge](https://github.com/conda-forge/packmol-feedstock).
   - Para instalar via conda:
     ```bash
     conda install -c conda-forge packmol
     ```
   - Ou usando mamba:
     ```bash
     mamba install -c conda-forge packmol
     ```

---

Packmol está em constante desenvolvimento, com novos recursos e correções de bugs sendo adicionados regularmente. Reporte qualquer problema ou regressão para que possamos corrigi-los!
