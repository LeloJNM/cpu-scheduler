# CPU Scheduler

## Sobre o Projeto

Este repositório implementa e simula diferentes **algoritmos de escalonamento de CPU**, usados em sistemas operacionais para gerenciar a execução de processos.

## Algoritmos Implementados

- **FCFS (First-Come, First-Served)**
- **SJF (Shortest Job First)**
- **RR (Round Robin, quantum = 2)**

## Como Usar

### Requisitos

- Python 3.x instalado

### Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/cpu-scheduler.git
   cd cpu-scheduler
   ```
2. Execute o simulador:
   ```bash
   python scheduler.py
   ```

## Estrutura do Repositório

```
.
├── scheduler.py  # Arquivo principal para execução dos algoritmos
├── algorithms/   # Implementação dos diferentes algoritmos de escalonamento
├── data/         # Casos de teste e exemplos de entrada
├── results/      # Saídas e relatórios gerados
├── README.md     # Documentação do projeto
```

## Entrada e Saída

## Entrada e Saída

### Descrição da Entrada
A entrada é composta por uma série de pares de números inteiros separados por um espaço em branco, indicando o tempo de chegada e a duração de cada processo. A entrada termina com o fim do arquivo.

**Exemplo de entrada:**
```
0 20
0 10
4 6
4 8
```

### Descrição da Saída
A saída é composta por linhas contendo a sigla de cada um dos três algoritmos e os valores das três métricas solicitadas.
Cada linha apresenta:
- A sigla do algoritmo
- O tempo de retorno médio
- O tempo de resposta médio
- O tempo de espera médio

Os valores médios devem ser apresentados com uma casa decimal e separados por um espaço em branco.

**Exemplo de saída:**
```
FCFS 30.5 19.5 19.5
SJF 21.5 10.5 10.5
RR 31.5 2.0 20.5
```




## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.





