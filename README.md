### Overview
This is a Shopify Theme App extension project which adds the functionality to show a Shopify shop in different languages.
It uses Google's translation API to translate the Shopify store.

### Installation steps:
- Please update the dev_store_url in the shopify.app.toml file to your own store
- Run "npm run dev" command

Once run successfully, a preview URL will be provided which will take the user to the store admin panel.
If the app is not installed, it will ask the necessary permission to the store owner.
Once the app is installed, the user will be navigated to the store admin panel on the left.

On the left, under "Sales channels" section click "Online Store". From the Online Store menu click "Themes".
In the Themes page, click "Customize" to customize the theme.
In the "Header" section, click "Add block". In the pop-up menu, Under the "App Blocks" section, select this exention with name "Translation".
Save the change.

Now the user should be able to see the Google powered language selection menu on the header.
