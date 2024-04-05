# VPC

How can one host within a VPC any services that need to be public?

To host services within a VPC that need to be public, you can create a public subnet within your VPC with access to the internet gateway. This subnet is designated for hosting publicly accessible services. Ensure security by configuring appropriate security groups and network ACLs to control inbound and outbound traffic, while keeping necessary ports open securely. Additionally, allocate Elastic IP addresses to instances or services within the public subnet to provide static public IP addresses for external access.

What are examples of services that would live in the publicly-accessible part of the VPC? The privately-accessible part?

Public:

Web servers hosting public websites or web applications
APIs providing access to external clients
Load balancers distributing traffic to backend servers
DNS servers resolving domain names for public access

Private:

Database servers storing sensitive data
Internal applications or services that do not require direct external access
Backend services accessed only by other services within the VPC
Development or testing environments not meant for public access

What are the trade-offs of using a VPC vs traditional infrastructure?

Scalability: VPCs offer scalability by allowing you to easily scale resources up or down based on demand, while traditional infrastructure may require manual intervention for scaling.

Security: VPCs provide better security by allowing you to define and enforce network access controls using security groups and network ACLs, whereas traditional infrastructure may require additional network security measures to be implemented.

Cost: VPCs may have cost advantages due to pay-as-you-go pricing models and the ability to optimize resource usage, whereas traditional infrastructure may involve higher upfront costs for hardware and ongoing maintenance expenses.

Flexibility: VPCs offer flexibility by allowing you to quickly deploy and manage resources using APIs or management consoles, whereas traditional infrastructure may involve longer deployment times and manual configuration processes.

Complexity: VPCs can introduce complexity, especially for those unfamiliar with cloud networking concepts, whereas traditional infrastructure may offer a simpler setup for some use cases.

## Things I want to know more about

N/A

### Source

https://www.cloudflare.com/learning/cloud/what-is-a-virtual-private-cloud/