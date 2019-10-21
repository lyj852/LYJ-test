
1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:	var h1 = document.getElementById("h1");
			var  an = "你好";
		    var  bn = "刘亚杰";
		    var  ab = an+bn;
            h1.innerHTML(ab);

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:          var str = "87";
		 	var nstr = str.padEnd(6,"0");
			console.log(nstr);
			 h2.innerHTML = nstr;

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:var h3 = document.getElementById("h3");
    	var num=2.1456;
        console.log(num.toFixed(2));;
        h3.innerHTML=num;

4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:<body>
			<h4 id="h4"></h4>
			<img  src="img/head/,icon/1.jpg" alt=""/>
		<script>
	   var h4 = document.getElementById('h4');
        var imgs = document.getElementsByTagName('img');
         var imgin = imgs[0].getAttribute('src');
         h4.innerHTML=imgin;
		</script>
	</body>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答: var h5 = document.getElementById('h5');	
		 var h5 = document.getElementById('h5');	
			 var num= "aBcd";
			 var a = prompt("请输入验证码（aBcd）");
			 var b  = num.toLowerCase();
			 var c = num.toUpperCase();
			 if(b==c){
			 	h5.innerHTML = b;
			 	else{
		 		alert("验证错误")
			 	}
			 }
