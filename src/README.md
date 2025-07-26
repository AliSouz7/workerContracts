# Sistema de Cálculo de Rendimento de Funcionários por Contrato - Java

## 📋 Descrição

Este projeto é um sistema simples desenvolvido em Java que simula a estrutura de funcionários, departamentos e contratos por hora. Através de entradas via terminal, o programa permite:

- Cadastrar um funcionário vinculado a um departamento.
- Adicionar múltiplos contratos de trabalho por hora.
- Calcular o rendimento do funcionário em um determinado mês/ano, somando salário base e valores dos contratos realizados naquele período.

## 📂 Estrutura do Projeto

```text
src/
├── application/
│   └── Program.java
├── entities/
│   ├── Department.java
│   ├── HourContract.java
│   └── Worker.java
└── enumentities/
    └── WorkerLevel.java
```

**Descrição dos arquivos:**

- `Program.java`: Classe principal que executa a aplicação.
- `Department.java`: Representa o departamento do funcionário.
- `HourContract.java`: Representa contratos por hora.
- `Worker.java`: Representa o funcionário.
- `WorkerLevel.java`: Enum com os níveis possíveis de um funcionário (`JUNIOR`, `MID_LEVEL`, `SENIOR`).




## 🚀 Como Executar

1. Compile o projeto:
   ```bash
   javac application/Program.java

Execute:

java application.Program

💡 Exemplo de Funcionamento

Enter department's name: Design

Enter worker data:

Name: João Silva

Level: MID_LEVEL

Base salary: 2000.00

How many contracts to this worker? 2

Enter contract #1 data

Date (DD/MM/YYYY): 20/07/2025

Value per Hour: 50.00

Duration(hours): 10

Enter contract #2 data

Date (DD/MM/YYYY): 13/07/2025

Value per Hour: 30.00

Duration(hours): 20


Enter month and year to calculate income (MM/YYYY): 07/2025

Name: João Silva

Department: Design

Income for 07/2025: 2900.00


🧠 Conceitos Utilizados
Programação Orientada a Objetos (POO)

Composição de objetos

Enumeração

Manipulação de datas

Entrada/Saída de dados no terminal


🛠 Requisitos

Java JDK 8 ou superior

👨‍💻 Autor
Desenvolvido por [Alisson Souza Costa]


---




