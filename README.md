# Coupon Distribution System

## Introduction
This is a Coupon Distribution Platform for both consumers and merchants. Customers can easily get and manage their coupons in this platform where Merchants can directly distribute them. Considering when some limited coupons come out a huge amount of customers would rush to get them, we would use Kafka to solve the problem of real-time data processing of a very large scale of messages. Also, we would use HBase to implement the storage of customers' information to ensure the read and write efficiency. After the implementation of our platform, we plan to use PostMan to test our APIs and JMeter to finish the stress testing.
## Development Tools
- Tools：Maven, JDK8, HBase, Kafka, MySQL
- Development Environment：Intellij IDEA
- Cache：Redis
- Framework：SpringBoot
## Application Structure
<img src="./asset/application_structure.png">

## [Technology Structure](https://github.com/jiaqi-xiao/Coupon-Distribution-System/blob/master/doc/Technology_Structure.md)

- Cache Design
- Utility
- Log
- Exception
- Table Structure

## Merchant Subsystem

## Customer Subsystem