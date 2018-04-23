# How to provide a custom pushpin for a map


<p>This example demonstrates  how to implement a custom pushpin using its template. <br />
</p>


<h3>Description</h3>

<p>To accomplish this,  it is necessary to create a <strong>System.Windows.DataTemplate</strong> that contains the StackPanel with a custom pushpin image and TextBlock (specifies the pushpin title). </p><p>Then, add this data template to a window&#39;s resource and apply it to a map pushpin via the <strong>MapPushpin.Template</strong> property.</p>

<br/>


