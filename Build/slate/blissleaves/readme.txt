@Author     Bobby Dang

The .env has been gitignored to not pass on authentication details.  After cloning this repo create a .env file and fill it in with details and values show below.

# The myshopify.com URL to your Shopify store 
SLATE_STORE=

# The API password generated from a Private App 
SLATE_PASSWORD=

# The ID of the theme you wish to upload files to 
# Go to your shopify <store_url>/admin/themes.xml to get ID
SLATE_THEME_ID=

# A list of file patterns to ignore, with each list item separated by ':' 
SLATE_IGNORE_FILES=