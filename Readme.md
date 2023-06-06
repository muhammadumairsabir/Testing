```mermaid
flowchart TD;
    1[Create Contract]--> 2[Try to again create contract should return duplicate email Error];
    2-->3[Get Contract by End Customer ID];
    2-->4[Get Contracts By EndCustomerId With No Contracts];
    4-->5;
