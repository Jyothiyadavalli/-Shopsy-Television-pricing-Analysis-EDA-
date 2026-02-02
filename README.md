# -Shopsy-Television-pricing-Analysis-EDA-


---

## Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of Smart Television products listed on the **Shopsy e-commerce platform**.
The goal is to understand **pricing variations**, identify **key factors influencing TV prices**, and help consumers make **value-for-money purchase decisions**.

The analysis explores how attributes such as **brand, screen size, resolution, display panel, operating system, discounts, and customer engagement** impact pricing.

---

## Domain

**E-commerce and Retail Analytics**

This project analyzes:

* Television brands
* Prices and discount strategies
* Screen sizes and resolutions
* Display panel technologies
* Operating systems
* Customer ratings and engagement

---

## Business Problem

Consumers often find large price differences among TVs with similar specifications on Shopsy.

Examples:

* TVs priced at ₹12,000 vs ₹60,000+ with similar features
* Large variation across brands and operating systems
* Premium resolutions and panels inflating prices
* Confusing discount structures

This creates difficulty in choosing the right TV based on value rather than marketing.

---

## Objectives

* Analyze TV price distribution across brands
* Study the relationship between screen size and price
* Compare pricing across resolutions (HD Ready, Full HD, 4K)
* Evaluate the impact of display panel technology
* Analyze the influence of operating systems
* Identify value-for-money TV segments
* Understand customer engagement patterns

---

## Data Source

* **Website**: Shopsy (Television category)
* **Data Type**: Publicly available product listings
* **Collection Method**: Web scraping
* **Tools Used**:

  * Python
  * Requests
  * Selenium
  * Pandas

Ethical scraping practices were followed using only publicly accessible data.

---

## Data Collection Process

1. Identified relevant Shopsy TV listing pages and product URLs
2. Sent HTTP requests to retrieve page content
3. Parsed HTML using Selenium
4. Extracted features such as:

   * Brand
   * Price (Original and Discounted)
   * Screen size
   * Resolution
   * Panel type
   * Operating system
   * Ratings and discounts
5. Cleaned and structured the data using Pandas
6. Exported the dataset to CSV/Excel for analysis

---

## Dataset Overview

* **Rows**: Smart TV product listings

* **Columns**:

  1. Brand
  2. Original Price
  3. Discounted Price
  4. Screen Size
  5. Resolution
  6. Panel Type
  7. Operating System
  8. Ratings

* **Data Types**: Numerical and Categorical

---

## Analysis Performed

### Univariate Analysis

* TV prices are highly right-skewed
* Majority of TVs fall in the low to mid-price range
* Mid-sized screens (43–55 inches) dominate the market
* Ultra HD is the most common resolution
* Google TV dominates operating system availability
* Customer engagement is concentrated on a few popular models

---

### Bivariate Analysis

* Price increases with screen size
* Larger TVs show wider price variation
* 4K TVs are priced significantly higher than HD Ready and Full HD
* WebOS TVs are priced highest, followed by Tizen and Google TV
* Higher-priced TVs often show larger advertised discounts
* Customer engagement is strongest in the ₹10,000–₹50,000 range

---

### Multivariate Analysis

* Brand and resolution together strongly influence price
* Premium brands price 4K TVs significantly higher
* OLED and QLED panels command a strong premium over LED
* Budget brands focus on affordability despite similar resolutions
* 4K TVs show high engagement across both budget and premium segments

---

## Statistical Testing

* One-way ANOVA confirmed a **statistically significant difference** in mean prices across screen size categories
* Screen size is a key determinant of TV pricing

---

## Key Insights

* Customer engagement follows a winner-takes-most pattern
* Affordability drives engagement more than premium pricing
* 4K resolution significantly increases prices
* Operating system strongly impacts pricing
* Google TV dominates the Smart TV ecosystem
* Premium features do not always translate into higher satisfaction

---

## Conclusion

Smart TV pricing on Shopsy is influenced by a combination of **resolution, brand positioning, screen size, panel technology, and operating system**.

Mid-priced TVs (₹10,000–₹50,000) deliver the best balance of affordability and customer engagement.
Premium features raise prices but do not consistently increase perceived value.
Google TV has emerged as the dominant operating system in the market.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Selenium
* Requests
* Excel

---

