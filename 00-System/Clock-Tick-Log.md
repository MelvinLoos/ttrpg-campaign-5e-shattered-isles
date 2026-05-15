# Clock Tick Log

This is a persistent, append-only ledger for faction clock ticks. Each row represents a specific change (delta) to a clock's progress during or after a session. When reporting a session's impact, the GM should sum the Net column for each clock to determine its current state.

| Session | Date | Clock | Δ Segments | Direction | Trigger | Net (running) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 2024-05-01 | — | 0 | — | No clock ticks this session | — |
