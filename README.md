## Problem-Solving Approach

**Step 1:** Load the data using pandas.

**Step 2:** Data Preprocessing
* Dropping null values, duplicates, changing text data to lower case.
* Removing unnecessary columns.

**Step 3:** Calculating other important parameters
* TimeDiff: How time sensitive or urgent a particular order is.

**Step 4:** Applying clustering algorithm
* I clustered the orders based on the distance and its time constraint or urgency. Each cluster is executed first based on the distance, so that trips are efficient as well as the deliveries are done on time.

**Step 5:** Applying all the constraints
* For each cluster formed firstly I checked the weight constraint.
* Secondly if the clusters changes or the weight constraint gets exceeded then a new trip will get started.
* In the last trip( when left) the rest of the deliveries are added in that particular trip following all constrains.

**Step 6:** The trips are sorted on the basis of the distance covered.

**Step 7:** The final output is returned.

Author: [@anujsahani01](https://github.com/anujsahani01)
