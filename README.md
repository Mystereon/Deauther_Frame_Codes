# Deauther_Frame_Codes
Deauther frame codes 
Code	802.11 definition	Explanation

0	Reserved	NOT SUPPORTED

1	Unspecified reason	TBD

2	Previous authentication no longer valid	NOT SUPPORTED

3	station is leaving (or has left) IBSS or ESS	NOT SUPPORTED

4	Disassociated due to inactivity	Do not send any data after association;

5	Disassociated because AP is unable to handle all currently associated stations	TBD

6	Class 2 frame received from nonauthenticated station	

7	Class 3 frame received from nonassociated station	NOT SUPPORTED

8	Disassociated because sending station is leaving (or has left) BSS	TBD

9	Station requesting (re)association is not authenticated with responding station	NOT SUPPORTED

10	Disassociated because the information in the Power Capability element is unacceptable	NOT SUPPORTED

11	Disassociated because the information in the Supported Channels element is unacceptable	NOT SUPPORTED

12	Reserved	NOT SUPPORTED

13	Invalid information element, i.e., an information element defined in this standard for
which the content does not meet the specifications in Clause 7	NOT SUPPORTED

14	Message integrity code (MIC) failure	NOT SUPPORTED

15	4-Way Handshake timeout	NOT SUPPORTED

16	Group Key Handshake timeout	NOT SUPPORTED

17	Information element in 4-Way Handshake different from (Re)Association Request/Probe
Response/Beacon frame	NOT SUPPORTED

18	Invalid group cipher	NOT SUPPORTED

19	Invalid pairwise cipher	NOT SUPPORTED

20	Invalid AKMP	NOT SUPPORTED

21	Unsupported RSN information element version	NOT SUPPORTED

22	Invalid RSN information element capabilities	NOT SUPPORTED

23	IEEE 802.1X authentication failed	NOT SUPPORTED

24	Cipher suite rejected because of the security policy	NOT SUPPORTED

25-31	Reserved	NOT SUPPORTED

32	Disassociated for unspecified, QoS-related reason	NOT SUPPORTED

33	Disassociated because QAP lacks sufficient bandwidth for this QSTA	NOT SUPPORTED

34	Disassociated because excessive number of frames need to be acknowledged, but are not
acknowledged due to AP transmissions and/or poor channel conditions	NOT SUPPORTED

35	Disassociated because QSTA is transmitting outside the limits of its TXOPs	NOT SUPPORTED

36	Requested from peer QSTA as the QSTA is leaving the QBSS (or resetting)	NOT SUPPORTED

37	Requested from peer QSTA as it does not want to use the mechanism	NOT SUPPORTED

38	Requested from peer QSTA as the QSTA received frames using the mechanism for which
a setup is required	NOT SUPPORTED

39	Requested from peer QSTA due to timeout	NOT SUPPORTED

40	Peer QSTA does not support the requested cipher suite	NOT SUPPORTED

46-65535	46--65 535 Reserved	NOT SUPPORTED

98	Cisco defined	TBD

99	Cisco defined
Used when the reason code sent in a deassoc req or deauth by the client is invalid – invalid length, invalid value etc	Example: Send a Deauth to the AP with the reason code to be invalid, say zero
 
