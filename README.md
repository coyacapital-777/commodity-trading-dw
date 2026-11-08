# commodity-trading-Data Warehouse (guide to commercial trading analytics)
Supply Chain Analyst portfolio — Commodity Trading Data Warehouse: price realization and market analytics (MDKA case)

Commodity Trading Data Warehouse
Supply Chain Analyst Portfolio — Commodity Trading (Mining Case: MDKA)

!CI

About This Portfolio
I am a Supply Chain Analyst specializing in Commodity Trading, building an end-to-end data pipeline to support commercial decision-making and risk management in mining commodity trading operations.

This portfolio demonstrates how a Supply Chain Analyst can:

Translate the commodity trade lifecycle (deal, quotation period, pricing, and settlement) into an analytical data model.
Build a data warehouse from raw CTRM exports into business-ready analytical marts.
Develop actionable trading desk KPIs, including price realization, pricing basis, and contract fulfillment.
Implement business-aware data quality tests, ensuring that unpriced transactions are not treated as zero, quotation periods are valid, and financial sign conventions are consistent.
This is not a traditional manufacturing supply chain analytics portfolio focused on OTIF, MRP, or inventory turnover.

This is not a generic Data Engineering project.

It demonstrates the intersection of supply chain analytics, commodity trading operations, and data warehousing.

Business Problem
MDKA (Merdeka Copper Gold) operates in the mining industry, where commodity sales are influenced by global benchmark prices.

Key commodity benchmarks include:

Gold: LBMA Gold Price PM
Copper: LME Copper Cash
However, the final realized price of each trade does not necessarily equal the benchmark price.

Several commercial factors influence the final transaction value:

Quotation Period (QP): The average benchmark price over a contractually defined pricing period.
Hedging: A portion of the trading volume may already be locked at a predetermined price.
Premium/Discount: Commercial adjustments based on buyer agreements and market conditions.
Foreign Exchange (FX): Certain contracts, costs, and settlements may involve currencies other than USD.
The data warehouse is designed to answer four critical business questions:

Price Realization: How does the realized selling price of each trade compare with its corresponding market benchmark?
Buyer Profitability: Which buyer generates the highest commercial premium?
Contract Fulfillment: Is the annual GSPA commitment with ANTAM of 3 metric tons being fulfilled?
Unpriced Exposure: Which trades remain unpriced, and what is the outstanding pricing exposure?
This project builds an end-to-end analytical pipeline that transforms raw trading data into actionable insights through a structured data warehouse and a Metabase dashboard.
