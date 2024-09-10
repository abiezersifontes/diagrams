In the next diagram we can see the main components of the Dev Assistant App
```mermaid
graph TD;
    subgraph Dev Assistant
        A[Frontend] --> B[Backend];
        B[Backend] --> C[(DB)];
    end
    A[Frontend] --> D[Authentication and Authorization Provider]
    D[Authentication and Authorization Provider] --> A[Frontend]
    B[Backend] --> E[AI Model];
    B[Backend] --> F[Cloud Provider];
    B[Backend] --> G[Project Management Tool];
```