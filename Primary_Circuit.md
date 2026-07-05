Primary Circuit & Components

I. Circuit Topology and Configuration

The primary circuit utilizes a dual Microwave Oven Transformer (MOT) configuration supplying a high-voltage output of 4400 V AC. The circuit topology is arranged as follows:

   i. The high-voltage AC output 4.4 KV is connected in parallel with the resonant tank capacitor bank.
  
  ii. The spark gap and the primary coil are connected in series with one another.
  
 iii. This series combination (spark gap + primary coil) is then connected in parallel across the primary high-voltage terminals.

Detailed circuit diagrams and physical assembly photographs can be found in the Images/ directory of this repository.


II. Primary Coil Specifications

The primary coil was constructed as a vertical helical inductor using the following parameters:
  
  i. Conductor: 13 SWG (Standard Wire Gauge) enameled copper wire.
 
 ii. Form/Support: A 110 mm diameter, 400 mm tall PVC pipe acting as the structural chassis.

iii. Windings: Approximately 14 turns, evenly spaced across the form factor.
 
 iv. Total Material Used: Approximately 5 meters of 13 SWG wire.

III. Spark Gap Assembly & Thermal Management

The spark gap acts as the high-speed switching element that periodically discharges the tank circuit.

  i. Design: A static two-electrode configuration mounted on an insulating wooden base to prevent electrical arcing to the chassis and minimize heat transfer.

 ii. Electrodes: While copper electrodes are recommended for optimal conductivity and lifespan, steel nails were utilized for this build, spaced at an 
     experimental gap of approximately 3 mm (adjustable between 2-5 mm).

iii. Thermal Considerations: The electrodes experience rapid thermal loading during operation. If the electrodes overheat, the air in the gap remains ionized,
     preventing the coil from firing correctly until it cools. To mitigate this thermal runaway, a dedicated forced-air cooling fan was integrated directly
     adjacent to the gap to accelerate cooling cycles.

IV. Resonant Tank Capacitor Bank
    To determine the required primary capacitance, calculations were conducted using the JAVATC Tesla Coil Calculator. Due to component availability and high-  
    voltage safety margins, a custom capacitor bank was engineered:
    Individual Unit Rating: 2 kV, 47 nF film capacitors.

Bank Configuration: A series-parallel network consisting of 4 parallel strings, where each string contains 5 capacitors connected in series (a 5*4 array, totaling 20 individual capacitors).

Final Equivalent Bank Rating: 10 kV maximum voltage rating with a total capacitance of 37.6 nF}.
