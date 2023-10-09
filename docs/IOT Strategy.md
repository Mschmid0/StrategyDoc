# IOT Strategy
```mermaid
graph LR
  Connect[Connect]
  Collect[Collect]
  Store[Store]
  Visualize[Visualize]
  Analyze[Analyze]
  Act[Act]

  Connect --> Collect
  Collect --> Store
  Store --> Visualize
  Visualize --> Analyze
  Analyze --> Act
```
## Connect
Identify the machinery and equipment that need to be connected, including production equipment, 3D printers, and post-processing equipment. Determine the necessary connectivity requirements and security protocols for each data source.

## Collect
Collect valuable data from the three major data sources: material production data, machine sensor data during 3D printing, and data from cleaning and thermal post-processing and sintering. Define the data collection process for each data source.

## Store
Determine where to store the data from the three major data sources, considering capacity, scalability, and data access requirements for each data source.

## Visualize
Create visualizations, such as dashboards and graphs, that provide insights into the data from the three major data sources.

## Analyze
Use data mining, machine learning, or predictive analytics to gain insights and identify opportunities for optimization for each of the three major data sources.

## Act
Take action based on the insights gained from data analysis for each of the three major data sources, such as optimizing production processes, improving product quality, or reducing downtime. Define the actions to be taken and expected outcomes for each data source.

!!! info  "Lorem ipsum" 
	[](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-2)[](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-3)Lorem ipsum dolor sit amet, consectetur [](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-4)adipiscing elit. Nulla et euismod nulla. [](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-5)Curabitur feugiat, tortor non consequat [](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-6)finibus, justo purus auctor massa, nec [](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#__codelineno-9-7)semper lorem quam in massa.


---
```mermaid
graph TD
    subgraph Connect
        A[Identify Machinery & Equipment]
        B[Determine Connectivity Requirements]
    end

    subgraph Collect
        C[Collect Material Production Data]
        D[Collect Machine Sensor Data]
        E[Collect Post-Processing Data]
        F[Define Data Collection Process]
    end

    subgraph Store
        G[Determine Storage Location]
        H[Consider Capacity, Scalability, and Access]
    end

    subgraph Visualize
        I[Create Dashboards & Graphs]
        J[Provide Insights]
    end

    subgraph Analyze
        K[Use Data Mining, ML, or Predictive Analytics]
        L[Gain Insights and Identify Opportunities]
    end

    subgraph Act
        M[Take Action Based on Insights]
        N[Optimize Production Processes, Improve Quality, Reduce Downtime]
        O[Define Actions and Expected Outcomes]
    end

    A --> B
    B --> C
    B --> D
    B --> E
    D --> F
    C --> F
    E --> F
    F --> G
    G --> H
    F --> I
    I --> J
    J --> K
    K --> L
    L --> M
    M --> N
    N --> O
```
