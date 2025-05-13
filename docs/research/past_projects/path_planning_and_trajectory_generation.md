# Path Planning and Trajectory Generation

The goal of the path planner is to generate a way-point path from the plane's current position to a goal using a terrain containing obstacles of various types. Our UAV path planner uses Rapidly-exploring Random Trees (http://msl.cs.uiuc.edu/rrt/) to explore the terrain and find a path to a goal.

In the diagram at right (click to see large image), the blue cross is the position of the airplane and the magenta cross is the goal. The path that the planner chose is represented in magenta and the graph of possible paths is yellow.

Brandon Call also used this path planner to plan paths for a mars rover. He has included several iterations of this application's graph growing in the sequence illustrated below. In this image, the white terrain represents obstacles while the dark colors are flat, drivable terrain. The yellow branches are the rapidly-exploring trees, and the best path is indicated by the pink line. After the path planner makes a way-point path, the trajectory generation makes the path smooth and flyable for the UAV. In the future, plans include plotting a rough initial path quickly and then refining the latter portions of the path while the plane begins to fly the initial portion.

Sponsor
Air Force Office of Scientific Research

Duration
September 2002 – September 2003

Project Description
Trajectory generation creates paths between specified points that can be realized by an unmanned air vehicle. Paths can be created that preserve straight-line path length, minimize flight time, or guarantee observation of a given area.

These equations represent how an airplane reacts to heading change input. Trajectory generation deals with how to satisfy these physical constraints while still getting the airplane to fly along a specified path.

Because airplanes physically cannot turn too sharply, only a small region can be reached by the airplane in the next instant of time. This adds complexity to the problem of traversing a path, especially when the path has many corners.

This figure shows how the trajectory generation algorithm calculates when the next turn should begin. By fixing all of the circles to the minimum turning radius of the airplane, we can ensure that the trajectory is realizable.

Here are three possible paths that the airplane could take if it’s purpose was to come near the point at the end of the triangle. The top preserves straight-line path length, which is very useful when coordinating the timing of multiple airplanes.

The BYU Magicc Laboratory has implemented this trajectory generation algorithm as a step in coordinating the timing and movements of teams of airplanes.
