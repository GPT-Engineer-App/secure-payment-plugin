# secure-payment-plugin

This project involves creating a secure third-party payment plugin for WooCommerce. The plugin allows users to send their shopping cart to a third-party payment processor without sharing the delivery address. It includes functionalities such as CSRF protection using a nonce field, secure data encryption and decryption for storing delivery addresses, and secure API communication with the third-party processor. Key features include:

- Addition of custom nonce field to checkout form for CSRF protection
- Processing of third-party payments with error handling and user notifications
- Secure transmission of cart details to the third-party payment processor
- Encryption of delivery addresses before storing in the database
- Comprehensive error logging and user notification system

Technologies and tools used: PHP, WooCommerce hooks and filters, OpenSSL for encryption, WordPress functions for HTTP requests and nonce verification.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/secure-payment-plugin.git
cd secure-payment-plugin
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
