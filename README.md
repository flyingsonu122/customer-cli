# Customer Management CLI

## Installation

Install the dependencies

```sh
$ npm install
```


## Create Symlink

```sh
$ npm link
```

## Usage

* First of all, you should have mongoDB installed on your computer

* Open a terminal in **C:\data\db>** directory and run mongod

```sh
$ mongod
```

* Leave it running, till you are working with this CLI

## Commands

List Customers (list or l)
```sh
$ customer-cli list
```

Find Customers (find or f)
```sh
$ customer-cli find [NAME]
```

Add Customer (add or a)
```sh
$ customer-cli add
```

Update Customer (update or u)
```sh
$ customer-cli update [_ID]
```

Remove Customer (remove or r)
```sh
$ customer-cli remove [_ID]
```

## Took Guide from

**Brad Traversy**
[Traversy Media](http://www.traversymedia.com)


## License

This project is licensed under the MIT License