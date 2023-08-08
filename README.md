# Bread Layout [![NuGet Version](https://img.shields.io/nuget/v/breadlayout)](https://www.nuget.org/packages/BreadLayout/) [![Downloads](https://img.shields.io/nuget/dt/breadlayout)](https://www.nuget.org/packages/BreadLayout/)
The Bread Layout is a Xamarin Forms layout that allows the user to pan and zoom into an 
image wrapped within the layout.

# Usage
To utilize the layout, simply incorporate the namespace into the Xamarin Form XML file, 
and store the image inside of the layout in the following manner:

```xml
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage ...
             xmlns:breadLayout="clr-namespace:BreadLayout;assembly=BreadLayout">

    <breadLayout:BreadLayout>
        <Image
            ... />
    </breadLayout:BreadLayout>

</ContentPage>
```
