# Ccount AWS Public IPv4

## AWS will charge for public IPv4 in 2024, how many IPv4 do you have?

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