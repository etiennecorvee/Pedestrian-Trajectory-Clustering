# ECO

:\Projects\newCEN\code\analyse\TrajCluter\07-Pedestrian-Trajectory-Clustering>python town_clustering.py
Traceback (most recent call last):
  File "town_clustering.py", line 33, in <module>
    town_trajectories = town_data()
  File "town_clustering.py", line 21, in town_data
    data = DL.read_from_txt()
  File "C:\Projects\newCEN\code\analyse\TrajCluter\07-Pedestrian-Trajectory-Clustering\data\process_data.py", line 28, in read_from_txt
    self.data_matrix = self.raw_data.as_matrix()
  File "C:\Tools\Python372\lib\site-packages\pandas\core\generic.py", line 5274, in __getattr__
    return object.__getattribute__(self, name)
AttributeError: 'DataFrame' object has no attribute 'as_matrix'

C:\Projects\newCEN\code\analyse\TrajCluter\07-Pedestrian-Trajectory-Clustering>python NYGC_clustering.py
Traceback (most recent call last):
  File "NYGC_clustering.py", line 59, in <module>
    data_NYGC = get_all_trajectory(12684)
  File "NYGC_clustering.py", line 44, in get_all_trajectory
    data.append(get_coord_from_txt(filename, ped_ID))
  File "NYGC_clustering.py", line 23, in get_coord_from_txt
    data = file2matrix(filename)
  File "NYGC_clustering.py", line 17, in file2matrix
    data = np.loadtxt(filename, dtype=int)
  File "C:\Tools\Python372\lib\site-packages\numpy\lib\npyio.py", line 981, in loadtxt
    fh = np.lib._datasource.open(fname, 'rt', encoding=encoding)
  File "C:\Tools\Python372\lib\site-packages\numpy\lib\_datasource.py", line 269, in open
    return ds.open(path, mode, encoding=encoding, newline=newline)
  File "C:\Tools\Python372\lib\site-packages\numpy\lib\_datasource.py", line 623, in open
    raise IOError("%s not found." % path)
OSError: ./Annotation/000001.txt not found.

C:\Projects\newCEN\code\analyse\TrajCluter\07-Pedestrian-Trajectory-Clustering>python play.py
(1.1, 2.2)
[1. 2.]
1