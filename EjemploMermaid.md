  ```mermaid
stateDiagram-v2
    [*] --> Error
    Error --> Desistir: "Huir"
    Error --> Google: "Buscar en Google"
    Google --> Desistir: "Paso!"
    Google --> StackOverFlow: "Buscar en StackOverFlow"
    StackOverFlow --> ChatGPT: "Buscar en ChatGPT"
    StackOverFlow --> Desistir: "No puedo más"
    ChatGPT --> Desistir: "Apagar el ordenador"
    ChatGPT --> Abandonar: "Esto de programar no es lo mío"
    
  ```
