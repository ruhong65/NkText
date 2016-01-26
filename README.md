# Nktext
it's a plug that uses jquery& canvas. it can help you transform a normal text into particle, at the same time, it also provides different data for arrangement

# How to use

To get started, download the plugin, unzip it and copy files to your website/application directory. Load files in the section of your HTML document. Make sure you also add the jQuery library.

        <head>
            <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7/jquery.min.js"></script>
            <link rel="stylesheet" href="css/normalize.css">
	        <script src="js/NkText.js"></script>
	    </head>

Create your canvas add a class:
        <canvas class="canvas"></canvas>

Initialise the script like this:

        $(document).ready(function(){
            $('.canvas').NkText({
                    text:'red|splash'
            });
        })

May also be passed an optional options object which will extend the default values. Example:
        
        $(document).ready(function(){
			$('.canvas').NkText({
				text:'red|splash',
				fontPer:0.4,
				color:'#FF1CAE',
				spaces:3000,
				removeInput:true,
				loop:true
			});
		})
		
#Bug tracker

Have a bug? Please create an issue on GitHub at https://github.com/ruhong65/NkText/issues

	
