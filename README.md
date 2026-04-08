# Products Deduplication Challenge

## English

### Task Goal
The task is about finding and unifying duplicate or inconsistent listings that describe the same product.  
The goal of the solution is to group listings that refer to the same product, avoid merging different products by mistake, and finally show the customer the lowest price from all listings linked to that product.

### Chosen Approach
I chose an approach based on text normalization, Hebrew-English term mapping, and comparison of key product details.  
The purpose of this approach is to handle inconsistent product names, detect duplicates carefully, and avoid incorrect merges between products that may look similar but are not the same.  
After grouping the relevant listings, the lowest price is selected from each product group.

For a more detailed explanation of the solution steps, please see the attached notebook.


## עברית 

### מטרת המשימה
המשימה עוסקת בזיהוי ואיחוד רשומות כפולות או לא אחידות המתארות את אותו מוצר.
מטרת הפתרון היא לאחד רשומות המתייחסות לאותו מוצר, תוך הימנעות ממיזוג שגוי של מוצרים שונים, ובסיום להציג ללקוח את המחיר הנמוך ביותר מתוך כלל הרשומות ששוייכו לאותו מוצר.

### הגישה שנבחרה 
בחרתי בגישה המבוססת על נרמול טקסט, מיפוי מונחים מקבילים בין עברית לאנגלית והשוואה בין מאפיינים מרכזיים של המוצר.
מטרת הגישה היא להתמודד עם שמות לא אחידים של אותו מוצר, לזהות כפילויות בצורה זהירה ולמנוע איחוד שגוי של מוצרים דומים אך שונים.
לאחר קיבוץ הרשומות הרלוונטיות, נבחר המחיר הנמוך ביותר מבין כל קבוצת המוצרים.

לפירוט מלא יותר של שלבי הפתרון, ניתן לראות את המחברת המצורפת.
