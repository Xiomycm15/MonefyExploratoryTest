

## Test Scenario: Category component for unsubscriber user

| **Test Charter 1**| Add new category for an unsubscriber user|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|60 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that user is not able to add a new category because it is not subscribed. User should land on Monefy Pro Screen|
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| Medium, because this function is not used so frequently, but also can be used when user has recently download the application|
|**Activities**|- Try to add a new category  for Expense section <br/>- Try to add a new category  for Income section  <br/>- Select any category and try to change icon <br/> - Select any category and edit category name with same icon as an unsubscriber user <br/>- Select any category and edit category name with different icon as an unsubscriber user <br/>- Delete any category as an usubscriber user and cancel <br/>- Delete any category as an usubscriber user and accept <br/>- Select any category and disable it <br/>- Select a disable category and enable it <br/>- Add new incomes for two different categories and then merged them 
**Oracle Notes**|- Unsubscriber user won't be able to add a new category or change icon<br/>- Unsubscriber user will be able to edit category name <br/>- Unsubscriber user will be able to merge category as much as he wants| 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same test for a variety of the mostly OS in multiple devices  <br/>- Perform same test cases for a subscriber user| 

## Test Scenario: Accounts component for unsubscriber user

| **Test Charter 2**| Add new account for an unsubscriber user|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|90 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that user is able to add a new account even when it is not subscribed. User should be able to add all kind of accounts like debit and credit cards, cash entry, savings, deposits, etc.|
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| High, because this function is used so frequently since user could adquire new entries at any moment|
|**Activities**|- Add a new account Included Balance on <br/>- Add new account Included Balance off <br/>- Try to add new account with Exchange rate <br/>- Edit existing account with included balance on to off <br/>- Edit existing account with included balance off to on <br/>- Edit existing account with new currency <br/>- Edit existing account with new initial balance date <br/>- Edit existing account with new icon <br/>- Disable an account <br/>- Merge two existing accounts <br/>- Enable an account <br/>- Delete an account <br/>- Edit Initial Account Balance <br/>- Try to transfer between accounts when user just have on account <br/>- Try to transfer between accounts when user have more than two accounts <br/>- Try to transfer between two account with amount equal to zero
**Oracle Notes**|- Unsubscriber user won't be able to edit currency or exchange rate <br/>- Unsubscriber user will be able to edit account name, initial balance date, initial account balance <br/>- Unsubscriber user will be able to disable, enable, delete and merge accounts  <br/>-User won't be able to see merge option when there is just one account <br/>- User won't be able to transfer money if user just have one account or doesn't input any amount| 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same testing for a variety of the mostly OS in multiple devices <br/>- Perform same test cases for a subscriber user| 


## Test Scenario: Currency component for unsubscriber user

| **Test Charter 3**| Currency component access for unsubscriber user|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|5 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that unsubscriber user is not able to access to Currency component|
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| Low, because this function will be rarely used since user won't be able to acess to this function|
|**Activities**|- Unsubscriber user won't be able to acess to the currency component at any point
**Oracle Notes**|- User will land on Monefy Pro screen everytime he tries to acess to the currency component| 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same testing for a variety of the mostly OS in multiple devices <br/>- Perform same test cases for a subscriber user| 

## Test Scenario: Balance settings component for unsubscriber user

| **Test Charter 4**|Balance Settings configurations for unsubscriber user|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|30 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that unsubscriber user is able to configurate balance settings |
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| High, because balance component section can be used with no restrictions for the unsubscriber user|
|**Activities**|- Enable Budget Mode and input a value different than zero while user is under All accounts mode <br/>- Disable Budget Mode and input a value different than zero while user is under All accounts screen <br/>- Enable Budget Mode and input a value different than zero while user is under Cash account mode <br/>- Disable Budget Mode and input a value different than zero while user is under Cash account screen <br/>- Verify Budget Mode on under screens Day, Week, Month, Year, All, Interval and Choose Date <br/>- Enable Carry Over section with Budget Mode enable. Verify behaviour under screens Day, Week, Month, Year, All, Interval and Choose Date. Validate with more than one day registered <br/>- Enable Carry Over section with Budget Mode disable. Verify behaviour under screens Day, Week, Month, Year, All, Interval and Choose Date. Validate with more than one day registered <br/>- Enable Future recurring records <br/>- Disable Future recurring records| 
**Oracle Notes**|- User will be able to enable and disable all the moods for Balance settings  component <br/>- Unsubscriber user will be able to test Budget Mode and Carry Over functionalities <br/>- Unsubscriber user won't be able to test Future recurring records functionality because it is not allowed to add recurring records | 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same testing for a variety of the mostly OS in multile devices <br/>- Perform same test cases for a subscriber user| 

## Test Scenario: General settings component for unsubscriber user

| **Test Charter 5**|General Settings configurations for unsubscriber user|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|60 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that unsubscriber user is restricted to some general settings, but it is also allowed to configured some of them|
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| High, because general settings component section can be used so frequently by the user|
|**Activities**|- Try to setup Unlock Monefy option <br/>- Try to enable dark theme <br/>- Setup multiple languages configuration <br/>- Setup multiple currencies configuration <br/>- Configurate multiple first days of week <br/>- Configurate multiple first days of month <br/>- Try to setup Passcode protection <br/>- Setup a review application <br/>- Export a file to different channels <br/>- Research and select About Monefy. Visit the next hyperlinks: monefy.me, incons8 and Privacy Policy  <br/>- Select About Monefy. Enable and Disable google analytics. Select OK <br/>- Try to setup synchronization with Google Drive <br/>- Try to setup synchronization with Dropbox <br/>- Setup Data backup <br/>- Setup Restore Data <br/>- Setup to clear data <br/>- Data Restore should show history everytime it performs it | 
**Oracle Notes**|- Currency can be change trhough the general settings but it can not be changed through Account add <br/>- The language change do not change quote Future recurring records option| 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same testing for a variety of the mostly OS in multile devices <br/>- Perform same test cases for a subscriber user| 

## Test Scenario: Monefy Mainly Screen 

| **Test Charter 6**|Monefy mainly screen validations|
|--|--|
|**Start**|26/07/2021  5:00pm|
| **Test Name** |Jeimmy Xiomara Camacho Medina|
|**Duration**|50 mins|
|**Actor**|Unsuscribed user|
| **Purpose** |To evaluate that unsubscriber user is allowed to register new incomes and new expenses|
|**Setup**|Setup an Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio. Assure that user is unsubscribed |
|**Priority**| High, because it is the most used functionality due to it is the mainly purpose of application |
|**Activities**|- Add a new income for cash entry <br/>- Add a new expense for cash entry <br/>- Add a new income for payment card <br/>- Add a new expense for  payment card <br/>- Add a new expense per each category in the chart <br/>- Deploy Balance dropdown and verify History like new expenses, new incomes, carry over, etcetera. Verify dropdown for day, week, month, year, all, interval, Choose date <br/>- Input different set of data for incomes and expenses for multiple days. Then, scroll right and left between days information <br/>- Search records by looking diiferent  expenses and incomes <br/>- Search records by looking a word not registered in the system <br/>- Validate chart behaviour when adding new expenses <br/>- Transfer button and functionality validation from one account to the same account <br/>- Transfer button and functionality validation from one account to a different account |  
**Oracle Notes**|- When user look for a word not registered in the system, "No records have been found" message is populated under inferior part of the screen. After this process, if the user tab on the screen the message change its position to the center | 
|**Variations**|- Perform same test cases under disconnected WIFI network <br/>- Perform same testing for a variety of the mostly OS in multile devices <br/>- Perform same test cases for a subscriber user| 


**

## Bugs Discovered: 

** 
| Summary | Unsubscriber user can not change currency from account component but user do it through general settings  |
|--|--|
|**Priority**| High|
|**Severity**| Medium|
|**Component**| Accounts|
|**Description**| Unsubscriber user is not able to change currency of an account, but is able to do it through general settings|
|**Environment**|  Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio|
|**Data**| Unsubscriber User|

** 
| Summary | when unsubscriber user tries to merge two accounts both balances are not adding as expected|
|--|--|
|**Priority**| High|
|**Severity**| Medium|
|**Component**| Accounts|
|**Description**| when unsubscriber user merge two accounts balances are not adding as expected. Just one of the balances is populated in the charts|
|**Environment**|  Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio|
|**Data**| Unsubscriber User|


** 
| Summary | Unsubscriber user can not change currency from account component but user do it through general settings  |
|--|--|
|**Priority**| High|
|**Severity**| Medium|
|**Component**| Accounts|
|**Description**| Unsubscriber user is not able to change currency of an account, but is able to do it through general settings|
|**Environment**|  Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio|
|**Data**| Unsubscriber User|

** 
| Summary | Language change edition does not change Future recurring records quote. It stills redacted in english language|
|--|--|
|**Priority**| Low|
|**Severity**| Low|
|**Component**| Settings|
|**Description**| Future Recurring records is not changing from language when user configures language to another one different than english|
|**Environment**|  Emulator of a google mobile pixel 2, playstore GooglePlay, resolution 1080x1920 420dpi, API 27, CPU/ABIx86, size on Disk 10GB with Android Studio|
|**Data**| Unsubscriber User|