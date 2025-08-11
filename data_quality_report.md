| Column             | DataType   |   MissingCount |   MissingPercent |   UniqueValues | SampleValues                                                             |
|:-------------------|:-----------|---------------:|-----------------:|---------------:|:-------------------------------------------------------------------------|
| order_id           | object     |              0 |                0 |          25000 | ['#HLWTRIGAJB0RFL' '#9LMWG6T6H0IPE0' '#Q6J5C5621SSE5V' '#J145DOUKB5RVBN' |
|                    |            |                |                  |                |  '#7ZXNMSUU22AK4J']                                                      |
| customer_id        | object     |              0 |                0 |          25000 | ['A86556872001' '0A9218115AAA' '8A5A09200074' '97602786977A'             |
|                    |            |                |                  |                |  '744297746010']                                                         |
| product_id         | object     |              0 |                0 |          25000 | ['6Q3V14RXRF' '33MRMEM3WN' 'E674NZH16V' 'ETMIXJHFAT' '5BYOWYYY5P']       |
| product_name       | object     |              0 |                0 |            100 | ['Huggies Rompers' 'Gerber Blankets' 'Fossil Jeans' "Carter's Rompers"   |
|                    |            |                |                  |                |  'Adidas Sneakers']                                                      |
| main_category      | object     |              0 |                0 |              8 | ['baby' 'Baby' 'Men' 'Kids' 'Women']                                     |
| sub_category       | object     |              0 |                0 |             32 | ['Rompers' 'Blankets' 'Jeans' 'Sneakers' 'Shoes']                        |
| brand              | object     |           1250 |                5 |             17 | ['Huggies' 'Gerber' 'Fossil' "Carter's" 'Adidas']                        |
| price              | float64    |            250 |                1 |          16576 | [118.62  26.84 219.38  12.05 145.36]                                     |
| quantity           | int64      |              0 |                0 |              3 | [1 2 3]                                                                  |
| discount_percent   | int64      |              0 |                0 |              6 | [10 15 25  0  5]                                                         |
| final_price        | float64    |              0 |                0 |          20151 | [106.76  22.81 329.07  12.05 130.82]                                     |
| payment_method     | object     |           1250 |                5 |              4 | ['PayPal' 'Gift Card' 'Credit Card' 'Cash on Delivery']                  |
| review_rating      | int64      |              0 |                0 |              5 | [3 2 4 5 1]                                                              |
| order_date         | object     |              0 |                0 |            365 | ['2024-09-10' '2025-06-25' '2025-01-08' '2024-08-28' '2024-11-12']       |
| delivery_days      | float64    |            250 |                1 |              9 | [5. 8. 3. 1. 4.]                                                         |
| is_returned        | int64      |              0 |                0 |              2 | [0 1]                                                                    |
| region             | object     |           1250 |                5 |              4 | ['Midwest' 'West' 'Northeast' 'South']                                   |
| customer_age_group | object     |           1250 |                5 |              5 | ['25-34' '35-44' '45-54' '55+' '18-24']                                  |
| device_type        | object     |           1250 |                5 |              3 | ['Mobile' 'App' 'Desktop']                                               |