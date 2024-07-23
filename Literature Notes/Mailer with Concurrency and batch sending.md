#Mailer with Concurrency
Created: 2024-07-05 12:00

##References
1.  We will be be using background jobs
2. A gem like sidekiq which works with redis or solid queue that works with active storage
3. configure the broker
4. create a worker or the function for sending the emails in batches of maybe 40-50
5. do your scheduler and determine the interval you want it sent
6. run the script

