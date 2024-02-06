# CLTV_Calculation_and_Prediction

This project employs the BG-NBD and Gamma-Gamma models to analyze customer purchase behaviors and predict Customer Lifetime Value (CLTV). This analysis helps businesses optimize their marketing strategies and manage customer relationships more effectively.

## BG-NBD Model  <br>
<img src="https://miro.medium.com/v2/resize:fit:1400/0*YUvxLkMUNx2jOIek" alt="alternatif metin" width="600" height=auto>

The BG-NBD (Beta-Geometric/Negative Binomial Distribution) model is a method used to predict the number of future purchases a customer will make. The model addresses how customer purchase behavior changes over time and the likelihood of customer churn.

### Features of the BG-NBD Model

- **Purchase Behavior Prediction:** Predicts how often customers will make purchases in the future.
- **Churn Analysis:** Assesses whether customers will cease interactions with the brand.

## Gamma-Gamma Submodel <br>

<img src="[resmin_url_adresi](https://miro.medium.com/v2/resize:fit:1400/1*ERgwQVrKQDl34Oq0STzTSA.png)" alt="alternatif metin" width="600" height=auto>

The Gamma-Gamma model is used to predict the monetary value of a customer's future purchases. This model analyzes the relationship between purchase frequency and the amount of money a customer spends.

### Features of the Gamma-Gamma Model

- **Monetary Value Prediction:** Estimates how much money customers will spend on each purchase.
- **Purchase Value Assessment:** Serves as a crucial tool for understanding the value of customer purchases.

## Combining for CLTV Model

The combination of the BG-NBD and Gamma-Gamma models provides a comprehensive method for predicting Customer Lifetime Value (CLTV). This approach evaluates both the frequency of a customer's future purchases and the amount of money they will spend during these transactions.

### Advantages of the CLTV Model

- **Comprehensive Analysis of Customer Value:** Helps understand the long-term value of customers to the business.  
- **Optimization of Marketing Strategies:** Provides data for developing customized marketing campaigns based on customer segments.  
- **Risk Management:** Identifies high-value customers, allowing the business to allocate its resources more effectively.<br>
<img src="https://assets-global.website-files.com/5ef27cb65411b70949a151e9/5fc098d7f7b16d5ed93e972a_CLTV1.04.png" alt="alternatif metin" width="600" height=auto>

# Business Problem

**1.** Verinin Hazırlanması (Data Preperation)  
**2.** BG-NBD Modeli ile Expected Number of Transaction  
**3.** Gamma-Gamma Modeli ile Expected Average Profit  
**4.** BG-NBD ve Gamma-Gamma Modeli ile CLTV'nin Hesaplanması  
**5.** CLTV'ye Göre Segmentlerin Oluşturulması
**6.** Çalışmanın fonksiyonlaştırılması

## Introduction
- E-ticaret şirketinin müşterilerini segmentlere ayırma ve pazarlama stratejileri belirleme isteği.  

## Data Set Story
- Online Retail II veri seti  
- İngiltere merkezli online satış mağazasının 01/12/2009 - 09/12/2011 tarihleri arasındaki satışlarını içeriyor.  

## Variables
• **InvoiceNo:** Invoice number. A unique number for each transaction or invoice. If it starts with 'C', it indicates a cancelled transaction.  
• **StockCode:** Product code. A unique number for each product.  
• **Description:** Product name.  
• **Quantity:** The number of units sold. It indicates how many of each product were sold in the invoices.  
• **InvoiceDate:** The date and time of the invoice.  
• **UnitPrice:** The price of the product (in pounds sterling).  
• **CustomerID:** Unique customer number.  
• **Country:** The name of the country. The country where the customer lives.  

## Analysis
- Müşteri alışveriş alışkanlıklarına göre segmentlere ayrılması  
- Segmentlere özel pazarlama stratejilerinin belirlenmesi  
- Müşteri memnuniyetinin artırılması  
- Satışların ve karlılığın artması  
