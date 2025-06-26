Subject: Observations from BLDC Fan Sample Comparison (Cheap vs. Premium)

Hi Team,

Following up on the task to analyze the sample fans, here are the key observations after opening the 'Cheap' and 'Premium' BLDC fan samples:

**'Cheap' Fan Sample:**

*   **Motor:** 18 poles. The stator stamping appears to be made of CRC material, similar to our current non-BLDC fans.
*   **Rotor:** Uses a magnet ring instead of an outer ring.
*   **Winding:** Uses a lower gauge copper wire compared to the premium model.
*   **Winding Machine:** Verification needed if our existing winding machine can handle this gauge and configuration, or if a new one is required.
*   **PCB:** Model identified as IP-BFC-24F13. It seems similar to readily available options like this one: [https://m.indiamart.com/proddetail/bldc-fan-controller-pcb-2852996512030.html](https://m.indiamart.com/proddetail/bldc-fan-controller-pcb-2852996512030.html)
*   **Remote:** Standard RF remote.

**'Premium' Fan Sample:**

*   **Motor:** 12 poles (cores). The overall construction is significantly different from the cheap model and our existing fans.
*   **Winding:** Uses a higher gauge copper wire compared to the cheap model.
*   **Materials:** It appears we would need to source all new materials for this design (stamping, rotor, etc.).
*   **Remote:** Uses an IR (Infrared) remote, not RF. There's a sensor visible in the transparent top cover for the IR signal.
*   **PCB:** Specific model not noted, but distinct from the cheap version.

**Summary of Key Hardware Differences Noted:**

1.  **Stator/Poles:** Cheap (18-pole CRC), Premium (12-pole, different construction).
2.  **Rotor:** Cheap (Magnet Ring), Premium (Different construction).
3.  **Winding:** Different copper gauges used. Potential need for a new winding machine for the cheap model's configuration.
4.  **PCB:** Different PCBs and likely different controllers/components.
5.  **Remote:** Cheap (RF), Premium (IR).
6.  **Sourcing:** Premium model likely requires sourcing entirely new mechanical components.

These observations will be crucial for our "Make vs. Buy" decision regarding the PCBs and finalizing the mechanical designs.

Let's discuss these findings further.

Thanks,

Rohan