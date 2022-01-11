```js
<div id = 'bottom' onclick = 'bottom()'>Hide</div>
<div id = 'content' style = "display:block">Hi, My name is Tonny</div>

<script>
<!--定義function-->
function bottom(){
	var btn = document.getElementById('bottom');
	var con = document.getElementById('content');
    
    if(con.style.display === 'block'){   	
        con.style.display = 'none';
    	btn.innerText = 'Show';
    }
    else{
    	con.style.display = 'block';
    	btn.innerText = 'Hide';
    }

}
</script>
```
