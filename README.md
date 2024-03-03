# chat-system-design
- Scalable chat app
 - Handle active user 100 milion daily active user (100 million DAU)
- One to one chat
- Group chat
  - group member limit like - 100 member in one group
- Message size limit
  - text length should be less than 100,000 characters long
- End to end encryption
- Support both web app and mobile app
- Chat history should be stored
  - Forever
- Low delivery latency
- Online presence
- Multiple device support - the same account can be logged in to multiple accounts at the same time.
- Push notification

## Database
- In-memory
 - Redis
 - Kafka 
- Persistence storage
 - Cassandra
 - MongoDB
 - PostgreSQL (In case of relational chat between friends) 
