# Latte Lounge - Basic Express Routing Using GET

## Run
    npm install
    npm start

Open http://localhost:3000

## Routes
| Route | Response |
|---|---|
| GET / | public/index.html |
| GET /menu | public/menu.html |
| GET /about | public/about.html |
| GET /contact | public/contact.html |
| GET /api/menu | all products (JSON) |
| GET /api/menu?category=pastry | filtered by query string |
| GET /api/menu/:id | one product by route param, 404 JSON if missing |

Each page visit logs `Rendering <file>` in the terminal.

Photos: Unsplash / Pexels