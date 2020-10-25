# Plan of the experiment

* **Scenes:**
  There are 20 photos in each scene, 10 without the mark and 10 with it.
  Order of photos matter; first 10 taken in a scene should not contain the mark,
  then next 10 should.
  Strict ordering of photos will enable us to sort their names and
  automatically label them with python (this assumes the camera numbers photos
  automatically, which is rather common).
  Each scene should consist of photos of the same place taken from different
  angles.
  Single scene should contain photos of the very same instance of the mark
  (single drawing of the mark).
  Marks on photos should be clearly visible.
  
  Some examples of scenes:
  
    * Take ten photos of a whiteboard without mark, then draw a mark on it and 
      take ten photos of it.
    
    * Take ten photos of a sidewalk, then draw a mark on it with chalk.
      Take ten photos of it.
    
    It is diserable to change colors of the mark between scenes.

* **Series**: There are 12 scenes in every series.
  A single series contains 12 * 20 = 240 photos.
  Series consist of scenes taken in the same environment and time of day.
  Series should be: 
    - One taken during day indoors with natural light.
    - One taken during nigh indoors with artificial (light bulb) light.
    - One taken during day outdoors.

* **Series per person**:
  A single experiment participant should take three series.
  That means single person takes 3 * 240 = 720 photos

* There are two participants in the experiment, which makes the dataset consist
  of 720 * 2 = 1440 photos.
