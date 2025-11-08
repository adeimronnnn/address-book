# Address Boook

A simple address book application to store and manage contact information.

## Link

- URL Deployment :
- Repopsitory :

## Features

- Add, edit, and delete contact
- Search contacts by name or email

## Tech Stack 

- HTML
- CSS
- JavaScript

## Flowchart

```mermaid 
flowchart TD
        A[Start] --> B[Display Contact List]
        B --> C{User Action}
        C -->|Add Contact| D[Show Add Contact Form]
        C -->|Edit Contact| E[Show Add Contact Form]
        C -->|Detele Contact| F[Confirm Deletio]
        D --> G[Save New Contact] 
        E --> H[Update Contact]
        F --> I[Remove Contact]
        G --> B
        H --> B
        I --> B
        B --> J[End]
```