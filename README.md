# A static website

This is a simple static website, with an html file, a css file and a javascript file. 

You could host this website directly in a storage account in Azure. 

In short:
 - sign-in to the https://portal.azure.com/
 - create a storage account
 - in the storage account, create a container named $web
 - upload the static files from this repo to the $web container
 - navigate to the storage account, and then to 'Static website' to find the generated url
 - example: https://storagestaticwebsite123.z6.web.core.windows.net/

For more info: https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website-how-to
