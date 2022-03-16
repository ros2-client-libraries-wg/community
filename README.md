# ROS 2 Client Libraries Working Group

This document defines the scope and governance of the ROS 2 Client Libraries Working Group.

The Client Libraries Working Group is responsible for the management, design and development of the foundational ROS 2 client library, rcl, as well as the “core” client libraries as determined by the ROS 2 TSC.
Currently these are rclcpp and rclpy.
The working group discusses new feature design and triages contributions, including discussing controversial pull requests with the goal of resolving discussions and moving those pull requests towards acceptance.

## Scope of work

- Design of rcl and "core" ROS 2 client libraries
- Management of rcl, "core" ROS 2 client libraries, and relevant supporting libraries
- In conjunction with the Middleware Working Group, define the boundary between the client libraries and the middleware layer
- Discussion and selection of design and task priorities, under the guidance of the TSC
- Pull request triage

## Repositories responsible for

- [rcl](https://github.com/ros2/rcl)
- [rclcpp](https://github.com/ros2/rclcpp)
- [rclpy](https://github.com/ros2/rclpy)
- [rcl_interfaces](https://github.com/ros2/rcl_interfaces)
- [rcl_logging](https://github.com/ros2/rcl_logging)
- [spdlog_vendor](https://github.com/ros2/spdlog_vendor)
- [rcutils](https://github.com/ros2/rcutils)
- [rcpputils](https://github.com/ros2/rcpputils)
- [rpyutils](https://github.com/ros2/rpyutils)
- [examples](https://github.com/ros2/examples)
- [demos](https://github.com/ros2/demos)

## Meetings

The working group meets regularly every other Wednesday at 15:00 UTC.
See the [ROS Events calendar](https://calendar.google.com/calendar/embed?src=agf3kajirket8khktupm9go748%40group.calendar.google.com) for the specific time of the next meeting.
To receive invitations to the meetings and record the meeting in your own calendar, sign up to the [meeting invitations Google Group](https://groups.google.com/forum/#!forum/ros-client-libraries-working-group-invites) (this group is for meeting invitations only, not discussion).

## Communication channels

Discussion relevant to the working group happens:

- On the issue trackers for the relevant repositories
- On the ROS Discourse, with the tag [wg-client-libraries](https://discourse.ros.org/tag/wg-client-libraries)

## Modifying this governance document

Changes to this document should be proposed via pull request.
The PR will be merged on working group approval.
