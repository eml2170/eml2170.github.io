---
layout: post
title: Democratic Candidates' Political Positions
---
<html>
<p>I was pretty disappointed by <a href="https://www.nytimes.com/interactive/2020/01/19/opinion/amy-klobuchar-elizabeth-warren-nytimes-endorsement.html">The New York Times' endorsement</a> over the weekend. Warren and Klobuchar basically represent different brands of liberalism, so I think endorsing both is confusing and unhelpful; the point of an endorsement is to take a position. The first primary, in Iowa, is only two weeks away, and I still have no idea who I would vote for. <br><br>
	
Wikipedia has <a href="https://en.wikipedia.org/wiki/Political_positions_of_the_2020_Democratic_Party_presidential_primary_candidates">an overly informative page</a> on <i>all 29</i> Democratic candidates' political positions. To make it easier to read, I filtered it down to the frontrunners. I did this by grabbing the source code and writing some Python (and ad hoc copy pasta) to extract the table elements and strip out unnecessary styling, attributes and whatnot from the source code. There's probably a better way. <br><br>

You can see that overall the candidates agree on most issues, but with differences in health care, economic issues, foreign policy and defense. You can also see a few cases where a single candidate takes the opposite position (Biden's are interesting).

<h2>Education</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Tuition-free public college
</th>
<th>Debt relief for student loans
</th>
<th>Affirmative action
</th>
<th>Universal child care
</th>
<th>Universal pre-kindergarten
</th>
<th>Increase funding for primary and secondary public education
</th></tr><tr>
	<th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td bgcolor="#FFB">Partial<br>[note 3]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr>
<tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 4]</td>
<td bgcolor="#FFB">Partial<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 6]</td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes <br></td>
<td bgcolor="#9F9">Yes <br></td>
<td>?</td>
<td bgcolor="#9F9">Yes <br></td>
<td bgcolor="#9F9">Yes <br></td>
<td>?
</td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 13]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr></table>

<div class="reflist" style="list-style-type: decimal;">
<div class="mw-references-wrap mw-references-columns"><ol class="references">
<li id="cite_note-Debt-free-1"><span class="reference-text">Supports "debt-free" college</span>
</li>
<li id="cite_note-6"><span class="mw-cite-backlink"><b><a href="#cite_ref-6" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">In 2015, Biden supported four years of free public college, but has not stated support for this since launching his 2020 campaign. Since launching his campaign, he has spoken in favor of two years of free community college.</span>
</li>
<li id="cite_note-PSLFP-9"><span class="reference-text">Supports debt forgiveness for teachers and other educators through the Public Service Loan Forgiveness Program</span>
</li>
<li id="cite_note-20"><span class="reference-text">Supports tuition-free college for "lower" and "middle-income families"</span>
</li>
<li id="cite_note-26"><span class="reference-text">Supports loan forgiveness under certain circumstances</span>
</li>
<li id="cite_note-CommunityCollege-30"><span class="reference-text">Supports tuition-free <a href="/wiki/Community_colleges_in_the_United_States" title="Community colleges in the United States">community college</a></span>
</li>
<li id="cite_note-45"><span class="mw-cite-backlink"><b><a href="#cite_ref-45" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports tuition-free <a href="/wiki/Community_colleges_in_the_United_States" title="Community colleges in the United States">community college</a> "for those who can’t afford it"</span>
</li>
<li id="cite_note-48"><span class="mw-cite-backlink"><b><a href="#cite_ref-48" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports tuition-free college "for families in need"</span>
</li>
<li id="cite_note-53"><span class="mw-cite-backlink"><b><a href="#cite_ref-53" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports tuition-free college for students that commit to <a href="/wiki/National_service" title="National service">national service</a> for at least three years</span>
</li>
<li id="cite_note-55"><span class="mw-cite-backlink"><b><a href="#cite_ref-55" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports expanding <a href="/wiki/Pell_Grant" title="Pell Grant">Pell Grants</a></span>
</li>
<li id="cite_note-57"><span class="mw-cite-backlink"><b><a href="#cite_ref-57" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports tuition-free <a href="/wiki/Community_colleges_in_the_United_States" title="Community colleges in the United States">community college</a> or the first two years of public college</span>
</li>
<li id="cite_note-75"><span class="mw-cite-backlink"><b><a href="#cite_ref-75" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Free childcare for poor parents, more affordable for lower and middle-income families through subsidies</span>
</li>
<li id="cite_note-82"><span class="mw-cite-backlink"><b><a href="#cite_ref-82" aria-label="Jump up" title="Jump up">^</a></b></span> <span class="reference-text">Supports tuition-free or "nearly free" <a href="/wiki/Community_colleges_in_the_United_States" title="Community colleges in the United States">community college</a></span>
</li>
</ol></div></div>


<h2>Environmental Issues</h2>

<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Green New Deal
</th>
<th>No Fossil Fuel Money pledge
</th>
<th>Nuclear power to reduce emissions
</th>
<th>Carbon tax
</th>
<th>Paris Agreement
</th>
<th>Ban fracking
</th>
<th>Ban offshore drilling
</th>
<th>Declare climate change a national emergency
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#FFB">Partial<br>[note 3]</td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes <br></td>
<td bgcolor="#9F9">Yes <br></td>
<td>Unclear<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br>[note 8]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial
<p></p>
</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr></table>

<ol><li><b>^</b> Opposed to new offshore drilling operations
</li>
<li>^ <i><b>a</b></i> <i><b>b</b></i> Pushes the decarbonization deadline out two decades from 2030 to 2050
</li>
<li><b>^</b> Will pursue an international ban of offshore drilling in the Arctic
</li>
<li><b>^</b> Would allow fracking, but with tighter oversight.
</li>
<li><b>^</b> Under certain conditions
</li>
<li><b>^</b> Establish a permanent moratorium on all future offshore drilling and Arctic drilling
</li>
<li><b>^</b> Stop new fracking operations
</li>
<li><b>^</b> Seen as a Temporary Solution
</li>
</ol>
<h2>Gun control</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Universal background checks
</th>
<th>Ban assault weapons
</th>
<th>Gun buyback
</th>
<th>Require gun license
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td bgcolor="#F99">No <br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td bgcolor="#9F9">Yes <br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td>Unclear <br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td bgcolor="#9F9">Yes <br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Voluntary <br></td>
<td bgcolor="#9F9">Yes <br></td></tr></table>

<ol><li><b>^</b> Only for assault weapons
</li>
</ol>
<h2>Health care</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Support single-payer healthcare system
</th>
<th>Support public health insurance option
</th>
<th>Eliminate private health insurance
</th>
<th>Import prescription drugs from Canada
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes <br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#FFB">Partial<br></td></tr></table>


<h2>Immigration and border security</h2>

<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Proposed Trump border wall
</th>
<th>Trump travel ban
</th>
<th>Support DACA
</th>
<th>Allow more visa workers
</th>
<th>Demilitarize Mexico-US border
</th>
<th>Invest in ports of entry
</th>
<th>Abolish ICE
</th>
<th>Decriminalize illegal immigration
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br>[<i>citation needed</i>]</td>
<td bgcolor="#F99">No<br></td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Limited<br>[note 1]<br></td></tr></table>

<ol><li>^ <i><b>a</b></i> <i><b>b</b></i> Legal mechanisms, provided by the Immigration and Nationality Act, should remain to combat drug and human trafficking. Other cases would not be criminally prosecuted.
</li>
</ol>
<h2>Technology</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Reinstate net neutrality
</th>
<th>Treat private data as personal property
</th>
<th>CASE Act
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td>Unclear<br></td>
<td>?</td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr></table>

<h2>Economics</h2>

<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Estate tax
</th>
<th>Postal banking
</th>
<th>Reparations for slavery
</th>
<th>Wealth tax
</th>
<th>Breaking up the largest banks
</th>
<th>Support NAFTA
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td>?</td>
<td>?</td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 2]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br></td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td>?
</td></tr></table>

<ol><li><b>^</b> Supports a commission that determines what form reparations could take
</li>
<li>^ <i><b>a</b></i> <i><b>b</b></i> <i><b>c</b></i> <i><b>d</b></i> <i><b>e</b></i> <i><b>f</b></i> <i><b>g</b></i> <i><b>h</b></i> <i><b>i</b></i> Supports H.R. 40
</li>
</ol>

<h2>Labor and welfare issues</h2>

<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Raise minimum wage
</th>
<th>Basic income
</th>
<th>Paid family leave
</th>
<th>Paid sick leave
</th>
<th>Limit right-to-work laws
</th>
<th>Job guarantee
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">$15 <br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">$15 <br></td>
<td bgcolor="#FFB">Partial<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">$15 <br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">$15 <br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">$15 <br></td>
<td bgcolor="#FFB">Open <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br>[note 3]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr></table>

<ol><li><b>^</b> Supports the federal minimum wage being $12 and a $15 minimum wage being implemented in "high-cost cities".
</li>
<li><b>^</b> Proposes a massive expansion of earned income tax credit, which has been described as a related policy proposal to basic income. However, the EITC is not basic income, it is two different welfare models.
</li>
<li><b>^</b> Pushes for a Basic Income as opposed to a livable wage, although Yang states that whether states should increase minimum wage or not depends on economy and budget.
</li>
</ol>
<h2>Foreign policy</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Pardon Julian Assange
</th>
<th>Rejoin the Iran Nuclear Deal
</th>
<th>Recognize Juan Guaidó as interim President of Venezuela
</th>
<th>Two-state solution for the Israeli-Palestinian conflict
</th>
<th>Leveraging Aid to Israel
</th>
<th>Use tariffs against China
</th>
<th>Meet directly with North Korea's Kim Jong-un
</th>
<th>Resume diplomatic relations with Syria's President Bashar al-Assad
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td>Unclear<br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td>Unclear<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td>Unclear<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br>[note 4]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td bgcolor="#F99">No<br>[note 5]</td></tr><tr><th>Andrew Yangn</th><td bgcolor="#9F9">Yes</td><td bgcolor="#F99">No<br></td><td bgcolor="#9F9">Yes<br></td><td bgcolor="#9F9">Yes<br></td><td bgcolor="#9F9">Yes<br></td><td bgcolor="#F99">No<br></td><td bgcolor="#FFB">Temporary <br>[note 6]</td><td bgcolor="#9F9">Yes<br></td><td bgcolor="#FFB">Open<br></td></tr></table>
<ol><li>^ <i><b>a</b></i> <i><b>b</b></i> <i><b>c</b></i> <i><b>d</b></i> <i><b>e</b></i> <i><b>f</b></i> <i><b>g</b></i> <i><b>h</b></i> <i><b>i</b></i> <i><b>j</b></i> <i><b>k</b></i> Only with preconditions
</li>
<li><b>^</b> "[The US should] support measures to hold Bashar al-Assad accountable to the Syrian people."
</li>
<li><b>^</b> "The only way to achieve true security is through diplomacy and negotiation."
</li>
<li><b>^</b> Has called for "international and regional cooperation for free elections in Venezuela".
</li>
<li><b>^</b> "Assad has got to go"
</li>
<li><b>^</b> Tariffs will not be repealed immediately until a deal is made with China
</li>
</ol>
<h2>Defense</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Withdraw troops from Afghanistan
</th>
<th>Intervention in Syria
</th>
<th>Military Intervention in Venezuela
</th>
<th>Intervention in Yemen
</th>
<th>Drone strikes
</th>
<th>Decrease the annual military budget
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">By end of 1st term <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">1st year <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">By end of 1st term <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">By end of 1st term <br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#FFB">Limited <br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">By end of 1st term <br></td>
<td>Unclear<br></td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td>?<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">By end of 1st term<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#F99">No<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td></tr></table>
<h2>Donald Trump
</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Impeachment inquiry on President Trump
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Partial<br></td></tr></table>

<h2>Electoral and institutional reform
</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Abolish the Electoral College
</th>
<th>Abolish the filibuster
</th>
<th>Adoption of IRV/RCV
</th>
<th>Ban voter ID laws
</th>
<th>D.C. statehood
</th>
<th>Puerto Rico statehood
</th>
<th>End felony disenfranchisement after imprisonment
</th>
<th>Expand / reform Supreme Court
</th>
<th>Make Election Day a federal holiday
</th>
<th>Lower voting age to 16
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td>Unclear<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td>?</td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#FFB">Open <br></td>
<td bgcolor="#FFB">Open <br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open<br>[note 3]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br>[note 4]</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open <br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Open <br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br>[note 5]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr></table>

<ol><li><b>^</b> Supports electoral college reform
</li>
<li><b>^</b> Impose term limits for Supreme Court justices, open to expanding the number of justices
</li>
<li><b>^</b> Supports a process of self-determination where Puerto Ricans decide the nature of their relationship with the US
</li>
<li><b>^</b> Impose term limits for Supreme Court justices, opposed to expanding the number of justices
</li>
<li><b>^</b> Impose term limits for Supreme Court justices
</li>
</ol>
<h2>Campaign finance</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>No corporate PAC donations
</th>
<th>Overturn Citizens United
</th>
<th>Publicly funded elections
</th>
<th>Democracy vouchers
</th>
<th>We the People Amendment
</th>
<th>Fundraising from billionaires?
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td>?
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#FFB">Partial<br>[note 2]</td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?
</td></tr></table>

<ol><li><b>^</b> Self-funding campaign
</li>
<li><b>^</b> Accepts contributions from billionaires, does not hold high-dollar fundraisers
</li>
</ol>

<h2>Abortion</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Support right to abortion
</th>
<th>Contraceptive mandate
</th>
<th>Fund Planned Parenthood
</th>
<th>Retain Hyde Amendment
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br>[note 1]</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#F99">No<br></td></tr></table>

<ol><li><b>^</b> Biden formally declared his support for the Hyde amendment. before later dropping his support following controversy
</li>
</ol>
<h2>Criminal justice
</h2>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>End capital punishment
</th>
<th>Legalization of marijuana
</th>
<th>Expunging cannabis conviction records
</th>
<th>End cash bail
</th>
<th>End private prisons
</th>
<th>End mandatory minimum sentencing for nonviolent drug offenses
</th>
<th>Job placement services for released offenders
</th>
<th>Decriminalization of sex work
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 1]</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 3]</td>
<td>?</td>
<td bgcolor="#FFB">Partial<br></td>
<td>?</td>
<td bgcolor="#FFB">Partial<br></td>
<td>?</td>
<td bgcolor="#F99">No<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td bgcolor="#FFB">Open <br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br></td>
<td>?</td>
<td bgcolor="#FFB">Open <br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#FFB">Partial<br>[note 5]</td>
<td bgcolor="#9F9">Yes<br></td>
<td>?</td>
<td>?</td>
<td bgcolor="#FFB">Partial <br></td></tr></table>

<ol><li><b>^</b> Supports decriminalization at federal level, rescheduling marijuana from Schedule I to Schedule II, and allowing "states to continue to make their own choices regarding legalization."
</li>
<li><b>^</b> Supports capital punishment only in limited circumstances
</li>
<li>^ <i><b>a</b></i> <i><b>b</b></i> Supports legalization at the federal level, but believes states should decide at the state level
</li>
<li><b>^</b> Supports seeking the death penalty for convicted terrorists
</li>
<li><b>^</b> Wants to reduce the use of cash bail
</li>
</ol>
<h2>LGBT issues
</h2><table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Equality Act
</th>
<th>Same-sex marriage
</th>
<th>Transgender military service
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td>
<td bgcolor="#9F9">Yes<br></td></tr></table>

<h2>Pledge to support eventual nominee</h2>
<p>Candidates have been encouraged by organisations, namely Indivisible Project and Individual Action, to take a pledge of unity, known as 'We Are Indivisible'. This means supporting the eventual Democratic nominee, should the candidate's own nomination be unsuccessful. The stance of each candidate is stated as follows:</p>
<table><tr><th>Candidate
</th>
<th>Still running?
</th>
<th>Took the pledge
</th></tr><tr><th>Joe Biden
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes
</td></tr><tr><th>Pete Buttigieg
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes
</td></tr><tr><th>Amy Klobuchar
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes
</td></tr><tr><th>Bernie Sanders
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes
</td></tr><tr><th>Elizabeth Warren
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#9F9">Yes
</td></tr><tr><th>Andrew Yang
</th>
<td bgcolor="#9F9">Yes</td>
<td bgcolor="#F99">No<br>[note 1]</td></tr></table>
<ol><li><b>^</b>
 Stated he " - actually signed a similar pledge and would never do anything to increase odds of Trump winning which a 3rd party bid would likely do."
</li></ol>