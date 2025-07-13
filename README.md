# **E-commerce Analytics Dashboard for Stuffed Animal Toys**

## 🚀 Project Overview

A growing e-commerce startup specializing in **stuffed animal toys** has successfully completed three years of operations. As the company scales further, **Cindy Sharp (CEO)** is preparing for the next round of funding and aims to leverage data-driven insights to:

- ✅ Optimize overall business performance  
- 🚀 Drive successful new product launches  
- ⚙️ Enhance operational efficiency  

This interactive **Streamlit dashboard** presents insights across key business areas including:
- Traffic analysis  
- Product sales  
- Customer behavior  
- Channel performance  
- Business KPIs  
- Refund patterns and product launches  

---

## 🧠 Tech Stack

| Layer       | Technology                                |
|-------------|--------------------------------------------|
| **Frontend** | Streamlit (with custom dark theme UI)     |
| **Backend**  | SQL Server (via SQLAlchemy and pyodbc)    |
| **Libraries**| pandas, numpy, seaborn, matplotlib, plotly, itertools |
| **Deployment**| GitHub + Render                          |

---

## 🧱 Entity Relationship Diagram (ERD)

This app uses data sourced from a **SQL Server database** with the following schema:

![ER Diagram](images/er_diagram.png)

### **Tables:**

- `website_sessions` – Session-level data (device type, UTM parameters, repeat users)  
- `website_pageviews` – All page views linked to sessions  
- `orders` – Purchase-level data (session ID, product, quantity, price)  
- `order_items` – Individual items per order with price & cost  
- `order_item_refunds` – Refunds issued per order item  
- `products` – Product metadata including names and categories  
