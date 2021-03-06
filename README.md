# Charts.WPF
Modern UI Charts for WPF.

```csharp
Install-Package Charts.WPF -Version 1.0.0
```

# Release Notes:
Fork of http://modernuicharts.codeplex.com/

Code ported to C#6. General bug fixes and optimizations for the newest .NET frameworks.

### Screenshots

![Light Theme](https://github.com/mendonca-andre/Charts.WPF/blob/master/Screenshots/light.png)

![Dark Theme](https://github.com/mendonca-andre/Charts.WPF/blob/master/Screenshots/dark.png)

### Examples

```csharp
public class TestClass
{
    public string Category { get; set; }
    public int Number  { get; set; }
}

<chart:ChartSeries
    SeriesTitle="Errors"
    DisplayMember="Category"
    ValueMember="Number"    
    ItemsSource="{Binding Path=Errors}" />
```
  
