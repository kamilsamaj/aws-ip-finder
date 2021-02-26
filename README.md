# aws-ip-finder
Find what AWS service is using a given IP address

# Usage
## `aws-ip-finder refresh`
Fetch the latest AWS IP Range definition from https://ip-ranges.amazonaws.com/ip-ranges.json and store it as a temporary file.
Cached files older than 24 hours are automatically refreshed.

## `aws-ip-finder list-services`
List all AWS services found in the IP ranges file.

## `aws-ip-finder find-service <IP_ADDRESS>`
Find what AWS service is using a particular IP address. `IP_ADDRESS` should be a valid IPv4 or IPv6 address.

## `aws-ip-finder ip-ranges <AWS_SERVICE_NAME>`
Return a list of all IP ranges used by a particular AWS service
