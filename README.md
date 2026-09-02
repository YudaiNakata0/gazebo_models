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
  - 450mm x 600mm x 5mm white board
  - 40mm x 40mm black patch at the center
  - 10mm diameter white circle at the center of the patch
## Notes
- Load world files in ros launch files
  - ```$(find gazebo_models)/worlds/{world type}.world```
- Set ```GAZEBO_MODEL_PATH``` path for searching model
  - ```export GAZEBO_MODEL_PATH=/home/user/catkin_ws/src/gazebo_models/models:$GAZEBO_MODEL_PATH```
