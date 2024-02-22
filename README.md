## This file contains information about
### Admin login information 👉  /signIn 1x 
**OutPut**
<br/>
```
[
  {
    "id": "..",
    "name": "..",
    "pass": "..",
    "email": "..."
  }
]
```
### Product reviews 👉  /feedback 6x 
**OutPut**
```
[
  {
    "id": ..,
    "date": "...",
    "idProduct": "..",
    "img":"..",
    "user": "...",
    "comment": "...",
    "idUser": ".."
  },...
]
```
### Information about the project team 👉  /team 4x 
**OutPut**
```
[
  {
    "id": "...",
    "name": "..",
    "jopTitle": "...",
    "age": "..",
    "img": "..."
  },...
]
```
### Product categories 👉  /categories 4x 
**OutPut**
```
[
  {
    "id": "...",
    "categorie": "..."
  },...
]
```
### Brands 👉  /Brands 6x 
**OutPut**
```
[
  {
    "id": "..",
    "img":"...",
  },..
]
```
### Trending products 👉  /trandingProducts 6x 
**OutPut**
```
[
  {
    "id": "..",
    "title": "...",
    "price": "...",
    "qty": "...",
    "categorie": "...",
    "color": [
      {
        "color": "...",
        "img":"...",
      },
      {
        "color": "...",
        "img":"...",
      }
    ],
"img":"..."
  },...
]
```
### Trending products this week 👉  /TrendingThisWeek 10x 
**OutPut**
```
[
  {
    "id": "..",
    "title": "...",
    "price": "...",
    "qty": "...",
    "categorie": "...",
    "color": [
      {
        "color": "...",
        "img":"...",
      },
      {
        "color": "...",
        "img":"...",
      }
    ],
"img":"..."
  },...
]
```
### Blogs 👉  /Blogs 5x 
**OutPut**
```
[
  {
    "id": "...",
    "title": "...",
    "value":"...",
    "date": "...",
    "description": "...",
    "img":"...",
  },...
]
```
### Products 👉  /Products 28x 
**OutPut**
```
[
  {
    "id": "..",
    "title": "...",
    "price": "...",
    "qty": "...",
    "categorie": "...",
    "color": [
      {
        "color": "...",
        "img":"...",
      },
      {
        "color": "...",
        "img":"...",
      }
    ],
"img":"..."
  },...
]
```
### Mail 👉  /mail 4x 
**OutPut**
```
[
  {
    "id": "...",
    "date": "...",
    "email": "...",
    "phone": "...",
    "comment": "...",
    "name": "...",
    "idUser": "..."
  },...
]
```
### Orders 👉  /orders 10x 
**OutPut**
```
[
  {
    "id": "...",
    "Customer": "...",
    "Email": "...",
    "Phone": "...",
    "item": "...",
    "price": "...",
    "date": "...",
    "status": "...",
    "payment": "..."
  },
]
```
### Sales Statistics 👉 /barChart 4x
**OutPut**
```
 {
    "country": "...",
    "Order": ...,
    "Order Color": "...",
    "Pending": "...",
    "Pending Color": "...",
    "Cancelled": "...",
    " Cancelled Color": "...",
    " Delivered": ...,
    " Delivered Color": "..."
  },
]
```
### Sales By Category 👉 /pieChart 4x
**OutPut**
```
[
  {
    "id": "...",
    "label": "...",
    "value": ...,
    "color": "..."
  },...
]
```
### Order Activity 👉 /orderActivity 7x 
**OutPut**
```
[
  {
    "id": "...",
    "activity": "...",
    "state": "...",
    "date": "..."
  },
]
```
### Top users 👉 /users 6x 
**OutPut**
```
[
  {
    "id": ...,
    "Name": "...",
    "phone": "...",
    "email": "...",
    "country": "...",
    "TotalBuy": "..."
  },...
]
