# How-to-wrap-text-in-.NET-MAUI-CheckBox
This repository contains a sample demonstrating of wrapping text using LineBreakMode property in .NET MAUI CheckBox.

## LineBreakMode support in .NET MAUI CheckBox (SfCheckBox)
The LineBreakMode Support feature enables flexible text truncation and wrapping options within user interface components, enhancing readability and presentation. It facilitates various modes like WordWrap, CharacterWrap, MiddleTruncation, etc., accommodating diverse layout requirements efficiently.

The following code example illustrate how to set LineBreakMode in SfCheckBox.

**XAML**
```
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="WordWrap"/>
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="CharacterWrap"/>
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="HeadTruncation"/>
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="MiddleTruncation"/>
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="TailTruncation"/>
  <syncfusion:SfCheckBox Text="By clicking here, I state that I have read and understood the terms and conditions." LineBreakMode="NoWrap"/>

```

**C#**
```
   SfCheckBox  sfCheckBox  = new SfCheckBox();
   sfCheckBox.Text = "By clicking here, I state that I have read and understood the terms and       conditions.";
   sfCheckBox.LineBreakMode = LineBreakMode.WordWrap; 

```