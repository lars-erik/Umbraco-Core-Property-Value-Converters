# Umbraco Core Property Editor Converters v1 for Umbraco v6.2 #

For Umbraco v7.1+ please go to the [v2 branch](https://github.com/Jeavon/Umbraco-Core-Property-Value-Converters/tree/v2)

![](PropertyValueConverters.png)

This package currently implements converters for the following built-in Umbraco property editors

- [MNTP](docs/MNTP.md) - returns `IEnumerable<IPublishedContent>`
- [Ultimate Picker](docs/UltimatePicker.md) - returns `IEnumerable<IPublishedContent>` if Data Type setting "Type" is set to a multi node selector (e.g. CheckBoxList) or returns `IPublishedContent` if Data Type setting "Type" is set to a single node selector (e.g. DropDownList)
- [XPath CheckBoxList](docs/XPathCheckBoxList.md) - returns `IEnumerable<IPublishedContent>` (except if member, values setting should be set to "Node Ids"
- [XPath DropDownList](docs/XPathDropDownList.md) - returns `IPublishedContent` (except if member, value setting should be set to "Node Id")
- [Content Picker](docs/ContentPicker.md) - returns `IPublishedContent`
- [Media Picker](docs/MediaPicker.md) - returns `IPublishedContent`
- [Related Links](docs/RelatedLinks.md) - returns `RelatedLinksList`
- Multiple Textstring - returns `List<string>`