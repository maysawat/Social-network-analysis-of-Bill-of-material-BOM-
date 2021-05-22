# Social-network-analysis-of-Bill-of-material-BOM


Social network analysis of Bill of material (BOM)

### Detail of Project 

https://medium.com/p/b7bef7456989/edit

### Video Presentation


### Setup and Install Neo4j Desktop

https://neo4j.com/download/

### Import Data From CSV. Files
Master Data
1.Item 
2.Vendor
3.Production BOM
4.Purchase Price
5.Revenue By Item

List of Relation
1.ProductionBOM => Item and Production BOM (Directed Graph)
2.HAVE => Production BOM and Item(Raw Material) as weight->QtyperUnit (Bipartite graph)
3.Item and Purchase Price คือบอกว่ามี Item (Directed Graph)
4.
5.



-ความสัมพันธ์ระหว่าง Item และ Purch Price คือบอกว่ามี Item นี้มีราคาซื้ออะไรบ้างโดยมี Vendor เป็น Directed Graph
-ความสัมพันธ์ระหว่าง Vendor และ Item คือ Vendor แต่ละรายขาย Item ที่เป็น Raw Material อะไรบ้าง โดยมี weight เป็น Unit Price เป็น Directed Graph


### Query
