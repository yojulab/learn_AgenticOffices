# Agency Topology: Interaction Structure

```mermaid
graph TD
    Client[Client / Market] <--> CD[Creative Director Agent]
    CD <--> Analyst[Trend Analyst Agent]
    CD <--> Designer[Lead Designer Agent]
    Designer <--> Product[Product Producer Agent]
    Product <--> Sales[Global Sales Agent]
    
    subgraph "Internal Production Brain"
    CD
    Analyst
    Designer
    end
    
    subgraph "Execution Layer"
    Product
    Sales
    end
    
    MarketData[(Market/Trend DB)] --- Analyst
    Portfolio[(Agency Portfolio)] --- Designer
```

## 1. External Nodes
- **Market/Client**: The source of demands and trends.
- **Consumer**: The final destination for products.

## 2. Agent Infrastructure
- **Decision Hub (CD)**: Orchestrates the flow and maintains the philosophy.
- **Knowledge Node (Analyst)**: Feeds innovation and data-driven insights.
- **Creative Node (Designer)**: Translates philosophy into visuals.
- **Action Node (Product/Sales)**: Executes the real-world manufacturing and transaction.
