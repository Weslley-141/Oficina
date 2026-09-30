# 🔧 Sistema de Oficina em Java

> ⚠️ **Nota:** Este repositório é um **re-upload** de um projeto desenvolvido anteriormente, publicado nesta conta para fins de organização, preservação do histórico de código e atualização de portfólio.

Um sistema de simulação e gerenciamento de uma **oficina mecânica**, desenvolvido durante minha formação em **Desenvolvimento de Sistemas**, com foco na aplicação de conceitos de **Programação Orientada a Objetos (POO)** utilizando Java.

O projeto representa diferentes elementos de uma oficina, como clientes, mecânicos, veículos, motores e consertos, utilizando classes, herança, interfaces, enumerações e estruturas genéricas.

---

## 🎯 Objetivo

O projeto foi desenvolvido como uma atividade prática de **Programação Orientada a Objetos**, tendo como objetivo aplicar conceitos fundamentais de POO na construção de um sistema baseado em uma oficina mecânica.

A atividade também buscou trabalhar diferentes recursos da linguagem Java, incluindo **classes abstratas, herança, interfaces, enums, generics e sobrescrita de métodos**.

---

## 🏗️ Estrutura do sistema

O sistema é composto por classes responsáveis por representar os principais elementos da oficina.

### 👥 Pessoas

- `Pessoa` — classe abstrata que representa uma pessoa.
- `Cliente` — representa os clientes e o veículo vinculado.
- `Mecanico` — representa os mecânicos e suas especialidades.
- `IMecanico` — interface relacionada às atividades realizadas pelo mecânico.

### 🚗 Veículos

- `Veiculo` — classe abstrata para representação dos veículos.
- `Carro` — especialização de `Veiculo` para automóveis.
- `Moto` — especialização de `Veiculo` para motocicletas.
- `Motor` — representa o motor associado ao veículo.

### 🔧 Consertos

A classe `Consertos` representa os serviços realizados na oficina, relacionando:

- Veículo
- Mecânico
- Data
- Custo
- Status
- Prioridade
- Tipo de serviço

O sistema também possui operações para:

- Iniciar um conserto
- Finalizar um conserto
- Cancelar um conserto
- Atualizar a prioridade

---

## 🧩 Conceitos de POO praticados

Durante o desenvolvimento foram trabalhados conceitos como:

- Classes e objetos
- Encapsulamento
- Herança
- Classes abstratas
- Polimorfismo
- Interfaces
- Enumerações (`enum`)
- Sobrescrita de métodos com `@Override`
- Composição entre objetos
- Classes genéricas
- `ArrayList<T>`
- `Predicate<T>`
- `LocalDate`

---

## 🏷️ Enumerações

O sistema utiliza diferentes `enum` para representar categorias e estados da aplicação:

- `TipoCombustivel`
- `StatusConserto`
- `EspecialidadeMecanico`
- `PrioridadeConserto`
- `TipoServico`

Essas enumerações são utilizadas para representar valores predefinidos relacionados aos veículos, mecânicos e serviços da oficina.

---

## 📋 Listagem genérica

A classe `ListagemGenerica` utiliza **Generics** e `ArrayList<T>` para permitir o gerenciamento de diferentes tipos de registros.

Entre as operações previstas estão:

- Adicionar elementos
- Remover elementos
- Listar elementos
- Buscar elementos utilizando `Predicate<T>`
- Consultar o tamanho da lista

---

## 🛠️ Tecnologias

- **Java**
- **Programação Orientada a Objetos**
- **Eclipse IDE** — ambiente utilizado durante o desenvolvimento original

---

## 💻 Como executar

O projeto foi desenvolvido originalmente utilizando o **Eclipse IDE** e possui uma aplicação executada através do terminal.

### Pré-requisitos

- **Java JDK** instalado
- Uma IDE compatível com Java, caso deseje importar o projeto

### Execução

1. Clone o repositório:

   ```bash
   git clone https://github.com/Weslley-141/Oficina.git
   cd Oficina
   ```

2. Importe o projeto na IDE de sua preferência.

3. Localize a classe `Main`.

4. Execute o método `main`.

5. Utilize o sistema através do terminal.

---

## 📂 Estrutura

```text
Oficina/
│
├── src/
│   ├── module-info.java
│   │
│   └── oficina/
│       ├── TipoCombustivel.java
│       ├── StatusConserto.java
│       ├── EspecialidadeMecanico.java
│       ├── PrioridadeConserto.java
│       ├── TipoServico.java
│       ├── Pessoa.java
│       ├── IMecanico.java
│       ├── Cliente.java
│       ├── Mecanico.java
│       ├── Veiculo.java
│       ├── Carro.java
│       ├── Moto.java
│       ├── Motor.java
│       ├── Util.java
│       ├── ListagemGenerica.java
│       ├── Consertos.java
│       └── Main.java
│
└── README.md
```

---

## 📚 Contexto acadêmico

Projeto desenvolvido durante o curso de **Desenvolvimento de Sistemas**, como atividade prática de Programação Orientada a Objetos.

A proposta da atividade foi baseada na construção de um sistema de oficina mecânica, utilizando conceitos de POO para representar seus diferentes componentes e relacionamentos.

---

## 👨‍💻 Autor

**Weslley Eugênio**

GitHub: [@Weslley-141](https://github.com/Weslley-141)
