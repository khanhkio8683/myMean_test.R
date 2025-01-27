# myMean_test.R
Evaluation and results of testing the myMean function in R.
# Data for testing
assignment2 <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22)

# Function to calculate the mean
myMean <- function(assignment2) {
  return(sum(assignment2) / length(assignment2))
}

# Test the function and print the result
result <- myMean(assignment2)
print(paste("The mean of assignment2 is:", result))
