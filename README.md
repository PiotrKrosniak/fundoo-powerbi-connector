# Power BI Custom Connectors for Rapid Pro FunDoo

Custom connector to use Rapid pro endpoint for FunDoo UNICEF Project.

## Quickstart
### Instalation

1. Download the .mez file of the desired connector from this repo (.mez file).
2. Copy downloaded file to [Documents]/Power BI Desktop/Custom Connectors. 
 - (If you don't have these folders on your computer, you must create them)
3. Check the Allow any extensions to load without validation or warning in Power BI Desktop option under (File > Options > Security > Data Extensions).
4. Restart Power BI Desktop

### Getting Data

1. With Power BI Desktop open, look for the connector under Home > Get Data > Other.
2. Select the desired connector and Click “Connect” button.
3. A popup will appear to confirm if you want to connect to a third party service, confirm by clicking“Continue”.
4. Input API base URL if requested. (eg: https://rapidpro.ilhasoft.mobi/api/v2/)
5. Input the token of the organization you want to get the data for, and optionally define the time period for which the data was created that you want to get. 
 - (you can find API token in https://rapidpro.ilhasoft.mobi/org/home/ or https://rapidpro.ilhasoft.mobi/api/v2/explorer/
6. Select the items you want and click transform or load data.

<img width="833" alt="Screen Shot 2023-04-26 at 09 11 26" src="https://user-images.githubusercontent.com/6203857/234851703-d6526378-7987-434e-afef-946c100748b8.png">
