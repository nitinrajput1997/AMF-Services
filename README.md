# AMF-Services

![](/amf.png)

Every network function produces some services and consumes some services. We will discuss the services which were consumed by other functions.<br />

a) **Namf_Communication**<br />
Provides the service operation for transporting N1 messages to UE.<br />
Provides the service operation for initiating N2 messages towards the access network.<br />
Allows network functions to subscribe and unsubscribe for notification of specific N1 messages from UE.<br />
Allows network functions to subscribe and unsubscribe for notification of specific information from the access network.<br />
Security Context management<br />
UE information management and transfer (including its security context)<br />

b) **Namf_MT**<br />
Paging UE if UE is in Idle state and responds to other network functions after the UE enters CM-Connected State.<br />
Respond to requester network function if UE is in connected mode.<br />
Providing the terminating domain selection information for IMS voice to the consumer network functions.<br />

c) **Namf_Location**<br />
Allows network functions can request the current geodetic and optionally civic location of a target UE.<br />
Allows network functions to be notified of event information related to emergency sessions.<br />
Allows network functions to request network provider location information(NPLI) and/or local time zone corresponding to the location of the target UE.<br />

d) **Namf_EventExposure**<br />
Location changes<br />
Time Zone changes<br />
Access Type changes<br />
Registration State changes<br />
Connectivity State changes<br />
UE loss of Communication<br />
UE Reachability Status<br />
