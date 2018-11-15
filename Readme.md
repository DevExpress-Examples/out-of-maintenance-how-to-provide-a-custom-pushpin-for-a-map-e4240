<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MapShape_Template/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MapShape_Template/MainWindow.xaml))
<!-- default file list end -->
# How to provide a custom pushpin for a map


<p>This example demonstrates  how to implement a custom pushpin using its template. <br />
</p>


<h3>Description</h3>

<p>To accomplish this, it is necessary to create a <strong>System.Windows.Controls.ControlTemplate</strong> that contains the <strong>StackPan</strong><strong>el</strong> with a custom pushpin image and TextBlock (specifies the pushpin title).</p>
<p>Then, add this data template to a window's resource and apply it to a map pushpin via the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfMapMapPushpin_Templatetopic"><u>MapPushpin.Template</u></a> property.</p>

<br/>


