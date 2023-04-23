# Optimum-Power-Control-at-Different-Loading-Condition
Objective: We consider three different loading condition such as base load, peak-load and off-peak load. Here we kept voltage constant and given different time delay considering voltage spike, surge voltage for three loading condition. We use current injection device to give the rated power to the load.
Equipment:
•	220V-6V Transformer
•	555 timer
•	Resistors (10K,1K)
•	Relay 6V DC
•	Capacitors –(103pf,10uf,2pf,1000uf)
•	Load (100W,60W,25W)
•	Vero board
•	Diode (1N4001)
•	POT (500K ohm)
•	Switch ,wires
•	Current Injection device
•	Variac
Working Principle:
When AC main single phase supply comes to the step down centre tapped transformer, it convert voltage 6V AC. Two diode (1N4007) rectify and convert AC to DC. 555 timer use for generating the time delay. In this project consider three types of load. Such as base load,peak load and off-peak load. For base load consider 5 seconds time delay. Both peak and off-peak load consider 1 second time delay. Shorted normally open terminal of all 6v relay and connected to the one end of the load. Another terminal of the load is connected to the main AC power supply live line. Here we use three different rating load. Such as 60 watt(base load), 100watt(off-peak load) and 200 watt(peak load).

In this project, we keep the voltage rating 220V constant. Consider step down transformer-1 and timer circuit for base load. Similarly transformer-2 for off-peak and transformer-3 for peak load. When 220V comes from main supply to the transformer-1, timer circuit gives 5 seconds delay then current flow through the relay. Then the relay is energized and 60watt load is connected if press the switch. We measure the current across the load using clamp meter. If current is less than the load rating current then use current injection device to give the rated current to the load. So that we give the load rated power. Similar operation also happen for transformer-2 and transformer-3, only difference is generate time delay.
Application:
By using this project concept consumer can get rated power across the loads. So that consumer loads component life time can be longer.
In power plant, this can build a bridge between generation end to consumer end.
https://github.com/mohsinislamrifat/Optimum-Power-Control-at-Different-Loading-Condition
