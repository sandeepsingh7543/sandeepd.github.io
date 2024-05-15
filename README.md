
# Portfolio Website - Sandeep Singh

My portfolio displayed in a web page. 



## Technologies Used
- HTML5
- CSS3
- JavaScript
- SCSS


## Code Example

    // Moves the view to the starting of the page
    
    $("#navigation .brand a").click(function (e) {
	    e.preventDefault();
	    var targetElement = $(this).attr("href");
	    var targetPosition = $(targetElement).offset().top;
	    $("html,body").animate({ scrollTop: 0 }, "slow");
    });


## Credits

**©** **Sandeep Singh** | *2020*

