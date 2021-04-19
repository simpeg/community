# Upload Tutorial Data for SimPEG

If you have permission to access the cloud storage repository,
uploading data and linking to tutorials in documentation is done as follows:

1. **Access the google cloud** using the following URL https://console.cloud.google.com/ . If you have access, you should be taken to a Google Cloud Platform landing page.

2. **Finding storage bucket:** In the *Resources* panel, selected *Storage*
   --> From the list of storage locations, select the *simpeg* storage bucket
   --> Within this bucket, go to the *doc-assets* directory
   
3. **Uploading files:** Drag and drop the file into this directory. We expect that for the most part files are compressed to *tar.gz*

4. **Setting permissions:** For the file you have just uploaded, open the *object overflow menu*. This is the 'three dots' on the right side of the screen for the file.
   --> Go to *Edit permissions*
   --> Click *Add entry* and set *Entity* = Public, *Name* = allUsers and *Access* = Reader for the new entity
   --> Click *SAVE*

5. **URL for download link:** Click *COPY URL* to copy the downloable link to clipboard.
