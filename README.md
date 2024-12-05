## The Course Project

### Public and Private Pages

Public "marketing" pages & Private "app" pages

### Table:

| Public/Private | Route | Description |
| --- | --- | --- |
| Public | / | Home page |
| Public | /pricing | Pricing info |
| Public | /auth | User authentication |
| Protected | /expenses | List of expenses |
| Protected | /expenses/raw | Raw data of expenses |
| Protected | /expenses/add | Add a new expense |
| Protected | /expenses/edit/:id | Edit an expense |
| Protected | /expenses/analysis | Analysis of expenses |


### Comencem!

Per crear un nou projecte de Remix, utilitza la comanda `npx create-remix@latest`. Això, com sempre, et demanarà algunes qüestions com el nom de la carpeta de projecte, si ho necessites.


Per començar, intenta generar l'estructura d'arxius, preferiblement amb el format de nom d'arxiu (notació amb punts), ja que és la que he fet servir i l'opció "moderna" de Remix. 

app/
├── routes/
│   ├── _index.tsx                   // Ruta "/"
│   ├── pricing.tsx                  // Ruta "/pricing"
│   ├── auth.tsx                     // Ruta "/auth"
│   ├── expenses._index.tsx          // Ruta "/expenses"
│   ├── expenses.raw.tsx             // Ruta "/expenses/raw"
│   ├── expenses.add.tsx             // Ruta "/expenses/add"
│   ├── expenses.edit.$id.tsx        // Ruta "/expenses/edit/:id"
│   ├── expenses.analysis.tsx        // Ruta "/expenses/analysis"