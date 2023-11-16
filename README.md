# Count AWS Public IPv4

## AWS will charge for public IPv4 in 2024, how many IPv4 do you have?

- [The Register - AWS: IPv4 addresses cost too much, so you’re going to pay](https://www.theregister.com/2023/07/31/aws_says_ipv4_addresses_cost/)
- [AWS Blog – AWS Public IPv4 Address Charge + Public IP Insights
](https://aws.amazon.com/blogs/aws/new-aws-public-ipv4-address-charge-public-ip-insights/)
- [AWS Blog - Identify and optimize public IPv4 address usage on AWS
](https://aws.amazon.com/blogs/networking-and-content-delivery/identify-and-optimize-public-ipv4-address-usage-on-aws/)

## How to run?

- git glone git@github.com:lichti/count_aws_public_ipv4.git
- cd count_aws_public_ipv4
- virtualenv venv
- source venv/bin/activate
- pip install boto3
- mv credentials.ini.example credentials.ini
- mv settings.ini.example settings.ini
- edit credentials.ini and settings.ini
- python count-aws-ips.py | tee my_aws_ipv4_report.txt
