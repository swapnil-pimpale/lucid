lucid
=====

Cloud Computing, one of the emerging trends provides IT services through
virtualized resources to its tenants and charges them on the basis of resource
utilization. Due to lack of transparency in the activities taking place on the
virtual machines at service provider's end and various security issues, users
hesitate to move their infrastructure to Cloud. The users do not have a clear
idea of what they are being charged for. In order to get the required
information, users can track the activities on their virtual machines by using
third party network monitoring tools. However these tools hog a significant
amount of memory which affects the performance of other critical processes
running on the VMs. Hence, we propose LUCID, a solution for monitoring network
activity of VMs.
LUCID will reside in Dom0 which is a controller OS of Xen Hypervisor, leading
to centralized monitoring of multiple VM's. LUCID provides kernel level packet
capture mechanism and archiving of the captured data. Efficient Indexing
Mechanism has been built to facilitate faster retrieval of this data when
queried. The results are presented to the user via a SaaS interface (Software
as a Service) where user can specify various queries and view corresponding
results. This data helps the users to monitor network activity and also view
the recorded traffic which provides the much needed transparency regarding
network activity especially during the dormant period. Hence the user gets a
clear idea of what he is being charged for.
