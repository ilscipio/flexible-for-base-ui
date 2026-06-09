Base UI helper with smart completion, auto-import, inline docs, drag-and-drop, live preview, and a full component browser.

We are building the best Base UI development experience for JetBrains IDEs and your feedback is essential. Please [leave a review](https://plugins.jetbrains.com/plugin/32195-flexible-for-base-ui), or reach out at info@ilscipio.com - we want to hear what works, what doesn't, and what you'd like to see next.

## Core Features

### Smart Completion
* **Component name completion** - type `<` in any JSX/TSX file and get all Base UI components and subcomponents
* **Dot-notation support** - complete `Accordion.Root`, `Select.Trigger`, `Dialog.Portal` and all other subcomponents
* **Auto-import** - accepting a completion automatically inserts or updates the `import { ... } from '@base-ui-components/react/...'` statement
* **Works everywhere** - `.tsx`, `.jsx`, `.ts`, and `.js` files

### Hover Documentation
* **Inline docs** - hover over any Base UI component tag or press F1/Ctrl+Q for full documentation
* **Props reference** - see every prop with its type, required/optional status, and default value
* **Subcomponents list** - instantly see all available subcomponents (e.g., Select has Root, Trigger, Value, Icon, Positioner, Popup, Item, and more)
* **Code examples** - typical usage patterns shown directly in the popup
* **One-click navigation** - link to the official base-ui.com documentation for each component

### Component Browser
* **Visual browser** in the right sidebar with all 37 components and 4 utilities
* **Category filtering** - Form/Input, Navigation/Layout, Display/Overlay, Data Display
* **Live search** - filter components by name as you type
* **Detail panel** - click any component to see its description, full props table, subcomponents, and example code
* **Drag and drop** - drag a component from the browser directly into your editor; the import statement is added automatically
* **Copy button** - copy the code snippet to your clipboard with one click

### Live Preview
* **JCEF-based preview** - see a rendered preview of each component in the tool window
* **Theme switching** - toggle between light and dark preview themes
* **Auto-sync** - preview updates when you select a different component

### Gutter Icons
* **Import markers** - icons appear next to Base UI import statements in the editor gutter
* **Quick docs** - click the icon to open the official documentation for that component in your browser

### Settings
* Configure at **Settings > Tools > Flexible For Base UI**
* Toggle individual features: completion, documentation, line markers, live preview
* Master enable/disable switch for the entire plugin

## Supported Components

### Form/Input (15)
Autocomplete, Button, Checkbox, CheckboxGroup, Field, Fieldset, Form, Input, NumberField, Radio, Select, Slider, Switch, Toggle, ToggleGroup

### Navigation/Layout (4)
Collapsible, Menu, NavigationMenu, Toolbar

### Display/Overlay (8)
Accordion, AlertDialog, Dialog, Drawer, Popover, PreviewCard, Toast, Tooltip

### Data Display (6)
Avatar, Meter, Progress, ScrollArea, Separator, Tabs

### Interactive (4)
Combobox, ContextMenu, Menubar, OTPField

### Utilities (4)
CSPProvider, DirectionProvider, mergeProps, useRender

## Getting Started

### Quick Start
1. Install the plugin from JetBrains Marketplace
2. Open a React project with `@base-ui-components/react` in `package.json`
3. Open the **Base UI** tool window from the right sidebar
4. Browse components, drag them into your code, or type `<` in JSX/TSX for completion
5. Hover over any Base UI tag for inline documentation

### Productivity Tips
* **Type `<Acc` + Tab** for instant Accordion completion with auto-import
* **Drag from browser** to insert a full component snippet with import in one motion
* **Hover + click link** to jump straight to base-ui.com docs for any component
* **F1 on a tag** to open the full documentation popup with props and examples
* **Category dropdown** in the browser to narrow down to Form, Navigation, Display, or Data components

### Customization
* **Feature toggles**: Settings > Tools > Flexible For Base UI
* **Line markers**: enable/disable gutter icons next to imports
* **Live preview**: enable/disable the JCEF preview panel

### Supported IDEs
* IntelliJ IDEA Ultimate
* WebStorm
* PhpStorm
* Any JetBrains IDE with JavaScript plugin support

### Requirements
* JetBrains IDE version 2023.3 or later
* JavaScript plugin enabled (bundled with Ultimate/WebStorm/PhpStorm)
* A project using `@base-ui-components/react`

## What's New in 2026.1.0

- Initial release with component browser, smart completion, hover documentation, gutter icons, and drag-and-drop support for all 37 Base UI components and 4 utilities

See [CHANGELOG.md](CHANGELOG.md) for complete details.

## Made by Developers with a Passion for Modern Web Development

The integration is the work of [Ilscipio](https://www.ilscipio.com/):

<p style="text-align:center">
<img src="https://www.ilscipio.com//wp-content/uploads/2018/11/ilscipio_soldier2-2.svg" width="200" alt="The Ilscipio Logo - A roman soldier"/>
</p>

We build developer tools and plugins as part of our technology stack and understand the unique needs of frontend engineers working with modern component libraries. We created this plugin to make Base UI development more intuitive and productive in JetBrains IDEs.

We're sharing this tool with the React community to support the ecosystem's growth and to make accessible component development more approachable.

* Special discounts are available for individual developers and of course for the whole Open Source community.

## Bugs & Feature Requests

If you have any questions, feature requests or stumble upon the occasional bug, come leave us a message at [Ilscipio](https://www.ilscipio.com/)
