| 编号 | 坏味道名称 | 腐烂点 |
|:-------------|:---------------|:-------------|
| $1 | Data Class | `CartItem` |
| $2 | Repeated Switches | `CheckInSystem and Employee` |
| $2 | Feature Envy | `CheckInSystem switch should in Employee` |
| $3 | Long Method | `Customer.statement()` |
| $3 | Feature Envy | `get thisAmount and frequentRenterPoints should in rental` |
| $4 | Shotgun Survey | `sendChangeNotification() used in two different class` |
| $5 | Loops | `CollectionCalculate.filterEvenNumber()` |
| $6 | Refused Request | `Goat and Cow only implement milk(), Chicken and Duck only implement layEggs() ` |
| $7 | Feature Envy | `findUser should in User`|
| $8 | Feature Envy  | `ConfigSetting should be in application` |
| $9 | Middle Man  | `useless RoomChecker` |
| $10 | Long Method  | `OrderReceipt.printReceipt()` |
| $11 | Speculative Generality  | `HumanAble` |
| $12 | Mysterious Name | `p` |
| $13 | Comments  |  |
| $14 | Temporary Field  | `productBatchesToExpired` |
| $15 | Mutable Data  | `totalPrice` |
| $16 | Data Clumps  | `buyerName buyerPhoneNumber buyerAddress` |
| $17 | Insider Trading  | `Department and Person` |
| $18 | Alternative Classes With Different Interfaces, Duplicate Code  | `Two Printer, AirwayBill.to(), AirwayBill.from() Receipt.getReceiptString()-customerInformation` |
| $19 | Long Method  | `compairResult` |
| $20 | Primitive Obsession  | `DeliveryManager` |
| $21 | Message Chains  | `DiseaseControlCenter.hasPatient` |
| $22 | Insider Trading  | `License and Motorist` |
| $22 | Feature Envy  | `Motorist.getRiskFactor` |
| $23 | Alternative Classes With Different Interfaces | `IPChecker and IPValidator` |
| $24 | Divergent Change | `Account.toXml Account.toText` |

