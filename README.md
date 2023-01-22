# pivot_SQL
Flattening variances with PIVOT function in SQL
<p dir="auto"><span style="color: rgb(226, 80, 65);">Schemas, Tables, Columns and Values are changed from the original ones to avoid sensitive data being released outside the company.</span></p>
<p dir="auto">Tool used:</p>
<ul dir="auto">
    <li>SQL</li>
</ul>
<p>Created the Query to have a fast view of the Week on Week trend variances.</p>
<p>The first CTE returns the unit summary Week by Week.</p>
<p>The second CTE is created to have the variances taking the previous week&apos;s data with the LEAD Window Function</p>
<p>The third part uses the PIVOT SQL function to flatten the data</p>
<p dir="auto"><br></p>
