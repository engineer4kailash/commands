## <p align="center"><ins>NSX-T Manager</ins></p>

| Description | Command |
| :--- | :---: |
| NSX-T Cluster Manager details | ***get managers*** |
| NSX-T Cluster Status | ***get cluster status*** |
| NSX-T Cluster Status with verbose output  | ***get cluster status verbose*** |
| NSX-T Cluster Configuration Details | ***get cluster config*** |
| NSX-T Manager to display ARP Table | ***get logical-switch arp-table*** |
| NSX-T to display the MAC table for a specific LS | ***get logical-switch mac-table*** |
| NSX-T Manager to display transport node table | ***get logical-switch transport-node-table*** |
| From NSX Edge to see routes | ***get logical-router<br>vrf number_of_T0<br>get route*** |
| From NSX Edge to see BGP Neighbor | ***get cluster config*** |
| NSX-T Cluster Configuration Details | ***get logical-router<br>vrf number_of_T0<br>get bgp neighbor*** |
| NSX Manager to see the tunnel between Transport Hosts | ***get host-switch tunnels*** |

## <p align="center"><ins>Logical Routers</ins></p>

| Description | Command |
| :--- | :---: |
| List all the logical Routers on Transport Node/Edges | ***get logical-routers*** |
| Select VRF routing context on Node | ***vrf vrf_number*** |
| Get the BGP neighbor status  | ***get bgp neighbor summary*** |
| Get the Routes in VRF /Logical Routers | ***get routes ipv4*** |