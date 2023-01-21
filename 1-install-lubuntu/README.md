# Install Lubuntu

### Step 1
Fare il setup dell'indirizzo IP di Lubuntu 1 (scripts/lubuntu1/Setup.sh):

    ```
    ip addr add 10.0.0.101/24 dev enp0s3
    ip link set enp0s3 up
    ```

### Step 2
Fare il setup dell'indirizzo IP di Lubuntu 2 (scripts/lubuntu2/Setup.sh):

    ```
    ip addr add 10.0.0.102/24 dev enp0s3
    ip link set enp0s3 up
    ```

### Step 3
Fare il setup dell'indirizzo IP di Lubuntu 3 (scripts/lubuntu3/Setup.sh):

    ```
    ip addr add 10.0.0.103/24 dev enp0s3
    ip link set enp0s3 up
    ```
