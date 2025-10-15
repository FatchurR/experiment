## 🚀 FatchurR Apps Version Flow

```mermaid
flowchart LR
    A[v1.0 Alpha]:::alpha --> B[v1.1 Beta]:::beta --> C[v2.0 Stable]:::release
    C --> D[v3.0 Major Update]:::release
    D --> E[v4.0 Feature Expansion]:::beta
    E --> F[v5.0 Final Release 🚀]:::release

    click A "https://github.com/FatchurR/yourrepo/releases/tag/v1.0-alpha" "Lihat Patch v1.0 Alpha"
    click B "https://github.com/FatchurR/yourrepo/releases/tag/v1.1-beta" "Lihat Patch v1.1 Beta"
    click C "https://github.com/FatchurR/yourrepo/releases/tag/v2.0-stable" "Lihat Patch v2.0"
    click D "https://github.com/FatchurR/yourrepo/releases/tag/v3.0" "Lihat Patch v3.0"
    click E "https://github.com/FatchurR/yourrepo/releases/tag/v4.0-feature" "Lihat Patch v4.0"
    click F "https://github.com/FatchurR/yourrepo/releases/tag/v5.0" "Lihat Patch v5.0"

    classDef alpha fill:#ffe6cc,stroke:#ff9900,stroke-width:2px;
    classDef beta fill:#ccf0ff,stroke:#0099ff,stroke-width:2px;
    classDef release fill:#ccffcc,stroke:#33cc33,stroke-width:2px;
