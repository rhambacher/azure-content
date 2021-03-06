# Java Developer Center - How To Guides

## Data management and integration

### [Blob Service][blob_service]

Blobs are the simplest way to store large amounts of unstructured text or binary data such as video, audio and images. Blobs are an ISO 27001 certified managed service that can auto-scale to store up to 100 terabytes of data. They are accessible from virtually anywhere via REST and client APIs.

### [Service Bus Queues][service_bus_queues]

Service Bus Queues offer simple first in, first out guaranteed message delivery and support a range of standard protocols (REST, AMQP, WS*) and APIs to put and pull messages on and off a queue.

### [Service Bus Topics][service_bus_topics]

Service Bus Topics provide a publish/subscribe messaging model to support one-to-many communication. You can optionally register filter rules for a topic on a per-subscription basis, which allows you to restrict which messages to a topic are received by which topic subscriptions.

### [Queue Service][queue_service]

Windows Azure Queues store large numbers of messages that can be accessed from anywhere in the world via authenticated calls using HTTP or HTTPS. Common uses of Queue storage include creating a backlog of work to process asynchronously, and passing messages from a Windows Azure Web role to a Windows Azure Worker role.

### [Table Service][table_service]
Tables offer NoSQL capabilities for applications that require storage of large amounts of unstructured data. Tables are an ISO 27001 certified managed service that can auto-scale to store up to 100 terabytes of data. They are accessible from virtually anywhere via REST and managed APIs.

### [SQL Database][sql_database]

For applications that need a full featured relational database-as-a-service, Windows Azure offers SQL Database, formerly known as SQL Azure Database. SQL Database offers a high-level of interoperability, enabling customers to build applications using many of the major development frameworks.

## Additional guides

### [Service Runtime][service_runtime]

The Windows Azure Service Runtime allows your hosted service to communicate with the Windows Azure environment.

### [SendGrid Email Service][sendgrid]

Windows Azure applications can use SendGrid to include email functionality.  SendGrid provides reliable email delivery,  real-time analytics, and flexible APIs that allow users to easily incorporate the service into their Windows Azure applications.

### [Twilio Voice and SMS Service][twilio]

Windows Azure applications can use Twilio to incorporate phone call and Short Message Service (SMS) message functionality.  Use the Twilio APIs to make and receive phone calls, make and receive SMS messages, and enable voice communication using existing internet connections, including mobile connections.

[blob_service]: ../howto/blob-storage.md
[service_bus_queues]: ../howto/service-bus-queues.md
[service_bus_topics]: ../howto/service-bus-topics.md
[queue_service]: ../howto/queue-storage.md
[table_service]: ../howto/table-storage.md
[sql_database]: ../howto/using_sql_azure_in_java.md
[service_runtime]: http://msdn.microsoft.com/en-us/library/windowsazure/hh690948.aspx
[sendgrid]: ../howto/sendgrid-email-service.md
[twilio]: ../howto/twilio_in_java.md
