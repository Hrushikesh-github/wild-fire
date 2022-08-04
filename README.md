# wild-fire

All the code has been taken from https://github.com/google-research/google-research/tree/master/simulation_research/next_day_wildfire_spread
I'm not the original author.

Temporary repository 


CHANGES MADE:
1. In ee_utils.py added LST and LULC source, band names
2. Changed the function  _get_time_slices   in export_ee_data.py by adding a line for LST and appending it in return statement.
3. For LuLC I made the following changes in _export_dataset  in export_ee_data.py and updated it in the same function in image_list list variable :
4. Added LuLC and LST in the function _get_all_feature_bands() in export_ee_data.py
5. Added LuLC and LST image collections in _get_all_image_collections() in export_ee_data.py
 
