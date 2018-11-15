<!-- default file list -->
*Files to look at*:

* [BBCExporter.cs](./CS/BBCExporter.cs) (VB: [BBCExporter.vb](./VB/BBCExporter.vb))
* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [Program.cs](./CS/Program.cs) (VB: [Program.vb](./VB/Program.vb))
<!-- default file list end -->
# How to create a custom exporter for a specific format


<p>This example illustrates how to create and register a custom DocumentModelExporter for a <a href="http://www.bbcode.org/"><u>BBCode</u></a> format. It supports a number of basic BBCode tags (including hyperlinks and images). The major export functionality is implemented in overridden Export* methods of the <strong>BBCodeExporter</strong> class.</p>

<br/>


