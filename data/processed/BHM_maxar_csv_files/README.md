Example csv files generated by the data processing pipeline, i.e. by running the Python script `regrid_maxar.py` in `src/data`. Note that this script will by default place the csv files in a different location (on the S3 data bucket), here we just provide examples.

The csv files contain the following columns:
* file_name: name of file
* left: left x co-ord
* right: right x co-ord
* top: top y co-ord
* bottom: bottom y co-ord
* min_value: minimum height value (if applicable)
* max_value: maximum height value (if applicable)
* pixel_horiz: number of pixels in x dimension
* pixel_vert: number of pixels in y dimension
* number_of_nan: number of NaN values
