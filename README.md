# Bread Layout
A layout designed to allow the user to Pinch and Pan the layout content to view its content in various manners.

# Usage
To utilize the layout, simply incorporate the namespace into the Xamarin Form XML file, and store the image
inside of the layout in the following manner:

```
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage ...
             xmlns:breadLayout="clr-namespace:BreadLayout;assembly=BreadLayout">

    <breadLayout:BreadLayout>
        <Image
            ... />
    </breadLayout:BreadLayout>

</ContentPage>
```
