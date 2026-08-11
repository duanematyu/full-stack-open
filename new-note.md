```mermaid
sequenceDiagram
    Actor User
    participant Browser
    participant Server

    User->>Browser: Inputs and submits new note
    Browser->>Server: POST "https://studies.cs.helsinki.fi/exampleapp/new_note"
```
