<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/GridMVVMSelection/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/GridMVVMSelection/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/GridMVVMSelection/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/GridMVVMSelection/MainWindow.xaml.vb))
* [ViewModel.cs](./CS/GridMVVMSelection/ViewModel.cs) (VB: [ViewModel.vb](./VB/GridMVVMSelection/ViewModel.vb))
<!-- default file list end -->
# MVVM - How to bind the GridControl's selected rows to a property in a ViewModel


<p>This example demonstrates how to bind GridControl's selected rows to a property in ViewModel in a MVVM-based application. The SelectionAttachedBehavior helper class used in this sample, provides a bindable SelectedItemsSource property, that can be used to define selection at the ViewModel level.</p>
<p><strong>Note</strong>, we made the SelectionAttachedBehavior class as generic as possible, and the same approach can also be used for other controls that support multiple selection. This example demonstrates how this can be done when working with the standard ListBox control, as well as with the standard DataGrid.</p>

<br/>


