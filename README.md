# TASK-3
 Event Grid: Auto-index Blob Metadata into  Cosmos (Event Grid + Functions + Cosmos)

This project automatically adds new files (blobs) from an Azure Storage container into Cosmos DB.
When a file is uploaded to the documents folder, Event Grid triggers a function.
The function reads file info and content, and saves it in Cosmos DB.
