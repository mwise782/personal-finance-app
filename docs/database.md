# Database Documentation
## Tables
### User
#### Overview
Contains users

#### Columns
##### userId
###### Description
Autoincrementing ID column.

##### userUUID
###### Description
Unique ID that can be publicly exposed.

##### displayName
###### Description
Display name of the user.

##### email
###### Description
Email address of the user.

### Account
#### Overview
Contains user accounts.

#### Columns
##### accountId
###### Description
Autoincrementing ID column.

##### accountUUID
###### Description
Unique ID that can be publicly exposed.

##### userId
###### Description
ID of the owning user of the account.

##### currencyId
###### Description
ID of the currency of the account.

##### name
###### Description
Name of the account.

### Transaction
#### Overview
Contains account transactions.

#### Columns
##### transactionId
###### Description
Autoincrementing ID column.

##### transactionUUID
###### Description
Unique ID that can be publicly exposed.

##### accountId
###### Description
ID of account to which the transaction belongs.

##### dateId
##### Description
ID of the date of the transaction.

##### categoryId
###### Description
ID of the category of the transaction.

##### description
###### Description
Description of the transaction.

##### amount
###### Description
Value of the transaction.