Time Info Node
==============

This node returns time info from the current scene. It has four output sockets and none input sockets. The values returned are integers. 

.. image:: time_info_node.png

**Frame:** Returns the final frame (time remapping is applied). This node is crucial for changing properties over time. Math operations can be applied to this node in order to animate properties.

**Start Frame:** Gives the frame where the animation begins.

**End Frame:** obvious...

**Frame Rate:** Frame Rate in this Scene (24 by default). The frame rate is the total amount of frames displayed by second on the animation.
