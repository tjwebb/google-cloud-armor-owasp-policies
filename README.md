# google-cloud-armor-owasp-policies
OWASP Top 10 Security Policies for Google Cloud Armor

## Load policies into Google Cloud

For example:
```
gcloud compute security-policies create a1-injection-policy
  --file-format yaml
  --file-name a1-injection-policy.yaml
```
