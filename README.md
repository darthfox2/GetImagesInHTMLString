# GetImagesInHTMLString
A simple function to decompose the attributes of IMG TAG from HTML.

example:
<div>
<h1 style='font-size: 45px'><font color='#006b19'>1.Chapter One</font></h1><h2 style='font-size: 35px'><font color='#006b19'>1.1 Article structure</font></h2><h4>標題</h4>
<p>&nbsp;</p>
<p>當要轉換大量的XXXXXXXXXX與編輯。</p>
<p>&nbsp;</p>
<p>PDFXXXX轉換器的「<strong>從</strong><strong>PDF</strong><strong>轉換</strong>」模式是用來轉換PDF檔案為MS Office Word、Excel、PowerPoint、文字和影像格式。XXXXXXX輸出檔案型式以及為結果檔案配置轉換設定。</p>
<p>&nbsp;</p>
<p style="text-align:center"><img alt="test" height="796" src="http://XXXXXX/Uploads/637853724038168071.png" width="997" /></p>
<ol style="list-style-type: upper-alpha;">
	<li style="text-align: left;"><span style="background-color:#ffffff;">支援的格式</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">切換到「</span><strong><span style="background-color:#ffffff;">轉換為</span></strong><strong><span style="background-color:#ffffff;">PDF</span></strong><span style="background-color:#ffffff;">」模式，以便從其他格式建立PDF</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">檔案佇列（或檔案清單）</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">開始轉換</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">檢視轉換紀錄</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">輸出路徑</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">轉換設定</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">選擇輸出格式</span></li>
	<li style="text-align: left;"><span style="background-color:#ffffff;">支援</span></li>
</ol><br/><br/><br/><br/><br/>
</div>

Result:
List<HtmlImageList>.First().Src = http://XXXXXX/Uploads/637853724038168071.png
List<HtmlImageList>.First().Alt = test
List<HtmlImageList>.First().Width = 997
List<HtmlImageList>.First().Height = 796
