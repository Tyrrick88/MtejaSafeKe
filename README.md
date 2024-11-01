# MtejaSafeKe

MtejaSafe is a secure escrow service platform built with Django, designed to bring trust to online transactions in the Kenyan marketplace. With a growing number of online stores and sellers on social media platforms like Instagram, MtejaSafe aims to provide a reliable middle ground for buyers and sellers, ensuring both parties' satisfaction and security in each transaction.

## Features

    User Profiles: Buyers and sellers have dedicated profiles with relevant information, including contact details and transaction histories.
    Product Listings: Sellers can list products with descriptions, prices, and availability for buyers to browse.
    Escrow Transactions: Each transaction goes through an escrow process, holding funds until the buyer confirms receipt and satisfaction with the product.
    Payment Integration: Secure payment processing is integrated with M-Pesa for seamless transactions in the Kenyan market.
    Real-Time Notifications: Buyers and sellers receive notifications throughout each transaction's stages, from initiation to completion.

## Tech Stack

    Backend: Django, Django REST Framework
    Database: SQLite (for development) or PostgreSQL
    Payment Gateway: M-Pesa (with potential for Stripe or Flutterwave extensions)
    Deployment: Docker (optional), Nginx, Gunicorn

## Getting Started

Follow the instructions in the README to set up your local development environment, configure your M-Pesa API credentials, and start testing.
Future Enhancements

    Additional Payment Gateways: Support for Stripe and Flutterwave for international users.
    Ratings and Reviews: Allow buyers to rate sellers after a transaction.
    Automated Dispute Resolution: Implement a system to handle transaction disputes.

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.
