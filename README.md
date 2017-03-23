<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
		<meta name="viewport" content="width=device-width,initial-scale=1 user-scalable=0">
		<style type="text/css">
			.distinguish{
				border:1px solid #eee;
				width:80%;
				height:auto;
				text-align: center;
			}
			
			.upload {
				border:1px solid #eee;
			    padding: 4px 10px;
			    height: 20px;
			    line-height: 20px;
			    position: relative;
			    cursor: pointer;
			    color: #888;
			    background: #fafafa;
			    border: 1px solid #ddd;
			    border-radius: 4px;
			    overflow: hidden;
			    display: inline-block;
			    *display: inline;
			    *zoom: 1
			}

			.upload  input {
			    position: absolute;
			    font-size: 100px;
			    right: 0;
			    top: 0;
			    opacity: 0;
			    filter: alpha(opacity=0);
			    cursor: pointer
			}

			.upload:hover {
			    color: #444;
			    background: #eee;
			    border-color: #ccc;
			    text-decoration: none
			}
		</style>
	</head>
	<body>
		<h4>图片上传</h4>
		<div class="upload">
			<input type="file" accept="image/*;capture=camera">选择
		</div>
		<p>识别结果</p>
		<div class="distinguish">
			<img src="img/loading.gif" />
		</div>
	</body>
</html>
