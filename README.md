# Mongo Stream

![logotype_1a](https://user-images.githubusercontent.com/36637989/42541267-9785db22-8499-11e8-931a-c84733d07a45.png)

Mongo Stream is a Node.js project that aims to make use of Mongo 3.6+ change-streams
to synchronize data between Mongodb and ElasticSearch

## Prerequisites

* Node.js (tested with version 8)
* Mongodb 3.6+
* Elasticsearch 2.4.5, 5.x+ (Compatibility for 6 is a future goal)

## Setup

```
git clone https://github.com/electionsexperts/mongo-stream.git

npm install
```

## Usage

To use with default configuation:
```
npm start
```

To use with a custom config file:
```
./server.js -c <path-to-config-file>
```

## Contributing

Feel free to submit pull requests. If you'd like to contribute towards closing an open issue please leave a comment with your solution proposal in the comment section of the issue.  

## Credits

This project was originally developed [here](https://github.com/votem/mongo-stream) and will henceforth be maintained and updated at: https://github.com/electionsexperts/mongo-stream.
