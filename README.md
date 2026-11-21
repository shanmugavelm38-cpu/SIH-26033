# Smart India Hackathon Workshop
# Date:30/10/26
## Reference Number:26008603
## Name:UMAS KARTHICK S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

•THE PROBLEM:TOO MANY INTERMEDIARIES
Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution: Demand-First Community Pooling

### How the Solution Works

The platform connects farmers and FPOs with local households, retailers, restaurants, and bulk buyers. Buyers post the produce they need, the quantity, and the delivery date. The platform combines nearby orders and shares the total demand with farmers, who can confirm what they have available.

Once orders are matched, produce can be collected from farmers or a nearby FPO and delivered together. This gives farmers a clearer idea of what buyers want before they send their produce to market. The platform can also use past orders and seasonal patterns to help estimate demand and plan delivery routes.

### How It Addresses the Problem

Farmers often depend on several intermediaries to reach buyers, which can reduce the price they receive. Buyers, in turn, may pay more by the time produce reaches them. By connecting farmers and FPOs directly with buyers, the platform can shorten this chain and make prices clearer to both sides.

Combining nearby orders also makes delivery more practical, especially when individual farmers do not have enough produce to fill a large order. Better information about demand can help farmers plan what to supply and reduce the chance of produce going unsold.

### What Makes the Solution Different

The platform starts with buyer demand and pools orders before farmers prepare their supply. This gives farmers a clearer view of what customers need, rather than asking them to list produce and wait for buyers to find it.

It also brings order matching and delivery coordination together. Small farmers and FPOs can combine their produce to serve larger buyers, while nearby customers can be served through shared deliveries.

## Technical Approach:

### Technologies Used

- **Front end:** React with HTML and CSS for a mobile-friendly interface where buyers can place requests and farmers or FPOs can list available produce.
- **Back end:** Python with FastAPI to manage accounts, produce listings, pooled orders, and order matching.
- **Database:** PostgreSQL to store user details, buyer requests, farmer supply, and delivery information.
- **Demand estimation:** Python with pandas and scikit-learn to estimate demand from previous orders and seasonal patterns. The prototype can begin with historical averages and use a forecasting model when more data is available.
- **Route planning and maps:** Google OR-Tools to plan delivery routes based on locations and vehicle capacity, with Leaflet and OpenStreetMap to display those routes.

### End-to-End Process

Buyers enter the produce, quantity, location, and delivery date they need. The platform groups nearby requests for the same produce and shares the pooled demand with local farmers and FPOs. Farmers confirm the quantities they can supply. The platform matches confirmed supply to the orders, plans collection and delivery stops, and updates the order status. Completed orders are saved to help estimate future demand.

### FLOWCHART
<img width="1600" height="2100" alt="image" src="https://github.com/user-attachments/assets/ce3d6d0f-b368-4172-8809-c629ea0b6fd6" />


### Implementation Method

The prototype will first provide separate screens for buyers, farmers or FPOs, and an administrator. Buyers will be able to submit requests, and farmers will be able to list produce and confirm available quantities. The back end will save this information and group nearby requests into pooled orders.

Once the main order process is working, route planning will be added using sample locations and vehicle capacities. The prototype will also show order status and a basic demand estimate based on past orders. The demonstration will follow one request from buyer submission through order pooling, farmer confirmation, and delivery planning.

## Feasibility and Viability:

### Feasibility of the Idea

Demand-First Community Pooling can be developed as a web application using existing tools for online orders, databases, maps, and route planning. A basic prototype can demonstrate the main process: buyers submit requests, the platform pools nearby demand, farmers confirm available produce, and delivery stops are planned.

The idea should first be piloted in one local area with a small group of farmers or an FPO, a few common crops, and nearby buyers. Starting on a small scale makes it possible to check whether supply can meet pooled demand and whether collection and delivery are practical before expanding to more locations or produce.

### Potential Challenges and Risks

- **Supply and quality may vary:** Farmers may not have the requested quantity, or produce may differ in freshness and quality.
- **Orders may not pool reliably:** There may not be enough nearby buyers requesting the same produce at the same time.
- **Delivery may be costly or delayed:** Long distances, small orders, and limited transport could reduce the benefit of pooling.
- **Farmers and buyers may be slow to adopt the platform:** Some users may have limited internet access or prefer familiar ways of buying and selling.
- **Prices and payments may cause disputes:** Market prices can change, and users need clear information about product quality, delivery fees, and payment status.
- **The service must cover its operating costs:** If order handling and delivery cost more than the platform earns, it may be difficult to sustain.

### Strategies to Address the Challenges

The pilot should work with an FPO or local farmer group to confirm supply and agree on basic quality standards before orders are accepted. The platform can set a cutoff time for pooled orders and notify buyers if the requested quantity cannot be fulfilled. If a pooled order is too small, it can be rescheduled or offered with the delivery cost shown clearly.

To make delivery practical, the pilot can use nearby collection points and coordinate with local transport providers. The platform should show farmers and buyers the agreed produce quantity, price, delivery fee, and order status. Simple, multilingual screens and assisted onboarding through FPO staff can help users who are less familiar with digital services.

Viability should be measured during the pilot by comparing farmers’ net earnings and buyers’ total cost with their usual way of trading, along with delivery time, fulfilled orders, and unsold produce. A transparent service fee or bulk-buyer subscription could help cover operating costs, provided the pilot shows that the platform remains worthwhile for both farmers and buyers.

## Impact and Benefits:

### Potential Impact on the Target Audience

The main target audience is farmers and Farmer Producer Organizations (FPOs), with local collection hubs supporting the process. By pooling orders from nearby buyers, the platform can help FPOs coordinate member supply, identify demand, and organize collection and delivery. Farmers could gain access to more buyers and clearer information about quantities, prices, and delivery arrangements.

Consumers, retailers, restaurants, and other bulk buyers could use the platform to find local produce and place combined orders. Collection hubs could help organize produce from several farmers before it is delivered. The actual impact would depend on local participation, reliable supply, and whether pooled delivery is practical.

### Benefits of the Solution

- **Economic:** Direct connections with buyers may help farmers retain a larger share of the selling price. Buyers can see prices and delivery fees before confirming an order. Pooling orders may also make transport more efficient for FPOs and hubs.
- **Social:** The platform can give farmers and buyers clearer information about demand, prices, and order status. It can support cooperation among FPO members and help smaller producers reach buyers they might not serve individually.
- **Environmental:** Coordinating nearby orders and deliveries may reduce avoidable trips. Better matching between demand and supply may also help prevent some produce from remaining unsold. These benefits depend on effective planning and should be measured during a pilot.
- **Operational:** FPOs and hubs can use order and supply records to plan collection, manage quantities, and understand which produce buyers request most often.

## Research and References

1. e-NAM — National Agriculture Market — Online agricultural trading and price discovery.
2. e-NAM information for FPOs — FPO produce aggregation and trading.
3. e-NAM registration and logistics information — FPO registration and logistics support.
4. FPO scheme and guidelines — SFAC — Government information on Farmer Producer Organizations.
5. Daily mandi prices — Open Government Data Platform — Wholesale price data for market comparisons.
6. Post-harvest losses study — MoFPI/NABCONS — Government summary of research on post-harvest losses.

    ### THANK YOU
   
