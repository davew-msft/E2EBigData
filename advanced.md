## Setup

1. create a storage account

2. add it to your existing cluster

* spark config
* add a key-value pair separated with a space, like this:  
* `fs.azure.account.key.your_storage_account.blob.core.windows.net your_key1_value`
* here is an example:  

`fs.azure.account.key.davewdemo.blob.core.windows.net c+MMXnxfn5kT+r0uBwdNT3kVO+z1rHwVXxaAD8slWicQ0Ik0dOsPaCYHNYB7SfPJPrrWmI8uofPL/8mnci913Q==`

**Note that the above connstring WILL work.  It is my copy of the data.  Please don't hack it/delete it**

3. restart cluster

4. with Azure Storage Explorer upload 
the data folder to a container named `spark` and a folder named `data`.  HINT:  If you drag/drop the `data` folder to the `spark` container everything should work.  

5. Upload `Labs\Lab01\DataExploration.ipynb` and work the lab on your cluster once it restarts.