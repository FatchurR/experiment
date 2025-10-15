```mermaid
flowchart TD
    A[Start] --> B{Apakah data valid?}
    B -->|Ya| C[Proses Data]
    B -->|Tidak| D[Perbaiki Data]
    C --> E[Finish]
