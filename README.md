# BFQ Updates for Dual-Actuator HDDs
Seagate Technology's Exos 2x14 and Exos 2x18 HDDs use MACH 2 technology to give users access to two sets of HDD actuators (and therefore, two I/O streams) concurrently.
The actuators are accessible via a split in the LBA space, but effectively taking advantage of the potential performance increases is currently not a native feature of the Linux block layer. The work in this repository is dedicated to making BFQ actuator-aware, natively pursuing the improved performance of multiple actuators whenever possible. 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=-gyW4bOv3iU" target="_blank">
 <img src="http://img.youtube.com/vi/-gyW4bOv3iU/maxresdefault.jpg" alt="Watch the video" width="480" height="360" border="10" />
</a>
