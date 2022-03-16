---
---

Congratulations to Richard Hendricks for winning first place in the Wowchemy Prize.

<head>
  <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
  <script type="text/javascript">
    google.charts.load('current', {'packages':['table']});
    google.charts.setOnLoadCallback(drawTable);

    function drawTable() {
      var data = new google.visualization.DataTable();
      data.addColumn('string', 'Name');
      data.addColumn('number', 'Salary');
      data.addColumn('boolean', 'Full Time Employee');
      data.addRows([
        ['Mike',  {v: 10000, f: '$10,000'}, true],
        ['Jim',   {v:8000,   f: '$8,000'},  false],
        ['Alice', {v: 12500, f: '$12,500'}, true],
        ['Bob',   {v: 7000,  f: '$7,000'},  true]
      ]);

      var table = new google.visualization.Table(document.getElementById('table_div'));

      table.draw(data, {showRowNumber: true, width: '100%', height: '100%'});
    }
  </script>
</head>
<body>
  <div id="table_div"></div>
</body>



<!--more-->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.

Sed eu dui nec ligula bibendum dapibus. Nullam imperdiet auctor tortor, vel cursus mauris malesuada non. Quisque ultrices euismod dapibus. Aenean sed gravida risus. Sed nisi tortor, vulputate nec quam non, placerat porta nisl. Nunc varius lobortis urna, condimentum facilisis ipsum molestie eu. Ut molestie eleifend ligula sed dignissim. Duis ut tellus turpis. Praesent tincidunt, nunc sed congue malesuada, mauris enim maximus massa, eget interdum turpis urna et ante. Morbi sem nisl, cursus quis mollis et, interdum luctus augue. Aliquam laoreet, leo et accumsan tincidunt, libero neque aliquet lectus, a ultricies lorem mi a orci.

Mauris dapibus sem vel magna convallis laoreet. Donec in venenatis urna, vitae sodales odio. Praesent tortor diam, varius non luctus nec, bibendum vel est. Quisque id sem enim. Maecenas at est leo. Vestibulum tristique pellentesque ex, blandit placerat nunc eleifend sit amet. Fusce eget lectus bibendum, accumsan mi quis, luctus sem. Etiam vitae nulla scelerisque, eleifend odio in, euismod quam. Etiam porta ullamcorper massa, vitae gravida turpis euismod quis. Mauris sodales sem ac ultrices viverra. In placerat ultrices sapien. Suspendisse eu arcu hendrerit, luctus tortor cursus, maximus dolor. Proin et velit et quam gravida dapibus. Donec blandit justo ut consequat tristique.
