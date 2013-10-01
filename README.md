#Haml is HTML Abstraction Markup Language


###1. Install Haml (ruby gem)
<code>>> install gem haml</code>
<br>
<br>

###2. Convert Haml to HTML (command line)
<code>>> haml writteninhaml.haml writteninhtml.html</code>
####HTML Code
	<h1>Hello World</h1>
	<p class='name' id='first'>Jae</p>
	<p class='name' id='last'>Lee</p>
####Haml Code
	%h1 Hello World
	%p.name#first Jae
	%p.name#last Lee
<br>
###3. Refactoring HTML tags to Haml
<table>
    <tr>
        <td width="33%">HTML tags</td>
        <td width="33%">HTML class elements</td>
		<td width="33%">HTML id elements</td>
    </tr>
    <tr>
        <td style='color:red;'>%</td>
        <td style='color:red;'>.</td>
        <td style='color:red;'>#</td>
    </tr>
</table>
<br>
###4. Reference Links
- Haml Tutorial http://haml.info/tutorial.html

