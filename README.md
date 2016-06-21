#Banana DNtp

This workflow supports my academic process, which is,:

1. Use a PDF viewer with good support annotations to directly highlight,
   underline and make notes on papers content. I particularly like
   Clearview for this, although, Highlights has its merits too.
2. Export the notes into convenient format for editing and expansion upon and
   further comment.
3. Finally, pull together the different notes into a cohesive form.

This helps me with the first two items; providing the following features:

1. Extra shortcuts for launching specialised PDF viewers, with the *dpp*, *dpc*
   and *dph* keywords.
2. Creation and association (using the URL property of the PDF's record) of
   markdown files in a subgroup, called 'pdf notes', which is a sibling of
   the PDF in question. Using the *dn* keyword.
3. Opening the markdown file via the hyperlink, wherever it has been moved
   to. Using the dn keyword.
4. Opening markdown with two keywords: *dmv* and *dme*. The first, *dmv*, is
   intended to open the markdown file with a views; Marked 2 for example.
   The second is intended to open it in an editor; such as MacVim or
   whatever you like.

For features described in (1) and (4) use the current selection in DNtp to decide which PDF or markdown file to work on. The other two, (2) and (3), do so too but indirectly; the PDF which is associated with the markdown should be selected to open the markdown.  

