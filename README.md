
```mermaid
    gantt

    title Desenvolvimento de Software
    dateFormat  YYYY-MM-DD
    
    section Planejamento
    Requisitos      :done, req, 2023-01-01, 10d
    Design          :active, des, 2023-01-10, 15d
    
    section Desenvolvimento
    Codificação     :crit, dev, 2023-01-25, 30d
    Testes          :test, after dev, 15d
    
    section Lançamento
    Implantação     :dep, after test, 5d
    Treinamento     :tra, after dep, 10d



  
```

```mermaid
flowchart TD
    A(["Exemplo"])
    A --> B{"Faça um Escolha"}
    B --> C["A"]
    B --> E["B"]
    B --> D["C"]
```

```mermaid

graph TD;
  A[inicio] --> B{Nota >6};
  B -->|Sim| C[Aprovado];
 B --> |Não| D[Reprovado];

```


```mermaid
graph TD
    subgraph Matriz
        A1["C8"]:::branco-->  A2["C20"]:::amarelo --> A3["V50"]:::laranja --> A4["V100"]:::vermelho
        B1["D8"]:::branco --> B2["E20"]:::amarelo --> B3["E50"]:::laranja --> B4["E100"]:::vermelho
        C1["D8"]:::branco --> C2["D20"]:::amarelo --> C3["D50"]:::laranja --> C4["D100"]:::vermelho
        D1["C8"]:::branco-->  D2["C20"]:::amarelo --> D3["C50"]:::laranja --> D4["C100"]:::vermelho
    end

    classDef branco fill:#fff,stroke:#000,stroke-width:1px;
    classDef amarelo fill:#FFD84D,stroke:#000,stroke-width:1px;
    classDef laranja fill:#FFA233,stroke:#000,stroke-width:1px;
    classDef vermelho fill:#E64C3C,stroke:#000,stroke-width:1px;


```
```mermaid
graph TD
  

    %% Marcações das situações
    S1["🔵 Situação 1\nProjeto pequeno, baixa criticidade"]:::situacao --> A2
    S2["🔴 Situação 2\nProjeto grande, alta criticidade"]:::situacao --> D3

    classDef branco fill:#fff,stroke:#000,stroke-width:1px;
    classDef amarelo fill:#FFD84D,stroke:#000,stroke-width:1px;
    classDef laranja fill:#FFA233,stroke:#000,stroke-width:1px;
    classDef vermelho fill:#E64C3C,stroke:#000,stroke-width:1px;
    classDef situacao fill:#4DA3FF,stroke:#000,stroke-width:1px,stroke-dasharray: 5 5;

```

