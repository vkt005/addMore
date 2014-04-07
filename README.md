<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"></head>
<body><pre style="word-wrap: break-word; white-space: pre-wrap;">
# Ad More Element

Sample code for adding more element at run time through javascript or cloaning html element with in the form or cloaning of any other html element 

This sample has throughly tested on all browser and running properly

## Usage

If you'd like to use the code in your own project, copy `admore.js` and include it.

    &lt;script src="/path/to/admore.js"&gt;&lt;/script&gt;
    

And then ad following code in your file 
.mulit-field-demo  // is element class which you want to repeat
 <script type="text/javascript">
           $(document).ready(function () {
                $(".mulit-field-demo").EnableAddMore({linkText: 'add more'});
            });
</script>

See `admore.js` for additional parameters you can include when initializing the EnableAddMore
</pre></body></html>