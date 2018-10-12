# Disaster-Broadcast

## Brief Idea
During disaster(s) there is high chances of people getting displaced or lost. 
We wanted to create a broadcast transponder system using existing infrastructure to basically 
broadcast signals and locate lost people on basis of received echoes.

## Detailed Idea
During time of disaster we propose to use either a swarm of drones of helicopters to broadcast high 
power radio signals in a specified frequency over and accross the affected area. Devices such as mobile 
phones, radio transponders or anything that can receive this signal would then transmit back and the 
broadcaster would be able to detect incoming pings and thereby locate people.

## Features

* Radio broadcasters
  * Used to send broadcasts at a specific frequency and pickup distinctive response
    signals to locate people
* Radio devices/transeivers
  * These are present with the people
  * Can emit distinctive pings.
  * Can pickup broadcast signals and can emit responses.
* Central server
  * This is what we want to implement
  * Co-ordinates broadcasts and pings 
  * Maps pings to an approximate geography
  * Co-ordination between different broadcasting teams
  * Insights wrt total area covered by to broadcasts
  * Can include additional capabilities to call for backup among others
  * Communication can also happen accross this channel.

## Analogy
Our idea is something similar to finding a lost aircraft by using tranceivers which can capture the 
disctincive pings of the black-boxes. In our idea the aircraft are people and the black-boxes are 
radio devices which can emit distinctive pings or emit "response" signals to emergency broadcasts.

## How do we stand apart?
We plan to use the already existing infrastructure like radio tranceiver present in any basic mobile 
phone, etc 
So no need for new hardware or complex adoptation process. We feel our solution would be effective 
irrespective of literacy in using technology. The presence of a powered radio device would suffice.
Our solution would not necessarily require internet, or mobile signal which might not exist during 
calamity period.
