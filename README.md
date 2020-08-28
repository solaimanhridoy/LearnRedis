<img src="img/Redis-Logo.wine.png" alt="Redis Logo" style="zoom:18%;" />

# LearnRedis

## What is Redis? 

-- Open source, in memory, NoSQL Database

--Created 2009 by Salvatore Sanifilippo

-- Reputation = Ridiculously Fast

## **What can I do with Redis?**

-- 5 data types (String, List, Set, Sorted Set, Hash)

- +2 special types (bitmap & hyperloglog)

-- 160 Commands

-- Lua scripts add flexibility 

-- Use Cases:

- User Session Store
- Recent visitors list
- Friends of Friends list
- PubSub
- Many, Many use cases!

## Who uses Redis?

- Twitter, Instagram, Pinterest, tumblr, stackoverflow, github, docker, craiglist

 and many more.



## What kind of DB is Redis?

-- Key Data-Strucutures ... not just Key Value/String

- Value data types, string, list, set, sorted set, hash
- Also: Bitmaps and HyperLogLog

-- Run's in-memory

- which means .. very fast reads and writes.
- But with disk persistence, so you survive a crash
- The only lilitation is physical memory
- Note: RLEC was created to solve memory limits

## How is Redis Used?

-- Extremely easy to use; clearly documented at redis.io

-- Mainly used as Cache Layer

- Many use it as their 2nd-class database
- Some even a 1st class

-- It's also a great Pub/Sub engine!

-- All config is done in one very clear text file

-- Single-threaded

## Redis vs Memcached

-- Redis supports supercast of Memcached features

-- Rich set of data types, not just key-value pairs

-- Persistence, you don't lose RAM when reboot

-- Replication, master-slave

## Redis: Use Cases

1. Show latest items listings in your home page
2. Deletion and filtering
3. Leader boards and related problems
4. Order by user votes and time
5. Implement expires on time
6. Counting stuff
7. Unique N items in a given amount of time
8. Real time analysis of what is happening, for stats, anti spamm or whatever
9. Pub/Sub
10. Queues
11. Caching

**Key Take Away**

-- Don't engage in model wars

-- Composing powerful and simple primitives together.

-- You can write specialized code, but Redis makes it easier to implement

