var array=[1,2,3,4,5,6];
var size=array.length;
for(var i=0;i<(size/2);i++) {
    var temp=array[i];
    array[i]=array[size-i-1];
    array[size-i-1]=temp;
}

console.log(array);
