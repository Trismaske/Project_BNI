# Project_BNI

This project was designed to locate sites that are close enough to share a fiber location which will aid in prioritising sites that require upgrades.
_________________________________________________________________________________________________________________________________________

### [Version 3 (Final Notebook)](https://gitlab.com/ShezBasha/project_bni/tree/master/Version%203)

#### • [Data Quality Reports](https://gitlab.com/ShezBasha/project_bni/tree/master/Data%20Quality%20Reports)

##### • Configuration File user Guide 
> The purpose of this file is to provide options for configuration of the notebook Many instances in the notebook requres a form of user input to return what the user requires.
>> This will aid in :
>> • Selecting a data source from which to import
>>
>> • Transforning ang address data set into requited dataframe format
>>
>> • Max distance neighbours selection
>>
>> • Map visualisation 

____________________________________________________________________________________________________________________________________

#### Previous versions  
>* [Version 1](https://gitlab.com/ShezBasha/project_bni/tree/master/Version%201)
> • This is the very first version of calculating the max distance neighbours.
>
>>  Version 1.2 was an attempt to improve the functionality and user-friendliness of the notebook by making it interactive.

>* [Version 2](https://gitlab.com/ShezBasha/project_bni/tree/master/Version%202)
> •This notebook contains the preprocessing and formatting of the table as well as the functions for Max distance neighbours and Same   > block Neighbours, where same block neighbours is a limited to sites with in 100m (0.1km).
>
>> Version 2.1 is a configuration file which is necessary for this notebook to run as it formats the table based on the configurations in the configuration file.
>>* [Input/Output](https://gitlab.com/ShezBasha/project_bni/blob/master/Version%202/input_output.ipynb)
>>•Input & Output functions which allow importing/exporting of data according to the users' preference.
>>  
>>* [Address Formatting](https://gitlab.com/ShezBasha/project_bni/blob/master/Version%202/Address_formatting_Table_1.ipynb)
>>• Two notebooks used to formate BigQuery tables into the correct schema, which then uses an API to fill in the missing details of the >>addresses.
>>
>>* [Distance calculator](https://gitlab.com/ShezBasha/project_bni/blob/master/Version%202/Format_and_Neighbours_version_2.ipynb)
>>• This notebooks function is to find sites within a certain distance, including finding sites on the same block.
>>
>> • Dataset has been split into each unique city and a dictionary is created where each city has distances from one site to every other >>   site in that respective City. The distances are computed once then stored in a large dictionary.

__________________________________________________________________________________________________________________________________________






