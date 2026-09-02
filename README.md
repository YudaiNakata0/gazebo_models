# gazebo_models
Object and world models for gazebo simulation.
## Models
- wall
  - simple wall (box)
- wall_hole
  - wall with holes
  - blue painted circle
  - wooden texture
  - two world files (vertical & inclined)
- wall_line
  - wall with a line
  - blue surface
- wall_curve
  - wall with a curve
  - blue surface
- wall_image
  - wall with photo
- exp_board
  - 300mm x 450mm x 5mm board
  - 40mm x 40mm colored patch at the center
## Notes
- Load world files in ros launch files
  - ```$(find gazebo_models)/worlds/{world type}.world```
- Set ```GAZEBO_MODEL_PATH``` path for searching model
  - ```export GAZEBO_MODEL_PATH=/home/user/catkin_ws/src/gazebo_models/models:$GAZEBO_MODEL_PATH```
