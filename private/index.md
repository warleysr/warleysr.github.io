# Private projects

The main private project that I'm working with is called **VikingsToolbox** and consists of a system composed of:

### 📱Android app
A paid app that has the main functionality of changing some files in user games folders for better performance. It has integration with [Shizuku](https://shizuku.rikka.app/) to get access to **Android/data** folder and the user can buy his access automatically through the app with integration for payments with PIX (brazilian payment method) and credit cards using Stripe.

**Built with:** Kotlin, Jetpack Compose, Ktor, coil, Accompanist Pager

- Demonstration video: [https://drive.google.com/file/d/1VI8YZhu7yJeOJCC2lQzrA8SWv4E8W4Tr/view](https://drive.google.com/file/d/1VI8YZhu7yJeOJCC2lQzrA8SWv4E8W4Tr/view)
- Download page: [https://blackgroup.com.br/tb](https://blackgroup.com.br/tb)

### 🌐 Backend
The backend manages the users, serve the zip files to the client and integrates with all necessary APIs and to the WhatsApp BOT. I developed automatic payments integrations with [MercadoPago](https://mercadopago.com.br), [Efí](https://sejaefi.com.br) and [Stripe](https://stripe.com). Also created a re-seller system where interested individuals can register to sell our product under coupons and earn commission.

**Built with:** Python, Flask, Flask-Login, SQLAlchemy, requests, MySQL

### 🤖 WhatsApp BOT
This BOT is used to send notification to users with his access information on success payments and also when a payment is not completed to ask if he had any problem during the proccess. For admins it offers a lot of commands to control users and payments. Also used for automating marketing messages in WhatsApp groups.

**Built with:** NodeJS, express, whatsapp-web.js

I'm the creator and only maintainer of all these projects.
