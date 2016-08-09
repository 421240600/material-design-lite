# mdl-theme

MDL theme is a foundational module that provides theming to MDL components, and also makes it available to
developers as a set of CSS classes.

## Installation

> Note: Installation via the npm registry will be available after alpha.


## Usage

```html
<span class="mdl-theme--primary">
  Some text in the primary color.
</span>

<span class="mdl-theme--accent-bg mdl-theme--text-primary-on-accent">
  Some text on an accent color background.
</span>
```

## CSS classes

There are a number of CSS classes available for taking advantage of theming.

They are derived from the three theme colors in MDL:
- Primary: the primary color used in your application. This applies to a number of UI elements, such as app bars.
- Accent: the accent color used in your application. This applies to UI elements such as FABs.
- Background: the background color for your application. This is the color on top of which your UI is drawn.

### Theme color classes

These classes set either the text color or the background color to one of the theme colors.

| Class                   | Description                                                 |
| ----------------------- | ----------------------------------------------------------- |
| `mdl-theme--primary`    | Sets the text color to the theme primary color.             |
| `mdl-theme--accent`     | Sets the text color to the theme accent color.              |
| `mdl-theme--background` | Sets the background color to the theme background color.    |
| `mdl-theme--primary-bg` | Sets the background color to the theme primary color.       |
| `mdl-theme--accent-bg`  | Sets the background color to the theme accent color.        |

### Text colors for contrast

These classes set the text color to a suitable color to be used on top of a given background. The color to be used
depends on two criteria: the background color (namely, whether it's light or dark) and the text style.

There are five types of text style:
- Primary, used for most text
- Secondary, used for text which is lower in the visual hierarchy
- Hint, used for text hints (such as those in text fields and labels)
- Disabled, used for text in disabled components and content
- Icon, used for icons

The styles below allow you to apply the correct text color for a given text style and background.

#### Text on a theme primary color background

| Class                                     | Description                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| `mdl-theme--text-primary-on-primary`      | Set text to suitable color for primary text on top of a theme primary color background.   |
| `mdl-theme--text-secondary-on-primary`    | Set text to suitable color for secondary text on top of a theme primary color background. |
| `mdl-theme--text-hint-on-primary`         | Set text to suitable color for hint text on top of a theme primary color background.      |
| `mdl-theme--text-disabled-on-primary`     | Set text to suitable color for disabled text on top of a theme primary color background.  |
| `mdl-theme--text-icon-on-primary`         | Set text to suitable color for icons on top of a theme primary color background.          |

#### Text on a theme accent color background

| Class                                     | Description                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| `mdl-theme--text-primary-on-accent`       | Set text to suitable color for primary text on top of a theme accent color background.    |
| `mdl-theme--text-secondary-on-accent`     | Set text to suitable color for secondary text on top of a theme accent color background.  |
| `mdl-theme--text-hint-on-accent`          | Set text to suitable color for hint text on top of a theme accent color background.       |
| `mdl-theme--text-disabled-on-accent`      | Set text to suitable color for disabled text on top of a theme accent color background.   |
| `mdl-theme--text-icon-on-accent`          | Set text to suitable color for icons on top of a theme accent color background.           |

#### Text on the theme background

| Class                                     | Description                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| `mdl-theme--text-primary-on-background`   | Set text to suitable color for primary text on top of the theme background.               |
| `mdl-theme--text-secondary-on-background` | Set text to suitable color for secondary text on top of the theme background.             |
| `mdl-theme--text-hint-on-background`      | Set text to suitable color for hint text on top of the theme background.                  |
| `mdl-theme--text-disabled-on-background`  | Set text to suitable color for disabled text on top of the theme background.              |
| `mdl-theme--text-icon-on-background`      | Set text to suitable color for icons on top of the theme background.                      |

#### Text on a light-colored background (useful for custom backgrounds)

| Class                                     | Description                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| `mdl-theme--text-primary-on-light`        | Set text to suitable color for primary text on top of a light-colored background.         |
| `mdl-theme--text-secondary-on-light`      | Set text to suitable color for secondary text on top of a light-colored background.       |
| `mdl-theme--text-hint-on-light`           | Set text to suitable color for hint text on top of a light-colored background.            |
| `mdl-theme--text-disabled-on-light`       | Set text to suitable color for disabled text on top of a light-colored background.        |
| `mdl-theme--text-icon-on-light`           | Set text to suitable color for icons on top of a light-colored background.                |

#### Text on a dark-colored background (useful for custom backgrounds)

| Class                                     | Description                                                                               |
| ----------------------------------------- | ----------------------------------------------------------------------------------------- |
| `mdl-theme--text-primary-on-dark`         | Set text to suitable color for primary text on top of a dark-colored background.          |
| `mdl-theme--text-secondary-on-dark`       | Set text to suitable color for secondary text on top of a dark-colored background.        |
| `mdl-theme--text-hint-on-dark`            | Set text to suitable color for hint text on top of a dark-colored background.             |
| `mdl-theme--text-disabled-on-dark`        | Set text to suitable color for disabled text on top of a dark-colored background.         |
| `mdl-theme--text-icon-on-dark`            | Set text to suitable color for icons on top of a dark-colored background.                 |
