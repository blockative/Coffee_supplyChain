# Coffee Supply Chain

## Description
Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

### Actors
* Farmer
* Distributor
* Retailer
* Consumer

### Actions
* **Farmer** – harvest coffee beans, process coffee beans, pack coffee bags, add coffee palettes, ship coffee palettes
* **Distributor** – buy coffee palettes
* **Retailer** – receive coffee palettes
* **Consumer** – buy coffee items 

Different steps that coffee beans goes through until it be bought by consumer showed in [activity diagram](#activity-diagram).

### User Interface

#### Product Overview Section
User can fetch information about concrete product.
![Product Overview](./img/product_overview.png "Product Overview")

#### Farm Details Section 
Farmer with concrete ID, Name, coordinates (Long and Lat), and some extra information can harvest coffee beans → process coffee beans → pack coffee bags → prepare them for sale.
![Farm Details](./img/farm_details.png "Farm Details")

#### Product Details Section
In this section prepared for sale coffee palettes can be bought by distributor. 
Then coffee palettes shiped by farmer to Retailer. Then Retailer received these palettes.
And finally Consumer bought Coffee items from Retailer.
![Product Details](./img/product_details.png "Product Details")

#### Transaction History Section 
This section contains IDs of all transactions that was produced with concrete product.
![Transaction History](./img/transaction_history.png "Transaction History")

## UML Diagrams

### Activity Diagram
![Activity Diagram](./uml/Activity%20Diagram.png "Activity Diagram")

### Sequence Diagram
![Sequence Diagram](./uml/Sequence%20Diagram.png "Sequence Diagram")

### State Diagram
![State Diagram](./uml/State%20Diagram.png "State Diagram")

### Data Model Diagram
![Data Model Diagram](./uml/Data%20Model%20Diagram.png "Data Model Diagram")



