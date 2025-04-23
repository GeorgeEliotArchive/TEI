# TEI Assist
TEI Assist is an open-source tool designed to help users add machine-readable codes to text following standardized TEI guidelines. Currently in development by Dr. Yue Cui for the George Eliot Archive project, this tool enables editors to add tags with a single click, verify codes, and easily correct errors such as duplicates.
For more information, visit https://georgeeliotarchive.github.io/TEI/editor/

Here are the key features: 
1. Automatic Tagging: If you paste a document in the editing panel, and click the paragraph tag `<p>`. it will automatically add a `<p>` tag around the paragraph. Note, you may need to hit `command + z` to make the tags highlighted. 
2. Quick Editing Mode: Select any text in the editing panel and wrap it with the selected tag. The selected text will be shown in the “Tagged Elements” section below. 
3. Apply to All: All selected text is recorded in the “Tagged Elements” section with an “Apply to all” button. Clicking this will tag all occurrences of the selected text. If the first action doesn’t show, clicking again will display it. We are working to resolve this inconvenient bug.
4. Tag Verification: Use the “Verify All Tags” button to fix any double tags in your document.
5. Customizable Appearance: Change the font family and size to suit your preferences.

Future Features(under development)
1. Support for additional tags and automatic header generation.
2. AI-assisted tag generation.
3. A "Quick Deleting Mode" to remove tags from selected text.
