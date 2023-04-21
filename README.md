# 195


Router is a device which connects Multiple Local Area networks.

In this session we are going to learn how to Connect 2
Local Area networks using Router

--------------------------------------------------------
take computers and the switch now let’s connect them with each other.
instead of manually selecting the cable let’s click on the automatic selection.

This will choose the best cable according to the device and connect it to the appropriate port.
Which in our case is a fast Ethernet port.

Our switch and PC both have this port.PC only has 1 FastEthernet port but switch has multiple ethernet ports.
You can check how many ports a switch has by hovering the mouse above the switch.

Switch takes some time to set up thats the reason we see orange dots
We can skip that waiting time by clicking on the fast forward button.

Lets assign IP addresses to all the 3 computers. IP address for the computers on this network are going to
be in order of 10.0.0.1 upto 10.0.0.3


---------------------------------------
Once the IP address is assigned to all the computers in this network we can bring the Router on the screen.
Router options are present in the bottom left menu. We have different options for the Routers but we are going
to go with the first on


Next step is to connect the Router with Switch.The cable needed for this connection is also copper
straight through.


But the port will be different on the router.
Our switch has the Fast Ethernet Port as well as Gigabit
Ethernet port.
But router has only Gigabit Ethernet port



Difference between these 2 ports is that gigabit Ethernet is faster than fast ethernet.
The maximum speed of data transmission on fast Ethernet is 100 MBPS but on the gigabit port it is 1000MBPS.

But there are other differences also such as gigabit is costly and it can be used to transmit data over long
range(upto 70 km).But fast ethernet can transmit over short distances only upto 10 KM.

----------------------------------------

In order to connect the 2 devices select the copper straight through cable and click on the switch. Here select the
Gigabit port


Our connection of the Router and the switch is done.But
we still are having red triangles on the wire.
Which means that these 2 devices are not connected
properly

There are 2 steps we need to perform in order to bring the router online.

First is by default the port of the router is turned off.
We need to turn that On.

For that double click on the router and go to the config tab and then in the bottom left select the gigabit 0 port.
Here you have the option to turn it on
---------------------------------------

Once we assign the IP address here and turn this port on.
You can see that the cable now has the green triangles.
Which means our connection is successful

-------------------------
192.168.1.1,
192.168.1.2,
192.168.1.3

Now once all the computers are assigned the IP address
we can now connect the switch with the router.
Can you please tell me the process to do that?
First we need to connect the router and switch using the
copper straight through cable and the cable is connected
to Gigabit ethernet port on both ends

We now have a network of 2 Local Area Networks.
It is called WAN. Wide Area Network

We need to assign the IP address to the port on the router
and turn that port On.
Double click on the router and then go to config Tab.
Here select the gigabit ethernet port 2 and then assign the
IP address as 192.168.1.4 and check the on option.


Once we do this we can see that all the triangles are now
green which means that both of our LAN’s are connected
now.
----------------------------------------------------------------
Now let’s perform a ping test to see whether we can ping
the computer on the right LAn from the left LAN.
Double click on any computer on the left LAN and then
open the command prompt.
First we will check the IP address of this computer.
Can you tell me the command to do that?
Very good.
Let’s type ipconfig and press enter. This will show us the IP
address of this computer.

------------------
We tried to ping other computers. But this is not working.
This shows request time out.
This happens when the computers are not connected with
each other.

---------------------

When our computer connects with the internet.The first
device it connects with is our router.
Our router has an IP address which we also assigned
here.
But our computer doesn't know about this IP address of
the router.
They don’t know that this router exists. To overcome this
problem we need to tell our computers about the router
and it’s IP address.
This is called the default gateway.This is the first device in
the way to connect with the internet. Usually in the real
world when you connect with your router. It will
automatically assign the IP address and the default
gateway.
But since we are in a simulated environment. We have to
do this manually.
---------------------------

Double click on the first computer on the left network and
go to the IP configuration window.
There is a tab named default gateway.
In this write the IP address we assigned in the router.
Which is 10.0.0.4
Note: Default Gateway should be same as the IP
address assigned to the router

----------------------


