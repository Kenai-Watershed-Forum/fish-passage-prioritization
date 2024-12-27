The R data import function can't handle non-UTF-8 characters. That includes things like ’ as opposed to ' (very subtle difference).
Similarly, ” as opposed to " (again very subtle)
These will need to be manually removed from the data source csv files. Simply using ctrl + h to open up the find and replace tool and replace all of the wrong symbols and save the csv. 