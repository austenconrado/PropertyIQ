An AI-powered real estate investment agent built with Loveable, contains Supabase for backend analysis that analyzes both property fundamentals and a user’s personal financial profile to generate a comprehensive Investment Score.

The agent integrates data from:
Zillow – Property value estimates, price history, number of rooms, bathrooms, square footage, and rental potential
SpotCrime – Local crime data to assess neighborhood safety and risk exposure
United States Census Bureau (Census API) – Demographics, median income, employment data, and population trends


Evaluation Factors

Property-Level Factors:
Listing price and estimated value
Number of bedrooms and bathrooms
Property size and layout efficiency
Market trends and appreciation potential
Rental yield potential

Location & Risk Factors:
Crime rates and severity breakdown
Local income levels and economic stability
Population growth trends

Personal Investment Alignment:
User salary and income stability
State-specific cost considerations (taxes, insurance, regulatory environment)
Affordability ratios (price-to-income, debt-to-income modeling)
Risk tolerance and investment strategy (cash flow vs. appreciation focus)


Output
The agent generates:
A weighted Investment Score
Risk segmentation (market risk, neighborhood risk, affordability risk, strategy-fit risk)
Identified challenges and red flags
Clear recommendation: Buy, Hold, Reassess, or High Risk

This project demonstrates how an intelligent agent can combine public API data with personalized financial inputs to deliver transparent, data-driven real estate investment decisions tailored to each user.
