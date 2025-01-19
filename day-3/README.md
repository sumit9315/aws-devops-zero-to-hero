# What will you learn 

## Introduction to EC2:

What is EC2, and why is it important?

'''
ECC--->ELastic Cloud Compute
Compute means provide Compute resource like  CPU,RAM,DISK (in general Virtual Server...i.e AWS buy many physical server and install hypervisore and sell each server)
Cloud means compute service available on public cloud like AWS which can be used by anyone like pay as u use/go model.
Elastic means these service are scalable like we can increase/decrese RAM/CPU/Disk size as per requirement and use and also we can attach extra service like s3 bucket/cloudwatch etc if required easily. 
'''
Elastic Cloud Compute (EC2)
Compute
Refers to the provisioning of computational resources like CPU, RAM, and Disk.

EC2 essentially provides virtual servers.
AWS achieves this by purchasing physical servers, installing hypervisors on them, and selling slices of these servers as virtual machines.
Cloud
Indicates that the compute services are available over the public cloud, like AWS.

Accessible globally to anyone with an internet connection.
Operates on a pay-as-you-use/go model, offering flexibility and cost-efficiency.
Elastic
Highlights the scalability of these services:

You can scale up or down resources such as RAM, CPU, or Disk size based on your needs.
Additional services, such as S3 buckets, CloudWatch, and others, can be easily integrated as required.

```
- Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud.
- Access reliable, scalable infrastructure on demand. Scale capacity within minutes with SLA commitment of 99.99% availability.
- Provide secure compute for your applications. Security is built into the foundation of Amazon EC2 with the AWS Nitro System.
- Optimize performance and cost with flexible options like AWS Graviton-based instances, Amazon EC2 Spot instances, and AWS Savings Plans.
```

EC2 usecases

```
Deliver secure, reliable, high-performance, and cost-effective compute infrastructure to meet demanding business needs.
Access the on-demand infrastructure and capacity you need to run HPC applications faster and cost-effectively.
Access environments in minutes, dynamically scale capacity as needed, and benefit from AWS’s pay-as-you-go pricing.
Deliver the broadest choice of compute, networking (up to 400 Gbps), and storage services purpose-built to optimize price performance for ML projects
```

EC2 Instance Types

Recommended to follow [this](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html) page for very detailed and updated information.

General purpose

```
General Purpose instances are designed to deliver a balance of compute, memory, and network resources. They are suitable for a wide range of applications, including web servers,
small databases, development and test environments, and more.
```

Compute optimized

```
Compute Optimized instances provide a higher ratio of compute power to memory. They excel in workloads that require high-performance processing such as batch processing, 
scientific modeling, gaming servers, and high-performance web servers.
```

Memory optimized

```
Memory Optimized instances are designed to handle memory-intensive workloads. They are suitable for applications that require large amounts of memory, such as in-memory databases,
real-time big data analytics, and high-performance computing.
```

Storage optimized

```
Storage Optimized instances are optimized for applications that require high, sequential read and write access to large datasets. 
They are ideal for tasks like data warehousing, log processing, and distributed file systems.
```

Accelerated computing

```
Accelerated Computing Instances typically come with one or more types of accelerators, such as Graphics Processing Units (GPUs),
Field Programmable Gate Arrays (FPGAs), or custom Application Specific Integrated Circuits (ASICs). 
These accelerators offload computationally intensive tasks from the main CPU, enabling faster and more efficient processing for specific workloads.
```

![image](https://github.com/iam-veeramalla/aws-devops-zero-to-hero/assets/43399466/fc8e083c-dba5-41a6-94b9-14ebef0255c1)

Instance families

```
    C – Compute

    D – Dense storage

    F – FPGA

    G – GPU

    Hpc – High performance computing

    I – I/O

    Inf – AWS Inferentia

    M – Most scenarios

    P – GPU

    R – Random access memory

    T – Turbo

    Trn – AWS Tranium

    U – Ultra-high memory

    VT – Video transcoding

    X – Extra-large memory
```

Additional capabilities

```
    a – AMD processors

    g – AWS Graviton processors

    i – Intel processors

    d – Instance store volumes

    n – Network and EBS optimized

    e – Extra storage or memory

    z – High performance
```

## EC2 Instance Basics:

Understanding the concept of virtual servers and instances.
Key components of an EC2 instance: AMI (Amazon Machine Image), instance types, and instance states.
Differentiating between On-Demand, Reserved, and Spot instances.

## Launching an EC2 Instance:

- Step-by-step guide on launching an EC2 instance using the AWS Management Console.
- Configuring instance details, such as instance type, network settings, and storage options.
- Understanding security groups and key pairs for securing instances.

## Managing EC2 Instances:

- Starting, stopping, and terminating instances.
- Monitoring instance performance and utilization.
- Basic troubleshooting and accessing instances using SSH (Secure Shell).
