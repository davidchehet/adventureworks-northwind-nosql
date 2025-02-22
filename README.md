Reference materials 
Northwood Scehma : ![Screenshot 2025-02-20 at 3 14 58 PM](https://github.com/user-attachments/assets/ba73623c-7ed6-4927-8bd0-bed6359c392d)
AdventureWorks Schema : [AdvWorksOLTPSchema2005.pdf](https://github.com/user-attachments/files/18894259/AdvWorksOLTPSchema2005.pdf)

In this project, I displayed profiency in taking two structured databases, and merging them into a NoSQL database with MongoDB.
In order to make my NoSQL able to be query-able, it required several steps.
  1) Evaluating the two schemas to see which fields/columns are identical. For example, the 'suppliers' in Northwind is the same as the 'Vendor'. This had to be done for the entirety of my NoSQL database.
  2) Organizing the JSON files to have nested arrays of 'PurchaseOrderDetails' -> In the SQL version of both databases, if a purchase order had several different items within it, each item that was ordered got a separate row. Being as that is inefficient, we nested those details to fit every single PO detail into one Purchase Order.
  3) I added my own 'PurchaseOrder', showcasing that the database is open to adding in new information in an efficient way.

After this, I showcased my ability to query the information for important information applicable to real life.
