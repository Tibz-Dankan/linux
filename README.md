# Linux os

##### Make partition a swap

```.sh
sudo mkswap /dev/sda3

```

#### Apply the swap to the existing one

```.sh
sudo swapon /dev/sda3

```

### check for memory including swap

```.sh
free -h
```
