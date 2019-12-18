1. Download http://www.cvlibs.net/download.php?file=data_depth_selection.zip to folder X
2. Unzip "data_depth_selection.zip" (downloaded in 1) in folder X
3. Add kitti_archives_to_download.txt and datasetCreator.py to folder X
4. In folder X, run: wget -i kitti_archives_to_download.txt -P kitti_data/
5. Unzip folder in kitti_data. It can be done with the following two lines of code (directly from folder X) 
cd kitti_data
unzip "*.zip"
6. Folder X should now look like this
| /X
|---- datasetCreator.py
|---- /data_depth_selection
|---- /kitti_data
|---- kitti_archives_to_download.txt
|---- data_depth_selection.zip
7. In folder X, , run: python datasetCreator.py

Camera's parameters:
	baseline = 0.54
	f = 7.215377e+02