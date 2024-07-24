f5 AS3 declaration schema controls what objects may appear in a declaration, what name they may or must use, what properties they may have, which of those you must supply in the declaration, and which BIG-IP AS3 may fill with default values.
The JSON Schema document prescribes the syntax of a BIG-IP AS3 declaration

I intend to create a json declaration for a tenant in this example, each tenant can contain its applications, configurations, and resources, allowing for multi-tenancy on a single BIG-IP instance. 
This isolation is crucial for managing different environments example development, staging, and production) or other customers in a shared infrastructure.
In addition, you can have different VIP, Floating IP, Internal and External IP
-Mario Lebrun
