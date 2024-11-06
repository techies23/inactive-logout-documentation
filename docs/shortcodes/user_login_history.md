**This shortcode will only work with Inactive Logout pro enabled.**

The `[ina_user_login_history]` shortcode can be used display the list of login and logout activity for the logged in user.

### Syntax

`[ina_user_login_history enable_logout="no"]`

### Parameters

- **enable_logout** (string | optional)  
  A set of "yes" or "no" - If you set this to "yes" then a logout button would appear in each row. This way user can logout their old sessions or any unwanted sessions.

### Usage Examples

#### Example: Display user login activity logs for logged in user.

To show the list of login, logout activity for a user called "John": 

`[ina_user_login_history]`

#### Example: Display logout button

To show logout button that can trigger different session logouts.

`[ina_user_login_history enable_logout="yes"]`

### Important Notes

- This shortcode will only display the login and logout activity for the logged in user.
- Use this shortcode if you want your users to be able to view their login and logout logs which would be similar to that of the backend.

