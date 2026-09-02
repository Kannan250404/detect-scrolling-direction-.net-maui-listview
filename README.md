# How to detect scrolling direction in .NET MAUI ListView(SfListView)?

Detect the scrolling direction in [.NET MAUI ListView](https://www.syncfusion.com/maui-controls/maui-listview) by using the **Scrolled** event of
the [ListViewScrollView](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.ListView.ListViewScrollView.html).

**Steps**

1.In the [SfListView.HeaderTemplate](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.ListView.SfListView.html#Syncfusion_Maui_ListView_SfListView_HeaderTemplate), bind the ViewModel property to show the scroll direction.

2.Get
the **ListViewScrollView** by using the [ListView.GetScrollView](https://help.syncfusion.com/cr/maui/Syncfusion.Maui.ListView.Helpers.SfListViewHelper.html#Syncfusion_Maui_ListView_Helpers_SfListViewHelper_GetScrollView_Syncfusion_Maui_ListView_SfListView_) helper method and update the **ScrollDirection** value based on the previous offset.
![Detect scroll direction in .NET MAUI ListView (SfListView)](https://www.syncfusion.com/uploads/user/kb/maui/maui-2240/maui-2240_img1.gif)

Download the complete sample on [GitHub](https://github.com/SyncfusionExamples/detect-scrolling-direction-.net-maui-listview)

**Conclusion**

I hope you enjoyed learning how to
detect the scrolling direction in .NET MAUI ListView.

You can refer to our [.NET MAUI ListView feature tour](https://www.syncfusion.com/maui-controls/maui-listview) page to learn about its other groundbreaking feature
representations. Explore our [documentation](https://help.syncfusion.com/maui/listview/getting-started) to understand how to create
and manipulate data.

For current customers, check out our components from the [License and Downloads](https://www.syncfusion.com/sales/teamlicense) page. If you are new to Syncfusion®, try our 30-day [free trial](https://www.syncfusion.com/downloads/maui)to check out our other controls.

Please let us know in the comments section below if you have any queries or require clarification. Contact us through our [support
forums](https://www.syncfusion.com/forums), [Direct-Trac](https://support.syncfusion.com/create), or [feedback portal.](https://www.syncfusion.com/feedback/maui?control=sflistview) We are always happy to assist you!
