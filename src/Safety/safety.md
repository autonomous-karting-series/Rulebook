<!-- omit in toc -->
# Safety Rules

- [General Safety](#general-safety)
- [Fire Safety](#fire-safety)
- [Required Safety Components](#required-safety-components)
- [Remote Control](#remote-control)
- [Enforcement](#enforcement)
- [Resources](#resources)
  - [Bodywork](#bodywork)
  - [Long Range Control (Including Remote EStop)](#long-range-control-including-remote-estop)

## General Safety

   1. Teams are not permitted on track while Go-Karts are running.
      * If a team needs to retrieve a Go-Kart then the team must wait for all Go-Karts to stop on track and the team has been given approval from race officials.
   2. Teams are expected to be able to operate their go-karts completely remotely to reduce risk of on-track interventions.
      * Expected Remote Operations Include:
        * Resetting/Restarting Systems.
      * _Read As: Teams are encouraged to reduce the need for manual resetting of anything on the go-karts_

## Fire Safety

  1. All teams must have at minimum 2 fire extinguishers.
     * Fire Extinguishers must be rated for the type of batteries a team is using.
     * If a team is using a combination of battery compositions then the team must have extinguishers for each type of battery.
  2. Examples of Fire Supression allowed:
     1. Lead-Acid Batteries:
        * Cat Litter
        * Sand
        * Class ABC Fire Extinguisher
     2. Lithium Batteries:
        * Class D Fire Extinguisher
        * Specialized Lithium Extinguisher - [E-FireX *not affiliated*](https://efirex.com/product/e-firex-fire-extinguisher-2-liter/)

## Required Safety Components

 1. Urgent Stop
    * All teams must prove that they have a switch to trigger an Urgent Stop that has the go-kart come to a safe stop.
      * Urgent Stop must trigger if a controller leaves range or disconnects.
    * Urgent Stop must be commandable through software
    * Methods of stopping:
      * Automatic stopping on Software Command or Physical Controller trigger.
      * Switching to RC control to stop.
 2. __Remote Estop__ must be tied to at minimum a physical controller.
    1. Off the shelf Emergency Stop systems are allowed as long as they do not interfere with the track and has a physical trigger.
    2. __Remote Estop__ should initiate an Urgent Stop AND Disconnect power to the __Drivetrain__.
 3. __Physical Estop__ that is clearly labelled and cuts all power to the kart.
    * Physical switch must exist on go-kart to disconnect ALL power on the go-kart
      * Minimum of 1 switch, if there are multiple switches then any 1 switch must disconnect all power.
      * Must be a Push-Button style Emergency Stop Switch.
      * Can be remote controlled --not required
    * Team must explain all kill-switches in inspection
 4. Moving Commponents must have covers to prevent risk of injury or damage.
    * Chains must have chain covers.
 5. There must be no exposed sharp edges on the kart.
 6. Front and Rear bumpers are required.
    * Bumpers cannot be custom made and must be purchased.

## Remote Control

 1. Complete Remote Control is required.
    * Teams must be able to control the go-kart from their pit area regardless of go-kart position on the track.
    * Remote Control encompasses the following actions:
      * Triggering Safety Systems
      * RC Driving
      * Switchting between RC and Autonomous modes.
 2. The __Remote Estop__ controller is required to reach at minimum 200 meters line of sight to the kart.

## Enforcement

 1. Before a kart is allowed to run on the track it must undergo safety inspections and comply with all rules set forth in this document.
    1. Team Safety Officers must be present for that team's inspection.
 2. Inspections may consist of the following:
    1. Visual inspections.
    2. Physical inspections.
    3. Document inspections.

## Resources

__The following resources are not affiliated with Autonomous Karting Series Inc. but are included to aid teams in finding and sourcing components.__

### Bodywork
 * [Front Noses - Comet Kart](https://cometkartsales.com/Front-Nose/)
 * [Rear Bumpers - Comet Kart](https://cometkartsales.com/Rear-Plastic-Bumpers/)

### Long Range Control (Including Remote EStop)
 * [Crossfire Betaflight Article](https://oscarliang.com/crossfire-betaflight/) - Describes a solution for how to achieve long distance communication utilizing a 900MHz frequency.
 * [FrSky R9M Solution](https://oscarliang.com/setup-r9m-r9-mini-betaflight/) - Describes a solution utilizing used LoRa 900MHz frequency to achieve long distance.
 * [Kar-Tech Wireless Estop System](https://kar-tech.com/wireless-estop-system-multiple-receiver.html) - Off the shelf solution for Remote Estop.
 * [Radiomaster Pocket Radio Controller - ELRS](https://radiomasterrc.com/products/pocket-radio-controller-m2) - RadioMaster RC Controller with long-range capabilities
 * [Radiomaster RP4TD ExpressLRS](https://radiomasterrc.com/products/rp4td-expresslrs-2-4ghz-diversity-receiver) - RadioMaster RC Receiver with long-range capabilities