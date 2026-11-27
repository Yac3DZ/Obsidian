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
- [ ] when deleteing a door, its boolean cutout should be deleted as well
- [ ] use Float Boolean Solver, and extend the bottom cutout to avoid z fighting error in boolean



### Frame
- [ ] Plan frame structure
- [ ] Add frame types
- [ ] add round frame (not just arch frame)
- [ ]  rgrg

### Hinges
- [ ] Plan Hinges structure
- [ ] Add Hinges types

### Material
- [x] Add material grain
- [ ] ~~egeg~~