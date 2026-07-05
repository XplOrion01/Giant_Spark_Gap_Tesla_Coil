High-Voltage Power Supply Network

I. Power Architecture and Safety Constraints

i.The system utilizes a standard domestic input (230 V AC, 50 Hz) and steps it up to the kilovolt (kV) range required to energize the resonant tank circuit.

ii.Voltage Limitations: While optimal spark gap Tesla coils typically utilize 10-20 kV power supplies, this system was intentionally limited to approximately 4.4 kV to satisfy university laboratory safety regulations and mitigate extreme arc-over risks during presentation.


II. Component Specifications

i.High-Voltage Transformers: The power stage consists of two identical Microwave Oven Transformers (MOTs). Each individual transformer steps up the input voltage from 220 V to a secondary output of 2200 V AC.

ii.Ballasting / Current Limiting: MOTs are shunted transformers designed to run at high currents and will rapidly overheat or trip mains breakers if unrestricted. To limit the input draw and stabilize the arc, an inductive/resistive ballast network consisting of four 100 W incandescent filament bulbs connected in parallel was placed inline with the supply.

iii.Overcurrent & System Protection: For primary safety, a dedicated Two-Pole Miniature Circuit Breaker (MCB) is integrated at the main AC input line. The two-pole MCB is critical as it completely isolates both the Live and Neutral lines simultaneously in the event of a fault.


III. Wiring Topology and Circuit Configuration

The primary power supply section is wired according to the following electrical configuration:

i.Current Limiter Network: Four 100 W bulbs are wired in parallel with each other to increase the total allowable current throughput while still providing a safety ceiling.

ii.Transformer Interconnection: Low-Voltage (Primary) Side: The primary inputs of the two MOTs are wired in parallel to receive the incoming 230 V AC supply.
High-Voltage (Secondary) Side: The high-voltage secondary outputs of the two MOTs are wired in series (ensuring proper phasing) to combine their outputs, resulting in a total supply voltage of 4400 V AC (4.4 KV).

iii.Mains Control Loop: The AC mains input feeds directly into the two-pole MCB. The output of the MCB is wired in series with the parallel bulb ballast network, 
which then connects in series to the parallel primary inputs of the MOT assembly.

The combined high-voltage series output from the MOT secondaries is then routed directly to the primary tank circuit.
