## what is Azure Blob storage?
Azure Blob storage is Microsoft's cloud object storage service. Blob storage is designed to store large amounts of unstructured data.

Unstructured data is information that does not conform to a specific data model or description, such as text or binary data.


## Uses for blob storage include:
- Directly serving pictures or documents to a browser.
- File storage for dispersed access.
- Video and audio streaming
- Creating log files.

## advantages of Blob storage
- Low-cost, tiered storage 
- High availability 
- Consistent performance
- Capabilities for disaster recovery

## what resources does Blob storage provide?

The account for storage
The storage account's container
A container for a blob

## What are the blobs types that are supported in Azure storge?
Block blobs: they store text and binary data. Block blobs are made up of data chunks that can be controlled independently. Block blobs can store up to 190.7 TiB.

Append blobs: they are formed up of blocks like block blobs but are optimized for append operations. Append blobs are suitable for logging data from virtual machines.

Page blobs: they can hold random access files up to 8 TiB in size. Page blobs store virtual hard drive (VHD) files and act as disks for Azure virtual machines. See Overview of Azure page blobs for additional information.
