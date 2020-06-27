## Web Application Firewalls in the Cloud

There are a few different ways of incorporating WAF protection to defend against application level exploits.

### Cloud-Based WAF product

There are many vendors, such as Akamai or Cloudflare, which web clients point to as an entry point into your application. These are designated as CDN providers, however they provide WAF capabilities as part of their offering.

Cloud providers such as AWS also provide this type of service natively. AWS WAF can be placed in front of public facing application services such as CloudFront and API Gateway transparently so that application endpoints do not need to change.

#### WAF appliance

A WAF appliance or network based WAF can be deployed into a VPC to protect EC2 based application traffic. These can be costly and complex to implement and what you would typically find in a traditional data center environment.

Example vendors include:

-   F5
-   Fortinet
-   Imperva
-   etc.

### Host-Based WAFs

These products attempt to provide similar defense but are deployed as part of a web applications server instance.

#### Serverless Security Tools

Serverless applications also need to be defended. Many products offer capabilities to defend serverless applications from application exploits.

Example products include:

-   Aqua
-   Twistlock
-   PureSec

## WAF Best Practices

1. Test and Fine Tune WAF Rules
   Set up the WAF with identical configuration in lower environments for testing to ensure that your applications still work as expected in production. Fine tuning may be required to rule out false positives.

2. Penetration Testing
   Perform penetration and exploit testing against applications to ensure that the WAF defends as expected. Test both with and without the WAF to get a better understanding of defensive capabilities.

3. Logging
   Enable WAF logging and export logs to your security monitoring tools.

4. Discovery
   Identify all public endpoints for your applications including CloudFront, Application Load Balancers, API Gateway. If your application is exposed to the internet with other methods, consider moving your application behind these mentioned services.

Once identified, put together a plan to start defending your applications with a web application firewall.
