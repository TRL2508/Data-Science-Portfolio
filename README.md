# Data Science Portfolio
This repository contains my data science projects/assignments completed for academic and self-learning. <br/>
The projects/assignments are mostly in Jupyter notebook files.<br/>
<br/>
Do contact me via [LinkedIn](https://sg.linkedin.com/in/teh-rui-ling "My LinkedIn profile") if you are hiring a data scientist. :nerd_face:

## List of assignments/projects
<table>
  <tr align="left" valign="top">
    <th>Project/Assignment</th>
    <th>Description</th>
  </tr>
  <tr valign="top">
    <td>Extract and visualize stock data<br/>
      [<a href="">Assignment</a>]</td>
    <td>Extract the necessary stock data using:
      <ul>
        <li><a href="">yfinance (yahoo finance) library</a>, and/or</li>
        <li><a href="">web scraping</a> (requests library to download the webpage and save the text of response).</li>
      </ul>
      Then display the data in graphs.
      <br/>
      <br/>
      <b>Skills:</b> Python (pandas, requests, beautifulsoup, plotly), data visualization 
    </td>
  </tr>
  <tr valign="top">
    <td>Working with City of Chicago datasets using SQL and Python<br/>
      [Assignment 1 | Assignment 2 | Project]</td>
    <td>Load the datasets [Chicago Census (Socioeconomic Indicators) Data, Chicago Public Schools & Chicago Crime Data] in an Db2 database on IBM Cloud instance, connect to the database and execute SQL queries to retrieve data from multiple tables.
      <br/>
      <br/>
      <b>Skills:</b> Structured query language (SQL), python (pandas)
    </td>
  </tr>
  <tr valign="top">
    <td>Develop models to predict housing prices in King Country, Seattle (USA)<br/>
      [Assignment]</td>
    <td>Using the dataset that contains house sale prices in King Country, Seattle (USA) and develops models to predict housing prices using the variables or features.
      <br/>
      <br/>
      <b>Skills:</b> Python (pandas, matplotlib, numpy, seaborn, sklearn), data analysis, data wrangling, exploratory data analysis (EDA), model development, model evaluation and refinement, machine learning, data visualization<br/>
      <b>Algorithms:</b> Linear Regression, Ridge Regression
    </td>
  </tr>
  <tr valign="top">
    <td>Develop models to predict the price of the car</td>
    <td>Using 1985 automobile dataset and develop several models to predict the price of the car using the variables or features.
      <ol>
        <li>Data understanding<br/>
        Obtain basic insights from data with pandas library.</li>
        <li>Data wrangling<br/>
        Handle missing values, correct data format, standardize and normalize data.</li>
        <li>Exploratory Data Analysis (EDA) with Python<br/>
          <ul>
            <li>Explore features/characteristics to predict price of car.</li>
            <li>Charts/Graphs are used to visualize the relationship between the variables (whether there are any correlation or causation between the variables).</li>
          </ul>
        </li>
        <li>Model development<br/>
        Develop prediction models.</li>
        <li>Model evaluation and Refinement<br/>
        Evaluate and refine prediction models.</li>
      </ol>
      <b>Skills:</b> Python (pandas, matplotlib, numpy, seaborn, sklearn), data wrangling, exploratory data analysis (EDA), model development, model evaluation and refinement, machine learning, data visualization<br/>
      <b>Algorithms:</b> Simple Linear Regression (SLR), Multiple Linear Regression (MLR), Polynomial Regression, Ridge Regression</td>
  </tr>
  <tr valign="top">
    <td>Extract and visualize the data on immigration to Canada</td>
    <td>Extract, explore and visualize the dataset (Immigration to Canada from 1980 to 2013) using pandas, numpy, matplotlib to plot charts/graphs.
      <ul>
        <li>Line Plots</li>
        <li>Area Plots, Histograms and Bar Charts</li>
        <li>Pie Charts, Box Plots, Scatter Plots and Bubble Plots</li>
        <li>Waffle Charts, Word Clouds and Regression Plots</li>
        <li>Maps</li>
      </ul>
      <b>Skills:</b> Python (pandas, matplotlib, numpy, seaborn, wordcloud, folium), data wrangling, exploratory data analysis (EDA), data visualization
    </td>
  </tr>
  <tr valign="top">
    <td>Develop US Domestic Airline Flights Performance Dashboard<br/>
      [Assignment]</td>
    <td>The reporting carrier on-time performance dataset were extracted, and exploratory graphs/charts were made to understand the data first before creating the dashboard (contains 2 types of reports - (1) Yearly Airline Performance Report and (2) Yearly Airline Delay Report).
      <br/>
      <br/>
      <b>Skills:</b> Python (pandas, plotly, dash), exploratory data analysis (EDA), data visualization
    </td>
  </tr>
  <tr valign="top">
    <td>Explore and build an accurate model for the past loan dataset<br/>
      [Assignment]</td>
    <td>
      <ul>
        <li>Using the past loans dataset and applying the specific machine learning algorithms to build the models, and</li>
        <li>Evaluate the accuracy of the built models using different evaluation metrics.</li>
      </ul>
      <b>Skills:</b> Python (pandas, matplotlib, numpy, sklearn, scipy, seaborn), data wrangling, exploratory data analysis (EDA), model development, model evaluation, data visualization, machine learning<br/>
      <b>Algorithms:</b> K Nearest Neighbor (KNN), Decision Tree, Support Vector Machine (SVM), Logistic Regression
    </td>
  </tr>
  <tr valign="top">
    <td>Implementing the specific machine learning models and datasets to build the models for prediction</td>
    <td>
      <ins>Regression</ins>
      <ul>
        <li>Simple Linear Regression (SLR)<br/>
          The algorithm uses one independent variable (that have linear relationship with the dependent variable) from the fuel consumption dataset to predict the dependent variable (CO2 emissions).</li>
        <li>Multiple Linear Regression (MLR)<br/>
        The algorithm uses multiple independent variables (that have linear relationship with the dependent variable) from the fuel consumption dataset to predict the dependent variable (CO2 emissions).</li>
        <li>Non-Linear Regression<br/>
          <ul>
            <li>Polynomial Regression<br/>
            The algorithm uses one independent variable (that have curvilinear relationship with the dependent variable) from the fuel consumption dataset, as nth degree polynomial to predict the dependent variable (CO2 emissions).</li>
            <li>Logistic Regression<br/>
            The algorithm uses one independent variable (that have “S”-shaped (sigmoid) curve relationship with the dependent variable) from the China’s GDP (from 1960 to 2014) dataset to predict the dependent variable (GDP value).</li>
          </ul>
        </li>
      </ul>
      <ins>Classification</ins>
      <ul>
        <li>K-Nearest Neighbours (KNN)<br/>
          The algorithm and customer dataset to build a classifier model to be used to predict the group of new or unknown cases.</li>
        <li>Decision Tree<br/>
        Using the algorithm to build model from historical data of patients and their response to different medications. The trained model will predict the class of an unknown patient or find the proper drug for new patient.</li>
        <li>Logistic Regression<br/>
        Using the algorithm and telecommunications dataset for customer churn prediction.</li>
        <li>Support Vector Machine (SVM)<br/>
        Using the algorithm and human cell dataset, to predict/classify the new record of cells whether its benign or malignant.</li>
      </ul>
      <ins>Clustering</ins>
      <ul>
        <li>k-Means Clustering<br/>
        Using this algorithm to apply customer segmentation on the customer dataset. It will partition the customers into mutually exclusive groups/clusters.</li>
        <li>Hierarchical Clustering<br/>
        Using existing vehicle dataset and algorithm to find the most distinctive cluster of existing vehicles to the new vehicle.</li>
        <li>Density-Based Spatial Clustering of Applications with Noise (DBSCAN)<br/>
        The algorithm will cluster the location of weather stations in Canada and find the group/cluster of stations which show the same weather condition (without getting affected by noise).</li>
      </ul>
      <ins>Recommender Systems</ins>
      <ul>
        <li>Content-based Filtering<br/>
        Extract user’s input from movie dataset, to recommend movies that will satisfy the user’s preferences.</li>
        <li>Collaborative Filtering<br/>
        Extract user’s input from movie dataset and find similar group of users, to provide recommendation based on similarity index within that group.</li>
      </ul>
      <b>Skills:</b> Python (pandas, matplotlib, numpy, sklearn, scipy, seaborn), data wrangling, exploratory data analysis (EDA), model development, model evaluation, data visualization, machine learning<br/>
      <b>Algorithms:</b> Simple Linear Regression (SLR), Polynomial Regression, Multiple Linear Regression (MLR), Non-Linear Regression, K-Nearest Neighbours (KNN), Decision Tree, Logistic Regression, Support Vector Machine (SVM), k-Means Clustering, Hierarchical Clustering, Density-Based Spatial Clustering of Applications with Noise (DBSCAN), Recommender Systems, Content-based Filtering, Collaborative Filtering
    </td>
  </tr>
  <tr valign="top">
    <td>Data Science Capstone on SpaceX</td>
    <td>
      <ol>
        <li>Data collection
          <ul>
            <li>Through application programming interface (API)<br/>
            Make a get request to the SpaceX API.</li>
            <li>From web scraping<br/>
            Extract Falcon 9 launch records from Wikipedia.</li>
          </ul>
        </li>
        <li>Data wrangling<br/>
        Cleaning, re-organizing and transforming the raw data from Wikipedia and SpaceX API.</li>
        <li>Exploratory data analysis (EDA)
          <ul>
            <li>Structured query language (SQL)<br/>
            Load the SpaceX dataset in an Db2 database on IBM Cloud instance, connect to the database and execute SQL queries to retrieve data from the table.</li>
            <li>Data visualization<br/>
            Explore the features, obtain some preliminary insights about how the variables that would affect the success rate and which features that will be used in success prediction.</li>
            <li>Interactive map visualization with folium<br/>
            Visualize some geographical patterns about SpaceX launch sites.</li>
          </ul>
        </li>
        <li>Interactive visual analytics and dashboard<br/>
        The dashboard has been built for users to perform interactive visual analytics on SpaceX launch data in real-time.</li>
        <li>Model development and evaluation (Predictive analysis)<br/>
        Split the data (into training and test data) to find the best hyperparameter for the 4 machine learning algorithms. Then among the 4 models, find the best performed method using test data.</li>
        <li>Data findings report on SpaceX<br/>
        All the findings and data-driven insights (determine if the first stage of Falcon 9 will land successfully) are compiled in a report.</li>
      </ol>
      <b>Skills:</b> Python (pandas, requests, beautifulsoup, matplotlib, numpy, sklearn, folium, seaborn, dash, plotly), data wrangling, exploratory data analysis (EDA), structured query language (SQL), model development, model evaluation, data visualization, machine learning<br/>
      <b>Algorithms:</b> Logistic Regression, Support Vector Machine (SVM), Decision Tree, K Nearest Neighbor (KNN) 
    </td>
  </tr>
  <tr valign="top">
    <td>Speech-to-Text translation through APIs<br/>
        [Assignment]</td>
    <td>
      <ol>
        <li>To convert an audio file of an English speaker to text using a speech to text API (IBM Speech to Text service), and</li>
        <li>Translate the text (from English to Spanish) using a language translator API (IBM Language Translator service).</li>
      </ol>
      <b>Skills:</b> Python (pandas)
    </td>
  </tr>
</table>
