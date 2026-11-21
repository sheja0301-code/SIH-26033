# Smart India Hackathon Workshop
# Date:21/11/2026
## Reference Number:26016939
## Name: SHEJASHRI L J

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
1. Detailed Explanation of the Proposed Solution

HarvestLink is an AI-powered digital marketplace designed to connect farmers and Farmer Producer Organizations (FPOs) directly with consumers, retailers and bulk buyers.

The platform allows farmers to upload their available agricultural products, quantities, locations and expected prices. Buyers can search for products and place orders directly through the platform.

Its main feature is Smart Grouped Logistics, which combines suitable orders from nearby farmers into shared deliveries. This helps reduce individual transportation expenses and makes agricultural product distribution more efficient.

The platform also uses AI-based demand forecasting to predict the demand for agricultural products and route optimization to identify efficient collection and delivery routes.

2. How It Addresses the Problem

Multiple Intermediaries: Directly connects farmers with consumers and bulk buyers, reducing dependency on unnecessary middlemen.

Low Farmer Earnings: Provides better access to buyers and transparent price information.

High Consumer Prices: Reduces unnecessary supply-chain and transportation costs.

Transportation Problems: Groups orders from nearby farmers to support shared deliveries.

Uncertain Market Demand: Uses AI-based demand forecasting to help farmers plan their production and sales.

Inefficient Delivery: Uses route optimization to suggest efficient transportation routes.

3. Innovation and Uniqueness of the Solution

HarvestLink focuses on combining direct agricultural trading with intelligent transportation management.

Its key innovative features include:

Smart Order Aggregation: Combines agricultural products from multiple nearby farmers to fulfil bulk buyer requirements.

AI-Based Demand Forecasting: Analyses historical sales and market information to predict future product demand.

Smart Route Optimization: Identifies efficient collection and delivery routes to reduce transportation expenses.

Transparent Pricing: Displays product prices and delivery charges to help farmers and buyers make informed decisions.

Direct Market Access: Helps small and marginal farmers reach consumers, retailers and bulk buyers without depending on multiple intermediaries.

<img width="955" height="478" alt="image" src="https://github.com/user-attachments/assets/21b282ac-e147-44cc-b33a-520d9521b5fa" />


## Technical Approach. Technologies to Be Used

Frontend:

HTML – To create the structure of the website.

CSS – To design an attractive and user-friendly interface.

JavaScript – To provide interactive features.

Backend:

Python – For application logic and AI development.

Django – To manage users, products, orders and platform operations.

Database:

SQLite / PostgreSQL – To store farmer details, buyer information, product details and order records.

Artificial Intelligence and Machine Learning:

Python and Scikit-learn – For AI-based agricultural demand forecasting.

Pandas and NumPy – For processing and analysing agricultural market data.

Logistics and Route Optimization:

Google Maps API / OpenStreetMap – For location and mapping services.

Google OR-Tools – For optimizing product collection and delivery routes.

2. Methodology and Process for Implementation

Step 1: Farmer Registration
Farmers and FPOs register on the platform and provide their basic details and location.

Step 2: Product Listing
Farmers upload their available agricultural products, quantities and expected prices.

Step 3: Buyer Connection
Consumers, retailers and bulk buyers search for products and place orders directly.

Step 4: Smart Order Matching
The system matches buyer requirements with suitable products available from nearby farmers.

Step 5: Smart Order Aggregation
The platform combines compatible orders from multiple nearby farmers to support shared transportation.

Step 6: AI-Based Demand Forecasting
AI analyses historical sales and available market data to predict agricultural product demand.

Step 7: Route Optimization
The logistics module identifies suitable collection points and efficient delivery routes.

Step 8: Order Confirmation and Tracking
Orders are confirmed, and farmers and buyers can monitor delivery and payment status.

3. Technical Architecture Diagram

The following flowchart explains how HarvestLink connects farmers, buyers, AI forecasting and logistics management.

flowchart TD
    A[Farmers / FPOs] --> B[HarvestLink Platform]
    C[Consumers / Bulk Buyers] --> B

    B --> D[Product and Order Management]
    D --> E[Smart Farmer-Buyer Matching]

    E --> F[Smart Order Aggregation]

    F --> G[AI Demand Forecasting]
    F --> H[Logistics Management]

    G --> I[Demand Predictions]
    H --> J[Route Optimization]

    I --> K[Order Planning]
    J --> K

    K --> L[Order Confirmation]
    L --> M[Shared Delivery]
    M --> N[Order Tracking]

4. Expected Technical Outcome

The proposed system will provide a digital marketplace with direct farmer-to-buyer connections, AI-based demand forecasting and smart logistics support. It aims to reduce unnecessary intermediaries, optimize transportation and improve the efficiency of agricultural product distribution.
## Feasibility and Viability
1. Technical Feasibility

HarvestLink can be developed using commonly available web development technologies and AI tools.

Python and Django can be used to develop the digital marketplace.

HTML, CSS and JavaScript can create a user-friendly interface.

SQLite or PostgreSQL can store farmer, buyer, product and order details.

Machine learning techniques can support agricultural demand forecasting.

Mapping and route optimization tools can help plan efficient product collection and delivery.

The platform can initially be developed as a web application and expanded into a mobile application in the future.

2. Economic Feasibility

Uses open-source technologies to reduce development costs.

Helps farmers reduce individual transportation expenses through grouped deliveries.

Provides direct market access without depending on multiple intermediaries.

Can support small and marginal farmers through affordable digital services.

Can generate revenue through transparent platform service fees or optional logistics charges.

3. Long-Term Viability

HarvestLink aims to build a sustainable agricultural marketplace by improving connections between farmers and buyers. Its combination of direct trading, smart order aggregation, demand forecasting and logistics optimization can support long-term agricultural supply-chain development.

## Impact and Benefits
1. Potential Impact on the Target Audience

Farmers and FPOs:

Provides direct access to consumers, retailers and bulk buyers.

Creates better opportunities to earn through transparent pricing.

Helps small farmers sell their products through grouped orders.

Provides demand predictions to support better production and selling decisions.

Consumers and Bulk Buyers:

Provides access to agricultural products directly from farmers.

Helps reduce unnecessary supply-chain costs.

Offers transparent product prices and delivery charges.

Improves product availability through better order coordination.

Delivery Partners:

Provides organized collection and delivery schedules.

Helps reduce repeated transportation through grouped deliveries.

Creates opportunities for local transportation services.

2. Benefits of the Solution

Social Benefits:

Supports small and marginal farmers.

Improves connections between rural farmers and urban consumers.

Encourages digital awareness among farming communities.

Promotes fair and transparent agricultural trading.

Economic Benefits:

Improves earning opportunities for farmers.

Helps consumers access products at potentially lower prices.

Reduces transportation expenses through shared deliveries.

Supports local agricultural businesses and delivery partners.

Environmental Benefits:

Reduces unnecessary transportation trips.

Helps lower fuel consumption through efficient route planning.

Supports better demand forecasting to minimize potential food wastage.

Encourages efficient distribution of agricultural products.

3. Overall Expected Impact

HarvestLink aims to create a transparent, efficient and farmer-friendly agricultural supply chain. By combining direct digital trading, AI-based demand forecasting and smart grouped logistics, the platform seeks to improve farmers' earning opportunities, reduce unnecessary costs for consumers and support sustainable agricultural distribution.

## Research and References
e-NAM (https://www.enam.gov.in/) – For digital agricultural trading.

AGMARKNET (https://agmarknet.gov.in/) – For agricultural market prices.

Google OR-Tools (https://developers.google.com/optimization) – For route and logistics optimization.

Scikit-learn (https://scikit-learn.org/) – For AI-based demand forecasting.k
