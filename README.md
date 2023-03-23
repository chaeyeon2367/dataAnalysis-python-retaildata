</br>
</br>

# Retail Data analysis project using shopping mall order data 🛍

</br>

### 1. Dataset 
 - Order history data from 2010/12 - 2011/12 for an online retail site
 - Data from approximately 500,000 transactions 
 - Data source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail#)
 
</br>

### 2. Objectives of data analysis
 1. sales analysis
 2. customer analysis
   - Identify best customers
   - Analyze customer retention
 3. make a decision to run a push notification
 
   - Personalized push notification
       - Starting with Amazon, the trend is to personalize and find the best solution for each user.
        - Different users may have different spending patterns, so find out when they buy the most and send them coupons during those times
        
  4. Identify customer abandonment pages with log data
    
   - Web server log data
        - Files that record information about a request (IP, time, page visited, etc.) when a web server delivers a request to a client.
        - There are standards for the format of logs recorded, but the format can be changed in the settings.
        - Log data is mainly used in the form of debugging the web server, data analysis, etc.
        - Format used in the project

          - IP sessionID User identifier Time of day Request page status code Bytesize
   ```
   1.0.0.1 sessionid user59 [16/Dec/2019:02:00:08] GET /checkout 200 1508
   ```
   
 </br>
   - Conclusion: Funnel analysis shows that the cart-to-checkout payment process is the most time consuming.
   
   
   
   <img width="1018" alt="Capture d’écran 2023-03-23 à 20 20 01" src="https://user-images.githubusercontent.com/63314860/227325509-04239aee-fe1f-4c48-89fb-ee8aa5023bb1.png">
   
 </br>
 </br>
 
