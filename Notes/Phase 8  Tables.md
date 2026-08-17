PHASE 8 — TABLES

93. "<table>"

Function: Creates a table for structured tabular data.
Logic: Use tables for data, not for webpage layout.
Example:

<table>
    ...
</table>

94. "<tr>"

Function: Defines a table row.
Example:

<tr>
    ...
</tr>

95. "<td>"

Function: Defines a standard data cell in a table.
Example:

<tr>
    <td>HTML</td>
</tr>

96. "<th>"

Function: Defines a header cell that labels a row or column.
Example:

<tr>
    <th>Language</th>
</tr>

97. Table Headers

Function: Identifies what the data in a table row or column represents.
Logic: Use "<th>" for labels and "<td>" for data.
Example:

<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Hsan</td>
        <td>36</td>
    </tr>
</table>

98. "colspan"

Function: Makes a cell span across multiple columns.
Example:

<td colspan="2">Total</td>

99. "rowspan"

Function: Makes a cell span across multiple rows.
Example:

<td rowspan="2">HTML</td>

100. "<caption>"

Function: Provides a title or description for a table.
Example:

<table>
    <caption>Student Scores</caption>
</table>

101. "<thead>"

Function: Groups the header rows of a table.
Example:

<table>
    <thead>
        <tr>
            <th>Name</th>
        </tr>
    </thead>
</table>

102. "<tbody>"

Function: Groups the main data rows of a table.
Example:

<table>
    <tbody>
        <tr>
            <td>Hsan</td>
        </tr>
    </tbody>
</table>

103. "<tfoot>"

Function: Groups footer or summary rows of a table.
Example:

<table>
    <tfoot>
        <tr>
            <td>Total</td>
        </tr>
    </tfoot>
</table>

104. "<colgroup>"

Function: Groups one or more columns for styling or structural purposes.
Example:

<table>
    <colgroup>
        <col>
        <col>
    </colgroup>
</table>

105. "<col>"

Function: Represents one or more columns inside a "<colgroup>".
Example:

<colgroup>
    <col span="2">
</colgroup>

106. Accessible Tables

Function: Makes table data easier to understand for assistive technologies.
Logic: Use "<caption>", "<th>", and appropriate table structure to describe relationships.
Example:

<table>
    <caption>Student Scores</caption>
    <tr>
        <th>Name</th>
        <th>Score</th>
    </tr>
    <tr>
        <td>Hsan</td>
        <td>95</td>
    </tr>
</table>