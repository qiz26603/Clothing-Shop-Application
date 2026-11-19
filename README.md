Android Studio Ladybug Feature Drop | 2024.2.2 Patch 2
# P2q Store: Clothes Store Android App

An Android shopping app for a clothing store. Customers can browse products, view details, add items to a cart, and place an order. The app also includes functions for managing products (add, edit, delete) and a page with information about the shop.

This was a university team project (March 2025). I was the **team leader**, designed the UI in Figma, and developed the app in Java.

## Screenshots

| Home | Product detail | Cart | Order |
|------|----------------|------|-------|
| ![Home]<img width="407" height="850" alt="image" src="https://github.com/user-attachments/assets/3b57ea37-5a45-42c9-a21c-6a37143df0a8" />
| ![Detail] <img width="235" height="511" alt="image" src="https://github.com/user-attachments/assets/531ef6cc-fa60-4184-938e-14329eb1d6b9" />
 | ![Cart] <img width="240" height="510" alt="image" src="https://github.com/user-attachments/assets/b2f08003-9d0b-4e43-9365-9fae097c206c" />
| ![Order]<img width="237" height="507" alt="image" src="https://github.com/user-attachments/assets/74dda3ba-840f-4baa-b9bc-3bb3ddb8fbc9" />
|


System block diagram:

![System block diagram]
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/8ddd8378-c234-4a2a-8669-3e276857ab48" />


## Features

- **Home screen:** welcome banner, search bar, promotion banner, categories (Coats, Pants, All products), and a list of popular products.
- **Product list and detail:** browse all products and open a detail page for each item.
- **Cart:** add items from the detail page. If the cart is empty, the app shows an "empty cart" message.
- **Order:** fill in the required information and place an order. The app confirms when the order is successful.
- **Product management:** add new products, edit product information, and delete products.
- **About us:** detailed information about the shop.
- **Local database:** product data and cart data are stored in SQL.

## How it works

The app follows the flow in the system block diagram:

1. **Home** is the main screen. From here the user goes to **Cart**, **Product**, or **About us**.
2. **Product** shows all products from the product database. Tapping one opens the **Detail** screen.
3. On **Detail**, the user can click *Add to Cart* (saves to the cart database) or *Buy Now* (goes to the cart).
4. **Cart** reads from the cart database. With products, the user continues to **Order**. With no products, the app prints "The cart is empty".
5. **Order** asks for the required information and confirms the order.

## Tech stack

- **Language:** Java (part of the code was later migrated to Kotlin by a teammate)
- **Platform:** Android, built with Android Studio
- **Database:** SQL (product and cart data)
- **UI/UX design:** Figma

## My role

- Led the team: planned tasks and coordinated development.
- Designed the full UI/UX in Figma.
- Developed the app in Java.
- Worked on the database for products and cart.

## Team

- Nguyen Hoang Quyet: team leader, UI/UX design, development, collect data, built project flow
- Nguyen Trong Phuc: team member, database, backend developer
- Nguyen Hoang Phuc: team member, front-end developer.

## Notes

This is a learning project. The product data is sample data and is not connected to a real store.
