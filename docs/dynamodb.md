# Amazon DynamoDB

![DynamoDB](./images/dynamodb.png)

- DynamoDB is a fast and flexible NoSQL database service for all applications that need consistent, single-digit-millisecond latency at any scale.

- With DynamoDB, you can create tables and items. You can add items to a table. The system automatically partitions your data and has table storage to meet workload requirements.

- There is no practical limit on the number of items that you can store in a table. For instance, some customers have production tables that contain billions of items.

- One of the benefits of a NoSQL database is that items in the same table can have different attributes. This gives you the flexibility to add attributes as your application evolves. You can store newer format items side by side with older format items in the same table without needing to perform schema migrations.

- As your application becomes more popular and as users continue to interact with it, your storage can grow with your application's needs.

- In addition to scaling storage, DynamoDB also enables you to provision the amount of read or write throughput that you need for your table.

- As the number of application users grows, DynamoDB tables can be scaled to handle the increased numbers of read/write requests with manual provisioning.

- Some additional key features include global tables that enable you to automatically replicate across your choice of AWS Regions, encryption at rest, and item Time-to-Live (TTL).

## DynamoDB Components

The core DynamoDB components are tables, items, and attributes.

- A table is a collection of data.
- Items are a group of attributes that is uniquely identifiable among all the other items.
- Attributes are a fundamental data element, something that does not need to be broken down
  any further.

## Primary Key

DynamoDB supports two different kinds of primary keys.

- The partition key is a simple primary key, which is composed of one attribute called the sort key.

- The partition key and sort key are also known as the composite primary key, which is composed of two attributes.
