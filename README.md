# multiagent_learning

Top level project files for multiagent learning.

## Installation ##

### Linux ###

Install system dependencies:
```
sudo apt install libboost-dev libeigen3-dev libyaml-cpp-dev
```

In the working folder of your choice, clone the project code:
```
git clone https://github.com/JenJenChung/multiagent_learning.git
```

Clone internal dependencies:
```
cd multiagent_learning
git clone https://github.com/JenJenChung/include.git
```

Build the code:
```
cd build
cmake ..
make
```

## Running preconfigured projects

Run the project configured by `config.yaml` using six threads:
```
./testWarehouse -c ./config.yaml -t 6
```
Cosult the documentation for details about configuration file options.
