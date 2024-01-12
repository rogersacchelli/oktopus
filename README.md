<p align="center">
<img src="https://github.com/OktopUSP/oktopus/assets/83298718/fc05c512-951d-448c-8c31-1e0881783460"/></p>
<br/>
<ul>
    <li>
        <h4>Introduction:</h4>
    </li>
</ul>        
<p>
This repository aims to promote the development of a multi-vendor management platform for IoTs. Any device that follows the TR-369 protocol can be managed. The main objective is to facilitate and unify device management, which generates countless benefits for the end user and service providers, suppressing the demands that today's technologies require: device interconnection, data collection, speed, availability and more.
</p>
<ul>
    <li>
        <h4>TR-069 ---> TR-369 :</h4>
    </li>
</ul>  
<p>
The advent of the Internet of Things brings countless opportunities and challenges for service providers, with over a billion devices across the globe today making use of <a href="https://www.broadband-forum.org/download /TR-069_Amendment-2.pdf">TR-069</a>, what is the future of the protocol and what can we expect ahead?
</p>
<p>
The CWMP (CPE Wan Management Protocol), better known as TR-069, opened many doors for the ecosystem of providers, through which it is possible to deliver services with agility, which meet or exceed customer expectations, with proactive management and secure network, also bearing in mind the lower cost and greater efficiency for service providers.
</p>
<p>
With the rise of what we now call the smart home, the Internet of Things and the demand for increasingly interconnected and cloud-based environments, new demands and obstacles have emerged, opening the door to the creation of a new form of communication that meets the needs of current market needs.
</p>
<p>
There is a fierce race to monetize the IoT devices that are now part of the connected home and other environments. As a result, many companies are creating their own proprietary solutions; this is understandable given such pressure generated by the promise of Smart Home monetization. Unfortunately, these applications contribute to a poor ecosystem, where a provider ends up dependent and limited to a vertical solution, from a single vendor. This generates an <b>low competition environment (which leads to greater risks), less innovation, and the potential for very high cost solutions</b>.
</p>
<p>
The technologies behind Wi-Fi, device-to-device connectivity, the Smart Home and IoTs are constantly evolving and improving. It is important that when service providers look for a solution, they look for something that is "future proof", always thinking ahead.
</p>
<p>
Seeking to solve the challenges mentioned above, providers and manufacturers together developed the USP (User Services Platform), defined by the Broadband Forum's TR-369 standard, which is the natural evolution of the TR-069. <b>This new standard is designed to be flexible, secure, scalable and standardized to meet the demands of a connected world today, and in the future.</b>
</p>

<ul>
    <li>
        <h4>Companies/Institutions involved in the creation of the TR-369:</h4>
        <ul>
            <li> 
            Google
            </li>
            <li> 
            Nokia
            </li>
            <li> 
            Huawei
            </li>
            <li> 
            Axiros
            </li>
            <li> 
            Orange
            </li>
            <li> 
            Commscope
            </li>
            <li> 
            Assia
            </li>
            <li> 
            AT&AT
            </li>
            <li> 
            NEC
            </li>
            <li> 
            Arris
            </li>
            <li> 
            QA Cafe
            </li>
        </ul>
    </li>
</ul> 

--------------------------------------------------------------------------------------------------------------------------------------------------------

<ul>
    <li>
        <h4>Topology:</h4>
    </li>
</ul>  

<img src="https://usp.technology/specification/architecture/usp_architecture.png"/>

![image](https://github.com/leandrofars/oktopus/assets/83298718/b1d5a0c7-4567-464c-bc9b-1956ef5c5f3b)

![image](https://github.com/leandrofars/oktopus/assets/83298718/7b46dc1f-5eb2-4a1b-8e77-376b0836948a)

<ul>
    <li>
        <h4>Protocols:</h4> 
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/9b789f0b-cb0c-4cec-8b8e-767ba21bffae)
    </li>
</ul>

<ul>
    <li>
        <h4>Notifications/Data collection:</h4> 
        You can create notifications that fire on a value change, object creation and removal, complete operation, or an event.
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/184899a3-52e7-491a-8ee7-7b442fe50719)
    </li>
</ul>

<ul>
    <li>
        <h4><a href="https://github.com/BroadbandForum/obuspa">OB-USP-A</a> (Open Broadband User Services Platfrom Agent):</h4> 
        <ul>
             <li>
             Designed for embedded software (~400kb on ARM)
             </li>
             <li>
             Encoded in C
             </li>
             <li>
             License <a href="https://opensource.org/license/bsd-3-clause/">BSD 3-Clause</a>
             </li>
             <li>
             Made for Linux environments
             </li>
        </ul>
    </li>
</ul>

<ul>
    <li>
        <h4>Data Analysis</h4>
The protocol has a mechanism called "Bulk Data", where it is possible to collect large volumes of data from the device, the data can be collected by HTTP, or another telemetry MTP defined in the TR standard, this data can be in JSON, CSV format or XML. This generates the opportunity to use AI on top of this data, obtaining relevant information that can be used for different purposes, from predicting events, KPIs, information for the commercial area, but also for the best configuration of a device.
    </li>
</ul>

<ul>
    <li>
        <h4>WiFi:</h4>
It has over 130 Wi-Fi configuration and diagnostics metrics, many of these settings and parameters are a trade-off between signal coverage area, latency and throughput. When deploying Wi-Fi systems, there is a tendency to maintain the same configuration on all clients, causing the technology to perform below expectations. Machine Learning combined with the data analysis mentioned in the previous topic makes it possible to automate the management and optimization of Wireless networks, where a big data approach is able to find the ideal configuration for each device.
        
![image](https://github.com/leandrofars/oktopus/assets/83298718/3d6fe3e8-3ca2-460b-9583-da89b42753f8)
    </li>
</ul>

<ul>
    <li>
       <h4>Commands:</h4>
         It is possible to perform commands remotely on the product, such as: firmware update, reboot, reset, search for neighboring networks, backup, ping, network diagnostics and many others.
    </li>
</ul>

<ul>
    <li>
        <h4>IoT:</h4>
<div align="center">
<img src="https://github.com/leandrofars/oktopus/assets/83298718/a2a12d9d-05a0-428b-ba3f-1ad83c876301" width="90%"/>
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/91a87f43-3de7-42bd-a689-a4e14eecf5c0" width="60%"/>
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/73e2e360-d53e-494e-9a50-60c83dae75df" width="60%"/>
<div>
    </li>
</ul>

<ul>
    <li>
<h4>Software Modules:</h4>
Currently, telecommunications giants and startups, publishing new software daily, slow delivery cycles and manual and time-consuming quality assurance processes make it difficult for integrators and service providers to compete. USP "Software Module Management" allows a containerized approach to the development of software for embedded devices, making it possible to drastically reduce the chance of error in software updates, it also facilitates the integration of third parties in a device, still keeping the firmware part isolated from Vendor.
<br/>
<img src="https://github.com/leandrofars/oktopus/assets/83298718/64664b0e-81cd-4a29-bbc5-b4186a04dfa2" width="50%"/>
    </li>
</ul>



--------------------------------------------------------------------------------------------------------------------------------------------------------

<ul><li><h4>Infrastructure:</h4></li></ul>

![image](https://github.com/OktopUSP/oktopus/assets/83298718/b63ba300-c6e2-473b-9bfe-86b31f2b1276)

<ul>
    <li>
        <h4>API:</h4>
        <ul>
            <li> 
            <a href="https://documenter.getpostman.com/view/18932104/2s93eR3vQY#10c46751-ede9-4ea1-8ea4-264ebf539e5e">Documentation </a>
            </li>
            <li> 
            <a href="https://www.postman.com/docking-module-astronomer-46169629/workspace/oktopus">Workspace of tests and development</a>
            </li>
        </ul>
    </li>
</ul>
<ul>
    <li>
        <h4>Developer:</h4>
Run app using Docker:
<pre>
leandro@leandro-laptop:~$ cd oktopus/devops
leandro@leandro-laptop:~/oktopus/devops$ docker compose up
</pre>
    </li>
    <li>
Basic manual compilation and run:
    <ul>
        <li>
        <b>Dependencies:</b> Node version: v14.20.0 | Go version: v1.18.1
        </li>
        <li>
        Mqtt broker:
            <pre>leandro@leandro-laptop:~$ cd oktopus/backend/services/mochi/ && go run cmd/main.go -redis "127.0.0.1:6379"</pre>
        </li>
        <li>
        TR-369 controller:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/backend/services/controller/ && go run cmd/oktopus/main.go -u root -P root -mongo "mongodb://127.0.0.1:27017"</pre>
        </li>
        <li>
        Socketio server:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/backend/services/socketio && npm i && npm start</pre>
        </li>
        <li>
        Frontend:
            <pre>
leandro@leandro-laptop:~$ cd oktopus/frontend && npm i && npm run dev</pre>
        </li>       
    </ul>
OBS: Do not use those instructions in production. To implement the project in production you might use more resources that are already avaiable in Oktopus, but would take longer to explain in this README. Soon, there will be more help and explanations about those extra needed configs. 
</li>
    <li>
      <h4>Device test agent (obuspa):</h4>
        <p>You might follow the instructions to build <a href="https://github.com/BroadbandForum/obuspa">obuspa</a> at their repo QUICK_START_GUIDE.md and remember to define 'INCLUDE_PROGRAMMATIC_FACTORY_RESET' at <a href="https://github.com/BroadbandForum/obuspa/blob/master/src/vendor/vendor_defs.h">'vendor_defs.h'</a> inside src/vendor folder, also advice you to build it with make tool.</p>
        <p>You can customize <a href="https://github.com/OktopUSP/oktopus/tree/main/agent/oktopus-mqtt-obuspa.txt">'oktopus-mqtt-obuspa.txt'</a> accordingly to your needs, there you can change broker address, client password, and etc. '-i' option defines the interface your usp packets will go through, in this case it's localhost, also keep in mind that after you run obuspa if you made a change to 'oktopus-mqtt-obuspa.txt' and want it to take effect you must delete '/usr/local/var/obuspa/usp.db' file before running the agent again (docs provide you other methods to do it too).'-r' option defines the config file you want the agent to use. </p>
        <p>Run agent:</p>
        <pre>leandro@leandro-laptop:~/oktopus$ obuspa -p -v 4 -r agent/oktopus-mqtt-obuspa.txt -i lo</pre>
        <p>Obuspa has a lot of info and docs at their repo, which shows you many options to set your environment and customize agent to your embedded project. This basic agent has the purpose to test oktopus connection and shows an idea of how it's like with true devices, although with those, you're able to explore much more parameters and execute lots of configurations. Obuspa has default parameters and mocked info:</p>
        <img src="https://github.com/OktopUSP/oktopus/assets/83298718/4599d566-eada-4313-8ae1-31dae82391de"/>
        <img src="https://github.com/OktopUSP/oktopus/assets/83298718/501b4ccd-6147-4957-9096-695134e34b5e"/>
    </li>
    <p>
    In case you want a more complete and real-world simulation of devices you might use <a href="https://github.com/OktopUSP/agent-sim">Oktopus TR-369 Agent Simulator</a>.
    </p>
</ul>

--------------------------------------------------------------------------------------------------------------------------------------------------------

<ul>
    <li>
        <h4>Roadmap:</h4>
        <p>
            The project goals are organized with milestones that have a due date, just like a sprint. Those issues grouped in milestones are done and have their status updated in a kanban board.
        </p>
        <ul>
            <li> 
            <a href="https://github.com/OktopUSP/oktopus/milestones">Milestones </a>
            </li>
            <li> 
            <a href="https://github.com/orgs/OktopUSP/projects/1/views/2">Kanban Board </a>
            </li>
        </ul>
    </li>
</ul>

--------------------------------------------------------------------------------------------------------------------------------------------------------

<p>Are you going to use our project in your company? would like to talk about TR-369 and IoT management, we're online on <a href="https://join.slack.com/t/oktopustr-369/shared_invite/zt-1znmrbr52-3AXgOlSeQTPQW8_Qhn3C4g">Slack</a>.</p>
<p>If you are interested in internal information about the team and our intentions, visit our <a href="https://github.com/leandrofars/oktopus/wiki">Wiki</a>. [DEPRECATED]</p>

--------------------------------------------------------------------------------------------------------------------------------------------------------

<p>Bibliographic sources: <a href="https://www.broadband-forum.org/download/MU-461.pdf">MU-461.pdf</a>, <a href="https:/ /usp.technology/specification/index.htm">TR-369.html</a>, <a href="https://drive.google.com/drive/folders/1N7FqK0PkDhjCN5s3OhQ_wmz9UcTSwRCX">USP Training Session Slides</usp.technology/specification/index.htm">TR-369.html</a></p>
