# tamui

Tama Denshya UI Kit | Cross-Framework Suite

Why "**tamui**"? - It sounds like **Japanese word** `\_(-_-)_/`

> **Y**ielding elegant reactivity, **o**pen to every framework, **u**nbound by styling dogma, **a**scending beyond convention, **r**ooted in signals, **e**levating interface creation - **g**racefully **a**daptable, **y**et entirely headless.

**tamui** is a modular UI kit built on signal-driven architecture. It gives you the foundation for creating fully reactive components without dictating your design system. Use it as headless primitives, extend it into JSX-styled elements, or even compile it into Web Custom Elements. It is minimal, reactive, and unopinionated - made for developers who want complete control over their interface logic and presentation.

> It means it works in React.

## Figma UI Kit

## CSS

Additional useful styles, whether to include these or not is up to you.

**Reset**
Resets all browser default styles, useful for greater control and to make sure styles won't be affected by browser style changes.

```js
import "@denshya/tamui/styles/reset.css"
```

**Base**
Common styles for all applications.

```js
import "@denshya/tamui/styles/base.css"
```

## Icons

## Color Palette

## Typography

## Formatting

### `Price`

### `Phone`

### `Date`

## UI

_Click on the link to open example._

### Input

| Component               | Description |
| ----------------------- | ----------- |
| [`<Selector>`]()        |             |
| [`<Input>`]()           |             |
| [`<SearchBar>`]()       |             |
| [`<CheckPicker>`]()     |             |
| [`<CheckTreePicker>`]() |             |
| [`<CheckTree>`]()       |             |
| [`<Checkbox>`]()        |             |
| [`<InputNumber>`]()     |             |
| [`<InputPicker>`]()     |             |
| [`<InlineEdit>`]()      |             |
| [`<AdaptiveEdit>`]()    |             |
| [`<Radio>`]()           |             |
| [`<Rate>`]()            |             |
| [`<SelectPicker>`]()    |             |
| [`<TagPicker>`]()       |             |
| [`<TagInput>`]()        |             |
| [`<Toggle>`]()          |             |
| [`<DateInput>`]()       |             |
| [`<DatePicker>`]()      |             |
| [`<DateRangeInput>`]()  |             |
| [`<DateRangePicker>`]() |             |
| [`<TimePicker>`]()      |             |
| [`<TimeRangePicker>`]() |             |
| [`<Textarea>`]()        |             |
| [`<ColorPicker>`]()     |             |
| [`<FileSelector>`]()    |             |

### Data Display

| Component        | Description |
| ---------------- | ----------- |
| [`<Progress>`]() |             |

### Layouts

| Component             | Description |
| --------------------- | ----------- |
| [`<Table>`]()         |             |
| [`<Article>`]()       |             |
| [`<ToastLayout>`]()   |             |
| [`<PopupLayout>`]()   |             |
| [`<DrawerLayout>`]()  |             |
| [`<WhisperLayout>`]() |             |
| [`<PopoverLayout>`]() |             |

### Sections

| Component             | Description                                 |
| --------------------- | ------------------------------------------- |
| [`<UploadSection>`]() |                                             |
| [`<FAQ>`]()           |                                             |
| [`<Accordion>`]()     |                                             |
| [`<Slider>`]()        |                                             |
| [`<Steps>`]()         |                                             |
| [`<Table>`]()         | Regular, Virtualized, Tree, Affix, Editable |
| [`<Timeline>`]()      |                                             |
| [`<Tabs>`]()          |                                             |

### Static

| Component           | Description                                                         |
| ------------------- | ------------------------------------------------------------------- |
| [`<Badge>`]()       |                                                                     |
| [`<Loader>`]()      |                                                                     |
| [`<Notice>`]()      |                                                                     |
| [`<Placeholder>`]() |                                                                     |
| [`<Icon>`]()        |                                                                     |
| [`<Image>`]()       | Displays image, fallbacks when loading or errored, random image     |
| [`<Avatar>`]()      | The same as `Image`, but has placeholder, letter-based and editable |
| [`<Tag>`]()         |                                                                     |
| [`<Video>`]()       |                                                                     |

### Controls

| Component          | Description |
| ------------------ | ----------- |
| [`<Button>`]()     |             |
| [`<Buttons>`]()    |             |
| [`<IconButton>`]() |             |
| [`<Pagination>`]() |             |

### Other

| Component           | Description                           |
| ------------------- | ------------------------------------- |
| [`<Tooltip>`]()     |                                       |
| [`<Overlay>`]()     | A block that goes over other content. |
| [`<Dropdown>`]()    |                                       |
| [`<Breadcrumb>`]()  |                                       |
| [`<ContextMenu>`]() |                                       |
| [`<Expander>`]()    |                                       |

## UX

_Click on the link to open example._

|Behavior|Description|
|--------|-----------|
|Pagination||
|Looped||
|[`MediaQuery`]()||
|[`Breakpoint`]()||
|[`DragDrop`]()||
