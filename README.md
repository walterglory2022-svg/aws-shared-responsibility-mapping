# aws-shared-responsibility-mapping

In AWS, shared responsibility means security is divided into two parts.

AWS is responsible for security OF the cloud — they protect the physical buildings, the actual computers, the network cables, and the software that runs AWS itself. You don't see or control that part.

You, the customer, are responsible for security IN the cloud — everything you put inside AWS. Your data, your passwords, who can access your S3 buckets and RDS databases, your firewall rules, and how you configure your EC2 servers.

If AWS's data center burns down, it's AWS fault. If you leave your S3 bucket open to the public and someone steals your files, it's your fault — just like the Capital One breach.

Think of AWS like a big secured market complex in Port Harcourt.

AWS built the complex. They provide the fence, security guards at the gate, strong roof that won't leak, light (NEPA), and they make sure no thief breaks the main building. That's their responsibility — Security OF the Cloud.

You rented one shop inside. What you put inside that shop — your goods, your money, your padlock, who you give key to, how you arrange your shelves — that's YOUR responsibility. If you leave your shop open and someone steals your goods, you can't blame the market owner. That's Security IN the Cloud.

So with AWS, Amazon secures the building (computers, wires, data centers), while you secure your own things inside it (your passwords, your files in S3, your database in RDS, and who can access them).
