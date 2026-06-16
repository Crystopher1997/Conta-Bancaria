# Sistema Bancário - Projeto Tutorial 🚀

Este é um projeto conceitual de um **Sistema Bancário** desenvolvido em **Java**. O objetivo principal deste projeto é praticar conceitos de **Programação Orientada a Objetos (POO)**, incluindo encapsulamento, composição entre classes, organização em pacotes e manipulação de objetos.

O sistema simula uma estrutura bancária básica, onde uma conta bancária está associada a um titular, permitindo o gerenciamento de informações do cliente e operações financeiras simples.

---

## 🛠️ Tecnologias Utilizadas

* **Java SE**
* **JDK (Java Development Kit)**
* **IDE Recomendada:** NetBeans, IntelliJ IDEA ou Eclipse

---

## ⚙️ Funcionalidades

* Cadastro de clientes com nome, idade, renda e CPF.
* Criação de contas bancárias associadas a um titular.
* Consulta de dados do titular através da conta.
* Realização de depósitos.
* Realização de saques.
* Controle de saldo da conta.

---

## 🎯 Conceitos Aplicados

* Programação Orientada a Objetos (POO)
* Encapsulamento
* Composição entre classes
* Getters e Setters
* Organização em pacotes
* Instanciação de objetos
* Relacionamento entre objetos

---

## 📁 Estrutura de Pacotes

```text
src/
├── Cadastro/
│   └── Pessoa.java
├── Banco/
│   └── Conta.java
└── projetotutorial/
    └── ProjetoTutorial.java
```

### Relacionamento entre Classes

O projeto utiliza o conceito de **Composição/Associação**, onde a classe `Conta` possui um atributo do tipo `Pessoa`, garantindo que cada conta esteja vinculada a um titular.

---

## 💻 Exemplo de Utilização

```java
// Criando o titular
Pessoa novaPessoa = new Pessoa("Crys", 25, 2500, 123456789);
novaPessoa.setNome("Cassio");

// Criando a conta vinculada ao titular
Conta conta1 = new Conta(novaPessoa, 123, 123456789);

// Exibindo o nome do titular a partir da conta
System.out.println(conta1.getTitular().getNome());
// Saída: Cassio
```

---

## 🚀 Como Executar o Projeto

1. Certifique-se de possuir o JDK instalado em sua máquina.
2. Clone este repositório:

```bash
git clone https://github.com/Crystopher1997/Conta-Bancaria.git
```

3. Abra o projeto na IDE de sua preferência.
4. Compile e execute a classe `ProjetoTutorial.java`.

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos fundamentais da linguagem Java, como:

* Criação e utilização de classes e objetos.
* Encapsulamento de atributos.
* Utilização de construtores.
* Relacionamento entre objetos.
* Organização do código em pacotes.
* Aplicação de boas práticas de orientação a objetos.

---

## 👨‍💻 Autor

Desenvolvido por **Crystopher Carvalho**

GitHub: https://github.com/Crystopher1997
