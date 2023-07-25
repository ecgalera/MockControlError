# MockControlError

Agregamos Mocks y Control de Errores

1- Mocks: 

Podemos generar mocks de productos en: 

Get localhost:3000/api/mock       // utilizamos Postman

Ej: 
{
            "title": "Práctico Hormigon Toallas",
            "description": "Ergonomic executive chair upholstered in bonded black leather and PVC padded seat and back for all-day comfort and support",
            "departament": "Hogar",
            "stock": 3,
            "id": "a23ba6af99f643df0acdd5cc",
            "code": "1PIoBWWPe7",
            "price": 2993
        }

Podemos generar mocks de usuarios en: 

Get localhost:3000/api/users/mock       // utilizamos Postman

Ej: 

     {
            "firstName": "Miguel Ángel",
            "lastName": "Armijo Olivera",
            "email": "Pilar_MontanoCorrales@hotmail.com",
            "password": "SifQijLFvFFDqhN",
            "sex": "male",
            "birthDate": "1964-04-09T04:56:44.059Z",
            "id": "eaab10cdc0ca3eaff9cbd03f",
            "image": "https://cloudflare-ipfs.com/ipfs/Qmd3W5DuhgHirLHGVixi6V76LhCkZUz6pnFt5AJBiyvHye/avatar/278.jpg",
            "phone": "913 589 366",
            "products": [
                {
                    "title": "Sabroso Granito Queso",
                    "description": "The Apollotech B340 is an affordable wireless mouse with reliable connectivity, 12 months battery life and modern design",
                    "departament": "Bricolaje",
                    "stock": 13,
                    "id": "52a0dcd82ef70f2aa5bfeabe",
                    "code": "tCTZRbS08q",
                    "price": 1651
                },
                {
                    "title": "Sorprendente Algodón Pescado",
                    "description": "The Apollotech B340 is an affordable wireless mouse with reliable connectivity, 12 months battery life and modern design",
                    "departament": "Salud",
                    "stock": 18,
                    "id": "c1dea8ecf8c33159d6053605",
                    "code": "vJLG3T1OYp",
                    "price": 3395
                },
                {
                    "title": "Práctico Algodón Teclado",
                    "description": "New ABC 13 9370, 13.3, 5th Gen CoreA5-8250U, 8GB RAM, 256GB SSD, power UHD Graphics, OS 10 Home, OS Office A & J 2016",
                    "departament": "Videojuegos",
                    "stock": 3,
                    "id": "c1eed4418f08ddbdefbb53c9",
                    "code": "S2laJVdhXb",
                    "price": 4184
                }
            ],
            "role": "admin",
            "premiun": false
        },

2- Control de Errores: 
   Control de Errores para datos incompletos en products:

   Post localhost:300/api/product      // utilizamos Postman 
   utilizamos los siguientes insumos para generar el error: 

   {
    "title": "Pepsci Cola",
    "description": "gaseosa cola",
    "price": 569,
    "category":"bebidas",
    "status": true,
    "stock": 5 

}



    
