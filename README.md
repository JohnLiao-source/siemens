<img src="images/logo.png" alt="Project Logo" width="500"/>

iM-Connect® is a web-based and simple-to-use programming software developed by NOVAKON Co., Ltd., 
that supports a variety of industrial communication protocols, PLC drivers, and IIOT cloud 
connections as a simple but reliable protocol conversion and data acquisition platform for 
the "Connected" industries.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Documents](#Documents)
5. [Samples](#Samples)
6. [Version History](#version-history)
7. [License](#license)
8. [Download](#Download)

## Prerequisites
- OS requirement: Ubuntu20.04 x86-64
- [Industrial Edge Hub](https://docs.eu1.edge.siemens.cloud/get_started_and_operate/industrial_edge_hub/setup/ieh_index.html) Login IEH and create IEM instance.
- [Industrial Edge Management](https://docs.eu1.edge.siemens.cloud/get_started_and_operate/industrial_edge_management/overview.html) Install iM-CONNECT application on Edge Device
- [Industrial Edge Device](https://docs.eu1.edge.siemens.cloud/get_started_and_operate/industrial_edge_device/setup_onboarding/sign_up/sign_up_with_configurated_email_server.html) Control iM-CONNECT application.

## Installation
Follow the steps below to install the application.
1. Open the [Industrial Edge Hub](https://dahocove.iehub.eu1.edge.siemens.cloud/) website and Copy latest version to IEM(s)
2. Open the [Industrial Edge Management](https://docs.eu1.edge.siemens.cloud/get_started_and_operate/industrial_edge_management/overview.html) and install iM-CONNECT on Edge Device.<br><img src="images/open_IEM.png" alt="Project Logo" width="900"/>
3. Open the [Industrial Edge Device](https://docs.eu1.edge.siemens.cloud/get_started_and_operate/industrial_edge_device/setup_onboarding/sign_up/sign_up_with_configurated_email_server.html) and control the application.

## Usage
1. Open the IED in the browser and click the iM-CONNECT icon</br><img src="images/open_website.png" alt="Project Logo" width="900"/>
2. Please refer to [the user manual](https://www.novakon.com.tw/common/frontend/download?path=/uploads/images/support/download/IM-Connect_User_Guide_Novakon_EN.pdf) to operate the software on Edge Device

To configure the project, follow these steps:

## Documents
- [Start Simulation](http://34.81.108.66:9001/) Click the button to start the online simulation （Username: simulation / Password: novakon）
- [Software Tutorial](https://www.novakon.com.tw/en/software/detail/iM_Connect) Open the website and tab labeled "Software Tutorial" on the page.
- [User Manual](Documents/IM-Connect%20User%20Guide%20Siemens.pdf) The user manual provides comprehensive instructions on how to use the iM-Connect® software, including setup, configuration, and troubleshooting tips. It is an essential resource for getting the most out of the software.

## Samples
To better understand how to use iM-Connect®, you can refer to the following sample projects:

1. **Data Acquisition**
    - Description: Shows how to acquire data from a PLC and display it on a dashboard.
    - Files: [Samples/TAG.dat](Samples/TAG.docx)
    - Instructions: Follow the steps in the [Samples/TAG.pdf](Samples/TAG.pdf) file located in the sample directory.

2. **Datalogger Setup**
    - Description: Demonstrates how to set up datalog that record data to file/remote/database.
    - Files: [Samples/DATALOG.dat](Samples/DATALOG.dat)
    - Instructions: Follow the steps in the [Samples/Datalogger.pdf](Samples/Datalogger.pdf) file located in the sample directory.

3. **Alarm triggered**
    - Description: Example of trigger condition and send alarm to people.
    - Files: [Samples/ALARM.dat](Samples/ALARM.dat)
    - Instructions: Follow the steps in the [Samples/Alarm.pdf](Samples/Alarm.pdf) file located in the sample directory.

4. **Macro Programing**
    - Description: Demonstrates how to program by Javascript language.
    - Files: [Samples/MACRO.dat](Samples/MACRO.dat)
    - Instructions: Follow the steps in the [Samples/Macro.pdf](Samples/Macro.pdf) file located in the sample directory.

5. **MQTT Connection**
    - Description: Demonstrates how to use MQTT publisher(Device to Clound) and subscriber(Cloud to Device).
    - Files: [Samples/MQTT.dat](Samples/MQTT.dat)
    - Instructions: Follow the steps in the [Samples/MQTT.pdf](Samples/MQTT.pdf) file located in the sample directory.

5. **OPCUA Connection**
    - Description: Demonstrates how to use OPCUA to acquire data and write data to a PLC.
    - Files: [Samples/OPCUA.dat](Samples/OPCUA.dat)
    - Instructions: Follow the steps in the [Samples/OPCUA.pdf](Samples/OPCUA.pdf) file located in the sample directory.

5. **REST API**
    - Description: Demonstrates how to use RESTful API.
    - Files: [Samples/RESTAPI.dat](Samples/RESTAPI.dat)
    - Instructions: Follow the steps in the [Samples/RESTAPI.pdf](Samples/RESTAPI.pdf) file located in the sample irectory.

Each sample project includes detailed instructions and necessary files to help you get started quickly.

## Version History

| Version    | Date       | Changes / Notes                                                                                     |
|------------|------------|------------------------------------------------------------------------------------------------------|
| 2.2.24.07  | 2025-08-04 | - Added PLC driver support for BACnet/IP<br> - Implemented OPC UA Historical Access using both in-memory buffer and SQLite3 for short-term and long-term data storage<br> - Integrated MySQL 8.0 server for persistent data log storage |


## License
<!-- 表格 -->
<table>
    <tr>
        <th align="left" valign="bottom">Library/Component</th>
        <th align="left" valign="bottom">License</th>
    </tr>
    <tr>
        <td align="left" valign="top">Node.js</td>
        <td align="left" valign="top"><a href="#libraryA">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">Qt 4.8.7</td>
        <td align="left" valign="top"><a href="#libraryB">LGPLv2.1</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">BootstrapVue</td>
        <td align="left" valign="top"><a href="#libraryC">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">ECharts</td>
        <td align="left" valign="top"><a href="#libraryD">Apache v2.0</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">open62541</td>
        <td align="left" valign="top"><a href="#libraryE">MPLv2</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">express</td>
        <td align="left" valign="top"><a href="#libraryF">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">mqtt</td>
        <td align="left" valign="top"><a href="#libraryG">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">mysql</td>
        <td align="left" valign="top"><a href="#libraryH">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">mssql</td>
        <td align="left" valign="top"><a href="#libraryI">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">nodemailer</td>
        <td align="left" valign="top"><a href="#libraryJ">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">cors</td>
        <td align="left" valign="top"><a href="#libraryK">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">ftp</td>
        <td align="left" valign="top"><a href="#libraryL">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">asyncawait</td>
        <td align="left" valign="top"><a href="#libraryM">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">node-jsonwebtoken</td>
        <td align="left" valign="top"><a href="#libraryN">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">Vue</td>
        <td align="left" valign="top"><a href="#libraryO">MIT</a></td>
    </tr>
    <tr>
        <td align="left" valign="top">light-vue-tree</td>
        <td align="left" valign="top"><a href="#libraryP">MIT</a></td>
    </tr>
</table>
<hr>
<!-- 詳細內容Node.js -->
<div class="license-card">
    <div class="library-name" id="libraryA" style="font-size: 1.5em; font-weight: bold;">Node.js</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Node.js is a cross-platform, open-source server environment, Node.js is a back-end JavaScript runtime environment.<br> Contact:<a href="https://nodejs.org/">https://nodejs.org/</a></h4>
            <h4 style="margin-bottom: -20px;">Node.js is available under the MIT.</h4>
            <h4>Reference:<a href="https://en.wikipedia.org/wiki/MIT_License">GNU Lesser General Public License, version 2.1</a></h4>
        </div>
    </div>
</div>
<!-- 詳細內容Qt 4.8.7 -->
<div class="license-card">
    <div class="library-name" id="libraryB" style="font-size: 1.5em; font-weight: bold;">Qt 4.8.7</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">The Qt GUI Toolkit is Copyright (C) 2013 Digia Plc and/or its subsidiary(-ies).<br> Contact:<a href="http://www.qt-project.org/legal">http://www.qt-project.org/legal</a></h4>
            <h4 style="margin-bottom: -20px;">Qt is available under the LGPL.</h4>
            <h4>Reference:<a href="https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html">GNU Lesser General Public License, version 2.1</a></h4>
        </div>
    </div>
</div>
<!-- 詳細內容Bootstrap-vue -->
<div class="license-card">
    <div class="library-name" id="libraryC" style="font-size: 1.5em; font-weight: bold;">BootstrapVue</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">BootstrapVue is distributed under The MIT License (MIT)</h4>
            <h4>Reference:<a href="https://bootstrap-vue.org/">https://bootstrap-vue.org/</a></h4>
        </div>
    </div>
</div>
<!-- 詳細內容echart -->
<div class="license-card">
    <div class="library-name" id="libraryD" style="font-size: 1.5em; font-weight: bold;">ECharts</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">ECharts is distributed under Apache License Version 2.0.</h4>
            <h4>Reference:<a href="https://echarts.apache.org/">https://echarts.apache.org/</a></h4>
        </div>
    </div>
</div>
<!-- 詳細內容 open62541 -->
<div class="license-card">
    <div class="library-name" id="libraryE" style="font-size: 1.5em; font-weight: bold;">open62541</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">open62541 is licensed under the Mozilla Public License 2.0</h4>
            <h4>Reference:<a href="https://github.com/open62541/open62541/blob/master/LICENSE">https://www.open62541.org/</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 express -->
<div class="license-card">
    <div class="library-name" id="libraryF" style="font-size: 1.5em; font-weight: bold;">express</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2009-2014 TJ Holowaychuk <tj@vision-media.ca><br>
                Copyright (c) 2013-2014 Roman Shtylman <shtylman+expressjs@gmail.com><br>
                Copyright (c) 2014-2015 Douglas Christopher Wilson <doug@somethingdoug.com></h4>
            <h4>Reference:<a href="http://expressjs.com/en/starter/installing.html">http://expressjs.com/en/starter/installing.html</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 mqtt -->
<div class="license-card">
    <div class="library-name" id="libraryG" style="font-size: 1.5em; font-weight: bold;">MQTT</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2015-2016 MQTT.js contributors</h4>
            <h4>Reference:<a href="https://github.com/mqttjs/MQTT.js#contributors">https://github.com/mqttjs/MQTT.js#contributors</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 mysql -->
<div class="license-card">
    <div class="library-name" id="libraryH" style="font-size: 1.5em; font-weight: bold;">mysql</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2012 Felix Geisendörfer (felix@debuggable.com) and contributors
            Permission is hereby granted.</h4>
            <h4>Reference:<a href="https://github.com/open62541/open62541/blob/master/LICENSE">https://www.open62541.org/</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容node-mssql -->
<div class="license-card">
    <div class="library-name" id="libraryI" style="font-size: 1.5em; font-weight: bold;">node-mssql</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Contributions are very welcome!</h4>
            <h4>Reference:<a
                    href="https://github.com/tediousjs/node-mssql/wiki/Contributing">https://github.com/tediousjs/node-mssql/wiki/Contributing</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 nodemailer -->
<div class="license-card">
    <div class="library-name" id="libraryJ" style="font-size: 1.5em; font-weight: bold;">nodemailer</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2011-2016 Andris Reinman.</h4>
            <h4>Reference:<a href="https://github.com/nodemailer/nodemailer">https://github.com/nodemailer/nodemailer</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 cors -->
<div class="license-card">
    <div class="library-name" id="libraryK" style="font-size: 1.5em; font-weight: bold;">cors</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2013 Troy Goode <troygoode@gmail.com>.</h4>
            <h4>Reference:<a href="https://github.com/expressjs/cors">https://github.com/expressjs/cors</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 ftp -->
<div class="license-card">
    <div class="library-name" id="libraryL" style="font-size: 1.5em; font-weight: bold;">ftp</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright Brian White. All rights reserved.</h4>
            <h4>Reference:<a href="https://github.com/jlaffaye/ftp">https://github.com/jlaffaye/ftp</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 asyncawait -->
<div class="license-card">
    <div class="library-name" id="libraryM" style="font-size: 1.5em; font-weight: bold;">asyncawait</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px; margin-bottom: -20px;">Copyright (c) 2014-2016 Troy Gerwien.</h4>
            <h4>Reference:<a href="https://github.com/yortus/asyncawai">https://github.com/yortus/asyncawai</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 jsonwebtoken -->
<div class="license-card">
    <div class="library-name" id="libraryN" style="font-size: 1.5em; font-weight: bold;">node-jsonwebtoken</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px;">Reference:<a href="https://github.com/auth0/node-jsonwebtoken">https://github.com/auth0/node-jsonwebtoken</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容 Vue -->
<div class="license-card">
    <div class="library-name" id="libraryO" style="font-size: 1.5em; font-weight: bold;">Vue</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px;">Reference:<a href="https://vuejs.org">https://vuejs.org</a>
            </h4>
        </div>
    </div>
</div>
<!-- 詳細內容  light-vue-tree-->
<div class="license-card">
    <div class="library-name" id="libraryP" style="font-size: 1.5em;">light-vue-tree</div>
    <div class="content-container">
        <div class="content">
            <h4 style="margin-top:10px;">Reference:<a href="https://github.com/Create-Peace/light-vue-tree">https://github.com/Create-Peace/light-vue-tree</a>
            </h4>
        </div>
    </div>


## Download
Clone the repository and install the dependencies:

```bash
git clone https://github.com/JohnLiao-source/siemens.git
cd siemens
