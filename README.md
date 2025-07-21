# SuperCalcs-0.0.1
Uma super calculadora programada em Linguagem C

# SuperCalcs

![Capa/Banner do Projeto (Opcional)](https://via.placeholder.com/800x300?text=SuperCalcs+-+A+Calculadora+Completa)

Uma aplicação de console simples, mas poderosa, desenvolvida em C para realizar operações matemáticas básicas e outras funcionalidades úteis. O SuperCalcs foi criado com o objetivo de ser uma ferramenta rápida e eficiente para o dia a dia, oferecendo uma interface de usuário intuitiva via terminal.

## 🚀 Funcionalidades Atuais

* **Operações Básicas:** (Ex: Adição, Subtração, Multiplicação, Divisão - *detalhe mais se já tiver implementado*)
* **Tabuada:** Gerador de tabuadas interativo.
* **Menu de Navegação:** Sistema de menu claro para fácil acesso às diferentes funcionalidades.
* **Pausa e Carregamento:** Funções de pausa e barra de carregamento visual para uma melhor experiência do usuário.
* **Números Ordinais:** Conversão de números em texto ordinal (ex: "primeiro", "segundo").

## ✨ Sobre o SuperCalcs

* **Versão Atual:** `0.0.1`
* **Data da Criação da Versão:** `20/07/2025 - 21/07/2025`
* **Desenvolvedor:** `André Jorge`
* **Idiomas Suportados:** `Português Brasil (PT-BR)`
* **Sistemas Suportados:** `Windows`, `Linux`, `MacOS`

## 🛠️ Como Compilar e Rodar

Para compilar e executar o SuperCalcs, você precisará de um compilador C (como o GCC/MinGW).

### Pré-requisitos

* [GCC (GNU Compiler Collection)](https://gcc.gnu.org/)
    * No Windows, você pode usar o [MinGW-w64](https://www.mingw-w64.org/).
    * No Linux, instale via seu gerenciador de pacotes (ex: `sudo apt install build-essential` no Debian/Ubuntu).
    * No macOS, instale as [Xcode Command Line Tools](https://developer.apple.com/xcode/features/).

### Compilação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SeuUsuario/SuperCalcs.git](https://github.com/SeuUsuario/SuperCalcs.git)
    cd SuperCalcs
    ```
    *(Substitua `SeuUsuario/SuperCalcs.git` pelo caminho real do seu repositório)*

2.  **Compile o código:**
    Assumindo que seus arquivos `.c` estão na raiz do projeto (`main.c`, `menu.c`, `utils.c`, `op_basicas.c`, `tabuada.c`, etc.), você pode compilá-los com um comando similar a este:

    ```bash
    # Para Linux/macOS
    gcc -o supercalcs main.c menu.c utils.c op_basicas.c tabuada.c -Wall -std=c11

    # Para Windows (com MinGW/GCC)
    # Se você está usando o CLion com CMake, ele fará isso automaticamente.
    # Caso contrário, um comando manual poderia ser:
    gcc -o supercalcs.exe main.c menu.c utils.c op_basicas.c tabuada.c -Wall -std=c11
    ```
    * `supercalcs` (ou `supercalcs.exe`) será o nome do seu executável.
    * `main.c menu.c utils.c op_basicas.c tabuada.c` - Liste todos os seus arquivos `.c`.
    * `-Wall`: Habilita todos os avisos (boa prática!).
    * `-std=c11`: Define o padrão C11 (ou `c99` se preferir). Você pode usar `gnu2x` como está no seu CLion, mas `c11` é mais portátil.

### Execução

Após a compilação:

```bash
# No Linux/macOS
./supercalcs

# No Windows
supercalcs.exe
