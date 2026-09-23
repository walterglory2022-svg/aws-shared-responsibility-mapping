# aws-shared-responsibility-mapping

In AWS, shared responsibility means security is divided into two parts.

AWS is responsible for security OF the cloud — they protect the physical buildings, the actual computers, the network cables, and the software that runs AWS itself. You don't see or control that part.

You, the customer, are responsible for security IN the cloud — everything you put inside AWS. Your data, your passwords, who can access your S3 buckets and RDS databases, your firewall rules, and how you configure your EC2 servers.

If AWS's data center burns down, it's AWS fault. If you leave your S3 bucket open to the public and someone steals your files, it's your fault — just like the Capital One breach.
