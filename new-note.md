sequenceDiagram
    participant User
    participant Browser
    participant Server

    User->>Browser: Inputs and submits new note
    Browser->>Server: POST "new note 
