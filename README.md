# SolidWorks-Macros
This set of SolidWorks macros is developed to automate repetitive tasks involved in creating and managing engineering drawings, particularly focusing on balloons, BOMs, views, and blocks. They streamline the detailing process, improve consistency, and reduce manual work across single and multi-sheet drawings.

The Auto_balloon_&_Auto_BOM_all_sheets.swp macro is designed to automatically apply item balloons and insert a Bill of Materials (BOM) on every sheet in a drawing. It adheres to predefined settings, ensuring uniformity across sheets.

Auto_Block.swp simplifies the placement of predefined blocks such as title blocks or standard symbols. It retrieves block paths directly from the drawing’s custom properties or settings and inserts them into the current sheet.

With 3sheet_Different_Bom.swp, users can automatically generate three distinct BOM types—Top-Level Only, Parts Only, and Indented BOMs—on three separate sheets. This macro is particularly useful for documentation that requires varied BOM structures across different drawing pages. Any remaining sheets default to showing the Indented BOM style.

Auto_Full_BOM(Page 3Local).swp and Auto_Full_BOM.swp both generate a full BOM on a designated sheet, usually Page 3. The macros differ by using either a local or global BOM template, allowing flexibility depending on project standards.

Sheet1_Auto_balloon.swp focuses specifically on Sheet 1, applying balloons to all components based on standard ballooning rules. This is ideal when only the first sheet requires detailed itemization.

Toplevel_Bom.swp generates a Top-Level Only BOM on the active sheet. It filters out subcomponents, listing only top-level items using a specified BOM formatting template.

Auto_View.swp automates the insertion of standard drawing views such as front, top, right, and isometric, based on the model’s reference. It follows a predefined layout to ensure consistent view positioning. (based on current view)

Finally, Auto_View_block.swp combines view creation and block insertion into a single operation, making it efficient for setting up new drawing sheets with standard views and title blocks. (based on current view)
