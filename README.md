# delta_lake_pyspark

## create new lakehouse in microsoft fabric (either free tier or pro licence)

Once Lake house is created, create new workspace.

time to add csv file by uploading from desktop.

![New file upload](https://github.com/kunalpatade92/delta_lake_pyspark/blob/main/add_new_file.jpg)

## Create Delta tables
You can save the DataFrame as a Delta table by using the saveAsTable method. Delta Lake supports the creation of both managed and external tables:

Managed : Delta tables benefit from higher performance, as Fabric manages both the schema metadata and the data files.
External tables : allow you to store data externally, with the metadata managed by Fabric.



![spark data froma to read](https://github.com/kunalpatade92/delta_lake_pyspark/blob/main/read_data_into_dataframe.jpg)


![write data from dataframe to table](https://github.com/kunalpatade92/delta_lake_pyspark/blob/main/write_df_to_table.jpg)


![Managed_prduct table is created](https://github.com/kunalpatade92/delta_lake_pyspark/blob/main/managed_product_table.jpg)






