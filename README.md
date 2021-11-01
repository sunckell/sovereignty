# sovereignty
giving the authority to developers to govern themselves.

In some coporate situations, security mandates that AWS configurations such as KMS, IAM, and Security Groups not be directly accessible by developers.

Workflows begin to form in these situations that are normally not the most "developer friendly".

Soveriegnty is an example of how configurations can be centralized (single-repo) and promote developer efficiency. 

The idea simple, build standardized modules for KMS, IAM, Security Groups with an interface that doesn't need a PhD to understand. Deploy your configurations from here, then consume these resources in your IAC for you application.


