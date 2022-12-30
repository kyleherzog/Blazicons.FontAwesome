# Blazicons.FontAwesome
Provides the Font Awesome icon library packaged as [Blazicons](https://github.com/kyleherzog/Blazicons), SVG icon components for Blazor.

Check out the [Demo Site](http://blazicons.com).

[![Build Status](https://dev.azure.com/kyleherzog/Blazicons/_apis/build/status/Blazicons.FontAwesome?branchName=main)](https://dev.azure.com/kyleherzog/Blazicons/_build/latest?definitionId=19&branchName=main)

## Getting Started
To get started using the Font Awesome Blazicons, just install the Blazicons.FontAwesome NuGet package.

Next add the Blazicons reference to the `_Imports.razor` file in the Blazor project.

```csharp
@using Blazicons
```

Finally, add the Blazicon components to your Blazor pages/components.
```html
<Blazicon Svg="FontAwesomeRegularIcon.Calendar"></Blazicon>
<Blazicon Svg="FontAwesomeSolidIcon.Baseball"></Blazicon>
```

## Parameters & Styling
See the [Blazicons](https://github.com/kyleherzog/Blazicons) documentation for details on parameters and styling.