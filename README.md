# WENDY-S-CHOCO-COUNTRY-LEVEL-SALES-REPORT

## Problem Statement

This report helps the chocolate company understand how their salespersons are doing on a country level. It helps the chocolate company know if their salespersons are in loss or profit. Through different country report, they get to know their improvement area, & thus they can improve their sales by identifying these area that less revenue come from. It also lets them know the chocolate products that are most revenue, thus by using this sales report they saw clearly how everyone has been doing , they can further work on factors responsible for these low sales in some areas.
Overall, Organic Choco Syrup and 70% Dark Bites are the top 2 products that have lower sales, but looking at the products by country, Organic Choco Syrup and 50% Dark Bites had the lowest sales in Australia, Caramel Stuffed Bars and Organic Choco Syrup in Canada, 70% Dark Bites and Milk Bars in India, Almond Choco and Mint Chip Choco in New Zealand, White Choc and Mint Chip Choco in UK, Orange Choco and Almond Choco in USA.

Looking at the report, we can tell that thes products have low sales and may be advised to be discontinued in these countries.


### Steps followed 

- Step 1 : Load data into MS Excel, dataset is a csv file.
- Step 2 : Joined the cost per unit from the product table to the data in the salespersons table using the XLOOKUP
- Step 3 : Checked for blanks in the new table and corrected each column to the right data type.
- Step 4 : Also since there is a cost per unit column, the coulumn for sales per unit is created
- Step 5 : Then column for the total cost and profit were created.
- Step 6 : The new table was loaded to power query where REVENUE BY COUNTRY, TOP 5 PRODUCTS, TOP 5 SALESPERSONS	BOTTOM 5 SALESPERSONS, SALEPERSONS BY UNITS, TOTAL COST, TOTAL REVENUE, PROFIT, ETC
- Step 7 : A visualizations was assigned to each of the query from the insert view pane
- Step 8 : Proceeded in creating a sales report dashboard, a bar charts was was added to the canvas deplicating REVENUE BY COUNTRY, TOP 5 PRODUCTS, TOP 5 SALESPERSONS	BOTTOM 5 SALESPERSONS.
- Step 9 : A scattered plot was used to establish a relationship between total revenue and units sold.
- Step 10 : A slicer was added covering the geoghaphy four card visuals were added to the canvas, representing TOTAL REVENUE, TOTAL COST, TOTAL UNIT, TOTAL PROFIT.

### [1] SALES STATISTICS 

        Total Revenue = $1,240,869
	
        Total Cost    = $439,704	

        Total Units   = 45,660	
	
        Total Profit  = $801,165 	
	
        thus, the company is in profit


### [2] TOP 5 PRODUCTS($)

    Peanut Butter Cubes   - 69,160 
    Organic Choco Syrup   - 69,461 
    Baker's Choco Chips   - 70,273 
    Choco Coated AlmondS  - 71,967 
    Caramel Stuffed Bars  - 72,373 

  
### [3] REVENUE BY COUNTRY($)

    Australia    - 168,679 
    Uk           - 173,530 
    USA          - 189,434 
    New Zealand  - 218,813 
    Canada       - 237,944 
    India        - 252,469 


### [4] SALESPERSONS BY REVENUE($)

     Oby Sorrel      - 83,216 
     Brien Boise     - 98,084 
     Carla Molina    - 98,210 
     Gunar Cockshoot - 106,834 
     Barr Faughny    - 123,949 
     Curtice Advani  - 130,697 
     Husein Augar    - 132,580 
     Ches Bonnell    - 149,975 
     Ram Mahesh      - 151,599 
     Gigi Bohling    - 165,725 


### [5] TOP 5 SALESPERSONS BY COUNTRY

     Canada        - Gigi Bohling   -39,620 
     India         - Gigi Bohling   -41,559 
     New Zealand   - Ches Bonnell   -43,568 
     UK            - Barr Faughny   -45,752 
     USA           - Ram Mahesh     -38,325 


### [6] BOTTOM 5 SALESPERSONS BY COUNTRY

     Australia     - Gigi Bohling   -25,221 
     Canada        - Gigi Bohling   -39,620 
     India         - Gigi Bohling   -41,559 
     New ZealanD   - Ches Bonnell   -43,568 
     USA           - Ram Mahesh     -38,325 

### SNAPSHOT OF THE SALES REPORT
![wendy](https://github.com/Chiemezuo89/WENDY-S-CHOCO-COUNTRY-LEVEL-SALES-REPORT/assets/172860025/4edf1a23-00fc-47f5-9fec-b711796a0653)


