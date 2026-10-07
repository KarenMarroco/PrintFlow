```mermaid
sequenceDiagram
    actor Maker as Maker
    participant FrontEnd
    participant BackEnd
    participant BD as Banco de dados

    Maker->>FrontEnd: Informa peso e tempo da peça 3D
    Maker->>FrontEnd: Clica em "Calcular e Criar Pedido"
    FrontEnd->>BackEnd: Envia dados do orçamento (JSON)
    BackEnd->>BD: Busca preço do filamento e potência da impressora
    BD-->>BackEnd: Retorna os dados e custos base
    BackEnd->>BackEnd: Executa algoritmo da Calculadora de Custos
    BackEnd->>BD: Cria o novo pedido e item no banco
    BD->>BD: Dá baixa automática no estoque de filamento
    BD-->>BackEnd: Confirma salvamento e atualização
    BackEnd-->>FrontEnd: Retorna custos detalhados e ID do pedido
    FrontEnd-->>Maker: Exibe preço sugerido e sucesso na criação
