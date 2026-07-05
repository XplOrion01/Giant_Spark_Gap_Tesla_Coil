Enclosure Design, Thermal Management, and System Operation

I. Structural Chassis and Enclosure Design

Because this system was engineered as a university exhibition model, both structural aesthetics and functional component isolation were key design priorities.

i. Chassis Material: A custom wooden shell enclosure was fabricated to house the high-voltage control electronics and primary circuitry safely out of view.

ii. Coil Integration and Alignment: The top of the wooden enclosure features a precision-cut mounting hole.

iii. The un-wound 200 mm base of the secondary PVC coil form inserts directly into this hole, securing the heavy vertical structure without external bracing.

iv. The primary helical coil sits directly on top of the enclosure surface, perfectly concentric with the secondary coil, ensuring correct electromagnetic coupling geometry at the base.

v. Internal Component Layout: The high-voltage MOT network, resonant tank capacitor bank, and spark gap assembly are securely mounted within the lower interior compartment of the wooden chassis.

II. Forced-Air Cooling and Ventilation System

Operating high-power components within a closed wooden shell introduces severe thermal risks. A dedicated active cooling network was integrated to manage thermal dissipation:

i. Fan Network: Four independent 12 V DC cooling fans are mounted directly into ventilated ports carved into the chassis walls.

ii. Targeted Cooling: Strategic placement routes airflow directly over the incandescent bulb ballast network (which generates significant resistive heat) and across the static spark gap (to prevent thermal electrode degradation and continuous air ionization). The remaining fans establish a continuous intake/exhaust loop for the inner chamber.

iii. Auxiliary Power Supply: The fans are energized via a dedicated 12 V DC power adapter. The AC input of this adapter is wired in parallel directly to the load side of the main MCB, ensuring the cooling system activates immediately when the system is main-powered.

III. Control Interface and Operational Procedure

To ensure maximum safety during public demonstration, the control interface separates system power from the high-voltage firing sequence via a dead-man style configuration:

i. The Firing Control Switch: A momentary push-button switch is wired in series on the 230 V AC line, positioned immediately prior to the bulb ballast network. The high-voltage primary circuit will only energize while this button is actively held down by the operator.

ii. Independent Cooling Behavior: Because the $12\text{ V}$ cooling adapter is wired directly to the MCB, the cooling fans run continuously regardless of whether the push button is pressed. This allows the fans to cool down the internal components even between active firing windows.

Standard Operating Protocol:

System Initialization: Engaging the primary Two-Pole MCB powers on the internal cooling fan array and prepares the system.

Activation Sequence: Pressing and holding the momentary push switch completes the primary circuit loop, initiating the spark gap arc and generating the high-frequency secondary discharge.

Deactivation Sequence: Releasing the push switch immediately terminates the high-voltage output. Toggling the MCB to the "OFF" position isolates the entire apparatus from the mains grid.
