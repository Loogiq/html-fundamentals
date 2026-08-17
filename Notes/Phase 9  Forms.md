PHASE 9 — FORMS

107. "<form>"

Function: Creates a form for collecting and submitting user input.
Logic: It groups form controls into one submission.
Example:

<form>
    <input type="text">
    <button>Submit</button>
</form>

108. "<input>"

Function: Creates an interactive field for user input.
Example:

<input type="text">

109. "type"

Function: Defines the type and behavior of an "<input>".
Example:

<input type="email">

110. "name"

Function: Gives a form control a name used when submitting its data.
Example:

<input type="text" name="username">

111. "value"

Function: Defines the current or submitted value of a form control.
Example:

<input type="text" value="Hsan">

112. "id"

Function: Gives an element a unique identifier.
Logic: It can be used to connect elements, select them, or target them with CSS/JavaScript.
Example:

<input id="username">

113. "<label>"

Function: Provides a text label for a form control.
Logic: Connect it to an input using "for" and "id".
Example:

<label for="email">Email</label>
<input id="email" type="email">

114. "<button>"

Function: Creates a clickable button for an action.
Example:

<button type="submit">Submit</button>

115. "<textarea>"

Function: Creates a multi-line text input field.
Example:

<textarea name="message"></textarea>

116. "<select>"

Function: Creates a dropdown selection control.
Example:

<select name="language">
    <option>English</option>
    <option>Japanese</option>
</select>

117. "<option>"

Function: Defines an option inside a "<select>" or "<datalist>".
Example:

<select>
    <option>English</option>
    <option>Japanese</option>
</select>

118. "<optgroup>"

Function: Groups related options inside a "<select>".
Example:

<select>
    <optgroup label="Asian Languages">
        <option>Japanese</option>
        <option>Mandarin</option>
    </optgroup>
</select>

119. "<fieldset>"

Function: Groups related form controls together.
Example:

<fieldset>
    <input type="text">
    <input type="email">
</fieldset>

120. "<legend>"

Function: Provides a caption for a "<fieldset>".
Example:

<fieldset>
    <legend>Personal Information</legend>
    <input type="text">
</fieldset>

121. "<datalist>"

Function: Provides predefined suggestions for an input.
Example:

<input list="languages">

<datalist id="languages">
    <option value="English">
    <option value="Japanese">
</datalist>

122. "<output>"

Function: Represents the result of a calculation or user action.
Example:

<output>100</output>