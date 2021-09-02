<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128569024/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T172018)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/FullStackedSplineAreaChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/FullStackedSplineAreaChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Full-Stacked Spline Area Chart

The following example demonstrates how to create a [2D Full-Stacked Spline Area](https://docs.devexpress.com/WPF/17678/controls-and-libraries/charts-suite/chart-control/fundamentals/series-fundamentals/2d-series-types/area-series/full-stacked-spline-area?p=netframework) chart. To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add four [SplineAreaFullStackedSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.SplineAreaFullStackedSeries2D?p=netframework) objects with points to the diagram's [Diagram.Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection.

Also, this example shows how to display series labels on a diagram, customize labels pattern and add a [legend](https://docs.devexpress.com/WPF/6343/controls-and-libraries/charts-suite/chart-control/chart-elements/legends?p=netframework) (showing series names) to a chart.
