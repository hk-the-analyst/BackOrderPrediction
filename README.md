# BackOrderPrediction
Back Order Prediction In Supply Chain Management
Objective
Predicing Back Order in Supply Chain Management.

What is Back Order?
Back Order Prediction in supply chain management is the estimation of the likelihood that a product will be unavailable when a customer places an order. It involves analyzing historical sales data, inventory levels, lead times, and customer demand patterns to forecast the probability of a backorder situation. By utilizing statistical models or machine learning algorithms, companies can anticipate stockouts, manage customer expectations, optimize inventory, and enhance supply chain efficiency.

Accurate predictions enable proactive actions such as adjusting inventory, expediting deliveries, or finding alternative suppliers, leading to improved customer satisfaction and reduced lost sales.

Data Dictionary
Sku (Categorical)     Random ID for the product
​
national_inv          Current inventory level for the part
​
lead_time              Transit time for product (if available)
​
in_transit_qty         Amount of product in transit from source
​
forecast_3_month      Forecast sales for the next 3 months
​
forecast_6_month      Forecast sales for the next 6 months
​
forecast_9_month      Forecast sales for the next 9 months
​
sales_1_month         Sales quantity for the prior 1 month time period
​
sales_3_month         Sales quantity for the prior 3 month time period
​
sales_6_month         Sales quantity for the prior 6 month time period
​
sales_9_month         Sales quantity for the prior 9 month time period
​
min_bank             Minimum recommend amount to stock
​
potential_issue      Source issue for part identified
​
pieces_past_due      Parts overdue from source
​
perf_6_month_avg     Source performance for prior 6 month period
​
perf_12_month_avg    Source performance for prior 12 month period
​
local_bo_qty         Amount of stock orders overdue
​
Deck_risk:          This column is a flag or indicator that identifies the deck risk associated with a particular SKU. Deck risk                     typically refers to the risk of potential disruptions or issues in the supply chain, such as delays in                           shipping, production problems, or other challenges that may impact the availability of the product. It                           highlights the possibility of supply chain-related risks that could affect the availability of the SKU.
​
OE_constraint:       The OE_constraint column is a flag or indicator that represents any original equipment (OE) constraints                          associated with a SKU. Original equipment constraints are limitations or restrictions that arise from the                        use of specific parts or components in the manufacturing or assembly of a product. It indicates if there                        are any constraints or limitations on the availability or procurement of the SKU due to factors such as                          limited supplier options, specialized manufacturing requirements, or exclusive agreements.
​
PPAP_risk:          PPAP stands for Production Part Approval Process, which is a standardized process in the automotive industry                     (and some other industries) for ensuring the quality and conformity of parts used in production. The                             PPAP_risk column serves as a flag or indicator that indicates the level of risk associated with the                             production part approval process for a particular SKU. It may reflect the risk of encountering challenges or                     issues in the approval process, which could impact the timely availability of the SKU.
​
Stop_auto_buy:      The stop_auto_buy column is a flag or indicator that suggests whether there is a need to halt or stop the                       automatic purchasing or procurement of a SKU. It may be triggered by certain circumstances such as changes                       in demand, quality issues, pricing changes, or other factors that require a reevaluation of the automatic                       procurement process. This flag helps in identifying situations where the automated procurement system needs                     to be adjusted or temporarily halted.
​
Rev_stop:           The rev_stop column is a flag or indicator that identifies the presence of any revision stops associated                         with a SKU. Revision stops typically occur when there are changes or revisions being made to a product, such                     as design modifications, upgrades, or improvements. It indicates whether there are any temporary halts or                       stops in the production or procurement process due to ongoing revisions. These stops allow for necessary                         adjustments to be made before resuming production or procurement.
​
​
