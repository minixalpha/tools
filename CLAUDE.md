# CLAUDE.md

## Git
 - All feature branches should in "claude/"
 - language of commit/issue/mr/comments should be english

## New Tool workflow
 - Every tool should be a single html
 - If a tool needs image assets, place them in `assets/images/`
 - Tool page `<title>` format: `<Tool Name> - Tools`
 - Tool page should include a back link to homepage at the top: `<p><a href="index.html">&larr; Back to Tools</a></p>`
 - After dev a new tool, add an item in:
   - `index.html`: `<li><a href="<tool-file>.html"><tool name></a> - <tool description></li>`
   - `README.md`: `- [<tool name>](<tool-file>.html): <tool description>`
 - Verify in browser: tool page works correctly and index.html link navigates to it
