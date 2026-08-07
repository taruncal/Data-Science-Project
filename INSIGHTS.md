### 1. Average NPS by Source

**Location:** `Average NPS by Source.jpg` (or `IMAGES FOLDER/Average NPS by Source.jpg`)

In NPS rules, ratings 0 to 6 are counted as Detractors, while only ratings 9 and 10 count as Promoters.

Because the random data gives equal votes to every score, there are 7 Detractor categories compared to only 2 Promoter categories.

This heavy imbalance of categories forces the final NPS calculation deep into the negative (-45.5), even though the simple numerical average is 5.0.

---

### 2. Average Order Value By Category

**Location:** `Average Order Value By Category.jpg` (or `IMAGES FOLDER/Average Order Value By Category.jpg`)

The Average Order Value (AOV) is virtually identical across all product categories, ranging narrowly from $2,713.51 (Home) to $2,735.74 (Books).

Books holds the slightly highest average order value at $2,735.74, but the difference across all four categories is under $23 (~0.8%).

Such uniform averages across vastly different product types (like Books vs. Electronics) strongly suggest the dataset was generated artificially with random price distributions.


### 3. Average Order Value By Source

**Location:** `Average Order Value By Source.jpg` (or `IMAGES FOLDER/Average Order Value By Source.jpg`)

Average Order Value (AOV) is virtually identical across all customer acquisition channels, hovering tightly around $2,720 to $2,727.

Facebook Campaign yields the highest average spending at $2,727.18, but leads Organic Search ($2,720.71) by a negligible margin of less than $7.

This uniform performance across completely different traffic channels further confirms that the order amounts in the dataset were generated synthetically using a random distribution.

---

### 4. Average Purchase Amount By Gender

**Location:** `Average Purchase Amount By Gender.jpg` (or `IMAGES FOLDER/Average Purchase Amount By Gender.jpg`)

Average spending is nearly identical across demographics, with females averaging $2,727.48 and males averaging $2,723.24.

The difference in purchase amount between genders is negligible at just $4.24 (about 0.15%).

This near-perfect parity further reinforces that purchase amounts were randomly generated across customer attributes.

---

### 5. Customer Age Distribution

**Location:** `Customer Age Distribution.jpg` (or `IMAGES FOLDER/Customer Age Distribution.jpg`)

Customer ages span evenly from 18 to 70 with a fairly flat density curve (KDE line) sitting around ~12,000 across all age levels.

The alternating bin heights in the histogram are caused by binning artifacts (bin width alignment) rather than actual gaps in underlying customer behavior.

The overall uniform spread across the entire age spectrum confirms that age data was artificially generated using a uniform random distribution.

---

### 6. Customer Distribution By Age

**Location:** `Customer Distribution By Age.jpg` (or `IMAGES FOLDER/Customer Distribution By Age.jpg`)

Customer counts are spread evenly across all ages from 18 to 70, resulting in a virtually flat density curve holding steady around ~16,000.

The alternating height pattern between adjacent histogram bars is a visual binning artifact (bin size alignment), not a true variation in age distribution.

The flat trend across the entire age spectrum confirms that the underlying age values were synthetically generated using a uniform random distribution.


### 7. NPS Distribution

**Location:** `NPS Distribution.jpg` (or `IMAGES FOLDER/NPS Distribution.jpg`)

The Net Promoter Score (NPS) distribution is completely flat across all values from 0 to 10, with each score logging around 22,500 to 23,000 counts.

Because 7 of the 11 bins (0–6) are classified as Detractors while only 2 bins (9–10) are Promoters, the flat spread inherently skews the final NPS calculation negative (-45.5).

This perfectly equal distribution confirms that the customer survey responses were generated synthetically using a uniform random integer distribution.




### 8. Number of Customers Acquired by Source

**Location:** `Number of Customers Acquired by Source.jpg` (or `IMAGES FOLDER/Number of Customers Acquired by Source.jpg`)

Paid digital marketing channels (Instagram, Facebook, and SEM) lead acquisition evenly, bringing in over 36,000 customers each.

Instagram Campaign generated the highest volume with 36,616 customers, closely followed by Facebook (36,234) and SEM (36,045).

Organic Search lags significantly behind paid channels, acquiring 27,170 customers—roughly 25% lower than paid traffic streams.



### 9. Revenue By Age Group

**Location:** `Revenue By Age Group.jpg` (or `IMAGES FOLDER/Revenue By Age Group.jpg`)

The 55+ demographic drives the highest total sales volume by far, generating $210.20M in revenue.

Revenue across middle-age brackets (25–34, 35–44, and 45–54) remains virtually uniform, averaging roughly $125M–$127M per group.

The youngest segment (18–24) contributes the lowest overall revenue at $91.12M, largely because it covers a narrower 7-year span compared to the broader age brackets.




### 10. Revenue By Gender

**Location:** `Revenue By Gender.jpg` (or `IMAGES FOLDER/Revenue By Gender.jpg`)

Female customers generate slightly higher total revenue at $342.46M, compared to $338.88M from male customers.

The revenue split is almost perfectly balanced (~50.3% female vs. ~49.7% male), showing a gap of just $3.58M (~1%).

This near-equal distribution across genders further aligns with the synthetic, uniformly generated nature of the dataset.





### 11. Revenue By Source

**Location:** `Revenue By Source.jpg` (or `IMAGES FOLDER/Revenue By Source.jpg`)

Instagram Campaign is the top revenue generator overall, bringing in $191.22M.

Facebook Campaign ($182.10M) and SEM ($182.01M) perform nearly identically, taking the second and third spots.

Organic Search trails behind all paid channels significantly, generating $126.01M (~34% less than Instagram).




### 12. Revenue Contribution By Category

**Location:** `Revenue Contribution By Category.jpg` (or `IMAGES FOLDER/Revenue Contribution By Category.jpg`)

Books (30.1%) and Clothing (30.0%) are the primary revenue drivers, together accounting for over 60% of total revenue.

Electronics (20.0%) and Home (19.9%) form the remaining 40%, contributing equal shares to total sales.

Revenue split is clean and balanced into two distinct tiers: ~30% each for Books and Clothing, and ~20% each for Electronics and Home.






### 13. Revenue Over Time

**Location:** `Revenue Over Time.jpg` (or `IMAGES FOLDER/Revenue Over Time.jpg`)

Monthly revenue remains consistently stable around $15M to $16M ($1.5e7 to $1.6e7) throughout 2020 to mid-2023 with minimal seasonality.

The final recorded period (around late 2023) shows a sharp drop down to ~$0.75M, indicating incomplete data collection for the last month.

Excluding the partial final month, the overall business displays a highly steady and predictable revenue baseline over the 3-year period.






### 14. Top 10 Customers By Revenue

**Location:** `Top 10 Customers By Revenue.jpg` (or `IMAGES FOLDER/Top 10 Customers By Revenue.jpg`)

Customer ID 36437 leads all buyers with the highest total spend at $55,339.00, followed by ID 39817 at $51,718.00.

Spending across the remaining top customers (ranks 3 through 10) is remarkably clustered between $45,000 and $48,500.

The small variance among top spenders reflects a balanced high-value customer segment without extreme outlier whales.








### 15. Total Purchase Amount Distribution

**Location:** `Total Purchase Amount Distribution.jpg` (or `IMAGES FOLDER/Total Purchase Amount Distribution.jpg`)

Total purchase amounts are distributed completely flat between ~$500 and ~$5,000, holding a steady count of around 13,000 transactions per bin.

The sharp drop-offs at the far left (<$500) and far right (>$5,000) mark the exact lower and upper boundaries set for order totals.

This perfectly uniform shape confirms that transaction amounts were generated synthetically using a continuous random distribution.








### 16. Total Quantity Sold By Product Category

**Location:** `Total Quantity Sold By Product Category.jpg` (or `IMAGES FOLDER/Total Quantity Sold By Product Category.jpg`)

Clothing (225,322) and Books (223,876) lead sales volume, moving significantly higher unit quantities than other categories.

Electronics (150,828) and Home (149,698) form the secondary tier, selling roughly 33% fewer total units.

The items group neatly into two equal-performance pairs (~224k units vs. ~150k units), directly driving the revenue contribution split seen earlier.















































































