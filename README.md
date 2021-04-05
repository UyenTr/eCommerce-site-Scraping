# eCommerce-site-Scraping
For for our first project in the CoderSchool Machine Learning course we were given the task of choosing a product category from the popular Vietnamese B2C e-commerce platform Tiki. 
We chose the phone and tablets section as these are product we use daily. 
Next, we applied web scraping techniques to first extract 13 pieces of information about each of the products on page 1 of this category before expanding our search throughout all 22 pages of the product. 
These bits of information included each of the products names, prices, ratings averages, reviews and any discount rates applied to each product to name a few. 
Finally, we imported our extracted data into a panda dataFrame for easy viewing.

- What is the category you choose? Why?
- 
We chose the phone - tablet section from the Tiki website.
We chose this as we felt it was most relevant to our day to day lives.
Buying a phone or tablet is a much more pleasurable and cost effective experience than in South Africa.
We wanted to have a look at the data and see if it matched our expectations!

- How many products did u scrap?
423 out of a possible 423 products.
- What is the range and average price of that category?
- 423 out of a possible 423 products.
-
-  What is the range and average price of that category?

The cheapest product in this category cost 149 000 VND with the most expensive being the 37 990 000 iPhone 12 Pro Max 512GB!
That leaves a price range of 37 840 000 VND!

- What is the product with the most reviews and best reviews?

The most reviewed item was the Samamsung Galaxy M31 with 1597 reviews.
There were several products with a 100% reveiw rating but for the sheer amount of reviews and its 94% review rating we felt the Samamsung Galaxy M31 needs highlighting. 
We struggled a little with this as the values in of panada DataFrame returned strings. This morning we fixed the problem by converting the data we were looking for to integers and striping it so that it would run. 

The cheapest product in this category cost 149 000 VND with the most expensive being the 37 990 000 iPhone 12 Pro Max 512GB!
That leaves a price range of 37 840 000 VND!
