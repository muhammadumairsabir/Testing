```mermaid
flowchart TD;
    1[Create Contract]--> 2{Try to again create contract should return duplicate email Error};
    2-->3;
    2-->3;
    3-->4;
