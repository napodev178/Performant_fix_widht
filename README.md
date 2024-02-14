# Performant_fix_widht
Scripts for ingest fix widht files in snowflake based on business logic

Fixed width means that each field has a certain width. When Excel reaches the designated space on the row, a new field (column) begins. 
In order to open a fixed-width file, you will need a “file layout” that shows how wide each column is.

You can create multiple fixed-width file formats. For example, you might have a fixed-width file format to use for fixed-width flat files that contain quarterly sales data and another fixed-width file format to use for fixed-width flat files that contain inventory data.
If a fixed-width file format does not already exist, you must create a fixed-width file format before you create a mapping or mapping task that uses a fixed-width flat file.
To configure a fixed-width file format, you specify the number of columns and the width, name, and datatype for each column. You can also set advanced fixed-width format properties. For example, you can specify how to handle null characters or specify the default date format for each column.

The poc is with two files

1. Providers
2. Patients
