# OOTB Rules

[Docs](https://docs.datadoghq.com/) > [Datadog
Security](https://docs.datadoghq.com/security/) > [OOTB
Rules](https://docs.datadoghq.com/security/default_rules/)

Datadog provides out-of-the-box (OOTB) [detection
rules](https://docs.datadoghq.com/security/detection_rules/) to flag attacker
techniques and potential misconfigurations so you can immediately take steps
to remediate. Datadog continuously develops new default rules, which are
automatically imported into your account, your Application Security Management
library, and the Agent, depending on your configuration.

Datadog's Security Research team continuously adds new OOTB security detection
rules. While the aim is to deliver high-quality detections with the release of
integrations or other new features, the performance of these detections at
scale often needs to be observed before making the rule generally available.
These rules contain a Beta tag. This gives Datadog's Security Research team
time to either refine or deprecate detection opportunities that do not meet
Datadog's standards.

Click the following buttons to filter the detection rules. Security detection
rules are available for [Application Security
Management](https://docs.datadoghq.com/security/application_security/), [Cloud
SIEM](https://docs.datadoghq.com/security/cloud_siem/) (log detection and
signal correlation), [CSM
Misconfigurations](https://docs.datadoghq.com/security/cloud_security_management/misconfigurations/)
(cloud and infrastructure), [CSM
Threats](https://docs.datadoghq.com/security/threats/), [CSM Identity
Risks](https://docs.datadoghq.com/security/cloud_security_management/identity_risks/),
and [Attack
Paths](https://docs.datadoghq.com/security/security_inbox/?s=attack%20path#types-
of-findings-in-security-inbox).

AllAPPLICATION SECURITYATTACK PATHSCLOUD SIEM (LOG DETECTION)CLOUD SIEM
(SIGNAL CORRELATION)CSM IDENTITY RISKSCSM MISCONFIGURATIONS (CLOUD)CSM
MISCONFIGURATIONS (INFRA)CSM THREATS

![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)

1password ____

>

[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
1Password activity observed from Tor client IP  
](https://docs.datadoghq.com/security/default_rules/1password-activity-from-
tor-
ip/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
1Password service account token activity observed  
](https://docs.datadoghq.com/security/default_rules/1password-service-account-
token-
activity/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
1Password vault export attempt by user  
](https://docs.datadoghq.com/security/default_rules/1password-vault-
exfiltration-by-
user/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Anomalous amount of failed sign-in attempts by 1Password user  
](https://docs.datadoghq.com/security/default_rules/1password-anomalous-
failed-sign-in-by-
user/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Attempt to exfiltrate a 1Password item by user  
](https://docs.datadoghq.com/security/default_rules/1password-item-
exfiltration-by-
user/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Attempt to modify a 1Password item by user  
](https://docs.datadoghq.com/security/default_rules/1password-item-
modification-by-
user/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Impossible travel event observed from 1Password user  
](https://docs.datadoghq.com/security/default_rules/1password-impossible-
travel-
observed/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Unusual 1Password device authorization activity  
](https://docs.datadoghq.com/security/default_rules/1password-unusual-device-
authorization/)[![1password](https://static.datadoghq.com/static/images/logos/onepassword_avatar.svg)
Unusual 1Password item usage action observed from user  
](https://docs.datadoghq.com/security/default_rules/1password-unusual-item-
usage-action/)

![abnormal-
security](https://static.datadoghq.com/static/images/logos/abnormal-
security_avatar.svg)

Abnormal Security ____

>

[![abnormal-
security](https://static.datadoghq.com/static/images/logos/abnormal-
security_avatar.svg) Email with malicious attachment opened by user  
](https://docs.datadoghq.com/security/default_rules/abnormal-security-message-
with-malicious-attachment/)[![abnormal-
security](https://static.datadoghq.com/static/images/logos/abnormal-
security_avatar.svg) Email with spam category opened by user  
](https://docs.datadoghq.com/security/default_rules/abnormal-security-message-
with-spam/)[![abnormal-
security](https://static.datadoghq.com/static/images/logos/abnormal-
security_avatar.svg) Login attempt from new location detected  
](https://docs.datadoghq.com/security/default_rules/abnormal-security-unusual-
country-login/)[![abnormal-
security](https://static.datadoghq.com/static/images/logos/abnormal-
security_avatar.svg) Potential brute force attack detected  
](https://docs.datadoghq.com/security/default_rules/abnormal-security-brute-
force-login-fail/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

ACM ____

>

[![acm](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Certificate managed by ACM
should be renewed within 30 days of expiration  
](https://docs.datadoghq.com/security/default_rules/aws-acm-certificate-
managed-by-acm-should-be-renewed-within-30-days-of-
expiration/)[![acm](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Certificate managed by ACM
should be renewed within 7 days  
](https://docs.datadoghq.com/security/default_rules/aws-acm-certificate-
managed-by-acm-should-be-renewed-within-7-days/)[![acm](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Certificate managed by ACM should not be expired  
](https://docs.datadoghq.com/security/default_rules/aws-acm-certificate-
managed-by-acm-should-not-be-expired/)[![acm](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Certificates managed by ACM should be validated  
](https://docs.datadoghq.com/security/default_rules/aws-acm-certificates-
managed-by-acm-should-be-validated/)[![acm](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
RSA certificates managed by AWS ACM should use a key length of at least 2,048
bits  
](https://docs.datadoghq.com/security/default_rules/aws-acm-rsa-certificates-
managed-by-aws-acm-should-use-a-key-length-of-at-least-2048-bits/)

![amazon-backup](https://static.datadoghq.com/static/images/logos/amazon-
backup_avatar.svg)

Amazon Backup ____

>

[![amazon-backup](https://static.datadoghq.com/static/images/logos/amazon-
backup_avatar.svg) Backup recovery points should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-backup-recovery-point-
backup-recovery-points-should-be-encrypted-at-rest/)

![amazon-dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg)

Amazon Dms ____

>

[![amazon-dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg) DMS replication instances should not be public  
](https://docs.datadoghq.com/security/default_rules/aws-dms-replication-
instance-dms-replication-instances-should-not-be-public/)

![amazon-ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg)

Amazon Ec2 ____

>

[![amazon-ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EBS default encryption should be enabled  
](https://docs.datadoghq.com/security/default_rules/aws-ebs-default-
encryption-ebs-default-encryption-should-be-enabled/)[![amazon-
ec2](https://static.datadoghq.com/static/images/logos/amazon-ec2_avatar.svg)
EC2 launch templates should not configure network interfaces with public IPs  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-launch-template-
version-ec2-launch-templates-should-not-configure-network-interfaces-with-
public-ips/)

![amazon-efs](https://static.datadoghq.com/static/images/logos/amazon-
efs_avatar.svg)

Amazon Efs ____

>

[![amazon-efs](https://static.datadoghq.com/static/images/logos/amazon-
efs_avatar.svg) EFS access points should enforce a root directory  
](https://docs.datadoghq.com/security/default_rules/aws-efs-access-point-efs-
access-points-should-enforce-a-root-directory/)[![amazon-
efs](https://static.datadoghq.com/static/images/logos/amazon-efs_avatar.svg)
EFS access points should enforce a user identity  
](https://docs.datadoghq.com/security/default_rules/aws-efs-access-point-efs-
access-points-should-enforce-a-user-identity/)[![amazon-
efs](https://static.datadoghq.com/static/images/logos/amazon-efs_avatar.svg)
EFS data should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-efs-file-system-efs-
data-should-be-encrypted-at-rest/)[![amazon-
efs](https://static.datadoghq.com/static/images/logos/amazon-efs_avatar.svg)
EFS file systems should be in backup plans  
](https://docs.datadoghq.com/security/default_rules/aws-efs-file-system-efs-
file-systems-should-be-in-backup-plans/)

![amazon-event-
bridge](https://static.datadoghq.com/static/images/logos/amazon-event-
bridge_avatar.svg)

Amazon Event Bridge ____

>

[![amazon-event-
bridge](https://static.datadoghq.com/static/images/logos/amazon-event-
bridge_avatar.svg) EventBridge custom event buses should have a resource-based
policy attached  
](https://docs.datadoghq.com/security/default_rules/aws-eventbridge-event-bus-
eventbridge-custom-event-buses-should-have-a-resource-based-policy-attached/)

![amazon-fsx](https://static.datadoghq.com/static/images/logos/amazon-
fsx_avatar.svg)

Amazon Fsx ____

>

[![amazon-fsx](https://static.datadoghq.com/static/images/logos/amazon-
fsx_avatar.svg) AWS FSx Excessive File Denied  
](https://docs.datadoghq.com/security/default_rules/aws-fsx-excessive-file-
denied/)

![amazon-msk](https://static.datadoghq.com/static/images/logos/amazon-
msk_avatar.svg)

Amazon Msk ____

>

[![amazon-msk](https://static.datadoghq.com/static/images/logos/amazon-
msk_avatar.svg) MSK clusters should be encrypted in transit among broker nodes  
](https://docs.datadoghq.com/security/default_rules/aws-msk-cluster-msk-
clusters-should-be-encrypted-in-transit-among-broker-nodes/)

![amazon-step-
functions](https://static.datadoghq.com/static/images/logos/amazon-step-
functions_avatar.svg)

Amazon Step Functions ____

>

[![amazon-step-
functions](https://static.datadoghq.com/static/images/logos/amazon-step-
functions_avatar.svg) Step Functions state machines should have logging turned
on  
](https://docs.datadoghq.com/security/default_rules/aws-step-function-step-
functions-state-machines-should-have-logging-turned-on/)

![amazon-vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg)

Amazon Vpc ____

>

[![amazon-vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) VPC flow logging should be enabled in all VPCs  
](https://docs.datadoghq.com/security/default_rules/aws-vpc-vpc-flow-logging-
should-be-enabled-in-all-vpcs/)

![apache](https://static.datadoghq.com/static/images/logos/apache_avatar.svg)

Apache ____

>

[![apache](https://static.datadoghq.com/static/images/logos/apache_avatar.svg)
Apache HTTP requests from security scanner  
](https://docs.datadoghq.com/security/default_rules/apache-scanner-detected/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

API Gateway ____

>

[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway access logging
should be enabled for V2 API stages  
](https://docs.datadoghq.com/security/default_rules/aws-apigatewayv2-stage-
api-gateway-access-logging-should-be-enabled-for-v2-api-
stages/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway execution
logging should be enabled for REST APIs  
](https://docs.datadoghq.com/security/default_rules/aws-apigateway-stage-api-
gateway-execution-logging-should-be-enabled-for-rest-
apis/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway execution
logging should be enabled for WebSocket APIs  
](https://docs.datadoghq.com/security/default_rules/aws-apigatewayv2-stage-
api-gateway-execution-logging-should-be-enabled-for-websocket-
apis/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway REST API cache
data should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-apigateway-stage-api-
gateway-rest-api-cache-data-should-be-encrypted-at-
rest/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway REST API stages
should be configured to use SSL certificates for backend authentication  
](https://docs.datadoghq.com/security/default_rules/aws-apigateway-stage-api-
gateway-rest-api-stages-should-be-configured-to-use-ssl-certificates-for-
backend-authentication/)[![api_gateway](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
API Gateway routes should specify an authorization type  
](https://docs.datadoghq.com/security/default_rules/aws-apigatewayv2-route-
api-gateway-routes-should-specify-an-authorization-
type/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateway stage REST API
should have AWS X-Ray tracing enabled  
](https://docs.datadoghq.com/security/default_rules/aws-apigateway-stage-api-
gateway-stage-rest-api-should-have-aws-x-ray-tracing-
enabled/)[![api_gateway](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API Gateways should be
associated with a WAF Web ACL  
](https://docs.datadoghq.com/security/default_rules/aws-apigateway-stage-api-
gateways-should-be-associated-with-a-waf-web-acl/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Application Security ____

>

[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) API scan detected on service  
](https://docs.datadoghq.com/security/default_rules/api-scan-
detected/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Attack Tool  
](https://docs.datadoghq.com/security/default_rules/tool-scanner-
detected/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Bruteforce attack  
](https://docs.datadoghq.com/security/default_rules/appsec-ato-
bf/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cassandra injection
vulnerability triggered  
](https://docs.datadoghq.com/security/default_rules/appsec-cass-injection-
vulnerability-trigger/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Command injection attempt detected  
](https://docs.datadoghq.com/security/default_rules/appsec-shell-
attempts/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Command injection exploited  
](https://docs.datadoghq.com/security/default_rules/shi-vulnerability-
trigger/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Commercial vulnerability
scanner  
](https://docs.datadoghq.com/security/default_rules/commercial-scanner-
detected/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) CQL injections attempts  
](https://docs.datadoghq.com/security/default_rules/appsec-cassandra-
attempts/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Credential Stuffing attack  
](https://docs.datadoghq.com/security/default_rules/appsec-ato-groupby-
ip/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Distributed Credential
Stuffing campaign (attacker fingerprint)  
](https://docs.datadoghq.com/security/default_rules/distributed-ato-ua-
asn/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Distributed Credential
Stuffing campaign (attempt count)  
](https://docs.datadoghq.com/security/default_rules/distributed-ato-
traces/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Distributed Credential
Stuffing campaign (user count)  
](https://docs.datadoghq.com/security/default_rules/distributed-ato-
users/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Excessive account deletion
from an IP  
](https://docs.datadoghq.com/security/default_rules/bl-account-deletion-
ratelimit/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Excessive payment failures
from IP  
](https://docs.datadoghq.com/security/default_rules/bl-payment-
failures/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Excessive resource
consumption of third-party API  
](https://docs.datadoghq.com/security/default_rules/appsec-
expensive_apis/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Excessive sensitive activity from an IP (SDK instrumented)  
](https://docs.datadoghq.com/security/default_rules/bl-rate-
limiting/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Excessive sensitive activity
from an IP (WAF instrumented)  
](https://docs.datadoghq.com/security/default_rules/bl-rate-limiting-
waf/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Feature returning private
information abused by IP  
](https://docs.datadoghq.com/security/default_rules/pii-leak/)[![application-
security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Impossible travel observed
from business logic event  
](https://docs.datadoghq.com/security/default_rules/impossible-
travel/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Java code injections
attempts  
](https://docs.datadoghq.com/security/default_rules/appsec-ognl-
attempts/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) JWT authentication bypass
attempt  
](https://docs.datadoghq.com/security/default_rules/appsec-jwt-auth-
bypass/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Local File Inclusion (LFI)
attack attempts  
](https://docs.datadoghq.com/security/default_rules/appsec-lfi-attempts-
errors/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Local file inclusion
exploited  
](https://docs.datadoghq.com/security/default_rules/lfi-vulnerability-
trigger/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Log4shell RCE attempts -
CVE-2021-44228  
](https://docs.datadoghq.com/security/default_rules/appsec-log4j-attack-
attempt/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Log4shell vulnerability
triggered (RCE) - CVE-2021-44228  
](https://docs.datadoghq.com/security/default_rules/appsec-log4j-vuln-
trigger/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Mongo injections attempts  
](https://docs.datadoghq.com/security/default_rules/appsec-mongo-
attempts/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) OGNL injection attack
attempts on routes parsing OGNL  
](https://docs.datadoghq.com/security/default_rules/appsec-ognl-attempts-
errors/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Password reset token
bruteforce  
](https://docs.datadoghq.com/security/default_rules/bl-password-reset-
bf/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Reflected XSS attempts on
routes returning HTML  
](https://docs.datadoghq.com/security/default_rules/appsec-reflected-
xss/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Resource enumeration
detected  
](https://docs.datadoghq.com/security/default_rules/appsec-ressource-
enumeration/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Security scanner detected  
](https://docs.datadoghq.com/security/default_rules/security-scan-
detected/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Spring4shell RCE attempts -
CVE-2022-22963  
](https://docs.datadoghq.com/security/default_rules/appsec-spring4shell-
attack-attempts/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL injection exploited  
](https://docs.datadoghq.com/security/default_rules/appsec-sql-injection-
vulnerability-trigger/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL injections attempts  
](https://docs.datadoghq.com/security/default_rules/appsec-sql-injection-
attempts-db-queries/)[![application-security](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SSRF attempts on routes executing network queries  
](https://docs.datadoghq.com/security/default_rules/appsec-ssrf-attempts-http-
calls/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) SSRF exploited  
](https://docs.datadoghq.com/security/default_rules/appsec-ssrf-vulnerability-
trigger/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unauthenticated activity
detected  
](https://docs.datadoghq.com/security/default_rules/bl-privilege-violation-
ip/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unauthorized activity
detected  
](https://docs.datadoghq.com/security/default_rules/bl-privilege-violation-
user/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unusual account creations
from an IP  
](https://docs.datadoghq.com/security/default_rules/bl-signup-
ratelimit/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unusual password reset rate
activity  
](https://docs.datadoghq.com/security/default_rules/bl-rate-limiting-pw-
reset/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User activity detected from
outside authorized countries  
](https://docs.datadoghq.com/security/default_rules/bl-login-geofencing-
allowlist/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User activity detected from
unauthorized countries  
](https://docs.datadoghq.com/security/default_rules/bl-login-geofencing-
denylist/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User activity from Tor  
](https://docs.datadoghq.com/security/default_rules/bl-user-
tor/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User enumeration through
password reset  
](https://docs.datadoghq.com/security/default_rules/bl-password-
reset/)[![application-security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User has changed country  
](https://docs.datadoghq.com/security/default_rules/new-geo/)[![application-
security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User has used a disposable
email address  
](https://docs.datadoghq.com/security/default_rules/disposable-email/)

![appsync](https://static.datadoghq.com/static/images/logos/amazon-
appsync_avatar.svg)

Appsync ____

>

[![appsync](https://static.datadoghq.com/static/images/logos/amazon-
appsync_avatar.svg) AppSync GraphQL APIs should have field-level logging
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-appsync-graphql-api-
appsync-graphql-apis-should-have-field-level-logging-
enabled/)[![appsync](https://static.datadoghq.com/static/images/logos/amazon-
appsync_avatar.svg) AppSync GraphQL APIs should not use API keys for
authentication  
](https://docs.datadoghq.com/security/default_rules/aws-appsync-graphql-api-
appsync-graphql-apis-should-not-use-api-keys-for-authentication/)

![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg)

Atlassian Event Logs ____

>

[![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg) Atlassian administrative API token activity observed  
](https://docs.datadoghq.com/security/default_rules/atlassian-organization-
administrative-api-token-observed/)[![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg) Atlassian administrator impersonated user  
](https://docs.datadoghq.com/security/default_rules/atlassian-organization-
admin-login-impersonation/)[![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg) Atlassian user added to administrative group  
](https://docs.datadoghq.com/security/default_rules/atlassian-organization-
user-added-to-admin-group/)[![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg) Atlassian user added to organization administrative group  
](https://docs.datadoghq.com/security/default_rules/atlassian-organization-
user-added-to-org-admin-group/)[![atlassian-event-
logs](https://static.datadoghq.com/static/images/logos/atlassian-event-
logs_avatar.svg) Atlassian user invited to organization as an organization
administrator  
](https://docs.datadoghq.com/security/default_rules/atlassian-organization-
user-invited-to-org-as-org-admin/)

![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)

Auth0 ____

>

[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Anomalous number of Auth0 Attack Protection events  
](https://docs.datadoghq.com/security/default_rules/auth0-anomalous-number-of-
attack-protection-events-
login/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 breached password detection disabled  
](https://docs.datadoghq.com/security/default_rules/auth0-breached-password-
detection-
disabled/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 brute-force protection disabled  
](https://docs.datadoghq.com/security/default_rules/auth0-brute-force-
protection-
disabled/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 Guardian MFA push notifications rejected by user  
](https://docs.datadoghq.com/security/default_rules/auth0-guardian-mfa-push-
rejected/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 Guardian MFA push notifications rejected by user followed by successful
login  
](https://docs.datadoghq.com/security/default_rules/auth0-guardian-mfa-push-
rejected-then-successful-
login/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 suspicious IP throttling disabled  
](https://docs.datadoghq.com/security/default_rules/auth0-suspicious-ip-
throttling-
disabled/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 tenant invitation sent to user  
](https://docs.datadoghq.com/security/default_rules/auth0-tenant-
invitation/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Auth0 user logged in with a breached password  
](https://docs.datadoghq.com/security/default_rules/auth0-breached-
password/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Brute force attack on an Auth0 user  
](https://docs.datadoghq.com/security/default_rules/auth0-brute-force-
attack/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Credential stuffing attack on Auth0  
](https://docs.datadoghq.com/security/default_rules/auth0-credential-stuffing-
attack/)[![auth0](https://static.datadoghq.com/static/images/logos/auth0_avatar.svg)
Impossible Travel Auth0 login  
](https://docs.datadoghq.com/security/default_rules/auth0-impossible-travel/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Autoscaling Group ____

>

[![autoscaling_group](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Auto Scaling group launch
configuration should configure EC2 instances to require IMDSv2  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-launch-
configuration-auto-scaling-group-launch-configuration-should-configure-
ec2-instances-to-require-imdsv2/)[![autoscaling_group](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Auto Scaling group launch configuration should not assign public IP addresses  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-launch-
configuration-auto-scaling-group-launch-configuration-should-not-assign-
public-ip-addresses/)[![autoscaling_group](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Auto Scaling groups associated with a Classic Load Balancer should use ELB
health checks  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-group-
auto-scaling-groups-associated-with-a-classic-load-balancer-should-use-elb-
health-checks/)[![autoscaling_group](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Auto Scaling groups should use multiple instance types across multiple
Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-group-
auto-scaling-groups-should-use-multiple-instance-types-across-multiple-
availability-zones/)[![autoscaling_group](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
EC2 Auto Scaling group should use multiple Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-group-
ec2-auto-scaling-group-should-use-multiple-availability-
zones/)[![autoscaling_group](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) EC2 Auto Scaling groups
should use Amazon EC2 launch templates  
](https://docs.datadoghq.com/security/default_rules/aws-autoscaling-group-
ec2-auto-scaling-groups-should-use-amazon-ec2-launch-templates/)

![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg)

AWS ____

>

[![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) AWS Verified Access anomalous failed authentication
attempts by host  
](https://docs.datadoghq.com/security/default_rules/aws-verified-access-
anomalous-failed-auth-by-
host/)[![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) AWS Verified Access anomalous failed authentication
attempts by IP  
](https://docs.datadoghq.com/security/default_rules/aws-verified-access-
anomalous-failed-auth-by-
ip/)[![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) AWS Verified Access anomalous failed authentication
attempts by user  
](https://docs.datadoghq.com/security/default_rules/aws-verified-access-
anomalous-failed-auth-by-
user/)[![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) Brute forced ConsoleLogin event correlates with an
assumed role event  
](https://docs.datadoghq.com/security/default_rules/aws-signal-correlation-
login-assumed-
role/)[![aws](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) ConsoleLogin event correlates privileged policy applying
to a role  
](https://docs.datadoghq.com/security/default_rules/aws-signal-correlation-
login-applied-role/)

![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg)

AWS Logging Log Metric ____

>

[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) 'root' account access should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-root-
account-access-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) AWS Config configuration changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-aws-
config-configuration-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) AWS Management Console authentication failures should
be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-aws-
management-console-authentication-failures-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) AWS Management Console sign-ins without MFA should be
monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-aws-
management-console-sign-ins-without-mfa-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) AWS Organizations changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-aws-
organizations-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) CloudTrail configuration changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-
cloudtrail-configuration-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Disabling or deletion of Customer-Managed Keys should
be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-disabling-
or-deletion-of-customer-managed-keys-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) IAM policy changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
policy-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Network ACL changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-network-
acl-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Network gateway changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-network-
gateway-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Route table changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-route-
table-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) S3 bucket policy changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-s3-bucket-
policy-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Security group changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-security-
group-changes-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) Unauthorized API calls should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-
unauthorized-api-calls-should-be-
monitored/)[![aws_logging_log_metric](https://static.datadoghq.com/static/images/logos/amazon-
web-services_avatar.svg) VPC changes should be monitored  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-vpc-
changes-should-be-monitored/)

![aws-iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg)

AWS Iam ____

>

[![aws-iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS accounts should be configured with security contact
information  
](https://docs.datadoghq.com/security/default_rules/aws-account-aws-accounts-
should-be-configured-with-security-contact-information/)

![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure ____

>

[![azure](https://static.datadoghq.com/static/images/logos/azure-active-
directory_avatar.svg) Azure Active Directory risky sign-in  
](https://docs.datadoghq.com/security/default_rules/azure-active-directory-
risky-sign-
in/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD brute force login  
](https://docs.datadoghq.com/security/default_rules/azure_portal_brute_force_login/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) Azure AD escalation from Global Administrator to
User Access Administrator  
](https://docs.datadoghq.com/security/default_rules/azure-ad-user-access-
admin-role-
escalation/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD Identity Protection risky user  
](https://docs.datadoghq.com/security/default_rules/azure-ad-identity-
protection-risky-
users/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD Login Without MFA  
](https://docs.datadoghq.com/security/default_rules/azure-ad-sign-in-without-
mfa/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD member assigned built-in Administrator role  
](https://docs.datadoghq.com/security/default_rules/azure-ad-user-assigned-
builtin-admin-
role/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD member assigned Global Administrator role  
](https://docs.datadoghq.com/security/default_rules/azure-ad-user-assigned-
global-admin-
role/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD new verified domain added to tenant  
](https://docs.datadoghq.com/security/default_rules/azure-ad-new-verified-
domain/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) Azure AD possible MFA fatigue attack  
](https://docs.datadoghq.com/security/default_rules/azure-ad-mfa-push-
fatigue/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) Azure AD possible MFA fatigue attack followed by
successful login  
](https://docs.datadoghq.com/security/default_rules/azure-ad-mfa-push-fatigue-
followed-by-successful-
login/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure AD Privileged Identity Management member assigned  
](https://docs.datadoghq.com/security/default_rules/azure-ad-pim-assign-admin-
role/)[![azure](https://static.datadoghq.com/static/images/logos/azure-active-
directory_avatar.svg) Azure AD sign in from AADinternals default user agent  
](https://docs.datadoghq.com/security/default_rules/azure-ad-aadinternals-
default-
useragent/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) Azure AD sign in from AzureHound default user
agent  
](https://docs.datadoghq.com/security/default_rules/azure-ad-azurehound-
default-
useragent/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) BETA Azure administrative unit created  
](https://docs.datadoghq.com/security/default_rules/azure-admin-unit-
created/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) BETA Azure administrative unit modified  
](https://docs.datadoghq.com/security/default_rules/azure-admin-unit-
modified/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
BETA Azure AI API keys listed from previously unseen application  
](https://docs.datadoghq.com/security/default_rules/azure-ai-api-keys-listed-
unusual-
application/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
BETA Azure AI API keys listed outside of known AI web portals  
](https://docs.datadoghq.com/security/default_rules/azure-ai-api-keys-listed-
outside-of-common-
applications/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
BETA Azure AI models listed directly through API  
](https://docs.datadoghq.com/security/default_rules/azure-ai-model-listed-
through-
api/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
BETA Azure AI service high volume of chat requests  
](https://docs.datadoghq.com/security/default_rules/azure-ai-service-high-
volume-chat-
requests/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
BETA Azure Bastion shareable link created  
](https://docs.datadoghq.com/security/default_rules/azure-bastion-host-
shareable-
link/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Datadog Log Forwarder Deleted  
](https://docs.datadoghq.com/security/default_rules/azure-datadog-log-
forwarder-
deleted/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure diagnostic setting deleted or disabled  
](https://docs.datadoghq.com/security/default_rules/azure-diagnostic-setting-
deleted-or-
disabled/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
vm_avatar.svg) Azure disk export URI created  
](https://docs.datadoghq.com/security/default_rules/azure-disk-export-uri-
created/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Firewall Threat Intelligence Alert  
](https://docs.datadoghq.com/security/default_rules/azure_firewall_threat_intelligence_alert/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Frontdoor WAF Blocked a Request  
](https://docs.datadoghq.com/security/default_rules/azure-frontdoor-waf-
blocked-a-
request/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Frontdoor WAF Logged a Request  
](https://docs.datadoghq.com/security/default_rules/azure-frontdoor-waf-
logged-a-
request/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Function has administrative privileges over resources  
](https://docs.datadoghq.com/security/default_rules/function-has-admin-
priv/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure group has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/group-blast-
radius/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure group has administrative privileges over resources  
](https://docs.datadoghq.com/security/default_rules/group-has-admin-
priv/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Login Explicitly Denied MFA  
](https://docs.datadoghq.com/security/default_rules/azure_login_explicitly_denied_mfa/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure managed identity has a large permissions gap  
](https://docs.datadoghq.com/security/default_rules/managed-identity-perms-
gap/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure managed identity has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/managed-identity-blast-
radius/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure managed identity has administrative privileges over resources  
](https://docs.datadoghq.com/security/default_rules/managed-identity-has-
admin-
priv/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Network Security Group Open to the World  
](https://docs.datadoghq.com/security/default_rules/azure-network-security-
group-open-to-the-
world/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Network Security Groups or Rules Created, Modified, or Deleted  
](https://docs.datadoghq.com/security/default_rules/azure_network_security_groups_rules_created_modified_or_deleted/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure new owner added for service principal  
](https://docs.datadoghq.com/security/default_rules/azure-add-owner-service-
principal/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure New Owner added to Azure Active Directory application  
](https://docs.datadoghq.com/security/default_rules/azure-new-owner-added-to-
application/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure New Service Principal created  
](https://docs.datadoghq.com/security/default_rules/azure-new-service-
principal-
created/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Policy Assignment Created  
](https://docs.datadoghq.com/security/default_rules/azure_policy_assignment_created/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) BETA Azure restricted management administrative
unit created  
](https://docs.datadoghq.com/security/default_rules/azure-restricted-mgmt-
admin-unit-
created/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) Azure Service Principal was assigned a role  
](https://docs.datadoghq.com/security/default_rules/azure-service-principal-
assigned-azure-
role/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
vm_avatar.svg) Azure snapshot export URI created  
](https://docs.datadoghq.com/security/default_rules/azure-snapshot-export-uri-
created/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure SQL Server Firewall Rules Created or Modified  
](https://docs.datadoghq.com/security/default_rules/azure_sql_server_firewall_rules_created_or_modified/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) BETA Azure user added to restricted management
administrative unit  
](https://docs.datadoghq.com/security/default_rules/azure-user-added-to-
restricted-mgmt-admin-
unit/)[![azure](https://static.datadoghq.com/static/images/logos/azure-active-
directory_avatar.svg) BETA Azure user granted scoped role assignment over
administrative unit  
](https://docs.datadoghq.com/security/default_rules/azure-user-granted-scoped-
role-assignment-over-admin-
unit/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure user has a large permissions gap  
](https://docs.datadoghq.com/security/default_rules/user-perms-
gap/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure user has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/user-blast-
radius/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure user has administrative privileges over resources  
](https://docs.datadoghq.com/security/default_rules/user-has-admin-
priv/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure user invited an external user  
](https://docs.datadoghq.com/security/default_rules/azure_user_invited_an_external_user/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
containerinstances_avatar.svg) Azure user ran command on container instance  
](https://docs.datadoghq.com/security/default_rules/azure-command-executed-in-
container-
instance/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
active-directory_avatar.svg) BETA Azure user removed from restricted
administrative unit  
](https://docs.datadoghq.com/security/default_rules/azure-user-removed-from-
restricted-mgmt-admin-
unit/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
cosmosdb_avatar.svg) Azure user viewed CosmosDB access keys  
](https://docs.datadoghq.com/security/default_rules/azure-cosmosdb-user-
listed-access-
keys/)[![azure](https://static.datadoghq.com/static/images/logos/azure-
cosmosdb_avatar.svg) Azure user viewed CosmosDB connection string  
](https://docs.datadoghq.com/security/default_rules/azure-cosmosdb-user-
listed-
connectionstrings/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Virtual Machine instance has administrative privileges over resources  
](https://docs.datadoghq.com/security/default_rules/vm-instance-has-admin-
priv/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Brute-forced user has assigned a role  
](https://docs.datadoghq.com/security/default_rules/azure_brute_forced_user_assigned_role/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Credential added to Azure AD application  
](https://docs.datadoghq.com/security/default_rules/azure-ad-credential-added-
to-
application/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Credential added to rarely used Azure AD application  
](https://docs.datadoghq.com/security/default_rules/azure-ad-credential-added-
to-application-new-
term/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Credential Stuffing Attack on Azure  
](https://docs.datadoghq.com/security/default_rules/azure_credential_stuffing_attack/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Microsoft 365 - Modification of Trusted Domain  
](https://docs.datadoghq.com/security/default_rules/m365-modification-of-
federated-
domain/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Potential Illicit Consent Grant attack via Azure registered application  
](https://docs.datadoghq.com/security/default_rules/azure-ad-consent-to-
application/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Tor client IP address identified within Azure environment  
](https://docs.datadoghq.com/security/default_rules/azure-tor-traffic-
identified/)[![azure](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
User ran a command on Azure Compute  
](https://docs.datadoghq.com/security/default_rules/azure_run_command_on_virtual_machine/)

![azure.active_directory](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.active Directory ____

>

[![azure.active_directory](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure custom administrator roles should be disabled  
](https://docs.datadoghq.com/security/default_rules/azure-role-definition-
azure-custom-administrator-roles-should-be-disabled/)

![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.activity Log ____

>

[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Create or Update Network Security Group' activity log alert should be
configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
create-or-update-network-security-group-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Create or Update Public Ip Address' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
create-or-update-public-ip-address-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Create or Update Security Solutions' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
create-or-update-security-solutions-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Create or Update SQL Server Firewall Rule' activity log alert should be
configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
create-or-update-sql-server-firewall-rule-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Create Policy Assignment' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
create-policy-assignment-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Delete Network Security Group' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
delete-network-security-group-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Delete Policy Assignment' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
delete-policy-assignment-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Delete Public Ip Address Rule' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
delete-public-ip-address-rule-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Delete Security Solution' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
delete-security-solution-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Delete SQL Server Firewall Rule' activity log alert should be configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
delete-sql-server-firewall-rule-activity-log-alert-should-be-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for 'Create or Update
Network Security Group'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-create-or-update-
network-security-
group/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for 'Delete Load Balancer'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-delete-load-
balancer/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for 'Delete Storage
Accounts'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-delete-storage-
accounts/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for creating or updating
storage accounts  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-creating-or-updating-
storage-
accounts/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for creating or updating
virtual machines  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-creating-or-updating-
virtual-
machines/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a activity log alert configured for deallocating virtual
machines  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-activity-log-alert-configured-for-deallocating-virtual-
machines/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Delete Key Vault'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-delete-key-
vault/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Delete MySQL
Database'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-delete-mysql-
database/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Delete PostgreSQL
Database'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-delete-postgresql-
database/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Rename Azure SQL
Database'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-rename-azure-sql-
database-/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Update Key Vault'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-update-key-
vault-/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for 'Update Security
Policy'  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-update-security-
policy-/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for deleting Network
Security Group  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-deleting-network-
security-
group/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for deleting policy
assignments  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-deleting-policy-
assignments/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for deleting the SQL
Server firewall rule  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-deleting-the-sql-
server-firewall-
rule/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for deleting VMs  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-deleting-
vms/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for load balancer updates  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-load-balancer-
updates/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for mysql database updates  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-mysql-database-
updates/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for PostgreSQL database
updates  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-postgresql-database-
updates/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for power off events  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-power-off-
events/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for security solutions
creation or updates  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-security-solutions-
creation-or-
updates/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Account should have a configured activity log alert for sql database updates  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
account-should-have-a-configured-activity-log-alert-for-sql-database-
updates/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The account should have a configured activity log alert for firewall rule
creation or update  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
the-account-should-have-a-configured-activity-log-alert-for-firewall-rule-
creation-or-
update/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The user should configure an activity log alert for SQL Database deletion  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
the-user-should-configure-an-activity-log-alert-for-sql-database-
deletion/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
User should have a 'Create Policy Assignment' activity log alert configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
user-should-have-a-create-policy-assignment-activity-log-alert-
configured/)[![azure.activity_log](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
User should have a 'Delete Security Solution' activity log alert configured  
](https://docs.datadoghq.com/security/default_rules/azure-activity-log-alert-
user-should-have-a-delete-security-solution-activity-log-alert-configured/)

![azure.app_service](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.app Service ____

>

[![azure.app_service](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The Azure App Service should be enabled with 'always on'  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-the-
azure-app-service-should-be-enabled-with-always-on/)

![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.appservice ____

>

[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
App Service should use the latest version of TLS encryption  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-app-
service-should-use-the-latest-version-of-tls-
encryption/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure App Service should have authentication enabled  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-azure-
app-service-should-have-authentication-
enabled/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure App Service should have remote debugging disabled  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-azure-
app-service-should-have-remote-debugging-
disabled/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should use the latest HTTP version available  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-azure-
should-use-the-latest-http-version-
available/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should use the latest Java version available  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-azure-
should-use-the-latest-java-version-
available/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should use the latest Python version available  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-azure-
should-use-the-latest-python-version-
available/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
FTP deployments should be disabled  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-ftp-
deployments-should-be-
disabled/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Incoming client certificates should be required to be 'On'  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-
incoming-client-certificates-should-be-required-to-be-
on/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The app service should enable registration with Azure Active Directory  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-the-app-
service-should-enable-registration-with-azure-active-
directory/)[![azure.appservice](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The web app should redirect all HTTP traffic to HTTPS  
](https://docs.datadoghq.com/security/default_rules/azure-app-service-the-web-
app-should-redirect-all-http-traffic-to-https/)

![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.compute ____

>

[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'OS and Data' disks should be encrypted with Customer Managed Key (CMK)  
](https://docs.datadoghq.com/security/default_rules/azure-managed-disk-os-and-
data-disks-should-be-encrypted-with-customer-managed-key-
cmk/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Unattached disks' should be encrypted with Customer Managed Key (CMK)  
](https://docs.datadoghq.com/security/default_rules/azure-managed-disk-
unattached-disks-should-be-encrypted-with-customer-managed-key-
cmk/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Privileged Azure Entra user is a guest account  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-ad-user-
guest-
priviliged/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Privileged Azure Entra user is synced from on-premises AD  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-ad-user-
synced-
priviliged/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM contains critical vulnerabilities found in CISA
KEV with greater than 15 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-vuln-15days-cisa-
kev/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM contains critical vulnerabilities which have
exploits available with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-vuln-30days-exploit-
available/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM contains critical vulnerabilities with greater
than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-
vuln-30days/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM contains high vulnerabilities with greater than
60 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-
vuln-60days/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM has privileged role and password-based SSH
authentication  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
basic-auth-ssh-
priviliged/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM instance contains critical vulnerability
CVE-2024-3094 (RCE in liblzma and xz versions 5.6.0 and 5.6.1)  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
xz-
vuln/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly Accessible Azure VM instance has a critical vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-
vulns/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly Accessible Azure VM instance has a privileged service account and a
critical vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-
privileged-public-critical-
vulns/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM uses password-based SSH authentication  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
basic-auth-
ssh/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Publicly accessible Azure VM with privileged service account contains critical
vulnerabilities with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-azure-vm-public-
critical-vuln-30days-
privileged/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Virtual machines in Azure should use SSH authentication keys for security  
](https://docs.datadoghq.com/security/default_rules/azure-virtual-machine-
instance-virtual-machines-in-azure-should-use-ssh-authentication-keys-for-
security/)[![azure.compute](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Virtual Machines should utilize Azure Managed Disks  
](https://docs.datadoghq.com/security/default_rules/azure-virtual-machine-
instance-virtual-machines-should-utilize-azure-managed-disks/)

![azure.containerregistry](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.containerregistry ____

>

[![azure.containerregistry](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Container registries should use private link  
](https://docs.datadoghq.com/security/default_rules/azure-container-registry-
azure-container-registries-should-use-private-link/)

![azure.dbformysql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.dbformysql ____

>

[![azure.dbformysql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SSL connection on MySQL Database Server should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-mysql-server-ssl-
connection-on-mysql-database-server-should-be-
enabled/)[![azure.dbformysql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
TLS Version should be set to 'TLSV1.2' for MySQL flexible Database Server  
](https://docs.datadoghq.com/security/default_rules/azure-mysql-flexible-
server-tls-version-should-be-set-to-tlsv1.2-for-mysql-flexible-database-
server/)

![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.dbforpostgresql ____

>

[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Access to Azure services for PostgreSQL Database Server should be disabled  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-firewall-
rule-access-to-azure-services-for-postgresql-database-server-should-be-
disabled/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Infrastructure double encryption for PostgreSQL Database Server should be
enabled  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
infrastructure-double-encryption-for-postgresql-database-server-should-be-
enabled/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Server parameter 'connection_throttling' should be enabled for PostgreSQL
Database Server  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
server-parameter-connection_throttling-should-be-enabled-for-postgresql-
database-
server/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Server parameter 'log_checkpoints' should be enabled for PostgreSQL Database
Server  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
server-parameter-log_checkpoints-should-be-enabled-for-postgresql-database-
server/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Server parameter 'log_connections' should be enabled for PostgreSQL Database
Server  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
server-parameter-log_connections-should-be-enabled-for-postgresql-database-
server/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Server parameter 'log_disconnections' should be enabled for PostgreSQL
Database Server  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
server-parameter-log_disconnections-should-be-enabled-for-postgresql-database-
server/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Server parameter 'log_retention_days' should be greater than 3 days for
PostgreSQL Database Server  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
server-parameter-log_retention_days-should-be-greater-than-3-days-for-
postgresql-database-
server/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SSL connection on PostgreSQL Database Server should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
ssl-connection-on-postgresql-database-server-should-be-
enabled/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The Azure PostgreSQL database server should use geo-redundant backups  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
the-azure-postgresql-database-server-should-use-geo-redundant-
backups/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The Azure PostgreSQL Database Server should use the current major version  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
the-azure-postgresql-database-server-should-use-the-current-major-
version/)[![azure.dbforpostgresql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The server should have the 'log_duration' parameter set to 'ON'  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
the-server-should-have-the-log_duration-parameter-set-to-on/)

![azure.dbmysql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.dbmysql ____

>

[![azure.dbmysql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Private endpoint should be enabled for MySQL servers  
](https://docs.datadoghq.com/security/default_rules/azure-mysql-server-
private-endpoint-should-be-enabled-for-mysql-servers/)

![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.keyvault ____

>

[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
All keys in non-RBAC Azure Key Vaults should have an expiration time set  
](https://docs.datadoghq.com/security/default_rules/azure-key-vault-all-keys-
in-non-rbac-azure-key-vaults-should-have-an-expiration-time-
set/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
All keys in RBAC Azure Key Vault should have an expiration time set  
](https://docs.datadoghq.com/security/default_rules/azure-key-vault-all-keys-
in-rbac-azure-key-vault-should-have-an-expiration-time-
set/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
All secrets in Non-RBAC Azure Key Vault should have an expiration time set  
](https://docs.datadoghq.com/security/default_rules/azure-key-vault-all-
secrets-in-non-rbac-azure-key-vault-should-have-an-expiration-time-
set/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
All secrets in RBAC Azure Key Vault should have an expiration time set  
](https://docs.datadoghq.com/security/default_rules/azure-key-vault-all-
secrets-in-rbac-azure-key-vault-should-have-an-expiration-time-
set/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Key Vault should be recoverable  
](https://docs.datadoghq.com/security/default_rules/azure-key-vault-azure-key-
vault-should-be-
recoverable/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Key Vault should use RBAC  
](https://docs.datadoghq.com/security/default_rules/azure_key_vault-azure-key-
vault-should-not-be-configured-with-access-
policy/)[![azure.keyvault](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Storage account encryption scopes should use customer-managed keys to encrypt
data at rest  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
storage-account-encryption-scopes-should-use-customer-managed-keys-to-encrypt-
data-at-rest/)

![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.kubernetes ____

>

[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
AKS Cluster should have public access limited  
](https://docs.datadoghq.com/security/default_rules/azure-aks-cluster-aks-
cluster-should-have-public-access-
limited/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
AKS cluster should use a network policy between nodes  
](https://docs.datadoghq.com/security/default_rules/azure-aks-cluster-aks-
cluster-should-use-a-network-policy-between-
nodes/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
AKS Kubelet configuration file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-aks-
kubelet-configuration-file-ownership-should-be-assigned-to-
root/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's kubelet configuration file ownership should be assigned to
root  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-configuration-file-ownership-should-be-assigned-to-
root/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet configuration file should disable anonymous requests  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-configuration-file-should-disable-anonymous-
requests/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's kubelet configuration file should have permissions set to 644
or more restrictive  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-configuration-file-should-have-permissions-set-to-644-or-
more-
restrictive/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should be allowed to manage iptables  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-be-allowed-to-manage-
iptables/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should have the eventRecordQPS entry set  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-have-the-eventrecordqps-entry-
set/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should not allow hostname overrides  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-not-allow-hostname-
overrides/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should only allow explicitly authorized requests  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-only-allow-explicitly-authorized-
requests/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should rotate client certificates automatically  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-rotate-client-certificates-
automatically/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet should rotate server certificates automatically  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelet-should-rotate-server-certificates-
automatically/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS Cluster's Kubelet's read-only port should be disabled  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
aks-clusters-kubelets-read-only-port-should-be-
disabled/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
An AKS's Kubelet should use TLS authentication  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-an-
akss-kubelet-should-use-tls-
authentication/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The AKS kubeconfig file should have permissions set to 644 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-the-
aks-kubeconfig-file-should-have-permissions-set-to-644-or-more-
restrictive/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The Private Cluster feature for AKS should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-aks-cluster-the-
private-cluster-feature-for-aks-should-be-
enabled/)[![azure.kubernetes](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Timeouts for streaming connections in an AKS worker node should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-aks-worker-node-
timeouts-for-streaming-connections-in-an-aks-worker-node-should-be-enabled/)

![azure.monitor](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.monitor ____

>

[![azure.monitor](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Diagnostic Setting should capture appropriate categories  
](https://docs.datadoghq.com/security/default_rules/azure-diagnostic-setting-
diagnostic-setting-should-capture-appropriate-categories/)

![azure.network](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.network ____

>

[![azure.network](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Bastion shareable links should not be permitted  
](https://docs.datadoghq.com/security/default_rules/azure-network-bastion-
host-azure-bastion-shareable-links-should-not-be-
permitted/)[![azure.network](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Subnets should be associated with a Network Security Group  
](https://docs.datadoghq.com/security/default_rules/azure-network-subnet-
subnets-should-be-associated-with-a-network-security-
group/)[![azure.network](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The network security group should allow specific port rules  
](https://docs.datadoghq.com/security/default_rules/azure-security-group-the-
network-security-group-should-allow-specific-port-rules/)

![azure.networkwatcher](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.networkwatcher ____

>

[![azure.networkwatcher](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Network Security Group Flow Log retention period should be 'greater than 90
days'  
](https://docs.datadoghq.com/security/default_rules/azure-network-watcher-
network-security-group-flow-log-retention-period-should-be-greater-
than-90-days/)

![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.security ____

>

[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should be configured to send email notifications about security alerts
with High severity  
](https://docs.datadoghq.com/security/default_rules/azure-security-contact-
azure-should-be-configured-to-send-email-notifications-about-security-alerts-
with-high-
severity/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should be configured with a security contact email  
](https://docs.datadoghq.com/security/default_rules/azure-security-contact-
azure-should-be-configured-with-a-security-contact-
email/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure should send security alert emails to subscription owners  
](https://docs.datadoghq.com/security/default_rules/azure-security-contact-
azure-should-send-security-alert-emails-to-subscription-
owners/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
PostgreSQL Database ingress traffic should be restricted to specified IP
addresses  
](https://docs.datadoghq.com/security/default_rules/azure-postgresql-server-
postgresql-database-ingress-traffic-should-be-restricted-to-specified-ip-
addresses/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Security Group should restrict HTTP(S) access from the internet  
](https://docs.datadoghq.com/security/default_rules/azure-security-group-
security-group-should-restrict-https-access-from-the-
internet/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Security Group should restrict RDP access from the internet  
](https://docs.datadoghq.com/security/default_rules/azure-security-group-
security-group-should-restrict-rdp-access-from-the-
internet/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Security Group should restrict SSH access from the internet  
](https://docs.datadoghq.com/security/default_rules/azure-security-group-
security-group-should-restrict-ssh-access-from-the-
internet/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Security Group should restrict UDP access from the internet  
](https://docs.datadoghq.com/security/default_rules/azure-security-group-
security-group-should-restrict-udp-access-from-the-
internet/)[![azure.security](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SQL Databases should only allow ingress traffic from specific IP addresses  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-sql-
databases-should-only-allow-ingress-traffic-from-specific-ip-addresses/)

![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.sql ____

>

[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Audit data for Azure SQL Server should be retained for greater than 90 days  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-audit-
data-for-azure-sql-server-should-be-retained-for-greater-
than-90-days/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Auditing on SQL Server should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-auditing-
on-sql-server-should-be-
enabled/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Active Directory Admin should be configured for Azure SQL  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-azure-
active-directory-admin-should-be-configured-for-azure-
sql/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Data encryption for SQL Database Server should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-database-
data-encryption-for-sql-database-server-should-be-
enabled/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Microsoft Defender for SQL Server should be on for critical SQL Servers  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-
microsoft-defender-for-sql-server-should-be-on-for-critical-sql-
servers/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Periodic recurring vulnerability assessment scans should be enabled on SQL
servers  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-periodic-
recurring-vulnerability-assessment-scans-should-be-enabled-on-sql-
servers/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Private endpoint connections on Azure SQL Database should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-private-
endpoint-connections-on-azure-sql-database-should-be-
enabled/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SQL Server Vulnerability Assessments should send scan reports to subscribed
admins  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-sql-
server-vulnerability-assessments-should-send-scan-reports-to-subscribed-
admins/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SQL server's Transparent Data Encryption (TDE) protector should be encrypted
with a customer-managed key  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-sql-
servers-transparent-data-encryption-tde-protector-should-be-encrypted-with-a-
customer-managed-
key/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
SQL servers should use customer-managed keys to encrypt data at rest  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-sql-
servers-should-use-customer-managed-keys-to-encrypt-data-at-
rest/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Vulnerability Assessment (VA) setting 'Also send email notifications to admins
and subscription owners' should be set for SQL servers  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-
vulnerability-assessment-va-setting-also-send-email-notifications-to-admins-
and-subscription-owners-should-be-set-for-sql-
servers/)[![azure.sql](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Vulnerability Assessment should be enabled for SQL server  
](https://docs.datadoghq.com/security/default_rules/azure-sql-server-
vulnerability-assessment-should-be-enabled-for-sql-server/)

![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.storage ____

>

[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Blob public access' should be disabled for storage accounts with blob
containers  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
blob-public-access-should-be-disabled-for-storage-accounts-with-blob-
containers/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
'Trusted Microsoft Services' should be enabled for Storage Account access  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
trusted-microsoft-services-should-be-enabled-for-storage-account-
access/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure storage accounts should not allow cross tenant replication  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
azure-storage-accounts-should-not-allow-cross-tenant-
replication/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Azure Storage should have soft delete enabled  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
azure-storage-should-have-soft-delete-
enabled/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Blob Containers anonymous access should be restricted  
](https://docs.datadoghq.com/security/default_rules/azure-storage-blob-
container-blob-containers-anonymous-access-should-be-
restricted/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Blob Service storage logging should be enabled for 'Read', 'Write', and
'Delete' requests  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
blob-service-storage-logging-should-be-enabled-for-read-write-and-delete-
requests/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Minimum TLS version for storage accounts should be set to Version 1.2  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
minimum-tls-version-for-storage-accounts-should-be-set-to-
version-1.2/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Secure transfer required should be enabled  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
secure-transfer-required-should-be-
enabled/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Storage account containing the blob container with activity logs should be
encrypted with Customer Managed Key  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
storage-account-containing-the-blob-container-with-activity-logs-should-be-
encrypted-with-customer-managed-
key/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Storage containers storing activity logs should only be accessible by
authorized personnel  
](https://docs.datadoghq.com/security/default_rules/azure-storage-blob-
container-storage-containers-storing-activity-logs-should-only-be-accessible-
by-authorized-
personnel/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Storage for critical data should be encrypted with Customer Managed Key  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
storage-for-critical-data-should-be-encrypted-with-customer-managed-
key/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Table Service storage logging should be enabled for 'Read', 'Write', and
'Delete' requests  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
table-service-storage-logging-should-be-enabled-for-read-write-and-delete-
requests/)[![azure.storage](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
The default network access rule for Storage Accounts should be set to deny  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-the-
default-network-access-rule-for-storage-accounts-should-be-set-to-deny/)

![azure.storage_account](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)

Azure.storage Account ____

>

[![azure.storage_account](https://static.datadoghq.com/static/images/logos/azure_avatar.svg)
Private Endpoints should be used to access Storage Accounts  
](https://docs.datadoghq.com/security/default_rules/azure-storage-account-
private-endpoints-should-be-used-to-access-storage-accounts/)

![checkpoint-quantum-
firewall](https://static.datadoghq.com/static/images/logos/checkpoint-quantum-
firewall_avatar.svg)

Checkpoint Quantum Firewall ____

>

[![checkpoint-quantum-
firewall](https://static.datadoghq.com/static/images/logos/checkpoint-quantum-
firewall_avatar.svg) BETA Checkpoint Quantum firewall ransomware infection
detected  
](https://docs.datadoghq.com/security/default_rules/checkpoint-quantum-
firewall-ransomware-infection-detected/)

![cisco-duo](https://static.datadoghq.com/static/images/logos/cisco-
duo_avatar.svg)

Cisco Duo ____

>

[![cisco-duo](https://static.datadoghq.com/static/images/logos/cisco-
duo_avatar.svg) Cisco Duo administrator locked out after too many failed login
attempts  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-administrator-
locked-out/)[![cisco-
duo](https://static.datadoghq.com/static/images/logos/cisco-duo_avatar.svg)
Cisco Duo application enumeration by user  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-application-
enumeration/)[![cisco-
duo](https://static.datadoghq.com/static/images/logos/cisco-duo_avatar.svg)
Cisco Duo brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-brute-force-
attack/)[![cisco-duo](https://static.datadoghq.com/static/images/logos/cisco-
duo_avatar.svg) Cisco Duo bypass code created by administrator  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-bypass-code-
created-by-admin/)[![cisco-
duo](https://static.datadoghq.com/static/images/logos/cisco-duo_avatar.svg)
Cisco Duo bypass code is used to authenticate user request  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-bypass-code-
used-to-authenticate/)[![cisco-
duo](https://static.datadoghq.com/static/images/logos/cisco-duo_avatar.svg)
Cisco Duo user marked authentication request as fraudulent  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-authentication-
request-marked-as-fraudulent/)[![cisco-
duo](https://static.datadoghq.com/static/images/logos/cisco-duo_avatar.svg)
Multiple Cisco Duo push notifications denied  
](https://docs.datadoghq.com/security/default_rules/cisco-duo-multiple-push-
notifications-denied/)

![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg)

Cisco Secure Email Threat Defense ____

>

[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense high number
of threat emails received by an internal user  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-high-number-of-threat-emails-
received-by-an-internal-user/)[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense high number
of threat emails received from a particular domain  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-high-number-of-threat-emails-
received-from-a-particular-domain/)[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense high number
of threat emails sent by an internal user  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-high-number-of-threat-emails-
sent-by-an-internal-user/)[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense unusual
spike found for emails having `Domain brand impersonation` detection technique  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-unusual-spike-found-for-
emails-with-domain-brand-impersonation/)[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense unusual
spike found for emails having `Rare sender domain` detection technique  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-unusual-spike-found-for-
emails-with-rare-sender-domain/)[![cisco-secure-email-threat-
defense](https://static.datadoghq.com/static/images/logos/cisco-secure-email-
threat-defense_avatar.svg) BETA Cisco Secure Email Threat Defense unusual
spike found for the high severity verdict techniques  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-email-threat-
defense-cisco-secure-email-threat-defense-alert-unusual-spike-found-for-
verdicts-with-high-severity/)

![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg)

Cisco Secure Endpoint ____

>

[![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg) BETA Cisco Secure Endpoint Alert  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-endpoint-
cisco-secure-endpoint-alert/)[![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg) BETA Cisco Secure Endpoint high number of malicious files
from single host  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-endpoint-
cisco-secure-endpoint-alert-high-number-of-malicious-files-from-single-
host/)[![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg) BETA Cisco Secure Endpoint malicious activity detected in
system scan  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-endpoint-
cisco-secure-endpoint-alert-malicious-activity-detected-in-system-
scan/)[![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg) BETA Cisco Secure Endpoint malicious file detected on
multiple hosts  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-endpoint-
cisco-secure-endpoint-alert-malicious-file-detected-on-multiple-
hosts/)[![cisco-secure-
endpoint](https://static.datadoghq.com/static/images/logos/cisco-secure-
endpoint_avatar.svg) BETA Cisco Secure Endpoint rise in number of user login
requests detected  
](https://docs.datadoghq.com/security/default_rules/cisco-secure-endpoint-
cisco-secure-endpoint-alert-rise-in-number-of-user-login-request-detected/)

![cisco-umbrella-dns](https://static.datadoghq.com/static/images/logos/cisco-
umbrella-dns_avatar.svg)

Cisco Umbrella DNS ____

>

[![cisco-umbrella-dns](https://static.datadoghq.com/static/images/logos/cisco-
umbrella-dns_avatar.svg) Cisco Umbrella - access to personal network detected  
](https://docs.datadoghq.com/security/default_rules/cisco-umbrella-dns-access-
to-personal-network-detected/)[![cisco-umbrella-
dns](https://static.datadoghq.com/static/images/logos/cisco-umbrella-
dns_avatar.svg) Cisco Umbrella - allowed request to unsafe URL category  
](https://docs.datadoghq.com/security/default_rules/cisco-umbrella-dns-
allowed-request-to-unsafe-url-category/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Cloud Workload Security ____

>

[![cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) AppArmor profile modified  
](https://docs.datadoghq.com/security/default_rules/apparmor_modified_tty/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Auditd configuration
modified  
](https://docs.datadoghq.com/security/default_rules/auditd_modification/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud credentials accessed
by network utility  
](https://docs.datadoghq.com/security/default_rules/csp_imds_request/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Compiler executed in
container  
](https://docs.datadoghq.com/security/default_rules/compiler_in_container/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Compiler wrote suspicious
file  
](https://docs.datadoghq.com/security/default_rules/compile_after_delivery/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Container accessed using
kubectl in another container  
](https://docs.datadoghq.com/security/default_rules/kubectl_access/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Container breakout attempt
using Docker socket  
](https://docs.datadoghq.com/security/default_rules/curl_docker_socket/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Container breakout using
runc file descriptors  
](https://docs.datadoghq.com/security/default_rules/runc_leaky_fd/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Container management utility
in container  
](https://docs.datadoghq.com/security/default_rules/suspicious_container_client/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Crypto miner environment
variables observed  
](https://docs.datadoghq.com/security/default_rules/cryptominer_envs/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Crypto miner process
observed  
](https://docs.datadoghq.com/security/default_rules/cryptominer_args/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cryptocurrency miner
attempted to boost CPU performance  
](https://docs.datadoghq.com/security/default_rules/msr_allow_writes/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Database process spawned
shell  
](https://docs.datadoghq.com/security/default_rules/database_shell_execution/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) DNS lookup for
cryptocurrency mining pool  
](https://docs.datadoghq.com/security/default_rules/potential_cryptominer/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) DNS lookup for IP lookup
service  
](https://docs.datadoghq.com/security/default_rules/ip_check_domain/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) DNS lookup for paste service  
](https://docs.datadoghq.com/security/default_rules/paste_sites/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Dynamic linker hijacking
attempt  
](https://docs.datadoghq.com/security/default_rules/suspected_dynamic_linker_hijacking/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Evidence hidden by deleting
system log file  
](https://docs.datadoghq.com/security/default_rules/delete_system_log/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Executable bit added to
newly created file  
](https://docs.datadoghq.com/security/default_rules/executable_bit_added/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Exfiltration attempt via
network utility  
](https://docs.datadoghq.com/security/default_rules/net_util_exfiltration/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) File created and executed
inside container  
](https://docs.datadoghq.com/security/default_rules/new_binary_execution_in_container/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Hash of known malware
detected  
](https://docs.datadoghq.com/security/default_rules/malware_detected/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Interactive shell spawned in
container  
](https://docs.datadoghq.com/security/default_rules/interactive_shell_in_container/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Kubernetes DNS enumeration  
](https://docs.datadoghq.com/security/default_rules/kubernetes_dns_enumeration/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Kubernetes service account
token created in container  
](https://docs.datadoghq.com/security/default_rules/kubectl_token_creation/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Local account password
modified  
](https://docs.datadoghq.com/security/default_rules/passwd_execution/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Looney Tunables
(CVE-2023-4911) exploited for privilege escalation  
](https://docs.datadoghq.com/security/default_rules/looney_tunables_exploit/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Memfd object created  
](https://docs.datadoghq.com/security/default_rules/memfd_create/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network scanning utility
executed  
](https://docs.datadoghq.com/security/default_rules/common_net_intrusion_util/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network utility executed  
](https://docs.datadoghq.com/security/default_rules/net_util/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network utility executed in
container  
](https://docs.datadoghq.com/security/default_rules/net_util_in_container/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network utility executed
with suspicious URI  
](https://docs.datadoghq.com/security/default_rules/net_unusual_request/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Offensive Kubernetes tool
executed  
](https://docs.datadoghq.com/security/default_rules/offensive_k8s_tools/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Package installed in
container  
](https://docs.datadoghq.com/security/default_rules/package_management_in_container/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Post compromise shell
detected  
](https://docs.datadoghq.com/security/default_rules/post_compromise_shell/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Potential rootkit compiled
and then loaded  
](https://docs.datadoghq.com/security/default_rules/compile_and_load/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Process hidden using mount  
](https://docs.datadoghq.com/security/default_rules/mount_proc_hide/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Pwnkit privilege escalation
attempt  
](https://docs.datadoghq.com/security/default_rules/pwnkit_privilege_escalation/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Python executed with
suspicious arguments  
](https://docs.datadoghq.com/security/default_rules/python_cli_code/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Recently written or modified
suid file has been executed  
](https://docs.datadoghq.com/security/default_rules/suspicious_suid_execution/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Redis modified cron job
directory to execute commands  
](https://docs.datadoghq.com/security/default_rules/redis_cron_job_injection/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Redis sandbox escape
(CVE-2022-0543)  
](https://docs.datadoghq.com/security/default_rules/redis_sandbox_escape/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Redis server wrote
suspicious module file  
](https://docs.datadoghq.com/security/default_rules/redis_module_saved/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Resource provisioned using
kubectl in container  
](https://docs.datadoghq.com/security/default_rules/kubectl_provisioning/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Runc binary modified  
](https://docs.datadoghq.com/security/default_rules/runc_modification/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Sensitive namespace modified
using kubectl  
](https://docs.datadoghq.com/security/default_rules/kubectl_apply/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Shell process created by
Java application  
](https://docs.datadoghq.com/security/default_rules/java_shell_execution/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unfamiliar kernel module
loaded  
](https://docs.datadoghq.com/security/default_rules/new_kernel_module/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unfamiliar kernel module
loaded from memory  
](https://docs.datadoghq.com/security/default_rules/kernel_module_load_memory/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unfamiliar process accessed
AWS EKS service account token  
](https://docs.datadoghq.com/security/default_rules/aws_eks_service_account_token_accessed_unusual/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Unfamiliar process created
by web application  
](https://docs.datadoghq.com/security/default_rules/potential_web_shell_new_term/)[![cloud
workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User created interactively  
](https://docs.datadoghq.com/security/default_rules/user_created_tty/)

![cloudflare](https://static.datadoghq.com/static/images/logos/cloudflare_avatar.svg)

Cloudflare ____

>

[![cloudflare](https://static.datadoghq.com/static/images/logos/cloudflare_avatar.svg)
Cloudflare CASB Finding  
](https://docs.datadoghq.com/security/default_rules/cloudflare-casb-
finding-3pa/)[![cloudflare](https://static.datadoghq.com/static/images/logos/cloudflare_avatar.svg)
Cloudflare L7 DDOS detected  
](https://docs.datadoghq.com/security/default_rules/cloudflare-l7ddos-
detected/)[![cloudflare](https://static.datadoghq.com/static/images/logos/cloudflare_avatar.svg)
Impossible travel scenario observed in Cloudflare logs  
](https://docs.datadoghq.com/security/default_rules/cloudflare-impossible-
travel/)

![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg)

Cloudfront ____

>

[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) Cloudfront distribution should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distribution-should-be-
encrypted/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distribution should be integrated with WAF  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distribution-should-be-integrated-with-
waf/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distribution should have a security policy
requiring a secure version of TLS  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distribution-should-have-a-security-policy-requiring-
a-secure-version-of-
tls/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distribution should have logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distribution-should-have-logging-
enabled/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should be configured for
origin failover  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-be-configured-for-origin-
failover/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should be configured with a
default root object  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-be-configured-with-a-default-
root-
object/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should encrypt traffic to
custom origins  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-encrypt-traffic-to-custom-
origins/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should use custom SSL/TLS
certificates  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-use-custom-ssl-tls-
certificates/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should use origin access
control  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-use-origin-access-
control/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions should use SNI to serve HTTPS
requests  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-should-use-sni-to-serve-https-
requests/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions that utilize HTTP POST Methods
should have field-level encryption enabled  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-that-utilize-http-post-methods-should-
have-field-level-encryption-
enabled/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront distributions using origin access identity
should be migrated to origin access control  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-distributions-using-origin-access-identity-should-be-
migrated-to-origin-access-
control/)[![cloudfront](https://static.datadoghq.com/static/images/logos/amazon-
cloudfront_avatar.svg) CloudFront viewer should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-cloudfront-
distribution-cloudfront-viewer-should-be-encrypted/)

![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg)

Cloudtrail ____

>

[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-web-
services_avatar.svg) A user received an anomalous number of AccessDenied
errors  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-anomaly-
detection-access-
denied/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Additional AWS regions enabled  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-account-
enable-
regions/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Amazon Bedrock activity InvokeModel multiple regions  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-bedrock-
mulltiple-
regions/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Amazon Bedrock console activity  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-bedrock-
console_api_long_term_access_key/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Amazon Bedrock discovery attempt by long term access
key  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-bedrock-
model-
enumeration/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Amazon EC2 AMI exfiltration attempt by IAM user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ec2-ami-
exfil/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
Amazon S3 bucket policy modified  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-policy-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ses_avatar.svg) Amazon SES enumeration attempt by previously unseen user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ses-
enumerated/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ses_avatar.svg) Amazon SES modification attempt  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ses-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
sns_avatar.svg) Amazon SNS enumeration attempt by previously unseen user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-sns-
enumeration-new-
value/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Amazon SNS enumeration in multiple regions using a
long-term access key  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-sns-discovery-
multiple-
regions/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) An AWS account attempted to leave the AWS Organization  
](https://docs.datadoghq.com/security/default_rules/aws-organizations-leave-
organization/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
An AWS S3 bucket lifecycle expiration policy was set to disabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-lifecycle-
expiration-policy-
disabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
An AWS S3 bucket lifecycle policy expiration is set to < 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-s3-lifecycle-
expiration-
below-90-days/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
An AWS S3 bucket mfaDelete is disabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-lifecycle-
versioning-mfa-delete-
disabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
An EC2 instance attempted to enumerate S3 bucket  
](https://docs.datadoghq.com/security/default_rules/aws-s3-buckets-
enumerated/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Anomalous amount of access denied events for AWS EC2 Instance  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
ec2-anomalous-access-
denied/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Anomalous amount of Autoscaling Group events  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ec2-host-
enrich-autoscaling-
group/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Anomalous API Gateway API key reads by user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-user-
enumerated-api-keys-
anomaly/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Anomalous number of assumed roles from user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-user-
attempted-to-assumerole-
anomaly/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
Anomalous number of S3 buckets accessed  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-anomalous-
get-object-unique-
bucket-60minbucket/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Anomalous number of secrets retrieved from AWS Secrets
Manager  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-secrets-
manager-secrets-revealed-
anomaly/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
Anomalous S3 bucket activity from user ARN  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-s3-anomalous-
bucket-activity-by-
arn/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Attempt to create Xlarge EC2 instances in multiple AWS regions  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ec2-xlarge-
instance-in-multiple-
regions/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS access key creation by previously unseen identity  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-new-access-
key-created-by-new-
user/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS AMI Made Public  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-ami-made-
public/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS CloudTrail configuration modified  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-
configuration-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS CloudTrail trail should have global service events
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-aws-
cloudtrail-trail-should-have-global-service-events-
enabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudwatch_avatar.svg) AWS CloudWatch log group deleted  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-cloudwatch-
log-group-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudwatch_avatar.svg) AWS CloudWatch rule disabled or deleted  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-cloudwatch-
rule-disabled-or-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
config_avatar.svg) AWS Config modified  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-config-
disabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS console login without MFA  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-console-
login-no-
mfa/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS ConsoleLogin with MFA triggered Impossible Travel
scenario  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-console-
logins-impossible-travel-
mfa/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS ConsoleLogin without MFA triggered Impossible
Travel scenario  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-console-
logins-impossible-travel-no-
mfa/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS consoler detected  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-track-aws-
consoler/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
detective_avatar.svg) AWS Detective Graph deleted  
](https://docs.datadoghq.com/security/default_rules/aws-detective-graph-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS Disable Cloudtrail with event selectors  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-cloudtrail-
disable-through-event-
selectors/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EBS default encryption disabled  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-ebs-default-
encryption-
disabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EBS Snapshot Made Public  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ebs-
snapshot-made-
public/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EBS Snapshot possible exfiltration  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ebs-
snapshot-possible-
exfiltration/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EC2 new event for application  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-ec2-host-
enrich-new-application-
event/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EC2 new event for EKS Node Group  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ec2-host-
enrich-new-eks-nodegroup-
event/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS EC2 subnet deleted  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-subnet-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) AWS ECS cluster deleted  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-cluster-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS ECS CreateCluster API calls in multiple regions  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ecs-
createcluster-multiple-
regions/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
event-bridge_avatar.svg) AWS EventBridge rule disabled or deleted  
](https://docs.datadoghq.com/security/default_rules/aws-eventbridge-rule-
disabled-or-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
guardduty_avatar.svg) AWS GuardDuty detector deleted  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-guardduty-
detector-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
guardduty_avatar.svg) AWS GuardDuty publishing destination deleted  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-guardduty-
publishing-destination-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
guardduty_avatar.svg) AWS GuardDuty threat intel set deleted  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-guardduty-
threat-intel-set-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM activity by S3 browser utility  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-
activity-s3-browser/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM activity from EC2 instance  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-iam-activity-
from-
ec2-instance/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AdministratorAccess policy was applied to a group  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
privilegedpolicy-to-
group/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AdministratorAccess policy was applied to a role  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
privilegedpolicy-to-
role/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AdministratorAccess policy was applied to a user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
privilegedpolicy-to-
user/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AmazonSESFullAccess policy was applied to a group  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
sesfullaccess-to-
group/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AmazonSESFullAccess policy was applied to a role  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
sesfullaccess-to-
role/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM AmazonSESFullAccess policy was applied to a user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-apply-
sesfullaccess-to-
user/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM policy modified  
](https://docs.datadoghq.com/security/default_rules/aws-iam-policy-
changed/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM Roles Anywhere trust anchor created  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-roles-
anywhere-trust-anchor-
created/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS IAM User created with AdministratorAccess policy
attached  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-createuser-
then-attach-admin-
policy/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS Java_Ghost security group creation attempt  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-create-
security-group-java-
ghost/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
firehose_avatar.svg) AWS Kinesis Firehose stream destination modified  
](https://docs.datadoghq.com/security/default_rules/aws-kinesis-firehose-
destination-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
kms_avatar.svg) AWS KMS key deleted or scheduled for deletion  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-kms-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS Lambda function modified by IAM user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-lambda-
function-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS Lambda function resource-based policy modified by IAM user  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-lambda-
function-resource-policy-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS Network Access Control List created or modified  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-nacl-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS Network Gateway created or modified  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-network-gateway-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) AWS principal added to multiple EKS clusters  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-eks-
principal-granted-access-to-multiple-
clusters/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) AWS principal assigned administrative privileges in an EKS
cluster  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-eks-
principal-assigned-admin-permissions-to-
cluster/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) AWS principal granted access to a EKS cluster then removed  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-eks-
principal-creates-then-deletes-
accessentry/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) AWS RDS Cluster deleted  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS root account activity  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-root-
account-
activity/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
route-53_avatar.svg) AWS Route 53 DNS query logging disabled  
](https://docs.datadoghq.com/security/default_rules/aws-route53-query-logging-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
route-53_avatar.svg) AWS Route 53 VPC disassociated from query logging
configuration  
](https://docs.datadoghq.com/security/default_rules/aws-route53-disassociated-
query-
logging/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS Route Table created or modified  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-route-table-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS S3 Bucket ACL made public  
](https://docs.datadoghq.com/security/default_rules/aws-bucket-acl-made-
public/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
AWS S3 Public Access Block removed  
](https://docs.datadoghq.com/security/default_rules/aws-s3-public-access-
block-
removed/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) AWS security group created, modified or deleted  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-security-group-
modified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS Security Hub disabled  
](https://docs.datadoghq.com/security/default_rules/aws-security-hub-
disabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS SES add verified identity followed by the deletion
of the identity  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ses-
verifyemailidentity-then-
deleteidentity/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS SES discovery attempt by long term access key  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ses-quota-
discovery-long-term-access-
key/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) AWS SES email sending enabled in current AWS region  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ses-
updateaccountsendingenabled-
true/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) AWS VPC created or modified  
](https://docs.datadoghq.com/security/default_rules/aws-vpc-created-modified-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) AWS VPC Flow Log deleted  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-vpc-flow-
log-
deleted/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) AWS WAF traffic blocked by specific rule  
](https://docs.datadoghq.com/security/default_rules/aws-waf-anomaly-blocked-
traffic-specific-
rule/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) AWS WAF traffic blocked by specific rule on multiple IPs  
](https://docs.datadoghq.com/security/default_rules/aws-waf-anomaly-blocked-
traffic-specific-rule-multiple-
ips/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) AWS WAF web access control list deleted  
](https://docs.datadoghq.com/security/default_rules/aws-waf-webacl-
delete/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) AWS WAF web access control list modified  
](https://docs.datadoghq.com/security/default_rules/aws-waf-webacl-
modify/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) CloudTrail log file validation should be enabled  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
cloudtrail-log-file-validation-should-be-
enabled/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) CloudTrail logs S3 bucket should not be public
accessible  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
cloudtrail-logs-s3-bucket-should-not-be-public-
accessible/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) CloudTrail logs should be encrypted at rest using KMS
CMKs  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
cloudtrail-logs-should-be-encrypted-at-rest-using-kms-
cmks/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Cloudtrail SecretsManager secret retrieved from AWS
CloudShell environment  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
secretsmanager-getsecretvalue-
cloudshell/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) CloudTrail trails should be integrated with CloudWatch
Logs  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
cloudtrail-trails-should-be-integrated-with-cloudwatch-
logs/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Compromised AWS EC2 Instance  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-sts-creds-
impossible-travel-no-
vpns/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Compromised AWS IAM User Access Key  
](https://docs.datadoghq.com/security/default_rules/aws-iam-access-key-
impossible-travel-with-baseline-user-
locations/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 instance created using risky AMI search pattern  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-
ec2-insecure-ami-id-retrieval-
whoami/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Encrypted administrator password retrieved for Windows EC2
instance  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-getpasswordata-
error/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Invitation sent to account to join AWS organization  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
organization-invite-
account/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) New Amazon EC2 Instance type  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-new-instance-type-
detected/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) New AWS account seen assuming a role into AWS account  
](https://docs.datadoghq.com/security/default_rules/aws-iam-new-aws-account-
assumerole/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) New Private Repository Container Image detected in AWS ECR  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-new-private-
image/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) New Public Repository Container Image detected in AWS ECR  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-new-public-
image/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) New user seen executing a command in an ECS task  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-user-executed-
command-on-ecs-
container/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Object-level logging should be enabled for S3 bucket
read events  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
object-level-logging-should-be-enabled-for-s3-bucket-read-
events/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Object-level logging should be enabled for S3 bucket
write events  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-trail-
object-level-logging-should-be-enabled-for-s3-bucket-write-
events/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Password recovery request completed  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-password-
recovery-suspicious-
ip/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Possible AWS EC2 privilege escalation via the modification of
user data  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-ec2-modify-
user-data-priv-
escalation/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Possible privilege escalation via AWS login profile
manipulation  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-iam-login-
profile-
manipulated/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Possible RDS Snapshot exfiltration  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-rds-
snapshot-
exfiltration/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Potential administrative port open to the world via AWS
security group  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
ec2-security-group-administrative-port-open-to-
world/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Potential brute force attack on AWS ConsoleLogin  
](https://docs.datadoghq.com/security/default_rules/aws-iam-brute-force-
consolelogin/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Potential database port open to the world via AWS security
group  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
ec2-security-group-database-port-open-to-
world/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) S3 bucket access logging should be enabled on the
CloudTrail S3 bucket  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-bucket-
access-logging-should-be-enabled-on-the-
cloudtrail-s3-bucket/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Security group open to the world  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-open-
to-world/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Temporary AWS security credentials generated for user  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-federation-
token-
generation/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) The AWS managed policy AWSCompromisedKeyQuarantineV2
has been attached  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
compromised-key-quarantine-policy-
attached/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) There should be at least one multi-region CloudTrail
trail per AWS account  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-there-
should-be-at-least-one-multi-region-cloudtrail-trail-per-aws-
account/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Tor client IP address identified within AWS environment  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-tor-traffic-
identified/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) TruffleHog user agent observed in AWS  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-trufflehog-
user-
agent/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Unfamiliar IAM user retrieved a decrypted AWS Systems
Manager parameter  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-systems-
manager-decrypted-parameters-retrieved-new-
value/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Unfamiliar IAM user retrieved secret from AWS Secrets
Manager  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-secrets-
manager-secrets-revealed-new-
value/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Unfamiliar IAM user retrieved SSM parameter  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-systems-
manager-parameters-retrieved-new-
term/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Unusual AWS enumeration event from EC2 instance  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-
ec2-enumeration-new-
term/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) Unusual AWS identity requesting limit increase  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-unusual-
identity-increase-
quota/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) User enumerated AWS Secrets Manager - Anomaly  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-user-
enumerated-secrets-anomaly-
detection/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/amazon-
cloudtrail_avatar.svg) User enumerated AWS Systems Manager parameters -
Anomaly  
](https://docs.datadoghq.com/security/default_rules/cloudtrail-aws-user-
enumerated-systems-manager-parameter-values-
anomaly/)[![cloudtrail](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) User travel was impossible in AWS CloudTrail IAM log  
](https://docs.datadoghq.com/security/default_rules/aws-cloudtrail-user-
impossible-travel-with-baseline-user-locations/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

CNM Based Threat Detection ____

>

[![cnm-based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Connection to cryptomining
pool  
](https://docs.datadoghq.com/security/default_rules/netflow_mining_domain/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Connection to red team
domain  
](https://docs.datadoghq.com/security/default_rules/netflow_pentesting_domain/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Docker daemon publicly
accessible  
](https://docs.datadoghq.com/security/default_rules/open_docker_daemon/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Egress over IRC port  
](https://docs.datadoghq.com/security/default_rules/netflow_irc_egress/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Egress SSH scanning  
](https://docs.datadoghq.com/security/default_rules/netflow_external_ssh_recon/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Kubernetes API publicly
accessible  
](https://docs.datadoghq.com/security/default_rules/open_k8s_api/)[![cnm-based
threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Redis service publicly
accessible  
](https://docs.datadoghq.com/security/default_rules/open_redis/)[![cnm-based
threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Remote Desktop service
publicly accessible  
](https://docs.datadoghq.com/security/default_rules/open_rdp/)[![cnm-based
threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Service exposed using ngrok  
](https://docs.datadoghq.com/security/default_rules/netflow_ngrok/)[![cnm-
based threat detection](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) SSH service publicly
accessible  
](https://docs.datadoghq.com/security/default_rules/open_ssh/)

![codebuild](https://static.datadoghq.com/static/images/logos/amazon-
codebuild_avatar.svg)

Codebuild ____

>

[![codebuild](https://static.datadoghq.com/static/images/logos/amazon-
codebuild_avatar.svg) CodeBuild logs stored in S3 should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-codebuild-project-
codebuild-logs-stored-in-s3-should-be-
encrypted/)[![codebuild](https://static.datadoghq.com/static/images/logos/amazon-
codebuild_avatar.svg) CodeBuild project environment variables should not
contain plain text credentials  
](https://docs.datadoghq.com/security/default_rules/aws-codebuild-project-
codebuild-project-environment-variables-should-not-contain-plain-text-
credentials/)[![codebuild](https://static.datadoghq.com/static/images/logos/amazon-
codebuild_avatar.svg) CodeBuild projects should have logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-codebuild-project-
codebuild-projects-should-have-logging-
enabled/)[![codebuild](https://static.datadoghq.com/static/images/logos/amazon-
codebuild_avatar.svg) CodeBuild source credentials should be stored and
transmitted securely  
](https://docs.datadoghq.com/security/default_rules/aws-codebuild-source-
credentials-codebuild-source-credentials-should-be-stored-and-transmitted-
securely/)

![cognito](https://static.datadoghq.com/static/images/logos/amazon-
cognito_avatar.svg)

Cognito ____

>

[![cognito](https://static.datadoghq.com/static/images/logos/amazon-
cognito_avatar.svg) Cognito identity pool should not have the classic
authentication flow enabled  
](https://docs.datadoghq.com/security/default_rules/aws_identity_pool_classic_flow/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Confluence Audit Records ____

>

[![confluence-audit-records](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Atlassian Confluence admin
key usage  
](https://docs.datadoghq.com/security/default_rules/atlassian-confluence-
admin-key-usage/)[![confluence-audit-records](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Atlassian Confluence global setting changed  
](https://docs.datadoghq.com/security/default_rules/atlassian-confluence-
global-setting-changed/)[![confluence-audit-records](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Atlassian Confluence public link turned on  
](https://docs.datadoghq.com/security/default_rules/atlassian-confluence-
public-link-turned-on/)[![confluence-audit-records](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Atlassian Confluence site export  
](https://docs.datadoghq.com/security/default_rules/atlassian-confluence-site-
export/)[![confluence-audit-records](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Atlassian Confluence space export  
](https://docs.datadoghq.com/security/default_rules/atlassian-confluence-
space-export/)

![crowdstrike](https://static.datadoghq.com/static/images/logos/crowdstrike_avatar.svg)

Crowdstrike ____

>

[![crowdstrike](https://static.datadoghq.com/static/images/logos/crowdstrike_avatar.svg)
Crowdstrike Alerts  
](https://docs.datadoghq.com/security/default_rules/crowdstrike-third-party/)

![dms](https://static.datadoghq.com/static/images/logos/amazon-dms_avatar.svg)

DMS ____

>

[![dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg) DMS endpoints should require SSL/TLS  
](https://docs.datadoghq.com/security/default_rules/aws-dms-endpoint-dms-
endpoints-should-require-ssl-
tls/)[![dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg) DMS replication instances should have automatic minor version
upgrades enabled  
](https://docs.datadoghq.com/security/default_rules/aws-dms-replication-
instance-dms-replication-instances-should-have-automatic-minor-version-
upgrades-
enabled/)[![dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg) DMS replication tasks for the source database should have
logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-dms-replication-task-
dms-replication-tasks-for-the-source-database-should-have-logging-
enabled/)[![dms](https://static.datadoghq.com/static/images/logos/amazon-
dms_avatar.svg) DMS replication tasks for the target database should have
logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-dms-replication-task-
dms-replication-tasks-for-the-target-database-should-have-logging-enabled/)

![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)

Docker ____

>

[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
/usr/bin/containerd should be audited if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.11/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
/var/lib/docker should be audited  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.4/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Container images should include HEALTHCHECK instructions  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-4.6/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Container runtime should include the --pids-limit flag for cgroup limit
parameter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.28/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers on the default network bridge should restrict network traffic  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-2.1/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should have an enabled AppArmor profile  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.1/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should have memory usage limits configured on Docker hosts  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.10/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should not mount the Docker socket docker.sock inside them  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.31/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should not run in privileged mode  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.4/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should not share the host's user namespaces  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.30/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should run as a non-root user  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-4.1/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Containers should use the cgroup configured in Docker  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.24/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Docker daemon activities should be audited  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.3/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Docker-related files should be audited in /etc/docker  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.5/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Incoming system calls should be filtered using enabled Seccomp profiles  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.21/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Kernel capabilities in Linux should only be granted when necessary  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.3/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Private registry should use TLS encryption for a secure Docker environment  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-2.4/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Privileged port mapping for containers should be restricted to increase
security  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.7/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Processes in containers should have isolated Process ID (PID) namespaces  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.15/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
SELinux security options should be properly configured for effective
application security  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.2/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
Sensitive host system directories should not be mounted on containers  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.5/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/default/docker file ownership should be set to root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.19/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/default/docker file permissions should be set to 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.22/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/docker directory permissions should be set to 755 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.6/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/docker directory should be owned by root account  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.5/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/sysconfig/docker file permissions should be set to 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.21/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /etc/sysconfig/docker file should be owned by the root account and group  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.20/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The /usr/sbin/runc executable should be audited, if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.12/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The container should have a restart policy limited to 5 attempts  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.14/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The container should restrict acquiring additional privileges via suid or sgid
bits  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.25/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The container's health should be constantly monitored  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.26/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The container's root filesystem should be set to read-only  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.12/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The critical containers should be configured to remain responsive  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.11/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The daemon.json file should have permissions set to 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.18/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The daemon.json file should have user and group ownership set to root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.17/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The default Docker configuration file should be audited on RHEL  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.9/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The default Docker configuration file should be audited, if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.8/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker daemon configuration file should be audited if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.10/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker daemon log level should be set to 'info'  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-2.2/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker daemon should be allowed to configure the firewall rules  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-2.3/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker daemon should only be controlled by root and Docker group  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.2/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker instance should not use AUFS as its storage driver  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-2.5/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker local storage partition should be separate from other partitions  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.1/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker server certificate file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.11/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker server certificate file should have read-only or more restrictive
permissions  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.12/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker server certificate key file needs to have permissions of 400  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.14/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker server certificate key file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.13/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker socket file should be owned by root and Docker group  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.15/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The Docker socket file should have permissions of 660 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.16/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The docker.service file ownership and group should be set to root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.1/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The docker.service file permissions should be set to 644  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.2/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The docker.service file should have auditing configured if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.6/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The docker.socket file should be audited, if applicable  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-1.2.7/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The docker.socket file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.3/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The file permissions on docker.socket should be set to 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.4/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The host's network namespace should be hidden from containers  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.9/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The IPC namespace on the host should remain isolated from containers  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.16/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The registry certificate files should be individually and group owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.7/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The registry certificate files should have read-only or stricter permissions  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.8/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The TLS CA certificate file should be owned by root account  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.9/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The TLS CA certificate file should have read-only or more restrictive
permissions  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-3.10/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
The UTS namespace should not be shared with the host  
](https://docs.datadoghq.com/security/default_rules/cis-
docker-1.2.0-5.20/)[![docker](https://static.datadoghq.com/static/images/logos/docker_avatar.svg)
TLS authentication should be enabled for Docker daemon to restrict remote
access  
](https://docs.datadoghq.com/security/default_rules/cis-docker-1.2.0-2.6/)

![documentdb](https://static.datadoghq.com/static/images/logos/amazon-
documentdb_avatar.svg)

Documentdb ____

>

[![documentdb](https://static.datadoghq.com/static/images/logos/amazon-
documentdb_avatar.svg) DocumentDB clusters should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-docdb-cluster-
documentdb-clusters-should-be-encrypted-at-
rest/)[![documentdb](https://static.datadoghq.com/static/images/logos/amazon-
documentdb_avatar.svg) DocumentDB clusters should have an appropriate backup
retention period set  
](https://docs.datadoghq.com/security/default_rules/aws-docdb-cluster-
documentdb-clusters-should-have-an-appropriate-backup-retention-period-
set/)[![documentdb](https://static.datadoghq.com/static/images/logos/amazon-
documentdb_avatar.svg) DocumentDB clusters should have deletion protection
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-docdb-cluster-
documentdb-clusters-should-have-deletion-protection-
enabled/)[![documentdb](https://static.datadoghq.com/static/images/logos/amazon-
documentdb_avatar.svg) DocumentDB clusters should publish audit logs to
CloudWatch Logs  
](https://docs.datadoghq.com/security/default_rules/aws-docdb-cluster-
documentdb-clusters-should-publish-audit-logs-to-cloudwatch-logs/)

![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg)

Dynamodb ____

>

[![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg) DynamoDB Accelerator (DAX) clusters should be encrypted
at rest  
](https://docs.datadoghq.com/security/default_rules/aws-dax-cluster-dynamodb-
accelerator-dax-clusters-should-be-encrypted-at-
rest/)[![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg) DynamoDB table replicates to a public S3 bucket  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-dynamodb-
exports-
public-s3/)[![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg) DynamoDB tables should have deletion protection enabled  
](https://docs.datadoghq.com/security/default_rules/aws-dynamodb-dynamodb-
tables-should-have-deletion-protection-
enabled/)[![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg) DynamoDB tables should have point-in-time recovery
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-dynamodb-dynamodb-
tables-should-have-point-in-time-recovery-
enabled/)[![dynamodb](https://static.datadoghq.com/static/images/logos/amazon-
dynamodb_avatar.svg) DynamoDB tables should scale automatically with demand  
](https://docs.datadoghq.com/security/default_rules/aws-dynamodb-dynamodb-
tables-should-scale-automatically-with-demand/)

![ebs](https://static.datadoghq.com/static/images/logos/amazon-ebs_avatar.svg)

EBS ____

>

[![ebs](https://static.datadoghq.com/static/images/logos/amazon-
ebs_avatar.svg) EBS snapshot should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-ebs-snapshot-ebs-
snapshot-should-be-
encrypted/)[![ebs](https://static.datadoghq.com/static/images/logos/amazon-
ebs_avatar.svg) EBS volume snapshot should not be publicly shared  
](https://docs.datadoghq.com/security/default_rules/aws-ebs-snapshot-ebs-
volume-snapshot-should-not-be-publicly-
shared/)[![ebs](https://static.datadoghq.com/static/images/logos/amazon-
ebs_avatar.svg) EBS volumes should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-ebs-volume-ebs-
volumes-should-be-encrypted/)

![ec2](https://static.datadoghq.com/static/images/logos/amazon-ec2_avatar.svg)

EC2 ____

>

[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Amazon Machine Image (AMI) should only be available to trusted
accounts  
](https://docs.datadoghq.com/security/default_rules/aws-ami-amazon-machine-
image-ami-should-only-be-available-to-trusted-
accounts/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Default VPC security group should restrict all traffic  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
default-vpc-security-group-should-restrict-all-
traffic/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 Client VPN endpoints should have client connection logging
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-client-vpn-
endpoint-ec2-client-vpn-endpoints-should-have-client-connection-logging-
enabled/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 instance should not have a highly-privileged IAM role
attached to it  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-instance-should-not-have-a-highly-privileged-iam-role-attached-to-
it/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 instances and autoscaling groups should enforce IMDSv2  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-instances-and-autoscaling-groups-should-enforce-
imdsv2/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 instances should not be publicly accessible  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-instances-should-not-be-publicly-
accessible/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 instances should not use multiple ENIs  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-instances-should-not-use-multiple-
enis/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 paravirtual instance types should not be used  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-paravirtual-instance-types-should-not-be-
used/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 should be configured to use AWS VPC endpoints created for
the Amazon EC2 service  
](https://docs.datadoghq.com/security/default_rules/aws-vpc-endpoint-
ec2-should-be-configured-to-use-aws-vpc-endpoints-created-for-the-amazon-
ec2-service/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 subnets should not automatically assign public IP
addresses  
](https://docs.datadoghq.com/security/default_rules/aws-subnet-ec2-subnets-
should-not-automatically-assign-public-ip-
addresses/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) EC2 Transit Gateways should not automatically accept VPC
attachment requests  
](https://docs.datadoghq.com/security/default_rules/aws-transit-gateway-
ec2-transit-gateways-should-not-automatically-accept-vpc-attachment-
requests/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound CIFS access should be restricted to trusted networks  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-cifs-access-should-be-restricted-to-trusted-
networks/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound DNS access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-dns-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound FTP access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-ftp-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound HTTP access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-http-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound HTTPS access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-https-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound ICMP access to the host should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-icmp-access-to-the-host-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound MongoDB access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-mongodb-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound MSSQL access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-mssql-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound MySQL access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-mysql-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound OpenSearch access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-opensearch-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound Oracle access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-oracle-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound PostgreSQL access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-postgresql-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound RPC access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-rpc-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound SMTP access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-smtp-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound TCP NetBIOS access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-tcp-netbios-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound Telnet access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-telnet-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Inbound UDP NetBIOS access should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
inbound-udp-netbios-access-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Instance roles should be used for AWS resource access from
instances  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-instance-
roles-should-be-used-for-aws-resource-access-from-
instances/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Outbound access on all ports should be restricted  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
outbound-access-on-all-ports-should-be-
restricted/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible AWS EC2 instance is vulnerable to CUPS
remote code execution attack chain  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-cups-
emerging-
vulnerability/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 contains critical vulnerabilities
found in CISA KEV with greater than 15 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-vuln-15days-cisa-
kev/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 contains critical vulnerabilities
which have exploits available with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-vuln-30days-exploit-
available/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 contains critical vulnerabilities with
greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-
vuln-30days/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 contains high vulnerabilities with
greater than 60 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
high-
vuln-60days/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 host is running IMDSv1 and has an SSRF
vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
ssrf-vuln-
imdsv1/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 instance contains critical
vulnerability CVE-2024-3094 (RCE in liblzma and xz versions 5.6.0 and 5.6.1)  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
xz-vuln/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly Accessible EC2 instance has a critical vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-
vulns/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly Accessible EC2 instance has a critical vulnerability
has access to Redis ElasticCache with no AUTH  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-vulns-access-to-elasticcache-with-no-
auth/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 instance has access to an S3 bucket
with sensitive data  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-
ec2-public-s3-sensitive/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly Accessible EC2 instance has privileged role and a
critical vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-
ec2-privileged-public-critical-
vulns/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 instance should not have open
administrative ports  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-publicly-
accessible-ec2-instance-should-not-have-open-administrative-
ports/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 instance uses IMDSv1  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-
ec2-imdsv1/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 instances should not have highly-
privileged IAM roles  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-publicly-
accessible-ec2-instances-should-not-have-highly-privileged-iam-
roles/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible EC2 with privileged IAM role contains
critical vulnerabilities with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-ec2-public-
critical-vuln-30days-
privileged/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Publicly accessible Lambda function has a critical
vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-lambda-
public-critical-
vuln/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Security groups should not allow unrestricted access to ports
with high risk  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-security-
groups-should-not-allow-unrestricted-access-to-ports-with-high-
risk/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Security groups should restrict traffic to trusted IPv4
addresses  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
security-groups-should-restrict-traffic-to-trusted-
ipv4-addresses/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Security groups should restrict traffic to trusted IPv6
addresses  
](https://docs.datadoghq.com/security/default_rules/aws-security-group-
security-groups-should-restrict-traffic-to-trusted-
ipv6-addresses/)[![ec2](https://static.datadoghq.com/static/images/logos/amazon-
ec2_avatar.svg) Unused Network Access Control Lists should be removed  
](https://docs.datadoghq.com/security/default_rules/aws-network-acl-unused-
network-access-control-lists-should-be-removed/)

![ecr](https://static.datadoghq.com/static/images/logos/amazon-ecr_avatar.svg)

ECR ____

>

[![ecr](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) BETA Amazon ECR should be scanning all images for
vulnerabilities  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-repository-amazon-
ecr-should-be-scanning-all-images-for-
vulnerabilities/)[![ecr](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) ECR private repositories should have tag immutability enabled  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-repository-ecr-
private-repositories-should-have-tag-immutability-
enabled/)[![ecr](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) ECR private repositories should not grant public image
downloads  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-repository-ecr-
private-repositories-should-not-grant-public-image-
downloads/)[![ecr](https://static.datadoghq.com/static/images/logos/amazon-
ecr_avatar.svg) ECR private repositories should not grant public image uploads  
](https://docs.datadoghq.com/security/default_rules/aws-ecr-repository-ecr-
private-repositories-should-not-grant-public-image-uploads/)

![ecs](https://static.datadoghq.com/static/images/logos/amazon-ecs_avatar.svg)

ECS ____

>

[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS clusters should have Container Insights enabled  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-cluster-ecs-
clusters-should-have-container-insights-
enabled/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS containers should be limited to read-only access to root
filesystems  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
ecs-containers-should-be-limited-to-read-only-access-to-root-
filesystems/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS containers should run as non-privileged  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
ecs-containers-should-run-as-non-
privileged/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS Fargate services should automatically use the latest
Fargate platform version  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-service-ecs-
fargate-services-should-automatically-use-the-latest-fargate-platform-
version/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS services should not have public IP addresses assigned  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-service-ecs-
services-should-not-have-public-ip-addresses-
assigned/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS task definitions should have a logging configuration  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
ecs-task-definitions-should-have-a-logging-
configuration/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS task definitions should have secure networking modes and
user definitions  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
ecs-task-definitions-should-have-secure-networking-modes-and-user-
definitions/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) ECS task definitions should not share the host's process
namespace  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
ecs-task-definitions-should-not-share-the-hosts-process-
namespace/)[![ecs](https://static.datadoghq.com/static/images/logos/amazon-
ecs_avatar.svg) Secrets should not be passed as container environment
variables  
](https://docs.datadoghq.com/security/default_rules/aws-ecs-task-definition-
secrets-should-not-be-passed-as-container-environment-variables/)

![efs](https://static.datadoghq.com/static/images/logos/amazon-efs_avatar.svg)

EFS ____

>

[![efs](https://static.datadoghq.com/static/images/logos/amazon-
efs_avatar.svg) EFS file systems should have encryption at rest enabled  
](https://docs.datadoghq.com/security/default_rules/aws-efs-file-system-efs-
file-systems-should-have-encryption-at-rest-enabled/)

![eks](https://static.datadoghq.com/static/images/logos/amazon-eks_avatar.svg)

EKS ____

>

[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's kubelet configuration file ownership should
be assigned to root  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-configuration-file-ownership-should-be-assigned-to-
root/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet configuration file should disable
anonymous requests  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-configuration-file-should-disable-anonymous-
requests/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's kubelet configuration file should have
permissions set to 644 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-configuration-file-should-have-permissions-set-to-644-or-
more-
restrictive/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet should be allowed to manage iptables  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-should-be-allowed-to-manage-
iptables/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet should have the eventRecordQPS entry
set  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-should-have-the-eventrecordqps-entry-
set/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet should only allow explicitly
authorized requests  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-should-only-allow-explicitly-authorized-
requests/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet should rotate client certificates
automatically  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-should-rotate-client-certificates-
automatically/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet should rotate server certificates
automatically  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelet-should-rotate-server-certificates-
automatically/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS Cluster's Kubelet's read-only port should be disabled  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
eks-clusters-kubelets-read-only-port-should-be-
disabled/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) An EKS's Kubelet should use TLS authentication  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-an-
ekss-kubelet-should-use-tls-
authentication/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) EKS Cluster should have private endpoint enabled  
](https://docs.datadoghq.com/security/default_rules/aws-eks-cluster-eks-
cluster-should-have-private-endpoint-
enabled/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) EKS Cluster should have public access limited  
](https://docs.datadoghq.com/security/default_rules/aws-eks-cluster-eks-
cluster-should-have-public-access-
limited/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) EKS cluster should use a network policy between nodes  
](https://docs.datadoghq.com/security/default_rules/aws-eks-cluster-eks-
cluster-should-use-a-network-policy-between-
nodes/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) EKS clusters should have audit logs enabled  
](https://docs.datadoghq.com/security/default_rules/aws-eks-cluster-eks-
clusters-should-have-audit-logs-
enabled/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) EKS clusters should run on a supported version of Kubernetes  
](https://docs.datadoghq.com/security/default_rules/aws-eks-cluster-eks-
clusters-should-run-on-a-supported-version-of-
kubernetes/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) Kubelet configuration file ownership should be assigned to
root  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-
kubelet-configuration-file-ownership-should-be-assigned-to-
root/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) The kubeconfig file should have permissions set to 644 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-the-
kubeconfig-file-should-have-permissions-set-to-644-or-more-
restrictive/)[![eks](https://static.datadoghq.com/static/images/logos/amazon-
eks_avatar.svg) Timeouts for streaming connections in an EKS worker node
should be enabled  
](https://docs.datadoghq.com/security/default_rules/aws-eks-worker-node-
timeouts-for-streaming-connections-in-an-eks-worker-node-should-be-enabled/)

![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg)

Elasticache ____

>

[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache clusters should be provisioned in a VPC  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-clusters-should-be-provisioned-in-a-
vpc/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache clusters should not use the default subnet
group  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-clusters-should-not-use-the-default-subnet-
group/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache clusters should use a non-default port for
communication  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-clusters-should-use-a-non-default-port-for-
communication/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache clusters should use the latest engine
version available  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-clusters-should-use-the-latest-engine-version-
available/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis clusters before version 6.0 should
use Redis AUTH  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-redis-clusters-before-version-6.0-should-use-redis-
auth/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis clusters should be configured for
automatic backup  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-redis-clusters-should-be-configured-for-automatic-
backup/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis clusters should have auto minor
version upgrades enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
elasticache-redis-clusters-should-have-auto-minor-version-upgrades-
enabled/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis replication groups should be
encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
replication-group-elasticache-redis-replication-groups-should-be-encrypted-at-
rest/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis replication groups should be
encrypted in transit  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
replication-group-elasticache-redis-replication-groups-should-be-encrypted-in-
transit/)[![elasticache](https://static.datadoghq.com/static/images/logos/amazon-
elasticache_avatar.svg) ElastiCache Redis replication groups should have
automatic failover enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elasticache-
replication-group-elasticache-redis-replication-groups-should-have-automatic-
failover-enabled/)

![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)

Elasticsearch ____

>

[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch clusters should use the latest engine version  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-clusters-should-use-the-latest-engine-
version/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domain connections should be encrypted using a secure TLS
version  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domain-connections-should-be-encrypted-using-a-secure-tls-
version/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domain should enable encryption  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domain-should-enable-
encryption/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domain should only be accessible from an AWS VPC  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domain-should-only-be-accessible-from-an-aws-
vpc/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should be encrypted with KMS Customer Master Keys  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-be-encrypted-with-kms-customer-master-
keys/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should encrypt data transmitted between nodes  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-encrypt-data-transmitted-between-
nodes/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should have at least three dedicated master nodes  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-have-at-least-three-dedicated-master-
nodes/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should have audit logs enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-have-audit-logs-
enabled/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should have error logging to CloudWatch Logs enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-have-error-logging-to-cloudwatch-logs-
enabled/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
Elasticsearch domains should use at least three data nodes  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
elasticsearch-domains-should-use-at-least-three-data-
nodes/)[![elasticsearch](https://static.datadoghq.com/static/images/logos/elasticsearch_avatar.svg)
The Elasticsearch domain should block unsigned requests over the public
internet  
](https://docs.datadoghq.com/security/default_rules/aws-elasticsearch-domain-
the-elasticsearch-domain-should-block-unsigned-requests-over-the-public-
internet/)

![elb](https://static.datadoghq.com/static/images/logos/amazon-elb_avatar.svg)

ELB ____

>

[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) AWS ELB HTTP requests from security scanner  
](https://docs.datadoghq.com/security/default_rules/elb-scanner-
detected/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancer listener should use a secure
configuration  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancer-listener-should-use-a-secure-
configuration/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancers should be configured to use Connection
Draining  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancers-should-be-configured-to-use-connection-
draining/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancers should be configured to use defensive
or strictest desync mitigation mode  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancers-should-be-configured-to-use-defensive-or-strictest-
desync-mitigation-
mode/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancers should span multiple Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancers-should-span-multiple-availability-
zones/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancers should utilize cross-zone load
balancing  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancers-should-utilize-cross-zone-load-
balancing/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Classic Load Balancers with SSL/HTTPS listeners should use a
certificate issued by AWS Certificate Manager  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
classic-load-balancers-with-ssl-https-listeners-should-use-a-certificate-
issued-by-aws-certificate-
manager/)[![elb](https://static.datadoghq.com/static/images/logos/amazon-
elb_avatar.svg) Logging and Audits should be configured for Load Balancers  
](https://docs.datadoghq.com/security/default_rules/aws-elb-load-balancer-
logging-and-audits-should-be-configured-for-load-balancers/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Elbv2 ____

>

[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Application Load Balancers
should be configured to use defensive or strictest desync mitigation mode  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
application-load-balancers-should-be-configured-to-use-defensive-or-strictest-
desync-mitigation-mode/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Application Load Balancers
should have Access logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
application-load-balancers-should-have-access-logging-
enabled/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Application Load Balancers
should have deletion protection enabled  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
application-load-balancers-should-have-deletion-protection-
enabled/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Application Load Balancers
should use HTTPS  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
application-load-balancers-should-use-https/)[![elbv2](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Load Balancers should span multiple Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
load-balancers-should-span-multiple-availability-
zones/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Load Balancers should use
the latest security policy  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
load-balancers-should-use-the-latest-security-
policy/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Private application load
balancers should drop HTTP headers  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
private-application-load-balancers-should-drop-http-
headers/)[![elbv2](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Public-facing application
load balancers should drop HTTP headers  
](https://docs.datadoghq.com/security/default_rules/aws-elbv2-load-balancer-
public-facing-application-load-balancers-should-drop-http-headers/)

![fastly](https://static.datadoghq.com/static/images/logos/fastly_avatar.svg)

Fastly ____

>

[![fastly](https://static.datadoghq.com/static/images/logos/fastly_avatar.svg)
Fastly HTTP Requests from Security Scanner  
](https://docs.datadoghq.com/security/default_rules/fastly-scanner-detected/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

File Integrity Monitoring ____

>

[![file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Credentials file modified  
](https://docs.datadoghq.com/security/default_rules/credential_modified/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Critical system binary
modified  
](https://docs.datadoghq.com/security/default_rules/critical_binaries/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cron job modified  
](https://docs.datadoghq.com/security/default_rules/cron_at_job_injection/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Kernel module directory
modified  
](https://docs.datadoghq.com/security/default_rules/kernel_module/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Name Service Switch
configuration modified  
](https://docs.datadoghq.com/security/default_rules/nsswitch_conf_mod/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) RC scripts modified  
](https://docs.datadoghq.com/security/default_rules/rc_modified/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Shell command history
modified  
](https://docs.datadoghq.com/security/default_rules/shell_history_tamper/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) SSH authorized keys modified  
](https://docs.datadoghq.com/security/default_rules/ssh_authorized_keys/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) SSL certificate tampering  
](https://docs.datadoghq.com/security/default_rules/ssl_certificate_tampering/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Sudoers policy file modified  
](https://docs.datadoghq.com/security/default_rules/sudoers_policy_modified/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) System authentication files
modified  
](https://docs.datadoghq.com/security/default_rules/pam_modification/)[![file
integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Systemd service modified  
](https://docs.datadoghq.com/security/default_rules/systemd_modification/)

![fsx](https://static.datadoghq.com/static/images/logos/amazon-fsx_avatar.svg)

FSX ____

>

[![fsx](https://static.datadoghq.com/static/images/logos/amazon-
fsx_avatar.svg) FSx Lustre file systems should copy tags to backups  
](https://docs.datadoghq.com/security/default_rules/aws-fsx-file-system-fsx-
lustre-file-systems-should-copy-tags-to-
backups/)[![fsx](https://static.datadoghq.com/static/images/logos/amazon-
fsx_avatar.svg) FSx OpenZFS file systems should copy tags to backups and
volumes  
](https://docs.datadoghq.com/security/default_rules/aws-fsx-file-system-fsx-
openzfs-file-systems-should-copy-tags-to-backups-and-volumes/)

![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg)

GCP ____

>

[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
iam_avatar.svg) Access denied for Google Cloud Service Account  
](https://docs.datadoghq.com/security/default_rules/google-cloud-anomalous-
access-denied-
sa/)[![gcp](https://static.datadoghq.com/static/images/logos/google-compute-
engine_avatar.svg) Anomalous number of Google Cloud Compute GPU virtual
machines created  
](https://docs.datadoghq.com/security/default_rules/google-cloud-gce-gpu-vms-
cryptomining-anomaly-
detection/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-storage_avatar.svg) Anomalous number of Google Cloud Storage Buckets
Accessed  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
bucket-anomalous-
access/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
storage_avatar.svg) Anomalous number of Google Cloud Storage Objects Accessed  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
object-anomalous-
download/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Anomalous number of Google Compute Engine instances
created in multiple zones by user  
](https://docs.datadoghq.com/security/default_rules/google-compute-instances-
created-in-multiple-zones-
anomaly/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Attempt to add SSH key to Google Compute Engine
project metadata by a previously unseen user  
](https://docs.datadoghq.com/security/default_rules/google-cloud-compute-
engine-project-ssh-lateral-movement-new-
user/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) GCP App Engine Default Service Account has overly
permissive access to resources in the project  
](https://docs.datadoghq.com/security/default_rules/app-engine-service-
account-has-admin-
priv/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) GCP Compute Engine Default Service Account has overly
permissive access to resources in the project  
](https://docs.datadoghq.com/security/default_rules/compute-engine-service-
account-has-admin-
priv/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) GCP Group Account has overly permissive access to
resources in the project  
](https://docs.datadoghq.com/security/default_rules/group-account-has-admin-
priv/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) GCP User Account has overly permissive access to
resources in the project  
](https://docs.datadoghq.com/security/default_rules/user-account-has-admin-
priv/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) GCP User managed Service Account has overly permissive
access to resources in the project  
](https://docs.datadoghq.com/security/default_rules/service-account-has-admin-
priv/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
iam_avatar.svg) Google App Engine service account used outside of Google Cloud  
](https://docs.datadoghq.com/security/default_rules/google-app-engine-sa-
outside-google-
cloud/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
bigquery_avatar.svg) Google Cloud BigQuery - query results saved to cloud
storage  
](https://docs.datadoghq.com/security/default_rules/google-cloud-bq-exfil-via-
cloud-
storage/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-bigquery_avatar.svg) Google Cloud BigQuery - query results saved to new
table  
](https://docs.datadoghq.com/security/default_rules/google-cloud-bq-exfil-via-
tables/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
bigquery_avatar.svg) Google Cloud BigQuery results saved to cloud storage by a
previously unseen user  
](https://docs.datadoghq.com/security/default_rules/google-cloud-bq-exfil-via-
cloud-storage-new-
user/)[![gcp](https://static.datadoghq.com/static/images/logos/google-compute-
engine_avatar.svg) Google Cloud Compute Engine GPU virtual machine instance
created  
](https://docs.datadoghq.com/security/default_rules/google-cloud-gce-gpu-vms-
cryptomining/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud exposed service account key  
](https://docs.datadoghq.com/security/default_rules/google-cloud-exposed-
service-account-
key/)[![gcp](https://static.datadoghq.com/static/images/logos/google-compute-
engine_avatar.svg) Google Cloud GCE instance startup script added or modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-gce-
persistence-startup-
script/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Google Cloud IAM policy modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-iam-policy-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud IAM role created  
](https://docs.datadoghq.com/security/default_rules/google-cloud-iam-role-
created/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud IAM Role updated  
](https://docs.datadoghq.com/security/default_rules/google-cloud-iam-role-
updated/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-storage_avatar.svg) Google Cloud Logging Bucket deleted  
](https://docs.datadoghq.com/security/default_rules/google-cloud-logging-
bucket-
delete/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Google Cloud logging sink modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-logging-sink-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud Project external principal added as project
owner  
](https://docs.datadoghq.com/security/default_rules/google-cloud-project-
external-principal-project-
owner/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Google Cloud Pub/Sub Subscriber modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-pubsub-
subscriber-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Cloud Pub/Sub topic deleted  
](https://docs.datadoghq.com/security/default_rules/google-cloud-pubsub-topic-
deleted/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud Service Account accessing anomalous number
of Google Cloud APIs  
](https://docs.datadoghq.com/security/default_rules/google-cloud-anomalous-
api-requests/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Cloud Service Account created  
](https://docs.datadoghq.com/security/default_rules/google-cloud-service-
account-
create/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
iam_avatar.svg) Google Cloud Service Account Impersonation activity using
access token generation  
](https://docs.datadoghq.com/security/default_rules/google-cloud-service-
account-impersonation-activity-access-
token/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Google Cloud Service Account Impersonation using GCPloit
Exploitation Framework  
](https://docs.datadoghq.com/security/default_rules/google-cloud-service-
account-impersonation-activity-
gcploit/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Cloud Service Account key created  
](https://docs.datadoghq.com/security/default_rules/google-cloud-service-
account-key-
created/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Cloud SQL database modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-sql-database-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloudsql_avatar.svg) Google Cloud SQL instance data exported to cloud storage  
](https://docs.datadoghq.com/security/default_rules/google-cloud-cloudsql-db-
exfil-to-cloud-
storage/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloudsql_avatar.svg) Google Cloud SQL instance data exported to cloud storage
by a previously unseen user  
](https://docs.datadoghq.com/security/default_rules/google-cloud-cloudsql-db-
exfil-to-cloud-storage-new-
user/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
storage_avatar.svg) Google Cloud Storage Bucket contents downloaded without
authentication  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
bucket-unauthenticated-
access/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
storage_avatar.svg) Google Cloud Storage Bucket enumerated  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
bucket-
enumerated/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-storage_avatar.svg) Google Cloud Storage Bucket modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
bucket-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-storage_avatar.svg) Google Cloud Storage Bucket permissions modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-storage-
bucket-permissions-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud unauthorized service account activity  
](https://docs.datadoghq.com/security/default_rules/google-cloud-unauthorized-
sa-activity/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-iam_avatar.svg) Google Cloud unauthorized user activity  
](https://docs.datadoghq.com/security/default_rules/google-cloud-unauthorized-
user-
activity/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Compute Engine firewall egress rule opened
to the world  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
firewall-rule-allow-all-
egress/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Google Compute Engine firewall rule modified  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
firewall-rule-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Google Compute Engine image created  
](https://docs.datadoghq.com/security/default_rules/google-compute-image-
created/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Google Compute Engine instance metadata SSH key
added or modified  
](https://docs.datadoghq.com/security/default_rules/google-cloud-gce-instance-
ssh-key-
persistence/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Google Compute Engine instances created in multiple
zones by user  
](https://docs.datadoghq.com/security/default_rules/google-compute-instances-
created-in-multiple-zones-
threshold/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Compute Engine network created  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
network-
created/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Google Compute Engine network route created or
modified  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
route-
modified/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Google Compute Engine project metadata SSH key
added or modified  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
project-ssh-lateral-
movement/)[![gcp](https://static.datadoghq.com/static/images/logos/google-
compute-engine_avatar.svg) Google Compute Engine service account used outside
of Google Cloud  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-sa-
outside-google-
cloud/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Potential Google Cloud cryptomining attack from Tor IP  
](https://docs.datadoghq.com/security/default_rules/google-compute-engine-
potential-cryptomining-tor-ip-
attack/)[![gcp](https://static.datadoghq.com/static/images/logos/google-cloud-
platform_avatar.svg) Tor client IP address identified within Google Cloud
environment  
](https://docs.datadoghq.com/security/default_rules/google-cloud-tor-traffic-
identified/)

![gcp.k8s.cluster](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg)

Gcp.k8s.cluster ____

>

[![gcp.k8s.cluster](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) Anonymous request authorized  
](https://docs.datadoghq.com/security/default_rules/kubernetes-anonymous-
request-authorized/)

![github-telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg)

Github Telemetry ____

>

[![github-telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub a branch protection requirement was overridden by
a repository administrator  
](https://docs.datadoghq.com/security/default_rules/github-branch-protection-
override/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub Advanced Security modification  
](https://docs.datadoghq.com/security/default_rules/github-advanced-security-
modification/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub anomalous bot git activity  
](https://docs.datadoghq.com/security/default_rules/github-anomalous-bot-git-
activity/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub anomalous bot org activity  
](https://docs.datadoghq.com/security/default_rules/github-anomalous-bot-org-
activity/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub anomalous number of repositories cloned by user  
](https://docs.datadoghq.com/security/default_rules/github-anomaly-detection-
repository-cloning/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub audit log streaming endpoint was deleted  
](https://docs.datadoghq.com/security/default_rules/github-audit-log-stream-
destroy/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub audit log streaming endpoint was modified  
](https://docs.datadoghq.com/security/default_rules/github-enterprise-audit-
log-stream-modified/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub branch protection disabled on branch  
](https://docs.datadoghq.com/security/default_rules/github-branch-protection-
disabled/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub Dependabot configuration changed  
](https://docs.datadoghq.com/security/default_rules/github-dependabot-
configuration-changed/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub enterprise or organization recovery codes
activity  
](https://docs.datadoghq.com/security/default_rules/github-enterprise-or-
organization-recovery-codes-activity/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub enterprise owner added  
](https://docs.datadoghq.com/security/default_rules/github-enterprise-owner-
added/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub IP allow list  
](https://docs.datadoghq.com/security/default_rules/github-ip-
allowlist/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub MFA requirement disabled  
](https://docs.datadoghq.com/security/default_rules/github-mfa-requirement-
disabled/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub OAuth access token compromise  
](https://docs.datadoghq.com/security/default_rules/github-oauth-access-token-
compromise/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub OAuth application access restrictions disabled  
](https://docs.datadoghq.com/security/default_rules/github-oauth-app-
restrictions-disabled/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub organization was removed from enterprise  
](https://docs.datadoghq.com/security/default_rules/github-enterprise-
organization-removed/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub organization was transferred between enterprise
accounts  
](https://docs.datadoghq.com/security/default_rules/github-org-
transfer/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub payment method removed  
](https://docs.datadoghq.com/security/default_rules/github-payment-method-
removed/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub personal access token (PAT) auto approve
policy modified  
](https://docs.datadoghq.com/security/default_rules/github-personal-access-
token-auto-approve-policy-modified/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub Personal Access Token created by suspicious IP  
](https://docs.datadoghq.com/security/default_rules/github-personal-access-
token-created/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub personal access token granted and used to
clone large amount of repositories  
](https://docs.datadoghq.com/security/default_rules/github-pat-usage-for-
repository-clones/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub private repository changed to public
visibility  
](https://docs.datadoghq.com/security/default_rules/github-repository-
visibility-changed-to-public/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub repository transfer  
](https://docs.datadoghq.com/security/default_rules/github-repo-
transfer/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub SAML/OIDC has been disabled  
](https://docs.datadoghq.com/security/default_rules/github-oidc-saml-
disabled/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub secret scanning alert generated  
](https://docs.datadoghq.com/security/default_rules/github-secret-scanning-
alert/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub secret scanning disabled or bypassed  
](https://docs.datadoghq.com/security/default_rules/github-secret-scanning-
configuration-changed/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub SSH certificate authority deleted  
](https://docs.datadoghq.com/security/default_rules/github-ssh-certificate-
authority-deleted/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub SSH certificate requirement disabled  
](https://docs.datadoghq.com/security/default_rules/github-ssh-certificate-
requirement-disabled/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub SSH key added by suspicious IP  
](https://docs.datadoghq.com/security/default_rules/github-ssh-key-
added/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub unknown user cloned private repository  
](https://docs.datadoghq.com/security/default_rules/github-unknown-actor-
repository-clone/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) BETA GitHub user anomalously downloaded data as a ZIP
file  
](https://docs.datadoghq.com/security/default_rules/github-user-downloaded-
data/)[![github-
telemetry](https://static.datadoghq.com/static/images/logos/github-
telemetry_avatar.svg) GitHub user blocked from accessing organization
repositories  
](https://docs.datadoghq.com/security/default_rules/github-org-block-user/)

![gke](https://static.datadoghq.com/static/images/logos/google-kubernetes-
engine_avatar.svg)

GKE ____

>

[![gke](https://static.datadoghq.com/static/images/logos/google-kubernetes-
engine_avatar.svg) Google Cloud Kubernetes Engine cluster should not be
publicly accessible  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-google-cloud-kubernetes-engine-cluster-should-not-be-publicly-
accessible/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Bigquery Dataset ____

>

[![google_bigquery_dataset](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BigQuery data sets should
specify a default customer-managed encryption key  
](https://docs.datadoghq.com/security/default_rules/gcp-bigquery-bigquery-
data-sets-should-specify-a-default-customer-managed-encryption-
key/)[![google_bigquery_dataset](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BigQuery Dataset should not
be anonymously or publicly accessible  
](https://docs.datadoghq.com/security/default_rules/gcp-bigquery-bigquery-
datasets-should-not-be-anonymously-or-publicly-accessible/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Bigquery Table ____

>

[![google_bigquery_table](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BigQuery tables should be
encrypted with customer-managed encryption keys (CMEK)  
](https://docs.datadoghq.com/security/default_rules/gcp-bigquery-table-
bigquery-tables-should-be-encrypted-with-customer-managed-encryption-keys-
cmek/)

![google_cloud_asset_inventory](https://static.datadoghq.com/static/images/logos/google-
cloud-asset-inventory_avatar.svg)

Google Cloud Asset Inventory ____

>

[![google_cloud_asset_inventory](https://static.datadoghq.com/static/images/logos/google-
cloud-asset-inventory_avatar.svg) Cloud Asset Inventory should be enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-project-asset-
inventory-should-be-enabled/)

![google_cloud_sql_instance](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg)

Google Cloud SQL Instance ____

>

[![google_cloud_sql_instance](https://static.datadoghq.com/static/images/logos/google-
cloud-platform_avatar.svg) SQL database instances should only use private IP
addresses  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-database-instances-should-only-use-private-ip-addresses/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Compute Disk ____

>

[![google_compute_disk](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) VM disks for critical VMs
should be encrypted with customer-supplied encryption keys  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-disk-disks-
for-critical-vms-should-be-encrypted-with-customer-supplied-encryption-keys/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Compute Firewall ____

>

[![google_compute_firewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) RDP access should be
restricted from the internet  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-firewall-rdp-
access-should-be-restricted-from-the-
internet/)[![google_compute_firewall](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SSH access should be restricted from the internet  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-firewall-ssh-
access-should-be-restricted-from-the-internet/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Compute Instance ____

>

[![google_compute_instance](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Compute instances should be
launched with Shielded VM enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-be-launched-with-shielded-vm-
enabled/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Compute instances should have confidential computing enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-have-confidential-computing-
enabled/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Compute instances should only have internal IP addresses  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-only-have-internal-ip-
addresses/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Instances should be configured to use a non-default service account with
restricted API access  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-be-configured-to-use-a-non-default-service-account-with-
restricted-api-access/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Instances should have IP forwarding disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-have-ip-forwarding-
disabled/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Instances should use a non-default service account  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-use-a-non-default-service-
account/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Instances should use instance-specific SSH keys instead of project-wide keys  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
instances-should-use-instance-specific-ssh-keys-instead-of-project-wide-
keys/)[![google_compute_instance](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Projects should have OS
Login enabled for SSH authentication  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-
projects-should-have-os-login-enabled-for-ssh-
authentication/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google Compute instance has a critical severity
vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
critical-vulns/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google Compute instance has a privileged service account
and a critical severity vulnerability  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-
privileged-public-critical-vulns/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google Compute instance uses a privileged service account  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
priv/)[![google_compute_instance](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Publicly accessible Google
VM instance contains critical vulnerabilities found in CISA KEV with greater
than 15 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
critical-vuln-15days-cisa-kev/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google VM instance contains critical vulnerabilities which
have exploits available with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
critical-vuln-30days-exploit-
available/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google VM instance contains critical vulnerabilities with
greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
critical-vuln-30days/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google VM instance contains critical vulnerability
CVE-2024-3094 (RCE in liblzma and xz versions 5.6.0 and 5.6.1)  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
xz-vuln/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google VM instance contains high vulnerabilities with
greater than 60 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
high-vuln-60days/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Publicly accessible Google VM instance with a privileged service account
contains critical vulnerabilities with greater than 30 days exposure time  
](https://docs.datadoghq.com/security/default_rules/sec-issue-gcp-vm-public-
critical-vuln-30days-privileged/)[![google_compute_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Serial port connection for VM instances should be disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-instance-port-
connection-for-vm-instances-should-be-disabled/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Compute Network ____

>

[![google_compute_network](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Projects should not have
legacy networks configured for older projects  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-network-
projects-should-not-have-legacy-networks-configured-for-older-
projects/)[![google_compute_network](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Projects should only use non-default VPC networks  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-network-
projects-should-only-use-non-default-vpc-networks/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Compute Subnetwork ____

>

[![google_compute_subnetwork](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) VPC Flow Logs should be
enabled for all VPC subnets  
](https://docs.datadoghq.com/security/default_rules/gcp-compute-subnetwork-
flow-logs-should-be-enabled-for-all-vpc-subnets/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Dataproc Cluster ____

>

[![google_dataproc_cluster](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Dataproc cluster should be
encrypted using customer-managed encryption key  
](https://docs.datadoghq.com/security/default_rules/gcp-dataproc-cluster-
dataproc-cluster-should-be-encrypted-using-customer-managed-encryption-key/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google DNS Managed Zone ____

>

[![google_dns_managed_zone](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud DNS DNSSEC should use
a secure algorithm other than RSASHA1  
](https://docs.datadoghq.com/security/default_rules/gcp-dns-managed-zone-dns-
dnssec-should-use-a-secure-algorithm-other-than-
rsasha1/)[![google_dns_managed_zone](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Cloud DNS DNSSEC should use a zone-signing key with a secure algorithm other
than RSASHA1  
](https://docs.datadoghq.com/security/default_rules/gcp-dns-managed-zone-
cloud-dns-dnssec-should-use-a-zone-signing-key-with-a-secure-algorithm-other-
than-rsasha1/)[![google_dns_managed_zone](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Cloud DNS should have DNSSEC enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-dns-managed-zone-
cloud-dns-should-have-dnssec-enabled/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google DNS Policy ____

>

[![google_dns_policy](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud DNS logging should be
enabled for VPC networks  
](https://docs.datadoghq.com/security/default_rules/gcp-dns-policy-dns-
logging-should-be-enabled-for-vpc-networks/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Iam Policy ____

>

[![google_iam_policy](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud Audit Logging should
be configured to track admin activity and data access  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-cloud-
audit-logging-should-be-configured-to-track-admin-activity-and-data-
access/)[![google_iam_policy](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud Storage Bucket should
not be anonymously or publicly accessible  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-cloud-
storage-bucket-should-not-be-anonymously-or-publicly-
accessible/)[![google_iam_policy](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) KMS roles assigned to users
should utilize 'Separation of Duties'  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-kms-roles-
assigned-to-users-should-utilize-separation-of-duties/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Kms Crypto Key ____

>

[![google_kms_crypto_key](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) KMS encryption keys should
be rotated every 90 days or less  
](https://docs.datadoghq.com/security/default_rules/gcp-kms-crypto-key-
encryption-keys-should-be-rotated-every-90-days-or-less/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Kubernetes Engine Cluster ____

>

[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
'Regular' or 'Stable' release channels should be used for GKE clusters  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-regular-or-stable-release-channels-should-be-used-for-gke-
clusters/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Alpha clusters should not be used for production workloads  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-alpha-clusters-should-not-be-used-for-production-
workloads/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Authentication using Client Certificates should be disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-authentication-using-client-certificates-should-be-
disabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Auto-Repair for nodes should be enabled in GKE clusters  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-auto-repair-for-nodes-should-be-enabled-in-gke-
clusters/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Auto-Upgrade for nodes should be enabled in GKE clusters  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-auto-upgrade-for-nodes-should-be-enabled-in-gke-
clusters/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Cluster should be created with Private Nodes  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-cluster-should-be-created-with-private-
nodes/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Cluster should have Private Endpoint enabled and public access disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-cluster-should-have-private-endpoint-enabled-and-public-access-
disabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Cluster VPC flow logs and intranode visibility should be enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-cluster-vpc-flow-logs-and-intranode-visibility-should-be-
enabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Clusters should use binary authorization  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-clusters-should-use-binary-
authorization/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Control plane authorized networks should be enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-control-plane-authorized-networks-should-be-
enabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
GKE clusters should have monitoring and logging enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-gke-clusters-should-have-monitoring-and-logging-
enabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Legacy authorization (ABAC) should be disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-legacy-authorization-abac-should-be-
disabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
The GKE cluster should be encrypted using customer-managed keys in KMS  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-the-gke-cluster-should-be-encrypted-using-customer-managed-keys-in-
kms/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
The Web UI Dashboard should be disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-the-web-ui-dashboard-should-be-
disabled/)[![google_kubernetes_engine_cluster](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
VPC-native clusters should be used  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
cluster-vpc-native-clusters-should-be-used/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Kubernetes Engine Node Pool ____

>

[![google_kubernetes_engine_node_pool](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Container-Optimized OS (cos_containerd) should be used for GKE node images  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
node-pool-container-optimized-os-cos_containerd-should-be-used-for-gke-node-
images/)[![google_kubernetes_engine_node_pool](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Customer-Managed Encryption Keys (CMEK) should be used for boot disks  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
node-pool-customer-managed-encryption-keys-cmek-should-be-used-for-boot-
disks/)[![google_kubernetes_engine_node_pool](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure GKE node pools do not use default service accounts  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
node-pool-ensure-gke-node-pools-do-not-use-default-service-
accounts/)[![google_kubernetes_engine_node_pool](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
GKE nodes should use the metadata server  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
node-pool-gke-nodes-should-use-the-metadata-
server/)[![google_kubernetes_engine_node_pool](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
GKE Sandbox should be used for untrusted workloads  
](https://docs.datadoghq.com/security/default_rules/gcp-kubernetes-engine-
node-pool-gke-sandbox-should-be-used-for-untrusted-workloads/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Kubernetes Worker Node ____

>

[![google_kubernetes_worker_node](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A GKE Cluster's kubelet
configuration file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-configuration-file-ownership-should-be-assigned-to-
root/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet configuration file should disable anonymous requests  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-configuration-file-should-disable-anonymous-
requests/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's kubelet configuration file should have permissions set to 600 or
more restrictive  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-configuration-file-should-have-permissions-set-to-600-or-
more-restrictive/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet should be allowed to manage iptables  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-should-be-allowed-to-manage-
iptables/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet should have the eventRecordQPS entry set  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-should-have-the-eventrecordqps-entry-
set/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet should only allow explicitly authorized requests  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-should-only-allow-explicitly-authorized-
requests/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet should rotate client certificates automatically  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-should-rotate-client-certificates-
automatically/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet should rotate server certificates automatically  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelet-should-rotate-server-certificates-
automatically/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE Cluster's Kubelet's read-only port should be disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-gke-
clusters-kubelets-read-only-port-should-be-
disabled/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
GKE's Cluster's Kubelet should use TLS authentication  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-a-
gkes-clusters-kubelet-should-use-tls-
authentication/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
GKE Kubelet kubeconfig file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-gke-
kubelet-kubeconfig-file-ownership-should-be-assigned-to-
root/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
The GKE kubeconfig file should have permissions set to 644 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-the-
gke-kubeconfig-file-should-have-permissions-set-to-644-or-more-
restrictive/)[![google_kubernetes_worker_node](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Timeouts for streaming connections in a GKE worker node should be enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-gke-worker-node-
timeouts-for-streaming-connections-in-a-gke-worker-node-should-be-enabled/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Logging Log Bucket ____

>

[![google_logging_log_bucket](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Retention policies should be
configured using bucket lock on log buckets  
](https://docs.datadoghq.com/security/default_rules/gcp-logging-bucket-
retention-policies-should-be-configured-using-bucket-lock-on-log-buckets/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Logging Log Metric ____

>

[![google_logging_log_metric](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A log metric filter and
alert should exist for audit configuration changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-audit-configuration-
changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for cloud storage bucket IAM changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-cloud-storage-bucket-
iam-changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for custom role changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-custom-role-
changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for project ownership
assignments/changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-project-ownership-
assignments-changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for SQL instance configuration
changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-sql-instance-
configuration-changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for VPC network changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-vpc-network-
changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for VPC network firewall rule changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-vpc-firewall-rule-
changes/)[![google_logging_log_metric](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A
log metric filter and alert should exist for VPC network route changes  
](https://docs.datadoghq.com/security/default_rules/gcp-monitoring-alert-
policy-a-log-metric-filter-and-alert-should-exist-for-vpc-network-route-
changes/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Logging Log Sink ____

>

[![google_logging_log_sink](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Log entries should have log
sinks configured for exporting  
](https://docs.datadoghq.com/security/default_rules/gcp-logging-log-sink-log-
entries-should-have-log-sinks-configured-for-exporting/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Service Account ____

>

[![google_service_account](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud KMS cryptokeys should
restrict anonymous and/or public access  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-cloud-kms-
cryptokeys-should-restrict-anonymous-and-or-public-
access/)[![google_service_account](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Service accounts should keep
the 'Service Account Admin' and 'Service Account User' roles separate  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-service-
accounts-should-keep-the-service-account-admin-and-service-account-user-roles-
separate/)[![google_service_account](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Service accounts should only be bound to non-administrative roles  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-service-account-
service-accounts-should-only-be-bound-to-non-administrative-
roles/)[![google_service_account](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Service Accounts should only
use GCP managed keys  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-service-account-
service-accounts-should-only-use-gcp-managed-
keys/)[![google_service_account](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Service accounts should
rotate user-managed or external keys every 90 days or less  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-service-account-
key-service-accounts-should-rotate-user-managed-or-external-keys-
every-90-days-or-less/)[![google_service_account](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Users should be assigned the 'Service Account User' or 'Service Account Token
Creator' roles at the Service Account level  
](https://docs.datadoghq.com/security/default_rules/gcp-iam-policy-users-
should-be-assigned-the-service-account-user-or-service-account-token-creator-
roles-at-the-service-account-level/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google SQL Database Instance ____

>

[![google_sql_database_instance](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) MySQL instance should have
the 'skip_show_database' flag set to 'on'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
mysql-instance-should-have-the-skip_show_database-flag-set-to-
on/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
MySQL instances should have the 'local_infile' database flag set to 'off'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
mysql-instances-should-have-the-local_infile-database-flag-set-to-
off/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instance should have the 'log_disconnections' database flag enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instance-should-have-the-log_disconnections-database-flag-
enabled/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the 'log_connections' database flag set to
'on'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_connections-database-flag-set-to-
on/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the 'log_error_verbosity' flag set to
'DEFAULT' or stricter  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_error_verbosity-flag-set-to-default-
or-stricter/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the 'log_hostname' database flag set to 'on'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_hostname-database-flag-set-to-
on/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the 'log_min_messages' database flag set to
at least 'WARNING'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_min_messages-database-flag-set-to-at-
least-warning/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the 'log_statement' database flag set
appropriately  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_statement-database-flag-set-
appropriately/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the `log_min_duration_statement` flag set to
'-1' (disabled)  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_min_duration_statement-flag-set-to--
1-disabled/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
PostgreSQL instances should have the `log_min_error_statement` flag set to
'ERROR' or stricter  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
postgresql-instances-should-have-the-log_min_error_statement-flag-set-to-
error-or-stricter/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL database instances should enforce SSL for all incoming connections  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-database-instances-should-enforce-ssl-for-all-incoming-
connections/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL database instances should have automated backups enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-database-instances-should-have-automated-backups-
enabled/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Database instances should only allow ingress traffic from specific IP
addresses  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-database-instances-should-only-allow-ingress-traffic-from-specific-ip-
addresses/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the 'contained database authentication'
database flag set to 'off'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-contained-database-authentication-
database-flag-set-to-off/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the 'cross db ownership chaining' database
flag set to 'off'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-cross-db-ownership-chaining-database-
flag-set-to-off/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the 'external scripts enabled' database flag
set to 'off'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-external-scripts-enabled-database-flag-
set-to-off/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the 'remote access' database flag set to
'off'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-remote-access-database-flag-set-to-
off/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the 'user connections' database flag set to a
non-limiting value  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-user-connections-database-flag-set-to-a-
non-limiting-value/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the `3625 (trace flag)` database flag set to
'on'  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-3625-trace-flag-database-flag-set-to-
on/)[![google_sql_database_instance](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
SQL Server instances should have the `user options` database flag disabled  
](https://docs.datadoghq.com/security/default_rules/gcp-sql-database-instance-
sql-server-instances-should-have-the-user-options-database-flag-disabled/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Google Storage Bucket ____

>

[![google_storage_bucket](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Cloud storage buckets should
have uniform bucket-level access enabled  
](https://docs.datadoghq.com/security/default_rules/gcp-storage-bucket-cloud-
storage-buckets-should-have-uniform-bucket-level-access-enabled/)

![google.security.command.center](https://static.datadoghq.com/static/images/logos/google_avatar.svg)

Google.security.command.center ____

>

[![google.security.command.center](https://static.datadoghq.com/static/images/logos/google_avatar.svg)
Google Security Command Center  
](https://docs.datadoghq.com/security/default_rules/google-security-command-
center-3pa/)[![google.security.command.center](https://static.datadoghq.com/static/images/logos/google_avatar.svg)
Google Security Command Center finding muted  
](https://docs.datadoghq.com/security/default_rules/google-cloud-security-
center-mute-finding/)

![google.workspace.alert.center](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)

Google.workspace.alert.center ____

>

[![google.workspace.alert.center](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace Alert Center  
](https://docs.datadoghq.com/security/default_rules/3rd-party-detection-
method-google-workspace-alert-id/)

![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)

Gsuite ____

>

[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Domain added to Google Workspace allowlisted domains  
](https://docs.datadoghq.com/security/default_rules/google-workspace-domain-
added-to-trusted-
domain/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace accessed by Google  
](https://docs.datadoghq.com/security/default_rules/gsuite-access-to-
workspace-by-
google/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace admin role created  
](https://docs.datadoghq.com/security/default_rules/gsuite-admin-role-
created/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace administrator has disabled 2-step verification for
organizational unit  
](https://docs.datadoghq.com/security/default_rules/google-workspace-
administrator-has-
disabled-2sv/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace administrator initiated a data transfer request  
](https://docs.datadoghq.com/security/default_rules/google-workspace-admin-
data-transfer-
request/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace Tor client detected  
](https://docs.datadoghq.com/security/default_rules/google-workspace-tor-
client/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user assigned administrative role  
](https://docs.datadoghq.com/security/default_rules/google-workspace-user-
added-
admin/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user assigned super administrative role  
](https://docs.datadoghq.com/security/default_rules/gsuite-user-added-super-
admin/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user disabled 2-step verification  
](https://docs.datadoghq.com/security/default_rules/google-workspace-user-has-
disabled-2sv/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user edited account recovery information  
](https://docs.datadoghq.com/security/default_rules/google-workspace-user-
edits-recovery-
setting/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user forwarding email out of non Google Workspace domain  
](https://docs.datadoghq.com/security/default_rules/gsuite-forwarding-email-
non-workspace-
domain/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Google Workspace user has unenrolled from Advanced Protection  
](https://docs.datadoghq.com/security/default_rules/google-workspace-user-
unenrolled-from-advanced-
protection/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
Large amount of downloads on Google Drive  
](https://docs.datadoghq.com/security/default_rules/google-workspace-large-
amount-of-downloads-google-
drive/)[![gsuite](https://static.datadoghq.com/static/images/logos/gsuite_avatar.svg)
User attempted login with leaked password  
](https://docs.datadoghq.com/security/default_rules/gsuite-user-attempted-
login-with-leaked-password/)

![guardduty](https://static.datadoghq.com/static/images/logos/amazon-
guardduty_avatar.svg)

Guardduty ____

>

[![guardduty](https://static.datadoghq.com/static/images/logos/amazon-
guardduty_avatar.svg) AWS GuardDuty finding  
](https://docs.datadoghq.com/security/default_rules/aws-guardduty-third-
party/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Host Benchmarks ____

>

[![host-benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) A remote time server for
Chrony is configured  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-chronyd-specify-remote-server/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add grpquota Option to /home  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-home-grpquota/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /dev/shm  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-dev-shm-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /home  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-home-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-tmp-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /var  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /var/log  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to /var/log/audit  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-audit-nodev/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add nodev Option to /var/tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-tmp-nodev/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nodev Option to Removable Media Partitions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-nodev-removable-partitions/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add noexec Option to
/dev/shm  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-dev-shm-noexec/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add noexec Option to /tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-tmp-noexec/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add noexec Option to /var  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-noexec/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add noexec Option to /var/log  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-noexec/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add noexec Option to /var/log/audit  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-audit-noexec/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add noexec Option to
/var/tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-tmp-noexec/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add noexec Option to Removable Media Partitions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-noexec-removable-partitions/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add nosuid Option to
/dev/shm  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-dev-shm-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nosuid Option to /home  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-home-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nosuid Option to /tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-tmp-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nosuid Option to /var  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nosuid Option to /var/log  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add nosuid Option to /var/log/audit  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-log-audit-nosuid/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Add nosuid Option to
/var/tmp  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-var-tmp-nosuid/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Add usrquota Option to /home  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-mount-option-home-usrquota/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
All AppArmor Profiles are in enforce or complain mode  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-all-apparmor-profiles-in-enforce-complain-mode/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) All GIDs referenced in
/etc/passwd must be defined in /etc/group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-gid-passwd-group-same/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
All Interactive User Home Directories Must Be Group-Owned By The Primary Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupownership-home-directories/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) All Interactive User Home
Directories Must Be Owned By The Primary User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-home-directories/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) All Interactive User Home
Directories Must Have mode 0750 Or Less Permissive  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-home-directories/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) All Interactive Users Home
Directories Must Exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-user-interactive-home-directory-exists/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Audit Configuration Files
Must Be Owned By Group root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupownership-audit-configuration/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Audit Configuration Files
Must Be Owned By Root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-audit-configuration/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Build and Test AIDE Database  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-aide-build-database/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure Accepting Router Advertisements on All IPv6 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-all-accept-ra/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure AIDE to Verify the
Audit Tools  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-aide-check-audit-tools/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure auditd to use audispd's syslog plugin  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-auditd-audispd-syslog-plugin-activated/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure BIND to use System
Crypto Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-configure-bind-crypto-policy/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure Firewalld to
Restrict Loopback Traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-firewalld-loopback-traffic-restricted/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure Firewalld to Trust
Loopback Traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-firewalld-loopback-traffic-trusted/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure GNOME3 DConf User
Profile  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-enable-dconf-user-profile/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure Kernel Parameter for Accepting Secure Redirects By Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-secure-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure Libreswan to use
System Crypto Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-configure-libreswan-crypto-policy/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure ntpd To Run As ntp
User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ntpd-run-as-ntp-user/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure OpenSSL library to use System Crypto Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-configure-openssl-crypto-policy/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure Periodic Execution
of AIDE  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-aide-periodic-cron-checking/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure SELinux Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-selinux-policytype/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure server restrictions for ntpd  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ntpd-configure-restrictions/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure SSH to use System Crypto Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-configure-ssh-crypto-policy/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure System Cryptography Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-configure-crypto-policy/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Configure the Use of the pam_faillock.so Module in the /etc/pam.d/password-
auth File.  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-account-password-pam-faillock-password-auth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Configure the Use of the
pam_faillock.so Module in the /etc/pam.d/system-auth File.  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-account-password-pam-faillock-system-auth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Deactivate Wireless Network
Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-wireless-disable-interfaces/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Direct root Logins Not Allowed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-direct-root-logins/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Accepting ICMP Redirects for All IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-accept-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Accepting ICMP
Redirects for All IPv6 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-all-accept-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Accepting Router
Advertisements on all IPv6 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-default-accept-ra/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Apache Qpid (qpidd)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-qpidd-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Apport Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-apport-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable At Service (atd)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-atd-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Automatic Bug Reporting Tool (abrtd)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-abrtd-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Avahi Server Software  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-avahi-daemon-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Bluetooth Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-bluetooth-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable core dump backtraces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-coredump-disable-backtraces/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Core Dumps for All Users  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-disable-users-coredumps/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Core Dumps for SUID programs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-fs-suid-dumpable/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable GNOME3 Automount Opening  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-disable-automount-open/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable GNOME3 Automount
running  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-disable-autorun/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable GNOME3 Automounting  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-disable-automount/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable graphical user
interface  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-xwindows-remove-packages/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Host-Based Authentication  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-disable-host-auth/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Kernel Parameter for Accepting ICMP Redirects by Default on IPv4
Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-accept-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting ICMP Redirects by Default on IPv6 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-default-accept-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting Secure ICMP Redirects on all IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-secure-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting Source-Routed Packets on all IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-accept-source-route/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting Source-Routed Packets on all IPv6 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-all-accept-source-route/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting Source-Routed Packets on IPv4 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-accept-source-route/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Accepting Source-Routed Packets on IPv6 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-default-accept-source-route/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
IP Forwarding on IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-ip-forward/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Kernel Parameter for IPv6 Forwarding  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv6-conf-all-forwarding/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Sending ICMP Redirects on all IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-send-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Parameter for
Sending ICMP Redirects on all IPv4 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-send-redirects/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Kernel Support for
USB via Bootloader Configuration  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-grub2-nousb-argument/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Modprobe Loading of USB Storage Driver  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-usb-storage-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of cramfs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-cramfs-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of freevxfs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-freevxfs-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of hfs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-hfs-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Mounting of hfsplus  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-hfsplus-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of jffs2  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-jffs2-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of squashfs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-squashfs-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable Mounting of udf  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-kernel-module-udf-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Network File System (nfs)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-nfs-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Network Router Discovery Daemon (rdisc)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-rdisc-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable ntpdate Service (ntpdate)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-ntpdate-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Odd Job Daemon (oddjobd)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-oddjobd-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable Postfix Network Listening  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-postfix-network-listening-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable rpcbind Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-rpcbind-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable snmpd Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-snmpd-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable SSH Access via Empty Passwords  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-disable-empty-passwords/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable SSH Root Login  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-disable-root-login/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable SSH Support for .rhosts Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-disable-rhosts/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable storing core dump  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-coredump-disable-storage/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable systemd-journal-remote Socket  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-socket-systemd-journal-remote-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable the Automounter  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-autofs-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable the CUPS Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-cups-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Disable the GNOME3 Login User List  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-disable-user-list/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Disable XDMCP in GDM  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-gnome-gdm-disable-xdmcp/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Do
Not Allow SSH Environment Options  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-do-not-permit-user-env/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable authselect  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-enable-authselect/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable cron Daemon  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-crond-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable cron Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-cron-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable GNOME3 Login Warning Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-banner-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable GNOME3 Screensaver Lock After Idle Period  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-screensaver-lock-enabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Ignore Bogus ICMP Error Responses on IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-icmp-ignore-bogus-error-responses/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Ignore ICMP Broadcast Echo Requests on IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-icmp-echo-ignore-broadcasts/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Log Martian Packets on all IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-log-martians/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Use Reverse Path Filtering on all IPv4 Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-all-rp-filter/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Use Reverse Path Filtering on all IPv4 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-rp-filter/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Parameter to
Use TCP Syncookies on Network Interfaces  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-tcp-syncookies/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable Kernel Paremeter to
Log Martian Packets on all IPv4 Interfaces by Default  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-net-ipv4-conf-default-log-martians/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable PAM  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-enable-pam/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable Randomized Layout of Virtual Address Space  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-kernel-randomize-va-space/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable rsyslog Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-rsyslog-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable SSH Warning Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-enable-warning-banner-net/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable systemd_timesyncd
Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-timesyncd-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable systemd-journald Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-systemd-journald-enabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable the NTP Daemon  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-ntpd-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enable the NTP Daemon (al2023)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-chronyd-or-ntpd-enabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Enable the NTP Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-ntp-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enforce usage of pam_wheel for su authentication  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-use-pam-wheel-for-su/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Enforce Usage of pam_wheel with Group Parameter for su Authentication  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-use-pam-wheel-group-for-su/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure /dev/shm is configured  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-partition-for-dev-shm/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure /tmp Located On Separate Partition  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-partition-for-tmp/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure /var/log Located On Separate Partition  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-partition-for-var-log/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure /var/log/audit Located On Separate Partition  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-partition-for-var-log-audit/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure a Table Exists for Nftables  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-nftables-table/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All Accounts on the System Have Unique Names  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-account-unique-name/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All Accounts on the System Have Unique User IDs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-account-unique-id/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All Files Are Owned by a Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-ungroupowned/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure All Files Are Owned
by a User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-files-unowned-by-user/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All Groups on the System Have Unique Group ID  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-group-unique-id/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All Groups on the System Have Unique Group Names  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-group-unique-name/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure All SGID Executables Are Authorized  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-unauthorized-sgid/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure All SUID Executables
Are Authorized  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-unauthorized-suid/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure All User
Initialization Files Have Mode 0740 Or Less Permissive  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permission-user-init-files/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure all users last
password change date is in the past  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-last-change-is-in-past/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Amazon GPG Key
Installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-amazon-gpgkey-installed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure AppArmor is enabled
in the bootloader configuration  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-grub2-enable-apparmor/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure AppArmor is installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-apparmor-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure auditd Collects File Deletion Events by User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-file-deletion-events/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure auditd Collects
Information on Exporting to Media (successful)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-media-export/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure auditd Collects Information on Kernel Module Loading and Unloading  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-kernel-module-loading/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure auditd Collects
Information on the Use of Privileged Commands  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-privileged-commands/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure auditd Collects
System Administrator Actions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-sysadmin-actions/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure auditd Collects
Unauthorized Access Attempts to Files (unsuccessful)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-unsuccessful-file-modification/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Authentication
Required for Single User Mode  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-root-password-configured/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Base Chains Exist for
Nftables  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-nftables-base-chain/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure gpgcheck Enabled for All yum Package Repositories  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-gpgcheck-never-disabled/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure gpgcheck Enabled In
Main yum Configuration  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-gpgcheck-globally-activated/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure ip6tables Firewall
Rules Exist for All Open Ports  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ip6tables-rules-for-open-ports/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure iptables Firewall
Rules Exist for All Open Ports  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-iptables-rules-for-open-ports/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure journald is
configured to compress large log files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-journald-compress/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure journald is configured to send logs to rsyslog  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-journald-forward-to-syslog/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure journald is configured to write log files to persistent disk  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-journald-storage/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure LDAP client is not installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-openldap-clients-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Local Login Warning
Banner Is Configured Properly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-issue-cis/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Log Files Are Owned By Appropriate Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-files-groupownership/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Log Files Are Owned
By Appropriate User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-files-ownership/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Logs Sent To Remote Host  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-remote-loghost/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Mail Transfer Agent is not Listening on any non-loopback Address  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-has-nonlocal-mta/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Message Of The Day Is Configured Properly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-motd-cis/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure network interfaces are assigned to appropriate zone  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-firewalld-appropriate-zone/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure nftables Default Deny
Firewall Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-nftables-ensure-default-deny-policy/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure nftables Rules are
Permanent  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-nftables-rules-permanent/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure No Daemons are Unconfined by SELinux  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-selinux-confinement-of-daemons/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure No World-Writable
Files Exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-unauthorized-world-writable/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Only Users Logged In
To Real tty Can Execute Sudo - sudo use_pty  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sudo-add-use-pty/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure PAM Enforces Password Requirements - Authentication Retry Prompts
Permitted Per-Session  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-retry/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure PAM Enforces Password Requirements - Enforce for root User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-enforce-root/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Different Categories  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-minclass/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Different Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-difok/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure PAM Enforces Password Requirements - Minimum Digit Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-dcredit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Length  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-minlen/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Lowercase Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-lcredit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Special Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-ocredit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Minimum Uppercase Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-ucredit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure PAM Enforces Password
Requirements - Prevent the Use of Dictionary Words  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-dictcheck/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Remote Login Warning
Banner Is Configured Properly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-issue-net-cis/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure rsyslog Default File Permissions Configured  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-filecreatemode/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure rsyslog Does Not Accept Remote Messages Unless Acting As Log Server  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-nolisten/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure rsyslog is Installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-rsyslog-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure SELinux is Not Disabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-selinux-not-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure SELinux Not Disabled in /etc/default/grub  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-grub2-enable-selinux/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure SELinux State is Enforcing  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-selinux-state/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure shadow Group is Empty  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-shadow-group-empty/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Software Patches Installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-security-patches-up-to-date/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure SSH LoginGraceTime is configured  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-login-grace-time/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure SSH MaxStartups is configured  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-maxstartups/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Sudo Logfile Exists - sudo logfile  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sudo-custom-logfile/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure System Log Files Have Correct Permissions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rsyslog-files-permissions/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that /etc/at.deny does not exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-at-deny-not-exist/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that /etc/cron.allow exists  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-cron-allow-exists/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that /etc/cron.deny does not exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-cron-deny-not-exist/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that chronyd is running under chrony user account  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-chronyd-run-as-chrony-user/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that Root's Path Does Not Include Relative Paths or Null Directories  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-root-path-no-dot/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure that Root's Path Does Not Include World or Group-Writable Directories  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-root-path-dirs-no-write/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure that System Accounts
Are Locked  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-password-auth-for-systemaccounts/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure that System Accounts
Do Not Run a Shell Upon Login  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-shelllogin-for-systemaccounts/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure the Default Bash
Umask is Set Correctly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-umask-etc-bashrc/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure the Default C Shell Umask is Set Correctly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-umask-etc-csh-cshrc/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure the Default Umask is
Set Correctly For Interactive Users  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-umask-interactive-users/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure the Default Umask is
Set Correctly in /etc/profile  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-umask-etc-profile/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure the Default Umask is Set Correctly in login.defs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-umask-etc-login-defs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure the Group Used by
pam_wheel.so Module Exists on System and is Empty  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ensure-pam-wheel-group-empty/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure There Are No Accounts
With Blank or Null Passwords  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-empty-passwords-etc-shadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure ufw Default Deny
Firewall Policy  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-ufw-default-rule/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure ufw Firewall Rules Exist for All Open Ports  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ufw-rules-for-open-ports/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Users Cannot Change GNOME3 Screensaver Settings  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-screensaver-user-locks/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Users Cannot Change
GNOME3 Session Idle Settings  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-session-idle-user-locks/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Ensure Users Re-Authenticate
for Privilege Escalation - sudo  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sudo-require-authentication/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure Users Re-Authenticate for Privilege Escalation - sudo !authenticate  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sudo-remove-no-authenticate/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Ensure users' .netrc Files are not group or world accessible  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-users-netrc-file-permissions/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install AIDE  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-aide-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install firewalld Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-firewalld-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install iptables Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-iptables-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install iptables-persistent Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-iptables-persistent-installed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install libselinux Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-libselinux-installed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install nftables Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-nftables-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install PAE Kernel on Supported 32-bit x86 Systems  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-install-pae-kernel-on-x86-32/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install pam_pwquality
Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-pam-pwquality-installed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install sudo Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-sudo-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install systemd-journal-remote Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-systemd-journal-remote-installed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Install the cron service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-cron-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install the systemd_timesyncd Service  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-timesyncd-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Install ufw Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-ufw-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Limit Password Reuse  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-pwhistory-remember/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Limit Password Reuse (STIGs
- ubuntu2004)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-unix-remember/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Limit Password Reuse:
password-auth  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-pwhistory-remember-password-auth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Limit Password Reuse:
system-auth  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-pwhistory-remember-system-auth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Limit Users' SSH Access  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-limit-user-access/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Lock Accounts After Failed Password Attempts  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-passwords-pam-faillock-deny/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Make sure that the dconf
databases are up-to-date with regards to respective keyfiles  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-db-up-to-date/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Modify the System Login Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-issue/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Modify the System Login Banner for Remote Connections  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-issue-net/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Modify the System Message of the Day Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-banner-etc-motd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Package "prelink" Must not be Installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-prelink-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Prevent Login to Accounts With Empty Password  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-empty-passwords/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Record Attempts to Alter the localtime File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-time-watch-localtime/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Record attempts to alter
time through adjtimex  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-time-adjtimex/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Record Attempts to Alter Time Through clock_settime  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-time-clock-settime/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Record attempts to alter
time through settimeofday  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-time-settimeofday/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Record Attempts to Alter
Time Through stime  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-time-stime/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Record Events that Modify the System's Mandatory Access Controls  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-mac-modification/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Record Events that Modify
the System's Network Environment  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-networkconfig-modification/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Record Events that Modify
User/Group Information  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-audit-rules-usergroup-modification/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Remove ftp Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-ftp-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove iptables-persistent Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-iptables-persistent-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Remove NIS Client  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-ypbind-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove Rsh Trust Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-rsh-trust-files/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove telnet Clients  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-telnet-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove tftp Daemon  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-tftp-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove the GDM Package Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-gdm-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Remove the X Windows Package Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-xorg-x11-server-common-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Remove ufw Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-ufw-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Require Authentication for Emergency Systemd Target  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-require-emergency-target-auth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Require Authentication for
Single User Mode  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-require-singleuser-auth/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Require Re-Authentication When Using the sudo Command  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sudo-require-reauthentication/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Restrict Serial Port Root
Logins  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-restrict-serial-port-logins/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Restrict usage of ptrace to descendant processes  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sysctl-kernel-yama-ptrace-scope/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Restrict Virtual Console
Root Logins  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-securetty-root-login-console-only/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Account Expiration
Following Inactivity  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-account-disable-post-pw-expiration/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set configuration for IPv6
loopback traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-ipv6-loopback-traffic/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set configuration for loopback traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-loopback-traffic/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set Default firewalld Zone for Incoming Packets  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-firewalld-default-zone/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set Default ip6tables Policy for Incoming Packets  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-ip6tables-default-rule/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set Default iptables Policy for Incoming Packets  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-iptables-default-rule/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set Deny For Failed Password Attempts  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-passwords-pam-tally2/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set existing passwords a
period of inactivity before they been locked  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-set-post-pw-existing/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Existing Passwords
Maximum Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-set-max-life-existing/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Existing Passwords
Minimum Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-set-min-life-existing/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Existing Passwords
Warning Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-set-warn-age-existing/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set GNOME3 Screensaver
Inactivity Timeout  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-screensaver-idle-delay/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set GNOME3 Screensaver Lock
Delay After Activation Period  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-screensaver-lock-delay/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Interactive Session
Timeout  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-tmout/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set Interval For Counting Failed Password Attempts  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-passwords-pam-faillock-interval/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Lockout Time for Failed
Password Attempts  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-passwords-pam-faillock-unlock-time/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set LogLevel to INFO  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-loglevel-info/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set nftables Configuration for Loopback Traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-nftables-loopback-traffic/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set PAM''s Password Hashing
Algorithm  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-password-hashing-algorithm-systemauth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set PAM''s Password Hashing
Algorithm - password-auth  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-password-hashing-algorithm-passwordauth/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Hashing
Algorithm in /etc/libuser.conf  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-password-hashing-algorithm-libuserconf/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Hashing
Algorithm in /etc/login.defs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-password-hashing-algorithm-logindefs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Maximum Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-maximum-age-login-defs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Maximum
Consecutive Repeating Characters  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-pam-maxrepeat/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Minimum Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-minimum-age-login-defs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Minimum Length
in login.defs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-minlen-login-defs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set Password Warning Age  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-warn-age-login-defs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set SSH authentication
attempt limit  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-max-auth-tries/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set SSH Client Alive Count Max  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-keepalive/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set SSH Client Alive Interval  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-idle-timeout/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set SSH Daemon LogLevel to VERBOSE  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-loglevel-verbose/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set SSH MaxSessions limit  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-set-max-sessions/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Set the GNOME3 Login Warning Banner Text  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dconf-gnome-login-banner-text/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Set UFW Loopback Traffic  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-set-ufw-loopback-traffic/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Specify a Remote NTP Server  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-ntpd-specify-remote-server/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
System Audit Logs Must Be Group Owned By Root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-group-ownership-var-log-audit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) System Audit Logs Must Be
Owned By Root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-var-log-audit-stig/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) System Audit Logs Must Be
Owned By Root (al2023)  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-var-log-audit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) System Audit Logs Must Have
Mode 0640 or Less Permissive  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-var-log-audit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) System Audit Logs Must Have
Mode 0750 or Less Permissive  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-directory-permissions-var-log-audit/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) The Chrony package is
installed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-chrony-installed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
The Chronyd service is enabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-chronyd-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall avahi Server Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-avahi-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall bind Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-bind-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall CUPS Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-cups-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall cyrus-imapd Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-cyrus-imapd-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall DHCP Server Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-dhcp-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall dnsmasq Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-dnsmasq-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall dovecot Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-dovecot-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall httpd Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-httpd-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall mcstrans Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-mcstrans-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall net-snmp Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-net-snmp-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall nfs-kernel-server Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-nfs-kernel-server-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Uninstall nftables package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-nftables-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall nginx Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-nginx-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall openldap-servers Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-openldap-servers-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Uninstall rpcbind Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-rpcbind-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall rsh Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-rsh-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall rsync Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-rsync-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall Samba Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-samba-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall setroubleshoot Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-setroubleshoot-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Uninstall squid Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-squid-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall talk Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-talk-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall telnet-server Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-telnet-server-removed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Uninstall tftp-server
Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-tftp-server-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall the nis package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-nis-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall vsftpd Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-vsftpd-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall xinetd Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-xinetd-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Uninstall ypserv Package  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-package-ypserv-removed/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Use Only FIPS 140-2 Validated Ciphers  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-use-approved-ciphers/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Use Only FIPS 140-2 Validated MACs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-use-approved-macs/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Use Only Strong Ciphers  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-use-strong-ciphers/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Use Only Strong Key Exchange algorithms  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-use-strong-kex/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Use Only Strong MACs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-sshd-use-strong-macs/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
User Initialization Files Must Be Group-Owned By The Primary Group  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-user-dot-group-ownership/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User Initialization Files
Must Be Owned By the Primary User  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-user-dot-user-ownership/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) User Initialization Files
Must Not Run World-Writable Programs  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-user-dot-no-world-writable-programs/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify
/boot/efi/EFI/redhat/user.cfg Group Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-efi-user-cfg/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify
/boot/efi/EFI/redhat/user.cfg Permissions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-efi-user-cfg/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify
/boot/efi/EFI/redhat/user.cfg User Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-efi-user-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub/grub.cfg Permissions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-grub2-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub/grub.cfg User Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-grub2-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub2/grub.cfg Group Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-grub2-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub2/user.cfg Group Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-user-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub2/user.cfg Permissions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-user-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify /boot/grub2/user.cfg User Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-user-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify All Account Password Hashes are Shadowed  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-all-shadowed/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify All Account Password
Hashes are Shadowed with SHA512  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-password-all-shadowed-sha512/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify and Correct File
Permissions with RPM  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rpm-verify-permissions/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify File Hashes with RPM  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-rpm-verify-hashes/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify firewalld Enabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-firewalld-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Ownership of Message of the Day Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-motd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Ownership of System Login Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-issue/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Ownership of System Login Banner for Remote Connections  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-issue-net/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Ownership on
SSH Server Private *_key Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupownership-sshd-private-key/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Ownership on
SSH Server Public *.pub Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupownership-sshd-pub-key/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns
/etc/at.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-at-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns /etc/cron.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns /etc/shells File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-shells/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns Backup group File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-backup-etc-group/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns Backup
gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-backup-etc-gshadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns Backup
passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-backup-etc-passwd/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns Backup
shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-backup-etc-shadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns cron.d  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-d/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns cron.daily  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-daily/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns cron.hourly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-hourly/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns cron.monthly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-monthly/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Group Who Owns
cron.weekly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-cron-weekly/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns Crontab  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-crontab/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns group File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-group/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-gshadow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-passwd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-etc-shadow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Group Who Owns SSH Server config file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-sshd-config/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify nftables Service is Disabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-nftables-disabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify nftables Service is Enabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-nftables-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify No .forward Files Exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-forward-files/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify No netrc Files Exist  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-no-netrc-files/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Only Root Has UID 0  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-no-uid-except-zero/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on cron.d  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-d/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on cron.daily  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-daily/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on cron.hourly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-hourly/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on cron.monthly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-monthly/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on cron.weekly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-weekly/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on crontab  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-crontab/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Owner on SSH Server config file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-sshd-config/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify ownership of Message of the Day Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-motd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify ownership of System Login Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-issue/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify ownership of System Login Banner for Remote Connections  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-issue-net/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Ownership on SSH Server Private *_key Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-sshd-private-key/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Ownership on SSH
Server Public *.pub Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-sshd-pub-key/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions and Ownership of Old Passwords File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-etc-security-opasswd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify permissions of log files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-permissions-local-var-log/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on /etc/at.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-at-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on /etc/audit/auditd.conf  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-audit-auditd/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on
/etc/audit/rules.d/*.rules  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-audit-rulesd/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on
/etc/cron.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on /etc/shells File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-shells/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on Backup group File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-backup-etc-group/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on Backup
gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-backup-etc-gshadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on Backup
passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-backup-etc-passwd/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on Backup
shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-backup-etc-shadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on cron.d  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-d/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on cron.daily  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-daily/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on cron.hourly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-hourly/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on
cron.monthly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-monthly/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on
cron.weekly  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-cron-weekly/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on
crontab  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-crontab/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on group File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-group/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-gshadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify permissions on
Message of the Day Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-motd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-passwd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-shadow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Permissions on SSH Server config file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-sshd-config/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on SSH
Server Private *_key Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-sshd-private-key/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Permissions on SSH
Server Public *.pub Key Files  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-sshd-pub-key/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify permissions on System
Login Banner  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-issue/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify permissions on System Login Banner for Remote Connections  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-etc-issue-net/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify Root Has A Primary
GID 0  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-accounts-root-gid-zero/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify that All World-Writable Directories Have Sticky Bits Set  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-dir-perms-world-writable-sticky-bits/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify that audit tools are
owned by group root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupownership-audit-binaries/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify that audit tools are
owned by root  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-ownership-audit-binaries/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify that audit tools Have
Mode 0755 or less  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-audit-binaries/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify the UEFI Boot Loader
grub.cfg Group Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-efi-grub2-cfg/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify the UEFI Boot Loader
grub.cfg Permissions  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-permissions-efi-grub2-cfg/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify the UEFI Boot Loader
grub.cfg User Ownership  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-efi-grub2-cfg/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify ufw Enabled  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-service-ufw-enabled/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns /etc/at.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-at-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns /etc/cron.allow file  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-cron-allow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns Backup group File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-backup-etc-group/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns Backup gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-backup-etc-gshadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify User Who Owns Backup
passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-backup-etc-passwd/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify User Who Owns Backup
shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-groupowner-backup-etc-shadow/)[![host-
benchmarks](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Verify User Who Owns group
File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-group/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns gshadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-gshadow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns passwd File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-passwd/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify User Who Owns shadow File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-shadow/)[![host-benchmarks](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Verify Who Owns /etc/shells File  
](https://docs.datadoghq.com/security/default_rules/xccdf-org-ssgproject-
content-rule-file-owner-etc-shells/)

![iam](https://static.datadoghq.com/static/images/logos/aws-iam_avatar.svg)

IAM ____

>

[![iam](https://static.datadoghq.com/static/images/logos/aws-iam_avatar.svg)
Access keys granting 'root' should be removed  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-access-
keys-granting-root-should-be-
removed/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Access keys should be rotated every 90 days or less  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-access-keys-
should-be-rotated-every-90-days-or-
less/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS Cognito identity pool has guest access configured for a
role with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/cognito-identity-pool-
guest-role-admin-
access/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can assume a role with administrative
privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-admin-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can assume a role with administrative
privileges cross-account  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-cross-
account-admin-assume-
role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can assume multiple roles with administrative
privileges cross-account  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-cross-
account-admin-assume-multiple-
roles/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can create a login profile for an IAM user
with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-login-
profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can create access keys for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-create-
access-key/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can update a login profile for an IAM user
with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-update-
login-profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance can update the trust policy for a role with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-update-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS EC2 instance has administrative privileges  
](https://docs.datadoghq.com/security/default_rules/ec2-instance-with-admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group can assume a role with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-admin-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group can create a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-create-
login-profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group can create access keys for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-create-
access-key/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group can update a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-update-
login-profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group can update the trust policy for a role with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-update-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/blast-radius-
group/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM group has administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-groups-with-admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM policy with administrative privileges is not attached
to any principal  
](https://docs.datadoghq.com/security/default_rules/unattached-policies-with-
admin/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can assume a role with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-admin-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can assume a role with administrative privileges
cross-account  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-cross-
account-admin-assume-
role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can assume multiple roles with administrative
privileges cross-account  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-cross-
account-admin-assume-multiple-
roles/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can create a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-login-
profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can create access keys for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-create-
access-key/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can update a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-update-
login-profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role can update the trust policy for a role with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-update-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role has a large permissions gap  
](https://docs.datadoghq.com/security/default_rules/perms-gap-
role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role has a trust relationship with a wildcard
principal  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-wildcard-
trust/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/blast-radius-
role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role has administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role has administrative privileges and is inactive  
](https://docs.datadoghq.com/security/default_rules/iam-inactive-roles-with-
admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role with administrative privileges has a trust
relationship with a wildcard principal  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-admin-
wildcard-trust/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM role with external cross-account trust relationship
does not use an external ID  
](https://docs.datadoghq.com/security/default_rules/iam-roles-with-external-
access/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can assume a role with administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-admin-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can assume a role with administrative privileges
cross-account  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-cross-
account-admin-assume-
role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can assume multiple roles with administrative
privileges cross-account  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-cross-
account-admin-assume-multiple-
roles/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can create a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-login-
profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can create access keys for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-create-
access-key/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can update a login profile for an IAM user with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-update-
login-profile/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user can update the trust policy for a role with
administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-update-
assume-role/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user has a large permissions gap  
](https://docs.datadoghq.com/security/default_rules/perms-gap-
user/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user has access to a large number of resources  
](https://docs.datadoghq.com/security/default_rules/blast-radius-
user/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user has administrative privileges  
](https://docs.datadoghq.com/security/default_rules/iam-users-with-admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS IAM user has administrative privileges and is inactive  
](https://docs.datadoghq.com/security/default_rules/iam-users-inactive-with-
admin/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) AWS Lambda function has administrative privileges  
](https://docs.datadoghq.com/security/default_rules/lambda-function-with-
admin-
privileges/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Expired SSL/TLS certificates should be removed from AWS IAM  
](https://docs.datadoghq.com/security/default_rules/aws-iam-server-
certificate-expired-ssl-tls-certificates-should-be-removed-from-aws-
iam/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM Access Analyzer should be enabled in all active regions  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-region-iam-access-
analyzer-should-be-enabled-in-all-active-
regions/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM access keys that are inactive and older than 1 year should
be removed  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-access-
keys-that-are-inactive-and-older-than-1-year-should-be-
removed/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM customer managed policies should not allow decryption
actions on all KMS keys  
](https://docs.datadoghq.com/security/default_rules/aws-iam-policy-iam-
customer-managed-policies-should-not-allow-decryption-actions-on-all-kms-
keys/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM customer managed policies should not allow wildcard
actions for services  
](https://docs.datadoghq.com/security/default_rules/aws-iam-policy-iam-
customer-managed-policies-should-not-allow-wildcard-actions-for-
services/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM groups should have assigned permissions  
](https://docs.datadoghq.com/security/default_rules/aws-iam-group-iam-groups-
should-have-assigned-
permissions/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM groups should have at least one user attached  
](https://docs.datadoghq.com/security/default_rules/aws-iam-group-iam-groups-
should-have-at-least-one-user-
attached/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM groups should not have IAM inline policies that allow
decryption actions on all KMS keys  
](https://docs.datadoghq.com/security/default_rules/aws-iam-group-inline-
policy-iam-groups-should-not-have-iam-inline-policies-that-allow-decryption-
actions-on-all-kms-
keys/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM groups should not have inline policies attached  
](https://docs.datadoghq.com/security/default_rules/aws-iam-group-iam-groups-
should-not-have-inline-policies-
attached/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM password policy should require at least one lowercase
letter  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
password-policy-should-require-at-least-one-lowercase-
letter/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM password policy should require at least one number in
passwords  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
password-policy-should-require-at-least-one-number-in-
passwords/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM password policy should require at least one symbol  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
password-policy-should-require-at-least-one-
symbol/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM password policy should require uppercase characters  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
password-policy-should-require-uppercase-
characters/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM password policy should require user passwords to expire
within 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-iam-
password-policy-should-require-user-passwords-to-expire-
within-90-days/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM policies should adhere to least-privilege  
](https://docs.datadoghq.com/security/default_rules/aws-iam-policy-iam-
policies-should-adhere-to-least-
privilege/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM policies should be attached and managed at the group level  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-policies-
should-be-attached-and-managed-at-the-group-
level/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM policies should not use 'Effect: Allow' with 'NotAction'  
](https://docs.datadoghq.com/security/default_rules/aws-iam-policy-iam-
policies-should-not-use-effect-allow-with-
notaction/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles should be used within the last 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-iam-roles-
should-be-used-within-the-
last-90-days/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles should not allow untrusted GitHub Actions to assume
them  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-iam-roles-
should-not-allow-untrusted-github-actions-to-assume-
them/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles should not allow untrusted GitLab runners to assume
them  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-iam-roles-
should-not-allow-untrusted-gitlab-runners-to-assume-
them/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles should not have a trust policy that contains a
wildcard principal  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-iam-roles-
should-not-have-a-trust-policy-that-contains-a-wildcard-
principal/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles should not have IAM inline policies that allow
decryption actions on all KMS keys  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-inline-
policy-iam-roles-should-not-have-iam-inline-policies-that-allow-decryption-
actions-on-all-kms-
keys/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM roles with policies attached should be used within the
last 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-iam-role-iam-roles-
with-policies-attached-should-be-used-within-the-
last-90-days/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM server certificate should be renewed 30 days before
expiration  
](https://docs.datadoghq.com/security/default_rules/aws-iam-server-
certificate-iam-server-certificate-should-be-renewed-30-days-before-
expiration/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM User access keys should be created after initial setup  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-user-
access-keys-should-be-created-after-initial-
setup/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM users should have assigned permissions  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-users-
should-have-assigned-
permissions/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM users should not have both Console access and Access Keys  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-users-
should-not-have-both-console-access-and-access-
keys/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM users should not have IAM inline policies that allow
decryption actions on all KMS keys  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-inline-
policy-iam-users-should-not-have-iam-inline-policies-that-allow-decryption-
actions-on-all-kms-
keys/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) IAM users should not have the 'AdministratorAccess' policy
attached  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-users-
should-not-have-the-administratoraccess-policy-
attached/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Known compromised IAM users should not be present in the
account  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-known-
compromised-iam-users-should-not-be-present-in-the-
account/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) MFA should be enabled for all users with console access  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-mfa-should-
be-enabled-for-all-users-with-console-
access/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) MFA should be enabled for the 'root' account  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-mfa-
should-be-enabled-for-the-root-
account/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Only one active access key should exist per user  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-only-one-
active-access-key-should-exist-per-
user/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Password policy should prevent password reuse  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-password-
policy-should-prevent-password-
reuse/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Password policy should require at least 14 characters  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-password-
policy-should-require-at-
least-14-characters/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Support roles should be created to manage incidents with AWS
Support  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-support-
roles-should-be-created-to-manage-incidents-with-aws-
support/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) The 'root' account should not be used for daily tasks  
](https://docs.datadoghq.com/security/default_rules/aws-iam-credential-report-
the-root-account-should-not-be-used-for-daily-
tasks/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) The 'root' user account should use hardware-based MFA  
](https://docs.datadoghq.com/security/default_rules/aws-iam-account-the-root-
user-account-should-use-hardware-based-
mfa/)[![iam](https://static.datadoghq.com/static/images/logos/aws-
iam_avatar.svg) Unused credentials should be deactivated or removed  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-unused-
credentials-should-be-deactivated-or-removed/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

IAM Account ____

>

[![iam_account](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) AWS Config should be enabled
and recording in all active regions  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-region-aws-config-
should-be-enabled-and-recording-in-all-active-regions/)

![iis](https://static.datadoghq.com/static/images/logos/iis_avatar.svg)

IIS ____

>

[![iis](https://static.datadoghq.com/static/images/logos/iis_avatar.svg) IIS
HTTP requests from security scanner  
](https://docs.datadoghq.com/security/default_rules/iis-scanner-detected/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Jamfprotect ____

>

[![jamfprotect](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Jamf Protect alerts  
](https://docs.datadoghq.com/security/default_rules/jamf-protect-
alerts/)[![jamfprotect](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Jamf Protect threat events  
](https://docs.datadoghq.com/security/default_rules/jamf-protect-threat-
events/)

![jira-audit-
records](https://static.datadoghq.com/static/images/logos/jira_avatar.svg)

Jira Audit Records ____

>

[![jira-audit-
records](https://static.datadoghq.com/static/images/logos/jira_avatar.svg)
Atlassian Tor client activity detected  
](https://docs.datadoghq.com/security/default_rules/atlassian-tor-client-
activity/)

![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)

Jumpcloud ____

>

[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Credential stuffing attack on Jumpcloud  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-credential-
stuffing-
attack/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud admin granted system privileges  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-user-granted-
system-
admin/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud admin login without MFA  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-admin-login-no-
mfa/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud admin triggered impossible travel scenario  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-admin-
impossible-
travel/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud administrator role assigned  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-admin-role-
assigned/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-brute-force-
attack/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud password manager local export  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-password-
manager-
export/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud policy created  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-policy-
created/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Jumpcloud policy modified  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-policy-
modified/)[![jumpcloud](https://static.datadoghq.com/static/images/logos/jumpcloud_avatar.svg)
Multiple Jumpcloud push notifications denied  
](https://docs.datadoghq.com/security/default_rules/jumpcloud-multiple-push-
notifications-denied/)

![kinesis](https://static.datadoghq.com/static/images/logos/amazon-
kinesis_avatar.svg)

Kinesis ____

>

[![kinesis](https://static.datadoghq.com/static/images/logos/amazon-
kinesis_avatar.svg) Kinesis streams should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-kinesis-stream-
kinesis-streams-should-be-encrypted-at-rest/)

![kms](https://static.datadoghq.com/static/images/logos/amazon-kms_avatar.svg)

KMS ____

>

[![kms](https://static.datadoghq.com/static/images/logos/amazon-
kms_avatar.svg) KMS key policy should not allow everyone to use it  
](https://docs.datadoghq.com/security/default_rules/aws-kms-key-
public/)[![kms](https://static.datadoghq.com/static/images/logos/amazon-
kms_avatar.svg) KMS keys should not be unintentionally deleted  
](https://docs.datadoghq.com/security/default_rules/aws-kms-aws-kms-keys-
should-not-be-unintentionally-
deleted/)[![kms](https://static.datadoghq.com/static/images/logos/amazon-
kms_avatar.svg) Symmetric CMKs should have encryption key rotation enabled  
](https://docs.datadoghq.com/security/default_rules/aws-kms-symmetric-cmks-
should-have-encryption-key-rotation-enabled/)

![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)

Kubernetes ____

>

[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
[Deprecated The /etc/kubernetes/manifests/etcd.yaml file ownership should be
root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.8/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
A Kubernetes audit policy should exist  
](https://docs.datadoghq.com/security/default_rules/api_server_minimal_audit_policy_exists/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
A Kubernetes user attempted to perform a high number of actions that were
denied  
](https://docs.datadoghq.com/security/default_rules/kubernetes-high-number-of-
access-
denied/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
A Kubernetes user was assigned cluster administrator permissions  
](https://docs.datadoghq.com/security/default_rules/kubernetes-
clusterrolebinding-cluster-admin-
created/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
A new Kubernetes admission controller was created  
](https://docs.datadoghq.com/security/default_rules/kubernetes-new-admission-
controller/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
All requests should not be allowed; explicit authorization should be enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server audit log files should be retained for at least 10 log file
rotations  
](https://docs.datadoghq.com/security/default_rules/api_server_audit_log_files_retained_at_least_10_log_file_rotations/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server audit logs should be enabled  
](https://docs.datadoghq.com/security/default_rules/api_server_audit_logs_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server audit logs should be retained for at least 30 days  
](https://docs.datadoghq.com/security/default_rules/api_server_audit_logs_retained_at_least_30_days/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server should have the anonymous-auth argument set to false  
](https://docs.datadoghq.com/security/default_rules/kubelet_api_server_anonymous_auth_argument_set_to_false/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server should only authorize explicitly authorized requests  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.7/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
API server should verify the kubelet's certificate before establishing
connection  
](https://docs.datadoghq.com/security/default_rules/api_server_verifies_kubelets_certificate_before_establishing_connection/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Application with a critical vulnerability in a container with elevated
privileges  
](https://docs.datadoghq.com/security/default_rules/risky-container-crit-vuln-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Application with a critical vulnerability in a container with elevated
privileges assigned to a privileged Kubernetes node  
](https://docs.datadoghq.com/security/default_rules/risky-container-crit-vuln-
priv-node-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Certificate-based kubelet authentication should be required  
](https://docs.datadoghq.com/security/default_rules/api_server_certificate_based_kubelet_authentication_required/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Container with elevated privileges assigned to a privileged Kubernetes node  
](https://docs.datadoghq.com/security/default_rules/risky-container-priv-node-
kubernetes_node/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Containers should not be allowed to share the host network namespace  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.2.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Containers should not be generally permitted to run with hostIPC flag  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.2.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Containers should not be run with allowPrivilegeEscalation flag set to true  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.2.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Containers should not be run with the hostPID flag set to true  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.2.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Controller Manager profiling should be disabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Each controller should use individual service account credentials  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Each controller should use individual service account credentials  
](https://docs.datadoghq.com/security/default_rules/controller_manager_each_uses_individual_service_account_credentials/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd data directory should have permissions of 700 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.11/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd key-value store should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/api_server_etcd_encrypted_at_rest/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd key-value store should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.33/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd pod specification file should have permissions of 600 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/pod_specification_etcd_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd server should require API servers to present a client certificate and key
when connecting  
](https://docs.datadoghq.com/security/default_rules/api_server_etcd_server_requires_s_present_client_certificate_and_key_when_connecting/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
etcd servers should make use of TLS encryption for client connections  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.29/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd service should have client authentication enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should be configured for peer authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should be configured with TLS encryption  
](https://docs.datadoghq.com/security/default_rules/etcd_configured_with_tls_encryption/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should have client authentication enabled  
](https://docs.datadoghq.com/security/default_rules/etcd_client_authentication_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should have peer authentication configured  
](https://docs.datadoghq.com/security/default_rules/etcd_configured_peer_authentication/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should only allow the use of valid client certificates  
](https://docs.datadoghq.com/security/default_rules/etcd_only_allows_valid_client_certificates/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
etcd should use TLS encryption for client connections  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.32/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should use TLS encryption for peer connections  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Etcd should use TLS encryption for peer connections  
](https://docs.datadoghq.com/security/default_rules/etcd_uses_tls_encryption_peer_connections/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Ingress NGINX Controller pod is vulnerable to critical remote code execution
vulnerability (IngressNightmare)  
](https://docs.datadoghq.com/security/default_rules/pod_vulnerable_to_ingressnightmare/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kube-proxy configuration file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/kube_proxy_configuration_file_ownership_assigned_to_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kube-proxy configuration file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/kube_proxy_configuration_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet authentication should require certificate-based authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet client certificate rotation should be enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.11/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet connections should use HTTPS for enhanced security  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet default kernel parameter values should be protected from overriding.  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet nodes should only be authorized to read objects they are associated
with  
](https://docs.datadoghq.com/security/default_rules/api_server_kubelet_nodes_only_authorized_to_read_objects_they_associated_with/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet nodes should only read objects associated with them  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.8/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet server certificate rotation should be enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.12/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet should be able to manage changes to iptables  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.7/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet should enable authentication using certificates for TLS client
authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet should only allow explicitly authorized requests  
](https://docs.datadoghq.com/security/default_rules/kubelet_only_allows_explicitly_authorized_requests/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet should require HTTPS connections  
](https://docs.datadoghq.com/security/default_rules/kubelet_requires_https_connections/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelet should use TLS certificate client authentication  
](https://docs.datadoghq.com/security/default_rules/kubelet_uses_tls_certificate_client_authentication/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelets should be allowed to manage changes to the iptables  
](https://docs.datadoghq.com/security/default_rules/kubelet_allow_to_manage_changes_to_iptables/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubelets should have HTTPS connections with TLS setup  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.10/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes API server profiling should be disabled  
](https://docs.datadoghq.com/security/default_rules/api_server_profiling_disabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes PKI certificate files should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/kubernetes_pki_certificate_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes PKI certificate files should have permissions of 644 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.20/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes Pod Created in Kube Namespace  
](https://docs.datadoghq.com/security/default_rules/kubernetes-pod-created-in-
kube-
namespace/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes Pod Created with hostNetwork  
](https://docs.datadoghq.com/security/default_rules/kubernetes-pod-created-
with-
hostnetwork/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes principal attempted to enumerate their permissions  
](https://docs.datadoghq.com/security/default_rules/kubernetes-principal-
enumerate-
permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes Service Account Created in Kube Namespace  
](https://docs.datadoghq.com/security/default_rules/kubernetes-service-
account-created-in-kube-
namespace/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Kubernetes Service Created with NodePort  
](https://docs.datadoghq.com/security/default_rules/kubernetes-service-
created-with-
nodeport/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Log files for the API server should be rotated at 100 MB  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.25/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Logs for API server audits should be retained for 30 days  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.23/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Network policies should be defined to isolate traffic in cluster network  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.3.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
New Kubernetes Namespace Created  
](https://docs.datadoghq.com/security/default_rules/kubernetes-new-kubernetes-
namespace-
created/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
New Kubernetes privileged pod created  
](https://docs.datadoghq.com/security/default_rules/kubernetes-new-privileged-
pod/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Pods should use `root-ca-file` to pass serving certificates to the API server  
](https://docs.datadoghq.com/security/default_rules/controller_manager_pods_utilize_root_ca_file_to_pass_serving_certificates_to_api_server/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Pods should verify the API server's serving certificate before connecting  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
PodSecurityPolicy should be enabled to reject non-compliant pod creations  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.16/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Profiling for API server should be disabled, if not needed  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.21/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Publicly accessible application in a container with elevated privileges
assigned to a privileged Kubernetes node  
](https://docs.datadoghq.com/security/default_rules/risky-container-public-
app-priv-node-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Publicly accessible application in container with elevated privileges  
](https://docs.datadoghq.com/security/default_rules/risky-container-public-
app-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Publicly accessible application with a critical vulnerability in a container
with elevated privileges  
](https://docs.datadoghq.com/security/default_rules/risky-container-public-
app-crit-vuln-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Publicly accessible application with a critical vulnerability running on a
privileged Kubernetes node  
](https://docs.datadoghq.com/security/default_rules/risky-container-public-
app-crit-vuln-priv-node-
service/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
RBAC should be enabled for the API server  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.9/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
RBAC should be enabled for the Kubernetes API server  
](https://docs.datadoghq.com/security/default_rules/api_server_rbac_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Resources should be created in a non-default namespace in Kubernetes  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.7.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Scheduler profiling should be disabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.4.1/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Scheduler profiling should be disabled  
](https://docs.datadoghq.com/security/default_rules/scheduler_profiling_disabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Scheduler.conf file should only be alterable by owners with permissions of 644
or more restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.15/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Self-signed certificates should not be used for etcd TLS  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Service accounts management should be automated  
](https://docs.datadoghq.com/security/default_rules/api_server_admission_controller_serviceaccount_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Service accounts on the controller manager should have a private key file set  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Streaming connections should have timeouts enabled  
](https://docs.datadoghq.com/security/default_rules/kubelet_timeouts_on_streaming_connections_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
Streaming connections should have timeouts enabled and not be disabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The --audit-policy-file flag should be set for Kubernetes logging to be
enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-3.2.1/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The /etc/kubernetes/manifests/etcd.yaml file should have permissions of 644 or
stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.7/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The `admin.conf` file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/only_root_account_and_group_have_ownership_of_adminconf_file/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The `admin.conf` file should have permissions of 600 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/only_root_account_has_write_permissions_to_adminconf_file/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The `controller-manager.conf` file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/controller_manager_conf_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The `controller-manager.conf` file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/controller_manager_conf_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The admin.conf file should have permissions of 644 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.13/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server audit log files should be rotated once the file reaches 100 MB
or more  
](https://docs.datadoghq.com/security/default_rules/api_server_audit_log_files_rotated_once_file_reaches_100_mb_or_more/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server pod specification file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/api_server_pod_specification_file_ownership_assigned_to_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server pod specification file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/api_server_pod_specification_file_permissions_atleast_600/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should explicitly set a service account public key file  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.28/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should have a TLS connection setup  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.30/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should not allow anonymous requests to Kubelet  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.1/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should not use basic authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should only bind to secure, known ports  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.19/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API Server should require HTTPS connections  
](https://docs.datadoghq.com/security/default_rules/api_server_requires_https_connections/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should set up TLS connection for client authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.31/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should use secure authentication methods without token based
authentication  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should validate the service account token in etcd  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.27/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The API server should verify the kubelet's certificate before connecting  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The certificate authorities file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.8/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The certificate authorities file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/kubelet_certificate_authorities_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The certificate authorities file should have permissions of 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.7/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The client certificate authorities file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/kubelet_client_certificate_authorities_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Controller Manager API service should be bound to localhost  
](https://docs.datadoghq.com/security/default_rules/controller_manager_api_service_bound_to_localhost/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Controller Manager API service should only bind to localhost  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.7/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller manager pod specification file ownership should be root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller manager pod specification file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/pod_specification_controller_manager_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller manager pod specification file should have permissions of 600
or more restrictive  
](https://docs.datadoghq.com/security/default_rules/pod_specification_controller_manager_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Controller Manager profiling should be disabled  
](https://docs.datadoghq.com/security/default_rules/controller_manager_profiling_disabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller manager should have a service account private key file set  
](https://docs.datadoghq.com/security/default_rules/controller_manager_has_service_account_private_key_file_set/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller-manager.conf file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.18/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The controller-manager.conf file should have permissions of 644 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.17/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The default service account should not be used  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-5.1.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd data directory should be owned by etcd:etcd  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.12/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd data directory should be owned by the etcd user and group  
](https://docs.datadoghq.com/security/default_rules/etcd_data_directory_owned_by_etcd_user_and_group/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd data directory should have permissions of 700 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/etcd_data_directory_permissions_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd pod specification file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/pod_specification_etcd_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd server should require API servers to present an SSL CA file when
connecting  
](https://docs.datadoghq.com/security/default_rules/api_server_etcd_server_requires_s_present_an_ssl_ca_file_when_connecting/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The etcd service should be configured with TLS encryption  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.1/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The global request timeout for API server requests should be set appropriately  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.26/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The insecure API service should not be bound  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.18/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kube-proxy configuration file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet client certificate rotation should be enabled  
](https://docs.datadoghq.com/security/default_rules/kubelet_client_certificate_rotation_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet configuration file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/kubelet_configuration_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet configuration file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.10/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet configuration file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/kubelet_configuration_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet configuration file should have permissions of 644 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.9/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet read-only port should be disabled  
](https://docs.datadoghq.com/security/default_rules/kubelet_read_only_port_disabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet server certificate rotation on controller-manager should be
enabled  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.3.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet server certificate rotation on the controller-manager should be
enabled  
](https://docs.datadoghq.com/security/default_rules/controller_manager_enable_kubelet_server_certificate_rotation_on/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet server certificate rotation should be enabled  
](https://docs.datadoghq.com/security/default_rules/kubelet_server_certificate_rotation_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet service file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/kubelet_service_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet service file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet service file should have permissions of 600 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/kubelet_service_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet service file should have permissions of 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.1/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet.conf file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet.conf file should be owned by root  
](https://docs.datadoghq.com/security/default_rules/kubelet_conf_file_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet.conf file should have permissions of 600 or more restrictive  
](https://docs.datadoghq.com/security/default_rules/kubelet_conf_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The kubelet.conf file should have permissions of 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes admission controller 'AlwaysAdmit' should be disabled  
](https://docs.datadoghq.com/security/default_rules/api_server_admission_controller_alwaysadmit_disabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes admission controller 'NamespaceLifecycle' should be enabled  
](https://docs.datadoghq.com/security/default_rules/api_server_admission_controller_namespacelifecycle_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes admission controller 'NodeRestriction' should be enabled  
](https://docs.datadoghq.com/security/default_rules/api_server_admission_controller_noderestriction_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server request timeout should not exceed 60 seconds  
](https://docs.datadoghq.com/security/default_rules/api_server_request_timeout_exceeds_60_seconds_only_if_required/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server secure port should be enabled  
](https://docs.datadoghq.com/security/default_rules/api_server_secure_port_enabled/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API Server should enable audit logs on its server  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.22/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server should only allow explicitly authorized requests  
](https://docs.datadoghq.com/security/default_rules/api_server_only_allows_explicitly_authorized_requests/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server should use a service account public key file for
service accounts  
](https://docs.datadoghq.com/security/default_rules/api_server_uses_service_account_public_key_file_service_accounts/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server should use secure authentication methods and avoid
using token-based authentication  
](https://docs.datadoghq.com/security/default_rules/api_server_uses_secure_authentication_methods/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server should use TLS certificate client authentication  
](https://docs.datadoghq.com/security/default_rules/api_server_uses_tls_certificate_client_authentication/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes API server should validate that the service account token
exists in etcd  
](https://docs.datadoghq.com/security/default_rules/api_server_validates_service_account_token_exists_in_etcd/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes PKI directories should be owned by root  
](https://docs.datadoghq.com/security/default_rules/kubernetes_pki_directory_owned_by_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The Kubernetes PKI directory should be owned by root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.19/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The misconfigured resource should retain at least 10 log file rotations  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.24/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The ownership of the admin.conf file should be root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.14/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The proxy kubeconfig file should have permissions of 644 or stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.1.3/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The read-only port should be disabled in Kubelet  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-4.2.4/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler API service should not be bound to non-loopback insecure
addresses  
](https://docs.datadoghq.com/security/default_rules/scheduler_api_service_bound_to_localhost/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler configuration file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/scheduler_configuration_file_ownership_assigned_to_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler configuration file should only be alterable by owners  
](https://docs.datadoghq.com/security/default_rules/scheduler_configuration_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler pod specification file ownership should be assigned to root  
](https://docs.datadoghq.com/security/default_rules/pod_specification_scheduler_file_ownership_assigned_to_root/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler pod specification file ownership should be set to root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler pod specification file should have permissions of 600 or more
restrictive  
](https://docs.datadoghq.com/security/default_rules/pod_specification_scheduler_file_permissions/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler pod specification file should have permissions of 644 or
stricter  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.5/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler service should only be bound to localhost  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.4.2/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The scheduler.conf file should be owned by root:root  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.1.16/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
The secure port should not be disabled for the API server  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-1.2.20/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
TLS connections between etcd peers should not use self-signed certificates  
](https://docs.datadoghq.com/security/default_rules/cis-
kubernetes-1.5.1-2.6/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
TLS connections between etcd peers should not use self-signed certificates
that are automatically generated  
](https://docs.datadoghq.com/security/default_rules/etcd_prevent_self_signed_certificates_tls_connections_between_peers/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
User Attached to a Pod  
](https://docs.datadoghq.com/security/default_rules/kubernetes-user-attached-
to-
pod/)[![kubernetes](https://static.datadoghq.com/static/images/logos/kubernetes_avatar.svg)
User Exec into a Pod  
](https://docs.datadoghq.com/security/default_rules/kubernetes-user-exec-to-
pod/)

![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg)

Lambda ____

>

[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Lambda function should have access to VPC resources in
configuration  
](https://docs.datadoghq.com/security/default_rules/aws-lambda-function-
lambda-function-should-have-access-to-vpc-resources-in-
configuration/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Lambda function should not be accessible over the public
internet  
](https://docs.datadoghq.com/security/default_rules/aws-lambda-function-
lambda-function-should-not-be-accessible-over-the-public-
internet/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Lambda function should use the latest runtime environment
version  
](https://docs.datadoghq.com/security/default_rules/aws-lambda-function-
lambda-function-should-use-the-latest-runtime-environment-
version/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Lambda functions should not be configured with a privileged
execution role  
](https://docs.datadoghq.com/security/default_rules/aws-lambda-function-
lambda-functions-should-not-be-configured-with-a-privileged-execution-
role/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Publicly accessible Lambda function uses a privileged IAM
role  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-lambda-
public-privileged-role-
public/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) Publicly accessible Lambda function with a critical
vulnerability uses a privileged IAM role  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-lambda-
privileged-public-critical-
vuln/)[![lambda](https://static.datadoghq.com/static/images/logos/amazon-
lambda_avatar.svg) VPC Lambda functions should operate in multiple
Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-lambda-function-vpc-
lambda-functions-should-operate-in-multiple-availability-zones/)

![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)

Lastpass ____

>

[![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)
LastPass activity from a potentially malicious IP address  
](https://docs.datadoghq.com/security/default_rules/lastpass-activity-from-
suspicious-
ip/)[![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)
LastPass activity from a Tor client IP address  
](https://docs.datadoghq.com/security/default_rules/lastpass-activity-from-
tor-client-
ip/)[![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)
LastPass brute force attempt  
](https://docs.datadoghq.com/security/default_rules/lastpass-brute-force-
attempt/)[![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)
LastPass user impossible travel detected  
](https://docs.datadoghq.com/security/default_rules/lastpass-user-impossible-
travel/)[![lastpass](https://static.datadoghq.com/static/images/logos/lastpass_avatar.svg)
LastPass vault content export attempt  
](https://docs.datadoghq.com/security/default_rules/lastpass-vault-content-
export-attempt/)

![meraki](https://static.datadoghq.com/static/images/logos/meraki_avatar.svg)

Meraki ____

>

[![meraki](https://static.datadoghq.com/static/images/logos/meraki_avatar.svg)
Cisco Meraki organization appliance security IDS events  
](https://docs.datadoghq.com/security/default_rules/3rd-party-alert-meraki-
ids/)

![microsoft-365](https://static.datadoghq.com/static/images/logos/active-
directory_avatar.svg)

Microsoft 365 ____

>

[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-
teams_avatar.svg) A Microsoft Teams member was made owner of multiple teams  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-teams-
member-made-owner-of-multiple-
teams/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
A new Microsoft 365 application was installed  
](https://docs.datadoghq.com/security/default_rules/m365-new-app-
observed/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-
teams_avatar.svg) A new Microsoft Teams app or bot was observed  
](https://docs.datadoghq.com/security/default_rules/m365-teams-new-app-or-bot-
observed/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-
teams_avatar.svg) A potentially malicious file was sent in a Microsoft Teams
message  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-potentially-
malicious-link-in-
chat/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/exchange-
server_avatar.svg) Abnormal successful Microsoft 365 Exchange login event  
](https://docs.datadoghq.com/security/default_rules/m365-exchange-logins-
impossible-
travel/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-
teams_avatar.svg) An external Microsoft Teams member was added then removed  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-teams-
member-added-then-
removed/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Consent given to application associated with business email compromise attacks
in Microsoft 365  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-consent-to-
known-bec-
application/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/exchange-
server_avatar.svg) Exchange Online mail forwarding rule enabled  
](https://docs.datadoghq.com/security/default_rules/m365-mail-forwarding-rule-
enabled/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/exchange-
server_avatar.svg) Microsoft 365 Anomalous Amount of Deleted Emails  
](https://docs.datadoghq.com/security/default_rules/m365-large-amount-of-
deleted-
emails/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Anomalous Amount of Downloaded files  
](https://docs.datadoghq.com/security/default_rules/m365-anomalous-amount-of-
downloaded-
files/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Default or Anonymous user permissions added to mailbox folder  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-additional-
email-delegate-permissions-assign-default-
anonymous/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 eDiscovery content search started  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-ediscovery-
searchstarted/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 eDiscovery search export downloaded  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-ediscovery-
searchexportdownloaded/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Exchange inbox rule name associated with business email
compromise attacks  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-inbox-rule-
name-
iocs/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Exchange inbox rule set up to automatically forward email  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-inbox-
rules/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Exchange inbox rule set up to hide email  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-inbox-rules-
hide-
activity/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Exchange junk email settings modified by a suspicious VPN  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-junk-mail-
configuration-
evasion/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Exchange transport rule set up to automatically forward email  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-exchange-
transport-rule-
exfiltration/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Full Access delegate permissions added  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-additional-
email-delegate-permissions-full-
access/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Inbound Connector added or modified  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-inbound-
connector/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 mailbox audit logging bypass  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-mailbox-
auditlog-
bypass/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/onedrive_avatar.svg)
Microsoft 365 OneDrive anonymous link created  
](https://docs.datadoghq.com/security/default_rules/m365-onedrive-
anonymouslink/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Security and Compliance  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-security-
compliance-
alerts/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 SendAs permissions added  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-additional-
email-delegate-permissions-
sendas/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/sharepoint_avatar.svg)
Microsoft 365 SharePoint object shared with guest  
](https://docs.datadoghq.com/security/default_rules/m365-sharepoint-shared-
file-with-
guest/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-365_avatar.svg)
Microsoft 365 Unified Audit Logging Disabled  
](https://docs.datadoghq.com/security/default_rules/m365-admin-audit-log-
disabled/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/microsoft-
teams_avatar.svg) Multiple Microsoft Teams deleted  
](https://docs.datadoghq.com/security/default_rules/microsoft-365-multiple-
teams-deleted-by-
user/)[![microsoft-365](https://static.datadoghq.com/static/images/logos/active-
directory_avatar.svg) Unusual Authentication by Microsoft 365 Azure AD Service
Principal  
](https://docs.datadoghq.com/security/default_rules/m365-azure-ad-unusual-
service-principal-login/)

![microsoft-defender-for-
cloud](https://static.datadoghq.com/static/images/logos/microsoft-defender-
for-cloud_avatar.svg)

Microsoft Defender For Cloud ____

>

[![microsoft-defender-for-
cloud](https://static.datadoghq.com/static/images/logos/microsoft-defender-
for-cloud_avatar.svg) Microsoft Defender for Cloud  
](https://docs.datadoghq.com/security/default_rules/microsoft-defender-for-
cloud/)

![microsoft-graph](https://static.datadoghq.com/static/images/logos/microsoft-
graph_avatar.svg)

Microsoft Graph ____

>

[![microsoft-
graph](https://static.datadoghq.com/static/images/logos/microsoft-
graph_avatar.svg) BETA Microsoft graph security alerts  
](https://docs.datadoghq.com/security/default_rules/microsoft-graph-security-
alerts/)

![mimecast](https://static.datadoghq.com/static/images/logos/mimecast_avatar.svg)

Mimecast ____

>

[![mimecast](https://static.datadoghq.com/static/images/logos/mimecast_avatar.svg)
BETA Mimecast Alert: email contains malicious file  
](https://docs.datadoghq.com/security/default_rules/mimecast-mimecast-alert-
email-contains-malicious-
file/)[![mimecast](https://static.datadoghq.com/static/images/logos/mimecast_avatar.svg)
BETA Mimecast Alert: malicious URL clicked by user  
](https://docs.datadoghq.com/security/default_rules/mimecast-mimecast-alert-
malicious-url-clicked-by-
user/)[![mimecast](https://static.datadoghq.com/static/images/logos/mimecast_avatar.svg)
BETA Mimecast Alert: phishing email detected  
](https://docs.datadoghq.com/security/default_rules/mimecast-mimecast-alert-
phishing-email-
detected/)[![mimecast](https://static.datadoghq.com/static/images/logos/mimecast_avatar.svg)
BETA Mimecast Alert: user responded to impersonation message  
](https://docs.datadoghq.com/security/default_rules/mimecast-mimecast-alert-
user-responded-to-impersonation-message/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Multi Log Sources ____

>

[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BETA Activity observed from
malicious IP  
](https://docs.datadoghq.com/security/default_rules/activity-from-malicious-
ip/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BETA Activity observed to a
malicious domain  
](https://docs.datadoghq.com/security/default_rules/activity-to-malicious-
domain/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Base64 was detected in an
http.user_agent or http.referrer  
](https://docs.datadoghq.com/security/default_rules/cve-2021-44228-log4j-base64-detected/)[![multi
log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BETA Brute force attempt
from suspicious IP by user email  
](https://docs.datadoghq.com/security/default_rules/brute-force-activity-from-
suspicious-ip-by-user-email/)[![multi log sources](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
BETA Cloud provider activity observed from IP associated with cryptomining  
](https://docs.datadoghq.com/security/default_rules/cryptomining-ip-address-
observed/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Credential stuffing attack  
](https://docs.datadoghq.com/security/default_rules/credential-stuffing-
attack/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Log4j Scanner detected in
user agent or referrer  
](https://docs.datadoghq.com/security/default_rules/cve-2021-44228-log4j-scanning-
detected/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Log4Shell Scanning Detected  
](https://docs.datadoghq.com/security/default_rules/log4shell-malicious-
payload/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) BETA Login activity observed
from Tor client IP  
](https://docs.datadoghq.com/security/default_rules/login-activity-from-tor-
ip/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Potential cryptomining
detected through IP callback  
](https://docs.datadoghq.com/security/default_rules/hardcoded-cryptomining-
detection/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Scout Suite user agent
observed  
](https://docs.datadoghq.com/security/default_rules/scoutsuite-useragent-
observed/)[![multi log sources](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Spring RCE post-exploitation
activity attempted  
](https://docs.datadoghq.com/security/default_rules/spring-rce-http-get-
request-successful/)[![multi log sources](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
User agent associated with penetration testing tool observed  
](https://docs.datadoghq.com/security/default_rules/cloud-offensive-useragent-
observed/)

![mysql](https://static.datadoghq.com/static/images/logos/mysql_avatar.svg)

Mysql ____

>

[![mysql](https://static.datadoghq.com/static/images/logos/mysql_avatar.svg)
Malicious IP connected to MySQL database  
](https://docs.datadoghq.com/security/default_rules/mysql-malicious-ip/)

![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg)

Neptune ____

>

[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB cluster snapshots should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
snapshot-neptune-db-cluster-snapshots-should-be-encrypted-at-
rest/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB cluster snapshots should not be public  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
snapshot-neptune-db-cluster-snapshots-should-not-be-
public/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should be configured to copy tags to
snapshots  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-be-configured-to-copy-tags-to-
snapshots/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should be deployed across multiple
Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-be-deployed-across-multiple-availability-
zones/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-be-encrypted-at-
rest/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should have automated backups enabled  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-have-automated-backups-
enabled/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should have deletion protection
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-have-deletion-protection-
enabled/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should have IAM database
authentication enabled  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-have-iam-database-authentication-
enabled/)[![neptune](https://static.datadoghq.com/static/images/logos/amazon-
neptune_avatar.svg) Neptune DB clusters should publish audit logs to
CloudWatch Logs  
](https://docs.datadoghq.com/security/default_rules/aws-neptune-cluster-
neptune-db-clusters-should-publish-audit-logs-to-cloudwatch-logs/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Networkfirewall ____

>

[![networkfirewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network Firewall firewalls
should have deletion protection enabled  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-
firewall-network-firewall-firewalls-should-have-deletion-protection-
enabled/)[![networkfirewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network Firewall logging
should be enabled  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-
firewall-network-firewall-logging-should-be-
enabled/)[![networkfirewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network Firewall policies
should have at least one associated rule group  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-
firewall-network-firewall-policies-should-have-at-least-one-associated-rule-
group/)[![networkfirewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Network Firewall policy
default stateless action for fragmented packets should be drop or forward  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-
firewall-network-firewall-policy-default-stateless-action-for-fragmented-
packets-should-be-drop-or-forward/)[![networkfirewall](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Network Firewall policy default stateless action for full packets should be
drop or forward  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-
firewall-network-firewall-policy-default-stateless-action-for-full-packets-
should-be-drop-or-forward/)[![networkfirewall](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Network Firewall stateless rule groups should not be empty  
](https://docs.datadoghq.com/security/default_rules/aws-network-firewall-rule-
group-network-firewall-stateless-rule-groups-should-not-be-empty/)

![nginx](https://static.datadoghq.com/static/images/logos/nginx_avatar.svg)

Nginx ____

>

[![nginx](https://static.datadoghq.com/static/images/logos/nginx_avatar.svg)
NGINX HTTP requests from security scanner  
](https://docs.datadoghq.com/security/default_rules/nginx-scanner-detected/)

![nginx-ingress-
controller](https://static.datadoghq.com/static/images/logos/nginx-ingress-
controller_avatar.svg)

Nginx Ingress Controller ____

>

[![nginx-ingress-
controller](https://static.datadoghq.com/static/images/logos/nginx-ingress-
controller_avatar.svg) NGINX ingress controller HTTP requests from security
scanner  
](https://docs.datadoghq.com/security/default_rules/nginx-ingress-controller-
scanner-detected/)

![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)

Okta ____

>

[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Malicious authentication attempt detected by Okta ThreatInsight  
](https://docs.datadoghq.com/security/default_rules/okta-threat-
suspected/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Multiple Okta push notifications denied  
](https://docs.datadoghq.com/security/default_rules/okta-mfa-push-
fatigue/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta administrator role assigned to user  
](https://docs.datadoghq.com/security/default_rules/okta-admin-role-assigned-
to-
user/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta API Token Created or Enabled  
](https://docs.datadoghq.com/security/default_rules/okta-api-token-
created/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta application enumeration by user  
](https://docs.datadoghq.com/security/default_rules/okta-application-
enumeration/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta blocked numerous requests from a malicious IP  
](https://docs.datadoghq.com/security/default_rules/okta-blocked-security-
request/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta Identity Provider creation or modification  
](https://docs.datadoghq.com/security/default_rules/okta-idp-
modification/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta Impersonation  
](https://docs.datadoghq.com/security/default_rules/okta-impersonation-
metric/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta MFA Bypass Attempted  
](https://docs.datadoghq.com/security/default_rules/okta-mfa-
bypass/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta MFA reset for user  
](https://docs.datadoghq.com/security/default_rules/okta-mfa-factor-reset-
attempted/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta one-time refresh token reused  
](https://docs.datadoghq.com/security/default_rules/okta-one-time-refresh-
token-attempted-
reuse/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta phishing detection with FastPass origin check  
](https://docs.datadoghq.com/security/default_rules/okta-aitm-phishing-
detection-with-
fastpass/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta policy rule deleted  
](https://docs.datadoghq.com/security/default_rules/okta-policy-rule-deletion-
attempted/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
BETA Okta session hijacking  
](https://docs.datadoghq.com/security/default_rules/okta-session-
hijacking/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta User Access Denied to Sign On  
](https://docs.datadoghq.com/security/default_rules/okta-user-denied-access-
due-to-sign-in-
policy/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta User Attempted to Access Unauthorized App  
](https://docs.datadoghq.com/security/default_rules/okta-user-attempted-to-
access-unauthorized-
app/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta user reported suspicious activity  
](https://docs.datadoghq.com/security/default_rules/okta-user-suspicious-
activity-
reports/)[![okta](https://static.datadoghq.com/static/images/logos/okta_avatar.svg)
Okta user's MFA factors reset followed by access to the administrative console  
](https://docs.datadoghq.com/security/default_rules/okta-mfa-factor-reset-
then-access-admin-console/)

![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)

Onelogin ____

>

[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin administrator assumed a user  
](https://docs.datadoghq.com/security/default_rules/onelogin-admin-assumed-
user/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin API activity from malicious IP address  
](https://docs.datadoghq.com/security/default_rules/onelogin-api-activity-
malicious-
ip/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin API Token Created  
](https://docs.datadoghq.com/security/default_rules/onelogin-api-token-
created/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/onelogin-brute-force-
attack/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin user granted administrative privileges  
](https://docs.datadoghq.com/security/default_rules/onelogin-user-granted-
admin-
privileges/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin user locked out  
](https://docs.datadoghq.com/security/default_rules/onelogin-user-locked-
out/)[![onelogin](https://static.datadoghq.com/static/images/logos/onelogin_avatar.svg)
OneLogin user viewed secure note  
](https://docs.datadoghq.com/security/default_rules/onelogin-user-viewed-
secure-note/)

![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)

Opensearch ____

>

[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domain connections should be encrypted using the latest TLS
security policy  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domain-connections-should-be-encrypted-using-the-latest-tls-
security-
policy/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should be deployed within a VPC  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-be-deployed-within-a-
vpc/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should encrypt data sent between nodes  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-encrypt-data-sent-between-
nodes/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have at least three data nodes  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-at-least-three-data-
nodes/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have Audit Logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-audit-logging-
enabled/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have encryption at rest enabled  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-encryption-at-rest-
enabled/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have Error Logging enabled  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-error-logging-
enabled/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have fine-grained access control enabled  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-fine-grained-access-control-
enabled/)[![opensearch](https://static.datadoghq.com/static/images/logos/opensearch_avatar.svg)
OpenSearch domains should have the latest software update installed  
](https://docs.datadoghq.com/security/default_rules/aws-opensearch-domain-
opensearch-domains-should-have-the-latest-software-update-installed/)

![ossec-security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg)

Ossec Security ____

>

[![ossec-security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: Attack detected  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-attack-detected/)[![ossec-
security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: Multiple authentication failures  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-multiple-authentication-failures/)[![ossec-
security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: Multiple authentication failures
followed by a success  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-multiple-authentication-failures-followed-by-a-success/)[![ossec-
security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: OSSEC agent disconnected  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-ossec-agent-disconnected/)[![ossec-
security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: Possible attack detected  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-possibly-an-attack-detected/)[![ossec-
security](https://static.datadoghq.com/static/images/logos/ossec-
security_avatar.svg) BETA OSSEC Alert: Unusual spike in authentication failure  
](https://docs.datadoghq.com/security/default_rules/ossec-security-ossec-
alert-unusual-spike-in-authentication-failure/)

![palo-alto-cortex-xdr](https://static.datadoghq.com/static/images/logos/palo-
alto-cortex-xdr_avatar.svg)

Palo Alto Cortex Xdr ____

>

[![palo-alto-cortex-
xdr](https://static.datadoghq.com/static/images/logos/palo-alto-cortex-
xdr_avatar.svg) BETA Palo Alto Cortex XDR malware alert detected on multiple
hosts  
](https://docs.datadoghq.com/security/default_rules/palo-alto-cortex-xdr-palo-
alto-cortex-xdr-similar-alert-detected-across-multiple-hosts/)[![palo-alto-
cortex-xdr](https://static.datadoghq.com/static/images/logos/palo-alto-cortex-
xdr_avatar.svg) BETA Palo Alto Cortex XDR: New incident detected  
](https://docs.datadoghq.com/security/default_rules/palo-alto-cortex-xdr-palo-
alto-cortex-xdr-new-incident-detected/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Pan.firewall ____

>

[![pan.firewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Palo Alto Networks Firewall
- command and control traffic observed  
](https://docs.datadoghq.com/security/default_rules/pan-firewall-c2-traffic-
observed/)[![pan.firewall](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Palo Alto Networks Firewall
- crypto mining activity observed  
](https://docs.datadoghq.com/security/default_rules/pan-firewall-cryptomining-
activity-observed/)

![ping-federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg)

Ping Federate ____

>

[![ping-federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Admin Alert: impossible travel by user  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-admin-alert-impossible-travel-by-user/)[![ping-
federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Admin Alert: multiple failed login
attempts in a short time period  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-admin-alert-multiple-failed-login-attempts-in-a-short-time-
period/)[![ping-
federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Admin Alert: multiple login attempts by
locked account in a short time period  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-admin-alert-multiple-login-attempts-by-locked-account-in-a-short-
time-period/)[![ping-
federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Audit Alert: multiple failed
authentication attempts in a short time period  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-audit-alert-multiple-failed-authentication-attempts-in-a-short-
time-period/)[![ping-
federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Audit Alert: multiple failed slo login
attempts in a short time period  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-audit-alert-multiple-failed-slo-login-attempts-in-a-short-time-
period/)[![ping-
federate](https://static.datadoghq.com/static/images/logos/ping-
federate_avatar.svg) BETA PingFederate Audit Alert: multiple failed sso login
attempts in a short time period  
](https://docs.datadoghq.com/security/default_rules/ping-federate-
pingfederate-audit-alert-multiple-failed-sso-login-attempts-in-a-short-time-
period/)

![ping-one](https://static.datadoghq.com/static/images/logos/ping-
one_avatar.svg)

Ping One ____

>

[![ping-one](https://static.datadoghq.com/static/images/logos/ping-
one_avatar.svg) BETA PingOne device locked out after too many failed attempts  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
device-locked-out-after-too-many-failed-attempts/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne impossible travel authentication attempt  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
impossible-travel-authentication-attempt/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne impossible travel authentication attempts by OTP  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
impossible-travel-authentication-attempts-by-otp/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne multiple authentication assertions failed by FIDO device  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
multiple-authentication-assertion-failed-by-fido-device/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne multiple failed authentication attempts  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
multiple-failed-authentication-attempts/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne multiple failed authentication attempts by OTP  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
multiple-failed-authentication-attempts-by-otp/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne multiple Kerberos check failed attempts  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
multiple-kerberos-check-failed-attempts/)[![ping-
one](https://static.datadoghq.com/static/images/logos/ping-one_avatar.svg)
BETA PingOne user locked after too many failed attempts  
](https://docs.datadoghq.com/security/default_rules/ping-one-pingone-alert-
user-locked-after-too-many-failed-attempts/)

![postgresql](https://static.datadoghq.com/static/images/logos/postgres_avatar.svg)

Postgresql ____

>

[![postgresql](https://static.datadoghq.com/static/images/logos/postgres_avatar.svg)
Malicious IP connected to PostgreSQL database  
](https://docs.datadoghq.com/security/default_rules/postgresql-malicious-ip/)

![rds](https://static.datadoghq.com/static/images/logos/amazon-rds_avatar.svg)

RDS ____

>

[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Aurora clusters should have backtracking enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-aurora-
clusters-should-have-backtracking-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Aurora MySQL clusters should publish audit logs to CloudWatch
Logs  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-aurora-
mysql-clusters-should-publish-audit-logs-to-cloudwatch-
logs/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Neptune cluster replicates to a publicly accessible Neptune
instance  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-neptune-
neptune-public-
neptune/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Publicly accessible RDS database stores sensitive data  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-public-rds-
instance-
sensitive/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) Publicly Accessible RDS instance uses a common master database
username  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-rds-public-
common/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS cluster and instance snapshots should be encrypted at rest  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-snapshot-
rds-cluster-and-instance-snapshots-should-be-encrypted-at-
rest/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS cluster exports snapshots to publicly accessible S3 bucket  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-rds-private-
rds-instance-exports-
public-s3/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS cluster replicates to a publicly accessible RDS instance  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-rds-private-
rds-public-
rds/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should be configured to copy tags to snapshots  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-be-configured-to-copy-tags-to-
snapshots/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should be configured to use a custom
administrator name  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-be-configured-to-use-a-custom-administrator-
name/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should be configured to use multiple Availability
Zones  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-be-configured-to-use-multiple-availability-
zones/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should have Auto Minor Version Upgrade enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-have-auto-minor-version-upgrade-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should have deletion protection enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-have-deletion-protection-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should have encryption at rest enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-have-encryption-at-rest-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS clusters should have IAM authentication enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-cluster-rds-
clusters-should-have-iam-authentication-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS databases should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
databases-should-be-
encrypted/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS databases should have 'Auto Minor Version Upgrade' enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
databases-should-have-auto-minor-version-upgrade-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS databases should not be publicly accessible  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
databases-should-not-be-publicly-
accessible/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS event subscriptions should be configured to notify for
critical database parameter group events  
](https://docs.datadoghq.com/security/default_rules/aws-rds-event-
subscription-rds-event-subscriptions-should-be-configured-to-notify-for-
critical-database-parameter-group-
events/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS event subscriptions should be configured to notify for
critical database security group events  
](https://docs.datadoghq.com/security/default_rules/aws-rds-event-
subscription-rds-event-subscriptions-should-be-configured-to-notify-for-
critical-database-security-group-
events/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS event subscriptions should be configured to notify for
critical events  
](https://docs.datadoghq.com/security/default_rules/aws-rds-event-
subscription-rds-event-subscriptions-should-be-configured-to-notify-for-
critical-
events/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instance snapshots should not be publicly shared  
](https://docs.datadoghq.com/security/default_rules/aws-rds-db-snapshot-rds-
instance-snapshots-should-not-be-publicly-
shared/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should be configured to copy tags to snapshots  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-be-configured-to-copy-tags-to-
snapshots/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should be configured to use a custom
administrator name  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-be-configured-to-use-a-custom-administrator-
name/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should be configured to use Enhanced Monitoring  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-be-configured-to-use-enhanced-
monitoring/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should be configured to use multiple
Availability Zones  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-be-configured-to-use-multiple-availability-
zones/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should be deployed inside of a VPC  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-be-deployed-inside-of-a-
vpc/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should have automatic backups enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-have-automatic-backups-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should have deletion protection enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-have-deletion-protection-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should have IAM authentication enabled  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-have-iam-authentication-
enabled/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should publish logs to CloudWatch Logs  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-publish-logs-to-cloudwatch-
logs/)[![rds](https://static.datadoghq.com/static/images/logos/amazon-
rds_avatar.svg) RDS instances should use a non-default port  
](https://docs.datadoghq.com/security/default_rules/aws-rds-instance-rds-
instances-should-use-a-non-default-port/)

![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg)

Redshift ____

>

[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Logging for Redshift clusters should be enabled  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
logging-for-redshift-clusters-should-be-
enabled/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should be encrypted  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-be-
encrypted/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should enable SSL/TLS for client
connections  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-enable-ssl-tls-for-client-
connections/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should enforce encryption in transit  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-enforce-encryption-in-
transit/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should have 'allow version upgrade'
enabled  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-have-allow-version-upgrade-
enabled/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should have automatic snapshots enabled  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-have-automatic-snapshots-
enabled/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should not be publicly accessible  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-not-be-publicly-
accessible/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should not use the default database
name  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-not-use-the-default-database-
name/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should use a custom master username  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-use-a-custom-master-
username/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should use a non-default port for
communication  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-use-a-non-default-port-for-
communication/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should use enhanced VPC routing  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-use-enhanced-vpc-
routing/)[![redshift](https://static.datadoghq.com/static/images/logos/amazon-
redshift_avatar.svg) Redshift clusters should use the EC2-VPC platform for
better security  
](https://docs.datadoghq.com/security/default_rules/aws-redshift-cluster-
redshift-clusters-should-use-the-ec2-vpc-platform-for-better-security/)

![route53](https://static.datadoghq.com/static/images/logos/amazon-
route-53_avatar.svg)

Route53 ____

>

[![route53](https://static.datadoghq.com/static/images/logos/amazon-
route-53_avatar.svg) Route 53 public hosted zones should log DNS queries  
](https://docs.datadoghq.com/security/default_rules/aws-route53-hosted-zone-
route-53-public-hosted-zones-should-log-dns-queries/)

![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)

S3 ____

>

[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
Default encryption should be enabled on S3 buckets  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-default-
encryption-should-be-enabled-
on-s3-buckets/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
Publicly accessible S3 bucket stores sensitive data  
](https://docs.datadoghq.com/security/default_rules/sec-issue-aws-
public-s3-sensitive/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket ACLs should be restricted from public view  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-acl-
viewable-
public/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket ACLs should block public write actions  
](https://docs.datadoghq.com/security/default_rules/aws-s3-publicaccesscontrols/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket contents should only be accessible by authorized principals  
](https://docs.datadoghq.com/security/default_rules/aws-s3-publicpolicy/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket objects should not allow public listing via ACL  
](https://docs.datadoghq.com/security/default_rules/aws-s3-publicpermissions/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket policies should restrict access from other AWS accounts  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-bucket-
policies-should-restrict-access-from-other-aws-
accounts/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket policy should deny HTTP requests  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-bucket-
policy-should-deny-http-
requests/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 bucket policy should prevent public write access  
](https://docs.datadoghq.com/security/default_rules/aws-s3-public-policy-
write/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 buckets should have 'Block Public Access' enabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-buckets-
should-have-block-public-access-
enabled/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 buckets should have 'MFA Delete' enabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-buckets-
should-have-mfa-delete-
enabled/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 buckets should have versioning enabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-versioning/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 general purpose buckets should have a lifecycle configuration  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-general-
purpose-buckets-should-have-a-lifecycle-
configuration/)[![s3](https://static.datadoghq.com/static/images/logos/amazon-s3_avatar.svg)
S3 general purpose buckets should have static website hosting disabled  
](https://docs.datadoghq.com/security/default_rules/aws-s3-bucket-s3-general-
purpose-buckets-should-have-static-website-hosting-disabled/)

![sagemaker](https://static.datadoghq.com/static/images/logos/amazon-
sagemaker_avatar.svg)

Sagemaker ____

>

[![sagemaker](https://static.datadoghq.com/static/images/logos/amazon-
sagemaker_avatar.svg) SageMaker notebook instances should be launched in a
custom VPC  
](https://docs.datadoghq.com/security/default_rules/aws-sagemaker-notebook-
instance-sagemaker-notebook-instances-should-be-launched-in-a-custom-
vpc/)[![sagemaker](https://static.datadoghq.com/static/images/logos/amazon-
sagemaker_avatar.svg) SageMaker notebook instances should not grant users root
access  
](https://docs.datadoghq.com/security/default_rules/aws-sagemaker-notebook-
instance-sagemaker-notebook-instances-should-not-grant-users-root-
access/)[![sagemaker](https://static.datadoghq.com/static/images/logos/amazon-
sagemaker_avatar.svg) SageMaker notebook instances should not have direct
internet access  
](https://docs.datadoghq.com/security/default_rules/aws-sagemaker-notebook-
instance-sagemaker-notebook-instances-should-not-have-direct-internet-access/)

![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)

Salesforce ____

>

[![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)
Anomalous amount of Salesforce query results  
](https://docs.datadoghq.com/security/default_rules/salesforce-large-volume-
of-query-
activity/)[![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)
Anomalous amount of Salesforce records deleted  
](https://docs.datadoghq.com/security/default_rules/salesforce-anomalous-
amount-of-records-
deleted/)[![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)
Credential stuffing attack on Salesforce  
](https://docs.datadoghq.com/security/default_rules/salesforce-credential-
stuffing/)[![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)
Salesforce Brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/salesforce-brute-force-
attack/)[![salesforce](https://static.datadoghq.com/static/images/logos/salesforce_avatar.svg)
Salesforce login from disabled account  
](https://docs.datadoghq.com/security/default_rules/salesforce-login-from-
disabled-account/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Secretsmanager ____

>

[![secretsmanager](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Remove unused Secrets
Manager secrets  
](https://docs.datadoghq.com/security/default_rules/aws-secretsmanager-secret-
remove-unused-secrets-manager-secrets/)[![secretsmanager](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Secrets Manager secrets configured with automatic rotation should rotate
successfully  
](https://docs.datadoghq.com/security/default_rules/aws-secretsmanager-secret-
secrets-manager-secrets-configured-with-automatic-rotation-should-rotate-
successfully/)[![secretsmanager](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Secrets Manager secrets
should be rotated within 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-secretsmanager-secret-
secrets-manager-secrets-should-be-rotated-
within-90-days/)[![secretsmanager](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Secrets Manager secrets
should have automatic rotation enabled  
](https://docs.datadoghq.com/security/default_rules/aws-secretsmanager-secret-
secrets-manager-secrets-should-have-automatic-rotation-enabled/)

![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)

Sentinelone ____

>

[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
BETA Credential access via registry hive dumping  
](https://docs.datadoghq.com/security/default_rules/win-reg-credential-dump-
hives/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
BETA Process memory dumped using ProcDump  
](https://docs.datadoghq.com/security/default_rules/win-process-memory-dumped-
procdump/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
BETA Process memory dumped using the minidump function of comsvcs.dll  
](https://docs.datadoghq.com/security/default_rules/win-minidump-
usage/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
SentinelOne Alerts  
](https://docs.datadoghq.com/security/default_rules/sentinelone-alerts-third-
party/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
SentinelOne Threats  
](https://docs.datadoghq.com/security/default_rules/sentinelone-threats-third-
party/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
BETA Unusual ntdsutil usage  
](https://docs.datadoghq.com/security/default_rules/win-suspicious-ntdsutil-
usage/)[![sentinelone](https://static.datadoghq.com/static/images/logos/sentinelone_avatar.svg)
BETA Windows shadow copies deleted  
](https://docs.datadoghq.com/security/default_rules/win-vssadmin-delete-
shadows/)

![signal_sciences](https://static.datadoghq.com/static/images/logos/sigsci_avatar.svg)

Signal Sciences ____

>

[![signal_sciences](https://static.datadoghq.com/static/images/logos/sigsci_avatar.svg)
Signal Sciences flagged an IP  
](https://docs.datadoghq.com/security/default_rules/signalsciences-ip-
flagged/)

![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)

Slack ____

>

[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Microsoft Intune Enterprise MDM disabled for Slack  
](https://docs.datadoghq.com/security/default_rules/slack-intune-
disabled/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack anomaly event  
](https://docs.datadoghq.com/security/default_rules/slack-anomaly-
events/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack Brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/slack-brute-force-
attack/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack CLI login from suspicious IP address  
](https://docs.datadoghq.com/security/default_rules/slack-cli-login-
suspicious-
ip/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack data export download  
](https://docs.datadoghq.com/security/default_rules/slack-data-export-
download/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack data loss prevention rule modified  
](https://docs.datadoghq.com/security/default_rules/slack-dlp-rule-violation-
deactivated-
deleted/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack enterprise organization created or deleted  
](https://docs.datadoghq.com/security/default_rules/slack-organization-
created-
deleted/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack IdP configuration changed  
](https://docs.datadoghq.com/security/default_rules/slack-idp-configuration-
change/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack malicious content detected in uploaded file  
](https://docs.datadoghq.com/security/default_rules/slack-malicious-content-
detected/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack manual export downloaded  
](https://docs.datadoghq.com/security/default_rules/slack-manual-export-
downloaded/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack private channel converted to public  
](https://docs.datadoghq.com/security/default_rules/slack-private-channel-
converted-to-
public/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack SSO setting changed  
](https://docs.datadoghq.com/security/default_rules/slack-sso-settings-
changed/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack two factor authentication requirement changed  
](https://docs.datadoghq.com/security/default_rules/slack-two-factor-auth-
changed/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack user logout due to suspicious activity  
](https://docs.datadoghq.com/security/default_rules/slack-user-logout-
compromised/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Slack user role elevated to administrative privileges  
](https://docs.datadoghq.com/security/default_rules/slack-role-changed-to-
admin-or-
owner/)[![slack](https://static.datadoghq.com/static/images/logos/slack_avatar.svg)
Tor client IP address identified in Slack  
](https://docs.datadoghq.com/security/default_rules/slack-tor-ip-caller/)

![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)

Snowflake ____

>

[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake abnormal usage of OAuth access token  
](https://docs.datadoghq.com/security/default_rules/snowflake-abnormal-usage-
oauth-
token/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake anomalous querying of data by user  
](https://docs.datadoghq.com/security/default_rules/snowflake-anomalous-data-
querying-by-
user/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake Brute force attack on user  
](https://docs.datadoghq.com/security/default_rules/snowflake-brute-force-
attack/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake external access occurred  
](https://docs.datadoghq.com/security/default_rules/snowflake-external-access-
occurred/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake known malicious client application session  
](https://docs.datadoghq.com/security/default_rules/snowflake-sessions-known-
malicious-
clients/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake login from anomalous location  
](https://docs.datadoghq.com/security/default_rules/snowflake-login-from-
abnormal-
country/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake network policy modified  
](https://docs.datadoghq.com/security/default_rules/snowflake-network-policy-
modified/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake new client application sessions  
](https://docs.datadoghq.com/security/default_rules/snowflake-sessions-
anomalous-client-
applications/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake new data transfer to location  
](https://docs.datadoghq.com/security/default_rules/snowflake-data-transfer-
external-cloud-
provider/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake stage set to anomalous external cloud location  
](https://docs.datadoghq.com/security/default_rules/snowflake-stage-set-as-
external-cloud-
provider/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake UI login via password  
](https://docs.datadoghq.com/security/default_rules/snowflake-ui-login-via-
password/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake UI login via password from proxy or vpn  
](https://docs.datadoghq.com/security/default_rules/snowflake-ui-proxy-vpn-
login-via-
password/)[![snowflake](https://static.datadoghq.com/static/images/logos/snowflake_avatar.svg)
Snowflake user granted admin role  
](https://docs.datadoghq.com/security/default_rules/snowflake-grants-admin-to-
user/)

![sns](https://static.datadoghq.com/static/images/logos/amazon-sns_avatar.svg)

SNS ____

>

[![sns](https://static.datadoghq.com/static/images/logos/amazon-
sns_avatar.svg) SNS Topic should have access restrictions set for subscription  
](https://docs.datadoghq.com/security/default_rules/aws-sns-
subscription/)[![sns](https://static.datadoghq.com/static/images/logos/amazon-
sns_avatar.svg) SNS Topic should have restrictions set for publishing  
](https://docs.datadoghq.com/security/default_rules/aws-sns-
publishing/)[![sns](https://static.datadoghq.com/static/images/logos/amazon-
sns_avatar.svg) SNS Topic should have server-side encryption enabled  
](https://docs.datadoghq.com/security/default_rules/aws-sns-
encryption/)[![sns](https://static.datadoghq.com/static/images/logos/amazon-
sns_avatar.svg) SNS topic should not be accessible over the public internet  
](https://docs.datadoghq.com/security/default_rules/aws-sns-public/)

![sophos-central-
cloud](https://static.datadoghq.com/static/images/logos/sophos-central-
cloud_avatar.svg)

Sophos Central Cloud ____

>

[![sophos-central-
cloud](https://static.datadoghq.com/static/images/logos/sophos-central-
cloud_avatar.svg) BETA Sophos Alert: Core clean up failed  
](https://docs.datadoghq.com/security/default_rules/sophos-sophos-alert-core-
clean-up-failed/)[![sophos-central-
cloud](https://static.datadoghq.com/static/images/logos/sophos-central-
cloud_avatar.svg) BETA Sophos Central Cloud alert  
](https://docs.datadoghq.com/security/default_rules/sophos-sophos-alert/)

![sqs](https://static.datadoghq.com/static/images/logos/amazon-sqs_avatar.svg)

SQS ____

>

[![sqs](https://static.datadoghq.com/static/images/logos/amazon-
sqs_avatar.svg) SQS queue should have server-side encryption  
](https://docs.datadoghq.com/security/default_rules/aws-sqs-queue-sqs-queue-
should-have-server-side-
encryption/)[![sqs](https://static.datadoghq.com/static/images/logos/amazon-
sqs_avatar.svg) SQS queue should not be accessible over the public internet  
](https://docs.datadoghq.com/security/default_rules/aws-sqs-queue-sqs-queue-
should-not-be-accessible-over-the-public-internet/)

![ssh](https://static.datadoghq.com/static/images/logos/ssh_avatar.svg)

SSH ____

>

[![ssh](https://static.datadoghq.com/static/images/logos/ssh_avatar.svg) IAM
SSH public keys should be rotated at least every 90 days  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-iam-ssh-
public-keys-should-be-rotated-at-least-
every-90-days/)[![ssh](https://static.datadoghq.com/static/images/logos/ssh_avatar.svg)
No more than one active SSH public key should be assigned to a single user  
](https://docs.datadoghq.com/security/default_rules/aws-iam-user-no-more-than-
one-active-ssh-public-key-should-be-assigned-to-a-single-user/)

![ssm](https://static.datadoghq.com/static/images/logos/amazon-ssm_avatar.svg)

SSM ____

>

[![ssm](https://static.datadoghq.com/static/images/logos/amazon-
ssm_avatar.svg) EC2 instances managed by SSM should have a compliant
association status  
](https://docs.datadoghq.com/security/default_rules/aws-ssm-instance-
ec2-instances-managed-by-ssm-should-have-a-compliant-association-
status/)[![ssm](https://static.datadoghq.com/static/images/logos/amazon-
ssm_avatar.svg) EC2 instances managed by SSM should have a compliant patch
status  
](https://docs.datadoghq.com/security/default_rules/aws-ssm-instance-
ec2-instances-managed-by-ssm-should-have-a-compliant-patch-
status/)[![ssm](https://static.datadoghq.com/static/images/logos/amazon-
ssm_avatar.svg) EC2 instances should be managed by SSM  
](https://docs.datadoghq.com/security/default_rules/aws-ec2-instance-
ec2-instances-should-be-managed-by-ssm/)

![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)

Suricata ____

>

[![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)
Suricata anomaly detected from source IP address  
](https://docs.datadoghq.com/security/default_rules/suricata-suricata-alert-
anomaly-of-type-anomaly-type-
detected/)[![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)
Suricata baseline deviation from expected IP requests  
](https://docs.datadoghq.com/security/default_rules/suricata-suricata-alert-
baseline-deviation-from-expected-ip-
requests/)[![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)
Suricata high number of bytes out detected  
](https://docs.datadoghq.com/security/default_rules/suricata-suricata-alert-
high-number-of-bytes-out-
detected/)[![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)
Suricata high number of requests detected from single IP address  
](https://docs.datadoghq.com/security/default_rules/suricata-suricata-alert-
high-number-of-requests-detected-from-single-ip-
address/)[![suricata](https://static.datadoghq.com/static/images/logos/suricata_avatar.svg)
Suricata possible ARP spoofing detected  
](https://docs.datadoghq.com/security/default_rules/suricata-suricata-alert-
possible-arp-spoofing-detected/)

![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)

Tailscale ____

>

[![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)
Tailscale API access token created  
](https://docs.datadoghq.com/security/default_rules/tailscale-api-access-
token-
created/)[![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)
Tailscale device approval configuration disabled  
](https://docs.datadoghq.com/security/default_rules/tailscale-device-approval-
configuration-
disabled/)[![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)
Tailscale security email modified  
](https://docs.datadoghq.com/security/default_rules/tailscale-security-email-
modified/)[![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)
Tailscale user approval configuration disabled  
](https://docs.datadoghq.com/security/default_rules/tailscale-user-approval-
configuration-
disabled/)[![tailscale](https://static.datadoghq.com/static/images/logos/tailscale_avatar.svg)
Tailscale user role updated  
](https://docs.datadoghq.com/security/default_rules/tailscale-user-role-
updated/)

![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg)

Trellix Endpoint Security ____

>

[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security blocked web control
violation detected  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-blocked-web-control-violation-
detected/)[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security suspicious call was
detected and blocked  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-suspicious-call-was-detected-and-
blocked/)[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security tampering with exploit
prevention has been detected  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-tampering-with-exploit-prevention-has-been-
detected/)[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security unauthorized escalation of
privilege was attempt detected  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-unauthorized-escalation-of-privilege-was-
attempt-detected/)[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security unrestricted access
protection rule violation detected  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-unrestricted-access-protection-rule-
violation-detected/)[![trellix-endpoint-
security](https://static.datadoghq.com/static/images/logos/trellix-endpoint-
security_avatar.svg) BETA Trellix Endpoint Security unrestricted port blocking
rule violation detected  
](https://docs.datadoghq.com/security/default_rules/trellix-one-endpoint-
security-trellix-endpoint-security-unrestricted-port-blocking-rule-violation-
detected/)

![trend-micro-email-
security](https://static.datadoghq.com/static/images/logos/trend-micro-email-
security_avatar.svg)

Trend Micro Email Security ____

>

[![trend-micro-email-
security](https://static.datadoghq.com/static/images/logos/trend-micro-email-
security_avatar.svg) BETA Trend Micro Email Security alert: High volume of
emails from sender  
](https://docs.datadoghq.com/security/default_rules/trend-micro-email-
security-trend-micro-email-security-alert-high-volume-of-emails-from-
sender/)[![trend-micro-email-
security](https://static.datadoghq.com/static/images/logos/trend-micro-email-
security_avatar.svg) BETA Trend Micro Email Security alert: High volume of
emails to recipient  
](https://docs.datadoghq.com/security/default_rules/trend-micro-email-
security-trend-micro-email-security-alert-high-volume-of-emails-to-
recipient/)[![trend-micro-email-
security](https://static.datadoghq.com/static/images/logos/trend-micro-email-
security_avatar.svg) BETA Trend Micro Email Security alert: Phishing email
detected  
](https://docs.datadoghq.com/security/default_rules/trend-micro-email-
security-trend-micro-email-security-alert-malicious-email-detected/)

![trend-micro-vision-one-endpoint-
security](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-endpoint-security_avatar.svg)

Trend Micro Vision One Endpoint Security ____

>

[![trend-micro-vision-one-endpoint-
security](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-endpoint-security_avatar.svg) BETA Trend Micro Vision One Endpoint
Security alert: Content violation detected  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
endpoint-security-trend-micro-vision-one-endpoint-security-alert-content-
violation-detected/)[![trend-micro-vision-one-endpoint-
security](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-endpoint-security_avatar.svg) BETA Trend Micro Vision One Endpoint
Security alert: Spyware or grayware detected  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
endpoint-security-trend-micro-vision-one-endpoint-security-alert-spyware-or-
grayware-detected/)[![trend-micro-vision-one-endpoint-
security](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-endpoint-security_avatar.svg) BETA Trend Micro Vision One Endpoint
Security alert: Suspicious file detected  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
endpoint-security-trend-micro-vision-one-endpoint-security-alert-suspicious-
file-detected/)[![trend-micro-vision-one-endpoint-
security](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-endpoint-security_avatar.svg) BETA Trend Micro Vision One Endpoint
Security alert: Virus or malware detected  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
endpoint-security-trend-micro-vision-one-endpoint-security-alert-virus-or-
malware-detected/)

![trend-micro-vision-one-
xdr](https://static.datadoghq.com/static/images/logos/trend-micro-vision-one-
xdr_avatar.svg)

Trend Micro Vision One Xdr ____

>

[![trend-micro-vision-one-
xdr](https://static.datadoghq.com/static/images/logos/trend-micro-vision-one-
xdr_avatar.svg) BETA Trend Micro Vision One XDR alert  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
xdr-trend-micro-vision-one-xdr-alert-detected-an-alert/)[![trend-micro-vision-
one-xdr](https://static.datadoghq.com/static/images/logos/trend-micro-vision-
one-xdr_avatar.svg) BETA Trend Micro Vision One XDR impossible travel detected
for identity activity  
](https://docs.datadoghq.com/security/default_rules/trend-micro-vision-one-
xdr-trend-micro-vision-one-xdr-alert-impossible-travel-detected-for-identity-
activity/)

![twilio](https://static.datadoghq.com/static/images/logos/twilio_avatar.svg)

Twilio ____

>

[![twilio](https://static.datadoghq.com/static/images/logos/twilio_avatar.svg)
Twilio account geographic permissions updated  
](https://docs.datadoghq.com/security/default_rules/twilio-credentials-geo-
perm-
updated/)[![twilio](https://static.datadoghq.com/static/images/logos/twilio_avatar.svg)
Twilio account token promoted  
](https://docs.datadoghq.com/security/default_rules/twilio-auth-token-
promoted/)[![twilio](https://static.datadoghq.com/static/images/logos/twilio_avatar.svg)
Twilio bulk export from unusual location  
](https://docs.datadoghq.com/security/default_rules/twilio-unusual-bulk-
export/)

![twistlock](https://static.datadoghq.com/static/images/logos/twistlock_avatar.svg)

Twistlock ____

>

[![twistlock](https://static.datadoghq.com/static/images/logos/twistlock_avatar.svg)
Container image vulnerability detected  
](https://docs.datadoghq.com/security/default_rules/twistlock-container-
vulnerability-
discovered/)[![twistlock](https://static.datadoghq.com/static/images/logos/twistlock_avatar.svg)
Container violated compliance standards  
](https://docs.datadoghq.com/security/default_rules/twistlock-container-
compliance-finding/)

![vault](https://static.datadoghq.com/static/images/logos/vault_avatar.svg)

Vault ____

>

[![vault](https://static.datadoghq.com/static/images/logos/vault_avatar.svg)
Vault root token  
](https://docs.datadoghq.com/security/default_rules/vault-root-token-usage-
detected/)

![vpc](https://static.datadoghq.com/static/images/logos/amazon-vpc_avatar.svg)

VPC ____

>

[![vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) Network ACLs should enforce inbound traffic restrictions  
](https://docs.datadoghq.com/security/default_rules/aws-network-acl-network-
acls-should-enforce-inbound-traffic-
restrictions/)[![vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) Network ACLs should enforce outbound traffic restrictions  
](https://docs.datadoghq.com/security/default_rules/aws-network-acl-network-
acls-should-enforce-outbound-traffic-
restrictions/)[![vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) Remote administration port access should be restricted to
trusted networks  
](https://docs.datadoghq.com/security/default_rules/aws-network-acl-remote-
administration-port-access-should-be-restricted-to-trusted-
network/)[![vpc](https://static.datadoghq.com/static/images/logos/amazon-
vpc_avatar.svg) VPC endpoint should restrict public access  
](https://docs.datadoghq.com/security/default_rules/aws-vpc-endpointexposed/)

![vpn](https://static.datadoghq.com/static/images/logos/amazon-vpn_avatar.svg)

VPN ____

>

[![vpn](https://static.datadoghq.com/static/images/logos/amazon-
vpn_avatar.svg) Site-to-Site VPN connection tunnels should be online  
](https://docs.datadoghq.com/security/default_rules/aws-vpn-connection-site-
to-site-vpn-connection-tunnels-should-be-online/)

![waf](https://static.datadoghq.com/static/images/logos/amazon-waf_avatar.svg)

WAF ____

>

[![waf](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) WAF Classic rule groups should be migrated to WAFv2  
](https://docs.datadoghq.com/security/default_rules/aws-waf-rule-group-waf-
classic-rule-groups-should-be-migrated-to-
wafv2/)[![waf](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) WAF Classic rules should be migrated to WAFv2  
](https://docs.datadoghq.com/security/default_rules/aws-waf-rule-waf-classic-
rules-should-be-migrated-to-
wafv2/)[![waf](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) WAF Classic web ACLs should be migrated to WAFv2  
](https://docs.datadoghq.com/security/default_rules/aws-waf-acl-waf-classic-
web-acls-should-be-migrated-to-
wafv2/)[![waf](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) WAF rules should have CloudWatch metrics enabled  
](https://docs.datadoghq.com/security/default_rules/aws-wafv2-rule-group-waf-
rules-should-have-cloudwatch-metrics-
enabled/)[![waf](https://static.datadoghq.com/static/images/logos/amazon-
waf_avatar.svg) WAF web ACLs should have at least one rule or rule group  
](https://docs.datadoghq.com/security/default_rules/aws-wafv2-acl-waf-web-
acls-should-have-at-least-one-rule-or-rule-group/)

![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)

Windows ____

>

[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Multiple failed login attempts  
](https://docs.datadoghq.com/security/default_rules/windows-brute-force-
detection/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
PsExec execution detected  
](https://docs.datadoghq.com/security/default_rules/windows-psexec-execution-
detection/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Suspicious named pipe created  
](https://docs.datadoghq.com/security/default_rules/windows-suspicious-pipe-
detection/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows active directory object WriteDAC access  
](https://docs.datadoghq.com/security/default_rules/windows-ad-object-
writeadac-
access/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows active directory replication from non machine account  
](https://docs.datadoghq.com/security/default_rules/windows-active-directory-
replication-from-non-machine-
account/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows active directory user backdoors  
](https://docs.datadoghq.com/security/default_rules/windows-ad-user-
backdoors/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows audit log cleared  
](https://docs.datadoghq.com/security/default_rules/windows-event-audit-log-
cleared/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows BITS transfer job download from direct IP  
](https://docs.datadoghq.com/security/default_rules/windows-bits-transfer-job-
download-from-direct-
ip/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows BITS transfer job downloaded to suspicious folder  
](https://docs.datadoghq.com/security/default_rules/windows-bits-transfer-job-
download-to-suspicious-
folder/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows CobaltStrike service installations  
](https://docs.datadoghq.com/security/default_rules/windows-cobalt-strike-
service-
installation/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows credential dumping via WER application error  
](https://docs.datadoghq.com/security/default_rules/windows-potential-
credential-dumping-via-wer-app-
error/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows delete volume shadow copies via WMI with PowerShell  
](https://docs.datadoghq.com/security/default_rules/windows-delete-volume-
shadow-copies-via-wmi-with-
powershell/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows directory service restore mode password changed  
](https://docs.datadoghq.com/security/default_rules/windows-event-directory-
services-restore-mode-password-
changed/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows DNS query to Tor Onion address  
](https://docs.datadoghq.com/security/default_rules/windows-dns-query-tor-
onion-
address/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows Domain Admin group changed  
](https://docs.datadoghq.com/security/default_rules/windows-event-domain-
admin-group-
changed/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows eventlog cleared  
](https://docs.datadoghq.com/security/default_rules/windows-important-windows-
eventlog-
cleared/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows firewall disabled  
](https://docs.datadoghq.com/security/default_rules/windows-event-firewall-
disabled/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows hidden local user creation  
](https://docs.datadoghq.com/security/default_rules/windows-hidden-local-user-
creation/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows important scheduled task deleted or disabled  
](https://docs.datadoghq.com/security/default_rules/windows-important-
scheduled-task-deleted-
disabled/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows malware protection engine crash  
](https://docs.datadoghq.com/security/default_rules/windows-malware-
protection-engine-
crash/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows moriya rootkit  
](https://docs.datadoghq.com/security/default_rules/windows-moriya-
rootkit/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows MSSQL disable audit settings  
](https://docs.datadoghq.com/security/default_rules/windows-mssql-audit-
settings-
change/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows MSSQL XPCmdshell change  
](https://docs.datadoghq.com/security/default_rules/windows-mssql-xp-cmdshell-
change/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows Net command executed to enumerate administrators  
](https://docs.datadoghq.com/security/default_rules/windows-event-net-cmd-
local-admin-
enumeration/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows password change on directory service restore account  
](https://docs.datadoghq.com/security/default_rules/windows-password-change-
on-directory-service-
restore/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows password protected ZIP file opened with suspicious email
attachments  
](https://docs.datadoghq.com/security/default_rules/windows-password-
protected-zip-email-
attachment/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows password protected ZIP file opened with suspicious filenames  
](https://docs.datadoghq.com/security/default_rules/windows-password-
protected-zip-suspicious-
filenames/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows potential powershell reverseshell connection  
](https://docs.datadoghq.com/security/default_rules/windows-sysmon-potential-
powershell-reverseshell-
connection/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell AADInternals cmdlets execution  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-
aadinternals-cmdlets-
execution/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell create volume shadow copy  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-create-
volume-shadow-
copy/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell disable command history  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-
disable-command-
history/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell PSAsyncShell asynchronous TCP reverse shell  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-
psasyncshell-async-tcp-reverse-
shell/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell suspicious Get-ADDBAccount usage  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-
suspicious-get-addbaccount-
usage/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PowerShell Veeam backup servers credential dumping script
execution  
](https://docs.datadoghq.com/security/default_rules/windows-powershell-veeam-
backup-servers-
script/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows privilege escalation via local kerberos relay over LDAP  
](https://docs.datadoghq.com/security/default_rules/windows-privilege-
escalation-via-local-kerberos-relay-over-
ldap/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows protected storage service access  
](https://docs.datadoghq.com/security/default_rules/windows-protected-storage-
service-
access/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows PurpleSharp execution  
](https://docs.datadoghq.com/security/default_rules/windows-purplesharp-
execution/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows register new logon process by Rubeus  
](https://docs.datadoghq.com/security/default_rules/windows-logon-process-
rubeus/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows replay attack detected  
](https://docs.datadoghq.com/security/default_rules/windows-security-replay-
attack/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows restricted software access by the Software Restriction Policies  
](https://docs.datadoghq.com/security/default_rules/windows-restricted-
software-by-
srp/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows SAM registry hive handle request  
](https://docs.datadoghq.com/security/default_rules/windows-sam-registry-hive-
handle-
request/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows service installed by suspicious client  
](https://docs.datadoghq.com/security/default_rules/windows-service-installed-
by-suspicious-
client/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows shimcache flush  
](https://docs.datadoghq.com/security/default_rules/windows-shimcache-
flush/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows SMB create remote file admin share  
](https://docs.datadoghq.com/security/default_rules/windows-smb-create-remote-
file-admin-
share/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows suspicious computer name containing Samtheadmin  
](https://docs.datadoghq.com/security/default_rules/windows-susp-computer-
name-containing-
samtheadmin/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows suspicious PowerShell mailbox export to share  
](https://docs.datadoghq.com/security/default_rules/windows-suspicious-
powershell-mailbox-export-to-
share/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows user added to Domain Admin group  
](https://docs.datadoghq.com/security/default_rules/windows-event-user-added-
to-domain-admins-
group/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
Windows vulnerable spn enumerated  
](https://docs.datadoghq.com/security/default_rules/windows-spn-
enumeration/)[![windows](https://static.datadoghq.com/static/images/logos/windows_avatar.svg)
BETA Windows WCE wceaux.dll access  
](https://docs.datadoghq.com/security/default_rules/windows-wce-wceauxdll-
access/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Windows Cloud Workload Security ____

>

[![windows cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Bitsadmin used to download
or execute a file  
](https://docs.datadoghq.com/security/default_rules/suspicious_bitsadmin_usage/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Certutil used to transmit or
decode a file  
](https://docs.datadoghq.com/security/default_rules/certutil_usage/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) NTDS file referenced in
command line  
](https://docs.datadoghq.com/security/default_rules/ntds_in_commandline/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Process memory dumped using
procdump  
](https://docs.datadoghq.com/security/default_rules/procdump_usage/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Process memory dumped using
the minidump functions of comsvcs.dll  
](https://docs.datadoghq.com/security/default_rules/minidump_usage/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Scheduled task created  
](https://docs.datadoghq.com/security/default_rules/scheduled_task/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Suspicous ntdsutil usage  
](https://docs.datadoghq.com/security/default_rules/ntdsutil_usage/)[![windows
cloud workload security](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) WMI used to remotely execute
content  
](https://docs.datadoghq.com/security/default_rules/wmi_spawning_shell/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Windows File Integrity Monitoring ____

>

[![windows file integrity monitoring](https://datadog-
docs.imgix.net/images/svg-icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg)
Critical windows file modified  
](https://docs.datadoghq.com/security/default_rules/critical_windows_files_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows boot registry key
modified  
](https://docs.datadoghq.com/security/default_rules/windows_boot_registry_key_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows COM RPC debugging
registry key modified  
](https://docs.datadoghq.com/security/default_rules/windows_com_rpc_debugging_registry_key_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows explorer executable
modified  
](https://docs.datadoghq.com/security/default_rules/windows_explorer_executable_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows firewall
configuration registry key modified  
](https://docs.datadoghq.com/security/default_rules/windows_firewall_configuration_registry_keys_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows hosts file modified  
](https://docs.datadoghq.com/security/default_rules/windows_hosts_file_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows known DLLs registry
key modified  
](https://docs.datadoghq.com/security/default_rules/windows_known_dlls_registry_key_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows registry hives file
paths key modified  
](https://docs.datadoghq.com/security/default_rules/windows_registry_hives_file_paths_key_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows security essentials
executable modified  
](https://docs.datadoghq.com/security/default_rules/windows_security_essentials_executable_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows shell folders
registry key modified  
](https://docs.datadoghq.com/security/default_rules/windows_shell_folders_registry_key_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Windows system environment
variables modified  
](https://docs.datadoghq.com/security/default_rules/windows_system_environment_variable_modified/)[![windows
file integrity monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) Winlogon registry key
modified  
](https://docs.datadoghq.com/security/default_rules/windows_winlogon_registry_key_modified/)

![wiz](https://static.datadoghq.com/static/images/logos/wiz_avatar.svg)

WIZ ____

>

[![wiz](https://static.datadoghq.com/static/images/logos/wiz_avatar.svg) BETA
Impossible travel scenario observed in Wiz authentication  
](https://docs.datadoghq.com/security/default_rules/wiz-impossible-
travel/)[![wiz](https://static.datadoghq.com/static/images/logos/wiz_avatar.svg)
BETA Wiz threat finding  
](https://docs.datadoghq.com/security/default_rules/wiz-finding-3pa/)

![](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg?w=80&auto-enhance 2x)

Workload Security Monitoring ____

>

[![workload security monitoring](https://datadog-docs.imgix.net/images/svg-
icons/agent.67e2ccd5150e9b20fd3aa128af699606.svg) SELinux enforcement disabled  
](https://docs.datadoghq.com/security/default_rules/selinux_disable_enforcement/)

![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)

Zeek ____

>

[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
Anomalous failed SSH authentication attempts by a single IP address  
](https://docs.datadoghq.com/security/default_rules/zeek-ssh-anomalous-failed-
authentication-
attempts/)[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
Generic DNS tunnel detected by Zeek  
](https://docs.datadoghq.com/security/default_rules/zeek-generic-dns-tunnel-
is-
detected/)[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
SSH interesting hostname login notice from Zeek  
](https://docs.datadoghq.com/security/default_rules/zeek-ssh-interesting-
hostname-login-
notice/)[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
SSH login by password guesser from Zeek  
](https://docs.datadoghq.com/security/default_rules/zeek-ssh-login-by-
password-guesser-
notice/)[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
SSH password guessing notice from Zeek  
](https://docs.datadoghq.com/security/default_rules/zeek-ssh-password-
guessing-
notice/)[![zeek](https://static.datadoghq.com/static/images/logos/zeek_avatar.svg)
SSH watched country login notice from Zeek  
](https://docs.datadoghq.com/security/default_rules/zeek-ssh-watched-country-
login-notice/)

![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)

Zendesk ____

>

[![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)
Zendesk account assumption is enabled  
](https://docs.datadoghq.com/security/default_rules/zendesk-account-
assumption-
settings/)[![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)
Zendesk API token is created  
](https://docs.datadoghq.com/security/default_rules/zendesk-api-token-
created/)[![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)
Zendesk Automatic Redaction is disabled  
](https://docs.datadoghq.com/security/default_rules/zendesk-automatic-
redaction-
settings/)[![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)
Zendesk IP restriction settings is disabled  
](https://docs.datadoghq.com/security/default_rules/zendesk-ip-restrictions-
disabled/)[![zendesk](https://static.datadoghq.com/static/images/logos/zendesk_avatar.svg)
Zendesk user's suspension status is changed  
](https://docs.datadoghq.com/security/default_rules/zendesk-user-suspension/)

![zoom](https://static.datadoghq.com/static/images/logos/zoom_avatar.svg)

Zoom ____

>

[![zoom](https://static.datadoghq.com/static/images/logos/zoom_avatar.svg)
BETA Zoom account sign in requirements changed  
](https://docs.datadoghq.com/security/default_rules/zoom-account-
authentication-requirements-
changed/)[![zoom](https://static.datadoghq.com/static/images/logos/zoom_avatar.svg)
BETA Zoom user updated to privileged role  
](https://docs.datadoghq.com/security/default_rules/zoom-users-to-privileged-
role/)

