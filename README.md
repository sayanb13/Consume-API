Using this extension, we will see how to get data from an API. This extension will create a tab with name "Sayan" in Stores-> Settings -> Configuration.

![system-config](https://user-images.githubusercontent.com/39675303/120110725-4e68b800-c18c-11eb-850b-e5dc15a44ae3.PNG)

After clicking on this tab, few field will be displayed which are required.

![consume-api-config](https://user-images.githubusercontent.com/39675303/120111432-91785a80-c18f-11eb-8bac-dc688bdf3fb1.PNG)

Here if **Enable Http Auth** is enabled then you will have to provide the required details to create authorization token and use it for accessing the api.

In this section you will see two options in **Auth details used for**
1. API
2. Magento Admin

Based on the selection between above options, required fields will be displayed.
After Providing all the details in configuration section, save it and clear the cache. For checking the output of the API data on frontend, please write the below url in the browser and hit: http://[Your_Magento_Base_Url]/consumeapi/index/index .
