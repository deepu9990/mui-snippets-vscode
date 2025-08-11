# MUI Snippets Pro

A comprehensive collection of Material UI (MUI) code snippets for VS Code with full TypeScript support and responsive design patterns.

![VS Code](https://img.shields.io/badge/VS%20Code-1.74+-blue) ![Material UI](https://img.shields.io/badge/Material%20UI-v5+-blue) ![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue) ![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Features

- **80+ Complete Snippets**: All MUI Core components with latest props
- **MUI X Support**: DataGrid, Date Pickers, TreeView, and more
- **Multiple Prefix Formats**: Each snippet supports camelCase, snake_case, and lowercase prefixes
- **TypeScript Ready**: Full TypeScript compatibility with proper type definitions
- **Responsive Patterns**: Built-in responsive design patterns and layouts
- **Accessibility First**: ARIA attributes and accessibility best practices included
- **Theme Integration**: useTheme, styled components, and theme customization snippets
- **Layout Patterns**: Dashboard, forms, navigation, and common UI patterns

## 📦 Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "MUI Snippets Pro"
4. Click Install

## 🎯 Usage

Each snippet supports three different prefix formats:

- **camelCase**: `muiButton`
- **snake_case**: `mui_button`
- **lowercase**: `muibutton`

Simply start typing any of these formats and VS Code will show the available snippets.

### Quick Examples

#### Basic Button
Type: `muiButton` → Press Tab
```tsx
import { Button } from "@mui/material";

<Button
  variant="contained"
  color="primary"
  size="medium"
  onClick={() => handleClick()}
  disabled={false}
>
  Button Text
</Button>
```

#### Responsive Grid
Type: `muiGrid` → Press Tab
```tsx
import { Grid } from "@mui/material";

<Grid container spacing={2}>
  <Grid item xs={12} sm={6} md={4}>
    <!-- Content 1 -->
  </Grid>
  <Grid item xs={12} sm={6} md={4}>
    <!-- Content 2 -->
  </Grid>
  <Grid item xs={12} sm={6} md={4}>
    <!-- Content 3 -->
  </Grid>
</Grid>
```

#### Theme Hook
Type: `muiUseTheme` → Press Tab
```tsx
import { useTheme } from "@mui/material/styles";

const theme = useTheme();
// Access theme.palette.primary.main, theme.spacing(2), etc.
```

## � Available Snippets

### 🧩 Core Components (38 snippets)
| Component | Prefix | Description |
|-----------|--------|-------------|
| Button | `muiButton` | Button with variants and props |
| TextField | `muiTextField` | Text input with validation |
| Card | `muiCard` | Card with content and actions |
| Grid | `muiGrid` | Responsive grid layout |
| Dialog | `muiDialog` | Modal dialog with actions |
| Alert | `muiAlert` | Alert with severity levels |
| Autocomplete | `muiAutocomplete` | Autocomplete with options |
| Tabs | `muiTabs` | Tab navigation |
| Drawer | `muiDrawer` | Side navigation drawer |
| Menu | `muiMenu` | Dropdown menu |
| **And 28 more...** | | Checkbox, Radio, Select, Slider, etc. |

### 🎨 Layout Patterns (8 snippets)
| Pattern | Prefix | Description |
|---------|--------|-------------|
| Dashboard | `muiDashboardLayout` | Complete dashboard layout |
| App Bar | `muiAppBarWithDrawer` | Responsive app bar with drawer |
| Form | `muiCenteredForm` | Centered form layout |
| Footer | `muiStickyFooter` | Sticky footer layout |
| **And 4 more...** | | Sidebar, Card Grid, Stepper, etc. |

### 🎯 Hooks & Utils (13 snippets)
| Hook/Utility | Prefix | Description |
|--------------|--------|-------------|
| Theme | `muiUseTheme` | Access theme object |
| Media Query | `muiUseMediaQuery` | Responsive breakpoints |
| Styled | `muiStyled` | Styled components |
| Theme Toggle | `muiThemeToggler` | Dark/light mode toggle |
| **And 9 more...** | | sx prop, Container, Stack, etc. |

### 📊 MUI X Components (10 snippets)
| Component | Prefix | Description |
|-----------|--------|-------------|
| DataGrid | `muiDataGrid` | Data table with features |
| Date Picker | `muiDatePicker` | Date selection |
| Tree View | `muiTreeView` | Hierarchical tree |
| **And 7 more...** | | Time Picker, Date Range, etc. |

## �🔧 Configuration

The extension works out of the box with no configuration needed. Snippets are available in:
- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)

## 🤝 Contributing

Found a bug or want to request a new snippet? Please open an issue on our [GitHub repository](https://github.com/deepu9990/mui-snippets-vscode/issues).

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🔗 Links

- [Material UI Documentation](https://mui.com/)
- [MUI X Documentation](https://mui.com/x/)
- [GitHub Repository](https://github.com/deepu9990/mui-snippets-vscode)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=deepu9990.mui-snippets-pro)

## � Stats

- **Total Snippets**: 69 unique snippets
- **Total Prefix Variations**: 207 (3 formats per snippet)  
- **Language Support**: JavaScript, JSX, TypeScript, TSX
- **Framework Coverage**: Complete MUI ecosystem

---

**Happy coding with Material UI! 🎉**

*Made with ❤️ for the React/MUI community*
