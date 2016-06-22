#Banana DNtp

To configure this workflow you will need to alter the "viewer" varibles in the "Args and Vars". If you leave viewer unset the system default will be used. Please change the keywords to whatever makes sense or delete unnecessary launchers.

This workflow supports my process, which is,:

1. Use a PDF viewer with good support for annotations to directly highlight, underline and make notes on a papers content. I particularly like Clearview for this, although, Highlights has merits too.

2. Export the notes into a convenient format for editing and expansion of and further comment on the notes already made and embedded into the PDF.

3. Finally, pull together the different notes into a cohesive form.

This helps me with the first two items; providing the following features:

1. Extra shortcuts for launching specialised PDF viewers, with the dp (default), dpp (Preview), dpc (Clearview) and dph (Highlights) keywords.

2. Creation and association (using the URL property of the PDF's record) of markdown files in a subgroup, called 'pdf notes', which is a sibling of the PDF in question. Using the dn keyword.

3. Opening the markdown file via the hyperlink, wherever it has been moved to. Using the dn keyword.

4. Opening markdown with two keywords: dmv and dm. The first, dmv, is intended to open the markdown file with a viewer; Marked 2 for example. The second is intended to open it in an editor; the "viewer" variable is unset so the system default will be used.

The features described in (1) and (4) use the current selection in DNtp to decide which PDF or markdown file to work on. The other two, (2) and (3), do so too but indirectly; the PDF which is associated with the markdown should be selected to open the markdown.
