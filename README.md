****#TestCase - Myntra.com#****

1) Open https://www.myntra.com/
2) Mouse over on WOMEN (Actions -> moveToElement
3) Click Jackets & Coats
4) Find the total count of item (top) -> getText -> String
	 String str = driver.findElementByClassName("title-count").getText();
	 split, 
	 String text = str.replaceAll("\\D","") -> String
	 Integer.parseInt(text) -> int
5) Validate the sum of categories count matches
6) Check Coats
7) Click + More option under BRAND	
8) Type MANGO and click checkbox
9) Close the pop-up x
10) Confirm all the Coats are of brand MANGO
    findElements (brand) -> List<WebElement> 
    foreach -> getText of each brand 
    compare > if(condition)
11) Sort by Better Discount
12) Find the price of first displayed item
     findElements (price) -> List<WebElement> 
     get(0) -> WebElement -> getText -> String -> int
13) Mouse over on size of the first item
14) Click on WishList Now
15) Close Browse

****#TestCase - Nykaa.com#****

1) Go to https://www.nykaa.com/
2) Mouseover on Brands and Mouseover on Popular
3) Click L'Oreal Paris
4) Go to the newly opened window and check the title contains L'Oreal Paris
5) Click sort By and select customer top rated
6) Click Category and click Shampoo
7) check whether the Filter is applied with Shampoo
8) Click on L'Oreal Paris Colour Protect Shampoo
9) GO to the new window and select size as 175ml
10) Print the MRP of the product
11) Click on ADD to BAG
12) Go to Shopping Bag 
13) Print the Grand Total amount
14) Click Proceed
15) Click on Continue as Guest
16) Print the warning message (delay in shipment)
17) Close all windows

****#TestCase - makemytrip.com#****

1) Go to https://www.makemytrip.com/
2) Click Hotels
3) Enter city as Goa, and choose Goa, India
4) Enter Check in date as Next month 15th (May 15) and Check out as start date+5
5) Click on ROOMS & GUESTS and click 2 Adults and one Children(age 12). Click Apply Button.
6) Click Search button
7) Select locality as Baga
8) Select 5 start in Star Category under Select Filters
9) Click on the first resulting hotel and go to the new window
10) Print the Hotel Name 
11) Click MORE OPTIONS link and Select 3Months plan and close
12) Click on BOOK THIS NOW
13) Print the Total Payable amount
14) Close the browser

****#TestCase - hp.com#****

1) Go to https://store.hp.com/in-en/ 
2) Mouse over on Laptops menu and click on Pavilion 
3) Under SHOPPING OPTIONS -->Processor -->Select Intel Core i7
4) Hard Drive Capacity -->More than 1TB 
5) Select Sort By: Price: Low to High 
6) Print the First resulting Product Name and Price 
7) Click on Add to Cart 
8) Click on Shopping Cart icon --> Click on View and Edit Cart 
9) Check the Shipping Option --> Check availability at Pincode 
10) Verify the order Total against the product price 
11) Proceed to Checkout if Order Total and Product Price matches 
12) Click on Place Order 
13) Capture the Error message and Print 
14) Close Browser

****#TestCase - bigbasket.com#****

1) Go to https://www.bigbasket.com/
2) mouse over on  Shop by Category 
3)Go to FOODGRAINS, OIL & MASALA --> RICE & RICE PRODUCTS 
4) Click on Boiled & Steam Rice
5) Choose the Brand as bb Royal
6) Go to Ponni Boiled Rice - Super Premium and select 5kg bag from Dropdown
7) print the price of Rice
8) Click Add button
9) Verify the success message displayed 
10) Type Dal in Search field and enter
12) Go to Toor/Arhar Dal and select 2kg & set Qty 2 
13) Print the price of Dal
14) Click Add button
15) Mouse hover on My Basket 
16) Validate the Sub Total displayed for the selected items
17) Reduce the Quantity of Dal as 1 
18) Validate the Sub Total for the current items
19) Close the Browser

****#TestCase - ajio.com#****

1) https://www.ajio.com/shop/sale 
2) Enter Bags in the Search field and Select Bags in Women Handbags 
3) Click on five grid and Select SORT BY as "What's New"
4) Enter Price Range Min as 2000 and Max as 5000 
5) Click on the product "Puma Ferrari LS Shoulder Bag" 
6) Verify the Coupon code for the price above 2690 is applicable for your product, if applicable the get the Coupon Code and Calculate the discount price for the coupon 
7) Check the availability of the product for pincode 560043, print the expected delivery date if it is available 
8) Click on Other Informations under Product Details and Print the Customer Care address, phone and email 
9) Click on ADD TO BAG and then GO TO BAG 
10) Check the Order Total before apply coupon 
11) Enter Coupon Code and Click Apply 
12) Verify the Coupon Savings amount(round off if it in decimal) under Order Summary and the matches the amount calculated in Product details 
13) Click on Delete and Delete the item from Bag 
14) Close all the browsers

****#TestCase - azure.microsoft.com#****

1) Go to https://azure.microsoft.com/en-in/ 
2) Click on Pricing 
3) Click on Pricing Calculator 
4) Click on Containers 
5) Select Container Instances 
6) Click on Container Instance Added View 
7) Select Region as "South India" 
8) Set the Duration as 180000 seconds 
9) Select the Memory as 4GB 
10) Enable SHOW DEV/TEST PRICING 
11) Select Indian Rupee  as currency 
12) Print the Estimated monthly price 
13) Click on Export to download the estimate as excel 
14) Verify the downloaded file in the local folder 
15) Navigate to Example Scenarios and Select CI/CD for Containers 
16) Click Add to Estimate 
17) Change the Currency as Indian Rupee 
18) Enable SHOW DEV/TEST PRICING 
19) Export the Estimate 
20) Verify the downloaded file in the local folder

****#TestCase - honda2wheelersindia.com#****
1) Go to https://www.honda2wheelersindia.com/ 
2) Click on scooters and click dio 
3) Click on Specifications and mouseover on ENGINE 
4) Get Displacement value 
5) Go to Scooters and click Activa 125 
6) Click on Specifications and mouseover on ENGINE 
7) Get Displacement value 
8) Compare Displacement of Dio and Activa 125 and print the Scooter name having better Displacement. 
9) Click FAQ from Menu  
10) Click Activa 125 BS-VI under Browse By Product 
11) Click  Vehicle Price  
12) Make sure Activa 125 BS-VI selected and click submit 
13) click the price link 
14)  Go to the new Window and select the state as Tamil Nadu and  city as Chennai 
15) Click Search 
16) Print all the 3 models and their prices 
17) Close the Browser
