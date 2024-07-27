# Installing XLArig on your Raspberry Pi (Scala mining)

<br>
<br>
Check also our YouTube channel for instructions and other related information [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") :coffee:.

<h3><u>The commands to update and upgrade your Pi</u></h3>

```
sudo apt update
```
```
sudo apt upgrade
```

<h3><u>The command to reboot your Pi</u></h3>

```
sudo reboot now
```

<h3><u>The commands to install screen and other necessary tools and libraries </u></h3>

```
sudo apt install screen
```
```
sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
```
Now get the latest XLArig code:

```
git clone https://github.com/scala-network/XLArig.git
```

<h3><u>The commands to compile and build XLArig</u></h3>

Go to the XLArig directory by typing cd XLArig and enter the following command:

```
mkdir build
```

Now go to the new build directory by typing cd build and enter the following commands:

```
cmake ..
```
```
make
```

After you executed the above commands you must give your miner execution rights with the following command:
```
chmod u+x xlarig
```

<h3><u>The commandline to start mining Scala (XLA)</u></h3>

```
./xlarig --donate-level 0 -o mine.scalaproject.io:3333 -u YOUR_SCALA_WALLET_ADDRESS -p YOUR_WORKER_NAME -a panthera -k
```

<h3><u>Other commands which can be usefull</u></h3>

To start a screen session use the command:
```
screen
```
To disconnect from a screen session use the key combination:
Ctrl-a and d

To reconnect to a screen session use the command:
```
screen -r
```

We hope you have fun mining XLA (Scala)!!!


