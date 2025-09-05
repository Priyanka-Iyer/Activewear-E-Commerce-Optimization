# Activera - Activewear E-Commerce & Trend Forecasting  

Activera is an **online retail store** specializing in high-quality, affordable women’s activewear. This project demonstrates how we optimized Activera’s **e-commerce operations** using the **Shopify Admin API** and extended it with **trend forecasting** to stay ahead in the competitive activewear market.  

---

## Project Overview  

This repository contains two key components:  

1. **Activera E-Commerce Optimization (Shopify API)**  
   - Implemented real-time inventory management.  
   - Automated product information synchronization.  
   - Improved order tracking and fulfillment.  

2. **Activera Trend Forecasting – The Next Wave of Activewear**  
   - Analyzed historical and real-time fashion data (Google Trends, Vogue, Wikipedia).  
   - Extracted insights into consumer preferences and evolving activewear trends.  
   - Proposed AI-driven demand forecasting for future inventory and product planning.  

---

## Features  

### Shopify API Implementation  
- **Inventory Management**: Prevent stockouts & overselling with real-time tracking.  
- **Product Information Sync**: Ensure accurate product descriptions, prices, and sizes.  
- **Order Tracking & Fulfillment**: Integrated reliable updates for customer orders.  
- **Caching & Rate Limits**: Used `lru_cache` and polite delays to prevent API throttling.  

### Trend Forecasting Extension  
- **Athleisure Evolution**: Extracted text-based insights from historical fashion trends.  
- **Runway-Inspired Forecasting**: Analyzed fabrics, colors, and silhouettes shaping Spring 2025.  
- **Market Insights**:  
  - Tennis Dress demand spiked during **US Open 2024**.  
  - Yoga Set demand rising in late 2024–2025.  
  - Seamless Leggings show stable, long-term demand.  
- **Future Enhancements**: ML-powered demand forecasting (XGBoost), TikTok/Instagram trend integration, and real-time dashboards.  

---

## Tech Stack  

- **Language:** Python  
- **APIs:** Shopify Admin API (GraphQL + REST), Google Trends  
- **Libraries:** `shopifyapi`, `requests`, `pandas`, `time`, `functools`  
- **Data Storage:** CSV files for inventory & orders  
- **Visualization:** Pandas DataFrames, trend reports  

---

## Technical Implementation  

- **API Permissions**: Enabled Admin API with read/write for products & orders.  
- **Rate Limits**: Handled via `time.sleep(2)` and caching.  
- **Data Integration**: Combined trend data (Google Trends, Vogue insights, Wikipedia).  
- **Challenges**:  
  - API throttling (429 errors).  
  - Web scraping restrictions.  
  - Data merging across multiple sources.  

---

## Future Enhancements  

- AI-Powered Pricing & Demand Forecasting  
- Omnichannel Integration (Instagram, TikTok, Facebook Shops)  
- Enhanced Order Tracking (Shippo, AfterShip APIs)  
- Automated Customer Insights (NLP on reviews)  
- Real-Time Trend Dashboard  

---



