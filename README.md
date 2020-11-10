# surface-evolver-dump-visualization

This is a simple code used to visualize the surface produced by surface evolver dump. This code uses Mayavi package in python. This is a quick way to generate good quality visualization of the simulated surface in surface evolver. 
```
 __             __                    __            _                        _                 _ _              
/ _\_   _ _ __ / _| __ _  ___ ___    /__\_   _____ | |_   _____ _ __  /\   /(_)___ _   _  __ _| (_)_______ _ __ 
\ \| | | | '__| |_ / _` |/ __/ _ \  /_\ \ \ / / _ \| \ \ / / _ \ '__| \ \ / / / __| | | |/ _` | | |_  / _ \ '__|
_\ \ |_| | |  |  _| (_| | (_|  __/ //__  \ V / (_) | |\ V /  __/ |     \ V /| \__ \ |_| | (_| | | |/ /  __/ |   
\__/\__,_|_|  |_|  \__,_|\___\___| \__/   \_/ \___/|_| \_/ \___|_|      \_/ |_|___/\__,_|\__,_|_|_/___\___|_|   
                                                                                                                
```
The text files used in the code are extracted manually (for the time being) from the dump produced by Surface evolver. It has the information of the mesh vertices, the edges connecting the vertices and the faces produced by the edges. This data is used to make the simulated surface for visualization.

To run the code one needs python 3 along with matplotlib, numpy and mayavi modules.
To install Mayavi in anaconda one can execute the following command:
```conda install -c anaconda mayavi```

Special thanks to Nasser Alkmim (https://github.com/nasseralkmim) for the blog
http://nasseralkmim.github.io/notes/2016/08/11/drawing-3d-lines-in-python/ 
