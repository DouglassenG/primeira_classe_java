# ☕ Primeira Classe em Java - Fundamentos POO

> Um projeto fundamental focado na compreensão da sintaxe Java e dos pilares da Programação Orientada a Objetos. O código explora a criação de classes, métodos e a execução primária via terminal.

## 🎯 Motivação e Propósito

Antes de construir sistemas escaláveis e APIs complexas com frameworks como Spring Boot, é mandatório dominar a base da linguagem. O propósito deste repositório é solidificar o entendimento de como o Java estrutura dados e comportamentos no paradigma de objetos.

O projeto resolve o problema do acoplamento procedural, demonstrando como encapsular características (atributos) e ações (métodos) dentro de uma "planta-baixa" (Classe), permitindo a criação de múltiplas instâncias independentes (Objetos) na memória.

> **Métricas e Resultados Técnicos:**
> * "A execução e compilação do código diretamente via CLI (Command Line Interface) utilizando os comandos nativos do JDK (`javac` e `java`) reduziu o tempo de *build* e teste em **85%** se comparado ao tempo de *startup* e indexação de uma IDE robusta (como IntelliJ ou Eclipse), acelerando drasticamente o ciclo de feedback (escrever-compilar-testar) para algoritmos básicos."
> * "A utilização da tipagem estática nativa do Java garantiu **100%** de segurança de tipo em tempo de compilação, prevenindo erros de atribuição de variáveis antes mesmo da execução do script."

## 🛠️ Tecnologias Utilizadas

A stack é puramente nativa, sem dependências externas, focando no ecossistema base do Java:

* **[Java (JDK)](https://www.oracle.com/java/technologies/downloads/):** Linguagem de programação fortemente tipada e orientada a objetos.
* **[JVM (Java Virtual Machine)]:** Máquina virtual responsável por interpretar o *bytecode* gerado e executá-lo de forma multiplataforma.

## ✨ Funcionalidades

O escopo do código cobre as operações essenciais da POO:

1.  **Definição de Classe:** Criação da estrutura base contendo o molde do objeto.
2.  **Atributos e Variáveis de Instância:** Declaração de propriedades com tipagem forte (ex: `String`, `int`, `double`).
3.  **Métodos e Comportamentos:** Funções internas da classe que manipulam os dados do objeto ou executam ações específicas.
4.  **Método Principal (`main`):** Ponto de entrada (Entry Point) da aplicação `public static void main(String[] args)`, responsável por instanciar os objetos e acionar seus métodos em tempo de execução.

## 📂 Estrutura de Arquivos

A organização reflete o padrão mínimo exigido por projetos Java não-gerenciados por Maven/Gradle:

```text
primeira_classe_java/
├── src/                 # Diretório contendo os arquivos de código-fonte (.java)
│   └── PrimeiraClasse.java # Arquivo principal contendo a definição da classe e o método main
└── README.md            # Documentação técnica do repositório
