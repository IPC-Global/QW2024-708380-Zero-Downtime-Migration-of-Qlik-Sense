### Summary

Different EC2 instance types are recommended based on the server function. This article covers the latest recommendations for each software.

#### Related Content	
- [AWS EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)

#### Server Function and Recommended EC2 Instance Type

| Server Function                   | Instance Type and Generation                      |
|-----------------------------------|---------------------------------------------------|
| Qlik Sense Engines                | 💻 <b>r7a</b> or 💻 <b>c7a</b> (more expensive but exceptional performance) |
| Qlik Sense Schedulers             | 💻 <b>r7a</b> |
| Qlik Sense Central (no other role)| 💻 <b>m7a</b> |
| Qlik Sense Central (multi-purpose)| 💻 <b>r7a</b> |
| QlikView Server                   | 💻 <b>r7a</b> |
| QlikView Publisher                | 💻 <b>r7a</b> |
| Qlik NPrinting                    | 💻 <b>m7a</b> or 💻 <b>t3a</b> (if server usage is low) |
| Qlik Analytics Platform (QAP)     | 💻 <b>z1d</b> (higher RAM vs. CPU ratio) |
| Qlik GeoAnalytics Server          | 💻 <b>r7a</b> |

#### Notes:

| Instance Type | Description                                     | Link                                           |
|---------------|-------------------------------------------------|------------------------------------------------|
| **r7a**       | Memory-optimized servers, current generation, AMD processors | [More Info](https://aws.amazon.com/ec2/instance-types/r7a/) |
| **m7a**       | General purpose, current generation, AMD processors       | [More Info](https://aws.amazon.com/ec2/instance-types/m7a/) |
| **t3a**       | Low-cost burstable general purpose, current generation, AMD processors | [More Info](https://aws.amazon.com/ec2/instance-types/t3/) |
| **z1d**       | High memory to CPU ratio, current generation, custom Intel processor | [More Info](https://aws.amazon.com/ec2/instance-types/z1d/) |
| **c7a**       | Compute-optimized servers, current generation, AMD processors | [More Info](https://aws.amazon.com/ec2/instance-types/c7a/) |

<b>Reference</b>: [AWS EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)
