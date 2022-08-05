# invert

function invert(array) {
  for (var i = 0; i < array.length; i++){
    array[i] *= -1;
  }
   return array;
}


# getVolumeOfCuboid
class Kata {
  static getVolumeOfCuboid(length, width, height) {
    // your code here
    return length * width * height;
  }
}
