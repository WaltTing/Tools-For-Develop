# OJ之JavaScript篇

JavaScript在V8环境和Nodejs环境会有不同的输入输出语句；比如在Webstorm中可以配置js的Node环境。

另外，因为JS是门灵活的语言。不用根据输入数据的类型去分别写输入输出语句，而是接收数据后自行处理。

样例输入：

> 输出a+b的值。

## 1.V8环境

	while(line=readline()){
	     var lines = line.split(' ');   //输入的数据其实是当字符串来处理的，需要首先转换成字符数组
		 var a = parseInt(lines[0]);    
		 var b = parseInt(lines[1]);     
		 print(a+b); 
	}

## 2.Node环境

	var readline = require('readline');
	
	const rl = readline.createInterface({ 
		input: process.stdin, 
		output: process.stdout 
	}); 
	
	rl.on('line', function(line){ 
		var tokens = line.split(' '); 
		console.log(parseInt(tokens[0]) + parseInt(tokens[1])); 
	});

