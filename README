Nebraska election results parser
==================

Use the Google Spreadsheets API to dump live election results from the Nebraska Secretary of State's <a href="http://electionresults.sos.ne.gov/resultsMedia.aspx" target="_blank">website</a> to an HTML table.

<a href="http://www.codywinchester.com/electionresults/" target="_blank">Demo</a>.

Adapted from <a href="http://michelleminkoff.com/2010/11/22/using-google-spreadsheets-as-your-database/" target="_blank">this Michelle Minkoff walkthrough</a>.

Dependencies:
<ul>
<li><a href="http://jquery.com/" target="_blank">jQuery</a></li>
<li><a href="https://github.com/hail2u/jquery.table-filter" target="_blank">jQuery Table Filter</a></li>
<li><a href="http://jqueryui.com/tooltip/" target="_blank">jQuery UI Tooltip</a></li>
<li><a href="https://developers.google.com/chart/image/" target="_blank">Google Image Charts</a></li>
</ul>

Steps:
<ol>
<li>Create a new Google spreadsheet (<a href="https://docs.google.com/spreadsheet/ccc?key=0Ag4MM37uq7FmdFFBQmhnOFVaUWhOaFp5WDB1WngxTVE&usp=sharing" target="_blank">here's the sheet</a> feeding the demo).</li>
<li>In cell A2, use an =importDATA() function to pull in the CSV you want from the Secretary of State's website. In this case, I'm pulling in all of the races, so the formula is =ImportDATA("http://electionresults.sos.ne.gov/resultsCSV.aspx?text=All").</li>
<li>In the empty row above the data, copy-paste the *values* of the existing header row that starts in A2.</li>
<li>Hit the Share button in the upper right-hand corner of your screen and make sure your worksheet is public. Then go to File --> Publish to the Web --> Start Publishing. Copy the spreadsheet key -- you'll find this between "key=" and "&output=" -- mine is 0Ag4MM37uq7FmdFFBQmhnOFVaUWhOaFp5WDB1WngxTVE -- and paste it into the script at the bottom of the html file.</li>
<li>Basically all of the content on the page is created dynamically in the sheets.js file, so that's where you'd want to do most of the tweaking.</li>
</ol>
