---
date: '2018-11-03T05:05:26.530Z'
layout: page
title: Plugins
permalink: /Plugins/
---

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery-sheetrock/1.1.4/dist/sheetrock.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">


<h1>Hey AIESEC!</h1>
On this page you can find some best desing resources for your work!!!
Scroll down to look for more photos,videos,icons,fonts, templates an design guidelines from the list.
<p>Pro Tip: Use Ctrl + f for searching particural stock.</p>

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vStp_zF9I2VkxV6UmnMLYMcq8fxk0vPvh06AIDGQpU9A267Zt_WC-Ee_FTpzJGjzwYcIKXacJLBmuZL/pubhtml?gid=1197189565&amp;single=true&amp;widget=true&amp;headers=false"  style="width:100%; height: 800px; border: none"></iframe>

<script>
var mySpreadsheet = 'https://docs.google.com/spreadsheets/d/1nNebFruy7RCNQ1Kc8xcnsPBF5qW5VRZIqEU4IC3ZjKg/edit?usp=sharing';
$(document).ready(function(){
$('#plugins').sheetrock({
  url: mySpreadsheet,
  query: "select A,B order by L desc",
  fetchSize: 10
});
});
</script>

<table id="plugins" class="table table-condensed table-striped"></table>
