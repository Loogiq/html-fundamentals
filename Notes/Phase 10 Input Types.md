PHASE 10 — INPUT TYPES

123. Text Input

Function: Collects single-line text from the user.
Example:

<input type="text" name="username">

124. Password Input

Function: Collects sensitive text while hiding the characters.
Example:

<input type="password" name="password">

125. Email Input

Function: Collects an email address and enables email-specific validation.
Example:

<input type="email" name="email">

126. Number Input

Function: Collects a numeric value.
Example:

<input type="number" name="age">

127. Tel Input

Function: Collects a telephone number.
Example:

<input type="tel" name="phone">

128. URL Input

Function: Collects a URL and enables URL-specific validation.
Example:

<input type="url" name="website">

129. Search Input

Function: Collects search terms.
Example:

<input type="search" name="query">

130. Date Input

Function: Allows the user to select a date.
Example:

<input type="date" name="birthday">

131. Time Input

Function: Allows the user to select a time.
Example:

<input type="time" name="time">

132. Datetime Input

Function: Collects a date and time with a timezone.
Logic: The standard "datetime" input type is obsolete; use "datetime-local" when a local date and time are needed.
Example:

<input type="datetime-local" name="meeting">

133. Month Input

Function: Allows the user to select a month and year.
Example:

<input type="month" name="month">

134. Week Input

Function: Allows the user to select a week and year.
Example:

<input type="week" name="week">

135. Color Input

Function: Allows the user to select a color.
Example:

<input type="color" name="color">

136. Range Input

Function: Allows the user to select a numeric value from a range.
Example:

<input type="range" min="0" max="100">

137. Checkbox

Function: Allows the user to select zero or more options.
Example:

<input type="checkbox" name="language" value="english">

138. Radio Button

Function: Allows the user to select one option from a group.
Logic: Radio buttons with the same "name" belong to the same group.
Example:

<input type="radio" name="gender" value="male">
<input type="radio" name="gender" value="female">

139. File Input

Function: Allows the user to select files from their device.
Example:

<input type="file" name="photo">

140. Hidden Input

Function: Stores a value that is not displayed to the user but can be submitted with the form.
Example:

<input type="hidden" name="user_id" value="123">

141. Submit Input

Function: Creates an input control that submits the form.
Example:

<input type="submit" value="Submit">

142. Reset Input

Function: Resets form controls to their initial values.
Example:

<input type="reset" value="Reset">