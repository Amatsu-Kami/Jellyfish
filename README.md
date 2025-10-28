# Jellyfish

## 📑 Table of Contents

  - [Installation](#installation)
    - [Globally for all users](#globally-for-all-users)
    - [User/Device-Specific Theme (Display Settings)](#userdevice-specific-theme-display-settings)

## Installation

### Globally for all users


To apply a theme globally to all users via the Dashboard:

1.  **Navigate to Dashboard Settings**
    -   Log in as an administrator
    -   Go to **Dashboard** → **General** → **Custom CSS Code**
2.  **Add Import Statement**
    -   In the Custom CSS field, add all the desired `@import` statements:

```css
   @import url("https://cdn.jsdelivr.net/gh/Amatsu-Kami/jellyfish@main/loginPage.css");
   /* Any other imports or custom CSS will go here */
```
3.  **Save Changes**
    -   Click **Save** at the bottom of the page
    -   Refresh your browser to see the changes

### User/Device-Specific Theme (Display Settings)

Individual users can apply the theme to their own account without affecting others:

1.  **Navigate to User Settings**
    -   Click on your profile icon
    -   Go to **Settings** → **Display** → **Custom CSS Code**
2.  **Add Import Statement**
    -   In the Custom CSS field, add your `@import` statement:


```css
   @import url("https://cdn.jsdelivr.net/gh/Amatsu-Kami/jellyfish@main/loginPage.css");
```

3.  **Save and Refresh**
    -   Click **Save**
    -   Refresh the page to apply the theme
