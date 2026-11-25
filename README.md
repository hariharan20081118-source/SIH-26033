# Smart India Hackathon Workshop
# Date:25/11/2026
## Reference Number:26014249
## Name:S.Hariharan

# Problem Title
### SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
### Ministry of Consumer Affairs, Food & Public Distribution

# Theme
Agriculture, FoodTech & Rural Development

# Problem Description
### Expected Solution: Create a digital marketplace that:

### • Connects farmers/FPOs directly with consumers and bulk buyers.
### • Provides logistics support.
### • Uses AI for demand forecasting and route optimization.

# Benefits:

### • Better prices for farmers.
### • Lower prices for consumers.
### • Reduced supply chain inefficiencies.

# Proposed Solution
### We propose Farm Connect, an AI-powered digital marketplace that directly connects farmers, Farmer Producer Organizations (FPOs), consumers, retailers, restaurants and bulk buyers.

### The platform eliminates unnecessary intermediaries by allowing farmers to list their agricultural products directly on the marketplace.

### Key Features

### Direct Farmer-to-Consumer Marketplace: Farmers can upload their products, quantities, prices and availability. Consumers can purchase fresh agricultural products directly.

### FPO Integration: Multiple farmers can combine their agricultural products through FPOs and sell them in bulk to retailers, supermarkets and wholesalers.

### AI-Based Price Recommendation: AI analyzes market demand, historical prices and product availability to suggest fair selling prices to farmers.

### Smart Logistics Management: The platform connects farmers with delivery partners and identifies suitable transportation options.

### Demand Forecasting: AI predicts future demand for agricultural products to help farmers and sellers plan their supply.

### Real-Time Price Comparison: Consumers can compare prices from different farmers and select affordable products.

### Multilingual Support: The platform supports regional languages to make it accessible to rural farmers.

### Innovation and Uniqueness

### Direct communication between farmers and consumers.

### powered price recommendations.

### Smart demand forecasting.

### Optimized delivery routes.

### Transparent pricing without unnecessary intermediaries.

### Digital marketplace accessible through mobile phones.

## Technical Approach
Technologies to Be Used

### Component

### Technology

### Frontend

### HTML, CSS, JavaScript, React.js

### Backend

### Python, Django

### Database

### MySQL

### AI/ML

### Python, Scikit-learn

### Maps and Routes

### OpenStreetMap, OSRM

### API

### Django REST Framework

### Authentication

### Django Authentication

### Deployment

### Cloud Platform

### Implementation Methodology

### Step 1: User Registration

### Farmers, consumers, FPOs and bulk buyers register and log in to the platform.

### Step 2: Product Listing

### Farmers upload agricultural products with:

### Product name

### Available quantity

### Expected price

### Location

### Harvest date

### Product images

### Step 3: AI Price Prediction

### The AI model analyzes historical market prices, demand and availability to recommend suitable selling prices.

### Step 4: Product Discovery

### Consumers and bulk buyers search for agricultural products and compare prices from different farmers.

### Step 5: Order Management

### Consumers place orders directly with farmers or FPOs. Farmers receive order notifications and confirm availability.

### Step 6: Logistics Management

### The system identifies nearby delivery partners and suggests efficient delivery routes based on distance and delivery requirements.

### Step 7: Demand Forecasting

### The AI model predicts future demand using historical sales, seasonal patterns and market trends.

### System Workflow

### Farmer Registration → Product Upload → AI Price Recommendation → Product Listing → Consumer/Buyer Order → Order Confirmation → Logistics Assignment → Delivery → Payment Confirmation.
```Proposed System Architecture

       FARMERS / FPOs
              |
              v
       FARM CONNECT APP
              |
              v
       DJANGO BACKEND
              |
       +------+------+
       |      |      |
       v      v      v
    Product  Order  User
    Module   Module Module
       |      |      |
       +------+------+
              |
              v
          AI ENGINE
              |
       +------+------+
       |             |
       v             v
  Price Prediction  Demand
                    Forecasting
              |
              v
       LOGISTICS MODULE
              |
              v
       DELIVERY PARTNERS
              |
              v
          CONSUMERS
```
### Working Prototype

### The initial prototype will contain:

### Farmer registration and login page.

### Farmer product upload dashboard.

### Consumer product browsing page.

### Product search and price comparison.

### AI-based price recommendation.

### Order placement and tracking.

### Delivery route suggestion.

### Admin dashboard.

## Feasibility and Viability
### Feasibility of the Idea

### The proposed system is technically and economically feasible because it uses existing web development technologies, open-source tools and machine learning libraries.

### Farmers can access the platform through smartphones.

### FPOs can aggregate products from multiple farmers.

### Consumers can purchase products online.

### AI models can analyze available market and sales data.

### Logistics providers can support transportation and delivery.

### Potential Challenges and Risks

### Challenges

### Solutions

### Lack of digital knowledge among farmers

### Simple interface and regional language support

### Internet connectivity issues

### Lightweight mobile-friendly application

### Product quality differences

### Product grading and quality verification

### Transportation difficulties

### Multiple logistics partner integration

### Price fluctuations

### Regular market data updates

### Trust and payment issues

### Verified users and secure payment integration

### Strategies for Overcoming Challenges

### Provide farmer training and easy onboarding.

### Work with local FPOs and agricultural organizations.

### Introduce transparent pricing and product verification.

### Use reliable logistics partners.

### Regularly update AI models with new market data.

### Implement secure authentication and payment verification.

### Viability

### The platform can generate revenue through a small transparent service fee on successful transactions, optional logistics services and institutional buyer subscriptions.

### Basic farmer registration and product listing can remain free to encourage participation.

### The system can initially be implemented in one agricultural region and gradually expanded to other districts and states.

# Impact and Benefits
### Economic Benefits

### Farmers receive a better share of the selling price.

### Consumers can purchase agricultural products at competitive prices.

### Reduces unnecessary intermediary costs.

### Provides additional market opportunities for small farmers.

### Helps FPOs reach institutional buyers.

### Social Benefits

### Improves farmers' digital market access.

### Encourages rural entrepreneurship.
### Supports small and marginal farmers.

### Promotes digital literacy in rural communities.

### Strengthens connections between farmers and consumers.

### Environmental Benefits

###Optimized delivery routes can reduce unnecessary transportation.

### Better demand forecasting can help reduce food wastage.

### Efficient product distribution can improve resource utilization.

### Local sourcing can support shorter supply chains where practical.

### Target Beneficiaries

### Small and marginal farmers.

### Farmer Producer Organizations (FPOs).

### Individual consumers.

### Retail shops and supermarkets.

### Hotels and restaurants.

### Wholesale and institutional buyers.

### Logistics and delivery providers.

### Expected Outcomes

### Improved market accessibility for farmers.

###More transparent agricultural pricing.

### Reduced unnecessary intermediaries.

### Better coordination between supply and demand.

### More efficient agricultural product distribution.

# Research and References
###The proposed platform is supported by research into existing agricultural digital marketplaces and government initiatives.

### 1. National Agriculture Market (e-NAM)

### Government of India's electronic agricultural trading platform, which connects agricultural markets and supports online trading.

### Website: https://www.enam.gov.in/

### 2. Farmer Producer Organization (FPO) Scheme

### Government initiative supporting the formation and development of FPOs to improve farmers' collective bargaining power and market access.

### Website: https://agriwelfare.gov.in/

### 3. Open Network for Digital Commerce (ONDC)

### An open-network approach to digital commerce that can provide useful ideas for interoperable marketplace integration.

### Website: https://ondc.org/

### 4. Ministry of Agriculture & Farmers Welfare

### Government information about agricultural development, farmer welfare and digital agriculture initiatives.

### Website: https://agriwelfare.gov.in/

### 5. OpenStreetMap

### Open-source geographical data useful for mapping and location-based services.

### Website: https://www.openstreetmap.org/
