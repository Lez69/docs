---
title: Adding notes to a project board
intro: You can add notes to a project board to serve as task reminders or to add information related to the project board.
versions:
  free-pro-team
  enterprise-server
  github
topics:
  - pull requests
---

**Tips:**
- You can format your note using Markdown syntax. For example, you can use headings, links, task lists, or emoji. For more information, see "[Basic writing and formatting syntax."
- You can drag and drop or use keyboard shortcuts to reorder notes and move them between columns
- Your project board must have at least one column before you can add notes. For more information, see "[Creating a project board]."

When you add a URL for an issue, pull request, or another project board to a note, you'll see a preview in a summary card below your text.

### Adding notes to a project board

1. Navigate to the project board where you want to add notes.
2. In the column you want to add a note to, click edit.
3. Type your note, then click **Add**.

**Tip:** You can reference an issue or pull request in your note by typing its URL in the card.

### Converting a note to an issue

If you've created a note and find that it isn't sufficient for your needs, you can convert it to an issue.

When you convert a note to an issue, the issue is automatically created using the content from the note. The first line of the note will be the issue title and any additional content from the note will be added to the issue description.

**Tip:** You can add content in the body of your note to @mention someone, link to another issue or pull request, and add emoji. These {% data variables.product.prodname_dotcom %} Flavored Markdown features aren't supported within project board notes, but once your note is converted to an issue, they'll appear correctly. For more information on using these features, see "[About writing and formatting on {% data variables.product.prodname_dotcom %}](/articles/about-writing-and-formatting-on-github)

1. Navigate to the note that you want to convert to an issue.
3. Click **Convert to issue**.
4. If the card is on an organization-wide project board, in the drop-down menu, choose the repository you want to add the issue to.
5. Optionally, edit the pre-filled issue title, and type an issue body.
6. Click **Convert to issue**.
7. The note is automatically converted to an issue. In the project board, the new issue card will be in the same location as the previous note.

### Editing and removing a note

1. Navigate to the note that you want to edit or remove.
3. To edit the contents of the note, click **Edit note**.
4. To delete the contents of the notes, click **Delete note**.

### Further reading

- "[About project boards]"
- "[Creating a project board]"
- "[Editing a project board]"
- "[Adding issues and pull requests to a project board]"
