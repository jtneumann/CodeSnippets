function selectionSort(arr){
   
    for( var i = 0; i < arr.length; i++){
        var lowest = i;
        for(var j = i + 1; j < arr.length; j++){
            console.log(i,j);
            if(arr[j] < arr[lowest]){
                lowest = j;
            }
        }
        //outside j loop but inside i:
        if(i !== lowest){
                //swap
                var temp = arr[i];
                arr[i] = arr[lowest];
                arr[lowest] = temp;              
            }
    }//closes loops;
    return arr;
}



selectionSort([1,3,5,8,3,4,2,9,1,0])
