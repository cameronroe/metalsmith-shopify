# metalsmith-shopify
Why push every change to a server-rendered theme? Cache Shopify data and build themes with Metalsmith.

- Create a model of all Shopify objects that can be used in templates
- Potentially add that template data to files with the shopify flag
- Fetch data endpoints from Shopify, determine all the data that needs to be collected, for example you may need to download static assets.
  Here you'll need to download and save those assets to an assets folder (this should be specified). After you've got your data and assets
  collected in the metalsmith site on data objects, you'll be able to access that locally and develop your theme.