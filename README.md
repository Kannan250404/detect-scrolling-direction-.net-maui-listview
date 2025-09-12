**[View document in Syncfusion .NET MAUI Knowledge Base](https://www.syncfusion.com/kb/13575/how-to-detect-scrolling-direction-in-net-maui-listview-sflistview)**

## Sample

```xaml
<listView:SfListView x:Name="listView" ItemsSource="{Binding BookInfo}" ItemSize="120" IsStickyHeader="True">

    <listView:SfListView.ItemTemplate>
        <DataTemplate>
            <code>
            . . .
            . . .
            <code>
        </DataTemplate>
    </listView:SfListView.ItemTemplate>

    <listView:SfListView.HeaderTemplate>
        <DataTemplate>
            <code>
            . . .
            . . .
            <code>
        </DataTemplate>
    </listView:SfListView.HeaderTemplate>
</listView:SfListView>

C#:
scrollview.Scrolled += Scrollview_Scrolled;

private void Scrollview_Scrolled(object sender, ScrolledEventArgs e)
{
    if (e.ScrollY == 0)
        return;

    if (previousOffset >= e.ScrollY)
    {
        viewModel.ScrollDirection = "Up Direction";
    }
    else
    {
        viewModel.ScrollDirection = "Down Direction";
    }

    previousOffset = e.ScrollY;
}
```