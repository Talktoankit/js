# js
js Append child function 

        var target = document.getElementById("list1").children[2];
        var copyElement = target.cloneNode(true);
        //console.log(copyElement);
        document.getElementById("list2").appendChild(copyElement);
    
