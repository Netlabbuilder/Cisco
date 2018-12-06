In this lab, we configure **MP-BGP (BGP, VRFs with route-distinguisher, route-target import and export)** to route traffic between different VRFs (Customer_A, Customer_B and Resources) on Provider_Edge router.

* Networks at Resources site are available and reachable from Customer_A and Customer_B sites
  
* Networks at Customer_A and Customer_B sites are available and reachable from Resources site.
  
* Networks at Customer_A and Customer_B are isolated. They cannot be reachable from each other:
  
  * Customer_A site cannot access networks at Customer_B
    
  * Customer_B site cannot access networks at Customer_A
    

![](https://github.com/Netlabbuilder/Cisco/blob/master/IOS/BGP/Inter-VRF%20routing%20with%20MP-BGP/Inter-VRF%20Routing%20with%20MP-BGP.png)
