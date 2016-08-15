^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package marti_nav_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.5 (2016-08-14)
------------------
* Adds new services to save a route and to update a route's metadata:

  - SaveRoute
  
    - Takes a list of route points and saves it
    - If the route's GUID matches an existing route, it will be overwritten
    
  - UpdateRouteMetadata
  
    - Modifies an existing route
    - Replaces the properties on specified points with new properties
    
* Adds Obstacle/ObstacleArray messages to marti_nav_msgs.
* Contributors: Elliot Johnson, P. J. Reed

0.0.4 (2016-05-20)
------------------
* Build PlanRoute service.
* Add marti_nav_msgs/RouteSpeedArray message.
* Adding a service for planning routes
  Resolves `#61 <https://github.com/swri-robotics/marti_messages/issues/61>`_
* Adding a service to set the currently active route
* Add services for getting routes.
* Add service definition for saving a recorded route.
* Contributors: Elliot Johnson, Marc Alban, P. J. Reed

0.0.3 (2016-03-11)
------------------
* Adds RouteSpeed message.
* Contributors: Marc Alban

0.0.2 (2016-03-04)
------------------
* Adds Route, RoutePoint, and RoutePosition messages
  Route and RoutePoint are very general messages to define a sequence of
  achievable poses for a vehicle along with arbitrary metadata about the
  route and the point itself.
* Contributors: Jerry Towler

0.0.1 (2015-09-22)
------------------
* Fixing catkin_lint problems that could prevent installation.
* update cmake version to squash the CMP0003 warning
* remove dependencies on build_tools
* use format 2 package definition
* build fixes for catkin
* catkinize marti_messages
* Create README.md
* Contributors: Marc Alban, P. J. Reed
