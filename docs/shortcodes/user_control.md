**This shortcode will only work with Inactive Logout pro enabled.**

The `[ina_user_controls]` shortcode can be used to allow users to customize the inactive logout idle timeout settings from the frontend. This shortcode enables you to conditionally display the form for users with specific roles, such as `subscriber` or `administrator`..

### Syntax

`[ina_user_controls roles="role1,role2,..."]`

### Parameters

- **roles** (string)  
  A comma-separated list of user roles that can access the settings page. Only users with the specified roles will see the content within the shortcode.

### Example Screenshot

![User Control Settings](../img/user_control.png)

### Usage Examples

#### Example 1: Display Content for Subscribers Only

To show a message only to users with the `subscriber` role:

`[ina_user_controls roles="subscriber"]`

#### Example 2: Display Content for Subscribers and Administrators

To show a message to both `subscriber` and `administrator` roles:

`[ina_user_controls roles="subscriber,administrator"]`

#### Example 3: Display Content for All Users roles.

`[ina_user_controls]`

### Important Notes

- **Role names** should be lowercase and match the role slugs used in WordPress.

