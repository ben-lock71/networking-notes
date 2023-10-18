#Virtual Private Cloud

##What is a VPC?
A VPC is a logically isolated virtual network within public cloud infrastructure. 

##How is it implemented?
Within a public cloud, the resources forming the VPC are isolated behind security features and network controls which limit the IP addresses and applications which can access them. There is no specific hardware differentiation between the VPC resources and other resources which reside on the same public cloud. 

### Architecture
VPCs can offer all of the same resources as an independent network environment set up on specific hardware. 
Users can access virtual CPUs, storage (equivalent to hard drive space) and networking functions such as load balancers, routers and proxies. 
All of these features are software implemented and can be scaled up and down as required. 

##Benefits over hardware networks
VPCs are rapidly scalable, as additional computing resources can be brought within the perimeter of the cloud without the need to install extra hardware. 
This also comes with cost benefits, as there is no requirement to purchase and maintain hardware. Due to the scale of cloud hosting providers, these costs can be shared among customers to make the per user/per server cost significantly lower. 

##Potential drawbacks
As the VPC is hosted on third party hardware, you are not in control of uptime of that hardware and rely on the procedures put in place by the public cloud provider. 
As the perimeter is only based on logical access controls, the risk of unauthorised access may be greater than a private cloud on specific hardware to which no others have access.  
