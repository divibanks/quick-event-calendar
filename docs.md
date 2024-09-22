# Quick Event Calendar Plugin Documentation

## Description

**Quick Event Calendar** is a simple, performant, and WordPress-integrated event calendar plugin. It allows you to add posts, events, or any custom post type to a flexible, responsive calendar that can be placed in posts, pages, or widgets.

The calendar operates on a single page using AJAX loading, displaying all events (or posts) in a selected month beneath the calendar. It’s designed to be fast and lightweight, with no bloated styles or scripts. You can style your calendar using included themes, including a default and a minimal theme to seamlessly match your WordPress theme's appearance.

### Use Cases

The Quick Event Calendar plugin can be utilized by:

- **Website Owners / Administrators**: Easily display events or custom post types in a calendar format.
- **Event Organizers**: Create an event calendar to showcase upcoming events.
- **Bloggers / Content Creators**: Display content organized by date in a calendar format.
- **Business Owners**: Showcase events, promotions, or special offers visually.
- **Community Organizations**: Publicize upcoming events, meetings, or activities.
- **Personal Websites / Blogs**: Display schedules or milestones in a calendar format.

## Key Features

- **Simple and Performant**: Fast and lightweight, ensuring optimal performance.
- **AJAX Loading**: Provides a smooth user experience by loading events dynamically.
- **Custom Post Type Integration**: Flexibility to display events from any custom post type.
- **Responsive Design**: Seamlessly adapts across different devices and screen sizes.
- **Predefined Themes**: Easily style the calendar to match your WordPress theme.
- **Customizable Colors**: Tailor the appearance with accent colors, event colors, and background colors.

## Installation

1. Go to the WordPress admin dashboard.
2. Navigate to **Plugins > Add New**.
3. Search for **Quick Event Calendar**.
4. Click **Install Now**.
5. Activate the plugin.

## How to Use Quick Event Calendar

1. **Install and Activate**: From the WordPress plugin repository, install and activate the Quick Event Calendar plugin.
2. **Configure Settings**: Go to the plugin settings to configure options like selecting post types, categories, and which posts to display (published, scheduled, or future).
3. **Add Events**: Use the `[qcc-form]` shortcode to display the calendar submission form on any post, page, or widget.
4. **Display the Calendar**: Use the `[qcc-calendar]` shortcode on any post, page, or widget to show the calendar with the selected events.
5. **Customize Appearance**: Choose a predefined theme and adjust colors to match your site’s branding.

## Shortcodes

- Use the `[qcc-calendar]` shortcode in any post, page, or widget to display the calendar.
- Use the `[qcc-form]` shortcode in any post, page, or widget to display the calendar submission form.

## Template Tags

- Use `<?php echo do_shortcode("[qcc-calendar]"); ?>` in any page template to show the calendar.
- Use `<?php echo do_shortcode("[qcc-form]"); ?>` in any page template to show the calendar submission form.

## Help with Styling

To style your calendar, use the included themes. Choose either the default or the minimal theme that matches your current WordPress theme appearance.

### Configuration Options

After installing the plugin, configure the following options:

- Select the desired post type and category (if the post type is ‘post’).
- Choose which posts to show (default should include both published and scheduled/future posts).
- If using custom meta fields, note that the calendar works with preexisting fields; a third-party plugin may be needed to add new fields.
- Pick a predefined theme to match your site.
- Adjust the accent color, event color, and background color for the current day in the Configurator tab.

Once you finish the settings, use the `[qcc-calendar]` shortcode in any post, page, or widget to display the calendar.

## Conclusion

The Quick Event Calendar plugin is an efficient tool for managing and displaying events on your WordPress site. Its simplicity, responsiveness, and customization options make it a versatile choice for a wide range of users. For further assistance, feel free to check the plugin's support forums or documentation.

