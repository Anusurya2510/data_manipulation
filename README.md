# data_manipulation
demonstrates various data manipulation techniques using Python, primarily focusing on Pandas, NumPy, and related libraries for data analysis and processing.

## Prerequisites

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- pymongo (for MongoDB operations)
- requests (for API operations)

## Features

### Basic Data Structures
- Pandas Series and DataFrame operations
- NumPy array manipulations
- Data type conversions and transformations

### Data Loading Capabilities
- CSV files (including compressed files)
- Excel files (multiple sheets)
- JSON data (including nested structures)
- API data fetching
- MongoDB integration

### Core Operations
- Sorting and filtering
- Function application (apply, map, applymap)
- Grouping and aggregation
- Pivot tables and crosstabs
- Missing data handling
- Duplicate management

### Advanced Features
- DataFrame merging and joining
- Data concatenation
- Reshaping operations
- Statistical analysis
- Outlier detection
- Data normalization

### Time Series Analysis
- DateTime handling
- Time-based indexing
- Resampling and aggregation
- Rolling windows
- Time shifts and differences

## Installation

1. Clone the repository:
```bash
git clone 
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn pymongo requests
```


## Data Loading

The project supports multiple data loading methods:

### File-based Loading
- CSV files with custom delimiters and data types
- Compressed CSV files
- Excel files with multiple sheet handling
- JSON files with nested structure support

### API Integration
- Basic GET requests
- Pagination handling
- Authentication support
- Error handling

### Database Connection
- MongoDB integration
- Cursor to DataFrame conversion

## Core Operations

### Data Cleaning
- Missing value detection and handling
- Duplicate removal
- Outlier detection and management
- Data type consistency checks

### Data Transformation
- Custom function application
- Column manipulation
- Data normalization
- Statistical transformations

## Advanced Features

### Merging and Joining
- Inner, outer, left, and right joins
- Index-based joining
- Concatenation operations

### Reshaping
- Pivot tables
- Melting operations
- Stacking and unstacking

### Statistical Analysis
- Descriptive statistics
- Correlation analysis
- Distribution analysis
- Aggregation functions

## Time Series Analysis

Time series is a sequence of data points collected or recorded at successive points in time, often at uniform intervals (such as hourly, daily, monthly, or yearly). The order of the data points matters, and analyzing how the data changes over time is often a central focus.

### Key Characteristics

#### Temporal Ordering
- Data is ordered by time
- Sequence of data points is crucial for analysis
- Maintains chronological integrity

#### Frequency Types
Time series data can be recorded at various intervals:
- Hourly: Sensor readings from a machine every hour
- Daily: Stock prices at the end of each trading day
- Monthly: Monthly sales data for a retail store
- Yearly: Annual revenue figures

#### Patterns and Trends
- **Trends**: Long-term upward or downward movements in the data
- **Seasonality**: Recurring patterns over time
- **Cyclical Patterns**: Non-seasonal variations due to other factors

### Best Practices

1. **Data Preparation**
   - Convert timestamps to appropriate timezone
   - Handle missing values appropriately
   - Ensure consistent frequency

2. **Analysis Approach**
   - Decompose series into trend, seasonal, and residual components
   - Consider appropriate window sizes for rolling calculations
   - Account for seasonality in analysis

3. **Performance Optimization**
   - Use appropriate date indexing
   - Consider data volume when selecting analysis methods
   - Optimize memory usage for large datasets


### Window Operations
- Rolling windows
- Expanding windows
- Time shifts
- Difference calculations
