
1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:	var h1 = document.getElementById("h1");
			var  an = "���";
		    var  bn = "���ǽ�";
		    var  ab = an+bn;
            h1.innerHTML(ab);

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:          var str = "87";
		 	var nstr = str.padEnd(6,"0");
			console.log(nstr);
			 h2.innerHTML = nstr;

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:var h3 = document.getElementById("h3");
    	var num=2.1456;
        console.log(num.toFixed(2));;
        h3.innerHTML=num;

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:<body>
			<h4 id="h4"></h4>
			<img  src="img/head/,icon/1.jpg" alt=""/>
		<script>
	   var h4 = document.getElementById('h4');
        var imgs = document.getElementsByTagName('img');
         var imgin = imgs[0].getAttribute('src');
         h4.innerHTML=imgin;
		</script>
	</body>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��: var h5 = document.getElementById('h5');	
		 var h5 = document.getElementById('h5');	
			 var num= "aBcd";
			 var a = prompt("��������֤�루aBcd��");
			 var b  = num.toLowerCase();
			 var c = num.toUpperCase();
			 if(b==c){
			 	h5.innerHTML = b;
			 	else{
		 		alert("��֤����")
			 	}
			 }
