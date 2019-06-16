# node-thread-pool-behaviour
testing thread pool behaviour while executing filesystem read.

HTTPS is not managed by threadpool, while fileSystem read the file he wait 2 times for the hard drive response, while waiting the async task he execute crypto.pbkdf2 hash function.

this code test thread pool managing the threads executing another task when an async task is executed.
