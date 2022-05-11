# Burning Process

At the end of the pool, the Burns collector contains a
certain amount of tokens that will be deducted from the
total supply and discarded forever.

Since the idea of the project is to produce value, we believe
that this autonomous burning process is the greatest way to
maintain a good market impact and to prevent token
deflation.

Even though the risk of losing value is likely common in the
cryptocurrency world, our algorithms along with a process
mainly controlled by holders will help prevent or at least
minimize those risks.


```mermaid
flowchart TD
%% Nodes
    A((Start))
    B(Transfer tokens in Burns Collector<br>to easter address)
    C(Update total tokens supply)
    D((End))

%% Node links
    A --> B --> |Burnt tokens are discarded<br>forever| C --> D

%% Defining the styles
    classDef startStopNode fill:black,stroke-width:1px,stroke:#efefef,color:white
    classDef yellowStep fill:#ffc542,stroke:#ffce42,color:black

%% Assigning styles to nodes
    class A,D startStopNode;
    class C yellowStep;
```

--8<-- "includes/abbreviations.md"