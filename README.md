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

# Basic Mathematical Operations
function basicOp(operation, value1, value2)
{
  
  if (operation == "+"){
    return value1 + value2;
  }
  
  if (operation == "-"){
    return value1 - value2;
  }
  
  if (operation == "*"){
    return value1 * value2;
  }
  
  if (operation == "/"){
    
