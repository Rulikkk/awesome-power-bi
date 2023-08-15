# Awesome Power BI!

[![Join the chat at https://gitter.im/awesome-power-bi](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/awesome-power-bi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> A collection of awesome [Power BI](#general) frameworks, libraries, tools, resources, and software. This project is envisioned, designed and maintained by [Akvelon](https://akvelon.com) volunteer development team. If You would like Akvelon to develop a Power BI dashboard or custom visual, please, contact me via `rustem.mustafin [at] akvelon.com` or twitter: [@Rulikkk](https://twitter.com/rulikkk) or check out [visuals we've developed](#visuals-developed-by-akvelon).

Inspired by [awesome](https://github.com/sindresorhus/awesome), [awesome-dotnet](https://github.com/quozd/awesome-dotnet),  [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs), [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Contributions are always welcome!

Thanks to all [contributors](https://github.com/rulikkk/awesome-power-bi/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

## Contents

* [General](#general)
    - [Apps](#apps)
    - [Official Pages](#official-pages)
* [Development](#development)
    - [Custom Visuals Development](#custom-visuals-development)
    - [Utils](#utils)
    - [Connectors](#connectors)
    - [Other Development Resources](#other-development-resources)
    - [Leaders](#leaders)
* [Visuals](#visuals)
    - **[Visuals Developed by Akvelon](#visuals-developed-by-akvelon)**
    - [MS Open-Source Visuals](#ms-open-source-visuals)
    - [Power BI in AppSource](#power-bi-in-appsource)
* [Courses](#courses)
* [Communities](#communities)
* [Tutorials](#tutorials)

## General

### Apps

* [Power BI Web App](https://app.powerbi.com/)
* [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
* [Power BI iOS App](https://itunes.apple.com/app/microsoft-power-bi/id929738808)
* [Power BI Android App](https://play.google.com/store/apps/details?id=com.microsoft.powerbim)
* [Power BI Windows 10 App](https://www.microsoft.com/store/p/power-bi-mobile/9nblgggzlxn1) — Includes mixed reality capabilities for HoloLens!

### Official Pages

* [Power BI Homepage](https://powerbi.microsoft.com/) — The official homepage of Power BI by Microsoft.
* [Power BI User Documentation](https://docs.microsoft.com/power-bi/) — The official Power BI user documentation by Microsoft.
* [Power BI YouTube Channel](https://www.youtube.com/user/mspowerbi) — The official Power BI YouTube channel.
* [Power BI Twitter](https://twitter.com/mspowerbi) — Power BI official twitter.

## Development

This chapter covers topics related to building custom visuals and other ways to develop with Power BI. You can also check visuals [developed by Akvelon](#visuals-developed-by-akvelon) and [by Microsoft](#ms-open-source-visuals), which are open-source and serve as good samples of how to implement a custom visual.

### Custom Visuals Development

* [Power BI Visuals](https://docs.microsoft.com/en-us/power-bi/developer/visuals/custom-visual-develop-tutorial) — A step-by-step tutorial of developing your first Power BI visual by Microsoft.

### Utils

Power BI utils are set of tools that allow developer of Power BI visual to easily implement most common capabilities of visualizations.

* [DataViewUtils](https://github.com/Microsoft/powerbi-visuals-utils-dataviewutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-dataviewutils)) — provides set of tools to parse DataView object;
* [ChartUtils](https://github.com/Microsoft/powerbi-visuals-utils-chartutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-chartutils)) — helps to create chart axes and drawing labels;
* [ColorUtils](https://github.com/Microsoft/powerbi-visuals-utils-colorutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-colorutils)) — manages color manipulations;
* [TooltipUtils](https://github.com/Microsoft/powerbi-visuals-utils-tooltiputils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-tooltiputils)) — simplifies usage of the Tooltip API;
* [TypeUtils](https://github.com/Microsoft/powerbi-visuals-utils-typeutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-typeutils)) — extends the basic types of Power BI custom visuals;
* [InteractivityUtils](https://github.com/Microsoft/powerbi-visuals-utils-interactivityutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-interactivityutils)) — helps to implement cross-selection and cross-filtering;
* [FormattingUtils](https://github.com/Microsoft/powerbi-visuals-utils-formattingutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-formattingutils)) — provides functionality to format values;
* [SVGUtils](https://github.com/Microsoft/powerbi-visuals-utils-svgutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-svgutils)) — simplifies SVG manipulations;
* [TestUtils](https://github.com/Microsoft/powerbi-visuals-utils-testutils) ([npm](https://www.npmjs.com/package/powerbi-visuals-utils-testutils)) — provides set of mocks and fakes in order to simplify creating unit tests for custom visuals.

### Connectors

Power BI connectors and other tools that allow you to connect to various data sources.

* [SSASQueryProxy](https://github.com/jmarsik/SSASQueryProxy) - simple proxy for getting MDX query results from Analysis Services (SSAS) instance accessed by using MSMDPUMP HTTP interface to Power BI Desktop / Service WITH support for scheduled refresh

### Other Development Resources

* [Power BI for Developers Overview](https://docs.microsoft.com/en-us/power-bi/developer/overview-of-power-bi-rest-api) — Answer to "What can developers do with Power BI?" question and a good starting point for developing with Power BI.
* [Power BI and R](https://www.blue-granite.com/tutorials/power-bi-and-r) — Video-tutorial about Power BI and R, including R Scripts and R Visuals.
* [Power BI C#](https://github.com/Microsoft/PowerBI-CSharp) — .NET developer community for Power BI.
* [Power BI Javascript](https://github.com/Microsoft/PowerBI-JavaScript) — JavaScript library for embedding Power BI into your apps.
* [Charticulator](https://charticulator.com/) enables you to create bespoke and reusable chart layouts without writing any code. The constructor allows to export chart as Power BI visual.

### Leaders

#### Independent powerBI technology leaders

* <a id="kerry-kolosko">Kerry Kolosko</a>. A passionate data visualization enthusiast from Australia, actively engaged in PowerBI community. Here is an example of her review of [PlotlyJS custom visual](https://www.youtube.com/watch?v=ckJRvHVQPJk&ab_channel=HavensConsulting) which was created by the Akvelon team. If you're interested in her work, you can find a collection of her own data visualization templates on her [website](https://kerrykolosko.com/visualisations/).
  She also shares her knowledge and expertise on her [YouTube channel](https://www.youtube.com/@kerry_kolosko/featured).

* <a id="dave-gibbon">Dave Gibbon</a>. A pioneer of using 3D visualization tools. He is an experienced individual in the data visualization industry, who has provided a comprehensive review of the [PlotlyJS custom visual](https://www.youtube.com/watch?v=mujr5QuR3cc&ab_channel=Akvelon), which you can try following the [link](https://appsource.microsoft.com/en-us/product/power-bi-visuals/akvelon.plotlyjsvisualbyakvelon?exp=ubp8).

* <a id="daniel-marsh-patrick">Daniel Marsh-Patrick</a> is a consultant and producer of Power BI custom visuals from New Zealand.
  He has created numerous visuals of his own, which are available on his [website](https://coacervo.co/). Additionally, you can visit his [GitHub](https://github.com/dm-p) for more information about his visuals and projects.

## Visuals

### Visuals Developed by Akvelon

* [Bubble Chart by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381340) ([source](https://github.com/akvelon/pbicv-bubblechart)) — Bubble Chart by Akvelon provides efficient way to visualize your data that has one numeric dimension and one or two categories. This chart is simplified version of Scatter chart with tightly packed bubbles - this way you can show more categories in a given space. Additionally, Bubble chart allows creating groups of bubbles by providing additional second category field bucket.
* [Custom Calendar by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381179) — Akvelon’s Custom Calendar for Power BI is the best way to view and display daily data from any source.
* [Hierarchy Chart by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381333) — This Power BI add-on is perfect for ranking different departments, jobs, and employees who make up an organization. It can also be used to show family history and visualize genealogy information. If your data can be visualized in a tree structure, the Hierarchy Chart can display it in an easy-to-read format.
* [KPI Chart by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381432) — KPI Chart by Akvelon is a single visualization for illustrating and efficiently analyzing the correlation between two measures and it combines a line chart and a column chart with the same X-axis. Column and line charts show representation of the distribution of numerical data. Additionally, KPI Chart by Akvelon allows showing static and dynamic background KPI regions that can characterize, for example, the level of success before reaching the target.
* [Scatter Chart by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA104381703) — Scatter Chart by Akvelon is similar to other two-dimensional chart visuals and allows you to assess your units using multiple measures - X and Y axes coordinates, point size and saturation. Additionally, it supports rectangle selection - such filtering allows to select multiple points of the scatter within rectangle area. This feature will help you to filter specific cluster within your data and update your report to show information about that specific data points.
* [PlotlyJS by Akvelon](https://appsource.microsoft.com/en-us/product/power-bi-visuals/akvelon.plotlyjsvisualbyakvelon?tab=overview) - The Plotly.js integration combines Plotly.js, Chart Studio and Power BI to provide a comprehensive data visualization experience. It leverages the capabilities of ploty.js to offer a chart editor, empowering users to create and customize over 40 types of charts. This powerful tool enables the creation of various visualizations, ranging from simple Scatter charts to intricate 3D charts, Finance charts, and specialized visuals. You may find review of this visual by one of the independent powerBI technology leaders, such as [Kerry Kolosko](#kerry-kolosko) or [Dave Gibbon](#dave-gibbon)

### MS Open-Source Visuals

Akvelon developers are actively supporting and have contributed to the large list of custom open-source, MIT-licensed visuals and tools, started by Microsoft:

* [**Visuals Tools**](https://github.com/Microsoft/PowerBI-visuals-tools) — Tools for building/packaging Power BI visuals. Every Power BI custom visuals developer uses these tools.

* [**Webpack plugin**](https://github.com/Microsoft/powerbi-visuals-webpack-plugin) - The plugin allows for developing custom visuals by using webpack to build a visual package.

* [Aster](https://github.com/Microsoft/PowerBI-visuals-AsterPlot) — An Aster plot is a twist on a standard donut chart, using a second value to drive sweep angle.
* [Bullet Chart](https://github.com/Microsoft/powerbi-visuals-bulletchart) — A bullet chart that includes four orientations and a few customization options. Use to feature a single measure against a qualitative range.
* [Cartogram](https://github.com/Microsoft/powerbi-visuals-drilldown-cartogram) — Displays a hierarchical map set as a circle for each location, with size/color from specified values.
* [Chiclet Slicer](https://github.com/Microsoft/PowerBI-visuals-ChicletSlicer) — Use this slicer to display image and/or text buttons that act as an in-canvas filter. Define additional properties for the layout & selection to customize this slicer to meet your specific needs.
* [Chord Diagram](https://github.com/Microsoft/powerbi-visuals-chord) — A chord diagram is a graphical method of displaying the interrelationships between data in a matrix.
* [Choropleth](https://github.com/Microsoft/powerbi-visuals-drilldown-choropleth) — Displays a hierarchical map set with each location filled in a color from specified values.
* [Dotplot](https://github.com/Microsoft/powerbi-visuals-dotplot) — A dot plot is used to show a representation of the distribution of frequencies. It is most often used to show counts of an occurrence.
* [Drilldown Player](https://github.com/Microsoft/powerbi-visuals-drilldown-player) — Animates report components like a slicer on autopilot.
* [Dual KPI](https://github.com/Microsoft/powerbi-visuals-dualkpi) — A visual for displaying two correlated KPIs within a single visual.
* [Enhanced Scatter](https://github.com/Microsoft/powerbi-visuals-enhancedscatter) — A few more properties were added to the existing scatter chart visual, including shapes as markers, background image support, and developer crosshairs for positioning elements onto an image background.
* [Force Graph](https://github.com/Microsoft/PowerBI-visuals-ForceGraph) — Allows to visualize the relationship between items, the weightage of the relationship and the flow often brings out the untold insights into limelight, which are otherwise not very evident.
* [Funnel](https://github.com/Microsoft/powerbi-visuals-funnel) — Find outliers in your data, using a funnel plot.
* [Gantt Chart](https://github.com/Microsoft/powerbi-visuals-gantt) — A Gantt chart is a type of bar chart which illustrates a project timeline or schedule.
* [Globe Map](https://github.com/Microsoft/powerbi-visuals-globemap) — A 3D visual using WebGL for plotting locations, with category values displayed as bar heights and heat maps. 
* [Heatmap](https://github.com/Microsoft/powerbi-visuals-heatmap) — Use this custom visual to build a table heat map that can be used to visualise and compare data values in an easy and intuitive way.
* [Histogram](https://github.com/Microsoft/powerbi-visuals-histogram) — A histogram chart plots data ranges into intervals. Useful for estimating density.
* [Line Dot Chart](https://github.com/Microsoft/powerbi-visuals-linedotchart) — The LineDot chart is an animated line chart with fun animated dots. Use the LineDot chart to engage your audience especially in a presentation context.
* [Mekko Chart](https://github.com/Microsoft/powerbi-visuals-mekkochart) — A mix of a 100% stacked column chart and a 100% stacked bar chart combined into one view. Similar to a treemap, the dimensional values are represented by length and width of each rectangle. The width of a column is proportional to the total value of the column.
* [Pulse Chart](https://github.com/Microsoft/powerbi-visuals-pulsechart) — Pulse chart shows a line chart annotated with key events. Each event can be selected to filter and cross highlight other visuals to reveal insights or help tell a story.
* [Radar](https://github.com/Microsoft/PowerBI-visuals-RadarChart) — A simple radar chart supporting multiple measures plotted over a categorical axis. Also known as a web chart, spider chart, or star chart. Use to display performance metrics for quality improvement.
* [Sample Bar Chart](https://github.com/Microsoft/PowerBI-visuals-sampleBarChart) — A sample bar chart visual, used for tutorial purposes.
* [Sample Slicer](https://github.com/Microsoft/powerbi-visuals-sampleslicer) — A sample slicer visual for tutorials, demonstrating the use of the Advanced Filtering API introduced in the version 1.7 of [PowerBI Visuals Tools](https://github.com/Microsoft/PowerBI-visuals-tools).
* [Sankey](https://github.com/Microsoft/powerbi-visuals-sankey) — Type of flow diagram in which the width of the series is in proportion to the quantity of the flow. Use it to find major contributions to an overall flow.
* [Stream Graph](https://github.com/Microsoft/powerbi-visuals-streamgraph) — A stacked area chart with smooth interpolation. Often used to display values over time.
* [Sunburst](https://github.com/Microsoft/powerbi-visuals-sunburst) — Sunburst is a multilevel donut chart, used to visualize hierarchical data, depicted by concentric circles.
* [Timeline](https://github.com/Microsoft/powerbi-visuals-timeline) — Graphical date range selector used as a filtering component in the report canvas.
* [Tornado](https://github.com/Microsoft/PowerBI-visuals-Tornado) — A bar chart with category values listed vertically. Use for comparing the relative importance of a variable between two distinct groups.
* [Word Cloud](https://github.com/Microsoft/PowerBI-visuals-WordCloud) — Word Cloud is a visual representation of word frequency and value. Use it to get instant insight into the most important terms in a set.
* [Charticulator](https://appsource.microsoft.com/en-us/product/power-bi-visuals/WA200002793?tab=Overview) - Charticulator (charticulator.com) is the no-code way to create custom and reusable chart designs. Now you can create a custom chart right within Power BI using the Microsoft Charticulator Visual, either from scratch or using a template.

### Power BI in AppSource 

* [Power BI Visuals in AppSource](https://appsource.microsoft.com/marketplace/apps?product=power-bi-visuals) — Microsoft's marketplace for Power BI visuals.
* [Power BI Dashboards in AppSource](https://appsource.microsoft.com/marketplace/apps?product=power-bi) — Collection of dashboards, integrated with specific applications and services.

## Courses
* **[Akvelon's PowerBI Custom Visual Workshop](https://appsource.microsoft.com/en-us/marketplace/consulting-services/akvelon.custom_visual_workshop)** — In this five-days hands-on online training workshop you will learn how to build a new Power BI Custom Visual. Our Custom Visual developers have experience in creating many types of Power BI visualizations and will help you learn how you can achieve your goals in visualizing your data and take your Power BI reports to the next level.
* [Analyzing and Visualizing Data with Power BI](https://www.edx.org/course/analyzing-visualizing-data-power-bi-microsoft-dat207x-8) — Learn from the Power BI product team at Microsoft with a series of short, lecture-based videos, complete with demos, quizzes, and hands-on labs.
* [Microsoft Power BI - A Complete Introduction](https://www.udemy.com/powerbi-complete-introduction/) — Learn how to use Microsoft's Power BI Tools, including Power BI Desktop, Power BI Service, and PowerBI Developer.
* [Power BI Training](https://support.office.com/en-us/article/training-power-bi-b0d71655-a6a0-4874-8069-ed90f7d5544d) — A 5-minute hands-on video-introduction to Power BI.

## Communities

* [Power BI User Group (PUG)](https://www.pbiusergroup.com) — A user-led, user-driven community of 37,000 Power BI users.
* [Power BI Community](http://community.powerbi.com) — Connect, learn and discuss with business intelligence experts and peers.
* [RADACAD Blog](http://radacad.com/blog) — Blog about various Power BI features and use-cases.

## Tutorials

This section contains tutorials about _using Power BI_. If You are looking for development resources and tutorials, please head to [development section](#development).

* [Power BI Tips and Tricks](https://powerbi.tips) — A large collection of articles about Power BI, DAX queries, visuals, etc.
* [Guy in a Cube](https://guyinacube.com) — Tips & tricks, training, and roundups for Power BI and more!
