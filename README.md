# Simulated Fragile Object (Virtual Egg)

## Project Description:

The Virtual Eggs Test (Clemente et al.,2015) was adapted from the Box and Blocks Test in order to evaluate the dexterity of sensory enabled prostheses. For their initial studies, origami boxes and spaghetti strands were used as their simulated fragile object (egg). This method of construction while informative, simple and cost effective has limitations for use outside of laboratory settings. For example, it would be potentially challenging for an individual with upper limb loss to construct or reset the aparatus without the presence of another individual which could impact engagement in 'in-the-wild' test scenarios.

In order to address this, this repo contains the [.stl](Assembly%20stls) and [technical drawings](Technical%20Drawings) for a passive and reusable egg design. The design can be altered to provide various levels of fragility, and can easily be reset and re-used with a single hand while requiring little to no manual dexterity.

The following section details the construction of the egg.

## Manufacturing and Assembly Instructions:

The egg consists of [6 main components](Technical%20Drawings/Assembly%20Drawings.pdf):
- **Shell:** The outer casing for the egg
- **Slide:** The sliding plates used to grasp the object
- **Midplate:** This is used as a back-board for the spring-loaded plates and combine with the Runner top ensure square travel.
- **GravLock:** Small pins used to lock the egg when too much force is applied (the egg is crushed) through gravity.
- **Runner:** Ensures square travel of the Slide throughout the range of motion.
- **Spring:** Provides a method of calibrating the fragility of the object, along with returning the Slide to it's original position.

### 1. Manufacture
The main structural components for the egg are 3D printed in PLA. The parts are designed with a low tolerance to ensure smooth travel, however some simple post-processing may be necessary for correct operation.

For each egg the printed parts list is:
- 2 x [**Shell**](Assembly%20stls/Shell.stl)
- 2 x [**Slide**](Assembly%20stls/Slide.stl)
- 1 x [**Midplate**](Assembly%20stls/Midplate.stl)

The remainder of the manufactured parts, are made from brass dowelling with a rounded end:
- 2 x **Runner** (⌀5.2mm)
- 4 x **GravLock** (⌀2mm)

The **Spring** should be a compression based spring, with an id > ⌀6mm, and an un-compressed length of ~30mm. The _k_-value of the **Spring** will determine the relative fragility of the egg and should be chosen with your experimental set-up in mind. 

### 2. Construction
    
1. Affix **Runner** to central extrusion of **Slide** using an epoxy adhesive.
2. Insert **GravLock** into each hole on the bottom of the **Slides**.
3. Insert **Slide** into **Shell** ensuring the **GravLocks** are facing the correct direction (rounded end down).
4. Lubricate the contact surfaces of the **Shell** and **Runner**.
    - Both _Super Lube Multipurpose Synthetic Grease_ and fibreglass tape have proven to be effective in isolation but combined for best results.
5. Slot your selected **Spring** over the **Runner**, and the other end over the extrusion on **Midplate**.
6. Align the edges and adhere the back surface of **Shell** against **Midplate** maintaining gentle pressure.
7. Repeat this process for the second side.


I hope this may be of use to someone, and if there are any questions or if anything about the process is unclear send me a message.
