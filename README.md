# openrc-mongod

## Usage

1. Clone this repository.
```
git clone https://github.com/haturatu/openrc-mongod.git
```

2. Move the mongod script to /etc/init.d/mongod.
```
sudo mv mongod /etc/init.d/mongod
```

3. Optionally, change the permissions of the mongod script.
```
sudo chmod +x /etc/init.d/mongod
```

4. Add a service to OpenRC.
```
sudo rc-update add mongod default
```
done!
