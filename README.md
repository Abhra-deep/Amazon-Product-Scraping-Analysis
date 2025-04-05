# Amazon Soft Toys Analysis

This project walks through the complete process of scraping, cleaning, and analyzing sponsored products in the **soft toys** category from Amazon India.

---

## Part 1: Amazon Scraping

1. Go to [Amazon India](https://www.amazon.in/)
2. Search for: `"soft toys"`
3. Scrape the following data for all **sponsored products**:
   - **Title**: Name of the product
   - **Brand**: Brand of the product
   - **Reviews**: Number of customer reviews
   - **Rating**: Average customer rating (out of 5)
   - **Selling Price**: Current price
   - **Image URL**: Link to the product image
   - **Product URL**: Link to the product page
4. Save the data in a structured format (CSV or Excel)

---

## Part 2: Data Cleaning and Preparation

1. **Clean the data**:
   - Remove duplicate entries
   - Ensure `price`, `reviews`, and `rating` fields are numeric
   - Remove special characters such as ₹

2. **Prepare the data**:
   - Convert columns to appropriate data types
   - Handle missing or corrupted values

---

## Part 3: Analysis

### 1. Brand Performance Analysis

**Objective**: Identify the top-performing brands in the "soft toys" category.

**Metrics**:
- Brand frequency: Number of times each brand appears in sponsored products
- Average rating per brand

**Insights**:
- Discover top brands dominating the category
- Identify high-rated but less frequent brands with potential

**Visualizations**:
- Bar chart showing the top 5 brands by frequency
- Pie chart showing the percentage share of top brands

---

### 2. Price vs. Rating Analysis

**Objective**: Determine whether higher-priced products tend to have better ratings.

**Metrics**:
- Average price across different rating ranges
- Identification of outliers offering good value for money

**Insights**:
- Highlight high-value products (low price, high rating)
- Identify overpriced but poorly rated products

**Visualizations**:
- Scatter plot of price vs. rating
- Bar chart of average price by rating range

---

### 3. Review and Rating Distribution

**Objective**: Identify the most popular and trusted products.

**Metrics**:
- Top 5 products by number of reviews
- Top 5 products by average rating

**Insights**:
- Identify best sellers with high reviews and good ratings
- Highlight highly rated products with fewer reviews that could be promoted

**Visualizations**:
- Bar chart for top-rated products
- Bar chart for most-reviewed products

---

## Files

- `amazonproductscrapping.ipynb`: Contains scraping, cleaning, and analysis code
- `soft_toys_data.csv`: Cleaned dataset (optional export)
- `README.md`: Project documentation

---

## Notes

- This project is for educational and research purposes.
- Ensure compliance with Amazon's terms of service when scraping data.
