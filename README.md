<h1> Smart Traffic Management System</h1>

<h2>Table of Contents</h2>
<ul> 
<li>Overview</li>
<li>Features</li>
<li>Installation</li>
<li>Usage</li>
<li>System Architecture</li>
<li>Modules</li>
<li>Contributing</li>
<li>Acknowledgments</li>
</ul>
<hr style="border: 0.1px  black;">
<h3>Overview</h3>
The Smart Traffic Management System is a C++ application that simulates real-time traffic monitoring, vehicle record management, challan record handling, and traffic booth control. It helps authorities efficiently monitor and manage urban traffic.
<h4>Key Highlights:</h4>
<ul>
<li>Simulates traffic monitoring using cameras.</li>
<li>Manages vehicle and challan records interactively.</li>
<li>Provides a real-time traffic control simulation.</li>
<li>Displays traffic booth locations and helpline information.</li>
</ul>
    <hr style="border: 0.5px solid black;">
<h5>Features</h5>
<ul>
<li>Vehicle Records: View and manage vehicle details such as registration, make, model, and owner information.</li>
<li>Challan Records: City-specific challan records with details of fines and violations.</li>
<li>Real-time Traffic Monitoring: Monitor vehicles and detect accidents using simulated cameras.</li>
<li>Traffic Booth Management: City-wise traffic booth information and officer details.</li>
<li>Interactive Menu: User-friendly interface with options for traffic control and assistance.</li>
<li>Help Section: Provides nearby hospital locations and helpline numbers.</li>
</ul>
<hr style="border: 0.5px solid black;">
<h6> Installation </h6>
<b>Prerequisites</b><br>
<ul>
<li>C++ Compiler (e.g., GCC or MSVC)</li>
<li>CMake (optional for building)</li>
<li>A terminal or IDE supporting C++17 or later.</li>
</ul>
<b>Steps</b><br>
<ol>
<li>Clone this repository:</li>
<pre>git clone https://github.com/your-username/traffic-management-system.git
cd traffic-management-system</pre>
<li>Compile the code:</li>
<pre>g++ -std=c++17 -o traffic_management main.cpp</pre>
<li>Run the program:</li>
<pre>./traffic_management</pre>
</ol>
<hr style="border: 0.5px solid black;">
<b> Usage </b>
<ol>
<li>Launch the application.</li>
<li>Navigate through the menu to:</li>
    <ul>
<li>View vehicle or challan records.</li>
<li>Monitor traffic in real-time.</li>
<li>Search for specific vehicle records.</li>
<li>View traffic booth information.</li>
    </ul>
<li>Exit the program using the provided option.</li>
</ol>
<hr style="border: 0.5px solid black;">
   <b> System Architecture </b><br>
<pre>
+-----------------------------------------+
|      Smart Traffic Management System    |
+-----------------------------------------+
|       Vehicle Management Module         |
|       Challan Records Module            |
|       Traffic Booth Module              |
|       Real-time Traffic Monitoring      |
+-----------------------------------------+
</pre>
<hr style="border: 0.5px solid black;">
<h7><b>Modules</b></h7><br>
<h8><b>1. Traffic Camera</b></h8><br>
Simulates traffic monitoring and accident detection.<br>
<h9><b>2. Traffic Monitoring System</b></h9><br>
Manages multiple traffic cameras and provides real-time monitoring.<br>
<h10><b>3. Smart Traffic Management</b></h10><br>
Main user interface with an interactive menu to access all features.<br>
<hr style="border: 0.5px solid black;">
<b><font size="25">Demo</font></b><br>
<br>
Screenshots
<br>
<ul>
<li>Main Menu</li>
<li>Vehicle Records</li>
<li>Challan Records</li>
</ul>
<hr style="border: 0.5px solid black;">
<h11><b>Contributing</b></h11><br>
Contributions are welcome! To contribute:<br>
<ol>
<li>Fork the repository.</li>
<li>Create a new branch for your feature/bug fix:</li>
<pre>git checkout -b feature-name</pre>
<li>Commit your changes:</li>
<pre>git commit -m "Add new feature"</pre>
<li>Push to your fork and submit a pull request.</li>
</ol>
<hr style="border: 0.5px solid black;">
<h12><b>Acknowledgments</b></h12><br>
<ul>
<li>Thanks to all contributors and testers.</li>
<li>Special thanks to the open-source C++ community for guidance and inspiration.</li>
</ul>
