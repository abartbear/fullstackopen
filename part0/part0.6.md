# part0.6

New note in Single page app diagram


```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: JavaScript file
    deactivate server

    Note right of browser: no redirect - no refresh of whole page
```