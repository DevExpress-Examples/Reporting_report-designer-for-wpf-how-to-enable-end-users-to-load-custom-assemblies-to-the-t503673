<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/EnableEFBrowseButton/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/EnableEFBrowseButton/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/EnableEFBrowseButton/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/EnableEFBrowseButton/MainWindow.xaml.vb))
* [UseDataSourceWizardSettings.xaml](./CS/EnableEFBrowseButton/UseDataSourceWizardSettings.xaml) (VB: [UseDataSourceWizardSettings.xaml](./VB/EnableEFBrowseButton/UseDataSourceWizardSettings.xaml))
* [UseDataSourceWizardSettings.xaml.cs](./CS/EnableEFBrowseButton/UseDataSourceWizardSettings.xaml.cs) (VB: [UseDataSourceWizardSettings.xaml.vb](./VB/EnableEFBrowseButton/UseDataSourceWizardSettings.xaml.vb))
* [UseEFOptionsAndCustomization.xaml](./CS/EnableEFBrowseButton/UseEFOptionsAndCustomization.xaml) (VB: [UseEFOptionsAndCustomization.xaml](./VB/EnableEFBrowseButton/UseEFOptionsAndCustomization.xaml))
* [UseEFOptionsAndCustomization.xaml.cs](./CS/EnableEFBrowseButton/UseEFOptionsAndCustomization.xaml.cs) (VB: [UseEFOptionsAndCustomization.xaml.vb](./VB/EnableEFBrowseButton/UseEFOptionsAndCustomization.xaml.vb))
<!-- default file list end -->
# Report Designer for WPF - How to enable end-users to load custom assemblies to the Entity Framework context


In the <a href="https://documentation.devexpress.com/#XtraReports/CustomDocument114851">Entity Framework Data Source wizard</a>, it is possible to load custom assemblies by using the Browse button on the <a href="https://documentation.devexpress.com/#XtraReports/CustomDocument114856">Select the Data Context</a> page.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/report-designer-for-wpf-how-to-enable-end-users-to-load-custom-assemblies-to-the-entity-fr-t503673/17.1.3+/media/4b00efec-2108-11e7-80bf-00155d62480c.png"><br>In the End-User Designer, this button is hidden by default, so that end-users are allowed only to select the data context from assemblies referenced by the project.<br><img src="https://raw.githubusercontent.com/DevExpress-Examples/report-designer-for-wpf-how-to-enable-end-users-to-load-custom-assemblies-to-the-entity-fr-t503673/17.1.3+/media/5cb8b6d5-2108-11e7-80bf-00155d62480c.png"><br>This example illustrates how to enable this functionality in the End-User Report Designer for WPF.<br>To learn more, see <a href="https://documentation.devexpress.com/#XtraReports/CustomDocument117318">Security Considerations</a>.

<br/>


