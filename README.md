# AlienX – Bringing UI components into your IDE

**AlienX** is a powerful VS Code snippet extension crafted by the **AlienUI** team, designed to speed up your web and app development with ready-to-use UI components and utility snippets.

![Demo Tutorial Video](alienx.gif)

## Features

- 🧩 Multi-Framework Support – Generate UI snippets for Alien UI, AlienUI React, Material UI, Daisy UI in one extension.
- ⚡ Pre-built UI Components – Instantly add Button, Card, Input, Popover, Table, and more across supported libraries.
- 🔄 Web & Mobile Ready – Snippets for both web and mobile (React Native) components.
- 🎨 Multiple Styling Variants – Easily switch between themes like galaxy, earth, and mars (for AlienUI and AlienUI-React) or predefined styles from other UI libraries.
- 🛠️ Flexible & Customizable – Modify generated snippets to match your project’s design system effortlessly.
- ⏳ Save Time & Reduce Boilerplate – Generate full component structures in seconds for rapid development.
- 🎛 Component Selector – Choose from Alien UI, Alien UI React, Material UI, or Daisy UI.

## Installation

1. Open **VS Code**.
2. Go to **Extensions** (or press `Ctrl+Shift+X`).
3. Search for **AlienX**.
4. Click **Install**.
5. Reload VS Code if necessary.

## Usage

Before usage, make sure you've read documentation for the supported UI libraries to see the available component and their variants. Check:

- [AlienUI](https://alienui.vercel.app) for AlienUI React Native documentation.
- [AlienUI-React](https://alienui-react.vercel.app) for AlienUI React documentation.
- [MaterialUI](https://mui.com/material-ui) for MaterialUI documentation.
- [DaisyUI](https://daisyui.com) for DaisyUI documentation.

Create a `.tsx` or `.jsx` file in your project folder and Simply type the prefix for the UI snippet you need, and let AlienX do the rest!

The table below shows the available components and their respective prefix.

**Note:** For AlienUI & AlienUI-React component library, All components have both Javascript and Typescript support but Some reusable components have a seperate Javascript and Typescript(tsx) version such as (Accordion, Alert, Button, Dropdown) for better type safety.

| **Component**  | **Prefix (AlienUI React)** | **Prefix (AlienUI React Native)** | **Prefix MaterialUI** | **Prefix DaisyUI** |
| -------------- | -------------------------- | --------------------------------- | --------------------- | ------------------ |
| `Accordion`    | accordion-web              | accordion-app                     | mui-accordion         | dai-accordion      |
| `Alert`        | alert-web                  | alert-app                         | mui-alert             | dai-alert          |
| `Avatar`       | avatar-web                 | avatar-app                        | mui-avatar            | dai-avatar         |
| `Badge`        | badge-web                  | badge-app                         | mui-badge             | dai-badge          |
| `BreadCrumbs`  | breadcrumb-web             | breadcrumb-app                    | mui-breadcrumb        | dai-breadcrumb     |
| `Button`       | button-web                 | button-app                        | mui-btn               | dai-btn            |
| `Card`         | card-web                   | card-app                          | mui-card              | dai-card           |
| `Carousel`     | carousel-web               | carousel-app                      |                       |                    |
| `Checkbox`     | checkbox-web               | checkbox-app                      | mui-checkbox          | dai-checkbox       |
| `Dropdown`     | dropdown-web               | dropdown-app                      | mui-dropdown          | dai-dropdown       |
| `Input`        | input-web                  | input-app                         | mui-input             | dai-input          |
| `Modal`        | modal-web                  | modal-app                         | mui-modal             | dai-modal          |
| `Navbar`       | nav-web                    |                                   |                       |                    |
| `Notification` | notification-web           | notification-app                  |                       |                    |
| `Pagination`   | pagination-web             | pagination-app                    | mui-pagination        | dai-pagination     |
| `Popover`      | popover-web                | popover-app                       | mui-popover           | dai-popover        |
| `Progress Bar` | progress-web               | progress-app                      | mui-progress          | dai-progress       |
| `Search Bar`   | search-web                 | search-app                        |                       |                    |
| `Spinner`      | spinner-web                | spinner-app                       |                       | dai-spinner        |
| `Switch`       | switch-web                 | switch-app                        | mui-switch            | dai-switch         |
| `Tab`          |                            | tab-app                           | mui-tab               | dai-tab            |
| `Table`        | table-web                  | table-app                         | mui-table             | dai-table          |
| `Toast`        | toast-web                  | toast-app                         |                       |                    |

## Contributing

We welcome contributions from the community!

- **Report bugs** or suggest features via [GitHub Issues](https://github.com/AlienUI-Org/AlienX/issues).

## License

This project is licensed under the **MIT License** – free to use and modify.

## About AlienUI Team

**AlienUI Team** is a modern design and development team focused on creating developer-friendly tools and UI libraries.  
Follow us on [Website](https://alienui.vercel.app) | [Twitter](https://x.com/alienui) | [Linkedin](https://linkedin.com/company/alien-ui) | [GitHub](https://github.com/AlienUI-Org).

_Developed with ❤️ by the AlienUI Team_
