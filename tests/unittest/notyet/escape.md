Write a comment abouth the test here.
*** Parameters: ***
{}
*** Markdown input: ***
`\\`

`\`
*** Output of inspect ***
md_el(:document,[md_par([md_code("\\\\")]), md_par([md_code("\\")])],{},[])
*** Output of to_html ***
<p><code>\\</code></p>

<p><code>\</code></p>
*** Output of to_latex ***
{\colorbox[rgb]{1.00,0.93,1.00}{\tt \char92\char92}}

{\colorbox[rgb]{1.00,0.93,1.00}{\tt \char92}}
*** Output of to_md ***

*** Output of to_s ***

*** EOF ***



	OK!



*** Output of Markdown.pl ***
<p><code>\\</code></p>

<p><code>\</code></p>

*** Output of Markdown.pl (parsed) ***
Error: #<NoMethodError: undefined method `write_children' for <div> ... </>:REXML::Element>
