<div class='entry publication-entry' markdown='1'>

<h2 class='entry-title'><<entry.title>> ((* if entry.doi *))([<<entry.doi>>](<<entry.doi_url>>))((* elif entry.url *))([<<entry.url>>](<<entry.clean_url>>))((* endif *))
</h2>

<div class="entry-details" style='display: contents;' markdown='1'>
((* if entry.date_string *))
- <<entry.date_string>>
((* endif *))
- <<entry.authors|join(", ")>>
((* if entry.journal *))
- <<entry.journal>>
((* endif *))
((* if entry.location *))
- <<entry.location>>
((* endif *))
((* for item in entry.highlights *))
- <<item>>
((* endfor *))
</div>

</div>