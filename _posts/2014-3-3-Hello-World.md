---
layout: post
title: You're up and running!
frappecharts: true
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.

<div id="chart" style="width: 600px;height:400px;"></div>
<script type="text/javascript">
    let chart = new frappe.Chart( "#chart", { // or DOM element
data: {
  labels: ["A", "B", "C", "D","E"],
  datasets: [
    {
      name: "Main",
      values: [240, 124, 204, 153, 204]
    },
    {
      name: "Franchises",
      values: [12, 116, 60, 113, 111]
    }
  ]
},

barOptions: {
  stacked: 1    // default 0, i.e. adjacent
},
valuesOverPoints: 1,

type: 'bar', // or 'bar', 'line', 'pie', 'percentage'
height: 400,
colors: ['#4286f4', 'light-blue']
});
</script>