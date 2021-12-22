FROM amazonlinux:2

RUN yum -y update && yum -y install python3 && yum clean all && rm -rf /var/cache/yum
RUN python3 -m pip install requests boto3 awscli requests_aws4auth
