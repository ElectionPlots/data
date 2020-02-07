### Election Plots Data

#### CSV files (relevant fields only)

##### Constituency

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>conID</td>
		<td>Database generated primary key</td>
	</tr>
	<tr>
		<td>conName</td>
		<td>Name of constituency</td>
	</tr>
	<tr>
		<td>ons</td>
		<td>Ordnance survey identifier</td>
	</tr>
</tbody>
</table>

##### ConstituencyResult

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>conID</td>
		<td>Database generated constituency identifier</td>
	</tr>
	<tr>
		<td>electionID</td>
		<td>Database generated constituency identifier</td>
	</tr>
	<tr>
		<td>winningParty</td>
		<td>Winning party short identifier</td>
	</tr>
	<tr>
		<td>headline</td>
		<td>Result as in "GAIN FROM LAB", "HOLD" etc</td>
	</tr>
	<tr>
		<td>majority</td>
		<td>Winning candidate's margin of victory over second place</td>
	</tr>
	<tr>
		<td>electorate</td>
		<td>Registered voters in constituency</td>
	</tr>
	<tr>
		<td>turnout</td>
		<td>Percentage of electorate who voted</td>
	</tr>
	<tr>
		<td>turnoutChange</td>
		<td>Change in percentage of electorate who voted</td>
	</tr>
</tbody>
</table>

##### CandidateResult

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>conID</td>
		<td>Database generated constituency identifier</td>
	</tr>
	<tr>
		<td>electionID</td>
		<td>Database generated constituency identifier</td>
	</tr>
	<tr>
		<td>partyCode</td>
		<td>Short party identifier</td>
	</tr>
	<tr>
		<td>partyName</td>
		<td>Full party name</td>
	</tr>
	<tr>
		<td>candidateName</td>
		<td>Candidate name</td>
	</tr>
	<tr>
		<td>votes</td>
		<td>Votes for candidate</td>
	</tr>
	<tr>
		<td>voteShare</td>
		<td>Percentage share of vote</td>
	</tr>
	<tr>
		<td>voteShareChange</td>
		<td>Change in percentage share of vote</td>
	</tr>
</tbody>
</table>

##### constituency_headline.csv

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>ons</td>
		<td>Constituency identifier</td>
	</tr>
	<tr>
		<td>wp</td>
		<td>Winning party short identifier</td>
	</tr>
	<tr>
		<td>wpp</td>
		<td>Winning party at previous election short identifier</td>
	</tr>
	<tr>
		<td>flash</td>
		<td>Result as in "GAIN FROM LAB", "HOLD" etc</td>
	</tr>
</tbody>
</table>

Source: webscraped from [https://www.bbc.co.uk/news/election/2019/results](https://www.bbc.co.uk/news/election/2019/results). 

##### Age_by_year_data.csv

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>PCON11CD</td>
		<td>Constituency identifier</td>
	</tr>
	<tr>
		<td>Age_year</td>
		<td>Single year of age</td>
	</tr>
	<tr>
		<td>Age_percent</td>
		<td>Percentage of people in the constituency of the given single year of age</td>
	</tr>
</tbody>
</table>

Source: <a href="https://commonslibrary.parliament.uk/local-data/constituency-statistics-population-by-age/" target="_blank">House of Commons Library</a>

##### eureferendum_constituency.csv

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>ons_code</td>
		<td>Constituency identifier</td>
	</tr>
	<tr>
		<td>leave_to_use</td>
		<td>Leave vote as a % of total vote in EU referendum</td>
	</tr>
</tbody>
</table>

Source: <a href="https://commonslibrary.parliament.uk/parliament-and-elections/elections-elections/brexit-votes-by-constituency/" target="_blank">House of Commons Library</a>

##### HoC-2019GE-results-by-constituency.csv

<table>
<thead>
	<tr>
		<th>Column</th>
		<th>Description</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>ons_id</td>
		<td>Constituency identifier</td>
	</tr>
	<tr>
		<td>ons_region_id</td>
		<td>Region identifier</td>
	</tr>
	<tr>
		<td>region_name</td>
		<td>Regions of England plus Scotland, Wales and Northern Ireland</td>	
</tbody>
</table>

Source: <a href="https://researchbriefings.parliament.uk/ResearchBriefing/Summary/CBP-8749" target="_blank">House of Commons Library</a>