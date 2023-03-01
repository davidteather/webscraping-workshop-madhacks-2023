# webscraping-workshop-madhacks-2023
Introduction to Static Site Web Scraping Workshop For MadHacks 2023

[**TARGET WEBSITE**](https://davidteather.github.io/webscraping-workshop-website-madhacks-2023/)

## Activities

1. Get Prices From Home Page (Demo)
2. Print Product Title & Prices
3. Get All Colors Available For Each Product
4. Get Every Product's Material
    - This is visible when you click into a product's page
        <details>
            <summary>Hint 1</summary>
            You'll need to make an additional HTML request for each product.
        </details>
5. Filter all the products from highest reviewed to lowest reviewed
6. Product Availability
    - Not all products are available, look at `Gerald the Giraffe`
        <details>
            <summary>Bonus</summary>

            Add some logic to check products every X minutes, so you can be notified when products come back in stock
            
            
            Note: This website won't have items come back into stock, but if it was a real website you could have a Discord bot or something notify you.
            - Example: Old commisioned project I made (https://github.com/davidteather/Hotukdeals-Discord-Notifier)
        </details>
7. Scrape Reviews For Each Product
    <details>
        <summary>Bonus</summary>

        Try and do sentiment analysis on product reviews and sort by ones with the best average sentiment.

        You might find https://realpython.com/python-nltk-sentiment-analysis/#using-nltks-pre-trained-sentiment-analyzer helpful
    </details>


Solutions will be posted after workshop (if I forget remind me)