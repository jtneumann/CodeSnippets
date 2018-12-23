function nonidealStringSearch(string, pattern){
    var count = 0;
    for(var i = 0; i < string.length; i++){
        for(var j = 0; j < pattern.length; j++){
//              console.log(pattern[j],string[i + j]);
            if(pattern[j] !== string[i + j]) break;
            if( j === pattern.length -1) count++;         
        }
    }
    return count;
}

nonidealStringSearch("What hat am I missing?", "hat");