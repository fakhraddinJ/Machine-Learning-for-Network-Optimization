# Machine-Learning for Network Optimization
## Proactive network load distribution and link utilization optimization using machine-learning techniques
### Project Summary:
Today’s business demands require corporations to relocate their networks to several geographically separated areas to be able to handle and carry out a huge mixture of traffic flows from a wide range of diverse applications and customers. An issue in such cases it to efficiently manage and optimize edge links, as these links are the last point of administration domain, and rest of the underlying transit paths are hidden. Per flow path prediction for the purpose of load distribution for these kind of scenarios can help to optimize and improve the routing mechanism not only just per destination but even per each packet of a traffic stream. The proposed methodology of this work uses three powerful state-of-the-art machine-learning techniques __(Artificial neural Networks (ANN)__, __Support Vector Machines (SVM)__ and __Decision Trees (DT)__ to build a network performance analysis framework that can handle the link utilization efficiency. In order to get higher accuracy and compatibility in results, physical computing resources used to build the environment of the project, and a real-like network infrastructure implemented using virtual appliances for the measurements of traffic statistics and evaluation of the predictors. Traffic conditions and flow transmissions established using Cisco's IOS XE's built in features called "IP SLA UDP Jitter operations" on edge router appliances toward other edge nodes in a roundtrip fashion over the underlay network. Then, performance measurements of the network gathered using SNMP and NetFlow as input to the data collector called Network monitoring system (NMS) for warehousing and manipulation. Collected data then summarized to a clear and well-organized dataset using most influential flow metrics or attributes (e.g. RTT, Jitter, delay, loss rate …). Different structures of ML models for each of previously mentioned algorithms trained and validated on dataset in a 66%–34% training/validation split approach and repeated holdout method. Predictors reported an average accuracy of more than 90% on user data, in well-tuned structure sets. Next step after validation of predictions, was to implement some real samples of user traffic flows on the network, and assess the core link utilizations and their routing efficiency before and after applying policies. Significant improvement observed in network performance and utilization of edge links after applying ML policy, so that almost all of flow pockets routed using most appropriate outgoing interface causing better utilization and very less loss rate on critical edge links. Satisfying results also achieved in peak time traffic situation. The flexibility of the proposed methodology in comparison with passive measurements and capacity planning, lead to recommend its extension to larger similar network environments.

#### Written by: Fakhraddin Mohammed JAF
