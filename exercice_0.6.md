```mermaid

    Note right of browser: When the button on the form is clicked

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: HTTP status code 201
    deactivate server
    
    Note right of browser: data is sent with an the previous HTTP POST request and the data type is JSON
    Note right of browser: and the new note is added to the page by the javascript code

```
