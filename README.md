# dojot Real-Time Sample Client

It is a sample code to get device's data from dojot through socket.io.

## Usage

To install dependencies, run:

```shell
npm install
```

To start the client, run:

```shell
node index.js -U <dojot URL> -u <user> -p <password>
```

### Example

To start the sample client for a local dojot, run:

```shell
node index.js -U http://localhost:8000 -u admin -p admin
```