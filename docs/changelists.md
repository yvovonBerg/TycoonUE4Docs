# Changelists

## 1.2.0

->  New: Added button to convert the entire track to spline meshes, you can now edit the track using the spline directly! Still experimental. (You might have to tweak the length slider in tight corners)
->  New: Added spline length slider -> You can now adjust the length of each spline mesh.
->  New: Refactored the attachment system to use the spline directly as well, makes it much easier to update.
->  New: Changed the TycoonAnimation plugin to work based on distance on the spline vs just the points.

Bugfixes:
->  Fixed slow response on bend slider.
->  Fixed crash when spline component had been removed

## 1.1.0

-> Tycoon Animation hotfix: Resolved editor crashing when active train is not set in blueprints.

-> Tycoon hotfix: Resolved issue where the track would disappear after saving the map.

-> Tycoon hotfix: Resolved issue where the materials / textures were not visible after saving/loading maps.
