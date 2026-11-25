---
title: "Worklog Tuần 2"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Nắm kiến trúc mạng trên AWS.
* Tự xây dựng VPC với subnet public/private.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | Tìm hiểu hạ tầng toàn cầu AWS: Region, Availability Zone, Edge Location. | 21/09/2026 | 21/09/2026 | [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/) |
| 3   | Học VPC: CIDR, subnet, route table, Internet Gateway; thực hành tạo VPC. | 22/09/2026 | 22/09/2026 | [What is Amazon VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) |
| 4   | Học Security Group và Network ACL; thực hành giới hạn truy cập theo cổng. | 23/09/2026 | 23/09/2026 | [Security Groups](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html)<br>[Network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) |
| 5   | Học NAT Gateway và VPC Endpoint; thực hành cho subnet private ra Internet. | 24/09/2026 | 24/09/2026 | [NAT gateways](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html) |
| 6   | Tìm hiểu VPC Peering và Transit Gateway; so sánh các cách kết nối mạng. | 25/09/2026 | 25/09/2026 | [VPC Peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html)<br>[Transit Gateway](https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html) |

### Kết quả đạt được tuần 2:

* Tạo được VPC, subnet, route table, Internet Gateway và NAT Gateway.
* Phân biệt Security Group với NACL; biết khi nào dùng Peering hoặc Transit Gateway.
