# Magni
## For zoomin all HTML document not just Images

**What is Magni:** Magni let you to zoom all html document **not just images**,  and it is a lens magnifier, something like  [this](http://h10025.www1.hp.com/ewfrf-JAVA/Doc/images/823/c03671284.jpg) that is on Windows, and it is a kind of lens magnifier [Why I made this](http://stackoverflow.com/questions/30070035/magnifier-for-html-document)
# [DEMO](http://www.balit.ir/magni)


**Magni** is so easy, download the **.js** file from [here](https://raw.githubusercontent.com/MohammadKermani/magni/master/magni.js), **Jquery** is requirement.

This is the magni function and argumants with description:
`$('element').magni(scale,width,height,lensType,color,borderSize,shadow);`

<ul>
		<li><b>scale:</b>scale is the size of the Zoom, and the default value of that is 2.</li>
	        <li><b>width:</b>width of the lens.</li>
	        <li><b>height:</b>height of the lens.</li>
	        <li><b>lensType:</b> This argumant accept <i>circle and default</i> value and change the lens type.</li>
	        <li><b>color:</b> will change the border color of lens, and accept <i>default,rgba(x,x,x,x), rgb(x,x,x)</i>. and any other ways that will use in CSS to setting color for an element. </li>
	        <li><b>borderSize:</b>its name is clear and you should just give a <i>number</i> or <i>default</i>.</li>
	        <li><b>shadow:</b> If you need the lens have a box-shadow you can give<i>yes</i> for shadow, if you don't need it give <i>no</i>.</li>
	</ul>

**Examples:**

`$('body').magni(2,200,200,'circle','rgba(125,125,125,0.5)',2,'no');`

`$('body').magni(4,200,200,'Circle','red',2,'yes');`
