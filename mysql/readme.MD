----> Here in secret-manifest file you have an example how to use AWS SECRETS in our pods

--- > for this we need a Service account, IAM role and an INIT container with amazon/aws-cli image ---which dives into the
aws securely and gets info from there here we are getting secrets 

----> INIT container + Aws cli is the only secure combination to get data from aws to our pod directly.

----> for clear code explanation goto CHATGPT ---  How to get values form aws secrets into our k8s pod throgh init container
