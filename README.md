creative commons license 

trebuie sa pui for la label input

# terminal-github  

    git add .
    git commit -m ""
    git push
    
# check contrast

    https://webaim.org/resources/contrastchecker/


# complementary colors

    https://www.canva.com/colors/color-wheel/


# operator
    
    count = count + 1
    count += 1
    count++    

# parameter

    variable of function

    ex: function hello(name) {}

    name is a parameter in example


# variables

    coming soon

# Display: none

    element disappears

# setAttribute

    getElement.setAttribute("name of attribute", "value of attribute")


#  <script>

        const color = document.getElementById("1").getAttribute("memocolor");
        console.log("color:", color);

        document.getElementById("1").setAttribute("style", "background-color: " + color + ";")
        
    </script>

    <div class="gap">
            <button memocolor="red" id="1" onclick="play(event)"></button>
    </div>

    function play(e) {

            e.target.removeAttribute("style");

    }
