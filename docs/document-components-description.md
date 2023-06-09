---
hide:
  - navigation
---

# Document components description

Here is a description of the document components in [this document example](./document-example-with-all-components.md).

| Number | Component name | Component type | Notes |
|:---|:---|:---|:---|
| -- | Preview and Edit | buttons | The :material-file-eye: preview and :material-file-edit: edit buttons allow readers to preview the raw Markdown file in GitHub, or submit changes via pull requests. |
| **[01]** | Header image | image | Describes the area on the UI where the action or discussion occurs. |
| **[02]** | Topic title | H1 header | Each document has only one H1 header. This header appears in bold typeface at the top of the right-hand table of contents. Headers include an anchor link. |
| **[03]** | Top area admonition | admonition | This is an optional admonition to alert readers about the feature availability. This admonition has no title. |
| **[04]** | Internal link | link | A link to another document in Status Help or another H2 or H3 header in the same document. |
| **[05]** | Paragraph | text | Paragraphs are limited to a maximum of 60 words. |
| **[06]** | Sentence | text | Sentences are limited to a maximum of 25 words. |
| **[07]**| Info admonition | admonition | There are three types of admonitions, in order of importance: tip, info, and caution. |
| **[08]** | Section title | H2 header | Level-two headers group the different document sections. These headers appear in regular typeface in the right-hand table of contents. Headers include an anchor link. |
| **[09]** | Code format | code | We use a code-format typeface for certain variables to distinguish them from the regular text. For example: `Who holds`, `Is allowed to`, or `In`. |
| **[10]** | External link | link | A link to an external webiste. The link opens in a new tab and includes a trailing icon to inform readers is an external source. |
| **[11]** | Bullet list | list | Bullet lists convery relevant topic information. Procedure-type documents use "What to expect" title, while concept-type documents use "The basics" title. |
| **[12]** | Tabs | tabs | Tabs group information for a particular Status app platform o screen. |
| **[13]** | Interactive UI elements | UI label | Inside procedural steps, elements the user can click or tap use an icon first (if any) and the label name in bold typeface. |
| **[14]** | Second-level bullet lists | list | For steps with multiple options, options are grouped in second-level bullet lists. This element is rarely used and not recommended. |
| **[15]** | Procedural steps | numbered list | Procedures with steps (not tasks) the user should complete in a particular order use numbered lists. The number of steps is limited to six or seven per procedure. |
| **[16]** | Screenshot | image | Screeshosts guide users to the proper screen, and describe UI elements or UI interactions requiring multiple steps. |
| **[17]** | Internal admonition | admonition | When using a tabbed interface, this admonition is visible only selecting one of the tabs. This helps to clarify information for a particular tab only. |
| **[18]**  | Tip admonition | admonition | There are three types of admonitions, in order of importance: tip, info, and caution. |
| **[19]** | Substeps | H3 header | For procedural steps with more than 6-7 steps, we split the procedure into subprocedures. H3 is the minimum header level on our docs. Level-three headers don't appear in the right-hand table of contents. Headers include an anchor link. |
| **[20]** | Procedural steps in a table | numbered list | Some proceral steps go inside tables. :material-triangle: |
| **[21]** | Table | table | Any topic (procedure, concept, or reference) can include a table to summarize different information. |
| **[22]** | Legend | text | A short legend explaining the numbers or figures on the table. |
| **[23]**  | Internal link | A link to antoher part of the same document. Procedural steps may include internal links but never include external links. |
| **[24]**  | Admonition | admonition | In procedures, admonition go after the procedure or screenshot (if any). |
| **[25]**  | Tooltip | tooltip | A short description of a term that pops-up when the user taps (mobile) or hovers over the term (desktop). |
| **[26]**  | Checkboxes | checkbox | Procedures with more or less complex tasks (not steps) the user must complete, not necessarily in an orderly fashion. |
| **[27]** | Caution admonition | admonition | There are three types of admonitions, in order of importance: tip, info, and caution. |
| **[28]** | Common questions | H2, H3 headers | Some documents include this section at the end, with each question in a different H3 header. |
| -- | Date, Authors information | metadata | Articles include the date of last update, or creation date if there is no update. Additionally, articles include the GitHub avatar of up to three different authors. Clicking on the author avatar opens their GitHub profile page. |
| -- | Like, Dislike button | buttons | Provides users a way to send feedback about the document. | 

:material-triangle: Procedural steps inside tables should have the same format as procedural steps outside tables. At this time, we haven't updated the static site generator to achieve this functionality.
