# Changes

## Disclaimer

This section covers changes to the officially released rules for one or more of the following purposes:
 * Unanymous requests for changes from Team Leads that highlight issues that would prevent teams from competing.
 * Ammending rules to clarify the spirit of the rule. These changes should not impact any team's ability to compete.

Changes in this section are not yet in the official rulebook but overwrite existing rules. The latest revision of a rule change will take precedence over past rule changes.

## Update 2026_01_25

### Reason For Change
Categorie(s):
 * Ammending rules to clarify the spirit of the rule. These changes should not impact any team's ability to compete.

Purpose:
 * Components that are not intended to be removed frequently from the chassis should not use the weakest form of threadlocker to satisfy this rule. Threadlocker on these semi-permanently mounted components will help prevent loosening from vibration during operation.

### Rule(s) Changed

#### Mechanical > Mounting

```diff
-  1. Any component mounted directly to the chassis not mentioned already must be secured with a threadlocker.
+  1. Any component mounted directly to the chassis not mentioned already must be secured with a Medium Strength thread-locker.
      * Components that are needed to be removed and remounted frequently may be secured with a Positively Locking Nut.
      * Electrical wires must be secured with cable ties or similar items.
```

#### Mechanical > Weatherproofing

```diff
   1. All components mounted to the go-kart chassis that are not rated for exterior use must be contained within an IP65 Rated Container.
        Containers must use IP65 Rated grommets and fittings for cables and connectors.
        Containers must have ventilation.
   2. Examples of components that must be in weather-rated containers:
        Motor Controller (if not rated for external use)
        Batteries
        Computers
        Microcontrollers
        Breakout/Distribution Boards

+  3. External components that are rated for IP64 (or are generally seen as "weatherproof" without an IP certification) are also allowed.
+  4. Teams who have complications meeting Weatherproofing Requirements may use lower IP64 Ratings, however, there is still the expectations that barring severe weather all go-karts are able to operate.
```

#### Electrical > Batteries

```diff
-  7. Auxiliary Battery System Cannot exceed 50V nominal.
+  7. Auxiliary Battery System Cannot exceed Drivetrain (Primary) Battery System.
+    * The intent of the Auxiliary Battery System is to power auxiliary devices such as sensors, computers, and low-level control devices.
```

#### Safety > Required Safety Components

```diff
    Urgent Stop
        All teams must prove that they have a switch to trigger an Urgent Stop that has the go-kart come to a safe stop.
-           Urgent Stop must trigger if a controller leaves range or disconnects.
        Urgent Stop must be commandable through software
        Methods of stopping:
            Automatic stopping on Software Command or Physical Controller trigger.
            Switching to RC control to stop.
    Remote Estop must be tied to at minimum a physical controller.
        Off the shelf Emergency Stop systems are allowed as long as they do not interfere with the track and has a physical trigger.
        Remote Estop should initiate an Urgent Stop AND THEN Disconnect power to the Drivetrain.
+          The Go-kart should be able to re-power and be able to get back to driving without physical intervention.
+       Remote Estop must trigger if a controller leaves range or disconnects.
```

#### Safety > Required General Safety

```diff
+      3. Teams are not allowed to work on the Go-Kart while the Go-Kart is in the following states:
+          * Go-Kart has energized motors. An energized system is a system that has components powered on.
+          * Go-Kart is in Autonomous Mode.

```
