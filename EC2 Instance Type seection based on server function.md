

#### Summary	
Different EC2 instance types are recommended based on the server function.
This article covers the latest recommendation for each software.


#### Related Content	
- https://aws.amazon.com/ec2/instance-types/

#### Server Function and Recommended EC2 instance type
|Server Function   	|Instance Type and Generation   	|
|---	|---	|
|Qlik Sense Engines   	|<b>r7a</b> or <b>c7a</b> (more expensive but exceptional performance)   	|
|Qlik Sense Schedulers   	|<b>r7a</b>   	|
|Qlik Sense Central (no other role)   	|<b>m7a</b>   	|
|Qlik Sense Central (multi-purpose)   	|<b>r7a</b>   	|
|QlikView Server   	|<b>r7a</b>   	|
|QlikView Publisher   	|<b>r7a</b>   	|
|Qlik NPrinting   	|<b>m7a</b> or <b>t3a</b> (if server usage is low)   	|
|Qlik Analytics Platform (QAP)   	|<b>z1d</b> (higher RAM vs. CPU ratio)   	|
|Qlik GeoAnalytics Server   	|<b>r7a</b>    	|

#### Notes:

- <b>r7a</b>: memory-optimized servers, current generation, AMD processors, https://aws.amazon.com/ec2/instance-types/r7a/ 
- <b>m7a</b>: general purpose, current generation, AMD processors, https://aws.amazon.com/ec2/instance-types/m7a/
- <b>t3a</b>: low-cost burstable general purpose, current generation, AMD processors, https://aws.amazon.com/ec2/instance-types/t3/
- <b>z1d</b>: high memory to CPU ratio, current generation, custom Intel processor, https://aws.amazon.com/ec2/instance-types/z1d/
- <b>c7a</b>: compute-optimized servers, current generation, AMD processors, https://aws.amazon.com/ec2/instance-types/c7a/

<b>Reference</b>: https://aws.amazon.com/ec2/instance-types/







