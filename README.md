# Predictive_Booking_Optimizer
## Data Analysis and Predictive Modeling Report:

1. Introduction:
This report provides an overview of the data analysis and predictive modeling
performed on the dataset provided. The dataset contains information about bookings,
including various features such as booking slot, average order value, and the
occurrence of no-shows etc.

2. Data Preprocessing & EDA:
The dataset is loaded from the provided CSV file and explored using pandas functions.
Data current shape= [ 181859 rows × 73 columns ]
Initial data exploration included displaying the first few rows, obtaining information about
the dataset, and checking for missing values.
Basic statistics of the dataset are calculated to gain insights into the numerical features.
Missing values are handled by filling them with the mean of their respective columns.
The distribution of the 'ns' column (indicating no-shows) and the 'bookingslot' feature
are analyzed to understand their frequency distribution. And we got to know that out of
25 features, only one that is ‘booking slot’ types are object .

3. Data Visualization:
Visualization techniques, including count plots and heatmaps, are utilized to visualize
the distribution of the target variable (no-shows) and explore relationships between
features.
Boxplots are created to identify potential outliers in numerical features.Outlier is an
observation in a given dataset that lies far from the rest of the observations and the
data had some outlier.
file:///home/vishal/Documents/UC_Interview/images/Screenshot%20from%202024-03-18%2018-17-26.png

