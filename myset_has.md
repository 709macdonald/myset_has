//# myset_has

var myset_has = [1, 2, 3, 4, 5];
var number = 4;

function has(array,data){
  var index = array.indexOf(data);
  if (index > -1){
    console.log("True")
}
  else {
    console.log("False")
  }

}

has(myset_has, number);
