## FarmFolio

FarmFolio is a portal designed to help farmers sell their produce at better rates by connecting them with buyers across India. The system provides a simple interface that works on mobile and SMS to upload produce details and respond via phone and SMS, bridging the digital divide.

## Problem Statement

**Portal for Farmers to Sell Produce at Better Rates:**

- **Objective:** To create a system that provides farmers an interface to sell their produce and connect with buyers across India.
- **Solution:** A simple interface that works on mobile and SMS for uploading produce details and responding via phone and SMS.
- **Features:**
  - Allows anyone to buy produce/vegetables by initially visiting the place or using an integrated courier service for delivery.
  - Farmers can get better prices for their produce without additional costs for marketing and delivery of goods, though they can choose to charge more by delivering the items themselves.

## Purpose and Beneficiaries

### Benefits to Different Stakeholders:
- **Farmers:** Get better rates for their vegetables and can make additional income with pride.
- **Restaurant Owners, Buyers:** Access to fresh produce directly from farms.
- **Courier Companies, Delivery Agencies, Vegetable Vendors:** Increased business opportunities.

### National Benefits:
- Better rates for vegetables.
- Improved livelihoods for farmers.

### Challenges:
- Brokers and government rules.
- Overall profitability for the buyer to purchase directly from the farm, excluding transportation costs.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP

## Project Structure

The project consists of separate portals for farmers and buyers:

- **Farmer Portal:** Allows farmers to upload produce details, manage listings, and interact with buyers.
- **Buyer Portal:** Allows buyers to browse produce listings, contact farmers, and arrange purchases or deliveries.

## Setup Instructions

### Prerequisites

- XAMPP or any other PHP development environment
- Web browser

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yashlondhe90960/FarmFolio
   ```
2. **Start XAMPP:**

- **Open XAMPP Control Panel and start Apache and MySQL.**

## Import the Database

1. **Open phpMyAdmin**: [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
2. **Create a new database named `FarmFolio`.**
3. **Import the SQL file located in the repository (`database/farmfolio.sql`).**

## Configure the Project

1. **Move the project files to the XAMPP `htdocs` directory.**
2. **Update the database configuration in the project files (`config.php`) with your database credentials.**

## Run the Project

1. **Open your web browser and navigate to** [http://localhost/farmfolio](http://localhost/farmfolio).

## Usage

### Farmer Portal

- **Register/Login**: Farmers can register or log in to their accounts.
- **Upload Produce**: Farmers can upload details of their produce, including images, quantity, and price.
- **Manage Listings**: Farmers can view and manage their current listings.
- **Interact with Buyers**: Farmers can respond to inquiries from buyers via SMS or phone.

### Buyer Portal

- **Browse Produce**: Buyers can browse the available produce listings.
- **Contact Farmers**: Buyers can contact farmers directly to arrange purchases.
- **Arrange Deliveries**: Buyers can opt for courier services to have the produce delivered.

## Contributing

We welcome contributions to improve FarmFolio. If you have any suggestions or find any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors and participants in the hackathon.


