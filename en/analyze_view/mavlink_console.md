# MAVLink Console (Analyze View)

The MAVLink Console (**Analyze > Mavlink Console**) allows you to connect to the PX4 [nsh shell](https://dev.px4.io/en/debug/system_console.html) and send commands.

> **Note** The console only works when connected to *hardware* running the *PX4* flight stack. 
  PX4 SITL and ArduPilot are not supported.

<span></span>
> **Tip** This is a very useful feature for developers as it allows deep access to the system while the vehicle is flying (if connected via WiFi).

![Analyze View MAVLink Console](../../images/analyze/mavlink_console.jpg)

The view does not display any output except in response to commands.
Once the vehicle is connected, you can enter commands in the bar provided (for a full list of available commands enter: `?`).

Command output is displayed in the view above the command bar. 
Click **Show Latest** to jump to the bottom of the command output. 