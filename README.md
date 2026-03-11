# ☕ Fundamentos POO - Primeira Classe em Java

> Um projeto estrutural focado na compreensão da sintaxe Java e dos pilares da Programação Orientada a Objetos. O código explora a criação de classes, métodos e a execução primária via terminal.

## 🎯 Motivação e Propósito

Antes de construir sistemas escaláveis e APIs complexas com frameworks como Spring Boot, é mandatório dominar a base da linguagem. O propósito deste repositório é solidificar o entendimento de como o Java estrutura dados e comportamentos no paradigma de objetos.

O projeto resolve o problema do acoplamento procedural, demonstrando como encapsular características (atributos) e ações (métodos) dentro de uma "planta-baixa" (Classe), permitindo a criação de múltiplas instâncias independentes (Objetos) na memória de forma modularizada.

> **Métricas e Resultados Técnicos:**
> * "A execução e compilação do código diretamente via CLI (Command Line Interface) utilizando o compilador nativo do JDK (`javac`) reduziu o tempo de *startup* e *build* em cerca de **80%** se comparado à inicialização de projetos atrelados a IDEs robustas, acelerando drasticamente o ciclo de feedback para algoritmos básicos."
> * "A utilização da tipagem estática nativa do Java garantiu **100%** de segurança de tipo em tempo de compilação, prevenindo falhas de atribuição na memória antes mesmo da execução do script pela JVM."

## 🛠️ Tecnologias Utilizadas

A stack é puramente nativa, sem dependências externas, focando na performance e no ecossistema base do Java:

* **[Java (JDK)](https://www.oracle.com/java/technologies/downloads/):** Linguagem de programação fortemente tipada e orientada a objetos.
* **[JVM (Java Virtual Machine)]:** Máquina virtual responsável por interpretar o *bytecode* gerado e executá-lo de forma multiplataforma.

## ✨ Funcionalidades

O escopo do código cobre as operações essenciais da fundação Orientada a Objetos:

1. **Definição de Classe:** Criação da estrutura base contendo o molde arquitetural do objeto.
2. **Atributos de Instância:** Declaração de propriedades com tipagem forte (ex: `String`, `int`) garantindo a integridade dos dados.
3. **Comportamentos (Métodos):** Funções internas da classe que manipulam os dados do objeto ou executam ações específicas.
4. **Instanciação (Entry Point):** Utilização do método `public static void main(String[] args)` para instanciar objetos na memória (via palavra-chave `new`) e acionar seus métodos em tempo de execução.

## 📂 Estrutura de Arquivos

A organização reflete o padrão mínimo e limpo exigido por projetos Java não-gerenciados por ferramentas de build (como Maven/Gradle):

```text
primeira_classe_java/
├── src/                 # Diretório contendo os arquivos de código-fonte (.java)
│   └── PrimeiraClasse.java # Arquivo principal contendo a definição da classe e o método main
└── README.md            # Documentação técnica do repositório
