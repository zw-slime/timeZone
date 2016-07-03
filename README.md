# timeZone
用于显示时间插件；

使用方法：
   <div id="timeZone">
		  	    
		  </div>

<script type="text/javascript">
var times=[  {"name":"王强强","time":"05/30 18:00"},
		   				{"name":"王强强1","time":"05/30 18:01"},
		   				{"name":"王强强2","time":"05/30 18:03"},
		   				{"name":"王强强","time":"05/30 18:04"},
		   				{"name":"王强强1","time":"05/30 18:05"},
		   				{"name":"王强强2","time":"05/30 18:06"},
		   				{"name":"王强强","time":"05/30 18:07"},
		   				{"name":"王强强1","time":"05/30 18:08"},
		   				{"name":"王强强2","time":"05/30 18:09"},
		   				{"name":"王强强","time":"05/30 18:10"},
		   				{"name":"王强强1","time":"05/30 18:11"},
		   				{"name":"王强强2","time":"05/30 18:12"},
		   				{"name":"王强强","time":"05/30 18:13"}
	   				]
		
		
			$("#timeZone").timeZone({
				width:800,
				src:"",
				data:times
			});
 </script>
