```mermaid
sequenceDiagram
    participant user
    participant browser
    participant server
    
    user->>browser: inputs and submit new note
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    ```
