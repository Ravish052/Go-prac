# Go Learning Roadmap

## Goal

Learn Go by building progressively more complex projects while understanding:

* Go syntax and idioms
* Concurrency
* Networking and APIs
* Database access
* Testing
* Docker
* Production-ready backend architecture

Repository structure:

```text
go-learning/
├── .devcontainer/
├── fundamentals/
├── web/
├── concurrency/
├── microservices/
└── PLAN.md
```

---

# Phase 1: Go Fundamentals

## Project 1: Todo CLI

### Concepts

* Variables
* Functions
* Structs
* Slices
* Loops
* Conditionals
* JSON
* File I/O

### Features

* Add task
* List tasks
* Mark task complete
* Delete task
* Save to local JSON file

### Success Criteria

* Understand basic Go syntax
* Comfortable using structs and slices
* Comfortable with packages

---

## Project 2: Log/File Parser

### Concepts

* Reading files
* String manipulation
* Error handling
* Standard library usage

### Features

* Parse log files
* Count errors
* Count warnings
* Generate summary report

### Success Criteria

* Become comfortable with Go's error handling style
* Learn standard library patterns

---

# Phase 2: Web Development

## Project 3: URL Shortener

### Concepts

* net/http
* Request handling
* JSON APIs
* Maps
* Middleware basics

### Features

* Create short URL
* Redirect endpoint
* Statistics endpoint

### Success Criteria

* Build APIs without frameworks
* Understand HTTP handling

---

## Project 4: Notes API

### Concepts

* REST APIs
* Routing
* Validation
* Context package

### Features

* Create note
* Read note
* Update note
* Delete note

### Success Criteria

* Design clean API structure
* Organize packages effectively

---

# Phase 3: Concurrency

## Project 5: Concurrent Downloader

### Concepts

* Goroutines
* Channels
* WaitGroups

### Features

* Download multiple URLs simultaneously
* Progress tracking
* Retry failed downloads

### Success Criteria

* Understand Go concurrency model

---

## Project 6: Worker Pool

### Concepts

* Buffered channels
* Worker pools
* Job queues

### Features

* Fixed worker count
* Queue jobs
* Collect results

### Success Criteria

* Understand scalable concurrent processing

---

# Phase 4: Databases

## Project 7: Notes API + PostgreSQL

### Concepts

* database/sql
* PostgreSQL
* Migrations
* Transactions

### Features

* Persist notes
* Pagination
* Search

### Success Criteria

* Build database-backed services

---

## Project 8: URL Shortener + PostgreSQL

### Concepts

* Repository pattern
* SQL queries
* Data modeling

### Features

* Persistent storage
* Click tracking
* Expiration support

### Success Criteria

* Design relational schemas

---

# Phase 5: Authentication

## Project 9: Auth Service

### Concepts

* JWT
* Password hashing
* Middleware
* Configuration management

### Features

* Register
* Login
* Refresh token
* Protected endpoints

### Success Criteria

* Build reusable authentication service

---

# Phase 6: Caching and Performance

## Project 10: URL Shortener + Redis

### Concepts

* Redis
* Caching
* Performance optimization

### Features

* Cache redirects
* Cache statistics

### Success Criteria

* Understand cache patterns

---

# Phase 7: Production Readiness

## Topics

### Testing

* Unit tests
* Table-driven tests
* Integration tests

### Docker

* Multi-stage builds
* Containerized deployment

### Logging

* Structured logs

### Configuration

* Environment variables
* Secrets management

### CI/CD

* GitHub Actions
* Automated tests

---

# Final Project

## Mini E-Commerce Backend

### Features

* Users
* Authentication
* Products
* Inventory
* Orders
* PostgreSQL
* Redis
* Docker

### Objectives

Combine everything learned:

* Go fundamentals
* APIs
* Concurrency
* Databases
* Authentication
* Caching
* Testing
* Deployment

---

# Rules

1. Prefer standard library first.
2. Learn net/http before frameworks.
3. Learn database/sql before ORMs.
4. Write tests for every project.
5. Containerize every API project.
6. Commit code frequently.
7. Focus on understanding, not speed.

---

# Completion Checklist

* [ ] Fundamentals completed
* [ ] Web APIs completed
* [ ] Concurrency completed
* [ ] Databases completed
* [ ] Authentication completed
* [ ] Redis completed
* [ ] Testing completed
* [ ] Docker completed
* [ ] CI/CD completed
* [ ] Final project completed
