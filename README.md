<h1>Flipkart Mobile Sales Data Analysis</h1>
    <h2>Overview</h2>
    <p>This project performs an exploratory data analysis (EDA) on the Flipkart mobile sales data. The objective is to extract insights and provide recommendations for improving the mobile sales business on Flipkart.</p>
    <h2>Dataset</h2>
    <p>The analysis is performed on the Flipkart_mobile_brands_data.csv dataset, which contains the following columns:</p>
    <ul>
        <li><strong>Brand:</strong> Mobile brand name.</li>
        <li><strong>Model:</strong> Model name of the mobile.</li>
        <li><strong>Color:</strong> Color of the mobile.</li>
        <li><strong>Memory:</strong> RAM capacity.</li>
        <li><strong>Storage:</strong> Internal storage capacity.</li>
        <li><strong>Rating:</strong> Customer rating of the mobile.</li>
        <li><strong>Selling Price:</strong> Current selling price of the mobile.</li>
        <li><strong>Original Price:</strong> Original price of the mobile.</li>
    </ul>
    
  <h2>Analysis</h2>
    <p>The analysis includes the following steps:</p>
    <ol>
        <li>Data Loading and Overview: Load the dataset and display the first few rows.</li>
        <li>Rating Distribution: Plot the distribution of customer ratings.</li>
        <li>Selling Price Distribution: Plot the distribution of selling prices.</li>
        <li>Brand Popularity by Memory: Count the number of entries per memory configuration for each brand.</li>
        <li>Pairplot by Brand: Create pairplots to visualize relationships between variables, colored by brand.</li>
        <li>Selling Price Distribution by Brand: Plot the distribution of selling prices, segmented by brand.</li>
        <li>Brand Popularity: Plot the count of entries for each brand.</li>
        <li>Average Selling Price by Brand: Calculate and sort the average selling price for each brand.</li>
        <li>Rating vs. Selling Price: Create a scatter plot to visualize the relationship between rating and selling price, colored by brand.</li>
    </ol>
    <h2>Conclusion</h2>
    <ul>
        <li>The availability of low-range phones should be increased as most buyers purchase phones in the 15000 range.</li>
        <li>Vivo is providing more highly rated products and offers good value for money.</li>
        <li>It is not true that only higher-priced products have higher ratings; many mobiles in the 0 to 25000 range also have good ratings.</li>
    </ul>
    
   <h2>How to Run</h2>
    <ol>
        <li>Ensure you have the necessary Python libraries installed:</li>
        <pre><code class="language-bash">pip install pandas matplotlib seaborn</code></pre>
        <li>Download the Flipkart_mobile_brands_data.csv dataset and place it in your working directory.</li>
        <li>Run the provided code to perform the EDA and visualize the results.</li>
    </ol>
