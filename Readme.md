```mermaid
flowchart TD;
    1[Create Contract]--> 2[Try to again create contract should return duplicate email Error];
    2[Get Contract by End Customer ID]-->5;
    4[Get Contracts By EndCustomerId With No Contracts]-->5;
    5-->6;
