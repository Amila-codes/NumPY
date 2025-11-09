# Standard Deviation and Correlation in NumPy

## Explore the baseball data

Because the mean and median are so far apart, you decide to complain to the MLB. They find the error and send the corrected data over to you. It's again available as a 2D NumPy array np_baseball, with three columns.

The Python script in the editor already includes code to print out informative messages with the different summary statistics and numpy is already loaded as np. Can you finish the job? np_baseball is available.

---

## Instructions

The code to print out the mean height is already included. Complete the code for the median height.

Use np.std() on the first column of np_baseball to calculate stddev.

Do big players tend to be heavier? Use np.corrcoef() to store the correlation between the first and second column of np_baseball in corr.

---

## Example code
```python
avg = np.mean(np_baseball[:,0])
print("Average: " + str(avg))

# Print median height
med = np.median(np_baseball[:,0])
print("Median: " + str(med))

# Print out the standard deviation on height
stddev = np.std(np_baseball[:,0])
print("Standard Deviation: " + str(stddev))

# Print out correlation between first and second column
corr = np.corrcoef(np_baseball[:,0], np_baseball[:,1])
print("Correlation: " + str(corr))
```
---

## Results


Average: 73.6896551724138

Median: 74.0

Standard Deviation: 2.312791881046546

Correlation: [[1.         0.53153932]
     [0.53153932 1.        ]]
