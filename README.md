# vpn

This tools is helpful for quick connecting to the Saleforce, Inc network through the Anyconnect CLI.

## Installation

### Step 1.0 Clone Project.

1. Open your shell
1. Navigate to the root of your projects directory.
1. Clone this repository into your projects folder.
1. Navigate to the `vpn-automation` directory

### Step 2.0 Create A Symlink

The easiest way to utilize `vpn` is to create a symlink from the project to the `/usr/local/bin` directory on your machine. The following steps assume you are still in the `vpn-automation` directory.

**Execute:**

```
ln -s "$(pwd)/vpn" /usr/local/bin/vpn
```

**Validate** the symlink works by executing.

```
vpn -s
```

## Usage

```

Usage: vpn [-sd] OR vpn ONE_TIME_PASSWORD

  OPTIONS:

    -s    status
    -d    disconnect

```