#install.packages("readxl")



#install.packages('writexl')
library(writexl)



# create a data frame 
data <- data.frame(player=c('A', 'B', 'C', 'D'),
                   runs=c(100, 200, 408, NA),
                   wickets=c(17, 20, NA, 5))

# import data in dataframe to an excel sheet
write_xlsx(data, "tests/write2.xlsx")