### OSPF Numbership number = "12345"
### Name = "John Doe"

#### Issue Explanation:
I encountered an issue while trying to configure OSPF on my router. The routes were not being advertised as expected, and I need assistance in troubleshooting and resolving the problem.

#### URL of Your Screen Recording Video for the Issue

[![Issue Explanation Video](https://img.youtube.com/vi/vi/tGkkjpXzyT4/0.jpg)](https://www.youtube.com/watch?v=vi/tGkkjpXzyT4)
<!-- 
   Example for video URL, so it is displayed correctly. And volunteers can click and play it to get the issue explained by your voice.
   [![Sample Video](https://img.youtube.com/vi/tGkkjpXzyT4/0.jpg)](https://www.youtube.com/watch?v=tGkkjpXzyT4)
   In the above line, the YouTube ID of the video is "tGkkjpXzyT4" (excluding inverted commas).
-->

#### History of Terminal Commands for the Task

```bash
# Configuring OSPF on the router
$ enable
$ configure terminal
$ router ospf 1
$ network 192.168.1.0 0.0.0.255 area 0
$ exit
$ exit
$ show ip ospf neighbor
```

#### Terminal Output of Error or Support Required

```bash
Error: OSPF neighbor not forming
```

<!-- Below is an example of terminal commands and output --->
```bash
# Troubleshooting OSPF neighbor formation issue
$ show ip ospf neighbor

Neighbor ID     Pri   State           Dead Time   Address         Interface
192.168.1.2     1     INIT/DROTHER    00:00:34    192.168.1.2     GigabitEthernet0/0

Error: OSPF neighbor not forming. Please assist in resolving this issue.
```

#### Screenshots

- [Router Configuration](https://github.com/your-username/your-repo/blob/main/screenshots/router_config.png)
- [Error Message](https://github.com/your-username/your-repo/blob/main/screenshots/error_message.png)
