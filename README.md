// How old will I be in 2099?
function  calculateAge(firstYear, secondYear) {
  
// enter your code here.
  var firstYear;
  var secondYear;
  
  if (firstYear == secondYear){
    return "You were born this very year!";
  }
  
  if (firstYear > secondYear){
    if (firstYear - secondYear == 1){
      return "You will be born in 1 year.";
    }
    
    else{
      return "You will be born in " + (firstYear - secondYear) + " years.";
    }
    
  }
  
  
  else{
    if (secondYear - firstYear == 1){
      return "You are 1 year old.";
    }
    
    else{
      return "You are " + (secondYear - firstYear) + " years old.";
    }
    
  }

}








