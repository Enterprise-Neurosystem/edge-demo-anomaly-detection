# Managers 

## preprocess_data_manager

Prepares a timeseries data point for graphing (data collected from synthesize_data_manager). The class uses a generator that it receives from a data source. A timeseries data point is received
and the method, process_point() is used to process the point. When the point has been processed, it yields a message that contains json data that will be consumed.


## synthesize_data_manager

Collects data from a csv ([here](../static)) and periodically yields timeseries data points. 
