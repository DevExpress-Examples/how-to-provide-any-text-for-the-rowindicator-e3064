# How to provide any text for the RowIndicator


<p>To provide any text for the RowIndicator, override the DataTemplate for "IconPresenterTemplate" resource key.<br /><br /></p>
<p><strong>Edited:<br /></strong>You can find a more detailed description of the approach in the following article: <a href="https://www.devexpress.com/Support/Center/p/ka18642">How to modify DX themes in Silverlight</a>.<br />Another approach is suggested in the following example: <a href="https://www.devexpress.com/Support/Center/p/E2803">How to Display Row Handles within Row Indicator Cells</a>. </p>


<h3>Description</h3>

<p>This data template defines a RowIndicator appearance. There is a <strong>CustomIndicatorText</strong> TextBlock containing a row number added to each row indicator in this example. Note that described template depends on seven icon templates, so it is necessary to override them too. Next, it is necessary to set this new template to TableViews <a href="http://documentation.devexpress.dev/#WPF/DevExpressXpfGridTableView_RowIndicatorContentTemplatetopic"><u>RowIndicatorContentTemplate</u></a> property. All templates listed above are placed in Generic resource dictionary.</p>

<br/>


