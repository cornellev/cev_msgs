Custom ROS 2 messages for Cornell Electric Vehicles.

SensorCollect.msg
 - float64 : timestamp      [ Message time in s ]
 - float32 : velocity       [ Velocity in m/s]
 - float32 : steering_angle [ Steering angle in radians ]

Trajectory.msg
 - Header     : header       [ Header ]
 - Waypoint[] : waypoints    [ Array of Waypoints ]

Waypoint.msg
 - float32 : x     [ x-coordinate in meters ]
 - float32 : y     [ y-coordinate in meters ]
 - float32 : v     [ velocity in m/s ]
 - float32 : tau   [ steering angle in radians ]
 - float32 : theta [ heading in radians ]
 
