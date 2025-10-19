## 🚗 Bengkel FatchurR — Version Timeline

```mermaid
flowchart TD
    A["v1.0 Alpha<br>🗓️ 2024-05-10<br>🛠️ Initial release of Bengkel system (auth, booking)"]:::alpha --> 
    B["v1.1 Beta<br>🗓️ 2024-06-12<br>✨ UI improvement & bug fix"]:::beta --> 
    C["v2.0 Stable<br>🗓️ 2024-08-01<br>⚙️ Full CRUD + invoice system"]:::stable --> 
    D["v3.0 Major Update<br>🗓️ 2024-09-20<br>📦 Added dashboard analytics & AJAX booking"]:::major --> 
    E["v4.0 Feature Expansion<br>🗓️ 2024-10-10<br>💬 Email Invoice, Notification system"]:::beta --> 
    F["v5.0 Final Release<br>🗓️ 2024-12-01<br>🚀 Realtime update + optimized mobile view"]:::release

    click A "https://github.com/FatchurR/BengkelFR/releases/tag/v1.0-alpha" "Lihat Patch v1.0"
    click B "https://github.com/FatchurR/BengkelFR/releases/tag/v1.1-beta" "Lihat Patch v1.1"
    click C "https://github.com/FatchurR/BengkelFR/releases/tag/v2.0-stable" "Lihat Patch v2.0"
    click D "https://github.com/FatchurR/BengkelFR/releases/tag/v3.0" "Lihat Patch v3.0"
    click E "https://github.com/FatchurR/BengkelFR/releases/tag/v4.0-feature" "Lihat Patch v4.0"
    click F "https://github.com/FatchurR/BengkelFR/releases/tag/v5.0" "Lihat Patch v5.0"

    classDef alpha fill:#fef3c7,stroke:#f59e0b,stroke-width:2px,color:#111;
    classDef beta fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#111;
    classDef stable fill:#dcfce7,stroke:#22c55e,stroke-width:2px,color:#111;
    classDef major fill:#e9d5ff,stroke:#9333ea,stroke-width:2px,color:#111;
    classDef release fill:#fce7f3,stroke:#ec4899,stroke-width:2px,color:#111;
