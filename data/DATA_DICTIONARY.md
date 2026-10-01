# Dataset inventory

## `batch_outcomes.csv`

Rows: 3825 · Columns: 14

| Field | |
|---|---|
| `BatchID` | |
| `ProductID` | |
| `Category` | |
| `Status` | |
| `QtyPurchased` | |
| `QtySold` | |
| `QtyWasted` | |
| `WastedPct` | |
| `CloseDate` | |
| `Revenue_CLP` | |
| `Revenue_USD` | |
| `BatchCost_CLP` | |
| `GrossProfit_CLP` | |
| `GrossProfit_USD` | |

## `products.csv`

Rows: 128 · Columns: 10

| Field | |
|---|---|
| `ProductID` | |
| `Product` | |
| `Category` | |
| `SaleUnit` | |
| `PriceType` | |
| `Essential` | |
| `PeakSeason` | |
| `SalePrice_CLP` | |
| `SalePrice_USD` | |
| `CurrentStock` | |

## `purchases.csv`

Rows: 3825 · Columns: 16

| Field | |
|---|---|
| `BatchID` | |
| `ProductID` | |
| `Product` | |
| `Category` | |
| `SupplierRole` | |
| `SupplierID` | |
| `SupplierName` | |
| `PurchaseDate` | |
| `Quantity` | |
| `Unit` | |
| `UnitCost_CLP` | |
| `BatchCost_CLP` | |
| `BatchCost_USD` | |
| `ExpiryDate` | |
| `ExpiryType` | |
| `Season` | |

## `suppliers.csv`

Rows: 22 · Columns: 7

| Field | |
|---|---|
| `SupplierID` | |
| `SupplierName` | |
| `Address` | |
| `Phone` | |
| `Email` | |
| `HasDelivery` | |
| `PickupInStore` | |

## `supply_links.csv`

Rows: 256 · Columns: 13

| Field | |
|---|---|
| `SupplyID` | |
| `ProductID` | |
| `Product` | |
| `Category` | |
| `SupplierRole` | |
| `SupplierID` | |
| `SupplierName` | |
| `PurchasePrice_CLP` | |
| `PurchasePrice_USD` | |
| `PriceType` | |
| `PurchaseUnit` | |
| `LeadTime_Days` | |
| `HasDelivery` | |

