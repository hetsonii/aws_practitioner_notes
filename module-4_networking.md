# Module 4 - Networking

### Amazon Virtual Private Cloud (VPC)

### Internet Gateway (IGW):
- For public-facing VPCs

### AWS Direct Connect:
- Dedicated private connection from a private data center to AWS

### Network Access Control Lists (ACL):
- Manages both incoming and outgoing traffic in VPC
- Allows all inbound and outbound traffic by default
- Stateless (Basically like zero trust)

### Security Groups:
- Instance-level security
- Default EC2 security group blocks everything inbound
- All outbound traffic is always allowed to leave
- Stateful (Remembers stuff)

### Amazon Route 53 routing policies:
- Latency-based routing
- Geolocation DNS
- Geoproximity routing
- Weighted round-robin
