# serverless_archi

# Make a comparison between Serverless Framework and Terraform as tools for IaC. answer the following:

# - What type of infrastructure and application deployments are each tool best suited for?

# serverless framework are suitable for infrastructure such as S3 bucket, AWS Lambda, AWS DynamoDB. Terraform are suitable for application deployment for web server, databases

# - How do their primary objectives differ?

# - Terraform as a IaC is design to manage multiple resources across different platforms with a declarative approach to managing the infrastructure to ensure it provides consistency and version control. while serverless framework focus is on event driven architectures through the use of easy to use commands.

# - How do they differ in terms of learning curve and ease of use for developers or DevOps teams?

# Terraform is easy to use through the use of documentation available on the individual providers. While serverless architecture simplify hard to understand infrastructure details with easy to follow command.

# - What are the differences in how each tool handles state tracking and deployment changes?

# For eg. AWS has cloudwatch service has stream logs to track each invocation and execution for easy management. Whereas, Terraform uses state files to records the current state of the managed resources and mapping each resources to the configuration to the actual infrastructure. Terraform plan allows user to know what deployment changes will be done when the Terraform apply is applied and it will then update the state file.

# - In what scenarios would you recommend using Serverless Framework over Terraform, and vice versa?

# serverless framework - for quick deployment, built event driven architecture, single cloud provider. Terraform - when need to managed infrastructures across multiple cloud providers, when need to manage large and complex resources. 

# - Are there scenarios where using both together might be beneficial?

# in the event when using terraform requires event driven based architecture. We can implement it with terraform. Eg. create an S3 bucket that will trigger events.
