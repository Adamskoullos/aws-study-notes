# Choosing Region

1. Compliance
2. Proximity to customers
3. Available services within region
4. Pricing

## Regions & Availability Zones

![Screenshot from 2021-06-11 10-31-26](https://user-images.githubusercontent.com/73107656/121665483-4a983800-caa0-11eb-8c09-0d7cd5993702.png)

# Amazon CloudFront

AWS has edge locations where data is cached in memory and available closer to the user. CloudFront is AWS **CDN**.

# Provisioning AWS Resources

Setting up an infrastructure can be done via the `management console`, by using scripts `in the terminal` or through `AWS SDK's` by writing code within applications.

There are also a couple of management tools that assist in automating this process:

1. AWS **Elastic Beanstalk** can be set up and configured through code and manages:
   - Adjust capacity
   - Load balancing
   - Auto scaling
   - Application health monitoring
2. **CloudFormation** can be used to automate each new environment
