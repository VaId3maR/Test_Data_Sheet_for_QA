# Test data sheet for QA

> [!NOTE]
> This tool allows you to create and manage structured data sheets for testing purposes. It features editable tabs and rows with export/import functionality via JSON.

### Main Interface Overview
<img width="1920" height="911" alt="Main Interface Overview" src="https://github.com/user-attachments/assets/8e6b683e-aa9d-4b98-b159-cf2b207890d2" />

+ Each section (or "tab") represents a different group of test data.
+ Each row contains detailed information about a field: name, type, required status, examples, boundaries, invalid input, and expected behavior.

### Add a New Section
+ Click the “+ Add new section” button.
+ Enter the section name (e.g., “Login Page”).
+ A new tab will appear.

### Add a New Row
+ Select the tab where you want to add data.
+ Click “+ Add new row”.
+ Fill in the field details. All new rows are editable by default.

### Tooltips for Quick Info
+ Hover over inputs in the Examples, Boundary Values, Invalid Examples, and Expected Behavior columns to see full content as a tooltip.
+ This is useful when content is too long to read at a glance.

### Lock/Unlock Row Editing
+ Click the 🔒 or 🔓 icon in the "Actions" column to toggle editability for that row.
+ Locked rows are read-only to prevent accidental changes.

### Delete Rows or Tabs
+ To delete a row, click the ✖ icon in the "Actions" column and confirm.
+ To delete a section/tab, click the ✖ next to the tab name and confirm.

### Export to JSON
+ Click “📤 Save to JSON” to export your data.
+ A .json file will be downloaded with the full test sheet structure.

### Import from JSON
+ Click “📥 Load from JSON”, then choose a previously saved .json file.
+ Your data will be loaded into the editor automatically.

✅ Best Practices
+ Use separate sections for each screen or feature under test.
+ Hover over cells to reveal full information in tooltips.
+ Lock rows when data entry is complete to avoid accidental edits.
+ Export regularly to avoid data loss.
