
*** Parameters: ***
{}
*** Markdown input: ***
{a}: a
{:b: a}

*** Output of inspect ***
md_el(:document,[
	md_el(:ald,[],{:ald=>[[:ref, "a"]],:ald_id=>"a"},[]),
	md_el(:ald,[],{:ald=>[[:ref, "a"]],:ald_id=>"b"},[])
],{},[])
*** Output of to_html ***

*** Output of to_latex ***

*** Output of to_md ***

*** Output of to_s ***

*** EOF ***



	OK!



*** Output of Markdown.pl ***
<p>{a}: a
{:b: a}</p>

*** Output of Markdown.pl (parsed) ***
Error: #<NoMethodError: undefined method `write_children' for <div> ... </>:REXML::Element>
