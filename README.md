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

# Pull Requests
If you'd like to make an open-source contribution to this code base, you can submit a pull request for
me to review (NOTE: You cannot push code directly to the `main` branch).

# Issues & Inquiries
If you'd like to report a potential bug with this layout, or if you have suggestions for 
additional features you'd like to see from this layout, feel free to submit a GitHub Issue for 
me to address.
