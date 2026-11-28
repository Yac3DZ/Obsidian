#### Dynamic inside panels system
- create a dynamic inside panel system so you can use it to create multiple presets from it.
- it will contain two types horizontal or vertical, to make it less complicated.
- for the complicated ones we have to use separate geo nodes.

# todo

- [ ] create the logic for the simple grid system
- [x] add option to switch between horizontal and vertical
- [ ] Add option for mid Curve / Arch
- [ ] Add option for bottom Curve / Arch
- [ ] implement some presets.
- [x] Find a way to make the space between vertices is dependent on sin wave
- [ ] add advanced option for arch/curve controls, like making it for each column or combined.
- [ ] fix the mid mulls gap issue when having one column
- [ ] fix wood material in the inside.
- [x] find a way to rotate the door without breaking the material texture object coordinates.
- [ ] Improve UI for top bottom mid arch/ curve
- [ ] Add more options for round panel type
- [ ] Fix round panel radius option, when having left and right options to full radius.
- [x]  add option for round top and arched top door and frame using boolean

- [x] make a node setup that unifies the profile dimensions - using Bounding box
- [x] fix shading of the profile
- [x] find a way to set grain direction for the profile

- [ ] Add  **Offset Mid Rail** option
- [ ] Add **Offset Mid Mull** option

- [ ]Add **Bake** option to speed animation
- [x] Fix Groove Bug on the edges (depends on width)


### Door Addon
- [x] Implement Twinmotion like drage and drop door to fit exactly where the opening is
- [x] Drage drop onto a wall adds boolean and cuts out where the door should be
- [x] when deleteing a door, its boolean cutout should be deleted as well
- [x] use Float Boolean Solver, and extend the bottom cutout to avoid z fighting error in boolean
User Recomendation: ==Make sure the wall is clear from edges to make the boolean work correctly==
- [ ] Add option to flip the door when placing it
- [ ] Remove unnessecary options
- [ ] implement the fourth option "round top"


### Door Handle
- build a dynamic door handle system, it consists of 2 main parts:
      1. Outside: Consist of Door handle
      2. Inside: Consists of Latch

- [ ] Add three categoeries of door handle 10 from each category: Knob, Bar, handle
- [ ] Add Hinges types

### Frame
- [x] Plan frame structure  : It will consist of base frame and two covers from the inside and outside
- [x] Add frame Shape:  **Arch, Round Corner, Rectangle ** and **Round**
- [x] add round frame (not just arch frame)
- [ ] Add a functional Base Frame
- [ ] Add outer frame cover with profile design options
- [ ] Add frame Design:
      1. Profile Frame
      2. Classic 1 on 2
      3. Simple 1 between 2
- [ ] Add Frame Topes:
![[Screenshot-2026-11-28-010742.png|425]]

### Hinges
- [ ] Plan Hinges structure
- [ ] Add Hinges types

### Material
- [x] Add material grain