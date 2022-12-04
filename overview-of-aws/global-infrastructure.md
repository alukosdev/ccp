---
order: 600
---

:::banner
The following content is derived from the **Global infrastructure** section of the [Overview of Amazon Web Services](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/amazon-web-services-cloud-platform.html){ target="_blank" } whitepaper. It has been modified to align with current exam objectives.
:::

# Global infrastructure

## Components

- [Regions](#regions)
  - [Availability Zones](#availability-zones)
- [Edge Locations](#edge-locations)

==- Regions
An AWS Region is a physical location in the world that contains multiple Availability Zones.

Key features:
- Contains a minimum of two Availability Zones.

Region naming:

- `us` = Area
- `east` = Sub-area
- `2` = Number
- `us-east-2` = Region Name

==- Availability Zones
> Availability Zones consist of one or more discrete data centers, each with redundant power, networking, and connectivity, housed in separate facilities. These Availability Zones offer you the ability to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center.

Availability: Extent to which an application is fulfilling its intended business purpose. Applications that are highly-available are built in a manner where a single failure won't lessen the application's ability to be fully operational.

Key features:
- Consists of one or more data centers, offering high availability, fault tolerance, and scalability.
- Availability Zones are located within the geographic area of the AWS Region it is contained in.
- Availability Zones contain redundant power, networking, and connectivity.

AZ naming:

- `us` = Area
- `east` = Sub-area
- `2` = Number
- `a` = AZ
- `us-east-2a` = AZ Name

!!!
The primary purpose of an Availability Zone is to enable high availability.
!!!
==- Edge Locations
Key features:

- Used as nodes of a global content delivery network (CDN).
- AWS has two specific services that leverage edge locations: CloudFront and Route 53.
- Located globally at over 200 different locations.
- Allows AWS to serve content from locations closest to users.
!!!
The primary purpose of an AWS Edge Location is to serve content where it is closest to end users.
!!!
==-