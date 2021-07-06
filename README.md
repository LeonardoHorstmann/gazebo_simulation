# gazebo_simulation

based on http://gazebosim.org/tutorials?cat=guided_i&tut=guided_i5

to run: 
* install gazebo
* export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:~/<path>/gazebo_simulation/velodyne_plugin/build
* cd ~/<path>/gazebo_simulation/velodyne_plugin/build
* cmake ../
* make
* gazebo --verbose ../velodyne.world
