
𝐍𝐞𝐭𝐰𝐨𝐫𝐤𝐢𝐧𝐠 𝐢𝐧 𝐀𝐖𝐒

𝐀𝐖𝐒 𝐕𝐏𝐂 𝐚𝐧𝐝 𝐢𝐭𝐬 𝐚𝐬𝐬𝐨𝐜𝐢𝐚𝐭𝐞𝐝 𝐜𝐨𝐦𝐩𝐨𝐧𝐞𝐧𝐭𝐬 𝐢𝐧 𝐛𝐫𝐢𝐞𝐟:

𝐀𝐖𝐒 𝐕𝐏𝐂: A VPC is a logically isolated section of the AWS Cloud where you can launch AWS resources in a private network. You can have multiple VPCs in an AWS account, and each VPC can have multiple subnets.

𝐒𝐮𝐛𝐧𝐞𝐭: A subnet is a range of IP addresses in a VPC. You can launch AWS resources into subnets, and you can use route tables to control how traffic flows between subnets.

𝐑𝐨𝐮𝐭𝐞 𝐭𝐚𝐛𝐥𝐞: A route table is a set of rules that determine how traffic is routed within a VPC. It specifies the destination IP address or network range and the target gateway or subnet.

𝐈𝐧𝐭𝐞𝐫𝐧𝐞𝐭 𝐠𝐚𝐭𝐞𝐰𝐚𝐲: An internet gateway allows instances in a VPC to communicate with the internet.

𝐍𝐀𝐓 𝐠𝐚𝐭𝐞𝐰𝐚𝐲: A NAT gateway allows instances in a private subnet to communicate with the internet without having public IP addresses.

𝐄𝐥𝐚𝐬𝐭𝐢𝐜 𝐈𝐏 𝐚𝐝𝐝𝐫𝐞𝐬𝐬: An Elastic IP address is a static public IP address that you can associate with an instance in your VPC. This allows you to access the instance from the internet.

𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐠𝐫𝐨𝐮𝐩: A security group is a firewall that controls incoming and outgoing traffic to and from an instance.

𝐍𝐞𝐭𝐰𝐨𝐫𝐤 𝐚𝐜𝐜𝐞𝐬𝐬 𝐜𝐨𝐧𝐭𝐫𝐨𝐥 𝐥𝐢𝐬𝐭 (𝐀𝐂𝐋): An ACL is a firewall that controls traffic between subnets in a VPC.

𝐕𝐏𝐂 𝐩𝐞𝐞𝐫𝐢𝐧𝐠: VPC peering allows you to connect two VPCs in the same AWS account or different AWS accounts.

𝐕𝐏𝐂 𝐞𝐧𝐝𝐩𝐨𝐢𝐧𝐭: A VPC endpoint allows instances in a VPC to communicate with AWS services without having to go through the internet.

𝐕𝐏𝐂 𝐅𝐥𝐨𝐰 𝐋𝐨𝐠𝐬: Flow logs capture information about IP traffic going into and out of network interfaces in your VPC. They can be useful for troubleshooting, monitoring, and security analysis.

In addition to these core components, there are a number of other VPC components that you can use to customize your network, such as:

𝐀𝐖𝐒 𝐓𝐫𝐚𝐧𝐬𝐢𝐭 𝐆𝐚𝐭𝐞𝐰𝐚𝐲: A Transit Gateway is a central routing hub for your VPCs. It allows you to connect your VPCs to each other and to other AWS services, such as VPNs and Direct Connect.

𝐀𝐖𝐒 𝐍𝐞𝐭𝐰𝐨𝐫𝐤 𝐅𝐢𝐫𝐞𝐰𝐚𝐥𝐥: AWS Network Firewall is a managed firewall service that you can use to protect your VPCs from malicious traffic.

𝐀𝐖𝐒 𝐖𝐀𝐅: AWS WAF is a web application firewall service that you can use to protect your web applications from common web attacks.
