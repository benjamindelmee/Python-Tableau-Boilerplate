# Data

## 1 - PBC Folder

This folder contains the data **Provided By Client**.

These data must be stored *as it is*, without any modification.

### Naming convention

For each dataset sent by the client, **create a subfolder** with the following name:

`1-PBC/YYYYMMDD_PROVIDER_DataSetDescription/`

Where:
- `YYYYMMDD` is the **reception date**
- `PROVIDER` is the **name of the sender**
- `DataSetDescription` describes the **content of the folder**

*Why this convention ?*

We can easily track who sent what.
If we have requests, it's better to know the right person to ask.

### Rules

- **Never remove** the data sent by the client
- **Never update** the data sent by the client
- **Never work directly on** the data sent by the client. Instead **create a copy** in the folder `2-Processed`

*Why theses rules ?*

If by mistake we break the data PBC, we will have to ask twice the same data to the client, which isn't very professional...

## 2 - Processing Folder

This folder stores all the data **used or generated** during the analysis.

### Naming convention

The directory structure is up to you.

However, every data file must follow this naming convention:

- `S_filename`: TODO
- `P_filename`: TODO
- `TMP_filename`: TODO

*Why theses conventions ?*

TODO
