<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Pizza Sales Report – Power BI Dashboard</title>
<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        margin: 20px;
        color: #333;
    }
    h1, h2, h3, h4 {
        color: #d35400;
    }
    .section-title {
        border-bottom: 2px solid #d35400;
        padding-bottom: 4px;
        margin-top: 30px;
    }
    table {
        width: 100%;
        border-collapse: collapse;
        margin: 15px 0;
    }
    table th, table td {
        border: 1px solid #999;
        padding: 8px 10px;
        text-align: left;
    }
    table th {
        background-color: #f4f4f4;
    }
    .highlight {
        font-weight: bold;
        color: #c0392b;
    }
    ul {
        margin: 8px 0 8px 18px;
    }
</style>
</head>
<body>

<h1>🍕 <strong>Pizza Sales Report – Power BI Dashboard</strong></h1>
<hr />

<h2 class="section-title">📌 Project Overview</h2>
<p>
    This Power BI dashboard provides a comprehensive analysis of pizza sales from 
    <strong>January 2015 to December 2015</strong>. It helps stakeholders understand 
    <strong>revenue performance</strong>, <strong>customer purchasing patterns</strong>, 
    <strong>bestsellers</strong>, <strong>worst sellers</strong>, and 
    <strong>sales trends</strong> across days, months, categories, and sizes.
</p>

<h2 class="section-title">📊 Key Metrics</h2>
<table>
    <tr>
        <th>Metric</th>
        <th>Value</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><strong>Total Revenue</strong></td>
        <td>817.86K</td>
        <td>Total earnings generated from all pizza sales.</td>
    </tr>
    <tr>
        <td><strong>Average Order Value</strong></td>
        <td>38.31</td>
        <td>Average revenue per order.</td>
    </tr>
    <tr>
        <td><strong>Total Pizzas Sold</strong></td>
        <td>50K</td>
        <td>Quantity of pizzas sold.</td>
    </tr>
    <tr>
        <td><strong>Total Orders</strong></td>
        <td>21K</td>
        <td>Number of customer orders placed.</td>
    </tr>
    <tr>
        <td><strong>Average Pizzas per Order</strong></td>
        <td>2.32</td>
        <td>Indicates multi-item ordering behavior.</td>
    </tr>
</table>

<h2 class="section-title">🥇 Best & Worst Sellers</h2>

<h3>🔥 Best Sellers</h3>
<ul>
    <li><strong>Revenue:</strong> Thai Chicken Pizza</li>
    <li><strong>Quantity Sold:</strong> Classic Deluxe Pizza</li>
    <li><strong>Most Ordered:</strong> Classic Deluxe Pizza</li>
</ul>

<h3>❄️ Worst Sellers</h3>
<ul>
    <li><strong>Revenue:</strong> Brie Carre Pizza</li>
    <li><strong>Quantity Sold:</strong> Brie Carre Pizza</li>
    <li><strong>Least Ordered:</strong> Brie Carre Pizza</li>
</ul>

<h2 class="section-title">📈 Top & Bottom 5 Pizza Performance</h2>

<h3>⭐ Top 5 by Revenue</h3>
<ul>
    <li>The Thai Chicken – 43K</li>
    <li>The Barbecue Chicken – 43K</li>
    <li>The Californian – 41K</li>
    <li>The Classic Deluxe – 38K</li>
    <li>The Spicy Italian – 35K</li>
</ul>

<h3>⭐ Top 5 by Quantity</h3>
<ul>
    <li>Classic Deluxe – 2.5K</li>
    <li>Barbecue Chicken – 2.4K</li>
    <li>Hawaiian – 2.4K</li>
    <li>Pepperoni – 2.4K</li>
    <li>Thai Chicken – 2.4K</li>
</ul>

<h3>⬇️ Bottom 5 by Revenue</h3>
<ul>
    <li>Spinach – 15.6K</li>
    <li>Mediterranean – 15.4K</li>
    <li>Spinach Delight – 15.3K</li>
    <li>Green Garden – 14K</li>
    <li>Brie Carre – 11.6K</li>
</ul>

<h3>⬇️ Bottom 5 by Quantity</h3>
<ul>
    <li>Soppressata – 961</li>
    <li>Spinach – 950</li>
    <li>Calabrese – 937</li>
    <li>Mediterranean – 934</li>
    <li>Brie Carre – 490</li>
</ul>

<h2 class="section-title">📅 Sales Trend Insights</h2>

<h3>Daily Trend</h3>
<ul>
    <li>Peak sales: <strong>Friday & Saturday</strong></li>
    <li>Lowest sales: <strong>Sunday</strong></li>
</ul>

<h3>Monthly Trend</h3>
<ul>
    <li><strong>Highest:</strong> July, January</li>
    <li><strong>Lowest:</strong> October, February</li>
</ul>

<h2 class="section-title">🍕 Sales Breakdown</h2>

<h3>By Pizza Category</h3>
<ul>
    <li><strong>Classic – 15K</strong> (highest)</li>
    <li>Supreme – 12K</li>
    <li>Veggie – 12K</li>
    <li>Chicken – 11K</li>
</ul>

<p><span class="highlight">Insight:</span> Classic pizzas dominate both revenue and quantity.</p>

<h3>By Pizza Size</h3>
<ul>
    <li><strong>Large (L): 45.89%</strong></li>
    <li>Medium (M): 30.49%</li>
    <li>Small (S): 21.77%</li>
    <li>XL & XXL: &lt;2%</li>
</ul>

<p><span class="highlight">Insight:</span> Customers prefer larger pizza sizes, directly contributing to revenue.</p>

<h2 class="section-title">🧠 Business Insights</h2>
<ul>
    <li>Weekend demand suggests strong effectiveness of Friday–Saturday promotions.</li>
    <li>Classic & Chicken pizzas should be prioritized in marketing & inventory.</li>
    <li>Poor-selling pizzas (e.g., Brie Carre) may require recipe improvement or removal.</li>
    <li>Large-size pizzas dominate — bundle offers can increase revenue.</li>
    <li>Seasonal sales peaks (July, January) help in staffing & stock planning.</li>
</ul>

<h2 class="section-title">🛠️ Tech Stack</h2>
<ul>
    <li>Power BI Desktop</li>
    <li>DAX (Data Analysis Expressions)</li>
    <li>Power Query</li>
    <li>Microsoft SQL / CSV Source</li>
</ul>

<h2 class="section-title">📁 Files Included</h2>
<ul>
    <li><strong>Pizza Sales Report.pbix</strong> – Interactive dashboard</li>
    <li><strong>README.pdf</strong> – Project documentation</li>
</ul>

<h2 class="section-title">🚀 How to Use the Dashboard</h2>
<ol>
    <li>Download the <strong>.pbix</strong> file.</li>
    <li>Open it in <strong>Power BI Desktop</strong>.</li>
    <li>Use the slicers (Category, Date Range) to filter the data.</li>
    <li>Navigate through pages for detailed analysis.</li>
</ol>

<h2 class="section-title">📌 Conclusion</h2>
<p>
    This dashboard delivers actionable insights into pizza sales performance across categories, sizes, and time periods.  
    It supports data-driven decisions for marketing, inventory management, staffing, and menu optimization.
</p>

<h2 class="section-title">🔮 Future Improvements</h2>
<ul>
    <li>Add forecasting for monthly sales</li>
    <li>Implement Row-Level Security (RLS)</li>
    <li>Include customer segmentation</li>
    <li>Automate refresh using Power BI Service + Gateway</li>
    <li>Add KPIs like YoY, MoM growth metrics</li>
</ul>

<h2 class="section-title">🤝 Contributions</h2>
<p>Contributions, issues, and feature requests are welcome!</p>

<h2 class="section-title">📬 Contact</h2>
<p><strong>Email:</strong> subhasmitasahu72@gmail.com</p>
<p><strong>LinkedIn:</strong> 
<a href="https://www.linkedin.com/in/subhasmita-sahu-b0aa92209/" target="_blank">
    https://www.linkedin.com/in/subhasmita-sahu-b0aa92209/
</a>
</p>

</body>
</html>
