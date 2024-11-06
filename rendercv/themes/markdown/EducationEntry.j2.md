<div class='entry education-entry' markdown='1'>

<h1 class='entry-title'>
<<entry.institution>>, ((* if entry.degree *))<<entry.degree>> in ((* endif *))<<entry.area>>
</h1>

<div class="entry-details" style='display: contents;' markdown='1'>
((* if entry.date_string *))
- <<entry.date_string>>
((* endif *))
((* if entry.location *))
- <<entry.location>>
((* endif *))
((* for item in entry.highlights *))
- <<item>>
((* endfor *))
</div>
</div>