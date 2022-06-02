DataLabeling(file_name, start_idx=2, machine='Windows')

*file_name* : Path directory to spreadsheet
*start_idx* : Takes positive integer values. Loads urls starting at the i-th row
*machine (optional)* : Takes values 'Windows' and 'Mac'. If applicable, tabs will automatically close before a new one is opened.

# Note
In the event of a KeyError: "There is no item named '[Content_Types].xml' in the archive", the current file is corrupted and a new copy should be used.
