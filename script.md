            document.getElementById("container"); //Question 1
            document.querySelector("container")   //Question 2    
            document.getElementsByClassName("second"); //Question 3
            document.getElementsByClassName("ol li.third");//Question 4  
            
            //Question 5
           /* let text = document.getElementsByClassName("container");
            text[0]= "Hello";
            text[1]= "Hello";
            text[2]= "Hello";  */

            //Question 6
            let element1 = document.getElementById("footer");
            element1.classList.add("main");

            //Question 7
            let element2 = document.getElementById("footer");
            element2.classList.remove("main");

            //Question 8
            let newDiv=document.createElement('li');
            //Question 9
            newDiv.innerHTML="four";
            //Question 10
            let ul=document.querySelector('ul');
                ul.appendChild(newDiv);

             //Question 12
            let ol = document.querySelector('ol')
            let items1 = ol.getElementsByTagName("li");
                for (let i = 0; i < items1.length; ++i) {
                     items1[i].style.backgroundColor="green";
                                    }      
