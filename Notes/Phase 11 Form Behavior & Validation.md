PHASE 11 — FORM BEHAVIOR & VALIDATION

143. "action"

Function: Specifies where the form data is sent after submission.
Example:

<form action="/submit">
    ...
</form>

144. "method"

Function: Specifies how the form data is submitted.
Example:

<form method="post">
    ...
</form>

145. GET vs POST

Function: Defines two common methods for sending form data.
Logic: GET sends data in the URL; POST sends data in the request body.
Example:

<form method="get">
    ...
</form>

<form method="post">
    ...
</form>

146. "required"

Function: Makes a form field mandatory before submission.
Example:

<input type="email" required>

147. "placeholder"

Function: Displays a temporary hint inside an empty form field.
Example:

<input type="text" placeholder="Enter your name">

148. "disabled"

Function: Disables a form control so the user cannot interact with it.
Example:

<input type="text" disabled>

149. "readonly"

Function: Prevents the user from editing a field while allowing its value to remain usable.
Example:

<input type="text" value="Hsan" readonly>

150. "checked"

Function: Makes a checkbox or radio button selected by default.
Example:

<input type="checkbox" checked>

151. "selected"

Function: Makes an option selected by default in a dropdown.
Example:

<select>
    <option>English</option>
    <option selected>Japanese</option>
</select>

152. "min"

Function: Defines the minimum allowed value.
Example:

<input type="number" min="1">

153. "max"

Function: Defines the maximum allowed value.
Example:

<input type="number" max="100">

154. "minlength"

Function: Defines the minimum number of characters allowed.
Example:

<input type="text" minlength="3">

155. "maxlength"

Function: Defines the maximum number of characters allowed.
Example:

<input type="text" maxlength="20">

156. "pattern"

Function: Defines a pattern that the input value must match.
Example:

<input type="text" pattern="[A-Za-z]+">

157. "step"

Function: Defines the allowed intervals between numeric values.
Example:

<input type="number" min="0" max="10" step="2">

158. "autocomplete"

Function: Tells the browser whether and how it may autocomplete a form field.
Example:

<input type="email" autocomplete="email">

159. "multiple"

Function: Allows the user to select multiple values or files.
Example:

<input type="file" multiple>

160. HTML Form Validation

Function: Checks whether submitted form data meets defined requirements.
Logic: HTML can perform basic validation before the form is submitted.
Example:

<input type="email" required>